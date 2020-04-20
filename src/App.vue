<template>
  <div class="container">
    <div class="row">
      <div class="col-xs-12 col-sm-8 offset-sm-2 col-md-6 offset-md-3">
        <h1>VueX</h1>
        <app-result></app-result>
        <hr>
        <app-counter></app-counter>
      </div>
    </div>
  </div>
</template>

<script>
import Counter from "./components/Counter";
import Result from "./components/Result";

export default {
  name: 'App',
  components: {
    appCounter: Counter,
    appResult: Result,
  }

}
</script>

<style>

</style>
