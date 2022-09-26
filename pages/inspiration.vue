<script setup lang="ts">

</script>

<template>
  <div class="bg-white py-6 sm:py-8 lg:py-12">
  <div class="max-w-screen-2xl px-4 md:px-8 mx-auto">
    <div class="flex justify-between items-center gap-8 mb-4 sm:mb-8 md:mb-12">
      <div class="flex items-center gap-12">
        <h2 class="text-gray-800 text-2xl lg:text-3xl font-bold">My Inspirations</h2>

        <p class="max-w-screen-sm hidden md:block text-gray-500">
        We should always have some <mark> aim in life </mark> which we must try to achieve while being of help tp others - Sudha Murthy </p>
      </div>

     
    </div>

    <div class="grid grid-cols-2 sm:grid-cols-3 gap-4 md:gap-6 xl:gap-8">
      <!-- image - start -->
      <a href="#" class="group h-48 md:h-80 flex items-end bg-gray-100 overflow-hidden rounded-lg shadow-lg relative">
        <img src="/images/malala.webp" loading="lazy" alt="Photo by Minh Pham" class="w-full h-full object-cover object-center absolute inset-0 group-hover:scale-110 transition duration-200" />

        <div class="bg-gradient-to-t from-gray-800 via-transparent to-transparent opacity-50 absolute inset-0 pointer-events-none"></div>

        <span class="inline-block text-white text-sm md:text-lg relative ml-4 md:ml-5 mb-3">Malala Yousafzai</span>
      </a>
      <!-- image - end -->

      <!-- image - start -->
      <a href="#" class="group h-48 md:h-80 md:col-span-2 flex items-end bg-gray-100 overflow-hidden rounded-lg shadow-lg relative">
        <img src="/images/kailashji.webp" loading="lazy" alt="Photo by Magicle" class="w-full h-full object-cover object-center absolute inset-0 group-hover:scale-110 transition duration-200" />

        <div class="bg-gradient-to-t from-gray-800 via-transparent to-transparent opacity-50 absolute inset-0 pointer-events-none"></div>

        <span class="inline-block text-white text-sm md:text-lg relative ml-4 md:ml-5 mb-3">
        Kaliash Satyarthi
        </span>
      </a>
      <!-- image - end -->

      <!-- image - start -->
      <a href="#" class="group h-48 md:h-80 md:col-span-2 flex items-end bg-gray-100 overflow-hidden rounded-lg shadow-lg relative">
        <img src="/images/murtyji.webp" loading="lazy" alt="Photo by Martin Sanchez" class="w-full h-full object-cover object-center absolute inset-0 group-hover:scale-110 transition duration-200" />

        <div class="bg-gradient-to-t from-gray-800 via-transparent to-transparent opacity-50 absolute inset-0 pointer-events-none"></div>

        <span class="inline-block text-white text-sm md:text-lg relative ml-4 md:ml-5 mb-3">Sudha Murthy</span>
      </a>
      <!-- image - end -->

      <!-- image - start -->
      <a href="#" class="group h-48 md:h-80 flex items-end bg-gray-100 overflow-hidden rounded-lg shadow-lg relative">
        <img src="/images/dy.webp" loading="lazy" alt="Photo by Lorenzo Herrera" class="w-full h-full object-cover object-center absolute inset-0 group-hover:scale-110 transition duration-200" />

        <div class="bg-gradient-to-t from-gray-800 via-transparent to-transparent opacity-50 absolute inset-0 pointer-events-none"></div>

        <span class="inline-block text-white text-sm md:text-lg relative ml-4 md:ml-5 mb-3">Hon'ble D.Y. Chandrachud</span>
      </a>
      <!-- image - end -->
    </div>
  </div>
</div>
</template>
