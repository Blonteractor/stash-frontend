<script setup lang="ts">
// This starter template is using Vue 3 <script setup> SFCs
// Check out https://vuejs.org/api/sfc-script-setup.html#script-setup
import HelloWorld from "./components/HelloWorld.vue";
import Homepage from "./components/Homepage.vue";
import Sidebar from "./components/Sidebar.vue";
import Cards from "./components/Cards.vue";
</script>

<template>
  <div className="flex-container">
    <div className="sidebar-container">
      <Sidebar />
    </div>
    <div className="cards-container">
      <Cards />
    </div>
  </div>
</template>

<style scoped>
.flex-container {
  display: flex;
  background-color: #113536;
  gap: 43px;
  height: 100%;
  width: 100%;
}
.sidebar-container {
  flex: 1;
  background-color: #112123;
}
.cards-container {
  flex: 4;
}
</style>

<style>
body, html, #app {
  margin: 0;
}
</style>
