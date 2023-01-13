<script setup>
</script>

<template>
  <div class="w-[40vh] h-[40vh] flex flex-wrap rounded-[1vw] overflow-hidden m-auto mt-8 relative" v-if="$slidev.nav.currentPage === 15">
    <div class="w-1/2 h-1/2 bg-[#b1be32] relative swot-item" v-motion :initial="{scale: 0, opacity: 0}" :enter="{scale: 1, opacity: 1, transition: {duration: 500}}">
      <div class="w-full h-full flex items-center justify-center text-8xl opacity-30">S</div>
      <div class="absolute top-0 left-0 w-full h-full flex items-center justify-center text-4xl">优势</div>
    </div>
    <div class="w-1/2 h-1/2 bg-[#ffa636] relative swot-item" v-motion :initial="{scale: 0, opacity: 0}" :enter="{scale: 1, opacity: 1, transition: {duration: 500}}">
      <div class="w-full h-full flex items-center justify-center text-8xl opacity-30">W</div>
      <div class="absolute top-0 left-0 w-full h-full flex items-center justify-center text-4xl">劣势</div>
    </div>
    <div class="w-1/2 h-1/2 bg-[#4d859e] relative swot-item" v-motion :initial="{scale: 0, opacity: 0}" :enter="{scale: 1, opacity: 1, transition: {duration: 500}}">
      <div class="w-full h-full flex items-center justify-center text-8xl opacity-30">O</div>
      <div class="absolute top-0 left-0 w-full h-full flex items-center justify-center text-4xl">机会</div>
    </div>
    <div class="w-1/2 h-1/2 bg-[#df4b4b] relative swot-item" v-motion :initial="{scale: 0, opacity: 0}" :enter="{scale: 1, opacity: 1, transition: {duration: 500}}">
      <div class="w-full h-full flex items-center justify-center text-8xl opacity-30">T</div>
      <div class="absolute top-0 left-0 w-full h-full flex items-center justify-center text-4xl">威胁</div>
    </div>
    <div class="absolute top-0 left-0 right-0 bottom-0 m-auto bg-white text-black font-bold flex items-center justify-center text-2xl w-[10vh] h-[10vh] rounded-[5vh] cursor-pointer">SWOT</div>
  </div>
</template>
