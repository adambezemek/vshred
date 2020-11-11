<template>
  <div>
    <Header />
    <div class="p-4 mx-auto">
      <h2
        class="uppercase font-bold text-center text-2xl mb-3 lg:text-5xl lg:my-8"
      >
        Complete the Look
      </h2>
      <div class="product-max-width mx-auto lg:shadow-lg lg:relative">
        <ProductCarousel />
        <ProductDetails />
      </div>
      <a
        href="javascript:void(0);"
        class="block w-full text-center text-gray-500 underline hover:no-underline mt-2 lg:mt-10"
        >No Thanks</a
      >
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style>
html,
body {
  font-family: "Montserrat", sans-serif;
}
.product-max-width {
  max-width: 345px;
}
@media (min-width: 1024px) {
  .product-max-width {
    max-width: 736px;
    max-height: 384px;
  }
}
</style>
