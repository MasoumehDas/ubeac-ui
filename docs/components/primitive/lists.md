# ULists

## Properties

### variant

* type: String
* default: clean
* available values: shadowed, bordered, info ,warrnig,...

### tooltip
* Type:String

### visible

* type: boolean
* default: true

### Enable

* type: boolean
* default: ture

### icon
* type: String
* default: clean

### IconAlign
* type: String
* default: clean

### CurrentActive

* type: boolean
* default: false
* point :Only one item can be active at a time

## Methods

### Click
### ClickItems
    * point: Automatic submission of clicked item ID
### MouseOverItems
    * point: Automatic submission of mouse over item ID



## Examples

```html
<u-lists variant="shadowed"   visible="true" Enable="true"  @Click="" >
  <u-lists-Items icon=""    CurrentActive="true" visible="true" Enable="true"  icon="" IconAlign=""  tooltip="" @ClickItems="" @MouseOverItems="" >
   Anim pariatur cliche reprehenderit, enim eiusmod high life accusamus terry richardson ad squid. 3 wolf moon officia aute, 
  </u-lists-Items>
  <u-lists-Items  CurrentActive="false" visible="true" Enable="true" icon="" IconAlign=""  tooltip="" @ClickItems="" @MouseOverItems="" >
  
  <ul>
    <li> One </li>
    <li> Two </li>
    <li> Tree</li>
  </ul>
  
   
  </u-lists-Items>
   <u-lists-Items  CurrentActive="false" visible="true" Enable="true"   icon="" IconAlign=""  tooltip="" @ClickItems="" @MouseOverItems="" >
    Sample
  </u-lists-Items>
  
</u-lists>
```
