# Checkbox

## Overview

Use checkboxes when looking for yes or no answers.

Checkboxes enable to turn on and off one or more options from a set of alternatives. They can be used as a single option to be turned on or off. If only one option is to be selected in a set of options at a time, radio buttons should be used instead.

They can be presented either checked \(pre-selected\) or unchecked when the page loads.

This is a unit to present a checkbox. Each checkbox needs its label to describe what the checkbox is for for the user.

All options need to be grouped with `name` attribute for their association.

The icon for the label is optional.

### Checkbox States

| Visual | Name | Description |
| :--- | :--- | :--- |
| ADD SCREENSHOT | Checked |  |
| ADD SCREENSHOT | Unchecked |  |

### Accessibility & Best Practices

The `for` attribute of `<label>` and the `id` of `checkbox` pair the elements with the common values for both attributes. Each `id` value in the page has to e unique.

#### `<label>`

`<label>` describes its associated checkbox `<input type="checkbox">`.

`for` attribute is required to establish the association with its paired checkbox.

It must have the common value to the `id` value of the `<input>`.

A benefit of using labels is that the user can click on the label itself to set focus to the form element. This is useful to some with motor disabilities, particularly when selecting small checkboxes and radio buttons. You can try this by clicking on the word "Name:" above to see focus set to the text box. Clicking adjacent labels provides an easy way to check for proper form labeling.

#### `<input type="checkbox">`

Its `id` attribute is used to establish the association with the `<label>`. So, users can understand what this checkbox is for.

Ensure the `id` value is unique in the page to identify the checkbox as a unique item.

`name` attribute should share a common value between the checkboxes as grouped options.

#### `<svg aria-hidden="true">` \(Optional Component\)

This component is optional. It's a decorative element and safely omitted without any concerns for accessibility.

When the icon conveys the same text content as the `<label>`'s, the icon is used for decorative purpose with `aria-hidden="true"`. No text alternative is provided, and assistive technology would ignore the icon.

If it presents additional information to the label text content, the icon should not have `aria-hidden="true"` and provides text alternative through `alt`, visually hidden text, or other methods assistive technology can access.

