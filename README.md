# Lesbox
_Code less with lesbox for making custom styled select box..._

## Demo
https://priyaty.github.io/lesbox/

## HTML Strucure

```html
<div class=”lesbox-wrapper“ id=”list-id”>
  <select>
    <option></option>
    <option>Option 1</option>
    <option>Option 2</option>
    <option>Option 3</option>
    <option>Option 4</option>
    <option>Option 5</option>
  </select>
</div>
```

## Initialization
Initialize with:
```javascript
$('#list-id').lesbox();
```

## Settings

Option | Type | Default | Description
------ | ---- | ------- | -----------
dropdownIcon | string | default | It’s the class name/s of the dropdown icon. E.g dropdownIcon: “lesbox-icon”. Incase if font awesome icon has to be added, the value can be something like this “fa fa-angle-down”.
listHeading | string | List Items | Custom Select box list heading.
listName | string | list_name | Name attribute value of the respective select box.
additionalLinkClass | string | null | If there is any additional style class that needs to be added to the dropdown link, then that can be specified using this setting.

## Attributes

Add the following attribute/s to "option" tag/s:

Option | Type | Default | Description
------ | ---- | ------- | -----------
data-href | string | none | If a dropdown item needs to link to a page or any section, this attribute can used for inserting the link value.

## Custom styling of the select box
Use the following classes to make any desired css changes to the respective element.

### 1.	.lesbox-link
For styling the dropdown heading container use this class to add different css properties.

### 2.	.lesbox-list
For styling the dropdown box.

### 3.	.lesbox-list-item
For styling the dropdown outer list block.

### 4.	.lesbox-list-item__link
For styling the dropdown list item link.

### Browser Support
Lesbox works on IE7+ in addition to other modern browsers such as Chrome, Firefox, and Safari.

### Dependencies
jQuery 1.12+

### License

Copyright (c) 2017 Priya Tyagi

Licensed under the MIT license.

Free as in Bacon.
