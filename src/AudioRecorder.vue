<template>
  <div class="audio-recorder">
    <button @click="onClick">Play</button>
  </div>
</template>

<script>
export default {
 props: {},

 methods: {
  onClick(event) {
   this.$emit("click", event);
  },
 }
};
</script>

<style>

</style>
