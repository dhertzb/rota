<template>
  <b-input-group>
    <b-form-input size="lg" v-model="query" placeholder="Digite a carreira"></b-form-input>
     <b-input-group-append>
      <b-button @click="search" variant="outline-secondary" class="bg-blue">Pesquisar</b-button>
     </b-input-group-append>
  </b-input-group>
  </div>
</template>
<script>
export default {
  data(){
    return{
      query: ''
    }
  },
  methods:{
    search(){
      this.$router.push({
        path: `/carreiras/${this.query}`
      })
    }
  }
}
</script>
<style>
  .bg-blue{
    background-color:rgb(244 88 66 / 1);
    color: white;
    border: none;
  }
</style>