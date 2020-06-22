<template>
  <header>
    <div class="left-cotent">
      <img class="headerimg" src="../assets/images/logo.png" />
    </div>
    <div class="searchbox">
      <el-input size="medium" v-model="input" placeholder="Search"></el-input>
    </div>
    <div class="right-cotent">
      <el-button class="login_btn" type="text">Login</el-button>
      <el-button class="register_btn" type="text">Register</el-button>
    </div>
  </header>
</template>

<script>
export default {}
</script>

<style lang="scss" scoped>
header {
  display: flex;
  height: 100%;
  align-items: center;
  justify-content: space-between;
  .right-content {
    justify-content: space-between;
    .login_btn {
      color: black;
    }
  }
}
</style>
