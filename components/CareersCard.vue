<template>
  <b-card
    bg-variant="dark"
    text-variant="white"
    :title="carrer"
    :sub-title="hits"
    class="card__carrers"
  >
  </b-card>
</template>
<script>
export default {
  props:{
    carrer:{
      type: String
    },
    hits:{
      type: String
    }
  }
}
</script>
<style>
  .card__carrers{
    background:linear-gradient(90deg, rgba(2,0,36,1) 0%, #47688c 0%, #4656e2 100%);
    border: none;
  }
  .card__carrers .card-title{
    font-size: 1.2rem;
  }
  .card__carrers .card-subtitle{
    font-family: 'nunito';
    color: white!important;
  }
</style>
