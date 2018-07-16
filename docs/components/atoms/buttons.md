---
description: >-
  Buttons express what action will occur when the user clicks or touches it.
  Buttons are used to initialize an action, either in the background or
  foreground of an experience.
---

# Buttons

## Overview

Buttons are vital for creating a smooth conversational flow on the web, and should be used sparingly. Buttons should adhere to standard web practices, and afford for a target area of 45 pixels. They should also appear slightly raised, and not be completely flat. They have a slight shadow on them so they appear clickable. The small buttons are often used on forms and to set filters on listing pages. The large buttons should be used for primary calls to action. Font sizes reduce slightly on mobile.

### Anatomy

Accessibility

Label

## Button Variations

| **Visual** | **Name** | **Description & Usage** |
| --- | --- | --- | --- | --- | --- | --- |
| ![](../../.gitbook/assets/primary-button%20%283%29.gif) | Primary Button | For the principle call to action on the page. |
| ![Example of Secondary Button](../../.gitbook/assets/secondary-button-outline.gif) | Secondary Button | For the secondary action on a page. |
| ![Example of Quaternary Button](../../.gitbook/assets/quarternary-button.gif) | Quaternary Button | For the fourth action on a page. |
|  ![](../../.gitbook/assets/primary-button%20%282%29.gif)  | Small Primary Button | Use when there is not enough space for a regular button size.  |
|  ![](../../.gitbook/assets/primary-button%20%281%29.gif)  | Link Button | Link buttons are used to navigate to another page  |
| ![](../../.gitbook/assets/iconbutton%20%282%29.png) | Icon Button | When words are not enough, icons can be used in buttons to better communicate what the button does. Icons are always paired with text. |



## For Developers

### Primary Button

{% tabs %}
{% tab title="Visual" %}
![Example of Primary Button](../../.gitbook/assets/primary-button.gif)
{% endtab %}

{% tab title="HTML" %}
```text
<button type="button" class="ma__button" aria-label="">Button</button>
```
{% endtab %}

{% tab title="React" %}
[Primary Button in Storybook](http://mayflower-react.digital.mass.gov/?knob-button.info=this%20will%20be%20the%20tooltip%20text%20on%20hover&knob-button.text=button&knob-button.href=&selectedKind=atoms%2Fbuttons&selectedStory=Button&full=0&addons=1&stories=1&panelRight=0&addonPanel=storybook%2Factions%2Factions-panel)
{% endtab %}

{% tab title="Twig PL" %}
[Primary Button in Pattern Lab](https://mayflower.digital.mass.gov/?p=atoms-button)​
{% endtab %}
{% endtabs %}

#### Small Primary Button

{% tabs %}
{% tab title="HTML" %}
```text
<button type="button" class="ma__button ma__button--small  " aria-label="">Button</button>
```
{% endtab %}

{% tab title="React" %}
[Small Primary Button in Storybook](https://mayflower-react.digital.mass.gov/?knob-button.size=small&knob-button.info=this%20will%20be%20the%20tooltip%20text%20on%20hover&knob-button.text=button&knob-button.href=&selectedKind=atoms%2Fbuttons&selectedStory=Button&full=0&addons=1&stories=1&panelRight=0&addonPanel=storybooks%2Fstorybook-addon-knobs)
{% endtab %}

{% tab title="Twig PL" %}
[Small Primary Button in Pattern Lab](https://mayflower.digital.mass.gov/?p=atoms-button-as-small)
{% endtab %}
{% endtabs %}

### Secondary Button

{% tabs %}
{% tab title="Visual" %}
![Example of Secondary Button](../../.gitbook/assets/secondary-button-outline.gif)
{% endtab %}

{% tab title="HTML" %}
```text
<button type="button" class="ma__button ma__button--small ma__button--secondary ma__button--minor" aria-label="">Button</button>
```
{% endtab %}

{% tab title="React" %}
[Secondary Button in Storybook](http://mayflower-react.digital.mass.gov/?knob-button.theme=secondary&knob-button.info=this%20will%20be%20the%20tooltip%20text%20on%20hover&knob-button.text=button&knob-button.href=&knob-button.outline=true&selectedKind=atoms%2Fbuttons&selectedStory=Button&full=0&addons=1&stories=1&panelRight=0&addonPanel=storybooks%2Fstorybook-addon-knobs)
{% endtab %}

{% tab title="Twig PL" %}
[Secondary Button in Pattern Lab](https://mayflower.digital.mass.gov/?p=atoms-button-as-secondary-color)
{% endtab %}
{% endtabs %}

### Quaternary Button

{% tabs %}
{% tab title="Visual" %}
![Example of Quaternary Button](../../.gitbook/assets/quarternary-button.gif)
{% endtab %}

{% tab title="HTML" %}
```text
<button type="button" class="ma__button  ma__button--quaternary " aria-label="">Button</button>
```
{% endtab %}

{% tab title="React" %}
[Quaternary Button in Storybook](http://mayflower-react.digital.mass.gov/?knob-button.theme=quaternary&knob-button.info=this%20will%20be%20the%20tooltip%20text%20on%20hover&knob-button.text=button&knob-button.href=&selectedKind=atoms%2Fbuttons&selectedStory=Button&full=0&addons=1&stories=1&panelRight=0&addonPanel=storybooks%2Fstorybook-addon-knobs)
{% endtab %}

{% tab title="Twig PL" %}
[Quaternary Button in Pattern Lab](https://mayflower.digital.mass.gov/?p=atoms-button-as-quaternary-color)
{% endtab %}
{% endtabs %}

### Link Button

### Icon Button

{% tabs %}
{% tab title="Visual" %}
![Example of Icon Button](../../.gitbook/assets/iconbutton.png)
{% endtab %}

{% tab title="HTML" %}
```text
<button class="ma__button-icon ma__icon-small"><span>BUTTON</span><svg aria-hidden="true" width="20" height="20" viewBox="0 0 59 38" xmlns="http://www.w3.org/2000/svg"><path d="M29.414,37.657 L0.344,8.586 L8.828,0.102 L29.414,20.686 L50,0.1 L58.484,8.585 L29.414,37.657"></path></svg></button>
```
{% endtab %}

{% tab title="React" %}
[Icon Button in Storybook](https://mayflower-react.digital.mass.gov/?knob-ButtonWithIcon.canExpand=true&knob-button.href=&knob-button.text=button&knob-ButtonWithIcon.capitalized=true&knob-button.info=this%20will%20be%20the%20tooltip%20text%20on%20hover&knob-ButtonWithIcon.text=BUTTON&knob-ButtonWithIcon.icon=chevron&knob-ButtonWithIcon.expanded=true&selectedKind=atoms%2Fbuttons&selectedStory=ButtonWithIcon&full=0&addons=1&stories=1&panelRight=0&addonPanel=storybooks%2Fstorybook-addon-knobs)
{% endtab %}

{% tab title="Twig PL" %}
Not Available
{% endtab %}
{% endtabs %}



