---
title: Establish trust
permalink: /patterns/complex-form/establish-trust/
layout: styleguide
category: Patterns
lead: Help users understand the purpose of a form and the time commitment needed to complete it, feel confident they have what they need, and trust that the information they provide will be used responsibly and safeguarded.  
---

{:.margin-bottom-2}
## What problem does this solve?
Government forms can be very stressful and overwhelming for users to complete. If they are in the midst of a crisis or recovering from trauma, form completion can be very challenging. Respect for their life experiences and time, and reassurances about process and privacy can help reduce user stress and frustration.

## When to use this pattern 
Use this pattern when you are asking users to provide more than basic contact information, especially if you are collecting information that may require disclosing sensitive personal, financial, health, or safety details in a digital form.

## What’s the solution
Provide clear information on why it is necessary to complete the form, what information is needed to successfully complete the form, and how the information will be kept secure. Be as transparent as possible. 

## Guidance

<div class="grid-row grid-gap-3">
  <div class="tablet:grid-col-5">
    <div class="do-dont">
      <div class="do-dont__do">
      <h3 class="do-dont__heading">What to do</h3>
        <div class="do-dont__content">
          <ul>
            <li>Do provide information on why information is being collected and how it is being used. </li>
            <li>Do use <a href="https://www.plainlanguage.gov/">plain language</a>.</li>
            <li>Do use people-first, inclusive language.</li> 
            <li>Do <a href="/component/icon-list/">provide a list</a> of what information your user will need to successfully complete the form.</li>
            <li>Do provide an approximate amount of time it will take the user to complete the form.</li>
            <li>Do allow the user to save and resume if possible. Some users may need to take breaks as they complete a form on a difficult topic.</li>
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
            <li>Do not overwhelm your user. Provide enough background information to communicate the purpose and requirements of the form, but use principles of progressive disclosure to gradually move from simple to more difficult questions.</li>
            <li>Do not create a false sense of urgency. People under stress—even just the stress of filling out a long government form—do not need added pressure.</li>
            <li>Use care to avoid making gender, pronoun, or biological sex assumptions based on previous answers.</li>
            <li>Don’t provide examples that may make some groups feel excluded.</li>
          </ul>
      </div>
    </div>
  </div>
</div>

## Considerations
### Whether you need this data
<strong>Confirm you need this information.</strong> As with all personal information, consider whether you need to collect it at all, and clearly explain the reason for asking for the information and what will be done to secure the user’s privacy.

### User needs
<strong>Lead with the needs voiced from the community.</strong> Nobody knows your users better than your users. Trust is diminished when change is not aligned with needs or values. By considering users’ feedback you can mitigate the risk of alienation. 

## Usability guidance

<strong>Design to support people in difficult times.</strong> People under stress may have poor recall, make frequent errors completing forms, and may not notice the errors they make. They likely have a hard time staying focused, cannot easily categorize objects, and are easily frustrated. Consider <a href="{{ site.baseurl }}/patterns/complex-form/progress-easily/">simple form pages and helpful, no-blame error messaging</a>. Use care when surfacing content that appears based on previous answers. People under stress may already feel exposed and vulnerable. Use calm, straightforward language.

Whenever possible, <strong>allow users to save and resume</strong> long and potentially stress-inducing forms rather than assuming a form will be completed in a single session. Users may be accessing the form on a mobile device, or in a shared public space like a shelter or library where privacy is not guaranteed. They may be distracted by the environment or family members, or discover that additional records are needed. Some users simply need time to work up to answering difficult, potentially painful questions.

<strong>Practice transparency and integrity.</strong> Don’t hide information from your users. Clearly explain what you are collecting and why. By setting the expectations with your user early, users can feel more inclined to trust the process. 

<strong>Be reliable, consistent, and honest.</strong> Reduce the impact of failure with solid design and engineering. Be a good steward of your audience’s data, resources, and time.

## Ingredients

