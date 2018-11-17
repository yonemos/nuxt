<template lang="html">
  <nuxt-link to="/">TOP</nuxt-link>
</template>
<script>
export default {
  layout: 'dark',
  head() {
    return {
      // タイトルテンプレートがある場合は "ABOUT - ポートフォリオ" になる
      title: 'ABOUT',
      meta: [
        { hid: 'description', name: 'description', content: 'About ページ' }
      ]
    }
  }
}
</script>
​
<style lang="scss">
</style>
