<template>
  <div class="show">
    <p>{{message}}</p>
    <p>First name:{{}}</p>
    <p>Last name: {{}}</p>
    <p> Email: {{}} </p>
    <p> Phone Number: {{}} </p>
    <p> Short Bio: {{}} </p>
    <p> Linkedin URL: {{}} </p>
    <p> Twitter Handle: {{}} </p>
    <p> Personal Blog/Website URL: {{}} </p>
    <p> Online Resume URL: {{}} </p>
    <p> GitHub URL: {{}} </p>
    <p> Photo: {{}} </p>
    ____________________________________________

    <p>{{messageOne}}</p>
    <p>Start Date: {{}}</p>
    <p>End Date: {{}}</p>
    <p>Job Title: {{}}</p>
    <p>Company Name: {{}}</p>
    <p>Details: {{}}</p>
    _____________________________________________
    <p>{{messageTwo}}</p>
    <p>Start Date: {{}}</p>
    <p>End Date: {{}}</p>
    <p>Degree: {{}}</p>
    <p>University: {{}}</p>
    <p>Details: {{}}</p>
    _____________________________________________
    <p> Skill Name: {{}}</p>
    _____________________________________________
    <p> {{messageThree}}</p>
    <p> Name: {{}}</p>
    <p> Description: {{}}</p>
    <p> URL: {{}}</p>
    <p> Screenshot: {{}}</p>



    
    
  </div>
</template>

<style>
</style>

<script>
import axios from "axios";
export default {
  data: function () {
    return {
      message: "Welcome! Here you can see all of your information.",
      messageOne: "Experience",
      messageTwo: "Education",
      messageThree: "Capstone",
      resume: {},
    };
  },
  // created: function () {
  //   axios.get("/api/show/:id") +
  //     this.$route.params.id.then((response) => {
  //       console.log("show resume info", response);
  //       this.show = response.data;
  //     });
  // },
  methods: {},
};
</script>