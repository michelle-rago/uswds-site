- **Known assistive technology issues.** Testing with people using assistive technology revealed [usability concerns](https://github.com/uswds/uswds-site/issues/1898) that require additional investigation. At this time, consider using a [Select component]({{ site.baseurl }}/components/select) instead of a Combo box. More research and testing is planned to better understand and address these accessibility issues. If you would like to contribute to improving this component, please [join our community]({{ site.baseurl }}/about/community/) and share your feedback.
- **Customize form controls accessibly.** If you customize this component, ensure that it continues to meet the [accessibility requirements that apply to all form controls]({{ site.baseurl }}/components/form).
- **Always use a label.**  Make sure your select element has a label. Don’t replace it with the default menu option (for example, removing the “State” label and just having the menu read “Select a state” by default).
- **Avoid auto-submission.** Don’t use JavaScript to automatically submit the form (or do anything else) when an option is selected. Auto-submission disrupts screen readers because they select each option as they read them.