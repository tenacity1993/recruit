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
      <div class="title"><span>iOS高级开发工程师</span></div>
      <img class="img-left-1" src="../assets/img/weneedyou.png" alt="">
      <div class="text">
        <p>工作职责 <br>
          1.负责境外度假业务的研发工作，完善代码复用方案 <br>
          2.提升境外场景下的应用体验，调研新技术 <br>
          职位要求 <br>
          1.3年或以上iOS开发经验，熟练掌握iOS开发、测试、调优等技术以及相关工具的使用 <br>
          2.具有扎实的Objective-C语言基础，理解Objective-C Runtime和内存管理机制，熟练使用多线程、网络编程等技术 <br>
          3.具备复杂应用的架构设计能力，熟悉敏捷开发及项目管理流程 <br>
          4.积极主动，有良好的团队合作精神和强烈的责任感，对移动产品有浓厚兴趣及见解 <br>
        </p>
      </div>
    </div>
  </div>

</template>

<script>
  export default {
    name: "page6"
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
