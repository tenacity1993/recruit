<template>
  <swiper :options="swiperOption" class="swiper-box">
    <swiper-slide class="swiper-item"><page1></page1></swiper-slide>
    <swiper-slide class="swiper-item"><page2></page2></swiper-slide>
    <swiper-slide class="swiper-item"><page3></page3></swiper-slide>
    <swiper-slide class="swiper-item"><page4></page4></swiper-slide>
    <swiper-slide class="swiper-item">Slide 5</swiper-slide>
    <swiper-slide class="swiper-item">Slide 6</swiper-slide>
    <swiper-slide class="swiper-item">Slide 7</swiper-slide>
    <swiper-slide class="swiper-item">Slide 8</swiper-slide>
    <swiper-slide class="swiper-item">Slide 9</swiper-slide>
    <swiper-slide class="swiper-item">Slide 10</swiper-slide>
    <div class="swiper-pagination" slot="pagination"></div>
  </swiper>

</template>

<script type="text/ecmascript-6">
  import { swiper, swiperSlide } from 'vue-awesome-swiper'
  import page1 from '../components/page1'
  import page2 from './page2'
  import page3 from './page3'
  import page4 from './page4'

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
      page4
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
