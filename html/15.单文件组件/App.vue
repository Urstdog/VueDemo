<template>
  <!-- 3.使用组件 -->
  <div>
    <School></School>
    <Student></Student>
  </div>
</template>

<script>
//1.引入组件
import School from "./School.vue";
import Student from "./Student.vue";

export default {
  name: "App",
  template: "<App></App>",
  //2.注册组件
  components: {
    School,
    Student,
  },
};
</script>

<style>
</style>