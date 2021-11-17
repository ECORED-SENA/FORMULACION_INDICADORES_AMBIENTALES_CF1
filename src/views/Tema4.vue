<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.bg-foot
    .titulo-principal.color-acento-contenido(data-aos='flip-left')
      .titulo-principal__numero
        span 4
      h1 Aspectos e impactos ambientales

    p.mb-5.slideInUp  A continuación conoceremos qué son los aspectos ambientales y los impactos ambientales, estableciendo así la diferencia entre estos dos términos.

    #t_4_1.titulo-segundo.color-secundario
      h2  4.1 Aspectos ambientales
    .row.mb-5
      .col-lg-3
        figure.slideInLeft
          img(src='@/assets/curso/t4-i1.svg', alt='imagen decorativa')
      .col-lg-9.slideInRight
        p.mb-3  Para empresas que están orientadas hacia un futuro de sostenibilidad y sustentabilidad, no solo económica sino también ambiental, es esencial comprender cómo se está viendo afectado el medio ambiente en cada uno de los procesos que realiza la organización y la manera de hacerlo es por medio de una <b>identificación de aspectos e impactos ambientales los cuales determinarán las medidas necesarias para la mitigación de estos.</b>
        p.mb-3  Es necesario entender que <b>un aspecto ambiental es un elemento de actividades, productos o servicios de alguna actividad que puede interactuar de manera positiva o negativa con el medio ambiente.</b> Algunos ejemplos de los aspectos ambientales son entre otros:

    //-- Aqui vienen los cards

    p.mb-5  En el siguiente recurso se detallan estos aspectos.
    figure.mb-5
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/2L91WMqw96A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)

    h3.titulo-tercero
      i.fas.fa-leaf
      | &nbsp;Clasificación de los aspectos ambientales
    p.mb-5  La importancia del aspecto ambiental depende en gran medida del funcionamiento de la organización y su ubicación.
    p.mb-5  Para ello, <b>existen dos categorías distintas de aspectos ambientales:</b>

    .row.mb-5.justify-content-center
      .col-sm-6.col-xl-4.mb-4.mb-xl-0
        .tarjeta.tarjeta-flip.color-secundario(@mouseover="indicadorTarjetaFlip = false")
          .indicador--hover(v-if="indicadorTarjetaFlip")
          .tarjeta-flip__contenedor.h-100
            .tarjeta-flip__img(:style="{'background-image': `url(${require('@/assets/curso/t4-c1.png')})`}")
            .tarjeta-flip__contenido.p-4.p-xl-5.text-center
              .h2 Significativos
              br
              p.mb-5 Es un elemento de las actividades, productos o servicios de una empresa que tiene o puede tener un impacto sobre el medio ambiente.
      .col-sm-6.col-xl-4.mb-4.mb-xl-0
        .tarjeta.tarjeta-flip.color-secundario(@mouseover="indicadorTarjetaFlip = false")
          .indicador--hover(v-if="indicadorTarjetaFlip")
          .tarjeta-flip__contenedor.h-100
            .tarjeta-flip__img(:style="{'background-image': `url(${require('@/assets/curso/t4-c2.png')})`}")
            .tarjeta-flip__contenido.p-4.p-xl-5.text-center
              .h2 No significativos
              br
              p.mb-5 Los asociados al producto fabricado, buscando reducir al máximo el ciclo de vida de este.

    .row.mb-5.justify-content-center
      .col-lg-8
        .cajon.color-acento-contenido.p-4(data-aos='flip-up')
          p.mb-0  Tenga en cuenta que los no significativos corresponden a los impactos que son lo suficientemente notables como para marcar una gran diferencia en el medio ambiente.

    h3.titulo-tercero
      i.fas.fa-leaf
      | &nbsp;Identificación de los aspectos ambientales
    .row.mb-5
      .col-lg-2
        figure.slideInLeft
          img(src='@/assets/curso/t4-ic1.svg', alt='imagen decorativa')
      .col-lg-10
        p.mb-3  La identificación de los aspectos ambientales, permite conocer cuáles son las situaciones en las que las actividades, productos y servicios pueden afectar al medio ambiente y de esta manera, poder conocer qué tipos de impactos son susceptibles de generarse y con ello, hacer la evaluación dentro del sistema de gestión ambiental de la organización.



    Separador
    br
    br
    #t_4_2.titulo-segundo.color-secundario
      h2  4.2 Impactos ambientales
    .row.mb-5.justify-content-center
      .col-lg-10
        .bloque-texto-g.color-primario.p-3.p-sm-4.p-md-5.slideInUp
          .bloque-texto-g__img(
            :style="{'background-image': `url(${require('@/assets/curso/t4-i2.jpg')})`}"
          )
          .bloque-texto-g__texto.p-4.shadow-box
            p.mb-0 Los impactos ambientales son todas aquellas alteraciones que son generadas por el ser humano al medio ambiente ya sea de manera directa o indirecta por un proyecto, acción, obra o labor en un área determinada. Toda actividad que pueda causar un impacto ambiental en alguna de sus fases estará obligada a someterse al sistema de evaluación de impacto ambiental para determinar con claridad la magnitud de estos impactos.

    .row.mb-5
      .col-lg-2
        figure(data-aos='flip-left')
          img(src='@/assets/curso/t4-ic2.svg', alt='imagen decorativa')
      .col-lg-10
        p.mb-3  Por medio de la identificación de impactos ambientales se busca hacer una evaluación y valoración de los efectos presentes como resultado de las actividades, productos o servicios en una organización, así como, se pretende mediante la evaluación, poder hallar soluciones para prevenir, mitigar o controlar dichos impactos.
        p.mb-3  Los impactos ambientales se pueden establecer de acuerdo con los siguientes tipos:

    TabsB.color-acento-contenido.mb-5
      .py-4.py-md-5(titulo="El aprovechamiento de recursos naturales" :icono="require('@/assets/curso/t4-ico1.svg')")
        .row.justify-content-center
          .col-md-4
            figure.slideInLeft
              img(src='@/assets/curso/t4-i3.jpg', alt='imagen decorativa')     
          .col-md-6.mb-4.mb-md-0
            h4 El aprovechamiento de recursos naturales
            p Estos recursos pueden ser utilizados para el aprovechamiento forestal cuando son renovables, cuando no son renovables son utilizados en extracción como lo es el petróleo o el carbón.
      
      .py-4.py-md-5(titulo="Contaminación" :icono="require('@/assets/curso/t4-ico2.svg')")
        .row.justify-content-center
          .col-md-4
            figure.slideInLeft
              img(src='@/assets/curso/t4-i4.jpg', alt='imagen decorativa')     
          .col-md-6.mb-4.mb-md-0
            h4 Contaminación
            p Acá se relacionan aquellos proyectos que dentro de su funcionamiento emitan gases a la atmósfera o que contaminen cuerpos de agua con vertimientos.

      .py-4.py-md-5(titulo="Ocupación del territorio" :icono="require('@/assets/curso/t4-ico3.svg')")
        .row.justify-content-center
          .col-md-4
            figure.slideInLeft
              img(src='@/assets/curso/t4-i5.jpg', alt='imagen decorativa')     
          .col-md-6.mb-4.mb-md-0
            h4 Ocupación del territorio
            p Son aquellos proyectos que modifican las condiciones biológicas de un territorio ya sea por acciones de uso de tierras para extracción u otro tipo de acciones donde se vean afectadas las áreas determinadas.  

    h3.titulo-tercero
      i.fas.fa-leaf
      | &nbsp;Clasificación de los impactos ambientales
    p.mb-5  Dentro de los impactos ambientales, se encuentran distintas clasificaciones de acuerdo con sus propiedades; veamos los más representativos en el siguiente recurso:

    .row.mb-5.justify-content-center
      .col-xs-5.col-sm-8.col-md-6.col-lg-3.col-xl-3
        .nav-holder.align-items-center(data-aos="flip-left")
          img(src="@/assets/curso/t6-n1.png", alt="Imagen decorativa")
          .text.p-lg-3.p-4
            .row.px-lg-3.mb-lg-2
              p.h3 Positivo o negativo
              p.small De acuerdo a los efectos resultantes sobre el medio ambiente. 
      .col-xs-5.col-sm-8.col-md-6.col-lg-3.col-xl-3
        .nav-holder.align-items-center(data-aos="flip-left")
          img(src="@/assets/curso/t6-n2.png", alt="Imagen decorativa")
          .text.p-lg-3.p-4
            .row.px-lg-3.mb-lg-2
              p.h3 Directo o indirecto
              p.small Esto se da cuando el impacto es producido por una acción específica del proyecto. 
          .indicador--click(v-if="mostrarIndicador")
      .col-xs-8.col-sm-8.col-md-6.col-lg-3.col-xl-3
        .nav-holder.align-items-center(data-aos="flip-left")
          img(src="@/assets/curso/t6-n3.png", alt="Imagen decorativa")
          .text.p-lg-3.p-4
            .row.px-lg-3.mb-lg-2
              p.h3 Acumulativo
              p.small Este es el resultado de la adición de impactos ambientales que ocurrieron previamente y que aún están pasando actualmente. 
      .col-xs-8.col-sm-8.col-md-6.col-lg-3.col-xl-3
        .nav-holder.align-items-center(data-aos="flip-left")
          img(src="@/assets/curso/t6-n4.png", alt="Imagen decorativa")
          .text.p-lg-3.p-4
            .row.px-lg-3.mb-lg-2
              p.h3 Sinérgico
              p.small Se produce cuando la aglomeración de impactos tiene una incidencia mayor que cuando se suman individualmente. 
              
      .col-xs-8.col-sm-8.col-md-6.col-lg-3.col-xl-3
        .nav-holder.align-items-center(data-aos="flip-left")
          img(src="@/assets/curso/t6-n5.png", alt="Imagen decorativa")
          .text.p-lg-3.p-4
            .row.px-lg-3.mb-lg-2
              p.h3 Residual
              p.small Es aquel que persiste después de la implementación de medidas de mitigación.
              
      .col-xs-8.col-sm-8.col-md-6.col-lg-3.col-xl-3
        .nav-holder.align-items-center(data-aos="flip-left")
          img(src="@/assets/curso/t6-n6.png", alt="Imagen decorativa")
          .text.p-lg-3.p-4
            .row.px-lg-3.mb-lg-2
              p.h3 Temporal o permanente
              p.small Cuando son por un período de tiempo determinado.
      .col-xs-8.col-sm-8.col-md-6.col-lg-3.col-xl-3
        .nav-holder.align-items-center(data-aos="flip-left")
          img(src="@/assets/curso/t6-n7.png", alt="Imagen decorativa")
          .text.p-lg-3.p-4
            .row.px-lg-3.mb-lg-2
              p.h3 Reversible o irreversible
              p.small Estos dependen de qué tan factible es retornar a las condiciones originarias. 
      .col-xs-8.col-sm-8.col-md-6.col-lg-3.col-xl-3
        .nav-holder.align-items-center(data-aos="flip-left")
          img(src="@/assets/curso/t6-n8.png", alt="Imagen decorativa")
          .text.p-lg-3.p-4
            .row.px-lg-3.mb-lg-2
              p.h3 Continuo o periódico
              p.small Dependerá del período en que se exteriorice.


    h3.titulo-tercero
      i.fas.fa-leaf
      | &nbsp;Identificación de los impactos ambientales    
    p.mb-5  Para identificar los impactos ambientales es necesario conocer primero los aspectos ambientales dentro de su organización, tanto de las actividades, productos o servicios y cómo estos afectan el medio ambiente. A continuación, se relacionan algunas variables que se deben tener como factor contaminante.
    .tarjeta.soft-yellow2.p-4.mb-5
      LineaTiempoC.color-acento-contenido(text-small)
        .row.justify-content-center(titulo="Atmósfera")
          .col-md-4
            figure
              img(src='@/assets/curso/t4-m1.png', alt='imagen decorativa')        
          .col-md-6.mb-4.mb-md-0
            .h4 Atmósfera
            .h5 Factor contaminante:
            p.mb-3 Los factores contaminantes pueden ser gases, lluvia ácida, aerosoles o ruido.
            .h5 Identificación: 
            p.mb-3 Se identifican por medio de:
            ul.lista-ul
              li
                i.fas.fa-check
                p.mb-0 Los índices de calidad de aire.        
              li
                i.fas.fa-check
                p.mb-0  Emisiones de CO2.

        .row.justify-content-center(titulo="Ruido")
          .col-md-4
            figure
              img(src='@/assets/curso/t4-m2.png', alt='imagen decorativa')        
          .col-md-6.mb-4.mb-md-0
            .h4 Ruido
            .h5 Factor contaminante:
            p.mb-3 Son todos aquellos sonidos indeseables o que exceden los decibeles permitidos.
            .h5 Identificación: 
            ul.lista-ul
              li
                i.fas.fa-check
                p.mb-0 Nivel de presión acústica.
              li
                i.fas.fa-check
                p.mb-0  Decibelímetro.

        .row.justify-content-center(titulo="Agua")
          .col-md-4
            figure
              img(src='@/assets/curso/t4-m3.png', alt='imagen decorativa')        
          .col-md-6.mb-4.mb-md-0
            .h4 Agua
            .h5 Factor contaminante:
            p.mb-3 Son aquellos provenientes de acciones industriales o contaminantes orgánicos.
            .h5 Identificación: 
            ul.lista-ul
              li
                i.fas.fa-check
                p.mb-0 Índice de calidad de aguas.
              li
                i.fas.fa-check
                p.mb-0  pH.
              li
                i.fas.fa-check
                p.mb-0  Oxígeno disuelto.
              li
                i.fas.fa-check
                p.mb-0  Coliformes
        .row.justify-content-center(titulo="Suelos")
          .col-md-4
            figure
              img(src='@/assets/curso/t4-m4.png', alt='imagen decorativa')        
          .col-md-6.mb-4.mb-md-0
            .h4 Capacidad de los suelos
            .h5 Factor contaminante:
            ul.lista-ul
              li
                i.fas.fa-check
                p.mb-0  Erosión.
              li
                i.fas.fa-check
                p.mb-0  Inundación.  
              li
                i.fas.fa-check
                p.mb-0  Pérdida de capacidad de los suelos.
              li
                i.fas.fa-check
                p.mb-0  Cambios topográficos.                
                                         
            .h5 Identificación: 
            ul.lista-ul
              li
                i.fas.fa-check
                p.mb-0 % cubierta vegetal
              li
                i.fas.fa-check
                p.mb-0  % pedregosidad.
              li
                i.fas.fa-check
                p.mb-0  Producción agraria.


        .row.justify-content-center(titulo="Paisaje")
          .col-md-4
            figure
              img(src='@/assets/curso/t4-m5.png', alt='imagen decorativa')        
          .col-md-6.mb-4.mb-md-0
            .h4 Paisaje
            .h5 Factor contaminante:
            p.mb-3 Estos factores pueden verse determinados por la variación de vegetación, junto con la aridez del terreno o los cambios en el uso del suelo.
            .h5 Identificación: 
            ul.lista-ul
              li
                i.fas.fa-check
                p.mb-0 Método de valoración directa subjetiva.
              li
                i.fas.fa-check
                p.mb-0  Valoración indirecta.

        .row.justify-content-center(titulo="Fauna")
          .col-md-4
            figure
              img(src='@/assets/curso/t4-m6.png', alt='imagen decorativa')        
          .col-md-6.mb-4.mb-md-0
            .h4 Fauna
            .h5 Factor contaminante:
            p.mb-3 La pérdida de hábitat por contaminantes, por incendios, inundaciones o remoción en masa. 
            .h5 Identificación: 
            p.mb-3  Estará determinado por la abundancia de especies y sus diferentes variedades.

        .row.justify-content-center(titulo="Vegetación")
          .col-md-4
            figure
              img(src='@/assets/curso/t4-m7.png', alt='imagen decorativa')        
          .col-md-6.mb-4.mb-md-0
            .h4 Vegetación
            .h5 Factor contaminante:
            p.mb-3 Se puede dar por incendios, inundaciones o remoción en masa lo cual lleva a una pérdida de la cubierta vegetal.
            .h5 Identificación: 
            p.mb-3  Se deberán identificar especies endémicas, autóctonas y la diversidad entre ellas. 
                              

    p.mb-5  En el impacto ambiental existen una serie de pasos fundamentales para tener en cuenta en el proceso de identificación, como lo son:
    .row.mb-5.justify-content-center
      .col-lg-8
        PasosA.color-acento-botones.mb-5(tipo="n")
          .row.align-items-center
            .col-md-2.mb-4.mb-md-0
              figure
                img.nW(src='@/assets/curso/t4-p1.svg', alt='icono decorativo')
            .col-md-10
              p Afirmación de los objetivos puntuales del proyecto.

          .row.align-items-center
            .col-md-10.mb-4.mb-md-0
              p Se debe realizar un análisis de las posibilidades expertas para desempeñar el objetivo.
            .col-md-2
              figure
                img.nW(src='@/assets/curso/t4-p2.svg', alt='icono decorativo')
          .row.align-items-center
            .col-md-2.mb-4.mb-md-0
              figure
                img.nW(src='@/assets/curso/t4-p3.svg', alt='icono decorativo')
            .col-md-10
              p Declaración de las acciones propuestas, las cuales incluyen alternativas de posibles impactos ambientales.

          .row.align-items-center
            .col-md-10.mb-4.mb-md-0
              p Caracterización de las condiciones del medio ambiente previo al inicio del proyecto.
            .col-md-2
              figure
                img.nW(src='@/assets/curso/t4-p4.svg', alt='icono decorativo')
          .row.align-items-center
            .col-md-2.mb-4.mb-md-0
              figure
                img.nW(src='@/assets/curso/t4-p5.svg', alt='icono decorativo')
            .col-md-10
              p Se debe contar con un análisis de costos y beneficios.

          .row.align-items-center
            .col-md-10.mb-4.mb-md-0
              p Es necesario realizar el análisis de los impactos ambientales que estén relacionados con las acciones planteadas.
            .col-md-2
              figure
                img.nW(src='@/assets/curso/t4-p6.svg', alt='icono decorativo')

          .row.align-items-center
            .col-md-2.mb-4.mb-md-0
              figure
                img.nW(src='@/assets/curso/t4-p7.svg', alt='icono decorativo')
            .col-md-10
              p Se deben evaluar los impactos de las acciones que previamente se proponen y sus afectaciones al medio ambiente.

          .row.align-items-center
            .col-md-10.mb-4.mb-md-0
              p Resumen y recomendaciones.
            .col-md-2
              figure
                img.nW(src='@/assets/curso/t4-p8.svg', alt='icono decorativo')

























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
