# Error Message

## Overview

Error message is displayed at required fields which don't have any values based on the validation result.

## Usage

![](../../.gitbook/assets/form_input_text_error%20%281%29.png)

### Accessibility & Best Practices

The error message should have an association with the invalid form element, so assistive technologies can clearly address which element the error message is for to the user.

## Code

{% tabs %}
{% tab title="HTML" %}
```text
<label 
  for="text-input"
  class="ma__label ma__label--required ">Text Input as Error</label>
  <div class="ma__error-msg">you did not type something</div>
<input 
  class="ma__input js-is-required" 
  name="text-input" 
  id="text-input" 
  type="text" 
  placeholder="type something" 
  data-type="text"
        required />

<script>
  document.querySelector('.ma__error-msg').classList.add('has-error');
  document.querySelector('.ma__input').classList.add('has-error');
</script>

Text Input as Error
```
{% endtab %}

{% tab title="React" %}
Work in progress
{% endtab %}

{% tab title="Twig PL" %}
```text
{% include "@atoms/03-forms/input-text.twig" %}

<script>
  document.querySelector('.ma__error-msg').classList.add('has-error');
  document.querySelector('.ma__input').classList.add('has-error');
</script>
```
{% endtab %}
{% endtabs %}

