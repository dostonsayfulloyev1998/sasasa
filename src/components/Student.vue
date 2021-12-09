<template>
 <div>
       <h1>{{todo}}</h1>

      <table class="table table-bordered">
          <thead>
              <tr>
                  <th>name</th> <th>surname</th>  <th>age</th>
              </tr>
          </thead>

        <tbody>
            <tr v-for="item in student" :key="item">
                <td>{{item.name}}</td>  <td>{{item.surname}}</td>  <td>{{item.age}}</td>
            </tr>
        </tbody>
      </table>

 </div>

</template>

<script>
  export default {
    name:"Student",
    props:['todo','student']
  }

</script>


