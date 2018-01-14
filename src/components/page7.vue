<template>
  <div class="container">
    <img class="bg-img" src="../assets/img/bg2.gif" alt="">
    <img class="bg-img-boy" src="../assets/img/boy.gif" alt="">
    <div class="sologn">
      <span class="line-1">不做别人的影子， <br></span>
      <p class="line-2">活出自己的样子! <br></p>
      <span class="line-3">——境外度假北京团队等你 <br></span>
    </div>
    <div class="content">
      <div class="title"><span>FE高级开发工程师</span></div>
      <img class="img-left-1" src="../assets/img/weneedyou.png" alt="">
      <div class="text">
        <p>工作职责 <br>
          1.负责境外度假业务用户端和商户端的研发工作 <br>
          2.关注代码质量、研发效率、用户体验 <br>
          职位要求 <br>
          1.熟悉Mobile Web/Hybrid Web App等开发 <br>
          2.注重细节的习惯，大胆假设、小心求证的态度 <br>
          3.深入分析理解业务需求，承担复杂的任务，高质量的产出 <br>
          4.捕获灵感，创造性解决问题的思路，提升界面交互和代码执行效率 <br>
          5.指导低层级的工程师完成业绩、素质和技能的提升 <br>
        </p>
      </div>
    </div>
  </div>

</template>

<script>
  export default {
    name: "page7"
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
    .bg-img-boy {
      width: rem(124);
      height: rem(176);
      position: absolute;
      left: rem(52);
      top: rem(440);
    }

    .sologn {
      position: absolute;
      left: rem(40);
      top: rem(40);
      color: #fff;
      font-size: rem(24);
      text-align: left;

      .line-2 {
        text-indent: rem(96);
      }

      .line-3 {
        display: block;
        margin-top: rem(40);
        margin-left: rem(300);
      }

    }

    .content {
      .title {
        position: absolute;
        top: rem(636);
        left: rem(132);
        width: rem(520);
        height: rem(60);
        border: 2px solid #27e7c6;
        border-radius: rem(60);
        background-color: #27e7c6;

        span {
          line-height: rem(60);
          text-align: center;
        }
      }

      .img-left-1 {
        position: absolute;
        top: rem(740);
        left: rem(44);
        width: rem(36);
        height: rem(244);
      }

      .text {
        position: absolute;
        padding: rem(20);
        width: rem(560);
        top: rem(712);
        left: rem(120);
        border-left: 2px solid #27e7c6;
        border-right: 2px solid #27e7c6;;

        p {
          font-size: rem(24);
          line-height: 1.5;
          text-align: left;
          color: #fff;
        }
      }
    }

  }
</style>
