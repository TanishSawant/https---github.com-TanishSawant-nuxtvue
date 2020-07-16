<template>
  <div class="jokePage">
      <h1>Jokes</h1>
  </div>
</template>

<script>
import axios from "axios";

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
        try {
            const res = await axios.get("https://icanhazdadjoke.com/search", config)
            this.jokes = res.data.results;
            console.log(this.jokes)    
        } catch (error) {
            console.log(error)
        }
        
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