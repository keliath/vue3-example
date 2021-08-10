<template>
  <div>
    <h1>Rick and Morty</h1>
    <list-characters />
  </div>
</template>

<script>
import ListCharacters from "@/components/ListCharacters";
export default {
  name: "App",
  components: {
    ListCharacters,
  },
};
</script>

<style lang="scss">
</style>
