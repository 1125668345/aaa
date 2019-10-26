<template>
  <div class="home">
    <h1>欢迎访问我的首页</h1>
    <hello-world></hello-world>
  </div>
</template>

<script>
//import相当于node中的require("模块名")
//只要其他地方抛出了一个模块对象，这里都可用import引入
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

//module.exports={ ... }
export default {
  components: { //让HelloWorld称为Home的子组件
    HelloWorld
  }
}
</script>

<style scoped>
/*所有的style，最后都会混在一个css文件中*/
  h1{
    background-color:red;
    color:yellow;
  }
</style>
