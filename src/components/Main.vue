<template>
    <div>
        <MainFirstSection />
        <MainService />
        <Courses />
        <ReadMore />
        <RecentCourses />
        <Proud />
        <PopularCourses />
        <Instructor />
        <Testimonial />
    </div>
</template>

<script>
  import MainFirstSection from '../components/MainFirstSection.vue'
  import MainService from '../components/MainService.vue'
  import Courses from '../components/Courses.vue'
  import ReadMore from '../components/ReadMore.vue'
  import RecentCourses from '../components/RecentCourses.vue'
  import Proud from '../components/Proud.vue'
  import PopularCourses from '../components/PopularCourses.vue'
  import Instructor from '../components/Instructor.vue'
  import Testimonial from '../components/Testimonial.vue'
  import store from '../store'

export default{
  components: {
      MainFirstSection,
      MainService,
      Courses,
      ReadMore,
      RecentCourses,
      Proud,
      PopularCourses,
      Instructor,
      Testimonial,
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