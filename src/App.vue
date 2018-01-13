<template>
  <div id="app">
    <recruit></recruit>
    <div class="bottom">
      <i class="arrow"></i>
    </div>
  </div>
</template>

<script type="text/ecmascript-6">
import recruit from './components/recruit'

export default {
  name: 'app',
  components: {
    recruit
  }
}
</script>

<style lang="scss">
  * {
    margin: 0;
    padding: 0;
  }
  html,body {
    position: relative;
    height: 100%;
    font-family: 'PingFang SC', 'STHeitiSC-Light', 'Helvetica-Light', arial, sans-serif
  }
  body {
    background: #eee;
  }
  .bottom {
    position: fixed;
    top: 620px;
    left: 50%;
    margin-left: -20px;
    width: 40px;
    height: 20px;

    animation: mymove 1.5s infinite;

    @keyframes mymove
    {
      0% {
        top: 510px;
      }

      50% {
        top: 530px;
      }

      100% {
        top: 510px;
      }
    }
    .arrow {
      position: absolute;
      width: 100%;
      height: 100%;
      background: url("./assets/img/arrow.png") no-repeat center/100%;
    }
  }
</style>
