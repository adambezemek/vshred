<template>
  <div
    class="mt-2 w-full lg:bg-white lg:mt-0 lg:p-4 lg:absolute lg:top-0 lg:right-0 lg:h-full product-details-max-width"
  >
    <h2 class="uppercase font-bold text-2xl lg:text-xl">Essential Leggings</h2>
    <div
      class="text-brand-red line-through italic font-bold text-sm lg:text-xs"
    >
      $49.99
    </div>
    <div class="font-bold text-xl mb-4 lg:text-base lg:mb-2">$39.99</div>
    <div class="text-xs"><span class="font-bold">Color:</span> Sage Green</div>
    <div class="flex flex-wrap my-2 lg:justify-between">
      <div
        class="rounded-full border-2 border-transparent hover:border-white cursor-pointer h-8 w-8 flex items-center justify-center mr-1"
        style="background-color: #2D2D2F"
      ></div>
      <div
        class="rounded-full border-2 border-transparent hover:border-white cursor-pointer h-8 w-8 flex items-center justify-center mr-1"
        style="background-color: #223A5E"
      ></div>
      <div
        class="rounded-full border-2 border-transparent hover:border-white cursor-pointer h-8 w-8 flex items-center justify-center mr-1"
        style="background-color: #B71234"
      ></div>
      <div
        class="rounded-full border-2 border-transparent hover:border-white cursor-pointer h-8 w-8 flex items-center justify-center mr-1"
        style="background-color: #A7AE9E"
      ></div>
      <div
        class="rounded-full border-2 border-transparent hover:border-white cursor-pointer h-8 w-8 flex items-center justify-center mr-1"
        style="background-color: #C0AABF"
      ></div>
      <div
        class="rounded-full border-2 border-transparent hover:border-white cursor-pointer h-8 w-8 flex items-center justify-center mr-1"
        style="background-color: #B0C3D2"
      ></div>
      <div
        class="rounded-full border-2 border-transparent hover:border-white cursor-pointer h-8 w-8 flex items-center justify-center"
        style="background-color: #666563"
      ></div>
    </div>
    <div class="flex justify-between">
      <div class="text-xs mb-2">
        <span class="font-bold">Size:</span> Medium
      </div>
      <a
        href="javascript:void(0);"
        class="text-xs text-blue-400 underline hover:no-underline"
      >
        Size Guide
      </a>
    </div>
    <div class="flex flex-wrap">
      <div
        class="bg-gray-300 border-2 border-transparent hover:border-gray-600 cursor-pointer font-bold text-sm h-8 w-8 flex justify-center items-center mr-1"
      >
        XS
      </div>
      <div
        class="bg-gray-300 border-2 border-transparent hover:border-gray-600 cursor-pointer font-bold text-sm h-8 w-8 flex justify-center items-center mr-1"
      >
        S
      </div>
      <div
        class="bg-gray-300 border-2 border-transparent hover:border-gray-600 cursor-pointer font-bold text-sm h-8 w-8 flex justify-center items-center mr-1"
      >
        M
      </div>
      <div
        class="bg-gray-300 border-2 border-transparent hover:border-gray-600 cursor-pointer font-bold text-sm h-8 w-8 flex justify-center items-center mr-1"
      >
        L
      </div>
      <div
        class="bg-gray-300 border-2 border-transparent hover:border-gray-600 cursor-pointer font-bold text-sm h-8 w-8 flex justify-center items-center mr-1"
      >
        XL
      </div>
    </div>

    <ul
      class="list-disc ml-5 mt-5 lg:mt-2 font-semibold italic text-sm lg:text-xs"
    >
      <li class="mb-1">Body Contouring & Breathable</li>
      <li class="mb-1">High waisted ribbed waistband</li>
      <li class="mb-1">Moisture-Wicking</li>
      <li class="mb-1">Buttery-soft stretchy Fabric</li>
    </ul>

    <button
      class="uppercase bg-brand-red text-white border-4 border-transparent hover:bg-gray-100 hover:text-brand-red hover:border-brand-red font-bold w-full py-2 text-center my-5 lg:my-2 "
    >
      Add to Order
    </button>
  </div>
</template>

<style>
@media (min-width: 1024px) {
  .product-details-max-width {
    max-width: 300px;
  }
}
</style>
