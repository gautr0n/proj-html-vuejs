<template>
    <div>
        <MainFirstSection />
        <MainService />
        <Courses />
    </div>
</template>

<script>
  import MainFirstSection from '../components/MainFirstSection.vue'
  import MainService from '../components/MainService.vue'
  import Courses from '../components/Courses.vue'
  import store from '../store'

export default{
  components: {
      MainFirstSection,
      MainService,
      Courses,
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