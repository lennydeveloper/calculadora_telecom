<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png" v-bind:style="{height: '40px', width: '40px'}">
    <Conversiones msg="Conversión de Unidades"/>
  </div>
</template>

<script>
// @ is an alias to /src
import Conversiones from '@/components/Conversiones.vue'

export default {
  name: 'HomeView',
  components: {
    Conversiones
  }
}
</script>
