<template>
  <div class="jokes">
      <p>{{ joke }}</p>
  </div>
</template>

<script>
export default {
    name: "joke",
    props: ["id", "joke"]
}
</script>

<style>

</style>