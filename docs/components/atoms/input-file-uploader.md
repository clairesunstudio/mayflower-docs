# File Uploader

## Overview

`<input>` elements with `type="file"` let the user choose one or more files from their device storage. Once chosen, the files can be uploaded to a server using form submission, or manipulated using JavaScript and the File API.

Regardless of the user's device or operating system, the file input provides a button that opens up a file picker dialog that allows the user to choose a file.

## Usage

![](../../.gitbook/assets/form_input_file.png)

### Accessibility & Best Practices

The label and the text field have to be paired to identify the text field.

`<label>` requires `for` attribute to establish the association with the text field and describe the field. So, users can understand what this text field is for.

The `for` attribute share the same value with its paired `<input>`'s `id` to establish their association.

`id` is required to `<input type="file">`. Ensure its value is unique in the page.

Assistive technologies use this association to identify the field to the user.

## Code

{% tabs %}
{% tab title="HTML" %}
```text
<label 
  for="optional-input"
  class="ma__label ma__label--optional ">File Upload</label>
<input 
  class="ma__input " 
  name="optional-input" 
  id="optional-input" 
  type="file" 
  data-type="binary"
         />
```
{% endtab %}

{% tab title="React" %}
Work in progress
{% endtab %}

{% tab title="Twig PL" %}

{% endtab %}
{% endtabs %}

