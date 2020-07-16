<template>
  <div class="header">
      <h1 class="title1">BienVenidos!</h1>
      <ul class="ul">
          <li>
              <nuxt-link to="/">Home</nuxt-link>
          </li>
          <li>
              <nuxt-link to="/Jokes">Jokes</nuxt-link>
          </li>
          <li>
              <a href="https://tanishsawant.github.io/https---github.com-TanishSawant-Quotes/" target="_blank" rel="noopener noreferrer">Quotes</a>
          </li>
          <li>
              <a href="https://www.spanishdict.com/wordoftheday" target="_blank" rel="noopener noreferrer">Word Of The Day</a>
          </li>
      </ul>
  </div>
</template>

<script>
export default {
    name: "AppHeader"
}
</script>

<style>

    .title1{
    font-family:
    'Quicksand',
    'Source Sans Pro',
    -apple-system,
    BlinkMacSystemFont,
    'Segoe UI',
    Roboto,
    'Helvetica Neue',
    Arial,
    sans-serif;
  display: block;
  font-weight: 500;
  font-size: 40px;
  color: #482c55;
  letter-spacing: 1px;

    }
    .header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin-bottom: 1rem;
    padding-bottom: 1rem;
    border-bottom: 1px dotted #ccc;
    }
    .header .title {
    font-size: 3rem;
    color: #526488;
    }
    .header ul {
    display: flex;
    }
    .header a {
    display: inline-block;
    background: #333;
    color: #fff;
    padding: 0.3rem 1rem;
    margin-right: 0.5rem;
    }
</style>