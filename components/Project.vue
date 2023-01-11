<script setup>

</script>

<template>
  <div class="w-full h-full" v-if="$slidev.nav.currentPage === 2">
    <div v-motion :initial="{ x: -80, opacity: 0 }" :enter="{ x: 0, opacity: 1 }">
      测试
    </div>
    <div v-motion :initial="{ x: -90, opacity: 0 }" :enter="{ x: 0, opacity: 1, transition: {delay: 200}}">
      测试1
    </div>
    <div v-motion :initial="{ x: -100, opacity: 0 }" :enter="{ x: 0, opacity: 1, transition: {delay: 400} }">
      测试2
    </div>
    <div v-motion :initial="{ x: -120, opacity: 0 }" :enter="{ x: 0, opacity: 1, transition: {delay: 600} }">
      测试3
    </div>
  </div>
</template>