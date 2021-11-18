<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.bg-foot
    .titulo-principal.color-acento-botones(data-aos='flip-left')
      .titulo-principal__numero
        span 2
      h1 Sistemas de información ambiental   
    .row.mb-5
      .col-lg-7.slideInLeft
        p.mb-4.text-bold.text-green El sistema de información en Colombia denominado SIA, es el encargado de gestionar la información ambiental del país por medio de la integración de actores, procesos, políticas y tecnología, que gestiona información acerca del estado, el uso, aprovechamiento, sostenibilidad y vulnerabilidad del medio ambiente, para la educación y participación social con miras a la toma de decisiones que aporten hacia el desarrollo sostenible del país.
        .cajon.color-acento-botones.p-4.mb-4
          p.mb-0  El SIA tiene como objetivo identificar los ecosistemas, recursos naturales, o regiones que tienen alta prioridad en acciones de investigación, protección, recuperación o manejo sostenible. Este sistema está liderado por el Ministerio de Ambiente y Desarrollo Sostenible, en coordinación con los institutos de investigación ambiental 
            span.text-highlight <b>IDEAM, SINCHI, HUMBOLDT e INVEMAR</b>, 
            | las autoridades ambientales regionales, la comunidad académica y todos los usuarios y proveedores de la información ambiental.
        p.mb-3  Dentro de esta plataforma del sistema de información se pueden encontrar cifras y estadísticas ambientales de diferentes aspectos tales como:
      .col-lg-5.slideInRight
        figure
          img(src='@/assets/curso/t2-i1.jpg')

    .row.mb-5 
      .col-lg-6(data-aos='flip-left')
        ImagenInfografica.color-secundario.mb-5
          template(v-slot:imagen)
            figure
              img(src='@/assets/curso/t2-info1.svg', alt='paisaje natural con rios y cascadas')

          .tarjeta.color-acento-botones.p-3.shadow-box(x="24.5%" y="21.5%" numero="")
            p Aire
          .tarjeta.color-acento-botones.p-3.shadow-box(x="51.5%" y="4.5%" numero="")
            p Agua
          .tarjeta.color-acento-botones.p-3.shadow-box(x="76.5%" y="21%" numero="")
            p Biodiversidad
          .tarjeta.color-acento-botones.p-3.shadow-box(x="83%" y="88%" numero="")
            p Suelo           

      .col-lg-6(data-aos='flip-right')   
        ImagenInfografica.color-secundario.mb-5.customPoints
          template(v-slot:imagen)
            figure
              img(src='@/assets/curso/t2-info2.svg', alt='paisaje de ciudad edificios y autopistas')

          .tarjeta.color-acento-botones.p-3.shadow-box(x="11.5%" y="6%" numero="")
            p Capa de ozono
          .tarjeta.color-acento-botones.p-3.shadow-box(x="53%" y="6%" numero="")
            p Calidad urbana
          .tarjeta.color-acento-botones.p-3.shadow-box(x="87%" y="25.5%" numero="")
            p Residuos aprovechables
          .tarjeta.color-acento-botones.p-3.shadow-box(x="71%" y="88.5%" numero="")
            p Residuos orgánicos
          .tarjeta.color-acento-botones.p-3.shadow-box(x="15%" y="80%" numero="")
            p Cambio climático            

    .row.mb-5.justify-content-center 
      .col-lg-8
        .cajon.color-acento-contenido.p-4.mb-4(data-aos='flip-up')
          p.mb-0 En términos de información ambiental, este sistema es el más utilizado para la recolección, <b>debido a que está en constante actualización y se obtienen datos de todo el territorio nacional.</b>
























</template>

<script>
export default {
  name: 'Tema2',
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
