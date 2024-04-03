<template>
  <div>
    <!-- Tombol untuk memicu pop-up -->
    <button @click="showPopup = true">Klik</button>

    <!-- Pop-up -->
    <div v-if="showPopup" class="popup">
      <div class="popup-content">
        <!-- Konten Pop-up -->
        <h2>My Instagram</h2>
        <a href="https://www.instagram.com/f_audina/">Coba Klik</a>
        <!-- Tombol untuk menutup pop-up -->
        <button @click="showPopup = false">Tutup Pop-up</button>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      showPopup: false // Status untuk menampilkan atau menyembunyikan pop-up
    };
  }
};
</script>

<style>
/* Gaya untuk pop-up */
.popup {
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background-color: rgba(0, 0, 0, 0.5); /* Transparan hitam sebagai latar belakang */
  display: flex;
  justify-content: center;
  align-items: center;
}

.popup-content {
  background-color: #fff;
  padding: 20px;
  border-radius: 5px;
  box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.5);
}
</style>
