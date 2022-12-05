<template>
    <div class="container mt-5">
        <h3 class="fw-bold">Interpolación de texto</h3>
        <p class="fw-bold">Renderizado de texto: 
            <span class="badge bg-dark">{{ mensage }}
            </span>
        </p>
        <p class="fw-bold">Renderizado de número: 
            <span class="badge bg-dark">{{ numero }}</span>
        </p>
    </div>
</template>
<script>
    export default {
        name: 'App',
        data() {
            return {
                mensage: 'Hola mundo con Vue.js',
                numero: 22
            }
        }
    };
</script>