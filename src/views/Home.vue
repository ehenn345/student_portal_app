<template>
  <div class="home">
    <h1>Student Portal App</h1>
    <div id='container' style="margin:50px auto 0; width:450px;">
         <ejs-dropdownlist id='dropdownlist' :dataSource='loginData' placeholder='Login'></ejs-dropdownlist>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
import Vue from "vue";
import { DropDownListPlugin } from "@syncfusion/ej2-vue-dropdowns";
Vue.use(DropDownListPlugin);

export default Vue.extend({
  data: function () {
    return {
      loginData: [
        "Student Name1",
        "Student Name2",
        "Student Name3",
        "Student Name4",
        "Student Name5",
      ],
    };
  },
});
</script>

<style>
@import "../../node_modules/@syncfusion/ej2-base/styles/material.css";
@import "../../node_modules/@syncfusion/ej2-inputs/styles/material.css";
@import "../../node_modules/@syncfusion/ej2-vue-dropdowns/styles/material.css";
</style>