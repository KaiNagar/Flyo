<template>
  <section class="home-page main-layout">
    <img class="curvy" src="../imgs/bg-curvy-desktop.svg" alt="">
    <div class="img flex justify-center">
      <img src="../imgs/illustration-intro.png" alt="" />
    </div>
    <getting-started />
    <verifications />
    <stay-productive />
    
    <reviews />
    
  </section>
</template>

<script>
import gettingStarted from '@/cmps/getting-started.vue'
import verifications from '@/cmps/verifications.vue'
import stayProductive from '@/cmps/stay-productive.vue'
import reviews from '@/cmps/reviews.vue'
export default {
  components: {
    gettingStarted,
    verifications,
    stayProductive,
    reviews,
  },
  data() {
    return {}
  },
  methods: {},
  computed: {},
  created() {},
}
</script>
