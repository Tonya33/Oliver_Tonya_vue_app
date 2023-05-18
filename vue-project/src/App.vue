<script setup>
import HelloWorld from './components/HelloWorld.vue'
import TheWelcome from './components/TheWelcome.vue'
</script>

<template>
  <header>
    <img alt="Vue logo" class="logo" src="./assets/birdie-logo.svg" width="125" height="125" />

    <div class="wrapper">
      <HelloWorld msg="Hello and Welcome to tonya's app!" />
    </div>
  </header>

  <main>
    <TheWelcome />
  </main>
</template>

<style scoped>

</style>
