# UModals

## Properties

### variant

* type: String
* default: standard
* available values: ajax-fill, confirm, standard,...

### HasCloseButton
* type: boolean
* default: true

### HasSubmitButton
* type: boolean
* default: true

### HasConfirmButton
* type: boolean
* default: true

### ClosingAfterSubmit
* type: boolean
* default: true


### Title
* type: String

### icon
 * type: String
 * default: clean

### IconAlign
  * type: String
  * default: standard
  * available values: left,right ,...

### Sizing
* type: String
* available values: sm, lg, md,xl,full,...


## Methods


### ClickConfirmButton
    
### ClickSubmitButton

### ClickConfirmButton

### ClickAfterCloseButton





## Examples

```html
<u-modals variant="md" variant="confirm" Title="Warrnig" HasCloseButton="true"  @ClickConfirmButton="" @ClickAfterCloseButton="" />

<u-modals variant="md" variant="standard" Title="Create a new page" HasSubmitButton="true" ClosingAfterSubmit="true"  @ClickSubmitButton="" @ClickAfterCloseButton="" >
  <u-form Title="Sample" variant="grid"   sizing=""  visible="true"  icon=""  IconAlign="" readonly="false"  ReadonlyType="" NumberColumn="1" @ClearForm="" >
    <u-input type="text" label="sample1" value="sample1" />
    <u-input type="text" value="sample2" value="sample2"/>
  </u-form>
</ u-modals>

```









