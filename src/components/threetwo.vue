<template>
  <article class="container">
    <div class="center">
      <div class="inner">双飞翼布局</div>
    </div>
    <div class="left"></div>
    <div class="right"></div>
  </article>

</template>

<script>
export default {
  name: "threetwo"
}
</script>

<style scoped>
.container {
  min-width: 600px;/*确保中间内容可以显示出来，两倍left宽+right宽*/
}
.left {
  float: left;
  width: 200px;
  height: 400px;
  background: red;
  margin-left: -100%;
}
.center {
  float: left;
  width: 100%;
  height: 500px;
  background: yellow;
}
.center .inner {
  margin: 0 200px; 
}
.right {
  float: left;
  width: 200px;
  height: 400px;
  background: blue;
  margin-left: -200px;
}

</style>