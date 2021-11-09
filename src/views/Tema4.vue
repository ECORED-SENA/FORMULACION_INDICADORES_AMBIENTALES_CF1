<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    .titulo-principal.color-acento-contenido(data-aos='flip-left')
      .titulo-principal__numero
        span 4
      h1 Aspectos e impactos ambientales

    #t_4_1.titulo-segundo.color-secundario
      h2  4.1 Aspectos ambientales


    #t_4_2.titulo-segundo.color-secundario
      h2  4.2 Impactos ambientales



































</template>

<script>
export default {
  name: 'Tema3',
  data: () => ({
    // variables de vue
  }),
  mounted() {
    this.$nextTick(() => {
      this.$aosRefresh()
    })
  },
  updated() {
    this.$aosRefresh()
  },
}
</script>

<style lang="sass"></style>
