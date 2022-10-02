<template>
  <div class="games-container">
    <h2>Meus jogos</h2>
    <p>Os games que eu mais curto jogar!</p>
    <div class="games-thumbs">
      <img src="../assets/game1.png" alt="eita po" />
    </div>
  </div>
</template>

<script></script>

<style>
.games-container {
  padding: 24px 32px;
  widows: 100%;

  border-radius: 8px;
  border-top: 4px solid transparent;
  background: linear-gradient(hsla(257, 16%, 18%, 1) 0 0) padding-box,
    linear-gradient(
        90deg,
        hsla(255, 96%, 72%, 1),
        hsla(159, 77%, 58%, 1),
        hsla(54, 70%, 62%, 1)
      )
      border-box;
}
.games-container h2 {
  color: white;
  font-size: 24px;
  padding: 0;
  margin: 0;
}
.games-container p {
  font-size: 16px;
  color: #a1a1aa;
}
</style>
