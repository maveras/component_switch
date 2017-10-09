<template>
<div class="container">
  <div class="row">
    <div class="col-xs-12">
      <button @click="selectedComponent='appQuote'">appQuote</button>
      <button @click="selectedComponent='author'">Author</button>
      <button @click="selectedComponent='New'">New</button>
      <app-quote>
        <h2 slot="title">{{title}}</h2>
        <h3 slot="subtitle">subtitle</h3>
      </app-quote>
      <keep-alive>
        <component :is='selectedComponent'></component>
      </keep-alive>
    </div>
  </div>
</div>
</template>

<script>
import appQuote from './components/quote.vue'
import author from './components/author.vue'
import New from './components/new.vue'

export default {
  data () {
    return {
      title: 'Hello',
      selectedComponent: 'appQuote'
    }
  },
  components: {
    appQuote,
    author,
    New
  }
}
</script>

<style>
</style>
