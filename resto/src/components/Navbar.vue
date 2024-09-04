<template>
  <nav class="navbar navbar-expand-lg navbar-light bg-bluepastel">
    <div class="container">
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav">
          <li class="nav-item">
            <router-link class="nav-link" to="/">Home</router-link>
          </li>
          <li class="nav-item">
            <router-link class="nav-link" to="/project">Project</router-link>
          </li>
          <li class="nav-item">
            <router-link class="nav-link" to="/contact">Contact</router-link>
          </li>
        </ul>
      </div>
    </div>
    <div class="mb-2">
       <b-avatar  src="img/Albedo.jpg" v-b-popover.hover.bottomleft="'Halo! Nama saya Dina kumala sari. saya berasal dari jurusan PPLG SMKN 1 Kota Bengkulu.'" title="Tentang Saya"></b-avatar>
    </div>
  </nav>
</template>

<script>
export default {
  name: "NavbarView",
};
</script>

<style>
</style>