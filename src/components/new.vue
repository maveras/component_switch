<template>
  <div>
    <p> the new page</p>
    <p>counter: {{ counter }}</p>
    <button @click="counter++">counter</button>
  </div>

</template>
<script>
  export default {
    data () {
      return {
        counter: 0
      }
    },
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