<template>
  <div>
    <section class="home__main">
      <b-container fluid="xl">
        <b-row class="main__row">
          <b-col md="6" class="main__col">
            <div class="pt-5 mb-4">
              <h1 class="main__title">
                Encontre seu caminho para o <span class="underline">sucesso.</span>  
              </h1>
              <h3 class="main__subtitle">Trilhas de conhecimento para atingir o apice da sua carreira.</h3>
            </div>
            <home-search />
          </b-col>
          <b-col md="6" class="main__col">
            <div class="main__hero">
              <img src="~/assets/img/manreading.png">
            </div>
          </b-col>
        </b-row>
      </b-container>
    </section class="home__principles">
      <b-container fluid="xl" class="principles__container">
        <b-row>
          <b-col md="6">
            
          </b-col>
          <b-col md="6">
            <h2>Como funciona?</h2>
          </b-col>
        </b-row>
      </b-container>
    <section >
    </section>
    <section>
    </section>
  </div>
</template>

<script>
import HomeSearch from '../components/HomeSearch.vue'

export default {
  components:{
    HomeSearch
  }
}
</script>

<style>
.underline{
  text-decoration: underline;
}
.container {
  margin: 0 auto;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}
.home__main .main__row{
  margin-top: 40px;
}
.home__main{
  align-items: center;
}
.home__main .main__title{
  font-size: 4.5em;
  font-family: 'montserrat';
  color: #0d2a5e;
}
.main__subtitle{
  font-family: 'nunito-light';
}
.home__main .main__hero {
  background-image: linear-gradient(      rgb(244 88 66 / 55%),      rgb(237 255 224 / 0%)    );
  background-size: contain;
  background-repeat: no-repeat;
  display: flex;
  justify-content: flex-end;
}
.home__main .main__hero img{
  position: relative;
  top: -65px;
  transform: scaleX(-1);
  width: 95%;
}
.home__principles .principles__container{
  background: white;
}
</style>
