<template>
  <div class="shouYue">
    <p>总数量：{{num}}</p>
  </div>
</template>
<script>
export default {
  data() {
    return {
      num: 18,
    };
  },
};
</script>
<style scoped>
.shouYue {
  width: 300px;
  height: 100px;
  text-align: center;
  font-size: 30px;
  margin: 0 auto;
  margin-top: 30px;
  border: 3px solid black;
}
</style>