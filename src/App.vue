<!-- 定义生成HTML代码 -->
<template>
  <div >
    <!-- <h1>{{ message }}</h1> -->
    <element-view></element-view>
  </div>
</template>

<script>
import ElementView from './views/element/ElementView.vue'
export default {
  components: { ElementView },
  data() {
    return {
      message:"Hello Vue"
    }
  },
}
</script>

<!-- 控制css样式 -->
<style>
h1{
  color: brown;
  display: flex;
  align-items: center;
  justify-content: center;
}
</style>
