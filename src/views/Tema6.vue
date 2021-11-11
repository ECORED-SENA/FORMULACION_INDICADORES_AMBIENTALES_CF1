<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.bg-foot
    .titulo-principal.color-acento-contenido(data-aos='flip-left')
      .titulo-principal__numero
        span 6
      h1 Diagramas de flujo

    .row.mb-5
      .col-lg-5
        figure.slideInUp
          img(src='@/assets/curso/t6-i1.jpg')
      .col-lg-7.slideInLeft
        p.mb-3.text-bold.text-green  Un diagrama de flujo es la representación gráfica de un proceso, el cual surge para tener una visión más amplia por medio de gráficos en los cuales se denotan los pasos que se deben seguir en un proceso.
        p.mb-3  La importancia radica en que <b>nos facilita la forma de simbolizar visualmente el flujo de datos de una información.</b> Estos diagramas, sus diferentes características y etapas, facilitan la comprensión de la temática de los impactos ambientales, de una manera sencilla, clara, resumida, pero a la vez dando una visión global del contenido y la ruta que debe seguir, en los diferentes procesos para realizar las mediciones de los impactos ambientales.
        .cajon-b.color-acento-botones.px-0.py-3.mb-5
          p.mb-0 Los diagramas de flujo están compuestos por símbolos y cada uno cumple con una función, como se muestra en la siguiente tabla:

    .row.mb-5.justify-content-center
      .col-lg-8
        figcaption.customCaption.mb-3 <b>Tabla</b> &nbsp;Simbología diagramas de flujo
        .tabla-b.color-secundario.mb-5  
          table
            thead
              tr
                th.text-center Función
                th.text-center Símbolo
            tbody
              tr
                td Inicio o final del diagrama
                td.b-left
                  figure
                    img.nW.centered(src='@/assets/curso/t6-s1.svg' alt='figura geometrica')
              tr
                td Realización de una actividad
                td.b-left
                  figure
                    img.nW.centered(src='@/assets/curso/t6-s3.svg' alt='figura geometrica')
              tr
                td Entrada/Salida
                td.b-left
                  figure
                    img.nW.centered(src='@/assets/curso/t6-s4.svg' alt='figura geometrica')
              tr
                td Análisis de situación y toma de decisión
                td.b-left
                  figure
                    img.nW.centered(src='@/assets/curso/t6-s5.svg' alt='figura geometrica')
              tr
                td Documentación (generación, consulta, etc)
                td.b-left
                  figure
                    img.nW.centered(src='@/assets/curso/t6-s7.svg' alt='figura geometrica')
              tr
                td Bases de datos
                td.b-left
                  figure
                    img.nW.centered(src='@/assets/curso/t6-s8.svg' alt='figura geometrica')
              tr
                td Conector fuera de página
                td.b-left
                  figure
                    img.nW.centered(src='@/assets/curso/t6-s9.svg' alt='figura geometrica')
              tr
                td Preparación
                td.b-left
                  figure
                    img.nW.centered(src='@/assets/curso/t6-s10.svg' alt='figura geometrica')
              tr
                td Conector
                td.b-left
                  figure
                    img.nW.centered(src='@/assets/curso/t6-s11.svg' alt='figura geometrica')
              tr
                td Conector
                td.b-left
                  figure
                    img.nW.centered(src='@/assets/curso/t6-s12.svg' alt='figura geometrica')



    p.mb-5.text-bold  Y pueden ser:

    TabsC.color-primario.mb-5
      .py-3.py-md-4(titulo="Horizontal")
        .row.justify-content-center
          .col-md-12.mb-4.mb-md-0
            p Estos diagramas están orientados de derecha a izquierda según el orden de lectura establecido.
          .col-md-10
            figure
              img(src='@/assets/curso/t6-t1.svg', alt='ejemplo de diagrama horizontal')
      .py-3.py-md-4(titulo="Vertical")
        .row.justify-content-center
          .col-md-12.mb-4.mb-md-0
            p Se encuentran secuenciados de arriba hacia abajo, como un listado ordenado. 
          .col-md-6
            figure
              img(src='@/assets/curso/t6-t2.svg', alt='ejemplo de diagrama vertical')
      .py-3.py-md-4(titulo="Panorámico")
        .row.justify-content-center
          .col-md-12.mb-4.mb-md-0
            p Son aquellos que permiten tener una visualización total den contenido en una sola hoja, usando los dos modelos previamente descritos.
          .col-md-6
            figure
              img(src='@/assets/curso/t6-t3.svg', alt='ejemplo de diagrama Panorámico')

    p.mb-5.text-bold Los diagramas de flujo tienen tres características principales:

    .row.mb-5.justify-content-center
      .col-sm-6.col-xl-4.mb-4.mb-xl-0
        .tarjeta.tarjeta-flip.color-acento-botones(@mouseover="indicadorTarjetaFlip = false")
          .indicador--hover(v-if="indicadorTarjetaFlip")
          .tarjeta-flip__contenedor
            .tarjeta-flip__img(:style="{'background-image': `url(${require('@/assets/curso/t6-c1.svg')})`}")
            .tarjeta-flip__contenido.p-4.p-xl-5.text-center
              .h2 Sintética
              p Es una representación de un sistema de manera resumida.
              
      .col-sm-6.col-xl-4.mb-4.mb-xl-0
        .tarjeta.tarjeta-flip.color-acento-botones(@mouseover="indicadorTarjetaFlip = false")
          .indicador--hover(v-if="indicadorTarjetaFlip")
          .tarjeta-flip__contenedor
            .tarjeta-flip__img(:style="{'background-image': `url(${require('@/assets/curso/t6-c2.svg')})`}")
            .tarjeta-flip__contenido.p-4.p-xl-5.text-center
              .h2 Simbolizada
              p.mb-3 Aplica la simbología respectiva de los diagramas de flujo.

      .col-sm-6.col-xl-4.mb-4.mb-xl-0
        .tarjeta.tarjeta-flip.color-acento-botones(@mouseover="indicadorTarjetaFlip = false")
          .indicador--hover(v-if="indicadorTarjetaFlip")
          .tarjeta-flip__contenedor
            .tarjeta-flip__img(:style="{'background-image': `url(${require('@/assets/curso/t6-c3.svg')})`}")
            .tarjeta-flip__contenido.p-4.p-xl-5.text-center
              .h2 De forma visible a un sistema o un proceso
              p Los diagramas deben permitir todos los pasos de un proceso de manera clara.


    p.mb-5.text-bold  Y las siguientes funciones:
    
    .row.mb-5.justify-content-center
      .col-lg-4
        .tarjeta.c1.p-5.text-center
          figure
            img.nW.centered(src='@/assets/curso/t6-ch1.svg' alt='figura geometrica')
          p.mb-3  El poder entender un proceso al mostrarlo como un dibujo.
      .col-lg-4
        .tarjeta.c1.p-5.text-center
          figure
            img.nW.centered(src='@/assets/curso/t6-ch2.svg' alt='figura geometrica')
          p.mb-3  Permitir identificar los problemas y oportunidades de mejora del proceso.






















</template>

<script>
export default {
  name: 'Tema3',
  data: () => ({
    mostrarIndicador: true,
    indicadorImagenZoom: true,
    indicadorTarjetaFlip: true,
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
