# UTab

## Properties

### variant

* type: String
* default: regular
* available values: ajax, regular, bordered, pills, vertical,...

### tooltip
* Type: String

### TitleItem
* Type: String


### visible

* type: boolean
* default: true

### Enable

* type: boolean
* default: ture

### CurrentActive

* type: boolean
* default: false
* point :Only one item can be active at a time

### IconBeforclick
* Type:String
* default: arrow-start
* available values: arrow-start, plus, arrow-right-slim,...

### IconAfterClick
* Type:String
* default: arrow-down
* available values: arrow-down, minus,arrow-down-slim,...

## Methods

### Click
### ClickItems
    * point: Automatic submission of clicked item ID
### MouseOverItems
    * point: Automatic submission of mouse over item ID



## Examples

```html
<u-tab variant="regular"   visible="true" Enable="true"  @Click="">
  <u-tab-Items  TitleItem="Item One" IconBeforclick="arrow-start" IconAfterClick="arrow-down"  CurrentActive="true" visible="true" Enable="true"   tooltip="" @ClickItems="" @MouseOverItems="">
    <h5>Hello word</h5>
    <p>
      Quis anim sit do amet fugiat dolor velit sit ea ea do reprehenderit culpa duis
    </p>
    
  </u-tab-Items>
   <u-tab-Items  TitleItem="Item Two" IconBeforclick="arrow-start" IconAfterClick="arrow-down"  CurrentActive="false" visible="true" Enable="true"   tooltip="" @ClickItems="" @MouseOverItems="">
    <u-form Title="Create">
      .
      .
      .
   </u-tab-Items>
</u-tab>
```
