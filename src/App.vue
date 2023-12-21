<script>
import { NumericTextBoxComponent } from '@syncfusion/ej2-vue-inputs';

export default {
  components: {
    'ejs-numerictextbox' : NumericTextBoxComponent
  }
}

</script>

<template>
<div class="numerictextbox">
 <ejs-numerictextbox width="200px" :value="10" :max="100" :min="1" :step="5"
  format="000.00" :decimals="2" :validateDecimalOnType="true"
  :showSpinButton="false" >
 </ejs-numerictextbox>
</div>
</template>

<style>
  @import "../node_modules/@syncfusion/ej2-base/styles/fluent.css";
  @import "../node_modules/@syncfusion/ej2-vue-inputs/styles/fluent.css";

  .numerictextbox {
    margin-bottom: 150px;
  }

</style>
