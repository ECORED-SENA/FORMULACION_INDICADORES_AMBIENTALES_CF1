<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
  
    .titulo-principal
      .titulo-principal__numero
        span
          i.fas.fa-info
      h1 Introducción

    .row.mb-5.justify-content-center
      .col-lg-10
        .bloque-texto-g.color-primario.p-3.p-sm-4.p-md-5.custom-cardBlock.slideInUp
          .bloque-texto-g__texto.p-4.shadow-box
            p.mb-0 La formulación de indicadores ambientales requiere de conocimientos básicos de factores ambientales con el fin de apropiar los conceptos de medición y aplicabilidad. A continuación podrá identificar elementos básicos del proceso de introducción. Lo invitamos a ver el siguiente video para conocer más sobre la temática a estudiar.

          .bloque-texto-g__img(
            :style="{'background-image': `url(${require('@/assets/curso/t0-i1.jpg')})`}"
          )
            

    figure.mb-5
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/2L91WMqw96A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
      figcaption Video: Leyenda del video
    

</template>

<script>
export default {
  name: 'Introduccion',
  data: () => ({
    // variables de vue
  }),
}
</script>

<style lang="sass"></style>
