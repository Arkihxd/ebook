<template>
  <div class="wrapper">
    <h1>Home Page</h1>
  </div>
</template>

<script>
import Vue from 'vue'
export default Vue.extend({
  layout: 'ebook'
})
</script>

<style lang="scss" scoped>
.wrapper {
  display: grid;
  grid-template-columns: 1fr 1fr 1fr;
  grid-template-rows: 200px;
  grid-auto-flow: column;
  grid-gap: 0.5rem;
  @include screen('large', 'infinity'){
    grid-template-columns: 1fr;
  }
  .box {
    background-color: color('dark', 'darkest');
  }
}
</style>
