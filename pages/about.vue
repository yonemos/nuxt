<template lang="html">
  <div lass="dark">
    <nuxt-link to="/">TOP</nuxt-link>
    <p>ここはアバウトのページです</p>
    <logo/>
  </div>
</template>

<script>
import Logo from '~/components/Logo.vue'

export default {
  components: {
    Logo
  },
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
