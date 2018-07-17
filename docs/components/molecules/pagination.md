# Pagination

## Overview

![](../../.gitbook/assets/pagination.png)

### Accessibility & Best Practices

## Code

### Pagination

{% tabs %}
{% tab title="HTML" %}
```markup
<div class="ma__pagination js-pagination">
  <div class="ma__pagination__container">
    <button class="ma__pagination__prev js-pagination-prev" type="button">
      Previous
    </button>
    <button class="ma__pagination__page js-pagination-page" type="button" data-page="1">1</button>
    <span class="ma__pagination__spacer">&hellip;</span>
    <button class="ma__pagination__page js-pagination-page" type="button" data-page="3">3</button>
    <button class="ma__pagination__page js-pagination-page is-active" type="button" data-page="4">4</button>
    <button class="ma__pagination__page js-pagination-page" type="button" data-page="5">5</button>
    <span class="ma__pagination__spacer">&hellip;</span>
    <button class="ma__pagination__page js-pagination-page" type="button" data-page="10">10</button>
    <button class="ma__pagination__next js-pagination-next" type="button">
      Next
    </button>
  </div>
</div>
```
{% endtab %}

{% tab title="React" %}
[Pagination in React](https://mayflower-react.digital.mass.gov/?knob-href=%23&knob-info=&knob-pagination.pages=%5B%7B%22active%22%3Afalse%2C%22text%22%3A%221%22%2C%22ariaLabel%22%3A%22Go%20to%20Search%20Results%20Page%201%22%7D%2C%7B%22active%22%3Atrue%2C%22text%22%3A%22spacer%22%7D%2C%7B%22active%22%3Afalse%2C%22text%22%3A%223%22%2C%22ariaLabel%22%3A%22Go%20to%20Search%20Results%20Page%203%22%7D%2C%7B%22active%22%3Atrue%2C%22text%22%3A%224%22%2C%22ariaLabel%22%3A%22Go%20to%20Search%20Results%20Page%204%22%7D%2C%7B%22active%22%3Afalse%2C%22text%22%3A%225%22%2C%22ariaLabel%22%3A%22Go%20to%20Search%20Results%20Page%205%22%7D%2C%7B%22active%22%3Afalse%2C%22text%22%3A%22spacer%22%7D%2C%7B%22active%22%3Afalse%2C%22text%22%3A%2210%22%2C%22ariaLabel%22%3A%22Go%20to%20Search%20Results%20Page%2010%22%7D%5D&knob-ButtonSearch.text=Search&knob-pagination.next.text=Next&knob-pagination.prev.text=Previous&knob-HeaderSearch.defaultText=&knob-HeaderSearch.withOrgDropdown=true&knob-pagination.prev.ariaLabel=Go%20to%20Previous%20Search%20Results%20Page&knob-pagination.next.ariaLabel=Go%20to%20Next%20Search%20Results%20Page&knob-ButtonSearch.ariaLabel=Search&knob-tableOptions.feeTable=%7B%22head%22%3A%7B%22rows%22%3A%5B%7B%22rowSpanOffset%22%3Afalse%2C%22cells%22%3A%5B%7B%22heading%22%3Afalse%2C%22colspan%22%3A%22%22%2C%22rowspan%22%3A%22%22%2C%22text%22%3A%22Type%22%7D%2C%7B%22heading%22%3Atrue%2C%22colspan%22%3A%22%22%2C%22rowspan%22%3A%22%22%2C%22text%22%3A%22Name%22%7D%2C%7B%22heading%22%3Atrue%2C%22colspan%22%3A%22%22%2C%22rowspan%22%3A%22%22%2C%22text%22%3A%22Fee%22%7D%5D%7D%5D%7D%2C%22bodies%22%3A%5B%7B%22rows%22%3A%5B%7B%22rowSpanOffset%22%3Afalse%2C%22cells%22%3A%5B%7B%22heading%22%3Atrue%2C%22colspan%22%3A%22%22%2C%22rowspan%22%3A%224%22%2C%22text%22%3A%22Freshwater%20Fishing%22%7D%2C%7B%22heading%22%3Afalse%2C%22colspan%22%3A%22%22%2C%22rowspan%22%3A%22%22%2C%22text%22%3A%22Resident%20Citizen%20or%20Non-Resident%20Fishing%22%7D%2C%7B%22heading%22%3Afalse%2C%22colspan%22%3A%22%22%2C%22rowspan%22%3A%22%22%2C%22text%22%3A%22%2427.50%22%7D%5D%7D%2C%7B%22rowSpanOffset%22%3Atrue%2C%22cells%22%3A%5B%7B%22heading%22%3Afalse%2C%22colspan%22%3A%22%22%2C%22rowspan%22%3A%22%22%2C%22text%22%3A%22Resident%20Citizen%20or%20Non-Resident%20Minor%20Fishing%20%28Age%2015-17%29%22%7D%2C%7B%22heading%22%3Afalse%2C%22colspan%22%3A%22%22%2C%22rowspan%22%3A%22%22%2C%22text%22%3A%22FREE%22%7D%5D%7D%2C%7B%22rowSpanOffset%22%3Atrue%2C%22cells%22%3A%5B%7B%22heading%22%3Afalse%2C%22colspan%22%3A%22%22%2C%22rowspan%22%3A%22%22%2C%22text%22%3A%22Resident%20Citizen%20Fishing%20%28Age%2065-69%29%22%7D%2C%7B%22heading%22%3Afalse%2C%22colspan%22%3A%22%22%2C%22rowspan%22%3A%22%22%2C%22text%22%3A%22%2416.25%22%7D%5D%7D%2C%7B%22rowSpanOffset%22%3Atrue%2C%22cells%22%3A%5B%7B%22heading%22%3Afalse%2C%22colspan%22%3A%22%22%2C%22rowspan%22%3A%22%22%2C%22text%22%3A%22Resident%20Citizen%20Fishing%20%28Aged%2070%20or%20Over%29%22%7D%2C%7B%22heading%22%3Afalse%2C%22colspan%22%3A%22%22%2C%22rowspan%22%3A%22%22%2C%22text%22%3A%22FREE%22%7D%5D%7D%5D%7D%2C%7B%22rows%22%3A%5B%7B%22rowSpanOffset%22%3Afalse%2C%22cells%22%3A%5B%7B%22heading%22%3Atrue%2C%22colspan%22%3A%22%22%2C%22rowspan%22%3A%224%22%2C%22text%22%3A%22Hunting%22%7D%2C%7B%22heading%22%3Afalse%2C%22colspan%22%3A%22%22%2C%22rowspan%22%3A%22%22%2C%22text%22%3A%22Resident%20Citizen%20Hunting%22%7D%2C%7B%22heading%22%3Afalse%2C%22colspan%22%3A%22%22%2C%22rowspan%22%3A%22%22%2C%22text%22%3A%22%2427.50%22%7D%5D%7D%2C%7B%22rowSpanOffset%22%3Atrue%2C%22cells%22%3A%5B%7B%22heading%22%3Afalse%2C%22colspan%22%3A%22%22%2C%22rowspan%22%3A%22%22%2C%22text%22%3A%22Resident%20Citizen%20Hunting%2C%20%28Age%2065-69%29%22%7D%2C%7B%22heading%22%3Afalse%2C%22colspan%22%3A%22%22%2C%22rowspan%22%3A%22%22%2C%22text%22%3A%22%2416.25%22%7D%5D%7D%2C%7B%22rowSpanOffset%22%3Atrue%2C%22cells%22%3A%5B%7B%22heading%22%3Afalse%2C%22colspan%22%3A%22%22%2C%22rowspan%22%3A%22%22%2C%22text%22%3A%22Resident%20and%20Non-Resident%20Citizen%20Hunting%22%7D%2C%7B%22heading%22%3Afalse%2C%22colspan%22%3A%22%22%2C%22rowspan%22%3A%22%22%2C%22text%22%3A%22FREE%22%7D%5D%7D%2C%7B%22rowSpanOffset%22%3Atrue%2C%22cells%22%3A%5B%7B%22heading%22%3Afalse%2C%22colspan%22%3A%22%22%2C%22rowspan%22%3A%22%22%2C%22text%22%3A%22Resident%20Hunting%22%7D%2C%7B%22heading%22%3Afalse%2C%22colspan%22%3A%22%22%2C%22rowspan%22%3A%22%22%2C%22text%22%3A%22%2427.50%22%7D%5D%7D%5D%7D%5D%7D&knob-button.href=https%3A%2F%2Fmass.gov&knob-HeaderSearch.placeholder=Search%20Mass.gov&knob-button.text=button&knob-button.info=this%20will%20be%20the%20tooltip%20text%20on%20hover&knob-ButtonWithIcon.text=BUTTON&knob-HeaderSearch.buttonSearch.ariaLabel=Search&knob-HeaderSearch.orgDropdown.inputText=%7B%22boxed%22%3Atrue%2C%22label%22%3Anull%2C%22placeholder%22%3A%22Search%20an%20organization...%22%2C%22id%22%3A%22org-typeahead%22%2C%22options%22%3A%5B%7B%22text%22%3A%22%22%2C%22value%22%3A%22%22%7D%2C%7B%22text%22%3A%22Org%20Having%20%28Parentheses%20in%20the%20Name%29%22%2C%22value%22%3A%22org-having-parentheses-in-the-name%22%7D%2C%7B%22text%22%3A%22Attorney%20General%27s%20Office%22%2C%22value%22%3A%22attorney-general-office%22%7D%2C%7B%22text%22%3A%22Governor%27s%20Office%22%2C%22value%22%3A%22governors-office%22%7D%2C%7B%22text%22%3A%22Bureau%20of%20Environmental%20Health%22%2C%22value%22%3A%22bureau-of-environmental-health%22%7D%2C%7B%22text%22%3A%22Department%20of%20Conservation%20%26%20Recreation%22%2C%22value%22%3A%22department-of-conservation--recreation%22%7D%2C%7B%22text%22%3A%22Department%20of%20Unemployment%20Assistance%22%2C%22value%22%3A%22department-of-unemployment-assistance%22%7D%2C%7B%22text%22%3A%22495%2FMetroWest%20Suburban%20Edge%20Community%20Commission%22%2C%22value%22%3A%22495metrowest-suburban-edge-community-commission%22%7D%2C%7B%22text%22%3A%22Administrative%20Council%20on%20Toxics%20Use%20Reduction%22%2C%22value%22%3A%22administrative-council-on-toxics-use-reduction%22%7D%2C%7B%22text%22%3A%22Advisory%20Committee%20to%20the%20Administrative%20Council%20on%20Toxics%20Use%20Reduction%22%2C%22value%22%3A%22advisory-committee-to-the-administrative-council-on-toxics-use-reduction%22%7D%2C%7B%22text%22%3A%22Alcoholic%20Beverages%20Control%20Commission%22%2C%22value%22%3A%22alcoholic-beverages-control-commission%22%7D%2C%7B%22text%22%3A%22Appeals%20Court%22%2C%22value%22%3A%22appeals-court%22%7D%2C%7B%22text%22%3A%22Architectural%20Access%20Board%22%2C%22value%22%3A%22architectural-access-board%22%7D%2C%7B%22text%22%3A%22Berkshire%20District%20Attorney%20Paul%20J.%20Caccaviello%22%2C%22value%22%3A%22berkshire-district-attorney-paul-j-caccaviello%22%7D%2C%7B%22text%22%3A%22Board%20of%20Registration%20in%20Dentistry%22%2C%22value%22%3A%22board-of-registration-in-dentistry%22%7D%2C%7B%22text%22%3A%22Board%20of%20Registration%20in%20Medicine%22%2C%22value%22%3A%22board-of-registration-in-medicine%22%7D%5D%2C%22selected%22%3A%22%22%7D&knob-button.outline=true&knob-HeaderSearch.orgDropdown.dropdownButton=%7B%22text%22%3A%22All%20Organizations%22%2C%22capitalized%22%3Atrue%7D&knob-linkText=Lorem%20ipsum%20dolor%20sit%20amet&knob-HeaderSearch.buttonSearch.text=Search&knob-ButtonWithIcon.icon=chevron&selectedKind=molecules&selectedStory=Pagination&full=0&addons=1&stories=1&panelRight=0&addonPanel=storybooks%2Fstorybook-addon-knobs)
{% endtab %}

{% tab title="Twig PL" %}
[Pagination in Pattern Lab](https://mayflower.digital.mass.gov/?p=molecules-pagination)
{% endtab %}
{% endtabs %}

## Style

### Classnames

| **Name** | **scss Modifiers** |
| --- | --- | --- | --- | --- | --- |
| Container | .ma\_\_pagination .ma\_\_pagination\_\_container |
| Next | .ma\_\_pagination\_\_next |
| Spacer | .ma\_\_pagination\_\_spacer |
| Page | .ma\_\_pagination\_\_page |
| Previous | .ma\_\_pagination\_\_prev |

