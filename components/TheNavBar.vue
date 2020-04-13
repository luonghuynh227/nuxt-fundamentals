<template>
  <nav class="nav">
    <div class="logo">
      <!-- <a href="#" class="logo text-lg">
        Nuxt Fundamentals
      </a> -->
      <nuxt-link class="logo text-lg" :to="{name: 'index'}">
        Nuxt Fundamentals
      </nuxt-link>
      <div class="subheader">
        A Vue School course
      </div>
    </div>
  </nav>
</template>