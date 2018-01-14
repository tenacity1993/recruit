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

      .circle {
        display: block;
        position: absolute;
        top: 0px;
        left: rem(440);
        width: rem(100);
        height: rem(100);
        border-radius: 50%;
        background: #27e7c6;

        span {
          position: absolute;
          left: 50%;
          top: 50%;
          transform: translate(-50%, -50%);
          color: #fff;
          font-size: rem(24);
        }
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
        color: #fff;
        text-align: left;
        padding-top: rem(40);
        padding-left: rem(40);
        line-height: 1.8;
      }

      .line-1 {
        text-align: left;
        font-size: rem(28);
        line-height: 1.3;
      }

      .line-2 {
        display: inline-block;
        text-align: left;
        margin-top: rem(12);
        font-size: rem(28);
      }

      .line-bottom {
        text-align: right;
        display: inline-block;
        margin-top: rem(40);
        color: #fff;
        font-size: rem(32);
        animation: fadeIn 1000ms ease 600ms both running
      }
    }


  }

</style>
