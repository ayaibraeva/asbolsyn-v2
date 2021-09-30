<template>
  <div class="wrapper">
    <img :src="require('../assets/bg/bg-shape1.png')" class="bg-shape"/>



  </div>
</template>

<script>
export default {
  name: "index"
}
</script>

<style lang="scss" scoped>
.wrapper{
  position: relative;
}
.bg-shape{
  position: absolute;
  max-width: 1076.35px;
  height: 1039px;
  top: -218px;
  left: -10%;

}
</style>
