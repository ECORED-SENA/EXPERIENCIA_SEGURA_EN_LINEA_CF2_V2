<template lang="pug">
#app.app
  Header
  .contenedor-principal
    AsideMenu
    section.seccion-principal(:class="{'seccion-principal--barra-avance-open' : !menuState}")
      router-view
  BarraAvance
  Accesibilidad
</template>

<script>
export default {
  name: 'App',
  data: () => ({
    menuOpen: false,
  }),
  computed: {
    menuState() {
      return this.$store.getters.isMenuOpen
    },
  },
  mounted() {
    this.$aos.init({
      offset: 100,
    })
  },
}
</script>
<style lang="sass">
.banner-interno
  height: 160px
.banner-interno__fondo
  background-image: url(assets/curso/fondo_tema.png) !important
.banner-principal .tarjeta
  background-position: inherit !important
.titulo-principal__numero
  background-color: #004080 !important
.curso-main-container > .container
  overflow: clip !important
.titulo-segundo:after
  border-left-color: #004080 !important
.banner-principal .tarjeta
  background-color: transparent !important
.titulo-principal.color-acento-contenido .titulo-principal__numero span
  color: #fff !important
.banner-principal-decorativo-1
  animation: float1 2s ease-in-out infinite alternate !important
  top: 65% !important
  right: 75% !important
.banner-principal-decorativo-2
  animation: float1 3s ease-in-out infinite alternate !important
  top: 20% !important
  right: 78% !important
.banner-principal-decorativo-3
  animation: float1 3s ease-in-out infinite alternate !important
  top: 30% !important
  right: 7% !important
.titulo-principal.color-acento-contenido .titulo-principal__numero
  background-color: #004080 !important
.banner-principal__row .banner-principal__img
  padding-bottom: 0rem !important
.banner-principal__row .banner-principal__img img
  max-width: 450px
  margin: 0 auto
.banner-principal .tarjeta
  background-size: 100% 100% !important
.banner-principal p, .banner-principal h1, .banner-principal h2, .banner-principal h3, .banner-principal h4, .banner-principal h5, .banner-principal h6
  color: #12263F !important
.titulo-principal__numero span, .titulo-principal__numero i
  color: #fff !important
@media screen and (max-width: 992px)
  .banner-principal .tarjeta
    background-size: cover !important
</style>
