<template>
  <div class="container table">
    <div class="containerInner tableRow">
      <div class="column tableCell cell1">
        <div class="left aside">
          ....
        </div>
      </div>
      <div class="column tableCell cell2">
        <div class="content section">
          ...
        </div>
      </div>
      <div class="column tableCell cell3">
        <div class="right aside">
          ...
        </div>
      </div>
    </div>
  </div>

</template>

<script>
export default {
  name: "threefour"
}
</script>

<style scoped>
.table {
  width: auto;
  min-width: 1000px;
  margin: 0 auto;
  padding: 0;
  display: table;
}
.tableRow {
  display: table-row;
}
.tableCell {
  display: table-cell;
  width: 33%;
}
.cell1 {
  background: #f00;
  height: 800px;
}
.cell2 {
  background: #0f0;
}
.cell3 {
  background: #00f;
}

</style>