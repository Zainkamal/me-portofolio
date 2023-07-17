<script setup>
import { ref } from "vue";

const is_expanded = ref(false);

const ToggleMenu = () => {
  is_expanded.value = !is_expanded.value;
};
</script>
<template>
  <div class="word">
    <aside :class="`${is_expanded ? 'is-expanded' : ''}`">
      <div class="top position-absolute">
        <span class="material-icons text-bg-dark" @click="ToggleMenu">
          keyboard_double_arrow_right
        </span>
      </div>
      <div class="logo m-auto mt-5 mb-3">
        <img
          class="img"
          src="../assets/satu.jfif"
          alt=""
          style="max-width: 6rem"
        />
      </div>
      <h3 class="fs-5 text-center">Milfin Z.A</h3>
      <br />
      <div class="boxs">
        <div class="menu">
          <router-link to="/" class="button">
            <span class="material-icons">home</span>
            <span class="text">Home</span>
          </router-link>
          <router-link to="/aboutme" class="button">
            <span class="material-icons">home</span>
            <span class="text">About</span>
          </router-link>
          <router-link to="/resume" class="button">
            <span class="material-icons">description</span>
            <span class="text">Resume</span>
          </router-link>
          <router-link to="/project" class="button">
            <span class="material-icons"> hive </span>
            <span class="text">Project</span>
          </router-link>
          <router-link to="/contact" class="button">
            <span class="material-icons"> contact_mail </span>
            <span class="text">Contact</span>
          </router-link>
        </div>
        <div class="menu">
          <div class="button d-flex justify-content-around">
            <i class="bi bi-facebook"></i>
            <i class="bi bi-instagram"></i>
            <i class="bi bi-telegram"></i>
            <i class="bi bi-github"></i>
          </div>
        </div>
      </div>
    </aside>
  </div>
</template>
<style scoped>
.word {
  z-index: 180;
}
aside {
  display: flex;
  flex-direction: column;
  background-color: rgb(8, 2, 44);
  color: white;
  z-index: 99;
  width: 12rem;
  overflow: hidden;
  height: 100vh;

  transition: 0.2 ease-in-out;

  .top {
    z-index: 150;
    margin-left: 200px;
    margin-top: 10px;
    cursor: pointer;
  }

  .boxs {
    height: 100%;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
  }
  .button {
    display: flex;
    align-items: center;
    text-decoration: none;
    background-color: rgb(3, 3, 119);
    margin-left: 15px;
    margin-bottom: 15px;
    border-radius: 30px 0 0 30px;

    transition: 0.2s ease-in-out;
    padding: 0.5rem 0.5rem;
  }
  .button:hover {
    transform: scale(1.1, 1.1);
    cursor: pointer;
  }
  .text {
    color: white;
    opacity: 1;
  }
  .material-icons {
    color: white;
    margin-right: 10px;
    font-size: 25px;
  }
  &.is-expanded {
    width: 0;
    padding: 0;

    .top {
      margin-left: 5px;
    }
  }
}

.logo {
  width: 6rem;
  height: 7rem;
  overflow: hidden;
  margin-bottom: 1rem;
  border: 1px solid wheat;
  border-radius: 50%;
}

&.router-link-exact-active {
  background-color: blue;
  border-right: 5px solid blue;

  .material-icons,
  .text {
    color: white;
  }
}
@media (max-width: 768px) {
  .word {
    z-index: 180;
    position: fixed;
  }
  aside {
    width: 10rem;

    .top {
      margin-left: 120px;
    }
  }
  .text {
    font-size: 13px;
  }
}
</style>
