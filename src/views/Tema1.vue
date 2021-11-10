<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    .titulo-principal.color-acento-botones(data-aos='flip-left')
      .titulo-principal__numero
        span 1
      h1 Fuentes de información   
    .row.mb-5.justify-content-center
      .col-lg-10
        .bloque-texto-a.color-secundario.p-4.p-md-5.mb-5 
          .row.m-0.align-items-center.justify-content-between
            .col-lg-4.mb-4.mb-lg-0
              figure
                img.nW.centered(src='@/assets/curso/t1-ic1.png')
            .col-lg-8
              .bloque-texto-a__texto.p-4.shadow-box
                p Se habla de fuentes de información o fuentes de documentación para referirse al origen de una información en particular, es decir, el apoyo en el cual se puede acudir para su recuperación. En este sentido, las referencias pueden ser de un tipo muy diferente y de esta forma, proporcionar datos más o menos confiables que serán cruciales y que influyen de manera decisiva en los resultados que se obtengan. Para ello, se cuenta con fuentes de información primaria, secundarias y terciarias que se pueden consultar en el siguiente recurso.

    .tarjeta.bg-sliders.p-4.mb-5
      SlyderA
        .p-4
          .row
            .col-md-6.mb-4.mb-md-0
              .h4 Fuentes de información primaria
              p.mb-3  Contienen información original que ha sido publicada por primera vez y que no ha sido filtrada, interpretada o evaluada por nadie más. Son producto de una investigación o de una actividad creativa y componen la colección básica de una biblioteca y pueden encontrarse en soporte impreso o digital.
              p.mb-3  Entre los tipos más comunes se encuentran: libros, revistas científicas y de entretenimiento, periódicos, diarios, documentos oficiales de instituciones públicas, informes técnicos y de investigación de instituciones públicas o privadas, patentes, normas técnicas.        
            .col-md-6
              figure.slideInLeft
                img(src='@/assets/curso/t1-i1.png', alt='imagen decorativa')
        .p-4
          .row
            .col-md-6.mb-4.mb-md-0
              .h4 Fuentes de información secundaria
              p.mb-3  Contienen información primaria, sintetizada y reorganizada. Están diseñadas para facilitar y maximizar el acceso a las fuentes primarias o a sus contenidos. Se utilizan cuando no se tiene acceso a la fuente primaria por una razón específica, cuando los recursos son limitados y cuando la fuente no es confiable.
              p.mb-3  Entre los tipos más comunes se encuentran: enciclopedias, antologías, directorios, libros o artículos que interpretan otros trabajos o investigaciones. 
            .col-md-6
              figure.slideInLeft
                img(src='@/assets/curso/t1-i2.png', alt='imagen decorativa')
        .p-4
          .row
            .col-md-6.mb-4.mb-md-0
              .h4 Fuentes de información terciaria
              p.mb-3  Son guías físicas o virtuales que contienen información sobre las fuentes secundarias y forman parte de la colección de referencia de una biblioteca, además facilitan el control y acceso a toda la gama de repertorios de referencia. 
              p.mb-3  Entre los tipos más comunes se pueden encontrar: resúmenes, almanaques, bibliografías, cronologías, diccionarios y enciclopedias, directorios, libros de hechos y manuales.
            .col-md-6
              figure.slideInLeft
                img(src='@/assets/curso/t1-i3.png', alt='imagen decorativa')



















































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
