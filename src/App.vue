<template>
<div class="container">
  <div class="row">
    <div class="col-xs-12">
      <app-quote>
        <h2>{{title}}</h2>
        <h3>subtitle</h3>
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
      title: 'Hello'
    }
  },
  components: {
    appQuote
  }
}
</script>

<style>
</style>
