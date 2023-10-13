<template>
    <div class="image-slider">
      <swiper :options="swiperOptions">
        <swiper-slide v-for="(image, index) in images" :key="index">
          <img :src="image" alt="Imagen" />
        </swiper-slide>
      </swiper>
    </div>
  </template>
  
  <script>
  import { Swiper, SwiperSlide } from 'vue-awesome-swiper'
  
  export default {
    components: {
      Swiper,
      SwiperSlide,
    },
    data() {
      return {
        images: [
          '@/assets/imSlider1.jpg',
          '@/assets/imSlider2.png',
          '@/assets/imSlider3.jpg',
          // Agrega las URL de tus imágenes aquí
        ],
      }
    },
  }
  </script>
  
  <style scoped>
  .image-slider {
    max-width: 100%;
    overflow: hidden;
  }
  
  /* Estilos personalizados aquí */
  </style>
  