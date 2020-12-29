

<template>
  <div class="student-edit">
    <form v-on:submit.prevent="submit()">
      <h1>Student Information</h1>
      <ul>
        <li class="text-danger" v-for="error in errors">{{ error }}</li>
      </ul>
      <div class="form-group">
        <label>First Name:</label> 
        <input type="text" class="form-control" v-model="firstName">
      </div>
      <div class="form-group">
        <label>Last Name:</label>
        <input type="text" class="form-control" v-model="lastName">
      </div>
      <div class="form-group">
        <label>Email:</label>
        <input type="url" class="form-control" v-model="email">
      </div>
      <div class="form-group">
        <label>Phone Number:</label>
        <input type="url" class="form-control" v-model="phoneNumber">
      </div>
      <div class="form-group">
        <label>Short Bio:</label>
        <input type="url" class="form-control" v-model="shortBio">
      </div>
      <div class="form-group">
        <label>Linkedin Url:</label>
        <input type="url" class="form-control" v-model="linkedinUrl">
      </div>
      <div class="form-group">
        <label>Twitter Handle:</label>
        <input type="url" class="form-control" v-model="twitterHandle">
      </div>
      <div class="form-group">
        <label>Personal Blog Url:</label>
        <input type="url" class="form-control" v-model="personalBlogUrl">
      </div>
      <div class="form-group">
        <label>Resume Url:</label>
        <input type="url" class="form-control" v-model="resumeUrl">
      </div>
      <div class="form-group">
        <label>Github Url:</label>
        <input type="url" class="form-control" v-model="githubUrl">
      </div>
      <div class="form-group">
        <label>Photo:</label>
        <input type="url" class="form-control" v-model="photo">
      </div>
      <input type="submit" class="btn btn-primary" value="Submit">
    </form>
  </div>
</template>

<script>
export default {
  data: function () {
    return {
      message: "Update!",
      firstName: "ed",
      lastName: "Gutierrez",
      email: "ed@ed.com",
      phoneNumber: "5718935",
      shortBio: "he's a guy with class and style named ed",
      linkedinUrl: "https://linkedin.com/ed",
      twitterHandle: "edgtz",
      personalBlogUrl: "https://ed.github.io/",
      resumeUrl: "https://resume.com/",
      githubUrl: "https://ed.github",
      photo: "hdsancnjksd",
      errors: [],
    };
  },
  created: function () {},
  methods: {},
};
</script>
