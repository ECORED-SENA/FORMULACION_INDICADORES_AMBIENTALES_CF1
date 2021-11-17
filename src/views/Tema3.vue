<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.bg-foot
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

    .neg-margin-x.bg-sliders2
      .row.justify-content-center
        .col-lg-8
          ImagenInfografica.color-secundario.mb-5
            template(v-slot:imagen)
              figure
                img(src='@/assets/curso/t3-info1.svg', alt='imagen decorativa')

            .tarjeta.color-acento-botones.p-3.shadow-box(x="0%" y="13%" numero="")
              p.mb-0 Trámites de autorizaciones.
            .tarjeta.color-acento-botones.p-3.shadow-box(x="100%" y="13%" numero="")
              p.mb-0 Concesiones.
            .tarjeta.color-acento-botones.p-3.shadow-box(x="0%" y="80%" numero="")
              p.mb-0 Permisos necesarios para la realización de un proyecto.
            .tarjeta.color-acento-botones.p-3.shadow-box(x="100%" y="80%" numero="")
              p.mb-0 Oferta y demanda de recursos naturales que serán empleados en dichos proyectos.

    p.mb-5  En este sentido, es necesario relacionar los recursos naturales que serán objeto de uso, aprovechamiento o afectación, como consecuencia de la realización de las actividades. Por esto, será necesario presentar la información que se requiere especificada a continuación:
    .row.mb-5.justify-content-center
      .col-lg-10
        AcordionA.mb-5(tipo="a" clase-tarjeta="tarjeta soft-yellow")
          .row(titulo="Concesión de aguas superficiales")
            .col-md-6
              figure.slideInLeft
                img(src='@/assets/curso/t3-t1.svg', alt='imagen decorativa')
            .col-md-6.mb-4.mb-md-0
              p.mb-3 <b>Oferta:</b> se debe presentar los caudales de los cuerpos de agua que serán intervenidos en el proyecto.
              p.mb-3 <b>Demanda:</b> es necesario realizar un inventario que denote cuales son los usuarios que se verán afectados o beneficiados al ser utilizado este cuerpo de agua.    
              p.mb-3 Se requiere presentar los diseños de captación y conducción de los cuerpos de agua a intervenir.
              p.mb-3 Ubicación de los cuerpos de agua a utilizar por el proyecto.             

          .row(titulo="Uso de aguas subterráneas")
            .col-md-6
              figure.slideInLeft
                img(src='@/assets/curso/t3-t2.png', alt='imagen decorativa')
            .col-md-6.mb-4.mb-md-0
              ul.lista-ul
                li
                  i.fas.fa-check
                  p.mb-0  Particularidades hidrogeológicas de la zona de estudio. 
                li
                  i.fas.fa-check
                  p.mb-0  Se debe presentar un inventario detallado de pozos y manantiales que existan dentro del área de afectación. 
                li
                  i.fas.fa-check
                  p.mb-0  Evaluación geoeléctrica de los sitios de perforación.
                li
                  i.fas.fa-check
                  p.mb-0  Ubicación de los sitios de perforación.
                li
                  i.fas.fa-check
                  p.mb-0  Especificaciones del equipo de perforación a emplear.


          .row(titulo="Permiso de vertimientos")
            .col-md-6
              figure.slideInLeft
                img(src='@/assets/curso/t3-t3.png', alt='imagen decorativa')
            .col-md-6.mb-4.mb-md-0
              ul.lista-ul
                li
                  i.fas.fa-check
                  p.mb-0  Se debe realizar una descripción teórica de las sustancias contaminantes de acuerdo con la normatividad vigente.
                li
                  i.fas.fa-check
                  p.mb-0  Los caudales y volúmenes estimados de efluentes.
                li
                  i.fas.fa-check
                  p.mb-0  Es necesario el inventario de uso de aguas y vertimientos en la zona de donde se van a disponer.
                li
                  i.fas.fa-check
                  p.mb-0  Listado de posibles impactos ambientales dentro del cuerpo de agua receptor.

          .row(titulo="Ocupación de causes")
            .col-md-6
              figure.slideInLeft
                img(src='@/assets/curso/t3-t4.png', alt='imagen decorativa')
            .col-md-6.mb-4.mb-md-0
              ul.lista-ul
                li
                  i.fas.fa-check
                  p.mb-0  Inventario de las obras  a construir junto con su duración en el tiempo.
                li
                  i.fas.fa-check
                  p.mb-0  Un reconocimiento básico del comportamiento del cuerpo de agua en los sectores afectables.
                li
                  i.fas.fa-check
                  p.mb-0  Impactos ambientales previsibles.
                li
                  i.fas.fa-check
                  p.mb-0  Inventario de obras típicas de protección y de control torrencial.
                li
                  i.fas.fa-check
                  p.mb-0  Procedimientos de construcción.  
                li
                  i.fas.fa-check
                  p.mb-0  Listado de impactos producidos por dicha actividad. 


          .row(titulo="Aprovechamiento forestal")
            .col-md-6
              figure.slideInLeft
                img(src='@/assets/curso/t3-t5.png', alt='imagen decorativa')
            .col-md-6.mb-4.mb-md-0
              ul.lista-ul
                li
                  i.fas.fa-check
                  p.mb-0  Es necesario establecer cuál es la necesidad técnica del aprovechamiento forestal.
                li
                  i.fas.fa-check
                  p.mb-0  Se debe presentar el plano de ubicación con coordenadas geográficas de las áreas que han sido solicitadas para aprovechamiento.
                li
                  i.fas.fa-check
                  p.mb-0  Debe presentar el régimen de propiedad de las áreas que se aprovechan.
                li
                  i.fas.fa-check
                  p.mb-0  Se requiere las áreas que se aprovecharán, igualmente que la taxonomía de especies allí ubicadas.
                li
                  i.fas.fa-check
                  p.mb-0  Se deben indicar los proyectos compensatorios tales como protección, conservación y repoblación forestal.

          .row(titulo="Disposición de residuos sólidos")
            .col-md-6
              figure.slideInLeft
                img(src='@/assets/curso/t3-t6.png', alt='imagen decorativa')
            .col-md-6.mb-4.mb-md-0
              ul.lista-ul
                li
                  i.fas.fa-check
                  p.mb-0  Es necesario la clasificación de los residuos sólidos.
                li
                  i.fas.fa-check
                  p.mb-0  Se debe presentar el estimativo de volúmenes de residuos.
                li
                  i.fas.fa-check
                  p.mb-0  Listado de los impactos ambientales que puede traer consigo el proyecto.
                li
                  i.fas.fa-check
                  p.mb-0  Una matriz con las opciones de tratamiento, manejo y disposición.
                li
                  i.fas.fa-check
                  p.mb-0  Ubicación en planos de los sitios de manejo y disposición.

          .row(titulo="Emisiones atmosféricas")
            .col-md-6
              figure.slideInLeft
                img(src='@/assets/curso/t3-t7.png', alt='imagen decorativa')
            .col-md-6.mb-4.mb-md-0
              ul.lista-ul
                li
                  i.fas.fa-check
                  p.mb-0  Se debe presentar un cronograma con las fechas proyectada de iniciación y terminación del proyecto. 
                li
                  i.fas.fa-check
                  p.mb-0  Es necesario describir las actividades de mantenimiento, tratamiento y disposición.  
                li
                  i.fas.fa-check
                  p.mb-0  Realizar el estudio técnico de evaluación de las emisiones atmosféricas.  
                li
                  i.fas.fa-check
                  p.mb-0  Es necesario realizar el diseño de los sistemas de control de emisiones atmosféricas.










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
