<template>
  <div id="app">
    <audio src=""></audio>
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

  @import "./assets/style/mixin";
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
    top: rem(1240);
    left: 50%;
    margin-left: rem(-40);
    width: rem(80);
    height: rem(40);

    animation: mymove 1.5s infinite;

    @keyframes mymove
    {
      0% {
        top: rem(1200);
      }

      50% {
        top: rem(1060);
      }

      100% {
        top: rem(1200);
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
