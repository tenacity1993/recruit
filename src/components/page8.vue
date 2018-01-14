<template>
  <div class="container">
    <img class="bg-img" src="../assets/img/bg1.gif" alt="">
    <div class="title-box">
      <i class="icon-left"></i>
      <span class="text-1">我们的愿景 <br>Our Vision</span>
    </div>
    <div class="content">
      <div class="text">
        <span class="line-1">JOIN US <br></span>
        <span class="line-2">一起打造最优秀的 <br>研发团队 <br></span>
        <span class="line-bottom">美旅技术团队</span>
      </div>
    </div>

  </div>
</template>

<script>
  export default {
    name: "page8"
  }
</script>

<style scoped lang="scss">

  @import "../assets/style/mixin";

  .container {
    position: relative;
    width: rem(750);
    height: rem(1334);
    .bg-img {
      width: rem(750);
      height: rem(1334);
    }
    .title-box {
      display: inline-block;
      position: absolute;
      vertical-align: top;
      width: rem(352);
      height: rem(80);
      top: rem(280);
      left: rem(20);
      font-size: 0;

      .icon-left {
        position: absolute;
        left: 0px;
        top: 0px;
        width: rem(112);
        height: rem(64);
        background: url("../assets/img/joinus2.png") no-repeat center/100%;
      }

      .text-1 {
        position: absolute;
        left: rem(152);
        color: #fff;
        line-height: 1.2;
        font-size: rem(32);
      }
    }

    .content {
      position: absolute;
      top: rem(448);
      margin: 0 rem(128);
      width: rem(488);
      height: rem(632);
      border: 2px solid #27e7c6;

      .text {
        margin-top: rem(120);
        color: #fff;
        text-align: center;
      }

      .line-1 {
        text-align: center;

        font-size: rem(64);
        line-height: 1.3;
      }

      .line-2 {
        display: inline-block;
        margin-top: 6px;
        font-size: rem(40);
      }

      .line-bottom {
        display: inline-block;
        margin-top: rem(120);
        color: #fff;
        font-size: rem(32);
        text-align: right;
        animation: fadeIn 1000ms ease 600ms both running
      }
    }


  }

</style>
