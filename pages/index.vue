<template>
  <HomeTemplate />
</template>

<script>
import Vue from 'vue'
import { books } from '@/store'
export default Vue.extend({
  layout: 'ebook',
  async asyncData () {
    await books.index()
  }
})
</script>
