<script setup>
import TheWelcome from '../components/TheWelcome.vue'
</script>

<template>
  <main>
    <section id="profile">
      <div class="prof_pic">
        <img class="prof" src="../assets/rayul-_M6gy9oHgII-unsplash.jpg" alt="">
      </div>
      <div class="section_text">
        <h1 class="title">Hi, I'm Hardy and I am a experienced graphic designer</h1>
        <p>Create designs that express your brand</p>
      </div>
    </section>
    <section class="services">
      <h1 style="text-align: center; margin-bottom: 30px;" class="title">Our Services</h1>
      <div class="services-list">
        <div class="sev-box"><h3>Posters</h3></div>
        <div class="sev-box"><h3>App Design</h3></div>
        <div class="sev-box"><h3>Products</h3></div>
      </div>
    </section>
  </main>
</template>

<style>

.services-list{
  display: flex;
  align-items: center;
  justify-content: center;
}

.sev-box{
  width: 100px;
  height: 500px;
  margin: 10px;
  border-radius: 50px;
  background: url(https://images.unsplash.com/photo-1511466431307-d603e868975c?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxzZWFyY2h8MjB8fHBvc3RlcnN8ZW58MHx8MHx8fDA%3D&auto=format&fit=crop&w=1200&q=60);
  background-size: cover;
  background-position: center;
  position: relative;
  transition: width 0.5s;
}

.sev-box:nth-child(2){
  background-image: url(https://images.unsplash.com/photo-1551650975-87deedd944c3?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxzZWFyY2h8NHx8YXBwJTIwZGVzaWdufGVufDB8fDB8fHww&auto=format&fit=crop&w=1200&q=60);
  background-size: cover;
  background-position: center;
}

.sev-box:nth-child(3){
  background-image: url(https://images.unsplash.com/photo-1611930022073-b7a4ba5fcccd?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=687&q=80);
  background-size: cover;
  background-position: center;
}

.sev-box h3{
  color: rgb(0, 0, 0);
  position: absolute;
  bottom: 0;
  left: 30px;
  opacity: 0;
  transition: bottom 0.5s, opacity 0.5s;
}

.sev-box:hover{
  width: 300px;
  cursor: pointer;
}

.sev-box:hover h3{
  opacity: 1;
  bottom: 25px;
} 



p{
  text-align: left;
  font-size: 30px;
  color: rgb(144, 144, 144);
}
.prof{
  border-radius: 300px;
}
</style>
