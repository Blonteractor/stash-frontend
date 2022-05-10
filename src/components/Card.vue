<script setup lang="ts"></script>

<template>
  <div className="flex-container">
    <div className="item">
      <div id="img"></div>
    </div>
    <div className="item">
      <div id="img"></div>
    </div>
    <div className="item">
      <div id="img"></div>
    </div>
    <div className="item">
      <div id="img"></div>
    </div>
    <div className="item">
      <div id="img"></div>
    </div>
    <div className="item">
      <div id="img"></div>
    </div>
    <div className="item">
      <div id="img"></div>
    </div>
  </div>
</template>

<style scoped>
.item {
  order: 5;
  width: 401px;
  height: 384px;
  background: #112123;
  border-radius: 20px;
}

.flex-container {
  display: flex;
  justify-content: flex-start;
  gap: 10px 30px;
}

#img {
  /* position: absolute; */
  height: 220px;
  left: 1.15%;
  right: -1.38%;
  top: -1px;

  background: url(https://media.discordapp.net/attachments/747692657131651175/973511976665899028/20220510_043136.jpg);
  filter: blur(1px);
  border-radius: 20px;
  overflow: hidden;
}
</style>
