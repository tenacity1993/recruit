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
  .container {
    position: relative;
    width: 100%;
    height: 100%;
    .bg-img {
      width: 100%;
      height: 100%;
    }
    .bg-img-boy {
      width: 62px;
      height: 88px;
      position: absolute;
      left: 26px;
      top: 220px;
    }

    .sologn {
      position: absolute;
      left: 20px;
      top: 20px;
      color: #fff;
      font-size: 12px;
      text-align: left;

      .line-2 {
        text-indent: 48px;
      }

      .line-3 {
        display: block;
        margin-top: 20px;
        margin-left: 150px;
      }

    }

    .content {
      .title {
        position: absolute;
        top: 318px;
        left: 66px;
        width: 260px;
        height: 30px;
        border: 2px solid #27e7c6;
        border-radius: 30px;
        background-color: #27e7c6;

        span {
          line-height: 30px;
          text-align: center;
        }
      }

      .img-left-1 {
        position: absolute;
        top: 370px;
        left: 22px;
        width: 18px;
        height: 122px;
      }

      .text {
        position: absolute;
        padding: 10px;
        width: 280px;
        top: 356px;
        left: 60px;
        border-left: 2px solid #27e7c6;
        border-right: 2px solid #27e7c6;;

        p {
          font-size: 12px;
          line-height: 1.5;
          text-align: left;
          color: #fff;
        }
      }
    }

  }
</style>
