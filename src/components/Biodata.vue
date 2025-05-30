<template>
  <div class="biodata">
    <h1>Biodata</h1>
    <img src="@/assets/profile.jpg" alt="Foto Profil" class="profile-img" />
    <ul>
      <li><strong>Nama:</strong> Sabrina Ella Zafira</li>
      <li><strong>NIM:</strong> 225150707111079</li>
      <li><strong>Email:</strong> sabrinaella@student.ub.ac.id</li>
      <li><strong>Asal:</strong> Malang, Jawa Timur</li>
      <li><strong>Riwayat Pendidikan:</strong> Universitas Brawijaya, Prodi Teknologi Informasi</li>
      <li><strong>Alamat:</strong> Jl. Soekarno Hatta No.10, Malang</li>
      <li><strong>Hobi:</strong> Olahraga dan Meelukis.</li>
      <li><strong>Deskripsi:</strong> Mahasiswa Teknologi Informasi, antusias dalam pengembangan aplikasi dan UI/UX.</li>
      <li><strong>Skills:</strong> Menguasau HTML, CSS, JavaScript, Vue, React, Java, Phyton, dan UI/UX Design</li>
      <li><strong>Pengalaman:</strong> Magang di IDN Times sebagai UI/UX Designer</li>
      <li><strong>Proyek:</strong> UI/UX Design untuk aplikasi mobile e-koran milik IDN Times</li>
      <li><strong>Organisasi:</strong> Anggota Divisi FrontEnd POROS</li>
      <li><strong>Bahasa:</strong> Menguasai Bahasa Indonesia (Lancar), Bahasa Inggris (Menengah), Bahasa Jepang (Pemula)</li>
    </ul>
  </div>
</template>

<style scoped>
.biodata {
  max-width: 600px;
  margin: auto;
  padding: 20px;
}
.profile-img {
  width: 150px;
  height: 150px;
  border-radius: 50%;
  object-fit: cover;
  margin-bottom: 20px;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  margin: 10px 0;
}
</style>
