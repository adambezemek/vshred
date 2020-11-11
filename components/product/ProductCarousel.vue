<template>
  <div class="carousel-max-width">
    <VueSlickCarousel :arrows="true" :dots="true">
      <div>
        <img src="~/assets/woman-running.jpg" alt="Woman Running" />
      </div>
      <div>
        <img
          src="https://via.placeholder.com/436x384"
          loading="lazy"
          alt="Placeholder"
        />
      </div>
      <div>
        <img
          src="https://via.placeholder.com/436x384"
          loading="lazy"
          alt="Placeholder"
        />
      </div>
      <div>
        <img
          src="https://via.placeholder.com/436x384"
          loading="lazy"
          alt="Placeholder"
        />
      </div>
    </VueSlickCarousel>
  </div>
</template>

<script>
import VueSlickCarousel from "vue-slick-carousel";

export default {
  name: "ProductCarousel",
  components: { VueSlickCarousel }
};
</script>
