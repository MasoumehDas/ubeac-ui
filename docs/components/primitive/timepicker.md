# UTimepicker

## Properties

### variant

* type: String
* default: basic
* available values: basic, meridian, seconds, spinners,...

### sizing
* type: String
* default: clean
* available values:sm,lg ,... 


### PositionTarget
* type: String
* default: clean
* available values: top , left , right, ...

### tooltip
* Type:String

### visible

* type: boolean
* default: true

### format

* type: String

### mask

* type: String
### readonly

* type: boolean
* default: false

### Enable

* type: boolean
* default: ture


### sizing
* type: String
* default: clean
* available values:sm,lg ,... 

### label
* default: clean
* type: String

### icon
* type: String
* default: clean

### IconAlign

* type: String
* default: clean
* available values:left,right 

### dir

* type: string
* default: left
* available values: left, right


## Methods

### focus

### blur
### click
### mouseOver
### IconClick
## Examples

```html
<u-timepicker variant="basic" value="Sample" name="SampleID" placeholder="Sample" tooltip="Sample" format="" mask="" 
 disable="false" visible="true" readonly="false" dir="left" @focus=""  @blur="" @click="" @mouseOver="",icon="",IconAlign=""
 @IconClick="" placeholderIcon="" placeholderIconAlign="" label="Sample" sizing=""
         
 />
```
