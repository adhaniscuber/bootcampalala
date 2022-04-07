<template>
  <div class="nav">
  <navbar></navbar>
  <div class="container">
    <product-image-vue></product-image-vue>
  </div>
  <div class="containergambar">
    <card-vue></card-vue>
    <div class="footer">
      <footer-vue></footer-vue>
    </div>
  </div>
</div>
</template>

<script>
import Navbar from '../components/navbar.vue'
import footerVue from '../components/footer.vue'
import cardVue from '../components/card.vue'
import productImageVue from '../components/product-image.vue'
export default {
  components: {
    Navbar,
    footerVue,
    cardVue,
    productImageVue
  },
  
  metaInfo: {
    title: 'Hai ini nyoba aja ya.'
  }
}
</script>

<style>
.home-links a {
  margin-right: 1rem;
}
* {
  box-sizing:border-box;
  margin:0px;
  padding:0px;
}
</style>
