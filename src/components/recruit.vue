<template>
  <swiper :options="swiperOption" class="swiper-box">
    <swiper-slide class="swiper-item"><page1></page1></swiper-slide>
    <swiper-slide class="swiper-item"><page2></page2></swiper-slide>
    <swiper-slide class="swiper-item"><page3></page3></swiper-slide>
    <swiper-slide class="swiper-item"><page4></page4></swiper-slide>
    <swiper-slide class="swiper-item"><page5></page5></swiper-slide>
    <swiper-slide class="swiper-item"><page6></page6></swiper-slide>
    <swiper-slide class="swiper-item"><page7></page7></swiper-slide>
    <swiper-slide class="swiper-item"><page8></page8></swiper-slide>
    <swiper-slide class="swiper-item"><page9></page9></swiper-slide>
    <div class="swiper-pagination" slot="pagination"></div>
  </swiper>

</template>

<script type="text/ecmascript-6">
  import { swiper, swiperSlide } from 'vue-awesome-swiper'
  import page1 from '../components/page1'
  import page2 from './page2'
  import page3 from './page3'
  import page4 from './page4'
  import page5 from './page5'
  import page6 from './page6'
  import page7 from './page7'
  import page8 from './page8'
  import page9 from './page9'


  export default {
    data() {
      return {
        swiperOption: {
          direction: 'vertical',
          slidesPerView: 1,
          spaceBetween: 30,
          mousewheel: true,
          pagination: {
            el: '.swiper-pagination',
            clickable: true
          }
        }
      }
    },
    components: {
      swiper,
      swiperSlide,
      page1,
      page2,
      page3,
      page4,
      page5,
      page6,
      page7,
      page8,
      page9
    }
  }
</script>

<style lang="scss">
  .swiper-box {
    width: 100vw;
    height: 100vh;
    margin: 0 auto;
  }
  .swiper-item {
    height: 100%;
    text-align: center;
    font-size: 18px ;
    background: #fff;
    /* Center slide text vertically */
    display: -webkit-box;
    display: -ms-flexbox;
    display: -webkit-flex;
    display: flex;
    -webkit-box-pack: center;
    -ms-flex-pack: center;
    -webkit-justify-content: center;
    justify-content: center;
    -webkit-box-align: center;
    -ms-flex-align: center;
    -webkit-align-items: center;
    align-items: center;
  }
</style>
