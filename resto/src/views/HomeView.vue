<template>
  <div class="home">
    <NavbarView />
    <div class="container mt-3 grid cols-sm-2">
      <BreadCrumb  />
      <CardProduct />
      <hr>
    </div>
    <div class="container grid cols-sm-2" style="margin-top: 15%; margin-bottom: 5%;">
      <CardSaya class="grid-cols-4" />
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
import NavbarView from '@/components/Navbar.vue'
import CardProduct from '@/components/CardProduct.vue'
import BreadCrumb from '@/components/CrudBar.vue'
import CardSaya from '@/components/CardSaya.vue'

export default {
  name: 'HomeView',
  components: {
    NavbarView,
    CardProduct,
    BreadCrumb,
    CardSaya,
  },
}
</script>
