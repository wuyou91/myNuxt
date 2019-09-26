<template>
  <div class="container">
    首页
  </div>
</template>

<script>
export default {
  name: 'index',
  asyncData(context) {
    return {
      env: context.isDev
    }
  },
  created() {
    console.log(this.env)
  }
}
</script>

<style lang="scss" scoped>
.container {
  background: red;
}
</style>
