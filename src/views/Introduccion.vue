<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido(data-aos="flip-up")
      .titulo-principal__numero
        span
          i.fas.fa-info
      h1 Introducción

    .row.justify-content-center.justify-content-md-between.align-items-center
      .col-md-8.mb-4.mb-md-0
        h5 ¿Qué se debe hacer para enfrentar un riesgo digital?
        p Es una pregunta muy común entre las personas. Lo primero que debe tener presente es que no está solo, existen múltiples herramientas en las que tendrá apoyo, tanto en la generación de protección como en la conciencia de que todo depende del buen uso que se les dé a los dispositivos y servicios en red, y eso es lo que se aprenderá en este componente formativo.
        p
          b Se explicarán conceptos que debemos tener presentes y conocer a la perfección qué es la identidad digital para así saber dónde dejar la huella.
        p.mb-0
          b ¡Bienvenido!
      .col-6.col-md-3
        img(src='@/assets/curso/intro.svg')

    
</template>

<script>
export default {
  name: 'Introduccion',
  data: () => ({
    // variables de vue
  }),
}
</script>
<style lang="sass">
.escudo
  @media (min-width: $bp-min-xl)
    position: absolute
    bottom: 0
    transform: translateY(30%)
</style>
