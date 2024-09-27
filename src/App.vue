<template>
  <div>
    <h1>
      {{name}}
    </h1>
  </div>
</template>
<script lang="ts">
import { defineComponent } from 'vue'

export default defineComponent({
  data: function() {
    return {
      name: 'Hello World!',
    }
  },
});
</script>

<style>
h1 {
  color: white;
  background-color: black;
}
</style>
<style lang="scss">
$primary-color: white;
$bg: black;
h1 {
  color: $primary-color;
  background-color: $bg;
}
</style>
