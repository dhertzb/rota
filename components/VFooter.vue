<template>
<div class="footer">
  <b-container fluid="xl">
    <b-row class="py-4">
      <b-col md="4">
        <img class="footer__logo"src="~/assets/brand/logo-white.svg">
        <h6 class="text-white mt-4">Telefone: (xx) xxxxx-xxxx</h6>
        <h6 class="text-white mt-4">Email: xxxx@xxxx.com</h6>
        <h6 class="text-white mt-4">Trabalhe conosco.</h6>
        <h6 class="text-white mt-4">Sobre.</h6>
      </b-col>
      <b-col md="8">
        <span class="text-white mt-5 footer__description">
          Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed sodales lorem nec nulla semper, sit amet sodales ligula pharetra. Vestibulum ante ipsum primis in faucibus orci luctus et ultrices posuere cubilia curae; Phasellus molestie ultrices leo, in tincidunt sapien feugiat quis. Ut et elit sit amet arcu egestas volutpat eget tincidunt nisl. Suspendisse ac vestibulum augue. Nullam dictum odio ac enim cursus, non tempus mi facilisis. Suspendisse non convallis lacus. Mauris varius quis nisi in lobortis. Pellentesque ultrices malesuada neque, non pellentesque lacus scelerisque sed. Suspendisse sit amet turpis libero. 
        </span>
      </b-col>
    </b-row>
  </b-container>
</div>
</template>
<script>
export default {
  
}
</script>
<style scoped>
.footer{
  margin-top: 50px;
  background: #0d2a5e;
}
.footer__logo{
  width: 120px;
}
.footer__description{
  font-family: 'nunito';
}
</style>