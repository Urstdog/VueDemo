<template>
  <div>
    <h2>学生姓名: {{ name }}</h2>
    <h2>年龄: {{ age }}</h2>
  </div>
</template>

<script>
export default {
    data() {
    name: 'student'
    return {
      name: "张三",
      age: 20,
    };
  },
};
</script>

<style>
</style>