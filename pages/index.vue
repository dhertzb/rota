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
              <h3 class="main__subtitle">Trilhas de conhecimento para atingir o ápice da sua carreira.</h3>
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
    </section>
    <b-container fluid="xl">
      <section class="home__principles bg-white">
          <b-row class="mt-3 py-5">
            <b-col md="6" class="d-flex justify-content-center">
              <img src="~/assets/img/roadmap.svg" />
            </b-col>
            <b-col md="6">
              <h2 class="principles__title">Como funciona?</h2>
              <h3 class="principles__subtitle w-75 my-4">No rumo a pessoa pode buscar sobre a carreira que tiver interesse digitando o que procura ou através de uma lista de possibilidades.</h3>
              <b-button pill class="bg-red" size="lg">Ver carreiras</b-button>  
            </b-col>
          </b-row>
      </section>
      <section class="bg-white py-5">
        <b-row>      
          <b-col md="12">
            <img class="gif__example" src="~/assets/img/roadmap.gif" />
          </b-col>
        </b-row>
      </section>
      <section class="home__carrers bg-white py-4 px-4">
          <b-row>
            <b-col class="text-center">
              <h2>Trilhas mais procuradas</h2>
            </b-col>
          </b-row>
          <b-row class="mt-3">
            <b-col md="4">
              <careers-card carrer="Desenvolvimento Front End" hits="1023 acessos"/>
            </b-col>
            <b-col md="4">
              <careers-card carrer="Desenvolvimento Back End"  hits="893 acessos"/>
            </b-col>
            <b-col md="4">
              <careers-card carrer="Medicina"  hits="562 acessos"/>
            </b-col>
          </b-row>
          <b-row class="mt-5">
            <b-col md="4">
              <careers-card carrer="Engenharia civil" hits="1023 acessos"/>
            </b-col>
            <b-col md="4">
              <careers-card carrer="Odontologia"  hits="893 acessos"/>
            </b-col>
            <b-col md="4">
              <careers-card carrer="Criação de conteúdo - Youtube"  hits="562 acessos"/>
            </b-col>
          </b-row>
      </section>
      <section>
      </section>
    </b-container>
  </div>
</template>

<script>
import CareersCard from '~/components/CareersCard.vue'
import HomeSearch from '../components/HomeSearch.vue'

export default {
  components:{
    HomeSearch,
    CareersCard
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
.principles__container{
  background: white;
}
.principles__title{
  font-family: 'montserrat-bold';
  color: #dc3545;
  font-size: 2.5rem;
}
.principles__subtitle{
  font-family: 'nunito-light';
  font-size: 1.6rem;
}
.bg-red{
  background-color: #f69a30;
  border:0;
}
.gif__example{
  width:110%;
  left: -5%;
  position: relative;
  box-shadow: 1px 2px 10px 2px rgba(0,0,0,0.18);
  border-radius: 20px;
}
</style>
