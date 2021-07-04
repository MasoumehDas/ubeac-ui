# UForm

## Properties

### variant

* Type: String
* default: clean
* available values: grid, groups,row ,horizontal,inline


### sizing

* type: boolean
* available values: sm, lg, auto-sizing,... 

### visible

* type: boolean
* default: true

### icon 
* Type: String
* default: clean
* available values: user, plus, edit,...

### IconAlign 
* Type: String
* default: clean
* available values: right, left, center,...

### Title
* Type: String

### readonly
* type: boolean
* default: false

### ReadonlyType
* Type: String
* default: clean
* available values: lable-view, input-view ,...


### NumberColumn
* Type: Integer
* default: 1

## Methods

### Submit
### ClearForm
   



## Examples

```html
<u-form Title="Sample" variant="grid"   sizing=""  visible="true"  icon=""  IconAlign="" readonly="false"  ReadonlyType="" NumberColumn="1" @Submit="" @ClearForm="" >
  <u-input lable="Sample" name="Sample" />
  
</u-form> 
```
