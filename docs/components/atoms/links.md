# Links

## Overview

Links are used to embed actions or pathways to more information in a sentence or on a page.

### Link Variations

| **Visual** | **Name** | **Description & Usage** |
| :--- | :--- | :--- |
| ![](../../.gitbook/assets/link-1%20%281%29.png) | [Link](links.md#link) | Use when you are linking just a few words of text or when you are doing inline links. |
| ![](../../.gitbook/assets/decorativelink%20%281%29.png) | [Decorative Link](links.md#decorative-link) | Used for standalone links that require more emphasis. |
| ![](../../.gitbook/assets/linkchevron%20%282%29.png) | [Chevron Link](links.md#chevron-link) |  |
| ![](../../.gitbook/assets/primarybutton-4.png) | Link Button | Refer to [Link Button](buttons.md#link-button) in the [Buttons](buttons.md) section. |

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
\[Decorative Link in Storybook\]\([https://mayflower-react.digital.mass.gov/?knob-href=%23&knob-coloredHeading.text=Title text&knob-text=Title text&knob-info=&knob-compHeading.title=Title text&knob-sidebarHeading.title=Key Agencies&knob-pagination.pages=\[{"active"%3Afalse%2C"text"%3A"1"%2C"ariaLabel"%3A"Go to Search Results Page 1"}%2C{"active"%3Atrue%2C"text"%3A"spacer"}%2C{"active"%3Afalse%2C"text"%3A"3"%2C"ariaLabel"%3A"Go to Search Results Page 3"}%2C{"active"%3Atrue%2C"text"%3A"4"%2C"ariaLabel"%3A"Go to Search Results Page 4"}%2C{"active"%3Afalse%2C"text"%3A"5"%2C"ariaLabel"%3A"Go to Search Results Page 5"}%2C{"active"%3Afalse%2C"text"%3A"spacer"}%2C{"active"%3Afalse%2C"text"%3A"10"%2C"ariaLabel"%3A"Go to Search Results Page 10"}\]&knob-compHeading.titleContext=&knob-ButtonSearch.text=Search&knob-pagination.next.text=Next&knob-pagination.prev.text=Previous&knob-HeaderSearch.defaultText=&knob-coloredHeading.color=&knob-compHeading.id=&knob-HeaderSearch.withOrgDropdown=true&knob-level=1&knob-pagination.prev.ariaLabel=Go to Previous Search Results Page&knob-pagination.next.ariaLabel=Go to Next Search Results Page&knob-coloredHeading.level=2&knob-ButtonSearch.ariaLabel=Search&knob-tableOptions.feeTable={"head"%3A{"rows"%3A\[{"rowSpanOffset"%3Afalse%2C"cells"%3A\[{"heading"%3Afalse%2C"colspan"%3A""%2C"rowspan"%3A""%2C"text"%3A"Type"}%2C{"heading"%3Atrue%2C"colspan"%3A""%2C"rowspan"%3A""%2C"text"%3A"Name"}%2C{"heading"%3Atrue%2C"colspan"%3A""%2C"rowspan"%3A""%2C"text"%3A"Fee"}\]}\]}%2C"bodies"%3A\[{"rows"%3A\[{"rowSpanOffset"%3Afalse%2C"cells"%3A\[{"heading"%3Atrue%2C"colspan"%3A""%2C"rowspan"%3A"4"%2C"text"%3A"Freshwater Fishing"}%2C{"heading"%3Afalse%2C"colspan"%3A""%2C"rowspan"%3A""%2C"text"%3A"Resident Citizen or Non-Resident Fishing"}%2C{"heading"%3Afalse%2C"colspan"%3A""%2C"rowspan"%3A""%2C"text"%3A"%2427.50"}\]}%2C{"rowSpanOffset"%3Atrue%2C"cells"%3A\[{"heading"%3Afalse%2C"colspan"%3A""%2C"rowspan"%3A""%2C"text"%3A"Resident Citizen or Non-Resident Minor Fishing \(Age 15-17\)"}%2C{"heading"%3Afalse%2C"colspan"%3A""%2C"rowspan"%3A""%2C"text"%3A"FREE"}\]}%2C{"rowSpanOffset"%3Atrue%2C"cells"%3A\[{"heading"%3Afalse%2C"colspan"%3A""%2C"rowspan"%3A""%2C"text"%3A"Resident Citizen Fishing \(Age 65-69\)"}%2C{"heading"%3Afalse%2C"colspan"%3A""%2C"rowspan"%3A""%2C"text"%3A"%2416.25"}\]}%2C{"rowSpanOffset"%3Atrue%2C"cells"%3A\[{"heading"%3Afalse%2C"colspan"%3A""%2C"rowspan"%3A""%2C"text"%3A"Resident Citizen Fishing \(Aged 70 or Over\)"}%2C{"heading"%3Afalse%2C"colspan"%3A""%2C"rowspan"%3A""%2C"text"%3A"FREE"}\]}\]}%2C{"rows"%3A\[{"rowSpanOffset"%3Afalse%2C"cells"%3A\[{"heading"%3Atrue%2C"colspan"%3A""%2C"rowspan"%3A"4"%2C"text"%3A"Hunting"}%2C{"heading"%3Afalse%2C"colspan"%3A""%2C"rowspan"%3A""%2C"text"%3A"Resident Citizen Hunting"}%2C{"heading"%3Afalse%2C"colspan"%3A""%2C"rowspan"%3A""%2C"text"%3A"%2427.50"}\]}%2C{"rowSpanOffset"%3Atrue%2C"cells"%3A\[{"heading"%3Afalse%2C"colspan"%3A""%2C"rowspan"%3A""%2C"text"%3A"Resident Citizen Hunting%2C \(Age 65-69\)"}%2C{"heading"%3Afalse%2C"colspan"%3A""%2C"rowspan"%3A""%2C"text"%3A"%2416.25"}\]}%2C{"rowSpanOffset"%3Atrue%2C"cells"%3A\[{"heading"%3Afalse%2C"colspan"%3A""%2C"rowspan"%3A""%2C"text"%3A"Resident and Non-Resident Citizen Hunting"}%2C{"heading"%3Afalse%2C"colspan"%3A""%2C"rowspan"%3A""%2C"text"%3A"FREE"}\]}%2C{"rowSpanOffset"%3Atrue%2C"cells"%3A\[{"heading"%3Afalse%2C"colspan"%3A""%2C"rowspan"%3A""%2C"text"%3A"Resident Hunting"}%2C{"heading"%3Afalse%2C"colspan"%3A""%2C"rowspan"%3A""%2C"text"%3A"%2427.50"}\]}\]}\]}&knob-button.href=https%3A%2F%2Fmass.gov&knob-compHeading.color=&knob-HeaderSearch.placeholder=Search Mass.gov&knob-button.text=button&knob-compHeading.level=2&knob-button.info=this will be the tooltip text on hover&knob-sidebarHeading.level=2&knob-ButtonWithIcon.text=BUTTON&knob-HeaderSearch.buttonSearch.ariaLabel=Search&knob-HeaderSearch.orgDropdown.inputText={"boxed"%3Atrue%2C"label"%3Anull%2C"placeholder"%3A"Search an organization..."%2C"id"%3A"org-typeahead"%2C"options"%3A\[{"text"%3A""%2C"value"%3A""}%2C{"text"%3A"Org Having \(Parentheses in the Name\)"%2C"value"%3A"org-having-parentheses-in-the-name"}%2C{"text"%3A"Attorney General's Office"%2C"value"%3A"attorney-general-office"}%2C{"text"%3A"Governor's Office"%2C"value"%3A"governors-office"}%2C{"text"%3A"Bureau of Environmental Health"%2C"value"%3A"bureau-of-environmental-health"}%2C{"text"%3A"Department of Conservation %26 Recreation"%2C"value"%3A"department-of-conservation--recreation"}%2C{"text"%3A"Department of Unemployment Assistance"%2C"value"%3A"department-of-unemployment-assistance"}%2C{"text"%3A"495%2FMetroWest Suburban Edge Community Commission"%2C"value"%3A"495metrowest-suburban-edge-community-commission"}%2C{"text"%3A"Administrative Council on Toxics Use Reduction"%2C"value"%3A"administrative-council-on-toxics-use-reduction"}%2C{"text"%3A"Advisory Committee to the Administrative Council on Toxics Use Reduction"%2C"value"%3A"advisory-committee-to-the-administrative-council-on-toxics-use-reduction"}%2C{"text"%3A"Alcoholic Beverages Control Commission"%2C"value"%3A"alcoholic-beverages-control-commission"}%2C{"text"%3A"Appeals Court"%2C"value"%3A"appeals-court"}%2C{"text"%3A"Architectural Access Board"%2C"value"%3A"architectural-access-board"}%2C{"text"%3A"Berkshire District Attorney Paul J. Caccaviello"%2C"value"%3A"berkshire-district-attorney-paul-j-caccaviello"}%2C{"text"%3A"Board of Registration in Dentistry"%2C"value"%3A"board-of-registration-in-dentistry"}%2C{"text"%3A"Board of Registration in Medicine"%2C"value"%3A"board-of-registration-in-medicine"}\]%2C"selected"%3A""}&knob-button.outline=true&knob-HeaderSearch.orgDropdown.dropdownButton={"text"%3A"All Organizations"%2C"capitalized"%3Atrue}&knob-linkText=Lorem ipsum dolor sit amet&knob-HeaderSearch.buttonSearch.text=Search&knob-ButtonWithIcon.icon=chevron&selectedKind=atoms%2Flinks&selectedStory=DecorativeLink&full=0&addons=1&stories=1&panelRight=0&addonPanel=storybooks%2Fstorybook-addon-knobs](https://mayflower-react.digital.mass.gov/?knob-href=%23&knob-coloredHeading.text=Title%20text&knob-text=Title%20text&knob-info=&knob-compHeading.title=Title%20text&knob-sidebarHeading.title=Key%20Agencies&knob-pagination.pages=[{"active"%3Afalse%2C"text"%3A"1"%2C"ariaLabel"%3A"Go%20to%20Search%20Results%20Page%201"}%2C{"active"%3Atrue%2C"text"%3A"spacer"}%2C{"active"%3Afalse%2C"text"%3A"3"%2C"ariaLabel"%3A"Go%20to%20Search%20Results%20Page%203"}%2C{"active"%3Atrue%2C"text"%3A"4"%2C"ariaLabel"%3A"Go%20to%20Search%20Results%20Page%204"}%2C{"active"%3Afalse%2C"text"%3A"5"%2C"ariaLabel"%3A"Go%20to%20Search%20Results%20Page%205"}%2C{"active"%3Afalse%2C"text"%3A"spacer"}%2C{"active"%3Afalse%2C"text"%3A"10"%2C"ariaLabel"%3A"Go%20to%20Search%20Results%20Page%2010"}]&knob-compHeading.titleContext=&knob-ButtonSearch.text=Search&knob-pagination.next.text=Next&knob-pagination.prev.text=Previous&knob-HeaderSearch.defaultText=&knob-coloredHeading.color=&knob-compHeading.id=&knob-HeaderSearch.withOrgDropdown=true&knob-level=1&knob-pagination.prev.ariaLabel=Go%20to%20Previous%20Search%20Results%20Page&knob-pagination.next.ariaLabel=Go%20to%20Next%20Search%20Results%20Page&knob-coloredHeading.level=2&knob-ButtonSearch.ariaLabel=Search&knob-tableOptions.feeTable={"head"%3A{"rows"%3A[{"rowSpanOffset"%3Afalse%2C"cells"%3A[{"heading"%3Afalse%2C"colspan"%3A""%2C"rowspan"%3A""%2C"text"%3A"Type"}%2C{"heading"%3Atrue%2C"colspan"%3A""%2C"rowspan"%3A""%2C"text"%3A"Name"}%2C{"heading"%3Atrue%2C"colspan"%3A""%2C"rowspan"%3A""%2C"text"%3A"Fee"}]}]}%2C"bodies"%3A[{"rows"%3A[{"rowSpanOffset"%3Afalse%2C"cells"%3A[{"heading"%3Atrue%2C"colspan"%3A""%2C"rowspan"%3A"4"%2C"text"%3A"Freshwater%20Fishing"}%2C{"heading"%3Afalse%2C"colspan"%3A""%2C"rowspan"%3A""%2C"text"%3A"Resident%20Citizen%20or%20Non-Resident%20Fishing"}%2C{"heading"%3Afalse%2C"colspan"%3A""%2C"rowspan"%3A""%2C"text"%3A"%2427.50"}]}%2C{"rowSpanOffset"%3Atrue%2C"cells"%3A[{"heading"%3Afalse%2C"colspan"%3A""%2C"rowspan"%3A""%2C"text"%3A"Resident%20Citizen%20or%20Non-Resident%20Minor%20Fishing%20%28Age%2015-17%29"}%2C{"heading"%3Afalse%2C"colspan"%3A""%2C"rowspan"%3A""%2C"text"%3A"FREE"}]}%2C{"rowSpanOffset"%3Atrue%2C"cells"%3A[{"heading"%3Afalse%2C"colspan"%3A""%2C"rowspan"%3A""%2C"text"%3A"Resident%20Citizen%20Fishing%20%28Age%2065-69%29"}%2C{"heading"%3Afalse%2C"colspan"%3A""%2C"rowspan"%3A""%2C"text"%3A"%2416.25"}]}%2C{"rowSpanOffset"%3Atrue%2C"cells"%3A[{"heading"%3Afalse%2C"colspan"%3A""%2C"rowspan"%3A""%2C"text"%3A"Resident%20Citizen%20Fishing%20%28Aged%2070%20or%20Over%29"}%2C{"heading"%3Afalse%2C"colspan"%3A""%2C"rowspan"%3A""%2C"text"%3A"FREE"}]}]}%2C{"rows"%3A[{"rowSpanOffset"%3Afalse%2C"cells"%3A[{"heading"%3Atrue%2C"colspan"%3A""%2C"rowspan"%3A"4"%2C"text"%3A"Hunting"}%2C{"heading"%3Afalse%2C"colspan"%3A""%2C"rowspan"%3A""%2C"text"%3A"Resident%20Citizen%20Hunting"}%2C{"heading"%3Afalse%2C"colspan"%3A""%2C"rowspan"%3A""%2C"text"%3A"%2427.50"}]}%2C{"rowSpanOffset"%3Atrue%2C"cells"%3A[{"heading"%3Afalse%2C"colspan"%3A""%2C"rowspan"%3A""%2C"text"%3A"Resident%20Citizen%20Hunting%2C%20%28Age%2065-69%29"}%2C{"heading"%3Afalse%2C"colspan"%3A""%2C"rowspan"%3A""%2C"text"%3A"%2416.25"}]}%2C{"rowSpanOffset"%3Atrue%2C"cells"%3A[{"heading"%3Afalse%2C"colspan"%3A""%2C"rowspan"%3A""%2C"text"%3A"Resident%20and%20Non-Resident%20Citizen%20Hunting"}%2C{"heading"%3Afalse%2C"colspan"%3A""%2C"rowspan"%3A""%2C"text"%3A"FREE"}]}%2C{"rowSpanOffset"%3Atrue%2C"cells"%3A[{"heading"%3Afalse%2C"colspan"%3A""%2C"rowspan"%3A""%2C"text"%3A"Resident%20Hunting"}%2C{"heading"%3Afalse%2C"colspan"%3A""%2C"rowspan"%3A""%2C"text"%3A"%2427.50"}]}]}]}&knob-button.href=https%3A%2F%2Fmass.gov&knob-compHeading.color=&knob-HeaderSearch.placeholder=Search%20Mass.gov&knob-button.text=button&knob-compHeading.level=2&knob-button.info=this%20will%20be%20the%20tooltip%20text%20on%20hover&knob-sidebarHeading.level=2&knob-ButtonWithIcon.text=BUTTON&knob-HeaderSearch.buttonSearch.ariaLabel=Search&knob-HeaderSearch.orgDropdown.inputText={"boxed"%3Atrue%2C"label"%3Anull%2C"placeholder"%3A"Search%20an%20organization..."%2C"id"%3A"org-typeahead"%2C"options"%3A[{"text"%3A""%2C"value"%3A""}%2C{"text"%3A"Org%20Having%20%28Parentheses%20in%20the%20Name%29"%2C"value"%3A"org-having-parentheses-in-the-name"}%2C{"text"%3A"Attorney%20General's%20Office"%2C"value"%3A"attorney-general-office"}%2C{"text"%3A"Governor's%20Office"%2C"value"%3A"governors-office"}%2C{"text"%3A"Bureau%20of%20Environmental%20Health"%2C"value"%3A"bureau-of-environmental-health"}%2C{"text"%3A"Department%20of%20Conservation%20%26%20Recreation"%2C"value"%3A"department-of-conservation--recreation"}%2C{"text"%3A"Department%20of%20Unemployment%20Assistance"%2C"value"%3A"department-of-unemployment-assistance"}%2C{"text"%3A"495%2FMetroWest%20Suburban%20Edge%20Community%20Commission"%2C"value"%3A"495metrowest-suburban-edge-community-commission"}%2C{"text"%3A"Administrative%20Council%20on%20Toxics%20Use%20Reduction"%2C"value"%3A"administrative-council-on-toxics-use-reduction"}%2C{"text"%3A"Advisory%20Committee%20to%20the%20Administrative%20Council%20on%20Toxics%20Use%20Reduction"%2C"value"%3A"advisory-committee-to-the-administrative-council-on-toxics-use-reduction"}%2C{"text"%3A"Alcoholic%20Beverages%20Control%20Commission"%2C"value"%3A"alcoholic-beverages-control-commission"}%2C{"text"%3A"Appeals%20Court"%2C"value"%3A"appeals-court"}%2C{"text"%3A"Architectural%20Access%20Board"%2C"value"%3A"architectural-access-board"}%2C{"text"%3A"Berkshire%20District%20Attorney%20Paul%20J.%20Caccaviello"%2C"value"%3A"berkshire-district-attorney-paul-j-caccaviello"}%2C{"text"%3A"Board%20of%20Registration%20in%20Dentistry"%2C"value"%3A"board-of-registration-in-dentistry"}%2C{"text"%3A"Board%20of%20Registration%20in%20Medicine"%2C"value"%3A"board-of-registration-in-medicine"}]%2C"selected"%3A""}&knob-button.outline=true&knob-HeaderSearch.orgDropdown.dropdownButton={"text"%3A"All%20Organizations"%2C"capitalized"%3Atrue}&knob-linkText=Lorem%20ipsum%20dolor%20sit%20amet&knob-HeaderSearch.buttonSearch.text=Search&knob-ButtonWithIcon.icon=chevron&selectedKind=atoms%2Flinks&selectedStory=DecorativeLink&full=0&addons=1&stories=1&panelRight=0&addonPanel=storybooks%2Fstorybook-addon-knobs)\)
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
| :--- | :--- |
| Link | .ma\_\_content-link |
| Decorative Link | .ma\_\_decorative--link |
| Chevron Link | .ma\_\_content-link--chevron |
