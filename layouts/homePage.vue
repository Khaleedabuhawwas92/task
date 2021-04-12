<template>
  <Nuxt />
</template>
<style scoped>
body {
  background: rgb(0, 0, 0);
}
/* small */
@media (min-width: 640px) {
  body {
    background: red;
  }
}
/* mudim */
@media (min-width: 768px) {
  body {
    background: green;
  }
}
/* larg */
@media (min-width: 1024px) {
  body {
    background: greenyellow;
  }
}
</style>
