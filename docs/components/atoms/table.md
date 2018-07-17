# Table

## Overview

### Accessibility

## Code

### Table

{% tabs %}
{% tab title="HTML" %}
```markup
<table class="ma__table ">
  <thead>
    <tr>
      <th scope="col">Type</th>
      <th scope="col">Name</th>
      <th scope="col">Fee</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th data-label="Type" scope="row" rowspan="4">Freshwater Fishing</th>
      <td data-label="Name">Resident Citizen or Non-Resident Fishing</td>
      <td data-label="Fee">$27.50</td>
    </tr>
    <tr class="is-offset">
      <td data-label="Name">Resident Citizen or Non-Resident Minor Fishing (Age 15-17)</td>
      <td data-label="Fee">FREE</td>
    </tr>
    <tr class="is-offset">
      <td data-label="Name">Resident Citizen Fishing (Age 65-69)</td>
      <td data-label="Fee">$16.25</td>
    </tr>
    <tr class="is-offset">
      <td data-label="Name">Resident Citizen Fishing (Aged 70 or Over)</td>
      <td data-label="Fee">FREE</td>
    </tr>
  </tbody>
  <tbody>
    <tr>
      <th data-label="Type" scope="row" rowspan="4">Hunting</th>
      <td data-label="Name">Resident Citizen Hunting</td>
      <td data-label="Fee">$27.50</td>
    </tr>
    <tr class="is-offset">
      <td data-label="Name">Resident Citizen Hunting, (Age 65-69)</td>
      <td data-label="Fee">$16.25</td>
    </tr>
    <tr class="is-offset">
      <td data-label="Name">Resident and Non-Resident Citizen Hunting</td>
      <td data-label="Fee">FREE</td>
    </tr>
    <tr class="is-offset">
      <td data-label="Name">Resident Hunting</td>
      <td data-label="Fee">$27.50</td>
    </tr>
  </tbody>
</table>
```
{% endtab %}

{% tab title="React" %}

{% endtab %}

{% tab title="Twig PL" %}

{% endtab %}
{% endtabs %}

## Style

| **Name** | **scss Modifier** |
| --- | --- |
| Table | .ma\_\_table |

