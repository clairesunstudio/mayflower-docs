# Links

## Overview

Links are used to embed actions or pathways to more information in a sentence or on a page.

### Link Variations

| **Visual** | **Name** | **Description & Usage** |
| --- | --- | --- | --- | --- |
| ![](../../.gitbook/assets/link%20%281%29.png)  | [Link](links.md#link) | Use when you are linking just a few words of text or when you are doing inline links. |
| ![](../../.gitbook/assets/decorativelink.png)  | [Decorative Link](links.md#decorative-link) | Used for standalone links that require more emphasis. |
| ![](../../.gitbook/assets/linkchevron.png)  | [Chevron Link](links.md#chevron-link) |  |
| ![](../../.gitbook/assets/primarybutton.png)  | Link Button | Refer to [Link Button](buttons.md#link-button) in the [Buttons](buttons.md) section. |

### Accessibility & Best Practices

The purpose of a link can be determined from the link text alone or from the text combined with programmatically determined content

* The largest errors usually found here are on article preview links or similar where there may be multiple links on a page stating “read more” or other similar repeatable text, this should be avoided.
* Additionally links that are not links but items such as files, e-mail to links and phone numbers should be clearly labeled as such

## Code

### Link

{% tabs %}
{% tab title="HTML" %}
```markup
<a class="ma__content-link" href="#" title="">
  <span>This is a link</span>
</a>
```
{% endtab %}

{% tab title="React" %}

{% endtab %}

{% tab title="Twig PL" %}
[Link in Pattern Lab](https://mayflower.digital.mass.gov/?p=atoms-link)
{% endtab %}
{% endtabs %}

### Decorative Link

{% tabs %}
{% tab title="HTML" %}
```markup
<span class="ma__decorative-link">
  <a href="#" class="js-clickable-link" title="">
    Lorem ipsum dolor sit amet.&nbsp;
    <svg aria-hidden="true"><use xlink:href="#5d998bcb4a89b79d90516730de26bc4b.3"></use></svg><svg xmlns="http://www.w3.org/2000/svg" style="display: none"><symbol xmlns="http://www.w3.org/2000/svg" aria-hidden="true" version="1.1" viewBox="0 0 16 18" id="5d998bcb4a89b79d90516730de26bc4b.3"><path d="M983.721 1887.28L983.721 1887.28L986.423 1890L986.423 1890L986.423 1890L983.721 1892.72L983.721 1892.72L978.318 1898.17L975.617 1895.45L979.115 1891.92L971.443 1891.92L971.443 1888.0700000000002L979.103 1888.0700000000002L975.617 1884.5500000000002L978.318 1881.8300000000002Z " transform="matrix(1,0,0,1,-971,-1881)"/></symbol></svg>
  </a>
</span>
```
{% endtab %}

{% tab title="React" %}
[Decorative Link in Storybook](https://mayflower-react.digital.mass.gov/?knob-href=%23&knob-coloredHeading.text=Title%20text&knob-text=Title%20text&knob-info=&knob-compHeading.title=Title%20text&knob-sidebarHeading.title=Key%20Agencies&knob-pagination.pages=%5B%7B%22active%22%3Afalse%2C%22text%22%3A%221%22%2C%22ariaLabel%22%3A%22Go%20to%20Search%20Results%20Page%201%22%7D%2C%7B%22active%22%3Atrue%2C%22text%22%3A%22spacer%22%7D%2C%7B%22active%22%3Afalse%2C%22text%22%3A%223%22%2C%22ariaLabel%22%3A%22Go%20to%20Search%20Results%20Page%203%22%7D%2C%7B%22active%22%3Atrue%2C%22text%22%3A%224%22%2C%22ariaLabel%22%3A%22Go%20to%20Search%20Results%20Page%204%22%7D%2C%7B%22active%22%3Afalse%2C%22text%22%3A%225%22%2C%22ariaLabel%22%3A%22Go%20to%20Search%20Results%20Page%205%22%7D%2C%7B%22active%22%3Afalse%2C%22text%22%3A%22spacer%22%7D%2C%7B%22active%22%3Afalse%2C%22text%22%3A%2210%22%2C%22ariaLabel%22%3A%22Go%20to%20Search%20Results%20Page%2010%22%7D%5D&knob-compHeading.titleContext=&knob-ButtonSearch.text=Search&knob-pagination.next.text=Next&knob-pagination.prev.text=Previous&knob-HeaderSearch.defaultText=&knob-coloredHeading.color=&knob-compHeading.id=&knob-HeaderSearch.withOrgDropdown=true&knob-level=1&knob-pagination.prev.ariaLabel=Go%20to%20Previous%20Search%20Results%20Page&knob-pagination.next.ariaLabel=Go%20to%20Next%20Search%20Results%20Page&knob-coloredHeading.level=2&knob-ButtonSearch.ariaLabel=Search&knob-tableOptions.feeTable=%7B%22head%22%3A%7B%22rows%22%3A%5B%7B%22rowSpanOffset%22%3Afalse%2C%22cells%22%3A%5B%7B%22heading%22%3Afalse%2C%22colspan%22%3A%22%22%2C%22rowspan%22%3A%22%22%2C%22text%22%3A%22Type%22%7D%2C%7B%22heading%22%3Atrue%2C%22colspan%22%3A%22%22%2C%22rowspan%22%3A%22%22%2C%22text%22%3A%22Name%22%7D%2C%7B%22heading%22%3Atrue%2C%22colspan%22%3A%22%22%2C%22rowspan%22%3A%22%22%2C%22text%22%3A%22Fee%22%7D%5D%7D%5D%7D%2C%22bodies%22%3A%5B%7B%22rows%22%3A%5B%7B%22rowSpanOffset%22%3Afalse%2C%22cells%22%3A%5B%7B%22heading%22%3Atrue%2C%22colspan%22%3A%22%22%2C%22rowspan%22%3A%224%22%2C%22text%22%3A%22Freshwater%20Fishing%22%7D%2C%7B%22heading%22%3Afalse%2C%22colspan%22%3A%22%22%2C%22rowspan%22%3A%22%22%2C%22text%22%3A%22Resident%20Citizen%20or%20Non-Resident%20Fishing%22%7D%2C%7B%22heading%22%3Afalse%2C%22colspan%22%3A%22%22%2C%22rowspan%22%3A%22%22%2C%22text%22%3A%22%2427.50%22%7D%5D%7D%2C%7B%22rowSpanOffset%22%3Atrue%2C%22cells%22%3A%5B%7B%22heading%22%3Afalse%2C%22colspan%22%3A%22%22%2C%22rowspan%22%3A%22%22%2C%22text%22%3A%22Resident%20Citizen%20or%20Non-Resident%20Minor%20Fishing%20%28Age%2015-17%29%22%7D%2C%7B%22heading%22%3Afalse%2C%22colspan%22%3A%22%22%2C%22rowspan%22%3A%22%22%2C%22text%22%3A%22FREE%22%7D%5D%7D%2C%7B%22rowSpanOffset%22%3Atrue%2C%22cells%22%3A%5B%7B%22heading%22%3Afalse%2C%22colspan%22%3A%22%22%2C%22rowspan%22%3A%22%22%2C%22text%22%3A%22Resident%20Citizen%20Fishing%20%28Age%2065-69%29%22%7D%2C%7B%22heading%22%3Afalse%2C%22colspan%22%3A%22%22%2C%22rowspan%22%3A%22%22%2C%22text%22%3A%22%2416.25%22%7D%5D%7D%2C%7B%22rowSpanOffset%22%3Atrue%2C%22cells%22%3A%5B%7B%22heading%22%3Afalse%2C%22colspan%22%3A%22%22%2C%22rowspan%22%3A%22%22%2C%22text%22%3A%22Resident%20Citizen%20Fishing%20%28Aged%2070%20or%20Over%29%22%7D%2C%7B%22heading%22%3Afalse%2C%22colspan%22%3A%22%22%2C%22rowspan%22%3A%22%22%2C%22text%22%3A%22FREE%22%7D%5D%7D%5D%7D%2C%7B%22rows%22%3A%5B%7B%22rowSpanOffset%22%3Afalse%2C%22cells%22%3A%5B%7B%22heading%22%3Atrue%2C%22colspan%22%3A%22%22%2C%22rowspan%22%3A%224%22%2C%22text%22%3A%22Hunting%22%7D%2C%7B%22heading%22%3Afalse%2C%22colspan%22%3A%22%22%2C%22rowspan%22%3A%22%22%2C%22text%22%3A%22Resident%20Citizen%20Hunting%22%7D%2C%7B%22heading%22%3Afalse%2C%22colspan%22%3A%22%22%2C%22rowspan%22%3A%22%22%2C%22text%22%3A%22%2427.50%22%7D%5D%7D%2C%7B%22rowSpanOffset%22%3Atrue%2C%22cells%22%3A%5B%7B%22heading%22%3Afalse%2C%22colspan%22%3A%22%22%2C%22rowspan%22%3A%22%22%2C%22text%22%3A%22Resident%20Citizen%20Hunting%2C%20%28Age%2065-69%29%22%7D%2C%7B%22heading%22%3Afalse%2C%22colspan%22%3A%22%22%2C%22rowspan%22%3A%22%22%2C%22text%22%3A%22%2416.25%22%7D%5D%7D%2C%7B%22rowSpanOffset%22%3Atrue%2C%22cells%22%3A%5B%7B%22heading%22%3Afalse%2C%22colspan%22%3A%22%22%2C%22rowspan%22%3A%22%22%2C%22text%22%3A%22Resident%20and%20Non-Resident%20Citizen%20Hunting%22%7D%2C%7B%22heading%22%3Afalse%2C%22colspan%22%3A%22%22%2C%22rowspan%22%3A%22%22%2C%22text%22%3A%22FREE%22%7D%5D%7D%2C%7B%22rowSpanOffset%22%3Atrue%2C%22cells%22%3A%5B%7B%22heading%22%3Afalse%2C%22colspan%22%3A%22%22%2C%22rowspan%22%3A%22%22%2C%22text%22%3A%22Resident%20Hunting%22%7D%2C%7B%22heading%22%3Afalse%2C%22colspan%22%3A%22%22%2C%22rowspan%22%3A%22%22%2C%22text%22%3A%22%2427.50%22%7D%5D%7D%5D%7D%5D%7D&knob-button.href=https%3A%2F%2Fmass.gov&knob-compHeading.color=&knob-HeaderSearch.placeholder=Search%20Mass.gov&knob-button.text=button&knob-compHeading.level=2&knob-button.info=this%20will%20be%20the%20tooltip%20text%20on%20hover&knob-sidebarHeading.level=2&knob-ButtonWithIcon.text=BUTTON&knob-HeaderSearch.buttonSearch.ariaLabel=Search&knob-HeaderSearch.orgDropdown.inputText=%7B%22boxed%22%3Atrue%2C%22label%22%3Anull%2C%22placeholder%22%3A%22Search%20an%20organization...%22%2C%22id%22%3A%22org-typeahead%22%2C%22options%22%3A%5B%7B%22text%22%3A%22%22%2C%22value%22%3A%22%22%7D%2C%7B%22text%22%3A%22Org%20Having%20%28Parentheses%20in%20the%20Name%29%22%2C%22value%22%3A%22org-having-parentheses-in-the-name%22%7D%2C%7B%22text%22%3A%22Attorney%20General%27s%20Office%22%2C%22value%22%3A%22attorney-general-office%22%7D%2C%7B%22text%22%3A%22Governor%27s%20Office%22%2C%22value%22%3A%22governors-office%22%7D%2C%7B%22text%22%3A%22Bureau%20of%20Environmental%20Health%22%2C%22value%22%3A%22bureau-of-environmental-health%22%7D%2C%7B%22text%22%3A%22Department%20of%20Conservation%20%26%20Recreation%22%2C%22value%22%3A%22department-of-conservation--recreation%22%7D%2C%7B%22text%22%3A%22Department%20of%20Unemployment%20Assistance%22%2C%22value%22%3A%22department-of-unemployment-assistance%22%7D%2C%7B%22text%22%3A%22495%2FMetroWest%20Suburban%20Edge%20Community%20Commission%22%2C%22value%22%3A%22495metrowest-suburban-edge-community-commission%22%7D%2C%7B%22text%22%3A%22Administrative%20Council%20on%20Toxics%20Use%20Reduction%22%2C%22value%22%3A%22administrative-council-on-toxics-use-reduction%22%7D%2C%7B%22text%22%3A%22Advisory%20Committee%20to%20the%20Administrative%20Council%20on%20Toxics%20Use%20Reduction%22%2C%22value%22%3A%22advisory-committee-to-the-administrative-council-on-toxics-use-reduction%22%7D%2C%7B%22text%22%3A%22Alcoholic%20Beverages%20Control%20Commission%22%2C%22value%22%3A%22alcoholic-beverages-control-commission%22%7D%2C%7B%22text%22%3A%22Appeals%20Court%22%2C%22value%22%3A%22appeals-court%22%7D%2C%7B%22text%22%3A%22Architectural%20Access%20Board%22%2C%22value%22%3A%22architectural-access-board%22%7D%2C%7B%22text%22%3A%22Berkshire%20District%20Attorney%20Paul%20J.%20Caccaviello%22%2C%22value%22%3A%22berkshire-district-attorney-paul-j-caccaviello%22%7D%2C%7B%22text%22%3A%22Board%20of%20Registration%20in%20Dentistry%22%2C%22value%22%3A%22board-of-registration-in-dentistry%22%7D%2C%7B%22text%22%3A%22Board%20of%20Registration%20in%20Medicine%22%2C%22value%22%3A%22board-of-registration-in-medicine%22%7D%5D%2C%22selected%22%3A%22%22%7D&knob-button.outline=true&knob-HeaderSearch.orgDropdown.dropdownButton=%7B%22text%22%3A%22All%20Organizations%22%2C%22capitalized%22%3Atrue%7D&knob-linkText=Lorem%20ipsum%20dolor%20sit%20amet&knob-HeaderSearch.buttonSearch.text=Search&knob-ButtonWithIcon.icon=chevron&selectedKind=atoms%2Flinks&selectedStory=DecorativeLink&full=0&addons=1&stories=1&panelRight=0&addonPanel=storybooks%2Fstorybook-addon-knobs)
{% endtab %}

{% tab title="Twig PL" %}
[Decorative Link in Pattern Lab](https://mayflower.digital.mass.gov/?p=atoms-decorative-link)
{% endtab %}
{% endtabs %}

### Chevron Link

{% tabs %}
{% tab title="HTML" %}
```markup
<a class="ma__content-link ma__content-link--chevron" href="#" title="">
  <span>This is a link with a chevron</span>
</a>
```
{% endtab %}

{% tab title="React" %}
Not Available
{% endtab %}

{% tab title="Twig PL" %}
[Chevron Link in Pattern Lab](https://mayflower.digital.mass.gov/?p=atoms-link-chevron)
{% endtab %}
{% endtabs %}

## Style

### Classnames

| **Name** | **scss Modifiers** |
| --- | --- | --- | --- |
| Link | .ma\_\_content-link |
| Decorative Link | .ma\_\_decorative--link |
| Chevron Link | .ma\_\_content-link--chevron |

