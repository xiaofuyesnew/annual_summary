---
theme: default
class: text-center
drawings:
  persist: false
css: unocss
title: 2022 年终总结
---

# 2022 年终总结

<div class="text-2xl mb-16">挖掘技术的商业价值</div>

<div>
  汇报人：黄河水
</div>

---

# 2022 年参与制作的项目

<div v-motion :initial="{opacity: 0, x: -80}" :enter="{opacity: 1, x: 0}" v-if="$slidev.nav.currentPage === 2">
二姐速拼后台
</div>

<project />

---

# 2022 年参与制作的项目

<div v-motion :initial="{opacity: 0, x: -80}" :enter="{opacity: 1, x: 0}" v-if="$slidev.nav.currentPage === 3">
便利检
</div>

<project />

---

# 2022 年参与制作的项目

<div v-motion :initial="{opacity: 0, x: -80}" :enter="{opacity: 1, x: 0}" v-if="$slidev.nav.currentPage === 4">
星原数艺
</div>

<project />

---

# 2022 年参与制作的项目

<div v-motion :initial="{opacity: 0, x: -80}" :enter="{opacity: 1, x: 0}" v-if="$slidev.nav.currentPage === 5">
同济医院宣传管理系统
</div>

<project />

---

# 2022 年参与制作的项目

<div v-motion :initial="{opacity: 0, x: -80}" :enter="{opacity: 1, x: 0}" v-if="$slidev.nav.currentPage === 6">
C7 游戏盒子 APP
</div>

<project />

---

# 2022 年进行维护的项目

<img-list />

---

# 2022 年进行维护的项目

<div v-motion :initial="{opacity: 0, x: -80}" :enter="{opacity: 1, x: 0}" v-if="$slidev.nav.currentPage === 8">
新媒体互动
</div>

<project />

---

# 2022 年重构的项目

<div v-motion :initial="{opacity: 0, x: -80}" :enter="{opacity: 1, x: 0}" v-if="$slidev.nav.currentPage === 9">
般若考勤
</div>

<project />

---

# 2022 年开源项目

<div v-motion :initial="{opacity: 0, x: -80}" :enter="{opacity: 1, x: 0}" v-if="$slidev.nav.currentPage === 10">
Bore Admin (server)
</div>

<project />

---

# 2022 年开源项目

<div v-motion :initial="{opacity: 0, x: -80}" :enter="{opacity: 1, x: 0}" v-if="$slidev.nav.currentPage === 11">
Bore Template
</div>

<project />

---

# 2022 年开源项目

<div v-motion :initial="{opacity: 0, x: -80}" :enter="{opacity: 1, x: 0}" v-if="$slidev.nav.currentPage === 12">
Bore CLI
</div>

<project />

---

# 挖掘技术的商业价值

<div v-motion :initial="{opacity: 0, x: -80}" :enter="{opacity: 1, x: 0}" v-if="$slidev.nav.currentPage === 13">
2022 年思考了几个问题
</div>

<ol class="w-full flex flex-col items-center p-16" v-if="$slidev.nav.currentPage === 13">
  <li class="w-full text-3xl" v-motion :initial="{opacity: 0, x: -80}" :enter="{opacity: 1, x: 0, transition: {delay: 200}}" >是否只能通过行业项目来实现商业价值（赚钱）？</li>
  <li class="w-full text-3xl" v-motion :initial="{opacity: 0, x: -80}" :enter="{opacity: 1, x: 0, transition: {delay: 400}}">汪总说，“要提升我们企业的科技属性”。这一目标是否仅仅通过完成行业项目就可以达成？</li>
  <li class="w-full text-3xl" v-motion :initial="{opacity: 0, x: -80}" :enter="{opacity: 1, x: 0, transition: {delay: 600}}">是否可以通过技术创新，在技术领域进入头部环境来达成上述这一点？</li>
</ol>

---

# 挖掘技术的商业价值

<div v-motion :initial="{opacity: 0, x: -80}" :enter="{opacity: 1, x: 0}" v-if="$slidev.nav.currentPage === 14">
现实情况
</div>

<script setup>
  import comic from '/images/comic.jpg'
</script>

<div class="w-full flex flex-col items-center pt-6" v-if="$slidev.nav.currentPage === 14">
  <img :src="comic" alt="comic" v-motion :initial="{opacity: 0, scale: 0}" :enter="{opacity: 1, scale: 1, transition: {delay: 200}}"/>
  <div class="mt-6">*每个人对问题的看法和解答会根据位置和角度不同而不同，在此仅分享自己的思考结果，会后欢迎交流</div>
</div>

---

# 团队的 SWOT 分析

<swot />

---

# 团队的 SWOT 分析

<div v-motion :initial="{opacity: 0, x: -80}" :enter="{opacity: 1, x: 0}" v-if="$slidev.nav.currentPage === 16">
团队的优势(Strengths)
</div>

<ul class="w-full flex flex-col items-center p-16" v-if="$slidev.nav.currentPage === 16">
  <li class="w-full text-3xl" v-motion :initial="{opacity: 0, x: -80}" :enter="{opacity: 1, x: 0, transition: {delay: 200}}">皮实耐操——人员十分努力刻苦</li>
  <li class="w-full text-3xl" v-motion :initial="{opacity: 0, x: -80}" :enter="{opacity: 1, x: 0, transition: {delay: 400}}">八面玲珑——涉及技术栈领域广泛，什么类型的都能搞一点</li>
  <li class="w-full text-3xl" v-motion :initial="{opacity: 0, x: -80}" :enter="{opacity: 1, x: 0, transition: {delay: 600}}">瓜剖棋布——建制完整，产品、设计、前端、后端均有对应人员</li>
