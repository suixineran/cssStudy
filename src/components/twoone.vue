<template>
  <div class="parent" style="background-color: lightgrey;">
    <div class="left" style="background-color: lightblue;">
      <p>leftleftleftleftleftleftleftleftleftleftleftleftl
        eftleftleftleftleftleftleftleftleftleftleftleftleftleftleftleftleftleftleftleftleftleftleftleftleftleftleftleft</p>
    </div>
    <div class="right"  style="background-color: lightgreen;">
      <p>right</p>
      <p>right</p>
    </div>
  </div>
</template>

<script>
export default {
  name: "2-1"
}
</script>

<style scoped>
.parent {
  overflow: hidden;
  zoom: 1;
}
.left {
  float: left;
  margin-right: 20px;
}
.right {
  overflow: hidden;
  zoom: 1;
}


</style>