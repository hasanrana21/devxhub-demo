<template>
  <div class="wrapper">
    <div class="grid grid-cols-12 gap-4">
      <div
        v-for="(blog, index) in allBlogs"
        :key="index"
        class="
          col-span-4
          border-2
          px-6
          py-4
          hover:shadow-lg hover:border-none
          cursor-pointer
        "
      >
        <n-link to="/blogs/blogsDetails">
          <div class="flex justify-between items-center space-x-6">
            <h3 class="text-lg font-bold">User: {{ blog.userId }}</h3>
            <h3 class="text-lg font-bold">
              {{ blog.title }}
            </h3>
          </div>
          <p class="text-md">{{ blog.body }}</p>
        </n-link>
      </div>
    </div>
  </div>
</template>

<script>
import axios from 'axios'
export default {
  name: 'blogs',
  data() {
    return {
      allBlogs: [],
    }
  },

  mounted() {
    this.getBlog()
  },
  methods: {
    getBlog() {
      axios
        .get('https://jsonplaceholder.typicode.com/posts')
        .then((res) => {
          // console.log(res.data)
          this.allBlogs = res.data
        })
        .catch((err) => {
          console.log(err)
        })
    },
  },
}
</script>

<style scoped>
/* .wrapper {
  @apply py-20;
} */
</style>
