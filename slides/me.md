---
preload: false
---

<h1 class="!text-pink-500">Hi! 👋</h1>

<h3>Konstantin BIFERT ~ <span
    class="text-transparent bg-clip-text bg-gradient-to-br from-orange-500 to-pink-500">kissu</span></h3>

<div class="flex mt-6">
  <img v-motion :initial="{ x: -200, y: 0, scale: 1, rotate: 0 }" :enter="final"
    class="top-0 left-0 right-0 bottom-0 h-48 w-48 rounded" src="/images/kissu.jpg"
    alt="photo of konstantin" />
  <section class="ml-4">
    <p class="!m-0">
      <logos-vue/> Frontend Consultant <a href="https://twitter.com/passionpeopleNL">@passionpeopleNL</a>
    </p>
    <p class="my-2">
      <logos-nuxt-icon class="inline h-6" />
      <a href="https://nuxtjs.org/teams" class="ml-2">Nuxt.js Ambassador</a>
    </p>
    <p class="my-2">
      <logos-stackoverflow-icon class="inline mr-2" />
      <a href="https://stackoverflow.com/users/8816585/kissu">Daily helper on Stackoverflow</a>
      <p>🎤  Speaking in public places</p>
      <p>✨ I'm into gaming, I love mech keyboards, tech and DIY nerdy stuff</p>
    </p>
  </section>
</div>

<script setup lang="ts">
  const final = {
    x: 0,
    y: 0,
    scale: 1,
    transition: {
      type: 'spring',
      damping: 10,
      stiffness: 20,
      mass: 2
    }
  }
  const melon = {
    x: 50,
    y: -50,
    rotate: 0,
    scale: 1,
    transition: {
      type: 'spring',
      damping: 10,
      stiffness: 20,
      mass: 2
    }
  }
</script>
