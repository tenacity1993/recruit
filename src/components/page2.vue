<template>
  <div class="container">
    <img class="bg-img" src="../assets/img/bg1.gif" alt="">
    <div class="head">
      <i class="head-img"></i>
      <i class="icon-circle"></i>
      <span class="text-aboutus">关于我们</span>
    </div>
    <div class="img-aboutus"></div>
    <div class="medal"></div>
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
  .container {
    position: relative;
    width: 100%;
    height: 100%;
    .bg-img {
      width: 100%;
      height: 100%;
    }
    .head {
      display: inline-block;
      position: absolute;
      top: 128px;
      left: 20px;
      width: 200px;
      height: 42px;
      text-align: left;
      border-bottom: 2px solid #fff;
      font-size: 0;
      .head-img {
        display: inline-block;
        vertical-align: middle;
        width: 150px;
        height: 42px;
        background: url("../assets/img/aboutus1.png") no-repeat center/90%;
      }
      .icon-circle {
        display: inline-block;
        vertical-align: middle;
        margin-left: 20px;
        width: 18px;
        height: 18px;
        background: url("../assets/img/circle.png") no-repeat center/100%;
      }
      .text-aboutus {
        display: inline-block;
        margin: 3px 0 10px 100px;
        font-weight: 700;
        font-size: 20px;
        color: #fff;
      }
    }

    .content {
      position: absolute;
      top: 260px;
      left: 82px;
      width: 264px;
      height: 348px;
      border: 2px solid #27e7c6;
      color: #fff;
      .title-1 {
        font-size: 16px;
      }
      p {
        margin: 0 auto;
        text-align: center;
        text-indent: 32px;
        width: 80%;
        padding-top: 50px;
        text-align: left;
        font-size: 12px;
        line-height: 2;
        .title-2 {
          font-size: 16px;
        }
      }
    }

    .img-aboutus {
      position: absolute;
      left: 10px;
      top: 390px;
      width: 35px;
      height: 218px;
      background: url("../assets/img/aboutus2.png") no-repeat center/100%;
    }
    .medal {
      position: absolute;
      z-index: 3;
      top: 260px;
      left: 82px;
      width: 65px;
      height: 81px;
      background: #27e7c6 url("../assets/img/medal.jpg") no-repeat center/100%;
      transform: translate(-50%, -50%);

    }
  }

</style>
