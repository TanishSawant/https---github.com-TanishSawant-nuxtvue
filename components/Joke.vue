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
    .jokes{
        padding: 1rem;
        border: 1px dotted #ccc;
        margin: 1rem 0;
    }
</style>