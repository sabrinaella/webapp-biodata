<template>
  <div class="container">
    <h1 class="title">Curriculum Vitae</h1>
    <img src="@/assets/profile.jpg" alt="Foto Profil" class="profile-img" />

    <table class="biodata-table">
      <tr>
        <th>Nama</th>
        <td>Sabrina Ella Zafira</td>
      </tr>
      <tr>
        <th>NIM</th>
        <td>225150707111079</td>
      </tr>
      <tr>
        <th>Email</th>
        <td>sabrinaella@student.ub.ac.id</td>
      </tr>
      <tr>
        <th>Asal</th>
        <td>Malang, Jawa Timur</td>
      </tr>
      <tr>
        <th>Riwayat Pendidikan</th>
        <td>Universitas Brawijaya, Prodi Teknologi Informasi</td>
      </tr>
      <tr>
        <th>Alamat</th>
        <td>Jl. Soekarno Hatta No.10, Malang</td>
      </tr>
      <tr>
        <th>Hobi</th>
        <td>Olahraga dan Melukis</td>
      </tr>
      <tr>
        <th>Deskripsi</th>
        <td>Mahasiswa Teknologi Informasi, antusias dalam pengembangan aplikasi dan UI/UX.</td>
      </tr>
      <tr>
        <th>Skills</th>
        <td>Menguasai HTML, CSS, JavaScript, Vue, React, Java, Python, dan UI/UX Design</td>
      </tr>
      <tr>
        <th>Pengalaman</th>
        <td>Magang di IDN Times sebagai UI/UX Designer</td>
      </tr>
      <tr>
        <th>Proyek</th>
        <td>UI/UX Design untuk aplikasi mobile e-koran milik IDN Times</td>
      </tr>
      <tr>
        <th>Organisasi</th>
        <td>Anggota Divisi FrontEnd POROS</td>
      </tr>
      <tr>
        <th>Bahasa</th>
        <td>Menguasai Bahasa Indonesia (Lancar), Bahasa Inggris (Menengah), Bahasa Jepang (Pemula)</td>
      </tr>
    </table>
  </div>
</template>

<script>
export default {
  name: 'App',
}
</script>

<style>
/* Membuat halaman full screen dan center menggunakan Flexbox */
body, #app {
  margin: 0;
  padding: 0;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  background-color: #333; /* Latar belakang halaman soft cream */
}

.container {
  width: 100%;
  max-width: 800px;
  text-align: center;
  font-family: Arial, sans-serif;
  padding: 20px;
  background-color: #fffaf0; /* Warna kertas CV */
  color: #333; /* Abu gelap */
  box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
  border-radius: 10px;
}

.title {
  font-size: 32px;
  font-weight: bold;
  margin-bottom: 20px;
  color: #333;
}

.profile-img {
  width: 200px;
  height: 200px;
  border-radius: 50%;
  object-fit: cover;
  margin-bottom: 30px;
  border: 4px solid #D7D3BF; /* Border cream muda */
}

.biodata-table {
  width: 100%;
  border-collapse: collapse;
  background-color: #fffaf0;
  color: #333;
  margin-top: 20px;
}

.biodata-table th,
.biodata-table td {
  border: 2px solid #D7D3BF;
  padding: 12px 15px;
  text-align: left;
}

.biodata-table th {
  background-color: #ECEBDE;
  font-weight: bold;
  width: 200px;
}
</style>
