<template>
  <div>
    <p> i am the author page</p>
  </div>

</template>
<script>
  export default {
    props:['msg']
  }
</script>
<style scoped>
 div {
    border: 1px solid #ccc;
    box-shadow: 1px 1px 2px black;
    padding: 30px;
    margin: 30px auto;
    text-align: center;
  }

  h2 {
    color: red;
  }
</style>