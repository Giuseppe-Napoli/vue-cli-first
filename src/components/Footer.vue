<template>
  <footer>
    <h3>creato con</h3> 
    <img src="../assets/logo.png" alt="logo">
  </footer>
</template>

<script>
export default {
  name: 'Footer'
}
</script>

<style scoped>
  footer{
    display: flex;
    align-items: center;
  }

  h3{
    font-family: cursive;
    margin-right: 5px;
  }

  img{
    width: 30px;
  }
</style>