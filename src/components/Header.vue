<script setup></script>
<template>
  <nav
    class="navbar navbar-expand-lg navbar-light bg-light shadow p-3 bg-body rounded sticky-top"
  >
    <div class="container-fluid">
      <div class="d-flex align-items-center">
        <div class="kotak"></div>
        <h5>Milfin Z.A</h5>
      </div>
      <button
        class="navbar-toggler fs-5"
        type="button"
        data-bs-toggle="collapse"
        data-bs-target="#navbarSupportedContent"
        aria-controls="navbarSupportedContent"
        aria-expanded="false"
        aria-label="Toggle navigation"
      >
        <span class="navbar-toggler-icon"></span>
      </button>
      <div
        class="collapse navbar-collapse justify-content-end"
        id="navbarSupportedContent"
      >
        <ul class="navbar-nav">
          <li class="nav-item">
            <a class="nav-link active" aria-current="page" href="#">About me</a>
          </li>

          <li class="nav-item">
            <a class="nav-link" href="#resume">Resume</a>
          </li>

          <li class="nav-item">
            <a class="nav-link" href="#">Project</a>
          </li>

          <li class="nav-item">
            <a class="nav-link" href="#">Contact</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>
</template>
<style scoped>
.kotak {
  width: 10px;
  height: 10px;
  background: blue;
  margin-right: 10px;
  margin-bottom: 5px;
}
</style>
