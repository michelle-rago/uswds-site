---
permalink: /components/lifecycle/
layout: styleguide
title: USWDS component lifecycle
category: Components
lead: From suggesting new components to fixing bugs, the community contributes to every phase of the lifecycle.
type: docs
subnav:
  - text: Latest updates
    href: '#changelog'
changelog:
  key: docs-component-lifecycle
---

A design system is never “done.”
[Each component has its own lifecycle]({{ site.baseurl }}/components/status):
As our community’s needs evolve, USWDS adds new components, refines existing ones, and retires those that have become obsolete.

There’s a role for you at each stage, and we hope you’ll get involved.

{% assign lifecycle_phases = site.data.lifecycle-phases.phases %}
{% assign phase_number = 0 %}

<ol class="usa-process-list lifecycle-process margin-top-4">
  {% for phase in lifecycle_phases %}
    {% assign phase_number = phase_number | plus: 1 %}

    <li class="usa-process-list__item lifecycle-border--{{ phase.name | downcase  }}">
      <div class="lifecycle-phase">

        <h2 class="lifecycle-phase__heading">
          Phase {{ phase_number }}: {{ phase.name | capitalize }}
        </h2>

        <p class="lifecycle-phase__description">{{ phase.description }}</p>

        {% for subphase in phase.subphases %}
          <div class="lifecycle-phase__subphase">
            <h3 class="lifecycle-phase__subphase-header">
              {{ subphase.name }}
            </h3>
            <!-- {% if subphase.starts_when or subphase.ends_when%}
              <p class="font-lang-xs">
                {% if subphase.starts_when %}
                  <b>Starts when:</b> {{ subphase.starts_when }}<br/>
                {% endif %}
                {% if subphase.ends_when %}
                  <b>Ends when:</b> {{ subphase.ends_when }}<br/>
                {% endif %}
              </p>
            {% endif %} -->
            {% if subphase.description %}
              <p>{{ subphase.description }}</p>
            {% endif %}

            {% if subphase.contribution_method %}
              <b>Contribute by:</b>
              {% if subphase.contribution_method.size == 1 %}
                {% for method in subphase.contribution_method %}
                  {{ method }}
                {% endfor %}
              {% else %}
                <ul>
                  {% for method in subphase.contribution_method %}
                    <li>{{ method }}</li>
                  {% endfor %}
                </ul>
              {% endif %}
            {% endif %}

            {% if subphase.find_more %}
              <p>{{ subphase.find_more }}</p>
            {% endif %}

            {% if subphase.learn_more %}
              <p><b>Learn more:</b> {{ subphase.learn_more }}</p>
            {% endif %}
          </div>
        {% endfor %}

        </div>
      </li>
  {% endfor %}
</ol>