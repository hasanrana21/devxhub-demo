<template>
  <section>
    <Header></Header>
    <main>
      <Nuxt />
    </main>
  </section>
</template>

<script>
import Header from '../components/Header.vue'
export default {
  components: { Header },
}
</script>

<style>
html {
  padding: 0;
  margin: 0;
  box-sizing: border-box;
}
.wrapper {
  max-width: 1200px;
  @apply mx-auto py-20;
}
</style>
