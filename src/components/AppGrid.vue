<template>
  <div id="container">
    <div class="box odd">1</div>
    <div class="box even">2</div>
    <div class="box odd">3</div>
    <div class="box even">4</div>
  </div>
</template>

<script>
export default {
  name: "AppGrid",
};
</script>

<style scoped>
#container {
  display: flex;
  width: 100%;
  border: 3px solid #000;
}

.box {
  width: 50%;
  height: 100px;
  color: #fff;

  display: flex;
  justify-content: center;
  align-items: center;
}

.odd {
  background-color: #00f;
}

.even {
  background-color: #f00;
}
</style>
