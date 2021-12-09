<template>
  <div id="app">

       <Student :todo="message"/>


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
