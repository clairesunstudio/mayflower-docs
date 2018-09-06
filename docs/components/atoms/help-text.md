# Help Text

## Overview

Helper text provides supplemental information. It gives context about a field’s input, such as how the input will be used. It should be always visible.

Helper text is different from an error message. 

### Accessibility & Best Practices

Helper text should be used only where needed. It can be a great way of eliminating confusion and possible errors that the user might face when dealing with input field. As a rule of thumb, do not exceed 100 words of explanation.

It should be positioned where its association with the form element to provide information for is clear.

Its placement pattern should be consistent through the site.

Use `aria-describedby` in a control to associate with the `<div>` container for the helper text, then assistive technology understands the relationship between the help text and the form element.

Add `aria-describedby` to the `<input>`, and add the same value of the `aria-describedby` to the `id` value for the `<div>` which contains the helper text.

