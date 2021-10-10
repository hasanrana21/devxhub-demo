<template>
  <section>
    <Header></Header>
    <main>
      <Nuxt />
    </main>
  </section>
</template>


<script>
import Header from "../components/Header.vue"
export default {
  components: {Header}
}
</script>


<style scoped>
html{
  padding: 0;
  margin: 0;
  box-sizing: border-box;
}
</style>
