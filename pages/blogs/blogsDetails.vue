<template>
  <div>
    <h1>this is blogs details page</h1>
  </div>
</template>

<script>
import axios from 'axios'
export default {
  data() {
    return {
      postComments: [],
    }
  },
  mounted() {
    this.allComments()
  },
  methods: {
    allComments() {
      axios
        .get('https://jsonplaceholder.typicode.com/comments')
        .then((res) => {
          console.log(res.data)
        })
        .catch((err) => {
          console.log(err)
        })
    },
  },
}
</script>

<style scoped></style>
