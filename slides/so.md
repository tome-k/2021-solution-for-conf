<h1>Journey on SO</h1>
<div v-motion :initial="{ x: 1000, y: 0, scale: 1, rotate: 0 }" :enter="melon">🍉</div>

<div class="flex flex-col">
<p>Got a new job (October 2020) where I could choose the DREAM modern stack from scratch</p>
<v-clicks>
<span v-show="$slidev.nav.clicks < 2">Wordpress + jQuery + RaspberryPi for hosting + FTP for deployment 🤩</span>
<span><span class="text-transparent bg-clip-text bg-gradient-to-t from-green-500 to-green-500 text-2xl">Nuxt.js !!</span> 🏔️⛰️🧗‍♂️</span>
</v-clicks>
</div>

<div class="mt-8">

<p v-click>Why SO particularly:</p>
<ul>
  <li v-click>alone on the frontend team, needed some documentation/bookmarks/examples</li>
  <li v-click>was already used to help but in private places <img class="h-24" src="images/slack_help.png"/><img class="h-24" src="images/slack_js.png"/></li>
</ul>
</div>

<script setup lang="ts">
  const melon = {
    x: 700,
    y: -50,
    rotate: 0,
    scale: 2,
    transition: {
      type: 'spring',
      damping: 10,
      stiffness: 20,
      mass: 2
    }
  }
</script>

<!--
- Shawn Want: https://www.swyx.io/learn-in-public/
-->
