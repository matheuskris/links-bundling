<template>
  <div class="wrapper">
    <div class="image-container">
      <img src="../assets/perfil.jpeg" alt="" />
    </div>
    <GamesSection />
    <ChannelSection />
    <ConnectionSection />
  </div>
</template>

<script>
import GamesSection from "./GamesSection.vue";
import ChannelSection from "./ChannelSection.vue";
import ConnectionSection from "./ConnectionSection.vue";

export default {
  name: "MainPage",
  props: {},
  components: {
    GamesSection,
    ChannelSection,
    ConnectionSection,
  },
};
</script>

<style scoped>
.wrapper {
  width: 80%;
  max-width: 580px;
  height: 854px;
  margin-top: 32px;
  margin-inline: auto;

  display: flex;
  flex-direction: column;
  align-items: center;
  padding: 0px;
  gap: 32px;
}
.image-container {
  width: 120px;
  height: 120px;
}
.image-container img {
  width: 120px;
  height: 120px;
  border-radius: 49%;
  border: 4px solid transparent;
  background: linear-gradient(
      90deg,
      hsla(255, 96%, 72%, 1),
      hsla(159, 77%, 58%, 1),
      hsla(54, 70%, 62%, 1)
    )
    border-box;
}
</style>
