<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    .titulo-principal.color-acento-contenido(data-aos='flip-left')
      .titulo-principal__numero
        span 1
      h1 Fuentes de información   
    .row.mb-5.justify-content-center
      .col-lg-10
        .bloque-texto-a.color-secundario.p-4.p-md-5.mb-5 
          .row.m-0.align-items-center.justify-content-between
            .col-lg-4.mb-4.mb-lg-0
              figure
                img(src='@/assets/curso/t1-ic1.svg')
            .col-lg-8
              .bloque-texto-a__texto.p-4.shadow-box
                p Se habla de fuentes de información o fuentes de documentación para referirse al origen de una información en particular, es decir, el apoyo en el cual se puede acudir para su recuperación. En este sentido, las referencias pueden ser de un tipo muy diferente y de esta forma, proporcionar datos más o menos confiables que serán cruciales y que influyen de manera decisiva en los resultados que se obtengan. Para ello, se cuenta con fuentes de información primaria, secundarias y terciarias que se pueden consultar en el siguiente recurso.






















































    //- El componente "Muestras" tiene las aplicaciones de todos los componentes de la base
    //- se encuentra en src/components/Muestras.vue
    //- Una vez el componente "Muestras" no se necesite 
    //- Se debe borrar el "import Muestras from '../components/Muestras'" y en "components" en "<script"
    //- esto evitará que se compile en la carpeta final de distribución
    Muestras
  
</template>

<script>
import Muestras from '../components/Muestras' // borrar una vez el componente "Muestras" no se necesite
export default {
  name: 'Tema1',
  components: {
    Muestras, // borrar una vez el componente "Muestras" no se necesite
  },
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
