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
  .container {
    position: relative;
    width: 100%;
    height: 100%;
    .bg-img {
      width: 100%;
      height: 100%;
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

    .content {
      position: absolute;
      top: 224px;
      margin: 0 64px;
      width: 244px;
      height: 316px;
      border: 2px solid #27e7c6;

      .text {
        margin-top: 60px;
        color: #fff;
        text-align: center;
      }

      .line-1 {
        text-align: center;

        font-size: 32px;
        line-height: 1.3;
      }

      .line-2 {
        display: inline-block;
        margin-top: 6px;
        font-size: 20px;
      }

      .line-bottom {
        display: inline-block;
        margin-top: 60px;
        color: #fff;
        font-size: 16px;
        text-align: right;
        animation: fadeIn 1000ms ease 600ms both running
      }
    }


  }

</style>
