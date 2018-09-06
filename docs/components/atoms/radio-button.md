# Radio Button

## Overview

Radio buttons are generally presented in groups (a collection of radio buttons describing a set of related options) when the user must make only one selection out of a group of items. 

Only one radio button in a given group can be selected at the same time, whereas checkboxes let the user turn individual values on and off. Where multiple controls exist, checkboxes allow multiple values to be selected.

This is a unit to present a radio button. Each radio button needs its label to describe what the radio button is for for the user.


### Radio Button States

| Visual | Name | Description |
| :--- | :--- | :--- |
| ADD SCREENSHOT | Checked |  |
| ADD SCREENSHOT | Unchecked |  |


### Accessibility & Best Practices

#### `<label>`

`<label>` describes its associated radio button `<input type="radio">`.

`for` attribute is required to establish the association with the radio button.

It must have the common value to the `id` value of the `<input>`.


A benefit of using labels is that the user can click on the label itself to set focus to the form element. This is useful to some with motor disabilities, particularly when selecting small checkboxes and radio buttons. You can try this by clicking on the word "Name:" above to see focus set to the text box. Clicking adjacent labels provides an easy way to check for proper form labeling.

#### `<input type="radio">`

Its `id` attribute is used to establish the pairing with the `<label>`. So, users can understand what this radio button is for.

Ensure the `id` value is unique in the page to identify the radio button as a unique item and to pair with its `<label>`.

`name` attribute should share a common value between the grouped radio buttons.
