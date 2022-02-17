<template>
  <div class="demo">
    <h2>学生名字：{{ studentName }}</h2>
    <h2>学生年龄：{{ age }}</h2>
    <button @click="showName">点我提示学校</button>
  </div>
  <!-- 组件的结构 -->
</template>

<script>
const school = Vue.extend({
  data() {
    return {
      schoolName: "gdufs",
      address: "guangdong",
    };
  },
  methods: {
    showName() {
      alet(this.schoolName);
    },
  },
});
// 组件交互相关的代码（数据、方法等）
</script>

<style>
.demo {
  background-color: orange;
}
/* 样式 */
</style>
