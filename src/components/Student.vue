<template>
 <div>
   <table class="table table-striped">
   <thead>
   <tr>
     <th>id</th> <th>name</th> <th>surname</th> <th>age</th>
   </tr>
   </thead>
   <tbody>
   <tr v-for="item in talabalar" :key="item">
    <td>{{id++}}</td><td>{{item.name}}</td> <td>{{item.surname}}</td> <td>{{item.age}}</td>
   </tr>
   </tbody>
   </table>
 </div>

</template>

<script>
  export default {
    name:"Student",
      data(){
      return{
        id:-403,

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


