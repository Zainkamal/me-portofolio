<script setup></script>
<template>
  <main class="bg-dark-subtle">
    <div class="row" style="width: 100%; height: 100%">
      <div
        class="top d-flex text-center justify-content-center align-items-center"
      >
        <h3 class="text-primary me-1 fs-1">My</h3>
        <h3 class="">Resume</h3>
      </div>
      <div
        class="col-lg-4 border d-flex flex-column justify-content-center p-5"
      >
        <h3>Education</h3>
        <div class="bg-primary" style="width: 15%; height: 3px"></div>
        <br />
        <div class="">
          <h5 class="text-primary">2013-2016</h5>
          <p>SMP Nurul Abror Al-Robbaniyyin</p>
          <p class="text">
            Sekolah Menengah Pertama berakreditasi B, terdaftar dengan nomor SK:
            421/1402/429.101/2011, nomor NPSN 20574616, beralamat di Jl. Kh.
            Agus Salim No. 165 Kelurahan Alasbulu Kecamatan Wongsorejo Kab.
            Banyuwangi - Provinsi Jawa Timur, Berada dalam naungan YAYASAN NURUL
            ABROR AL-ROBBANIYIN.
          </p>
        </div>
        <div class="">
          <h5 class="text-primary">2016-2019</h5>
          <p>SMK Nurul Abror Al-Robbaniyyin</p>
          <p class="text">
            SMK Nurul Abror Al Robbaniyin berlokasi di Jl. KH. Agus Salim No.
            165, Alasbulu Wongsorejo, Krajan I, Alasbulu, Banyuwangi, Kabupaten
            Banyuwangi, Jawa Timur 68453,
          </p>
        </div>
        <div class="">
          <h5 class="text-primary">2019-Sekarang</h5>
          <p>Universitas Nurul Jadid - Fakultas Teknik - Informatika</p>
          <p class="text">
            Universitas Nurul Jadid (UNUJA) terletak di wilayah Kecamatan
            Paiton, Probolinggo. UNUJA adalah Perguruan Tinggi berbasis
            pesantren, dan merupakan penggabungan dari tiga Perguruan Tinggi
            yang telah berdiri sebelumnya di bawah naungan Yayasan Nurul Jadid,
            yakni IAI Nurul Jadid, STT Nurul Jadid, dan STIKES Nurul Jadid.
            Pendirian UNUJA diresmikan oleh Menristekdikti, Prof. H. Mohamad
            Nasir, Ph.D., pada 29 Oktober 2017.
          </p>
        </div>
      </div>
      <div
        class="col-lg-4 border d-flex flex-column justify-content-center p-5"
      >
        <h3>Expertise</h3>
        <div class="bg-primary" style="width: 15%; height: 3px"></div>
        <br />
        <div class="">
          <h5 class="text-primary">Semester 4</h5>
          <p>Labe-Base</p>
          <p class="text">
            Fakultas Teknik di Universitas Nurul Jadid mengadakan sebuah program
            untuk mahasiswa/mahasiswi dalam memahami pemograman berbasis WEB.
            dalam hal ini dosen membarikan materi HTML 5 , CSS3 , JavaScripts
            dan SASS kepada peserta. dengan tujuan memahami dasar-dasar bahasa
            pemograman berbasis WEB.
          </p>
        </div>
        <div class="">
          <h5 class="text-primary">Semester 6</h5>
          <p>Foundations of AI and Life Skills for Gen-Z</p>
          <p class="text">
            Program MSIB Foundations of AI and Life Skill for Gen-Z merupakan
            program pelatihan artivical Intelligence secara online untuk pelajar
            yang bertujuan bukan hanya untuk memperkenalkan teknologi AI ke
            pelajar,tapi juga untuk memungkinkan mereka bisa mengangkat
            perangkat AI, sehingga bisa membuat sesuatu produk yang menciptakan
            dampak social, berfokus pada pada domain utama AI (Data Science,
            Natural Language Processing, Computer Vision) dari level basic
            sampai level advance mencakup bahasa pemrograman Python dan AI
            Project Cycle (Problem Scoping, Data Acquisition, Data Exploration,
            Modelling, Evaluation dan Deployment).
          </p>
        </div>
        <div class="">
          <h5 class="text-primary">Semester 7</h5>
          <p>Boatcamp front-and Developer</p>
          <p class="text">
            Fakultas Teknik di Universitas Nurul Jadid mendirikan sebuah
            comunitas IT (COMMIT) untuk para mahasiswa/mahasiswi.comunitas ini
            mengadakan sebuah bootcamp untuk peserta yang telah lulus
            seleksi.beberapa bidang yang diterapkan didalam bootcemp ini,yaitu
            front-and (vue.js),back-and (node.js), dan Mobile (kotlin). sehingga
            mempunyai tujuan menciptakan sebuah aplikasi pesantren.
          </p>
        </div>
      </div>
      <div
        class="col-lg-4 border d-flex flex-column justify-content-center p-5"
      >
        <h3>Skills</h3>
        <div class="bg-primary" style="width: 15%; height: 3px"></div>
        <br />
        <div class="">
          <p class="fw-bold">HTML 5</p>
          <div class="bg-primary mb-3" style="width: 80%; height: 5px"></div>
          <p class="fw-bold">CSS 3</p>
          <div class="bg-primary mb-3" style="width: 60%; height: 5px"></div>
          <p class="fw-bold">JavaScripts</p>
          <div class="bg-primary mb-3" style="width: 40%; height: 5px"></div>
          <p class="fw-bold">Vue.js</p>
          <div class="bg-primary mb-3" style="width: 50%; height: 5px"></div>
          <p class="fw-bold">Mobile Legent</p>
          <div class="bg-primary mb-3" style="width: 100%; height: 5px"></div>
        </div>
      </div>
    </div>
  </main>
</template>
<style scoped>
main {
  width: 100%;
  max-height: 100vh;
  overflow: auto;
}
.left {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  text-align: center;
}
.link {
  border: 1px solid black;
  margin-right: 10px;
  text-decoration: none;
  color: rgb(0, 0, 0);
  padding: 25px 25px;
  border-radius: 50%;
}
.text {
  font-size: 12px;
}
@media (max-width: 768px) {
  .box {
    height: auto;
  }
  h3,
  h5,
  p {
    font-size: 15px;
    margin-top: 10px;
  }
  .link {
    padding: 10px;
    font-size: 12px;
  }
}
</style>
