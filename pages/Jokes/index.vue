<template>
  <div class="jokePage">
      <h1>Jokes</h1>
  </div>
</template>

<script>
export default {
    data() {
        return {
            jokes: []
        }
    },
    
    async created() {
        const config = {
            headers: {
                'Accept' : 'application/json'
            }
        }
        const result = await axios.get("https://icanhazdadjoke.com/", config)
    },

    head() {
        return {
            title: 'Jokes',
            meta: [
                {
                    hid: "Jokes",
                    name: "Jokes",
                    content: "This is the joke page"
                }
            ]
        }
    }
}
</script>

<style>

</style>