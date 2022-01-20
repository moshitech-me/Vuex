<template>
  <div class="counter-squared">
      <h2>State Getters</h2>
      {{$store.state.counter}}
      <sup>2</sup> = {{$store.getters.counterSquared}}

    </div>
</template>

<script>
export default {

}
</script>

<style>

</style>