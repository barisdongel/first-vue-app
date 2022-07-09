<script setup>
// This starter template is using Vue 3 <script setup> SFCs
// Check out https://vuejs.org/api/sfc-script-setup.html#script-setup
import HelloWorld from './components/HelloWorld.vue';
</script>

<template>
  <div class="card">
    <div class="user-img">
      <img
        src="https://avatars.githubusercontent.com/u/29428301?v=4"
        alt="user-img"
      />
    </div>
    <div class="card-body">
      <h1>Barış Ömer DÖNGEL</h1>
      <nav class="social">
        <a href="#" class="social-item">Github</a>
        <a href="#" class="social-item">Twitter</a>
        <a href="#" class="social-item">Instagram</a>
        <a href="#" class="social-item">LinkedIn</a>
      </nav>
      <p>
        Merhaba. Ben Barış. Web geliştiricisiyim. Birlikte çalışmak için mail
        atın.
      </p>
      <a href="mailto:barisdng26@gmail.com" class="mail-link"
        >barisdng26@gmail.com</a
      >
    </div>
  </div>
</template>
<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Lobster&display=swap');
.card {
  max-width: 600px;
  border: 1px solid #ddd;
  box-shadow: 1px 1px 6px #000;
}
.user-img img {
  border-radius: 300px;
  width: 50%;
}
.card-body h1 {
  font-family: 'Lobster', cursive;
  color: indigo;
}
.card-body p {
  font-family: 'calibri', cursive;
  margin-bottom: 35px;
}
.social {
  padding: 10px;
}
.social .social-item {
  margin: 10px;
  padding: 10px;
  border-bottom: 1px solid indigo;
}
.social .social-item:hover {
  color: indigo;
}
.mail-link {
  color: indigo;
  font-size: 22px;
  font-family: 'calibri';
  border: 1px solid #ddd;
  padding: 10px;
  transition: 0.2s;
}
.mail-link:hover {
  background-color: indigo;
  color: #fff;
}
</style>
