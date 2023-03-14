<template>
  <Header />
</template>

<script>
  import Header from './components/Header.vue'
  import store from './store'

export default{
  components: {
      Header,
    },
    data() {
      return {
        store
      }
    },
}
</script>

<style lang="scss" scoped>

</style>
