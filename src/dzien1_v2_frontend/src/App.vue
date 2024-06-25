<template>
  <main>
    <img src="/logo2.svg" alt="DFINITY logo" />
    <br />
    <br />
    hej blockchain!
    {{ licznik }}
    <button @click="podbij">Podbij</button>
  </main>
</template>

<script>
export default {
  data() {
    return {
      licznik: 0
    }
  },
  methods: {
    podbij() {
      this.licznik++
    }
  }
}
</script>