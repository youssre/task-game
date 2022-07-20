<template>
  <swiper
    :slides-per-view="4"
    :space-between="100"
    :loop="true"
    @swiper="onSwiper"
    @slideChange="onSlideChange"
  >
    <swiper-slide>
      <router-link to="#">
        <img class="rounded " src="@/assets/swip1.png" alt="">
      </router-link>
    </swiper-slide>
    <swiper-slide>
      <router-link to="#">
        <img class="rounded " src="@/assets/swip2.png" alt="">
      </router-link>
    </swiper-slide>
    <swiper-slide>
      <router-link to="#">
        <img class="rounded " src="@/assets/swip3.png" alt="">
      </router-link>
    </swiper-slide>
    <swiper-slide>
      <router-link to="#">
        <img class="rounded " src="@/assets/swip4.png" alt="">
      </router-link>
    </swiper-slide>
    <swiper-slide>
      <router-link to="#">
        <img class="rounded " src="@/assets/swip5.png" alt="">
      </router-link>
    </swiper-slide>

  </swiper>
</template>
<script>
  // Import Swiper Vue.js components
  import { Swiper, SwiperSlide } from 'swiper/vue';

  // Import Swiper styles
  import 'swiper/css';

  export default {
    components: {
      Swiper,
      SwiperSlide,
    },
    setup() {
      const onSwiper = (swiper) => {
        console.log(swiper);
      };
      const onSlideChange = () => {
        console.log('slide change');
      };
      return {
        onSwiper,
        onSlideChange,
      };
    },
  };
</script>
<style scoped>
img{
    width: 100px;
    margin-right: 10px;
}
</style>
