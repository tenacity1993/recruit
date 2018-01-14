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
  @import "../assets/style/mixin";

  .container {
    position: relative;
    width: rem(750);
    height: rem(1334);
    .bg-img {
      width: rem(750);
      height: rem(1334);
    }
    .text {
      .right-icon {
        position: absolute;
        z-index: 2;
        top: rem(40);
        right: rem(40);
        width: rem(376);
        height: rem(228);
        background: url("../assets/img/joinus1.png") no-repeat center/100%;
      }
      .title-1 {
        position: absolute;
        left: rem(140);
        top: rem(140);
        color: #fff;
        font-size: rem(32);
        line-height: 1.8;
      }
      .title-2 {
        position: absolute;
        left: rem(108);
        top: rem(200);
        color: #fff;
        font-size: rem(46);
        line-height: 1.5;
      }
      .title-3 {
        position: absolute;
        width: rem(400);
        left: rem(48);
        top: rem(280);
        background-color: #fffa7c;
        font-size: rem(28);
        color: #000;
        line-height: 1.8;
      }
      .icon-circle {
        position: absolute;
        top: rem(360);
        left: rem(260);
        width: rem(36);
        height: rem(36);
        background: url("../assets/img/circle.png") no-repeat center/100%;
      }
    }
    .sologn {
      position: absolute;
      top: rem(400);
      right: rem(40);
      p {
        font-size: rem(28);
        line-height: 2;
        text-align: right;
        color: #fff;
      }
    }

  }

</style>
