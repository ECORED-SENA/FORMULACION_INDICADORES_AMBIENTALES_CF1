<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    .titulo-principal.color-acento-contenido(data-aos='flip-left')
      .titulo-principal__numero
        span 5
      h1 Evaluación ambiental

    .row.mb-5
      .col-lg-7.slideInLeft
        p.mb-4.text-bold.text-green La evaluación ambiental tiene como objetivo la verificación de los parámetros y normativas que actualmente se encuentran vigentes para conocer el estado de los componentes del entorno, lo cual facilita planificar acciones a tomar con el fin de mantener o mejorar las condiciones del medio ambiente.
        .cajon.color-acento-botones.p-4.mb-4
          p.mb-0   La evaluación, al ser uno de los pasos fundamentales en el impacto ambiental, requiere conocer el proceso que se debe realizar, sobre todo al situarlo desde el manejo y utilización de <b>la matriz Leopold</b>.
        p.mb-3  En la década de 1970, el Dr. Med. Luna Leopold y algunos colaboradores desarrollaron proyectos de construcción con influencia, enfoque y contenido particularmente útiles, para la evaluación preliminar de estos proyectos que predicen un gran impacto ambiental. La forma de usar la matriz de Leopold se puede resumir en los siguientes pasos:
      .col-lg-5.slideInRight
        figure
          img(src='@/assets/curso/t5-i1.jpg')

    .row.mb-5.justify-content-center
      .col-lg-8(data-aos='flip-left')
        PasosA.color-acento-botones.mb-5(tipo="l")
          .row.align-items-center
            .col-md-2.mb-4.mb-md-0
              figure
                img.nW(src='@/assets/curso/t5-ic1.svg', alt='icono decorativo')
            .col-md-10
              p Limite la esfera de atribución.

          .row.align-items-center
            .col-md-10.mb-4.mb-md-0
              p Determine las acciones que ejerce el proyecto en el área.
            .col-md-2
              figure
                img.nW(src='@/assets/curso/t5-ic2.svg', alt='Texto que describa la imagen')
          .row.align-items-center
            .col-md-2.mb-4.mb-md-0
              figure
                img.nW(src='@/assets/curso/t5-ic3.svg', alt='icono decorativo')
            .col-md-10
              p Determine para cada acción los elementos se ven afectados.

          .row.align-items-center
            .col-md-10.mb-4.mb-md-0
              p Determine el significado de cada elemento en una escala de 1 a 10.
            .col-md-2
              figure
                img.nW(src='@/assets/curso/t5-ic4.svg', alt='Texto que describa la imagen')

          .row.align-items-center
            .col-md-2.mb-4.mb-md-0
              figure
                img.nW(src='@/assets/curso/t5-ic5.svg', alt='icono decorativo')
            .col-md-10
              p Determine el tamaño de cada acción en cada elemento en una escala de 1 a 10.

          .row.align-items-center
            .col-md-10.mb-4.mb-md-0
              p Determine si el tamaño es positivo o negativo.
            .col-md-2
              figure
                img.nW(src='@/assets/curso/t5-ic6.svg', alt='Texto que describa la imagen')

          .row.align-items-center
            .col-md-2.mb-4.mb-md-0
              figure
                img.nW(src='@/assets/curso/t5-ic7.svg', alt='icono decorativo')
            .col-md-10
              p Determine cuántas medidas de proyecto influyen en el medio ambiente, en la desagregación positiva y negativa.

          .row.align-items-center
            .col-md-10.mb-4.mb-md-0
              p Se deben añadir los resultados de las acciones. 
            .col-md-2
              figure
                img.nW(src='@/assets/curso/t5-ic8.svg', alt='Texto que describa la imagen')

          .row.align-items-center
            .col-md-2.mb-4.mb-md-0
              figure
                img.nW(src='@/assets/curso/t5-ic9.svg', alt='icono decorativo')
            .col-md-10
              p Determine cuántos factores ambientales se ven afectados por el proyecto que se adoptan en positivos y negativos.

          .row.align-items-center
            .col-md-10.mb-4.mb-md-0
              p Agregue resultados de los elementos del medio ambiente.
            .col-md-2
              figure
                img.nW(src='@/assets/curso/t5-ic10.svg', alt='Texto que describa la imagen')

    .row.mb-5
      .col-lg-2
        figure(data-aos='flip-left')
          img.nW(src='@/assets/curso/t5-ic11.svg', alt='Texto que describa la imagen')
      .col-lg-10(data-aos='slide-left')
        p.mb-3  De acuerdo con lo anterior, es necesario identificar, clasificar y valorar los impactos ambientales generados en cada uno de los procesos de la organización, con el fin de poder determinar las medidas correctivas o preventivas necesarias para la mitigación de estos impactos y así poder generar un proceso sostenible con el medio ambiente en el que se afecte en la menor proporción. 
        p.mb-3  Los proyectos o actividades que deben ser sometidas al <b>Sistema de Evaluación de Impacto Ambiental</b>, son los siguientes:

    .row.mb-5
      .col-lg-4
        figure(data-aos='slide-left')
          img.nW(src='@/assets/curso/t5-ic12.jpg', alt='Texto que describa la imagen')
      .col-lg-8  
        ul.lista-ul(data-aos='slide-right')
          li
            i.fas.fa-check
            p.mb-0  Acueductos, presas, drenajes, o aquellas actividades que alteren los cuerpos naturales de agua.
          li
            i.fas.fa-check
            p.mb-0  Líneas de transmisión de energía de alto voltaje.
          li
            i.fas.fa-check
            p.mb-0  Centrales generadoras de energía mayores a 3 MW.  
          li
            i.fas.fa-check
            p.mb-0  Reactores y establecimientos nucleares.  
          li
            i.fas.fa-check
            p.mb-0  Aeropuertos, terminales de buses, automotores, vías férreas, estaciones de servicio y autopistas.              
          li
            i.fas.fa-check
            p.mb-0  Puertos, vías de navegación, astilleros y terminales marítimas.  
          li
            i.fas.fa-check
            p.mb-0  Proyectos de turismo y desarrollo urbano. 
          li
            i.fas.fa-check
            p.mb-0  Proyectos industriales o inmobiliarios que se ejecuten en zonas declaradas latentes o saturadas. 
          li
            i.fas.fa-check
            p.mb-0  Proyectos de desarrollo minero, incluidos los de carbón, petróleo y gas. 
          li
            i.fas.fa-check
            p.mb-0  Oleoductos, gasoductos, ductos mineros u otros análogos. 
          li
            i.fas.fa-check
            p.mb-0  Ejecución de obras, programas o actividades en parques nacionales, reservas nacionales y santuarios de la naturaleza. 
          li
            i.fas.fa-check
            p.mb-0  Agroindustrias, planteles y establos de crianza, lechería y engorda de animales. 
          li
            i.fas.fa-check
            p.mb-0  Proyectos de desarrollo o explotación forestal en suelos de bosques nativos. 
          li
            i.fas.fa-check
            p.mb-0  Proyectos de explotación intensiva o de cultivos que utilicen el recurso hidrológico. 
          li
            i.fas.fa-check
            p.mb-0  Proyectos de saneamiento ambiental.
          li
            i.fas.fa-check
            p.mb-0  Proyectos donde se apliquen productos químicos de manera masiva. 
          li
            i.fas.fa-check
            p.mb-0  Proyectos de desarrollo, cultivo o explotación, en las áreas mineras, agrícolas y forestales. 



















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
