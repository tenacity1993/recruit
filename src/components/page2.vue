<template>
  <div class="container">
    <img class="bg-img" src="../assets/img/bg1.gif" alt="">
    <div class="head">
      <i class="head-img"></i>
      <i class="icon-circle"></i>
      <span class="text-aboutus">关于我们</span>
    </div>
    <div class="img-aboutus"></div>
    <img class="medal" src="../assets/img/medal.jpg">
    <div class="content">
      <span class="title-1">美团平台与酒旅事业群</span>
      <p>
        <span class="title-2">境外度假北京团队</span>
        是美团酒旅在2017年新成立的团队，目前团队规模有三十余人。境外度假是酒旅平台一个新的突破点，在2018年将会持续发力。
      </p>
    </div>
  </div>
</template>

<script>
  export default {
    name: "page2"
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
    .head {
      display: inline-block;
      position: absolute;
      top: rem(256);
      left: rem(40);
      width: rem(400);
      height: rem(84);
      text-align: left;
      border-bottom: 2px solid #fff;
      font-size: 0;
      .head-img {
        display: inline-block;
        vertical-align: middle;
        width: rem(300);
        height: rem(84);
        background: url("../assets/img/aboutus1.png") no-repeat center/90%;
      }
      .icon-circle {
        display: inline-block;
        vertical-align: middle;
        margin-left: rem(40);
        width: rem(36);
        height: rem(36);
        background: url("../assets/img/circle.png") no-repeat center/100%;
      }
      .text-aboutus {
        display: inline-block;
        margin: rem(6) 0 rem(20) rem(200);
        font-weight: 700;
        font-size: rem(40);
        color: #fff;
      }
    }

    .content {
      position: absolute;
      top: rem(520);
      left: rem(164);
      width: rem(528);
      height: rem(696);
      border: 2px solid #27e7c6;
      color: #fff;
      .title-1 {
        font-size: rem(32);
      }
      p {
        margin: 0 auto;
        text-align: center;
        text-indent: rem(64);
        width: 80%;
        padding-top: rem(100);
        text-align: left;
        font-size: rem(24);
        line-height: 2;
        .title-2 {
          font-size: rem(32);
        }
      }
    }

    .img-aboutus {
      position: absolute;
      left: rem(20);
      top: rem(780);
      width: rem(70);
      height: rem(436);
      background: url("../assets/img/aboutus2.png") no-repeat center/100%;
    }
    .medal {
      position: absolute;
      z-index: 3;
      top: rem(520);
      left: rem(164);
      width: rem(130);
      height: rem(162);
      transform: translate(-50%, -50%);

    }
  }

</style>
