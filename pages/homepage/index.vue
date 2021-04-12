<template>
  <div class="flex flex-col con">
    <header1 />
    <features />
    <brands />
    <infromation />
    <sections />
    <arrived />
    <course />
    <footer1 />
  </div>
</template>
<script>
import header1 from "~/components/homepage/header.vue";
import features from "~/components/homepage/features.vue";
import brands from "~/components/homepage/brands.vue";
import infromation from "~/components/homepage/infromation.vue";
import sections from "~/components/homepage/sections.vue";
import arrived from "~/components/homepage/arrived.vue";
import course from "~/components/homepage/course.vue";
import footer1 from "~/components/homepage/footer.vue";
export default {
  layout: "homePage",
  components: {
    header1,
    features,
    brands,
    infromation,
    sections,
    arrived,
    course,
    footer1,
  },
};
</script>
<style scoped>
.con {
}
.form {
  margin: auto;
}
</style>
