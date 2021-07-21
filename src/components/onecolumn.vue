<template>
  <div id="app">
    <div>常见布局</div>
    <div class="header"></div>
    <div class="content"></div>
    <div class="footer"></div>
  </div>
</template>

<script>

export default {
  name: 'App',
  components: {}
}
</script>

<style>

.header {
  margin: 0 auto;
  max-width: 960px;
  height: 100px;
  background-color: blue;
}

.content {
  margin: 0 auto;
  max-width: 960px;
  height: 400px;
  background-color: aquamarine;
}

.footer {
  margin: 0 auto;
  max-width: 960px;
  height: 100px;
  background-color: aqua;
}


</style>
