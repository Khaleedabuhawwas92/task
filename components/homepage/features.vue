<template>
  <div class="features">
    <div class="overlay">
      <img
        src="~/assets/image/registration-image/logo-footer-ar.png"
        alt=""
        width="110px"
        height="94px"
        class="logo"
      />
      <navbar />
      <paragraph />
    </div>
  </div>
</template>
<script>
import navbar from "~/components/homepage/navbar.vue";
import paragraph from "~/components/homepage/paragraph.vue";
export default {
  components: {
    navbar,
    paragraph,
  },
};
</script>
<style>
.overlay {
  overflow: hidden;
  position: absolute;
  left: 0;
  top: 0;
  width: 100%;
  height: 100%;
  color: white;
  background-color: rgba(10, 9, 9, 0.3);
  overflow: hidden;
}
.features {
  background: url("~/assets/image/home-page/background.jpg") no-repeat center
    center;
  background-size: cover;
  min-height: 860px;
  position: relative;
  width: 100%;
}
.logo {
  position: relative;
  top: 50px;
  left: 1741px;
}

.bluer {
  backdrop-filter: blur(20px);
}
</style>
