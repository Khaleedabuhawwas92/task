<template>
  <div class="cont">
    <background2 />
    <form2 />
  </div>
</template>

<script>
import background2 from "~/components/loginScreen/imageLoginScreen.vue";
import form2 from "~/components/loginScreen/formLoginScreen.vue";
export default {
  layout: "registration",
  components: {
    background2,
    form2,
  },
};
</script>
<style>
body {
}
.cont {
  display: flex;
  flex-direction: row;

  overflow: hidden;
}
</style>
