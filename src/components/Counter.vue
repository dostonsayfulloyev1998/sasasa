<template>
  <div class="one">
    <h1>counter:{{count}}</h1>
    <button @click="plus" class="btn btn-primary">plus</button>
    <button @click="minus" class="btn btn-danger">minus</button>

  </div>

</template>

<script>
  export default {
    name: "Counter",
    data(){
      return{
        count:0
      }
    },
    methods:{
      plus(){
        this.count++
      },
      minus(){
        this.count--
      }
    }
  }
</script>

<style>
  .one{
    border: 2px solid greenyellow;
    margin: 30px;
    padding: 15px;
    border-radius: 20px;
  }

</style>