<template>
  <MainPage />
</template>

<script>
import MainPage from "./components/MainPage.vue";

export default {
  name: "App",
  components: {
    MainPage,
  },
};
</script>

<style>
@import url("https://fonts.googleapis.com/css2?family=Inter&display=swap");
* {
  border: 0;
  padding: 0;
  box-sizing: border-box;
}
body {
  font-family: "Inter", sans-serif;
  background-image: url("./assets/banner-bg.png");
  width: 100%;
}
</style>
