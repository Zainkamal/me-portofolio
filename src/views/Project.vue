<script setup></script>
<template>
  <main class="bg-dark-subtle">
    <div class="container text-center p-4" style="width: 100%; height: 100%">
      <div class="d-flex justify-content-center">
        <h5 class="text-success">My</h5>
        <h5>Job</h5>
      </div>
      <h3 class="mb-5">Recent Projects</h3>
      <div class="row g-1">
        <div class="col-lg-4 content d-flex mb-2">
          <div class="img shadow-lg p-3 bg-body rounded">
            <img src="../assets/image.png" alt="" />
            <div class="title">
              <h5>WEB</h5>
              <p>My Portofolio</p>
              <a
                class="btn btn-primary"
                href="#"
                role="button"
                style="width: 4rem"
                >View</a
              >
            </div>
          </div>
        </div>
        <div class="col-lg-4 content d-flex mb-2">
          <div class="img shadow-lg p-3 bg-body rounded">
            <img src="../assets/hend-market.png" alt="" />
            <div class="title">
              <h5>WEB</h5>
              <p>Hend-Market</p>
              <a
                class="btn btn-primary"
                href="#"
                role="button"
                style="width: 4rem"
                >View</a
              >
            </div>
          </div>
        </div>
        <div class="col-lg-4 content d-flex mb-2">
          <div class="img shadow-lg p-3 bg-body rounded">
            <img src="../assets/kuliner.png" alt="" />
            <div class="title">
              <h5>WEB</h5>
              <p>Kuliner</p>
              <a
                class="btn btn-primary"
                href="#"
                role="button"
                style="width: 4rem"
                >View</a
              >
            </div>
          </div>
        </div>
        <div class="col-lg-4 content d-flex mb-2">
          <div class="img shadow-lg p-3 bg-body rounded">
            <img src="../assets/meja.png" alt="" />
            <div class="title">
              <h5>WEB</h5>
              <p>Meja (Mychet Unuja)</p>
              <a
                class="btn btn-primary"
                href="#"
                role="button"
                style="width: 4rem"
                >View</a
              >
            </div>
          </div>
        </div>
        <div class="col-lg-4 content d-flex mb-2">
          <div class="img shadow-lg p-3 bg-body rounded">
            <img src="../assets/simtren.png" alt="" />
            <div class="title">
              <h5>WEB</h5>
              <p>Simtren</p>
              <a
                class="btn btn-primary"
                href="#"
                role="button"
                style="width: 4rem"
                >View</a
              >
            </div>
          </div>
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
  display: flex;
  flex-direction: column;
  justify-content: center;
}
.content {
  display: flex;
  flex-wrap: wrap;
  gap: 10px;
}
.img {
  max-width: 25rem;
  position: relative;
  overflow: hidden;
  border-radius: 5px;
}
.img img {
  object-fit: cover;
  height: 100%;
  width: 100%;
  transition: 0.3s ease;
}
.title {
  content: "";
  color: white;
  height: 100%;
  width: 100%;
  position: absolute;
  left: 0;
  bottom: 0;
  top: 0;
  background: rgba(0, 0, 0, 0.623);
  z-index: 1;
  opacity: 0;
  transition: 0.3s ease;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}
.title:hover {
  opacity: 1;
}
</style>
