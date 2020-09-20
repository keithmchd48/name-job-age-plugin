<template>
  <div id="app">
    {{ $myInfo(`Keith ${$surname}`, 26) }}
    <!-- My name is Keith and I am a 26 years old Web Dev. -->
  </div>
</template>

<script>
    export default {
        name: 'App',
        created() {
            console.log(this.$surname) // Smith
            this.$surname = 'Machado'
            console.log(this.$surname) // Blacksmith
        }
    }
</script>

<style>
</style>
