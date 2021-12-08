<template>
  <div id="app">
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
   <h1> Salom web dunyosi </h1>
    <p>  <span>
      <span>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ad consequatur exercitationem expedita explicabo iusto non, obcaecati optio perspiciatis
        porro, ratione, reiciendis repellendus veritatis vitae. Eius expedita magni perferendis porro sed.</span>
      <span>Debitis dolore, ea laborum necessitatibus nostrum officiis pariatur quidem quis? Consectetur dolore iusto quae tempore. Blanditiis cupiditate dolorum, est inventore neque non perferendis quae. Laborum odio quod repellat rerum totam.</span><span>Ab alias blanditiis earum eius fugit ipsa iusto maiores necessitatibus neque officiis quia quidem, repellendus sint soluta vel! Blanditiis consectetur corporis ducimus est modi nihil placeat porro quod saepe soluta?</span><span>Ad debitis enim hic id illum impedit inventore itaque laborum magnam magni maiores minus molestias neque officiis optio quaerat quod recusandae saepe, totam voluptas? Autem labore maxime nemo omnis quaerat.</span><span>A adipisci animi assumenda cupiditate deserunt eos fugit necessitatibus similique sit, voluptatum? Adipisci aliquid deserunt eligendi explicabo ipsam ipsum, necessitatibus odit voluptate. Corporis error harum possimus ratione, similique tempore vitae?</span><span>Ab ducimus, et fuga incidunt inventore iste magni nam natus repellendus voluptates. Amet animi, consequuntur cupiditate ducimus eius eos eveniet, incidunt laboriosam laborum libero, obcaecati odio reprehenderit similique ullam voluptatum!</span><span>Accusantium alias, asperiores delectus deleniti dolor eveniet ipsa ipsam, iusto nemo nihil, obcaecati sunt voluptates? Accusantium, aliquid aperiam aspernatur consectetur dolore eos laborum tenetur! Aliquam debitis dolore praesentium quisquam totam!</span><span>Accusamus delectus dolore error hic necessitatibus nemo optio ratione repellat. A ab assumenda consequatur, delectus dolorum ducimus et facilis, magni, non nulla officiis quam qui rerum tempora tenetur voluptatibus voluptatum!</span><span>Amet at beatae, corporis doloribus est explicabo facere fugiat hic id ipsa laudantium magni maiores maxime minus modi nam nemo nostrum numquam pariatur qui rem rerum saepe unde ut voluptate.</span><span>Adipisci, consectetur, doloremque ea esse est explicabo fugiat inventore iste laboriosam maiores mollitia nesciunt, non nostrum perspiciatis placeat praesentium provident quae quas quasi rem rerum sequi tempore temporibus totam voluptates?</span>
    </span>
    </p>
    <Car/>
    <Counter/>
    <Counter/>
    <Counter/>
    <Counter/>
    <Student/>
  </div>
</template>

<script>
import Head from './components/Head1.vue'
import  Car from './components/Car.vue'
import Counter from './components/Counter.vue'
import Student  from "./components/Student.vue"

export default {
  name: 'App',
  components: {
    Car,
    Counter,
    Student,
    Head
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
