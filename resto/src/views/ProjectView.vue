<template>
  <div>
    <NavbarView />
    <div class="container mt-3">
      <BreadCrumb />
      <h1 class="text-widest text-center mb-3">Project yang saya buat dan saya ikuti</h1>
      <CardPro />
    </div>
  </div>
    
</template>

<script>
import NavbarView from '@/components/Navbar.vue'
import BreadCrumb from '@/components/CrudBar.vue'
import CardPro from '@/components/CardPro.vue'

export default {
  name: 'HomeView',
  components: {
    NavbarView,
    BreadCrumb,
    CardPro,

  },
}
</script>
