<template>
  <div class="demo">
    <h2>学校名称：{{schoolName}}</h2>
    <h2>学校地址：{{address}}</h2>
    <button @click="showX">点我输出x</button>
  </div>
</template>

<script>
//组件交互相关的代码（数据、方法等）
export default {
  //默认暴露
  name: 'school',
  data() {
    return {
      schoolName: '尚硅谷',
      address: '昌平'
    }
  },
  methods: {
    showX() {
      console.log(this.x)
    }
  }
}
</script>

<style>
/* 组件的样式 */
.demo {
  background-color: aqua;
}
</style>