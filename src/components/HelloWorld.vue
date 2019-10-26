<template>
  <div class="hello">
    <h2>我是子组件helloworld</h2>
  </div>
</template>

<script>
//相当于node中的: module.exports={ ... }
//只要这里抛出一个模块对象
//在其他地方都可以用import引入这个模块对象
export default {

}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
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
</style>
