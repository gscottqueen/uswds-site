---
component:
  status: ready
  package: usa-tk
  dependencies:
permalink: /components/combo-box/
title: Combo box
layout: component
category: Components
type: component
tags:
  - form
  - forms
  - form controls
  - input
  - dropdown
lead: A combo box helps users select an item from a large list of options.
initProps:
  - property: "`required`"
    element: select
    description: The combo box component will be required in terms of native form validation.
  - property: "`disabled`"
    element: select
    description: The combo box component will be disabled / read-only. You can re-enable it by executing the enable procedure on the component.
  - property: "`data-placeholder`"
    element: .usa-combo-box
    description: To update the placeholder text of the combo box, use the `data-placeholder` attribute. We recommend using a label or hint instead of a placeholder.
  - property: "`data-default-value`"
    element: .usa-combo-box
    description: The combo box will set this value as the default selection if it is found within the select options.
props:
  - property: "`data-filter`"
    element: .usa-combo-box
    description: The combo box will use this regular expression to filter the combo box options. You are declaring a case insensitive match over the entire option text, which means `^` and `$` are added automatically. You can specify the inputted query with `{{query}}`. You can also declare a custom query filter as a data property as well, which can be used in the custom filter (`data-number-filter="[0-9]"` and then using `data-filter="{{numberFilter}}.*"`). The default filter is `.*{{query}}.*`, which is a simple "find anywhere within the option" text.
procedures:
  - procedure: "`enable`"
    parameters: .usa-combo-box
    description: The combo box component will be enabled.
  - procedure: "`disable`"
    parameters: .usa-combo-box
    description: The combo box component will be disabled / read-only.
subnav:
- text: Preview
  href: '#tk-preview'
- text: Code
  href: '#tk-code'
- text: Guidance
  href: '#tk-guidance'
- text: Package
  href: '#tk-package'
---
