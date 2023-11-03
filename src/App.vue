<script>
// import HelloWorld from './components/HelloWorld.vue'

export default {
  data() {
    return {
      message: 'La mia prima app con Vite!'
    }
  },

  methods: {
    saluta() {
      console.log('ciao Vite!')
    }
  }
}
</script>

<template>
  <div class="container">

    <div class="messaggio">
      {{ message }}
    </div>
    <figure>
      <img src="../img/apple wallpaper.png " alt="">
    </figure>
  </div>
</template>

<style scoped>
.container {
  width: 800px;
  height: 700px;
  overflow: hidden;
  background-image: cover;
}

.messaggio {
  color: white;
  font-size: 50px;
  margin: 20px auto;
}

img {
  max-width: 100%;
  /* margin-left: auto;
  margin-right: auto; */

}
</style>
