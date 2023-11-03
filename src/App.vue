<script>
// import HelloWorld from './components/HelloWorld.vue'
export default {
  data() {
    return {
      message: 'La mia prima app con Vite!'
    }
  },
  methods: {
    sayHi() {
      console.log('Hi!')
    }
  }
}
</script>

<template>
  <div @click="sayHi">
    <h1 class="title">
      {{ message }}
    </h1>
  </div>
</template>

<style scoped>
.title {
  color: yellowgreen;
}
</style>
