<script setup lang="ts"></script>

<template>
  <div className="flex-container">
    <div className="item">
      <div id="img"></div>
      <img id='icon' src='https://cdn.discordapp.com/emojis/921067306363289640.webp?size=128&quality=lossless' />
    </div>
    <div className="item">
      <div id="img"></div>
      <img id='icon' src='https://cdn.discordapp.com/emojis/921067306363289640.webp?size=128&quality=lossless' />
    </div>
    <div className="item">
      <div id="img"></div>
      <img id='icon' src='https://cdn.discordapp.com/emojis/921067306363289640.webp?size=128&quality=lossless' />
    </div>
    <div className="item">
      <div id="img"></div>
      <img id='icon' src='https://cdn.discordapp.com/emojis/921067306363289640.webp?size=128&quality=lossless' />
    </div>
    <div className="item">
      <div id="img"></div>
      <img id='icon' src='https://cdn.discordapp.com/emojis/921067306363289640.webp?size=128&quality=lossless' />
    </div>
    <div className="item">
      <div id="img"></div>
      <img id='icon' src='https://cdn.discordapp.com/emojis/921067306363289640.webp?size=128&quality=lossless' />
    </div>
    <div className="item">
      <div id="img"></div>
      <img id='icon' src='https://cdn.discordapp.com/emojis/921067306363289640.webp?size=128&quality=lossless' />
    </div>
    <div className="item">
      <div id="img"></div>
      <img id='icon' src='https://cdn.discordapp.com/emojis/921067306363289640.webp?size=128&quality=lossless' />
    </div>
    <div className="item">
      <div id="img"></div>
      <img id='icon' src='https://cdn.discordapp.com/emojis/921067306363289640.webp?size=128&quality=lossless' />
    </div>
    <div className="item">
      <div id="img"></div>
      <img id='icon' src='https://cdn.discordapp.com/emojis/921067306363289640.webp?size=128&quality=lossless' />
    </div>
    <div className="item">
      <div id="img"></div>
      <img id='icon' src='https://cdn.discordapp.com/emojis/921067306363289640.webp?size=128&quality=lossless' />
    </div>
  </div>
</template>

<style scoped>
/* Flex box for all the cards */

#icon {
  position: relative;
  width: 65px;
  height: 65px;
  left: 21px;
  bottom: 30px;
  border-radius: 20px;
  object-fit: contain;
  background-color: #112123;
}
.flex-container {
  display: flex;
  flex-wrap: wrap;
  justify-content: flex-start;
  gap: 20px 30px;
}
.item {
  width: 350px;
  height: 350px;
  background: #112123;
  border-radius: 20px;
}
/* Card css */
/* Image on the card */
#img {
  /* position: absolute; */
  height: 220px;
  left: 1.15%;
  right: -1.38%;
  top: -1px;

  background: url(https://media.discordapp.net/attachments/747692657131651175/973511976665899028/20220510_043136.jpg);
  /* filter: blur(1px);  */
  border-radius: 20px;
  /* overflow: hidden; */
}
</style>
