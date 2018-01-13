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
