<template>
  <section class="header">
    <div class="py-3 px-20 flex justify-between items-center">
      <div>
        <button class="text-4xl font-bold text-white">
          <img
            src="https://devxhub.com/storage/uploads/logos/1619427889-350x89-1617479508-x-devxhub-next-logo.png"
            alt=""
            class="w-56"
          />
        </button>
      </div>
      <div class="menu">
        <n-link to="/">Home</n-link>
        <n-link to="/company">Company</n-link>
        <n-link to="/services">Services</n-link>
        <n-link to="/blogs/blogs">Blogs</n-link>
        <n-link to="/products">Products</n-link>
        <n-link to="/work">How We Work</n-link>
        <n-link to="/contact">Contact</n-link>
      </div>
    </div>
  </section>
</template>

<script>
export default {}
</script>

<style scoped>
.menu a {
  @apply text-white text-xl font-semibold py-1 px-2 mx-3;
}
.header {
  background-color: #37b1d1;
}
</style>
