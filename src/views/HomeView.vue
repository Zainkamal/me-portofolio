<script setup></script>
<template>
  <div
    class="box alert-danger bg-dark-subtle"
    style="min-height: 100vh; width: 100%"
  >
    <div class="row" style="width: 100%; height: 100%">
      <div class="col-lg-6 left">
        <div class="img">
          <img class="" src="../assets/aku.png" alt="" />
        </div>
        <br />
        <h3 class="">Milfin Zainul Asiqin</h3>
        <p class="">Fron-dend Developer</p>
        <div class="bg-primary" style="width: 60%; height: 5px"></div>
      </div>
      <div class="col-lg-6 left p-3">
        <h3>HELLO</h3>
        <h5>I`am Milfin</h5>
        <p>
          I`am Milfin Front-End Developer, I create web pages with UI / UX user
          interface, I have years of experience and many clients are happy with
          the project carrried out.
        </p>
        <br /><br />
        <div class="menu">
          <router-link to="/" class="link bg-primary">home </router-link>
          <router-link to="/aboutme" class="link bg-primary"
            >about
          </router-link>
          <router-link to="/resume" class="link bg-primary"
            >Resume
          </router-link>
          <router-link to="/project" class="link bg-info">Project </router-link>
          <router-link to="/contact" class="link bg-warning"
            >Contact
          </router-link>
        </div>
      </div>
    </div>
  </div>
</template>
<style scoped>
.box {
  overflow: hidden;
}
.left {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  text-align: center;
}
.img {
  border: 1px solid rgb(0, 0, 0);
  background-color: transparent;
  border-radius: 45% 45% 0 0;
  padding-top: 20px;
}
.img img {
  width: 19rem;
}
.menu {
  display: flex;
  justify-content: center;
}
.link {
  border: 1px solid black;
  margin-right: 10px;
  text-decoration: none;
  color: rgb(0, 0, 0);
  padding: 25px 25px;
  border-radius: 50%;
}
@media (max-width: 768px) {
  .box {
    height: auto;
  }
  .img {
    margin-top: 20px;
  }
  .img img {
    width: 15rem;
  }
  .menu {
    margin-left: 25px;
  }
  h3,
  h5,
  p {
    font-size: 15px;
  }
  .link {
    padding: 10px;
    font-size: 12px;
  }
}
</style>
