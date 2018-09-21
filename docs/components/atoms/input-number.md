# Input Number


## Overview

`<input>` elements of type "number" are used to let the user enter a number. They include built-in validation to reject non-numerical entries. The browser may opt to provide stepper arrows to let the user increase and decrease the value using their mouse or by simply tapping with a fingertip.

Browsers that don't support type "number" fall back to using a standard "text" input.

## Usage

![](../../.gitbook/assets/form_input_number.png)

Number representing the value of the number entered into the input. You can set a default value for the input by including a number inside the value attribute.

Mobile browsers further help with the user experience by showing a special keyboard more suited for entering numbers when the user tries to enter a value.

A number input is considered valid when empty and when a single number is entered, but is otherwise invalid. If the required attribute is used, the input is no longer considered valid when empty.

### Controlling step size

By default, the up and down buttons provided for you to step the number up and down will step the value up and down by 1. You can change this by providing a `step` attribute, which takes as its value a number specifying the step amount.

#### Allowing decimal values

When a number with a decimal, such as "1.0", is entered to the field, it will be considered invalid. If the field requires a value with decimals, set the `step` value.

### Specifying minimum and maximum values

You can use the `min` and `max` attributes to specify a minimum and maximum value that the field can have.

### Accessibility & Best Practices

The label and the text field have to be paired to identify the text field.

`<label>` requires `for` attribute to establish the association with the text field and describe the field. So, users can understand what this text field is for.

The `for` attribute share the same value with its paired `<input>`'s `id` to establish their association.

`id` is required to `<input type="text">`.  Ensure its value is unique in the page.

Assistive technologies use this association to identify the field to the user.


## Code

ADD CODE