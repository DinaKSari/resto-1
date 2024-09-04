<template>
<div>
  <b-card-group deck>
    <b-card title="School Suite" img-src="img/wan.jpg" img-alt="Image" img-top>
      <b-card-text>
        Saya termasuk ke dalam tim Front End sebagai ketua tim. Proyek School Suite merupakan Proyek besar di sekolah kami. Tugas saya sebagai ketua adalah mengelola dan mengatur pembagian tugas anggota tim. Sedangkan sebagai tim Front End, tugas saya adalah membuat tampilan mock up, login dan register.
      </b-card-text>
      <template #footer>
        <small class="text-muted">2022 - 2023</small>
      </template>
    </b-card>

    <b-card title="Game Edukasi di Mobile" img-src="img/wan.jpg" img-alt="Image" img-top>
      <b-card-text>
        Game ini saya buat menggunakan game engine Construct 2. Game ini merupakan game edukasi anak untuk mempelajari sejarah Indonesia.
      </b-card-text>
      <template #footer>
        <small class="text-muted">2022</small>
      </template>
    </b-card>

    <b-card title="Website Restaurant" img-src="img/wan.jpg" img-alt="Image" img-top>
      <b-card-text>
        Website ini saya buat dengan menggunakan Vue cli. Kita dapat melihat melihat menu lalu memesan makanan yang kita inginkan.
      </b-card-text>
      <template #footer>
        <small class="text-muted">2022</small>
      </template>
    </b-card>
  </b-card-group>
</div>
</template>
<script>
export default{
    name: 'CardPro'
}
</script>