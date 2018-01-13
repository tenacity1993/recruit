<template>
  <div class="container">
    <img class="bg-img" src="../assets/img/bg.gif" alt="">
    <div class="text">
      <div class="right-icon"></div>
      <transition enter-active-class="animated fadeInRight" leave-active-class="animated fadeOutLeft">
        <div class="title-1">美团点评</div>
      </transition>
      <div class="title-2">境外度假</div>
      <div class="title-3">Java · Android · iOS · FE</div>
      <i class="icon-circle"></i>
    </div>
    <div class="sologn">
      <p>有些事 不去做 <br>
        一辈子都无法判断 <br>
        是失败 还是 成功 <br>
      </p>
    </div>
  </div>
</template>

<script type="text/ecmascript-6">
  export default {
    name: "page1"
  }
</script>

<style scoped lang="scss">

  /*@import "../assets/style/font.scss";*/

  .container {
    position: relative;
    width: 100%;
    height: 100%;
    .bg-img {
      width: 100%;
      height: 100%;
    }
    .text {
      .right-icon {
        position: absolute;
        z-index: 2;
        top: 20px;
        right: 20px;
        width: 188px;
        height: 114px;
        background: url("../assets/img/joinus1.png") no-repeat;
      }
      .title-1 {
        position: absolute;
        left: 70px;
        top: 70px;
        color: #fff;
        font-size: 16px;
        line-height: 1.8;
      }
      .title-2 {
        position: absolute;
        left: 54px;
        top: 100px;
        color: #fff;
        font-size: 23px;
        line-height: 1.5;
      }
      .title-3 {
        position: absolute;
        width: 200px;
        left: 24px;
        top: 140px;
        background-color: #fffa7c;
        font-size: 14px;
        color: #000;
        line-height: 1.8;
      }
      .icon-circle {
        position: absolute;
        top: 180px;
        left: 130px;
        width: 18px;
        height: 18px;
        background: url("../assets/img/circle.png") no-repeat center/100%;
      }
    }
    .sologn {
      position: absolute;
      top: 200px;
      right: 20px;
      p {
        font-size: 14px;
        line-height: 2;
        text-align: right;
        color: #fff;
      }
    }

  }

</style>
