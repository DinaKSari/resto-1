<template>
  <div>
    <NavbarView />
    <div class="container mt-3 grid cols-sm-2">
      <BreadCrumb />
      <div style="background-color: azure; border-radius: 50%; padding: 30px 30px 30px 30px;">

      </div>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
import NavbarView from '@/components/Navbar.vue'
import BreadCrumb from '@/components/CrudBar.vue'

export default {
    name : 'FoodView',
    components: {
      NavbarView,
      BreadCrumb,
    }
}
</script>

<style>

</style>