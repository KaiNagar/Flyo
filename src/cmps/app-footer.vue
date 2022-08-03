<template>
  <section class="app-footer flex">
    <div class="bg"></div>
    <div class="container flex">
      <div class="footer-info">
        <div class="info-body flex">
          <img class="img" src="../imgs/icon-location.svg" alt="" />
          <p class="footer-txt">
            <img class="logo" src="../imgs/logo.svg" alt="" />
            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
            eiusmod tempor incididunt ut labore et dolore magna aliqua
          </p>
        </div>
      </div>
      <div class="contact-info">
        <div class="phone-number flex">
          <img src="../imgs/phone.png" alt="" />
          <span class="txt">+1-543-123-4567</span>
        </div>
        <div class="email flex align-center">
          <span class="img"><img src="../imgs/mail.png" alt="" /></span>
          <span class="txt"> example@fylo.com</span>
        </div>
      </div>
      <div class="nav-btns">
        <span>About Us</span>
        <span>Jobs</span>
        <span>Press</span>
        <span>Blog</span>
      </div>
      <div class="nav-btns seconds">
        <span>Contact Us</span>
        <span>Terms</span>
        <span>Privecy</span>
      </div>
      <div class="social-btns">
        <img src="https://cdn-icons-png.flaticon.com/512/20/20837.png" alt="" />
        <img
          src="https://cdn-icons.flaticon.com/png/512/4945/premium/4945968.png?token=exp=1659527152~hmac=0c733fb05ae2b77e920b71f87ea4b25e"
          alt=""
        />
        <img
          src="https://cdn-icons.flaticon.com/png/512/3128/premium/3128219.png?token=exp=1659527332~hmac=3bfb3fa0ea284e8b2ab85cae5851f094"
          alt=""
        />
      </div>
    </div>
    <subscribtion />
  </section>
</template>

<script>
import subscribtion from '@/cmps/subscribtion.vue'

export default {
  components: { subscribtion },
  data() {
    return {}
  },
  methods: {},
  computed: {},
  created() {},
}
</script>

<style></style>
