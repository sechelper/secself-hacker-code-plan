<script setup>
import 'bootstrap/dist/css/bootstrap.css'
import 'bootstrap-vue/dist/bootstrap-vue.css'

import Index from './components/index.vue'
import Welcome from './components/welcome.vue'
</script>

<template>
  <header>
    <div class="wrapper">
      <Index msg="助安社区" />

    </div>

  </header>

  <main>
    <Welcome />
  </main>

</template>

<style scoped>

header {
  line-height: 1.5;
}


@media (min-width: 1024px) {
  header {
    display: flex;
    place-items: center;
    padding-right: calc(var(--section-gap) / 2);
  }

  header .wrapper {
    display: flex;
    place-items: flex-start;
    flex-wrap: wrap;
  }
}
</style>
