<template>
<div class="container">
  <div class="row">
    <div class="col-xs-12">
      <app-quote msg="hellow">
      </app-quote>
    </div>
  </div>
</div>
</template>

<script>
import appQuote from './components/quote.vue'

export default {
  data () {
    return {
      msg: ''
    }
  },
  components: {
    appQuote
  }
}
</script>

<style>
</style>
