# Input Password

## Overview

`<input>` elements of type "password" provide a way for the user to securely enter a password. The input text is obscured so that it cannot be read, usually by replacing each character with a symbol such as the asterisk \("\*"\) or a dot \("•"\). This character will vary depending on the user agent and OS.

## Usage

![](../../.gitbook/assets/form_input_text%20%281%29.png)![](../../.gitbook/assets/form_input_text%20%281%29.png)

### Accessibility & Best Practices

The label and the text field have to be paired to identify the text field.

`<label>` requires `for` attribute to establish the association with the text field and describe the field. So, users can understand what this text field is for.

The `for` attribute share the same value with its paired `<input>`'s `id` to establish their association.

`id` is required to `<input type="text">`. Ensure its value is unique in the page.

Assistive technologies use this association to identify the field to the user.

## Code

ADD CODE

