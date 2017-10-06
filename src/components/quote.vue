<template>
  <div>
    <slot name="title"></slot>
    <slot name="subtitle"></slot>
    <slot name="defaultq"> I am a default quote, i will appear when i dont exist in the parent</slot>
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