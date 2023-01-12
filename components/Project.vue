<script setup>
import p_1 from '../images/p_1.png'
import p_2 from '../images/p_2.png'
import p_3 from '../images/p_3.png'
import p_4 from '../images/p_4.png'
import p_5 from '../images/p_5.png'
import p_6 from '../images/p_6.png'
import r from '../images/r.png'
import o_1 from '../images/o_1.png'
import o_2 from '../images/o_2.png'
import o_3 from '../images/o_3.png'

const projects = [
  {
    currentPage: 2,
    layout: 'image-left',
    image: p_1,
    features: [
      '第一次做物流类的后台管理',
      '完整地使用后台现代框架进行后台搭建',
      '硬件方面与打印机进行交互，打印出物流面单'
    ]
  },
  {
    currentPage: 3,
    layout: 'image-right',
    image: p_2,
    features: [
      '一个完整使用小程序技术能力的项目',
      '遇到了用户增长迅速的高并发瓶颈',
      '得到了领导及社区的重视'
    ]
  },
  {
    currentPage: 4,
    layout: 'image-left',
    image: p_3,
    features: [
      '第一次尝试新兴行业 NFT 领域的项目',
      '比较系统的实现了 3D 模型展示及交互',
      '前端技术栈使用最新的框架'
    ]
  },
  {
    currentPage: 5,
    layout: 'image-right',
    image: p_4,
    features: [
      '开发稿件部分，虽然属于常规的后台项目，但交互需求有些复杂',
      '使用了新的前端后台框架，但有些过于新',
      '用 ts 是被迫的🤯'
    ]
  },
  {
    currentPage: 6,
    layout: 'image-left',
    image: p_5,
    features: [
      '完整的游戏商城项目',
      '后端不是我们，前端搭接半成品，克服困难，有问题解决问题',
      'APP 打包的方式我们其实已经有更好的解决方案😏（监狱 APP 原型项目已实践）'
    ]
  },
  {
    currentPage: 8,
    layout: 'image-left',
    image: p_6,
    features: [
      '存量用户最高的小程序',
      '政策面收紧，不得已而为之',
      '建议年后抓紧时间改版，争取早日变现'
    ]
  },
  {
    currentPage: 9,
    layout: 'image-right',
    image: r,
    features: [
      '换用了最新的技术栈，尝试了做自动化代码检查',
      '重写了前期陆续添加的不合理耦合逻辑，拆分组件更合理，更易维护',
      '目前在做最后微调和收尾工作，2023年后上新'
    ]
  },
  {
    currentPage: 10,
    layout: 'image-left',
    image: o_1,
    features: [
      '换用了最新的技术栈，尝试了做自动化代码检查',
      '重写了前期陆续添加的不合理耦合逻辑，拆分组件更合理，更易维护',
      '目前在做最后微调和收尾工作，2023年后上新'
    ]
  },
  {
    currentPage: 11,
    layout: 'image-right',
    image: o_2,
    features: [
      '换用了最新的技术栈，尝试了做自动化代码检查',
      '重写了前期陆续添加的不合理耦合逻辑，拆分组件更合理，更易维护',
      '目前在做最后微调和收尾工作，2023年后上新'
    ]
  },
  {
    currentPage: 12,
    layout: 'image-left',
    image: o_3,
    features: [
      '换用了最新的技术栈，尝试了做自动化代码检查',
      '重写了前期陆续添加的不合理耦合逻辑，拆分组件更合理，更易维护',
      '目前在做最后微调和收尾工作，2023年后上新'
    ]
  }
]

</script>

<template>
  <template v-for="(item, index) in projects" :key="index">
    <div class="w-full h-10/12 flex items-center justify-between" v-if="$slidev.nav.currentPage === item.currentPage">
      <template v-if="item.layout === 'image-left'">
        <div class="w-1/2 h-full flex items-center justify-center p-4">
          <img class="max-w-full max-h-full" :src="item.image" v-motion :initial="{ x: -80, opacity: 0 }"
          :enter="{ x: 0, opacity: 1, transition: { delay: 200 } }" />
        </div>
        <ul class="w-1/2 h-full p-6 flex flex-col justify-center">
          <li v-for="(feat, idx) in item.features" v-motion :initial="{ x: 80, opacity: 0 }"
            :enter="{ x: 0, opacity: 1, transition: { delay: 200 * (idx + 1) } }">{{ feat }}</li>
        </ul>
      </template>
      <template v-if="item.layout === 'image-right'">
        <ul>
          <li v-for="(feat, idx) in item.features" v-motion :initial="{ x: -80, opacity: 0 }"
            :enter="{ x: 0, opacity: 1, transition: { delay: 200 * (idx + 1) } }">{{ feat }}</li>
        </ul>
        <div class="w-1/2 h-full flex items-center justify-center p-4">
          <img class="max-w-full max-h-full" :src="item.image" v-motion :initial="{ x: 80, opacity: 0 }"
          :enter="{ x: 0, opacity: 1, transition: { delay: 200 } }" />
        </div>
      </template>
    </div>
  </template>

</template>