<div class="usa-card-group flex-row margin-top-2">
  <div
  class="usa-card site-component-card grid-col-4 tablet:grid-col-4 margin-bottom-2"
  role="region"
  aria-atomic="true"
  aria-label="Visit icon list component"
  data-meta="Visit icon list component">
    <div class="usa-card__container">
      <header class="usa-card__header">
        <h3 class="usa-card__heading font-lang-lg">Icon list</h3>
      </header>
      <div class="usa-card__body font-lang-sm">
        <p>An icon list reinforces the meaning and visibility of individual list items with a leading icon.</p>
        <a href="/components/icon-list/">Visit Icon list</a>
      </div>
    </div>
  </div>
</div>

<div class="usa-accordion usa-accordion--bordered site-accordion-code site-component-preview">
  <button class="usa-accordion__button" aria-controls="accordion-preview-01" aria-expanded="true"><h2 id="pattern-preview">Pattern preview</h2></button>
  <div id="accordion-preview-01" class="usa-accordion__content">
    {% include patterns/physical-address.html %}
  </div>
</div>
<div class="usa-accordion usa-accordion--bordered site-accordion-code site-component-preview">
  <button class="usa-accordion__button" aria-controls="accordion-code-01" aria-expanded="false"><h2 id="pattern-code">Pattern code</h2></button>
  <div id="accordion-code-01" class="usa-accordion__content highlight-code">
    <div class="usa-sr-only">
       {% highlight text%}{% include patterns/physical-address.html %}{% endhighlight %}
    </div>
    {% highlight html%}{% include patterns/physical-address.html %}{% endhighlight %}
  </div>
</div>

## Related
- <a href="{{ site.baseurl }}/patterns/complex-form/keep-a-record/">Keep a record of submitted information</a> pattern
- <a href="{{ site.baseurl }}/patterns/complex-form/progress-easily/">Progress easily through a form</a> pattern


## References
- Build trust with these UX Guidelines (March 16,2019) Retrieved on July 19, 2022, from [https://uxdesign.cc/build-trust-with-these-ux-guidelines-f3d547bb2014#:~:text=%E2%80%8B%20Increase%20trust%20by%20letting,person%20instead%20of%20a%20robot.](https://uxdesign.cc/build-trust-with-these-ux-guidelines-f3d547bb2014#:~:text=%E2%80%8B%20Increase%20trust%20by%20letting,person%20instead%20of%20a%20robot.)
- Building Trust with Users Through Open Communication and Feedback, (June 13, 2019) Retrieved on July 19, 2022, from [https://digital.gov/2019/06/13/building-trust-with-users-through-open-communication-feedback/](https://digital.gov/2019/06/13/building-trust-with-users-through-open-communication-feedback/)  
- Communicating with and about people with disabilities. (February 1, 2022) Retrieved on July 28, 2022, from [https://www.cdc.gov/ncbddd/disabilityandhealth/materials/factsheets/fs-communicating-with-people.html](https://www.cdc.gov/ncbddd/disabilityandhealth/materials/factsheets/fs-communicating-with-people.html) 
- Design Principles, (n.d.) Retrieved on July 21, 2022 [https://designsystem.digital.gov/design-principles/](https://designsystem.digital.gov/design-principles/)
- Trauma-Informed Computing: Towards Safer Technology Experiences for All. Journal article Association for Computing Machinery in Proceedings of the 2022 CHI Conference on Human Factors in Computing Systems (CHI '22). 2022. Retrieved on July 22, 2022, from [https://doi.org/10.1145/3491102.3517475](https://doi.org/10.1145/3491102.3517475)
- Trust or bust: communicating trustworthiness in web design. (March 6, 1999) Retrieved on July 28, 2022, from [https://www.nngroup.com/articles/communicating-trustworthiness/](https://www.nngroup.com/articles/communicating-trustworthiness/)


## Changelog
- Created July 19, 2022
