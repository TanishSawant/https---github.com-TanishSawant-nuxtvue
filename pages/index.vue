<template>
  <section class="container">
    <div>
      <img class="imga" src="https://tse3.mm.bing.net/th?id=OIP.gaHwxo34nICH6VJCNNJpcwHaHa&pid=Api&P=0&w=300&h=300" alt="" width="300px" height="300px" srcset="">
      <div>
      <h1 class="title">
        Seguir aprendiendo español
      </h1>
      </div>
      <div class="links">
        <a
          href="https://www.youtube.com/"
          target="_blank"
          class="button--green">YouTube</a>
        <a
          href="https://www.google.com"
          target="_blank"
          class="button--grey">Google</a>
        <a
          href="https://www.spanishdict.com/"
          target="_blank"
          class="button--green">SpanishDict</a>
      </div>
    </div>
  </section>
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
  justify-content: center;
  align-items: center;
  text-align: center;
}

.imga {
  position: relative;
  bottom: 170px;
  left: 0px;
}



.title {
  position: absolute;
width: 547px;
height: 52px;
left: 496px;
top: 432px;

font-family: Poppins;
font-style: normal;
font-weight: normal;
font-size: 36px;
line-height: 54px;
text-align: center;
color: #051a47;
}

.para {
  bottom: 120px;
}

.subtitle {
position: absolute;
width: 547px;
height: 52px;
left: 496px;
top: 462px;

font-family: Poppins;
font-style: normal;
font-weight: normal;
font-size: 36px;
line-height: 54px;
text-align: center;
color: #DF2C3A;
}

.links {
  padding-top: 15px;
}
</style>
