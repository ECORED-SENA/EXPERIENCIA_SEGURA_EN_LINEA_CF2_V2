<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido(data-aos="flip-up")
      .titulo-principal__numero
        span 3
      h1 Delitos informáticos
    
    p.mb-5 Se definen como aquellos actos ilícitos en los que se usan las tecnologías de la información, como las computadoras, los programas informáticos, los medios electrónicos, internet, entre otros, como medio o como fin.

    #t3-1.titulo-segundo
      h2 3.1 Legislación actual

    p.mb-5 En Colombia, la legislación frente a los delitos informáticos, su tipificación y tipos de sanciones han tenido una evolución lenta en el tiempo, sin embargo, se ha legislado al respecto. A continuación, se realizará un resumen general de las leyes que marcaron el inicio y evolución de la legislación colombiana en esta temática:

    PasosAB.color-acento-contenido(tipo="n")
      div
        h3 Ley 527 de 1999:
        p por medio de la cual se define y reglamenta el acceso y uso de los mensajes de datos, del comercio electrónico y de las firmas digitales, y se establecen las entidades de certificación y se dictan otras disposiciones.
      div
        h3 Ley 599 de 2000:
        p el Código Penal Colombiano no habla explícitamente de delitos informáticos, sin embargo, algunos artículos protegen los bienes jurídicos de vulneraciones cometidas a través de la red informática.
      div
        h3 Ley 603 de 2000:
        p ley que ampara los derechos de autor, que protege la propiedad y producción intelectual.
      div
        h3 Ley 679 de 2001: 
        | entre otras cosas establece las normas atinentes para contrarrestar el abuso sexual de menores, a través de medios electrónicos.
      div
        h3 Ley 1266 de 2008:
        p ley de habeas data regula el manejo de la información contenida en bases de datos personales, en especial la financiera, crediticia, comercial, de servicios y la proveniente de terceros.
      div
        h3 Ley 1273 de 2009:
        p establece nuevos tipos penales relacionados con delitos informáticos y la protección de la información y de los datos.

    Separador

    #t3-2.titulo-segundo
      h2 3.2 Tipología, sanciones y penalizaciones de los delitos informáticos

    p.mb-5 Para hablar de la tipología y tipos de sanciones que actualmente están vigentes en Colombia, se debe tomar como referente la Ley 1273 de 2009, la cual está compuesta por dos capítulos. A continuación, se desglosan cada uno de ellos.

    h3 Capítulo 1
    p 
      b De los atentados contra la confidencialidad, la integridad y la disponibilidad de los datos y de los sistemas informáticos.

    AcordionA.mb-5(tipo="a" clase-tarjeta="tarjeta color-acento-contenido")
      div(titulo="Artículo 269A - Acceso abusivo a un sistema informático")
        p.mb-0 El que, sin autorización o por fuera de lo acordado, acceda en todo o en parte a un sistema informático protegido o no con una medida de seguridad, o se mantenga dentro del mismo en contra de la voluntad de quien tenga el legítimo derecho a excluirlo, incurrirá en pena de prisión de cuarenta y ocho (48) a noventa y seis (96) meses y en multa de 100 a 1.000 salarios mínimos legales mensuales vigentes.
      div(titulo="Artículo 269B - Obstaculización ilegítima de sistema informático o red de telecomunicación")
        p.mb-0 El que, sin estar facultado para ello, impida u obstaculice el funcionamiento o el acceso normal a un sistema informático, a los datos informáticos allí contenidos, o a una red de telecomunicaciones, incurrirá en pena de prisión de cuarenta y ocho (48) a noventa y seis (96) meses y en multa de 100 a 1000 salarios mínimos legales mensuales vigentes, siempre que la conducta no constituya delito sancionado con una pena mayor.
      div(titulo="Artículo 269C - Interceptación de datos informáticos")
        p.mb-0 El que, sin orden judicial previa intercepte datos informáticos en su origen, destino o en el interior de un sistema informático, o las emisiones electromagnéticas provenientes de un sistema informático que los transporte incurrirá en pena de prisión de treinta y seis (36) a setenta y dos (72) meses.
      div(titulo="Artículo 269D - Daño Informático")
        p.mb-0 El que, sin estar facultado para ello, destruya, dañe, borre, deteriore, altere o suprima datos informáticos, o un sistema de tratamiento de información o sus partes o componentes lógicos, incurrirá en pena de prisión de cuarenta y ocho (48) a noventa y seis (96) meses y en multa de 100 a 1.000 salarios mínimos legales mensuales vigentes.
      div(titulo="Artículo 269E - Uso de software malicioso")
        p.mb-0 El que, sin estar facultado para ello, produzca, trafique, adquiera, distribuya, venda, envíe, introduzca o extraiga del territorio nacional software malicioso u otros programas de computación de efectos dañinos, incurrirá en pena de prisión de cuarenta y ocho (48) a noventa y seis (96) meses y en multa de 100 a 1.000 salarios mínimos legales mensuales vigentes.
      div(titulo="Artículo 269F - Violación de datos personales")
        p.mb-0 El que, sin estar facultado para ello, con provecho propio o de un tercero, obtenga, compile, sustraiga, ofrezca, venda, intercambie, envíe, compre, intercepte, divulgue, modifique o emplee códigos personales, datos personales contenidos en ficheros, archivos, bases de datos o medios semejantes, incurrirá en pena de prisión de cuarenta y ocho (48) a noventa y seis (96) meses y en multa de 100 a 1000 salarios mínimos legales mensuales vigentes.
      div(titulo="Artículo 269G - Suplantación de sitios web para capturar datos personales")
        p El que con objeto ilícito y sin estar facultado para ello, diseñe, desarrolle, trafique, venda, ejecute, programe o envíe páginas electrónicas, enlaces o ventanas emergentes, incurrirá en pena de prisión de cuarenta y ocho (48) a noventa y seis (96) meses y en multa de 100 a 1.000 salarios mínimos legales mensuales vigentes, siempre que la conducta no constituya delito sancionado con pena más grave.
        p En la misma sanción incurrirá el que modifique el sistema de resolución de nombres de dominio, de tal manera que haga entrar al usuario a una IP diferente en la creencia de que acceda a su banco o a otro sitio personal o de confianza, siempre que la conducta no constituya delito sancionado con pena más grave.
        p.mb-0 La pena señalada en los dos incisos anteriores se agravará de una tercera parte a la mitad, si para consumarlo el agente ha reclutado víctimas en la cadena del delito.
      div(titulo="Artículo 269H - Circunstancias de agravación punitiva")
        p Las penas imponibles de acuerdo con los artículos descritos en este título, se aumentarán de la mitad a las tres cuartas partes si la conducta se cometiere:
        

        ul.lista-ul.mb-0.ps-4
          li 
            i.fas.fa-check
            | Sobre redes o sistemas informáticos o de comunicaciones estatales u oficiales o del sector financiero, nacionales o extranjeros.
          li 
            i.fas.fa-check
            | Por servidor público en ejercicio de sus funciones.
          li 
            i.fas.fa-check
            | Aprovechando la confianza depositada por el poseedor de la información o por quien tuviere un vínculo contractual con este.
          li 
            i.fas.fa-check
            | Revelando o dando a conocer el contenido de la información en perjuicio de otro.
          li 
            i.fas.fa-check
            | Obteniendo provecho para sí o para un tercero.
          li 
            i.fas.fa-check
            | Con fines terroristas o generando riesgo para la seguridad o defensa nacional.
          li 
            i.fas.fa-check
            | Utilizando como instrumento a un tercero de buena fe.
          li 
            i.fas.fa-check
            | Si quien incurre en estas conductas es el responsable de la administración, manejo o control de dicha información, además se le impondrá hasta por tres años, la pena de inhabilitación para el ejercicio de profesión relacionada con sistemas de información procesada con equipos computacionales.

    h3 Capítulo 2
    p 
      b De los atentados informáticos y otras infracciones

    AcordionA.mb-5(tipo="a" clase-tarjeta="tarjeta color-acento-contenido")
      div(titulo="Artículo 269I - Hurto por medios informáticos y semejantes")
        p.mb-0 El que, superando medidas de seguridad informáticas, realice la conducta señalada en el artículo 239 manipulando un sistema informático, una red de sistema electrónico, telemático u otro medio semejante, o suplantando a un usuario ante los sistemas de autenticación y de autorización establecidos, incurrirá en las penas señaladas en el artículo 240 de este Código.
      div(titulo="Artículo 269J - Transferencia no consentida de activos")
        p.mb-0 El que, con ánimo de lucro y valiéndose de alguna manipulación informática o artificio semejante, consiga la transferencia no consentida de cualquier activo en perjuicio de un tercero, siempre que la conducta no constituya delito sancionado con pena más grave, incurrirá en pena de prisión de cuarenta y ocho (48) a ciento veinte (120) meses y en multa de 200 a 1.500 salarios mínimos legales mensuales vigentes. La misma sanción se le impondrá a quien fabrique, introduzca, posea o facilite programa de computador destinado a la comisión del delito descrito en el inciso anterior, o de una estafa.

    p Ahora bien, si la conducta descrita en los dos incisos anteriores tuviere una cuantía superior a 200 salarios mínimos legales mensuales, la sanción allí señalada se incrementará en la mitad.

    p.mb-4
      b Para entender mejor los delitos informáticos observe el siguiente ejemplo: 

    SlyderA.con-fondo
      .s-contenedor
        .tarjeta.color-acento-botones.p-4.p-lg-5
          .row.align-items-center.justify-content-center
            .col-lg-8.mb-4.mb-lg-0
              p.mb-0
                b PEDRO MARTÍNEZ 
                | es un ingeniero de sistemas que se desempeña como administrador de la red en la empresa ABASTOS LTDA.
            .col-6.col-lg-4
              img.d-lg-none(src='@/assets/curso/t3-02.svg')
              img.d-none.d-lg-block(src='@/assets/curso/t3-02.svg' style="margin-top: -100px; margin-bottom: -100px")

      .s-contenedor
        .tarjeta.color-acento-botones.p-4.p-lg-5
          .row.align-items-center.justify-content-center
            .col-lg-8.mb-4.mb-lg-0
              p.mb-0 Este señor es amigo de 
                b ULISES PINTO 
                | quien fuera novio de 
                b MARTHA SÁNCHEZ 
                | funcionaria de la empresa.

            .col-6.col-lg-4
              img.d-lg-none(src='@/assets/curso/t3-03.svg')
              img.d-none.d-lg-block(src='@/assets/curso/t3-03.svg'  style="margin-top: -90px; margin-bottom: -90px")

      .s-contenedor
        .tarjeta.color-acento-botones.p-4.p-lg-5
          .row.align-items-center.justify-content-center
            .col-lg-6.mb-4.mb-lg-0
              p.mb-0 Un día cualquiera 
                b ULISES 
                | le dice a 
                b PEDRO 
                | que desea saber los números de teléfono y la dirección de 
                b MARTHA
                | , para lo cual 
                b PEDRO 
                | aprovechando su perfil, le entrega en una memoria USB dicha información, así mismo, le hace entrega de unas fotografías de la señora 
                b SÁNCHEZ 
                | que posteriormente son publicadas en internet. 
            .col-6
              img.d-lg-none(src='@/assets/curso/t3-04.svg')
              img.d-none.d-lg-block(src='@/assets/curso/t3-04.svg'  style="margin-top: -90px; margin-bottom: -90px")

      .s-contenedor
        .tarjeta.color-acento-botones.p-4.p-lg-5
          .row.align-items-center.justify-content-center
            .col-lg-6.mb-4.mb-lg-0
              h1 ¿Existe algún delito y cuál es la pena máxima?

            .col-6
              img.d-lg-none(src='@/assets/curso/t3-04.svg')
              img.d-none.d-lg-block(src='@/assets/curso/t3-04.svg'  style="margin-top: -90px; margin-bottom: -90px")

      .s-contenedor
        .tarjeta.color-acento-botones.p-4.p-lg-5
          .row.align-items-center.justify-content-center
            .col-6.col-lg-3.mb-4.mb-lg-0
              img(src='@/assets/curso/t3-05.svg')
            .col-lg-9
              p Según la Ley 1273 del 2009 los artículos que hacen parte del presente caso son:

              ul.lista-ul.mb-0
                li 
                  i.lista-ul__vineta
                  h4.mb-0(style="color: #004080") Artículo 269A.
                li 
                  i.lista-ul__vineta
                  h4.mb-0(style="color: #004080") Artículo 269F.
                li 
                  i.lista-ul__vineta
                  h4.mb-0(style="color: #004080") Artículo 269H.

      .s-contenedor
        .tarjeta.color-acento-botones.p-4.p-lg-5
          .row.align-items-center.justify-content-center
            .col-6.col-lg-2.mb-4.mb-lg-0
              img.d-lg-none(src='@/assets/curso/t3-06.svg')
              img.d-none.d-lg-block(src='@/assets/curso/t3-06.svg'  style="margin-top: -90px; margin-bottom: -90px")
            .col-6.d-lg-none.mb-4.mb-lg-0
              img.d-lg-none(src='@/assets/curso/t3-07.svg')
            .col-lg-7
              p.mb-0 Estos artículos son aplicados tanto para 
                b PEDRO 
                | como para 
                b ULISES
                | , puesto que ellos cometieron una conducta punible, de diferente agravación.
            .col-3.d-none.d-lg-block
              img(src='@/assets/curso/t3-07.svg' style="margin-top: -90px; margin-bottom: -90px")

      .s-contenedor
        .tarjeta.color-acento-botones.p-4.p-lg-5
          .row.align-items-center.justify-content-center
            .col-1.d-none.d-lg-block
              img(src='@/assets/curso/t3-08.svg' style="margin-top: -110px; margin-bottom: -90px")
            .col-lg-8.mb-4.mb-lg-0
              p.mb-0 Para 
                b PEDRO 
                | se tipifica el 
                b artículo 269A
                | , ya que este habla sobre el acceso abusivo a un sistema informático, porque pueda que él sea ingeniero de sistemas, pero su papel es administrador de la empresa y no debería estar utilizando su conocimiento en sacar información que no debe, para dársela a otra persona y mucho menos sin consentimiento del gerente o dueño de la empresa.
            .col-6.col-lg-3
              img.d-lg-none(src='@/assets/curso/t3-07.svg')
              img.d-none.d-lg-block(src='@/assets/curso/t3-07.svg'  style="margin-top: -110px; margin-bottom: -110px")

      .s-contenedor
        .tarjeta.color-acento-botones.p-4.p-lg-5
          .row.align-items-center.justify-content-center
            .col-4.col-lg-3
              img.d-lg-none(src='@/assets/curso/t3-06.svg')
              img.d-none.d-lg-block(src='@/assets/curso/t3-06.svg' style="margin-top: -90px; margin-bottom: -90px")
            .col-lg-9
              p.mb-0 Para 
                b ULISES 
                | se tipifica el 
                b articulo 269F
                | , ya que esta habla de la violación de datos personales, porque él, en vez de guardar esa información y datos de 
                b MARTHA
                |  para él solo, lo que hizo fue publicarlas, independientemente de las razones por las cuales lo hizo. 

      .s-contenedor
        .tarjeta.color-acento-botones.p-4.p-lg-5
          p El 
            b artículo 269H
            |, habla de las agravaciones que tienen cada una de sus acciones tanto de PEDRO como de ULISES, las cuales son:
          ul.lista-ul
            li 
              i.fas.fa-check
              p.mb-0
                b Tercera: 
                | aprovechando la confianza depositada por el poseedor de la información o por quien tuviere un vínculo contractual con este.
            li 
              i.fas.fa-check
              p.mb-0
                b Cuarta: 
                | revelando o dando a conocer el contenido de la información en perjuicio de otro.
            li 
              i.fas.fa-check
              p.mb-0
                b Octava: 
                | si quien incurre en estas conductas es el responsable de la administración, manejo o control de dicha información, además se le impondrá hasta tres años, la pena de inhabilitación para el ejercicio de profesión relacionada con sistemas de información procesada con equipos computacionales.

      .s-contenedor
        .tarjeta.color-acento-botones.p-4.p-lg-5
          .row.align-items-center.justify-content-center
            .col-3.col-lg-2.mb-4.mb-lg-0
              img.d-lg-none(src='@/assets/curso/t3-06.svg')
              img.d-none.d-lg-block(src='@/assets/curso/t3-06.svg' style="margin-bottom: -170px")
            .col-4.d-lg-none.mb-4.mb-lg-0
              img(src='@/assets/curso/t3-07.svg')
            .col-lg-7
              p La tercera y cuarta agravación la cumple ULISES y la octava agravación la cumple PEDRO. Con respecto a la pena, para PEDRO según la conducta que tuvo (artículo 269 A) es de 48 a 96 meses y según su agravación (artículo 269 H), esta pena se aumentará a la mitad o las tres cuartas (3/4) partes, por lo tanto, la pena la dictará el juez, dependiendo del aumento que le vaya a dar según los datos mencionados.
              p.mb-0 Para ULISES, según la conducta que tuvo (artículo 269 F) es de 48 a 96 meses y por su agravación (artículo 269 H), esta pena se aumentará la mitad o las tres cuartas (3/4) partes también.

            .col-3.d-none.d-lg-block
              img(src='@/assets/curso/t3-07.svg' style="margin-top: -170px")

      .s-contenedor
        .tarjeta.color-acento-botones.p-4.p-lg-5
          .row.align-items-center.justify-content-center
            .col-6.col-lg-3.mb-4.mb-lg-0
              img.d-lg-none(src='@/assets/curso/t3-10.svg')
              img.d-none.d-lg-block(src='@/assets/curso/t3-10.svg' style="margin-bottom: -54px")
            .col-lg-9
              p.mb-0 En conclusión, el juez debe determinar cuál fue de mayor agravación e implantarle a ese la pena aumentada a las tres cuartas (3/4) partes y al otro si aumentarle la mitad de la pena, según la importancia de conducta punible que tuvo. 
    
      
    


</template>

<script>
import PasosAB from '../components/PasosAB'
export default {
  name: 'Tema3',
  components: {
    PasosAB,
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
