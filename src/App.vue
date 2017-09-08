<template>
  <div id="app">
      <div class="preloader">
          <div class="status">
              <div class="status-mes"></div>
          </div>
      </div>
      <router-view></router-view>
  </div>
</template>

<script>
export default {
  name: 'app'
}
</script>

<style>
    #app {
        height:100%
    }
</style>
