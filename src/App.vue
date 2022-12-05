<template>
  <div class="container">
    <div class="bg-vue container text-center mt-5">
      <button
        class="btn btn-hover btn-vue"
        v-on:click="conteo++"
      >
        Contar
      </button>
      <br>
      Me has presionado <span class="badge bg-dark">{{conteo}}</span> veces
    </div>
  </div>
</template>

<script>
export default {
  name: 'App',
  data() {
    return {
      conteo: 0
    }
  }
};
</script>