<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    .titulo-principal.color-acento-contenido(data-aos='flip-left')
      .titulo-principal__numero
        span 3
      h1 Proyectos, obras y actividades

    .row.mb-5.justify-content-center
      .col-lg-10
        .bloque-texto-g.color-primario.p-3.p-sm-4.p-md-5.slideInUp
          .bloque-texto-g__img(
            :style="{'background-image': `url(${require('@/assets/curso/t3-i1.jpg')})`}"
          )
          .bloque-texto-g__texto.p-4.shadow-box
            p.mb-0 Existen diferentes tipos de proyectos, obras y actividades que requieren de la elaboración de estudios ambientales que están sujetos en su mayoría a un proceso de licenciamiento ambiental; con el propósito de facilitar la elaboración de estos estudios se ha puesto a disposición del público un conjunto de calificaciones de Impactos Ambientales Potenciales (IAP) de tales proyectos, obras o actividades.

    .row.mb-5
      .col-lg-2
        figure
          img(src='@/assets/curso/t3-ic1.svg' alt='imagen decorativa')
      .col-lg-10
        p.mb-3  <b>El IAP mide la capacidad que tiene un proyecto, obra o actividad de producir impactos ambientales sobre el medio físico, biótico y socioeconómico de acuerdo con sus características intrínsecas,</b> siendo posible evaluarlo con base en actividades previas o que se encuentran en ejercicio, pues en la medida en que el IAP refleja los impactos característicos de cada tipo de proyecto, obra o actividad, puede ser empleado para estimar de forma preliminar del grado de modificación de las condiciones ambientales de un proyecto en particular.
        p.mb-3.text-bold  Teniendo en cuenta que se debe cumplir con una normatividad previamente establecida como lo son:

    p.mb-5  En este sentido, es necesario relacionar los recursos naturales que serán objeto de uso, aprovechamiento o afectación, como consecuencia de la realización de las actividades. Por esto, será necesario presentar la información que se requiere especificada a continuación:

    .neg-margin-x.bg-sliders2
      .row.justify-content-center
        .col-lg-8
          ImagenInfografica.color-secundario.mb-5
            template(v-slot:imagen)
              figure
                img(src='@/assets/curso/t3-info1.svg', alt='imagen decorativa')

            .tarjeta.color-acento-botones.p-3(x="0%" y="13%" numero="")
              .h5.mb-2 titulo
              p Trámites de autorizaciones

    p.mb-5  En este sentido, es necesario relacionar los recursos naturales que serán objeto de uso, aprovechamiento o afectación, como consecuencia de la realización de las actividades. Por esto, será necesario presentar la información que se requiere especificada a continuación:

































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
