<template>
  <div class="container">
    <div class="row">
      <div class="col-xs-12 col-sm-8 offset-sm-2 col-md-6 offset-md-3">
        <h1>VueX</h1>
        <app-result></app-result>
        <app-another-result></app-another-result>
        <hr>
        <app-counter></app-counter>
        <app-another-counter></app-another-counter>
      </div>
    </div>
  </div>
</template>

<script>
import Counter from "./components/Counter";
import AnotherCounter from "./components/AnotherCounter";
import Result from "./components/Result";
import AnotherResult from "./components/AnotherResult";

export default {
  name: 'App',
  components: {
    appCounter: Counter,
    appAnotherCounter: AnotherCounter,
    appResult: Result,
    appAnotherResult: AnotherResult,
  }

}
</script>

<style>

</style>
