<template>
  <div id="wrapper">
    <div id="mainContent">...</div>
    <div id="sidebar">...</div>
  </div>

</template>

<script>
export default {
  name: "threefive"
}
</script>

<style scoped>
#wrapper {
  width: 960px;
  margin: 0 auto;
}
#mainContent {
  border-right: 220px solid #dfdfdf;
  position: absolute;
  width: 740px;
  height: 800px;
  background: green;
}
#sidebar {
  background: #dfdfdf;
  margin-left: 740px;
  position: absolute;
  height: 800px;
  width: 220px;
}

</style>