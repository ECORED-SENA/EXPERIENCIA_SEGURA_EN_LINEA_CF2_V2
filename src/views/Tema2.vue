<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido(data-aos="flip-up")
      .titulo-principal__numero
        span 2
      h1 Huella digital
    
    .pb-5.pt-4

    .tarjeta.color-acento-contenido.position-relative.p-5.mb-5
      img.pregunta(src='@/assets/curso/t1-02.svg')
      .row.align-items-center.justify-content-center
        .col-md-9.mb-4.mb-md-0
          h3.mb-0 ¿Sabía que la huella digital puede ser vista desde dos frentes?
        .col-6.col-md-3
          img.overflow-img(src='@/assets/curso/t2-01.svg')

    .pb-5.d-none.d-lg-block

    .row.justify-content-center.mb-5
      .col-xxl-9
        .row.justify-content-center
          .col-lg-6.mb-4.mb-lg-0
            .tarjeta.color-gradient.h-100.p-5
              .d-flex.justify-content-center.mb-4
                .numero-container
                  span 1
              p.mb-0 El primero corresponde a los rastros y huellas de identidad que un usuario deja al utilizar internet o dispositivos digitales.

          .col
            .tarjeta.color-gradient.h-100.p-5
              .d-flex.justify-content-center.mb-4
                .numero-container
                  span 2
              p.mb-0 El segundo está relacionado con la utilización de la huella dactilar en dispositivos de autenticación y verificación de identidad. 

    h5.mb-4 Para ampliar la información, lo invitamos a consultar el siguiente video.

    figure.mb-5
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/ZEOgJDBWkXg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)

    p Cuando se utiliza internet y los diferentes medios y dispositivos digitales, se comparte información sobre gustos, preferencias, datos personales, incluso la posición geográfica de las personas, y toda esta información puede ser usada para construir una imagen del perfil de la persona con actividades e intereses. Es importante pensar, entonces, en quién puede ver esa información, incluso si se tiene una buena configuración de privacidad, se puede copiar el contenido y transmitirlo para el mundo en general.

    p.mb-5 Por este motivo, se debe pensar muy bien antes de publicar opiniones, intereses, gustos, posiciones religiosas o políticas, porque una vez publicadas se pierde el control sobre este contenido y puede ser copiado o multiplicado de manera exponencial e incluso generar reacciones inoportunas.

    h3 Huella dactilar

    p.mb-5 Ahora, las huellas dactilares son una marca única con un patrón específico para cada persona. 

    .bloque-texto-a.color-primario.p-4.p-md-5.mb-5 
      .row.m-0.align-items-center.justify-content-center
        .col-6.col-lg-3.mb-4.mb-lg-0
          img(src='@/assets/curso/t2-02.svg')
        .col-lg-9
          .bloque-texto-a__texto.px-4.py-5
            p Según Interpol (s.f.): “No hay dos personas con las mismas huellas dactilares; ni siquiera los gemelos homocigóticos. Las huellas dactilares no cambian nunca, ni con la edad, a menos que la capa profunda o basal se destruya o se modifique intencionadamente por medio de cirugía plástica”.

    h4.mb-5 Todo esto indica que cada una de las huellas de los dedos y pies es única e irrepetible.

    p.mb-5 Este patrón único permite relacionar una serie de datos asociados a una persona como son:

    .pb-5.pt-3

    .tarjeta.color-secundario--claro-2.p-5
      img.huellas.mb-4.d-none.d-lg-block(src='@/assets/curso/t2-huellas.svg')
      img.huellas.mb-4.d-lg-none(src='@/assets/curso/t2-03.svg')

      ul.lista-ul.mb-0
        li 
          i.lista-ul__vineta
          h4.mb-0(style="color: #004080") El nombre.
        li 
          i.lista-ul__vineta
          h4.mb-0(style="color: #004080") La identificación.
        li 
          i.lista-ul__vineta
          h4.mb-0(style="color: #004080") La fecha de nacimiento, entre otros. 

    Separador

    #t2-1.titulo-segundo
      h2 2.1 Importancia de la huella digital

    p Para efectos de este curso, se enfatizará en el estudio de la huella digital como el rastro que se construye al hacer uso de Internet y de sus diferentes herramientas o dispositivos digitales.
      
    p.mb-5 
      b Es importante entender que dependiendo del uso que se hace de:

    .row.align-items-end.mb-5
      .col-md-6
        .tarjeta.color-gradient-b.p-3.mb-3
          .row.align-items-center
            .col-2
              img(src='@/assets/curso/t2-05.svg')
            .col
              h5.mb-0 Las herramientas tecnológicas e Internet

        .tarjeta.color-gradient-b.p-3.mb-3
          .row.align-items-center
            .col-2
              img(src='@/assets/curso/t2-06.svg')
            .col
              h5.mb-0 Tipo de búsquedas

        .tarjeta.color-gradient-b.p-3.mb-3
          .row.align-items-center
            .col-2
              img(src='@/assets/curso/t2-07.svg')
            .col
              h5.mb-0 Publicaciones

        .tarjeta.color-gradient-b.p-3.mb-3
          .row.align-items-center
            .col-2
              img(src='@/assets/curso/t2-08.svg')
            .col
              h5.mb-0 Compras

        .tarjeta.color-gradient-b.p-3
          .row.align-items-center
            .col-2
              img(src='@/assets/curso/t2-09.svg')
            .col
              h5.mb-0 Tipos de consumo

      .col-md-6
        img(src='@/assets/curso/inicio.png')

    p
      b Se va a ir construyendo una huella digital que contendrá los datos sobre todas las actividades antes planteadas.

    p.mb-5 Igualmente, cuando se realiza algún tipo de comentario o publicaciones en algunas plataformas tecnológicas como:

    .cajon.color-secundario.p-5.mb-5
      ul.lista-ul.mb-0
        li 
          i.fas.fa-check
          | Blogs.
        li 
          i.fas.fa-check
          | Webs y redes sociales.
        li 
          i.fas.fa-check
          | Uso de aplicaciones.
        li 
          i.fas.fa-check
          | Registros de correo electrónico.
        li 
          i.fas.fa-check
          | Compras.
        li.mb-0
          i.fas.fa-check
          | Consumo de plataformas de entretenimiento, entre otras. 

    p Esta es información que forma parte del historial en línea de una persona y, potencialmente, puede ser vista, compartida o comentada por otras personas o incluso ser almacenada en una base de datos, por lo que es importante tener presente que, de una forma u otra, <b>todo lo que se hace queda grabado</b>.

    p.mb-5
      b De acuerdo con lo anterior:


    .bloque-texto-a.color-primario.p-4.p-md-5.mb-5 
      .row.m-0.align-items-center.justify-content-center
        .col-6.col-lg-3.mb-4.mb-lg-0
          img(src='@/assets/curso/t2-02.svg')
        .col-lg-9
          .bloque-texto-a__texto.px-4.py-5
            p Es prácticamente imposible borrar la huella digital, porque así se borre una publicación o un comentario, siempre existe la posibilidad de que haya sido compartido, almacenado o registrado.

    .row.justify-content-center.align-items-end
      .col-5.col-md-3
        h4.mb-5(style="color: #0077EC") Después de lo estudiado, surge esta pregunta: 

      .col-5.col-md-3
        img(src='@/assets/curso/t2-12.svg')

      .col-3.d-none.d-md-block

    .row.justify-content-center.mb-5
      .col-md-8
        .tarjeta.color-acento-botones.p-5
          h2.d-block.text-center.mb-0 ¿Y por qué es importante la construcción de la huella digital?

    p.mb-0 La importancia de construir una muy buena huella digital radica, entre otras cosas, que en la actualidad las empresas de selección de talento humano acuden a las redes sociales y en general a internet para investigar e identificar comportamientos y posiciones de posibles candidatos que se presentan o que son requeridos en el mundo laboral.

    Separador

    #t2-2.titulo-segundo
      h2 2.2 Identidad digital

    p Como se ha mencionado, la huella digital permite con el tiempo y de acuerdo con las acciones, construir la identidad digital, que se trata de un “yo” en la red, que determina los datos que cada persona va dejando en la red, a partir del consumo de productos, servicios y publicaciones. La identidad digital determina qué ven los demás usuarios en términos de uso de recursos tecnológicos, en los que se reconocen los perfiles, aunque se puede dar que en muchos casos la identidad digital obedezca a un seudónimo.

    p.mb-5
      b Algunas de las amenazas que afectan la identidad digital, como parte de la utilización de Internet y los recursos tecnológicos, son:

    .row.align-items-end.justify-content-center
      .col-lg-6
        AcordionA(tipo="a" clase-tarjeta="tarjeta color-acento-contenido")
          div(titulo="Robo de identidad")
            p.mb-0 Esta es una de las amenazas con mayor riesgo, cuando no se hace bien el uso de la tecnología en cuanto a la seguridad y protección de las cuentas se  puede afectar la información personal y sensible y puede ser utilizada para realizar fraudes y engaños a nombre de la persona que es suplantada.
          div(titulo="Fraudes")
            p.mb-0 Se puede producir de diferentes maneras, aunque la más común es cuando hay suficiente información personal sin proteger en las redes o servicios digitales y esta es utilizada por terceros para suplantar y contactar a familiares y amigos con la excusa de que se les presentó algún inconveniente, con esta acción se aprovechan para solicitarles dinero o algún otro elemento de valor a nombre del vulnerado.
          div(titulo="Perfiles falsos")
            p.mb-0 Se da cuando se aprovechan las publicaciones, datos y fotos para crear perfiles falsos con los datos específicos de una persona y, de esta manera, generar fraudes mediante el contacto a familiares y amigos en búsqueda de dinero o favores e inclusive se puede llegar a dañar la reputación de la persona.
          div(titulo="Fuga de datos")
            p.mb-0 Se puede presentar cuando la información sensible o muy personal es utilizada por terceros para dañar la imagen o prestigio de una persona o entidad, incluso en algunos casos se pueden presentar extorsiones con fines económicos.
          div(titulo="Fines publicitarios")
            p.mb-0 Se presenta cuando los registros y huella digital es utilizada para el envío de publicidad y oferta de bienes y servicios que muchas veces no se ha autorizado, este mecanismo es muy común en las redes sociales debido a su modelo de negocio.
          div(titulo="Utilización de derechos de propiedad no consentida")
            p.mb-0 Se da cuando se utilizan los datos personales e información sin el debido consentimiento o aceptación de una política de protección de datos personales o consentimiento que permita su utilización, esta acción es jurídicamente tratable según la ley colombiana.
          div(titulo="Rastreo secreto")
            p.mb-0 Los posibles empleadores en la actualidad buscan rastrear las publicaciones en redes sociales y cualquier otra interacción o actividades que realizan los posibles empleados para obtener información referente a su vida personal. Dependiendo del tipo de publicaciones de su vida “privada”, se toma una decisión.
      .col-6.col-lg-6.pb-3
        .row.justify-content-center
          .col-10
            img(src='@/assets/curso/t2-13.svg')
    
      
          
      
</template>

<script>
export default {
  name: 'Tema2',
  components: {},
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
