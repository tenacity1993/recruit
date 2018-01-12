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
      <div class="title"><span>Java工程师</span></div>
      <img class="img-left-1" src="../assets/img/weneedyou.png" alt="">
      <div class="text">
        <p>岗位职责： <br>
          1.负责业务平台系统API设计和核心功能开发；<br>
          2.负责系统核心功能设计与相关文档的编写；<br>
          3.负责业务研发计划制定和进度推进。<br>
          任职要求：<br>
          1.计算机或相关专业本科以上学历；<br>
          2.熟练掌握Java语言，熟悉 Spring、SpringMVC、mybatis等框架；<br>
          3.熟悉mysql、redis等数据库，熟悉数据库优化；<br>
          4.互联网5年以上工作经验，3年以上系统架构设计经验；<br>
          5.有很强的计划与执行能力、项目管理能力，有丰富的项目管理经验。<br>
          6.具有较强学习能力、自我驱动能力、责任感。<br>
        </p>
      </div>
    </div>
  </div>

</template>

<script>
  export default {
    name: "page4"
  }
</script>

<style scoped lang="scss">
  .container {
    position: relative;
    .bg-img {
      width: 375px;
      height: 667px;
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
