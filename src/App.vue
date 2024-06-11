<template>
  <div id="app">
    <router-view></router-view>
  </div>

</template>

<script>
export default {
  components: {
    
  },
};
</script>

<style lang="scss" scoped>
#app {
  margin: 0 auto;
  max-width: 1280px;
  height: 100vh;
  max-height: 4000px;
  background: #111111;

  display: flex;
  flex-direction: column;
}

.playerContainer {
  width: 100%;
  height: calc(100% - 62px);
  position: relative;
}
</style>
