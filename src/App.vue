<template>
  <Header />
  <Main />
  <Footer />
</template>

<script>
  import Header from './components/Header.vue'
  import Main from './components/Main.vue'
  import Footer from './components/Footer.vue'
  import store from './store'

export default{
  components: {
      Header,
      Main,
      Footer
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
