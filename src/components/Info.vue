<script>
export default {
  name: "Info",
  data() {
    return {
      title: "Manz Component Vue",
      version: "3.0"
    }
  },
  methods: {
    welcome() {
      alert("Hello");
    }
  }
}
</script>

<template>
  <div class="container">
    <h2>Títular del componente de Vue</h2>
    <h3>{{ title }} {{ version }}</h3>
    <strong>Placeholder</strong>
  </div>
</template>

<style>
.container {
  background: #318c58;
  color: #fff;
  padding: 1rem 3rem;
}
</style>
