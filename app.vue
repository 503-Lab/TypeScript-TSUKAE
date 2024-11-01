<template>
  <div id="app" class="black-background">
    <p>TypeScriptつかえ</p>
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue';

export default defineComponent({
  name: 'App',
});
</script>

<style>
.black-background {
  background-color: black;
  height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
}

p {
  color: white;
  font-size: 2em;
}
</style>
