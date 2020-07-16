<template>
  <div class="container">
    <img class="imga" src="https://tse3.mm.bing.net/th?id=OIP.gaHwxo34nICH6VJCNNJpcwHaHa&pid=Api&P=0&w=300&h=300" alt="" width="300px" height="300px" srcset="">
    <div class="title">
      <h1>Sigue Aprendiendo Español</h1>
    </div>
  </div>
</template>

<script>
export default {
  head() {
        return {
            title: 'BienVenidos!',
            meta: [
                {
                    hid: "Home",
                    name: "Starter",
                    content: "This is the landing Page"
                }
            ]
        }
    }
}
</script>

<style>
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  vertical-align: 0%;
  justify-content: center;
  align-items: center;
  text-align: center;
  flex-direction: column;
}

.imga {
  position: relative;
  bottom: 200px;
  left: 0px;
}

.title {
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
  font-weight: 300;
  font-size: 20px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}
</style>
