<template>
  <div>
    <BookDetailsTemplate />
  </div>
</template>

<script lang="ts">
import Vue from 'vue'
import { books } from '@/store'

export default Vue.extend({
  layout: 'ebook',
  async asyncData ({ params }) {
    await books.show({ id: params.id as any })
    console.log(books.$single)
  }
})
</script>

<style scoped>

</style>
