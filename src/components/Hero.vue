<template>
  <div>
    <h2>Heroes</h2>
  </div>
</template>

<script>
export default {
  name: 'Hero',

}
</script>

<style scoped>
  div{
    width: 500px;
    height: 400px;
    background-image: url(../assets/supereroi.jpg);
  }
  h2{
    text-align: center;
    color: rgba(255, 0, 0, 0.8);
    font-size: 32px;
    text-shadow: 0px 10px 20px rgba(0, 0, 0, 1);
  }
</style>