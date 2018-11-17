<template lang="html">

  <div class="sample">
    
    <div>
      <slot/>
    </div>
    <div class="blue">
      <slot name="named"/>
    </div>
  </div>

</template>
​
<script>
export default {
  layout: 'dark',
  props: {
    title: {
      type: String,
      default: 'Defalut Title'
    }
  },
  data() {
    return {
      name: 'takip',
      num: 0
    }
  },
  methods: {
    plus() {
      this.num++
    },
    mounted() {
      console.log('mounted')
    }
  }
}
</script>
​
<style lang="scss" scoped>
</style>
