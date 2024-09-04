<template>
  <div class="demo">
    <h2>学生姓名：{{name}}</h2>
    <h2>学生年龄：{{age}}</h2>
  </div>
</template>

<script>
//组件交互相关的代码（数据、方法等）
export default {
  //默认暴露
  name: 'school',
  data() {
    return {
      name: '小米',
      age: 17
    }
  }
}
</script>

<style>
/* 组件的样式 */
</style>