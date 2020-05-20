<template>
  <div>
      <div>公司的罗列,好多好多公司</div>
      <i-button type="info" @click="add">信息按钮</i-button>
  </div>

</template>

<script>
export default {
  data () {
    return {

    }
  },
  methods: {
    add () {
      console.log(222222)

      this.$router.push('apt')
    }
  }
}
</script>

<style>

</style>
