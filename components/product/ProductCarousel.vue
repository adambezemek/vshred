<template>
  <div class="carousel-max-width">
    <VueSlickCarousel :arrows="true" :dots="true">
      <div>
        <img src="~/assets/woman-running.jpg" alt="Woman Running" />
      </div>
      <div>
        <img src="https://via.placeholder.com/436x384" alt="Placeholder" />
      </div>
      <div>
        <img src="https://via.placeholder.com/436x384" alt="Placeholder" />
      </div>
      <div>
        <img src="https://via.placeholder.com/436x384" alt="Placeholder" />
      </div>
    </VueSlickCarousel>
  </div>
</template>

<script>
import VueSlickCarousel from "vue-slick-carousel";
import "vue-slick-carousel/dist/vue-slick-carousel.css";
// optional style for arrows & dots
import "vue-slick-carousel/dist/vue-slick-carousel-theme.css";

export default {
  name: "ProductCarousel",
  components: { VueSlickCarousel }
};
</script>

<style>
.slick-prev {
  left: 0;
  z-index: 1;
}
.slick-next {
  right: 0;
  z-index: 1;
}
.slick-dots {
  bottom: 5px;
}
.slick-dots li {
  margin: 0;
}
.slick-dots li.slick-active button:before {
  opacity: 1;
  color: white;
}
@media (min-width: 1024px) {
  .carousel-max-width {
    max-width: 436px;
  }
}
</style>
