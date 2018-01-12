<template>
    <div class="container">
      <img class="bg-img" src="../assets/img/bg1.gif" alt="">
      <div class="title-box">
        <i class="icon-left"></i>
        <span class="text-1">我们的福利 <br>Our welfare</span>
      </div>
      <div class="content-box-1">
        <p>弹性工作制 <br>
           7-15天年假 <br>
           5天全薪病假 <br>
           五险一金+商业保险 <br>
           有竞争力的薪酬 <br>
           短期/长期激励 <br>
           舒适的健身房 <br>
        </p>
      </div>
      <div class="content-box-2">
        <div class="title">
          <span class="title-1">工作环境 <br></span>
          <span class="title-2">work environment</span>
        </div>
        <div class="text">
          <i class="wave"></i>
          <i class="wave"></i>
          <p>
            自由的工作空间 <br>
            随意切换的工作状态 <br>
            体系化的培养平台 <br>
            多样化的学习形式 <br>
            志同道合的小伙伴 <br>
            欢迎来跟我们一起 <br>
            打造更卓越的技术团队 <br>
          </p>
        </div>
      </div>
      <div class="meituan-img"></div>
    </div>
</template>

<script>
    export default {
        name: "page3"
    }
</script>

<style scoped lang="scss">
  .container {
    position: relative;
    .bg-img {
      width: 375px;
      height: 667px;
    }
    .title-box {
      display: inline-block;
      position: absolute;
      vertical-align: top;
      width: 176px;
      height: 40px;
      top: 140px;
      left: 10px;
      font-size: 0;

      .icon-left {
        position: absolute;
        left: 0px;
        top: 0px;
        width: 56px;
        height: 32px;
        background: url("../assets/img/joinus2.png") no-repeat center/100%;
      }

      .text-1 {
        position: absolute;
        left: 76px;
        color: #fff;
        line-height: 1.2;
        font-size: 16px;
      }
    }
    .content-box-1 {
      position: absolute;
      top: 190px;
      left: 24px;
      width: 160px;
      height: 202px;
      border: 2px solid #27e8c8;
      p {
        margin: 0 auto;
        padding-left: 12px;
        font-size: 14px;
        line-height: 2.14;
        text-align: left;
        color: #fff;
      }
    }
    .content-box-2 {
      position: absolute;
      top: 242px;
      left: 200px;

      .title {
        font-size: 15px;
        color: #fff;
        line-height: 1.2;
        text-align: left;
      }
      .wave {
        display: block;
        padding-left: 10px;
        width: 31px;
        height: 7px;
        background: url("../assets/img/wave.png") no-repeat center/60%;
      }

      .text {
        padding-top: 10px;
        p {
          padding-top: 10px;
          font-size: 14px;
          text-align: left;
          color: #fff;
        }
      }
    }
    .meituan-img {
      position: absolute;
      top: 410px;
      left: 24px;
      width: 160px;
      height: 224px;
      /*background-color: #fff;*/
      background: url("../assets/img/meituan.png") no-repeat center/100%;
    }
  }
</style>
