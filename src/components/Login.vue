<template>
  <div class="login_container">
    <div class="login_box">
      <div class="avatar_box">
        <img src="../assets/logo.png" alt="">
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Login'
}
</script>

<style lang="less" scoped>
  .login_container {
    background-color: #2d4d6d;
    height: 100%;
  }
  .login_box {
    width:450px;
    height: 300px;
    background-color: #fff;
    border-radius: 3px;
    position: absolute;
    left: 50%;
    top: 50%;
    transform: translate(-50%,-50%);

    .avatar_box {
      height: 130px;
      width: 130px;

      img {
        height: 130px;
        width: 130px;

      }
    }
  }
</style>
