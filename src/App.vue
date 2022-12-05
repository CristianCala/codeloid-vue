<template>
  <div class="container">
    <div class="row">
      <div class="col-12">
        <h3>Interpolación de texto</h3>
      </div>
      <div class="bg-vue container text-center col-12">
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

<style scoped>
  .color-vue {
    color: #42b883;
  }
  .btn-vue {
    background-color: white;
    color: #42b883;
    border:#42b883 1px solid;
  }
  .btn-hover:hover {
    background-color: #42b883;
    color: #fff;
  }
</style>
