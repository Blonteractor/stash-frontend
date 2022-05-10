<script>
import Sidebar from "./Sidebar.vue";
import Card from "./Card.vue";

export default {
  components: {
    Card,
  },
};
</script>

<template>
  <div id="bg">
    <!-- <Sidebar /> -->
    <Card />
  </div>
</template>

<style scoped>
#bg {
  position: absolute;
  height: 100%;
  left: 300px;
  width: ;
  top: 0px;
  background-color: #113536;
}
</style>
