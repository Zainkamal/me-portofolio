<script setup></script>
<template>
  <main class="bg-dark-subtle">
    <div class="container text-center p-4" style="width: 100%; height: 100%">
      <div class="row m-lg-5" style="width: 100%; height: 100%">
        <div class="col-lg-4">
          <div class="text">
            <span class="material-icons fs-1"> pin_drop </span>
            <h5>Address</h5>
            <p>Karanganyar,Paiton</p>
            <p>Probolinggo,Jawa Timur</p>
          </div>
          <div class="text">
            <span class="material-icons"> call </span>
            <p>+62 82-228-124-176</p>
            <p>+62 82-782-278-717</p>
          </div>
          <div class="text">
            <span class="material-icons"> mail </span>
            <p>milfinzain@gmail.com</p>
            <p>zainkamal@gmail.com</p>
          </div>
        </div>
        <div class="col-lg-8">
          <h5>Send us a message</h5>
          <p>
            if you have any work from me or types of quries related to my
            tutorial,you can send me message from here. it's my pleasure to help
            you
          </p>
          <input
            type="text"
            class="form-control"
            id="exampleFormControlInput1"
            placeholder="User Name"
          />
          <input
            type="number"
            class="form-control"
            id="exampleFormControlInput1"
            placeholder="No HP"
          />
          <input
            type="email"
            class="form-control"
            id="exampleFormControlInput1"
            placeholder="Email"
          />
          <textarea
            class="form-control"
            id="exampleFormControlTextarea1"
            rows="3"
            placeholder="Message"
          ></textarea>
          <button type="button" class="btn btn-primary">Primary</button>
        </div>
      </div>
    </div>
  </main>
</template>
<style scoped>
main {
  width: 100%;
  height: 100vh;
  overflow: auto;
}
.container {
  display: flex;
  justify-content: center;
  overflow: auto;
}
.text {
  border-bottom: 1px solid white;
  margin-bottom: 10px;
}
p {
  font-size: 13px;
}
input,
textarea {
  margin-bottom: 10px;
}
</style>
