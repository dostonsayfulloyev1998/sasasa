<template>
  <div id="app">
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">

    <form class="w-50 m-5">

        <div class="form-group">
          <label for="">name</label>
          <input type="text" class="form-control">
        </div>

        <div class="form-group">
          <label for="">surname</label>
          <input type="text" class="form-control">
        </div>

        <div class="form-group">
          <label for="">age</label>
          <input type="text" class="form-control">
        </div>

        <button class="btn btn-primary">add student</button>
    </form>

       <Student :todo="message" :student="talabalar"/>

  </div>
</template>

<script>

import Student from "./components/Student";

export default {
  name: 'App',
  components: {
     Student
  },
  data(){
      return{
        message:"hello wolrd",

        talabalar:[
          {
            name:"ali",
            surname:"valiyev",
            age:23
          },
          {
            name:"sherali",
            surname:"valiyev",
            age:23
          },
          {
            name:"erali",
            surname:"valiyev",
            age:23
          },
          {
            name:"begali",
            surname:"valiyev",
            age:23
          },
          {
            name:"joniali",
            surname:"valiyev",
            age:23
          },
          {
            name:"erali",
            surname:"valiyev",
            age:23
          }
        ]

      }
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
