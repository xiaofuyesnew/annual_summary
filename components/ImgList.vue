<script setup>
import w_1 from '../images/w_1.jpg'
import w_2 from '../images/w_2.png'
import w_3 from '../images/w_3.jpg'

const list = [
  {
    image: w_1,
    text: '旭辉铂悦湘江'
  },
  {
    image: w_2,
    text: '旭辉铂悦湘江'
  },
  {
    image: w_3,
    text: '旭辉铂悦湘江'
  }
]

</script>

<template>
  <div class="w-full h-10/12 flex items-center justify-around" v-if="$slidev.nav.currentPage === 7">
    <div class="flex flex-col w-1/5 items-center h-full justify-between py-4" v-motion :initial="{opacity: 0, y: 100}" :enter="{opacity: 1, y: 0, transition: {delay: 0}}">
      <img :src="list[0].image" />
      <div>{{ list[0].text }}</div>
    </div>
    <div class="flex flex-col w-1/5 items-center h-full justify-between py-4" v-motion :initial="{opacity: 0, y: 100}" :enter="{opacity: 1, y: 0, transition: {delay: 200}}">
      <img :src="list[1].image" />
      <div>{{ list[1].text }}</div>
    </div>
    <div class="flex flex-col w-1/5 items-center h-full justify-between py-4" v-motion :initial="{opacity: 0, y: 100}" :enter="{opacity: 1, y: 0, transition: {delay: 400}}">
      <img :src="list[2].image" />
      <div>{{ list[2].text }}</div>
    </div>
  </div>
</template>