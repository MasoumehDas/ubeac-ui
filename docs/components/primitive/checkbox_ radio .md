# UCheckbox & URadio

## Properties

### variant

* type: String
* default: clean
* available values: primary, bordered, danger, Warning, Info,...

### label
* Type: String

### sizing
* type: String
* default: clean
* available values:sm,lg ,... 

### visible

* type: boolean
* default: true

### readonly

* type: boolean
* default: false

### Switches

* type: String
* default: clean
* available values: Switches-primary, bordered, Switches-danger, Switches-Warning, Info,...

## Methods

### Click
### Changed
### Blur
   


## Examples

```html
<u-checkbox  variant="primary" visible="true" readonly="false" Switches="" @Changed="" @Click="" @Blur=""  label="Sample" />

<u-checkbox  variant="primary" visible="true" readonly="false" Switches="Switches-primary" @Changed="" @Click="" @Blur="" label="Sample" />

<u-radio  variant="primary" visible="true" readonly="false" Switches="" @Changed="" @Click="" @Blur="" label="Sample" />


<u-radio  variant="primary" visible="true" readonly="false" Switches="Switches-primary" @Changed="" @Click="" @Blur="" label="Sample" />


```



