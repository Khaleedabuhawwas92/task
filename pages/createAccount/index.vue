<template>
  <div class="cont">
    <background1 />
    <div class="form">
      <form1 />
    </div>
  </div>
</template>
<script>
import background1 from "~/components/registration/image-background.vue";
import form1 from "~/components/registration/form.vue";
export default {
  layout: "registration",
  components: {
    background1,
    form1,
  },
};
</script>
<style>
.cont {
  display: flex;
  flex-direction: row;
  overflow: hidden;
}
.form {
  margin: auto;
}
</style>
