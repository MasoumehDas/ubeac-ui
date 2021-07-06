# UAccordion

## Properties

### variant

* type: String
* default: simple
* available values: simple, open-on-focus ,formatted-results,template-for-results,...

### visible

* type: boolean
* default: true

### readonly
* type: boolean
* default: false

### name

* type: String

### values

* type: json


### placeholder

* type: String

### tooltip

* type: String

### sizing
* type: String
* default: clean
* available values:sm,lg ,md,... 

### label
* default: clean
* type: String

### autofocus

* type: boolean
* default: false

### placeholderIcon
* type: String

### placeholderIconAlign

* type: String
* default: clean
* available values:left,righ

### HasSeach
* type: boolean
* default: false

### HasAddNew
* type: boolean
* default: false

### HasMultipleSelection
* type: boolean
* default: false

## Methods

### focus
### changed
### blur
### click
### mouseOver


## Examples

```html
<u-autocomplete  label="Sample" autofocus="false" placeholderIcon="" placeholderIconAlign="" HasSeach="true" HasAddNew="false" HasMultipleSelection="true"
                variant="simple" visible="true" readonly="false" name="sample" values="[{Id:1,Name: sample1},{Id:2,Name: sample2},{Id:3,Name: sample3}]" sizing="md" @changed=""  @blur="" />
```

