<template lang="pug">
div.container
  div.login-box
    el-input(:span="6", :offset="6", placeholder="请输入用户名")
    el-input(:span="6", :offset="6", placeholder="请输入密码")
    el-button(type="primary",:disabled="true", @click="login()") 登录
</template>

<script>
  export default {
    data () {
      return {
        msg: 'Login'
      }
    }
  }

</script>
<style type="text/css" lang="scss" scoped="">
  .container {
    position: absolute;
    width: 100%;
    height: 100%;
    left: 0;
    top: 0;
    background: url("../assets/bg.jpg") no-repeat;
    .login-box {
      width:400px;
      height: 200px;
      position: fixed;
      top: 50%;
      left: 50%;
      transform: translate(-200px,-100px);
      padding: 20px 40px;
      background-color: #fff;
      border-radius: 8px;
      .el-input{
        margin-bottom: 30px;
      }
      .el-button{
        width: 50%;
        height: 40px;
      }
    }
  }
</style>
