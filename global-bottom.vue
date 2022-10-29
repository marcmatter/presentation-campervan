<!-- global-bottom.vue -->

<template>
  <footer class="absolute bottom-0 left-0 p-2 w-full flex items-center justify-between">
    <link rel="stylesheet" href="https://cdn.bootcss.com/font-awesome/4.7.0/css/font-awesome.css" />
    <div :class="`pl-2 ${$slidev.nav.currentPage === 1 ? 'invisible' : 'visible'}`">
      <SlideCurrentNo /> / <SlidesTotal />
    </div>
    <div>
      <a 
        href="https://github.com/slidevjs/slidev"
        target="_blank"
        alt="GitHub"
        :class="`text-xl icon-btn opacity-50 !border-none ${$slidev.nav.currentPage === 1 ? '!hover:text-white text-white/75' : '!hover:text-black'}`"
      >
        <carbon-logo-github />
      </a>
    </div>
  </footer>
</template>

<script setup>
</script>