</ul>

---

# 团队的 SWOT 分析

<div v-motion :initial="{opacity: 0, x: -80}" :enter="{opacity: 1, x: 0}" v-if="$slidev.nav.currentPage === 17">
团队的劣势(Weaknesses)
</div>

<ul class="w-full flex flex-col items-center p-16" v-if="$slidev.nav.currentPage === 17">
  <li class="w-full text-3xl" v-motion :initial="{opacity: 0, x: -80}" :enter="{opacity: 1, x: 0, transition: {delay: 200}}">过渡依赖人力去处理技术问题</li>
  <li class="w-full text-3xl" v-motion :initial="{opacity: 0, x: -80}" :enter="{opacity: 1, x: 0, transition: {delay: 400}}">技术方向不确定，很多方面只能“浅尝辄止”，不能专项深入</li>
  <li class="w-full text-3xl" v-motion :initial="{opacity: 0, x: -80}" :enter="{opacity: 1, x: 0, transition: {delay: 600}}">未能有效建立标准化工作流程</li>
</ul>

---

# 团队的 SWOT 分析

<div v-motion :initial="{opacity: 0, x: -80}" :enter="{opacity: 1, x: 0}" v-if="$slidev.nav.currentPage === 18">
团队的机遇(Opportunities)
</div>

<ul class="w-full flex flex-col items-center p-16" v-if="$slidev.nav.currentPage === 18">
  <li class="w-full text-3xl" v-motion :initial="{opacity: 0, x: -80}" :enter="{opacity: 1, x: 0, transition: {delay: 200}}">市场环境回暖，行业有曙光</li>
  <li class="w-full text-3xl" v-motion :initial="{opacity: 0, x: -80}" :enter="{opacity: 1, x: 0, transition: {delay: 400}}">忙时业务为主，闲时开源为主，半忙半闲时总结问题为主</li>
  <li class="w-full text-3xl" v-motion :initial="{opacity: 0, x: -80}" :enter="{opacity: 1, x: 0, transition: {delay: 600}}">依托技术提升的过程开辟一条以技术为主的商业模式</li>
</ul>

---

# 团队的 SWOT 分析

<div v-motion :initial="{opacity: 0, x: -80}" :enter="{opacity: 1, x: 0}" v-if="$slidev.nav.currentPage === 19">
团队的威胁(Threats)
</div>

<ul class="w-full flex flex-col items-center p-16" v-if="$slidev.nav.currentPage === 19">
  <li class="w-full text-3xl" v-motion :initial="{opacity: 0, x: -80}" :enter="{opacity: 1, x: 0, transition: {delay: 200}}">如果行业回暖不理想，需要做好准备</li>
  <li class="w-full text-3xl" v-motion :initial="{opacity: 0, x: -80}" :enter="{opacity: 1, x: 0, transition: {delay: 400}}">技术栈更新太快，走技术路线也容易落伍</li>
  <li class="w-full text-3xl" v-motion :initial="{opacity: 0, x: -80}" :enter="{opacity: 1, x: 0, transition: {delay: 600}}">业务与技术的挤兑</li>
</ul>

---

# 做开源带来的好处

<ul class="w-full flex flex-col items-center p-8" v-if="$slidev.nav.currentPage === 20">
  <li class="w-full text-3xl" v-motion :initial="{opacity: 0, x: -80}" :enter="{opacity: 1, x: 0, transition: {delay: 200}}">依托自有开源项目，形成技术社区，储备精准人才</li>
  <li class="w-full text-3xl" v-motion :initial="{opacity: 0, x: -80}" :enter="{opacity: 1, x: 0, transition: {delay: 400}}">可开放捐赠渠道，作为开源项目开发参与者的回馈和技术活动经费</li>
  <li class="w-full text-3xl" v-motion :initial="{opacity: 0, x: -80}" :enter="{opacity: 1, x: 0, transition: {delay: 600}}">直接对接公司自有业务，有技术改进可以迅速进行（对比使用其他开源库）</li>
  <li class="w-full text-3xl" v-motion :initial="{opacity: 0, x: -80}" :enter="{opacity: 1, x: 0, transition: {delay: 800}}">通过开源项目为公司影响力做宣传（提升公司的科技属性）</li>
</ul>

---

# 2023 我的计划

<ul class="w-full flex flex-col items-center p-16" v-if="$slidev.nav.currentPage === 21">
  <li class="w-full text-4xl" v-motion :initial="{opacity: 0, x: -80}" :enter="{opacity: 1, x: 0, transition: {delay: 200}}">将手头的开源项目完成，并逐步投入公司业务应用</li>
  <li class="w-full text-4xl" v-motion :initial="{opacity: 0, x: -80}" :enter="{opacity: 1, x: 0, transition: {delay: 400}}">组建一个开源社区，维护一批技术从业人员</li>
  <li class="w-full text-4xl" v-motion :initial="{opacity: 0, x: -80}" :enter="{opacity: 1, x: 0, transition: {delay: 600}}">新媒体互动改版变现</li>
</ul>

<div class="text-2xl flex justify-center">*如对以上任意一项感兴趣，欢迎随时与我进行交流</div>
