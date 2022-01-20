<template>
  <div class="buttons">
      <h2>Dispatch Action</h2>
      <button @click="$store.dispatch('decreaseCounterFromAction')">-</button>
      <button @click="$store.dispatch('increaseCounterFromAction')">+</button>
    </div>
</template>

<script>
export default {

}
</script>

<style>

</style>
    