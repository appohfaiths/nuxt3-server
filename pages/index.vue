<script lang="ts" setup>

const { data: charmander} = await useFetch('https://pokeapi.co/api/v2/pokemon/charmander')
</script>

<template>
  <div>
    Home Page for Nuxt 3 server course
  </div>
  <pre>
    {{ charmander }}
  </pre>
</template>

<style scoped></style>
