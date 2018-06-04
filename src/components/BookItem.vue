<template>
  <li v-for="book in books">{{book.title}}: {{book.author}}</li>
</template>


<script>
export default {
  name: BookList,
  props: ['book']
}
</script>

<style>
</style>
