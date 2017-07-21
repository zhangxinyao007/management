<template lang="pug">
  div.main-box
    div.left-block
      span 左边
    div.right-block
</template>

<script type="text/javascript">

</script>
<style type="text/css" lang="scss" scoped="">
  .main-box{
    width: 100%;
    height: 100%;
    .left-block{
      position: fixed;
      width: 200px;
      height: 100%;
      background-color: antiquewhite;
      z-index: 111;
    }
    .right-block{
      position: absolute;
      min-height: 100%;
      left: 0;
      right: 0;
      margin-left: 200px;
      background-color: aquamarine;
    }
  }
</style>
