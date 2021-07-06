# UTable

## Properties

### variant

* type: String
* default: Standard
* available values: Standard, Large, Regular, Bordered, Borderless,Striped,Hover,Dark

### visible

* type: boolean
* default: true

### HeaderTitle

* type: String

### ItemsTitle

* type: String

### ItemsValue

* type: String

### ItemsType

* type: String
* default: text
* available values: button, selected, dropdown,input

### iconHeader
* type: String
* default: clean
* available values: arrow-down, minus,arrow-down-slim,...

### IconHeaderAlign
* Type:String
* default: clean
* available values: left,right,...

### iconBody
* type: String
* default: clean
* available values: arrow-down, minus,arrow-down-slim,...

### IconBodyAlign
* Type:String
* default: clean
* available values: left,right,...

### FooterTitle
* type: String

### HasMultipleSelection
* type: boolean
* default: false

### HasPagging
* type: boolean
* default: true

### PaggingSize
* type: integer
* default: 30

### HasRowNumber
* type: boolean
* default: false

### HasSearchAllColumns
* type: boolean
* default: true

### HasSortItems
* type: boolean
* default: true

### ClickItems
    * point: Automatic submission of clicked item ID

### SelectItems
    * point: Automatic submission of clicked item ID   
    
### MouseOverItems
    * point: Automatic submission of mouse over item ID



## Examples

```html
<u-table HeaderTitle="Sample" visible=true variant="standard" HasMultipleSelection="true" HasPagging="true" PaggingSize="30" HasRowNumber="true" HasSearchAllColumns="true" @SelectItems="" >
  <u-table-Items ItemsType="text" ItemsTitle="column 1" ItemsValue="One" visible="true" iconHeader="" IconHeaderAlign="" iconBody="" IconBodyAlign=""  @ClickItems="" HasSortItems="true" />
   <u-table-Items ItemsType="input" ItemsTitle="column 2" ItemsValue="Two" visible="true" iconHeader="" IconHeaderAlign="" iconBody="" IconBodyAlign=""  @ClickItems="" HasSortItems="false" >
     <u-input type="text" value="input sample" icon="edit" IconAlign="left" @IconClick="" />
  </u-table-Items>
  <u-table-Items ItemsType="dropdown" ItemsTitle="column 3" ItemsValue="Tree" visible="true" iconHeader="" IconHeaderAlign="" iconBody="" IconBodyAlign=""  @ClickItems=""  HasSortItems="false" >
    <u-dropdown variant="shadowed" text="..."  visible="true" Enable="true"  @Click="" IconBeforclick="arrow-start" IconAfterClick="arrow-down" tooltip="">
  <u-dropdown-tems  ItemsTitle="Corporate 1" CurrentActive="true" visible="true" Enable="true"   tooltip="" @ClickItems="" @MouseOverItems="" IconBeforMouseOver="arrow-start" IconAfterMouseOver="arrow-down" />
  <u-dropdown-tems  ItemsTitle="Corporate 2" CurrentActive="false" visible="true" Enable="true"   tooltip="" @ClickItems="" @MouseOverItems="" IconBeforMouseOver="arrow-start" IconAfterMouseOver="arrow-down" />  
  <u-dropdown-tems  ItemsTitle="Corporate 3" CurrentActive="false" visible="true" Enable="true"   tooltip="" @ClickItems="" @MouseOverItems="" IconBeforMouseOver="arrow-start" IconAfterMouseOver="arrow-down" />
</u-dropdown>
  </u-table-Items>
  
 </u-table>
```




