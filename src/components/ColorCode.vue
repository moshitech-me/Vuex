<template>
  <h2>Two way data binding</h2>
    <input type="text" 
    v-model="colorCode"
    placeholder="Enter color code">
</template>

<script>
export default {
computed:{
    colorCode:{
      get(){
        return this.$store.state.colorCode
      },
      set(newValue){
       this.$store.dispatch('setColorCode',newValue)
       // we can also commit like following way directly but not a good practice
       //this.$store.commit('setColorCode',newValue)
      }
    }
  },
}
</script>

<style>

</style>