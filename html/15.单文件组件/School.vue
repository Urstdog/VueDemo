<template>
  <div>
    <h2>学校名称: {{ name }}</h2>
    <h2>学校地址 {{ address }}</h2>
    <!-- 局部注册组件-->
    <college></college>
  </div>
</template>

<script>
//1.分别暴露
// export const school = {}
//2.默认暴露
export default {
  name: "School",//组件名字
  data() {
    return {
      name: "郑州商学院",
      address: "郑州市巩义市",
    };
  },
  //注册组件
  components: {
    college,
  },
};
//3.统一暴露
//export { school };
</script>

<style>
</style>