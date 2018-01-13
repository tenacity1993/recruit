<template>
  <div class="container">
    <img class="bg-img" src="../assets/img/bg1.gif" alt="">
    <div class="title-box">
      <i class="icon-left"></i>
      <span class="text-1">加入我们 <br>一起创造未来</span>
      <div class="circle"> <span>官网</span></div>
    </div>
    <div class="content">
      <div class="text">
        <span class="line-1">JOIN US <br></span>
        <span class="line-2">  邮箱： <br>  miaowen@meituan.com <br>  标题： <br> 【应聘岗位+工作地点+姓名+电话】<br>
          附件：您的简历 <br>   办公地点：北京朝阳区恒电大厦</span>
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

      .circle {
        display: block;
        position: absolute;
        top: 0px;
        left: 220px;
        width: 50px;
        height: 50px;
        border-radius: 50%;
        background: #27e7c6;

        span {
          position: absolute;
          left: 50%;
          top: 50%;
          transform: translate(-50%, -50%);
          color: #fff;
          font-size: 12px;
        }
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
        color: #fff;
        text-align: left;
        padding-top: 20px;
        padding-left: 20px;
        line-height: 1.8;
      }

      .line-1 {
        text-align: left;
        font-size: 14px;
        line-height: 1.3;
      }

      .line-2 {
        display: inline-block;
        text-align: left;
        margin-top: 6px;
        font-size: 14px;
      }

      .line-bottom {
        text-align: right;
        display: inline-block;
        margin-top: 20px;
        color: #fff;
        font-size: 16px;
        animation: fadeIn 1000ms ease 600ms both running
      }
    }


  }

</style>
