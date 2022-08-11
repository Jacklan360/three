<template>
  <div class="title-box">
      <div class="left">
        <img src="../assets/logo.png" alt="">
        <H4>招聘网站</H4>
      </div>
      <div class="right">
        发部
      </div>
  </div>
</template>

<script>
import {defineComponent} from 'vue'
export default defineComponent({
  setup() {
    return {}
  }
})
</script>

<style scoped>
.title-box{
  height: 100px;
  display: flex;
  justify-content: space-between;
  align-items: center;
}
</style>
