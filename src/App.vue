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
  <div class="messaggio" @click="saluta">
    {{ message }}
  </div>
  <!-- <HelloWorld msg="Vite + Vue" /> -->
</template>

<style scoped>

.messaggio {
  color: blue;
  font-size: 50px;
}
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>
