---
title: Pronouns
permalink: /patterns/create-a-profile/pronouns/
layout: styleguide
category: Patterns
lead: The pronouns pattern helps users to provide information that will allow them to feel confident they will be addressed with the pronouns they use.
---

## What problem does this solve?
A name or biological sex are not indicative of the pronouns a person uses. Allowing users to specify their pronouns creates a more comfortable environment by removing the potential for frustration and alienation.
 
## When to use this pattern 
Follow this pattern when you are planning on referring to the person using pronouns instead of their name.

## What's the solution
Provide a text entry field that supports a rich array of special characters and accents that allows the user to inform you of their pronouns. If you plan to use this pattern for any automated communications you may need to consider a different approach. 

## Guidance

<div class="grid-row grid-gap-3">
  <div class="tablet:grid-col-5">
    <div class="do-dont">
      <div class="do-dont__do">
      <h3 class="do-dont__heading">What to do</h3>
        <div class="do-dont__content">
          <ul>
            <li>Do understand why you are collecting this information.</li>
            <li>Do provide examples. Many people may not be familiar with the concept of specifying pronouns.</li>
            <li>Do provide an open text field. Language is evolving and forced choice can make a user feel as though they need to fit themselves into a label determined by the form designer.</li>
            <li>Do support a rich array of diacritics, accents, and alternative characters. Do allow both upper and lowercase letters throughout each field.</li>
            <li>Allow users to enter hyphens, apostrophes, and blank spaces in each field.</li>
            <li>Do support long text fields. Allow users to enter up to 128 characters per field, but follow form norms for field display size.</li>
            <li>Do be prepared for a complex answer.</li>
          </ul> 
        </div>
      </div>
    </div>
  </div>
  <div class="tablet:grid-col-5">
    <div class="do-dont__dont">
    <h3 class="do-dont__heading">What not to do</h3>
      <div class="do-dont__content">
          <ul>
            <li>Do not make the field mandatory. While the information can be helpful, there are neutral options that can be used.</li>
            <li>Do not assume pronouns. If a user chooses not to answer, default to the use of they/them.</li>
            <li>Do not overwhelm the user with options. Default to a text entry field to allow user-provided pronouns.</li>
          </ul>
      </div>
    </div>
  </div>
</div>

## Considerations
### Whether you need this data
<b>Confirm you need this information.</b> As with all personal information, consider whether you need to collect it at all, and clearly explain the reason for asking for the information and what will be done to secure the user’s privacy.

<b>Consider how you will be using this information.</b> This pattern best supports verbal communication. If you plan on using the information for automated correspondence you may need to consider a different approach.

<b>If you don't need a controlled vocabulary.</b> Consider allowing for user-provided pronouns with an open-ended text field. Users should also have the ability to opt out of providing this information.

## Usability Guidance

Label Pronouns field:
- Pronouns

## Ingredients

<div class="usa-card-group flex-row margin-top-2">
    <li
    class="usa-card site-component-card grid-col-4 tablet:grid-col-4 margin-bottom-2"
    role="region"
    aria-atomic="true"
    aria-label="Visit Toggle"
    data-meta="Visit Toggle">
        <div class="usa-card__container">
        <header class="usa-card__header">
            <h3 class="usa-card__heading font-lang-lg">Text input</h3>
        </header>
        <div class="usa-card__body font-lang-sm">
            <p>A text input allows users to enter any combination of letters, numbers, or symbols. Text input boxes can span single or multiple lines.</p>
            <a href="/components/text-input/">Visit Text input</a>
        </div>
        </div>
    </li>
</div>

<div class="usa-accordion usa-accordion--bordered site-accordion-code site-component-preview">
  <button class="usa-accordion__button" aria-controls="accordion-preview" aria-expanded="true"><h2 id="pattern-preview">Pattern preview</h2></button>
  <div id="accordion-preview" class="usa-accordion__content">
    {% include patterns/pronouns.html %}
  </div>
</div>
<div class="usa-accordion usa-accordion--bordered site-accordion-code site-component-preview">
  <button class="usa-accordion__button" aria-controls="accordion-code" aria-expanded="false"><h2 id="pattern-code">Pattern code</h2></button>
  <div id="accordion-code" class="usa-accordion__content highlight-code">
    <div class="usa-sr-only">
      <figure class="highlight"><pre><code class="language-html" data-lang="html">{% include patterns/pronouns.html %}</code></pre></figure>
    </div>
    <figure class="highlight"><pre><code class="language-html" data-lang="html">{% highlight html%}{% include patterns/pronouns.html %}{% endhighlight %}</code></pre></figure>
  </div>
</div>

## References
- <a href="https://design.va.gov/content-style-guide/they-their">They, Their</a>, VA.gov
- <a href="https://design-system.service.gov.uk/patterns/gender-or-sex/">Gender or Sex</a>, Gov.uk
- <a href="https://www.digital.govt.nz/standards-and-guidance/design-and-ux/content-design-guidance/inclusive-language/gender-inclusive-language/">Gender-Inclusive Language</a>, Digital.govt.nz
- <a href="https://equity.ubc.ca/resources/gender-diversity/inclusive-forms/">Inclusive Forms</a>, University of British Columbia
- <a href="https://www.keshetonline.org/resources/whats-in-a-pronoun/">What's in a Pronoun</a>, Keshet.org
- <a href="http://www.practicemakesprogress.org/blog/2015/9/18/asking-about-gender-on-online-forms">Asking about gender on online forms</a>, Practice makes progress

## Changelog
- Created 07.01.22