<template>
  <div class="hello">
    <h1>标题测试</h1>
    <div class="article_contents">
        asdasadasda
    </div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'Welcome to Mai Tian'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
.hello {
    display: flex;
    background-color: #ffffed;
    padding: 1rem 10rem 1rem 10rem;
    flex-direction: row;
    justify-content: center;
    flex-basis:auto;
}
.article_contents {
    display: flex;
    padding: 1rem 10rem 1rem 10rem;
    background-color: #aefaff;
    flex-basis:auto;
}
</style>
