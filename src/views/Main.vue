<template>
  <el-container style="height: 100%">
    <el-header><common-header></common-header></el-header>
    <el-main></el-main>
  </el-container>
</template>

<script>
import CommonHeader from '../components/CommonHeader'

export default {
  components: {
    CommonHeader
  }
}
</script>

<style lang="scss" scoped>
.el-header {
  background-color: rgb(255, 255, 255);
}
.el-main {
  padding-top: 0;
}
</style>
