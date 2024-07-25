<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido(data-aos="flip-up")
      .titulo-principal__numero
        span 1
      h1 Herramientas y estrategias de protección
    
    
    p.mb-5 Se denomina herramientas de protección a todas las herramientas que nacen para cubrir las necesidades de seguridad digital en este caso; son aquellas que presentan un alivio en el uso de los contenidos digitales y se caracterizan por ser de carácter pago o gratuito, según se establezca por parte de cada fabricante.

    #t1-1.titulo-segundo
      h2 1.1 Clasificación y características de las herramientas de protección

    .pb-5

    .tarjeta.color-acento-contenido.position-relative.p-5.mb-5
      img.pregunta(src='@/assets/curso/t1-02.svg')
      .row.align-items-center.justify-content-center
        .col-md-8.mb-4.mb-md-0
          h3.mb-0 ¿Sabía que las herramientas y estrategias de protección son tan variables y distintas como las diferentes herramientas digitales y tecnológicas que se pueden usar?
        .col-6.col-md-4
          img.overflow-img(src='@/assets/curso/t1-01.svg')

    .pb-5.d-none.d-lg-block

    .row.justify-content-center.mb-5
      .col-xxl-9
        .tarjeta.color-secundario.p-3.mb-4
          h4.text-center.mb-0 Su número es tan extenso que se clasifican en dos grandes áreas:
        .row.justify-content-center
          .col-lg-6.mb-4.mb-lg-0
            .tarjeta.color-gradient.h-100.p-5
              .d-flex.justify-content-center.mb-4
                .numero-container
                  span 1
              h3.mb-4 Las que trabajan a nivel de usuario
              p.mb-0 Son las herramientas que se requieren para la protección personal y las buenas prácticas de seguridad, con contenidos digitales para aplicativos personales como redes sociales.

          .col
            .tarjeta.color-gradient.h-100.p-5
              .d-flex.justify-content-center.mb-4
                .numero-container
                  span 2
              h3.mb-4 Las que trabajan a nivel técnico o empresarial
              p.mb-0 Obedecen más a políticas institucionales tendientes a la protección de los recursos tecnológicos corporativos, dentro de los cuales se integran todos los datos que deben protegerse por parte de los usuarios o empleados de las diferentes organizaciones en sus diferentes roles. 

    h3.text-center.mb-4 Gráficamente se puede explicar así:
    .titulo-sexto.color-acento-contenido
      h5 Figura 1.
      span Herramientas de protección
    .row.justify-content-center.mb-5
      .col-xl-11.m-auto.col-md-7
        figure.d-none.d-lg-block
          img(src='@/assets/curso/1.svg' alt="Imagen que presenta para qué son las herramientas de protección personales y empresariales.")
        figure.d-lg-none
          img(src='@/assets/curso/2.svg' alt="Imagen que presenta para qué son las herramientas de protección personales y empresariales.")

    .row.justify-content-center
      .col-lg-12.mb-4
        .tarjeta.color-gradient.h-100
          .p-4.p-lg-5
            p.text-center.mb-4(style="min-height: 48px") Cada 
              b usuario 
              | debe seguir siempre estas recomendaciones y buenas prácticas:

            SlyderA.slider-small.mb-3
              div
                .row.justify-content-center.mb-4
                  .col-md-6
                    img(src='@/assets/curso/t1-04.svg')
                .row.justify-content-center
                  .col-11
                    .tarjeta.tarjeta--blanca.p-4
                      p.mb-0 Instalar y mantener un antivirus, ya sea de pago o gratuito.
              div
                .row.justify-content-center.mb-4
                  .col-md-6
                    img(src='@/assets/curso/t1-06.svg')
                .row.justify-content-center
                  .col-11
                    .tarjeta.tarjeta--blanca.p-4
                      p.mb-0 No instalar aplicaciones desconocidas o de las cuales no se tenga la plena certeza de su origen.
              div
                .row.justify-content-center.mb-4
                  .col-md-6
                    img(src='@/assets/curso/t1-07.svg')
                .row.justify-content-center
                  .col-11
                    .tarjeta.tarjeta--blanca.p-4
                      p.mb-0 Si se reciben correos de remitentes desconocidos y que además contienen datos adjuntos, se deben de eliminar y de ninguna manera abrir dichos archivos.
              div
                .row.justify-content-center.mb-4
                  .col-md-6
                    img(src='@/assets/curso/t1-08.svg')
                .row.justify-content-center
                  .col-11
                    .tarjeta.tarjeta--blanca.p-4
                      p.mb-0 Actualizar periódicamente el sistema operativo del dispositivo utilizado.
              div
                .row.justify-content-center.mb-4
                  .col-md-6
                    img(src='@/assets/curso/t1-09.svg')
                .row.justify-content-center
                  .col-11
                    .tarjeta.tarjeta--blanca.p-4
                      p.mb-0 Habilitar un <em>firewall</em> del sistema operativo que limite la ejecución de algunas aplicaciones o servicios no necesarios o desconocidos.

      .col-lg-12
        .tarjeta.color-gradient.h-100.p-4.p-lg-5
          p.text-center.mb-4(style="min-height: 48px") Ahora, desde el punto de vista 
            b empresarial
            | , las recomendaciones son:

          SlyderA.slider-small.mb-3
            div
              .row.justify-content-center.mb-4
                .col-md-6
                  img(src='@/assets/curso/t1-10.svg')
              .row.justify-content-center
                .col-11
                  .tarjeta.tarjeta--blanca.p-4
                    p.mb-0 Restringir los permisos administrativos para el acceso a los recursos tecnológicos solo a personal autorizado.
            div
              .row.justify-content-center.mb-4
                .col-md-6
                  img(src='@/assets/curso/t1-11.svg')
              .row.justify-content-center
                .col-11
                  .tarjeta.tarjeta--blanca.p-4
                    p.mb-0 Determinar corporativamente qué tipo de aplicaciones y cuáles pueden ser utilizadas de manera corporativa, tanto pagas como libres.

            div
              .row.justify-content-center.mb-4
                .col-md-6
                  img(src='@/assets/curso/t1-12.svg')
              .row.justify-content-center
                .col-11
                  .tarjeta.tarjeta--blanca.p-4
                    p.mb-0 Mantener actualizados los sistemas operativos, pero de manera controlada a partir de una política de actualizaciones.
            div
              .row.justify-content-center.mb-4
                .col-md-6
                  img(src='@/assets/curso/t1-13.svg')
              .row.justify-content-center
                .col-11
                  .tarjeta.tarjeta--blanca.p-4
                    p.mb-0 Utilizar siempre un antivirus, en lo posible de tipo corporativo y de pago.
            div
              .row.justify-content-center.mb-4
                .col-md-6
                  img(src='@/assets/curso/t1-14.svg')
              .row.justify-content-center
                .col-11
                  .tarjeta.tarjeta--blanca.p-4
                    p.mb-0 Controlar y restringir el acceso a las redes inalámbricas.
            div
              .row.justify-content-center.mb-4
                .col-md-6
                  img(src='@/assets/curso/t1-15.svg')
              .row.justify-content-center
                .col-11
                  .tarjeta.tarjeta--blanca.p-4
                    p.mb-0 No utilizar redes sociales o herramientas personales para la ejecución de actividades corporativas.
            div
              .row.justify-content-center.mb-4
                .col-md-6
                  img(src='@/assets/curso/t1-16.svg')
              .row.justify-content-center
                .col-11
                  .tarjeta.tarjeta--blanca.p-4
                    p.mb-0 Realizar copias de seguridad permanentes de la información sensible o crítica que es usada para el desarrollo de sus funciones dentro de la organización.

    Separador

    #t1-2.titulo-segundo
      h2 1.2 Antivirus gratuitos

    p.mb-5 El siguiente video explica qué es un antivirus y la diferencia entre los comerciales y los gratuitos.

    figure.mb-5
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/fs_3DUH8QAE?si=56JILxTJmM3upra3" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)

    h5.mb-5 También podemos encontrar otras diferencias, como son:

    .row.justify-content-around.mb-5
      .col-lg-8.col-xl-6.mb-4.mb-md-0
        AcordionA(tipo="a" clase-tarjeta="tarjeta color-acento-contenido")
          div(titulo="Consumo de recursos <em>hardware y software</em>")
            p.mb-0 Generalmente, los antivirus de pago o comerciales tienen interfaces más sencillas que consumen menos recursos que los gratuitos.
          div(titulo="Soporte técnico")
            p.mb-0 El soporte por parte del fabricante de un antivirus gratuito es más limitado en cuanto a actualizaciones, definiciones de nuevos virus entre los dos modelos.
          div(titulo="Anuncios")
            p.mb-0 Los antivirus gratuitos disponen de una serie de anuncios o publicidad de parte del fabricante o de terceros, esto puede resultar algo molesto.
          div(titulo="Tecnologías de punta")
            p.mb-0 Para la búsqueda, detección y eliminación de los virus, en los antivirus de pago se utilizan varias tecnologías que permiten identificar y detectar nuevos virus o mutaciones de acuerdo con los comportamientos de virus ya conocidos, mientras que en los antivirus gratuitos operan con una única tecnología que reconoce los antivirus más conocidos.
      .col.d-none.d-lg-block
        .row.justify-content-center.align-items-end.h-100
          .col-xl-8
            img(src='@/assets/curso/t1-17.svg')

    p.mb-5 A continuación, se enumeran algunas de las soluciones de antivirus gratuitos más conocidas o utilizadas y sus páginas web oficiales <b>desde donde se pueden descargar</b>. Por favor, valide el que se adapte a su necesidad e instale, <b>no se recomienda instalar más de uno</b> por dispositivo.

    .row.mb-5
      .col-3
        .tarjeta.tarjeta--blanca.shadow.p-3.mb-3
          img(src='@/assets/curso/t1-18.jpg')
        a.d-block.text-center(href="https://www.avast.com/" target="_blank") www.avast.com
      .col-3
        .tarjeta.tarjeta--blanca.shadow.p-3.mb-3
          img(src='@/assets/curso/t1-19.jpg')
        a.d-block.text-center(href="https://www.pandasecurity.com/" target="_blank") www.pandasecurity.com
      .col-3
        .tarjeta.tarjeta--blanca.shadow.p-3.mb-3
          img(src='@/assets/curso/t1-20.jpg')
        a.d-block.text-center(href="https://www.avg.com/" target="_blank") www.avg.com


    .row.align-items-center
      .col-3
        .tarjeta.tarjeta--blanca.shadow.p-3.mb-3
          img(src='@/assets/curso/t1-21.jpg')
      .col-4
        p.mb-0(style="color: #0077EC") Windows Defender: es un antivirus propio del sistema operativo Microsoft el cual solo debe activarse y mantenerse actualizado.

    Separador

    .row.justify-content-center.align-items-center.mb-5
        
      .col-md.mb-4.mb-md-0
        #t1-3.titulo-segundo
          h2 1.3 Gestión de contraseñas
        p Esta es una de las mejores prácticas a implementar como usuarios regulares de herramientas tecnológicas, donde se requiere para el acceso o uso ingresar con una cuenta de usuario y una contraseña.

        p Una mala práctica en este sentido puede comprometer la privacidad, lo que deriva en vulnerabilidad por parte de un tercero que puede editar, borrar o manipular la información personal de cada persona. Para el caso de los correos electrónicos, datos bancarios y redes sociales, el uso de estos elementos conocidos como <em>password</em> es fundamental y se debe tener cuidado extremo a la hora de su generación y uso. 
        
        p.mb-0
          b A continuación, se amplía en el siguiente video, el concepto de contraseña.

      .col-4
        img(src='@/assets/curso/t1-22.svg')

    figure.mb-5
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/MKGPDHf5VM0?si=djuXJvUDc3dZuIAK" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)

    .tarjeta.color-acento-botones.p-5.mb-5
      p.mb-0 Se deben tener siempre presente las siguientes recomendaciones, sean en el plano personal o corporativo, para evitar una mala práctica en la gestión de contraseñas.

    TabsA.color-secundario.mb-5
      .tarjeta.tarjeta--azul.p-5(titulo="No utilizar la misma contraseña en varios servicios")
        h4 No utilizar la misma contraseña en varios servicios
        p.mb-0 Nunca se debe usar la misma contraseña para acceder a diferentes servicios, esto debido a que la autenticación es vulnerable no solo en uno, sino en varios servicios al tiempo dejando muy expuestos los datos.

      .tarjeta.tarjeta--azul.p-5(titulo="Preguntas de seguridad")
        h4 Preguntas de seguridad
        p.mb-0 Algunas aplicaciones o servicios utilizan esta estrategia para poder facilitar el hecho de recuperar una contraseña o validar el acceso, tenga cuidado cuando cree estas preguntas asegurándose de que las respuestas y la selección de las preguntas solo sean conocidas por usted.

      .tarjeta.tarjeta--azul.p-5(titulo="Usar contraseñas robustas")
        h4 Usar contraseñas robustas
        p Esto significa que se deben de utilizar contraseñas seguras y ajustadas a algunos estándares que garanticen que estas no puedan ser reveladas o capturadas por un tercero, para este caso se recomienda que, entre otras características, una contraseña cuente con lo siguiente:
        ul.lista-ul
          li 
            i.lista-ul__vineta
            | Un número mínimo de 8 caracteres y que contenga en su combinación mínimamente.
          li 
            i.lista-ul__vineta
            | Una letra en mayúscula (A, B, C, …Z).
          li 
            i.lista-ul__vineta
            | Una letra en minúscula (a, b, c,…z).
          li 
            i.lista-ul__vineta
            | Un número (0,1, 2, 3…9).
          li 
            i.lista-ul__vineta
            | Un carácter especial (¡°|#$%&/()=?¡*+}{}[[.,-…).

      .tarjeta.tarjeta--azul.p-5(titulo="Doble autenticación")
        h4 Doble autenticación
        p.mb-0 Varios servicios de datos trabajan con dos o más medios de ingreso, es así como garantizan el uso del servicio, por ejemplo: para ingresar a un correo electrónico en un dispositivo desconocido por el sistema, se requiere la contraseña más un número que puede llegar a su dispositivo móvil, en este caso se necesita que el número de su dispositivo móvil sea constante porque entra a hacer parte de la contraseña.

      .tarjeta.tarjeta--azul.p-5(titulo="Utilizar un gestor de contraseña")
        h4 Utilizar un gestor de contraseña
        p.mb-0 Para la generación o creación de contraseñas seguras se recomienda la utilización de herramientas que permiten la generación de las contraseñas cumpliendo con todas las recomendaciones antes mencionadas; a continuación, se mencionan y se comparte el link de algunas de estas aplicaciones que pueden ser utilizadas, aunque es importante mencionar que algunas de ellas son pagas y otras de uso libre.

    p.mb-4
      b En el caso puntual de los generadores de contraseñas, se aconseja el uso de cualquiera de los siguientes recursos:

    .tabla-a.color-secundario.mb-4
      table
        thead
          tr
            th Gestor de contraseñas
            th Sitio web
        tbody
          tr
            td KeePass: es una solución de código abierto muy utilizada y potente.
            td 
              a(href="https://keepass.info/" target="_blank") https://keepass.info/
          tr
            td 1Password: es una muy buena alternativa de uso comercial, quizá la más recomendada.
            td 
              a(href="https://1password.com/" target="_blank") https://1password.com/
          tr
            td Dashlane: es una herramienta con excelente diseño y es sencilla de utilizar, aunque es de pago ofrece muy buenas funcionalidades.
            td
              a(href="https://www.dashlane.com/es" target="_blank") https://www.dashlane.com/es
          tr
            td Keeper: es una muy buena alternativa que, aunque no tiene un muy buen diseño, tiene aplicaciones para escritorio, móvil y navegadores.
            td
              a(href="https://www.keepersecurity.com/es_ES/" target="_blank") https://www.keepersecurity.com/es_ES/ 

    p.mb-5 Se propone utilizar un generador de contraseñas en el que, eligiendo los niveles de complejidad, puedan generarse las contraseñas. 
      b A continuación, se mencionan algunos de los sitios que pueden ser utilizados para esta labor:

    h3.mb-4 Lastpass

    p En este sitio se puede elegir qué nivel de seguridad y complejidad requiere la contraseña y se hace la generación de una contraseña segura.

    h3.mb-4 Roboform

    p Esta alternativa puede ser utilizada para generar contraseñas seguras.

    Separador

    #t1-4.titulo-segundo
      h2 1.4 Fuentes de descarga segura de #[em software]

    p.mb-5 En la cotidianidad, se utiliza Internet y otras herramientas tecnológicas y es común encontrar algunas soluciones de aplicaciones y/o servicios que pueden potencializar el uso de las TIC (Tecnologías de la Información y Comunicación), eso hace que sea obligatorio prestar especial atención a los sitios desde los cuales se hacen las descargas de cualquier tipo de aplicación. Lo primero, al momento de tratar de descargar una aplicación o archivo, es reconocer si la descarga se hace desde un sitio seguro y para ello se presentan las siguientes recomendaciones, las cuales cada usuario de las redes, puede aplicar a conveniencia.

    .row
      .col-lg-6
        .tarjeta.color-gradient-b.d-flex.px-4.py-5.mb-4
          .icono-tarjeta.me-4
            img(src='@/assets/curso/flecha-hacia-abajo.svg')
          p.mb-0 La mejor recomendación es descargar alguna aplicación, juego o archivo desde los sitios oficiales del fabricante.

        .tarjeta.color-gradient-b.d-flex.px-4.py-5.mb-4
          .icono-tarjeta.me-4
            img(src='@/assets/curso/flecha-hacia-abajo.svg')
          p.mb-0 Si la descarga se va a hacer a partir de un <em>link</em> recomendado por alguna persona o página, se deben de validar los comentarios de otros usuarios que hayan hecho la descarga e identificar las credenciales y reputación de quien publica algún comentario, ya que puede haber comentarios falsos dispuestos solo para generar una falsa confianza en la persona que va a descargar.

        .tarjeta.color-gradient-b.d-flex.px-4.py-5.mb-4
          .icono-tarjeta.me-4
            img(src='@/assets/curso/flecha-hacia-abajo.svg')
          p.mb-0 Si se desea comprar alguna aplicación, utilizar las tiendas oficiales; por ejemplo, en el tema de las aplicaciones móviles recurrir a las #[em apps store] según el dispositivo utilizado y siempre validar los comentarios y recomendaciones de otros usuarios.

        .tarjeta.color-gradient-b.d-flex.px-4.py-5.mb-4
          .icono-tarjeta.me-4
            img(src='@/assets/curso/flecha-hacia-abajo.svg')
          p.mb-0 Desconfiar de aplicaciones gratuitas, antes de descargar e instalar alguna aplicación de este tipo se debe verificar su origen e idoneidad, pues se puede incurrir en el uso de <em>software</em> falso que simula realizar acciones de protección y mejora del rendimiento del equipo, pero en realidad lo que hace es infectar o afectar los equipos con virus, <em>malware</em> y <em>adware</em>.


      .col-lg-6
        .tarjeta.color-gradient-b.d-flex.px-4.py-5.mb-4
          .icono-tarjeta.me-4
            img(src='@/assets/curso/flecha-hacia-abajo.svg')
          p.mb-0 No utilizar <em>software</em> falso o pirata, normalmente se tiende a utilizar <em>software</em> de manera ilegal sin licencia lo que obliga a utilizar los llamados <em>cracks</em> de activación, estos normalmente vienen infectados con algún tipo de virus, lo que ocasionará que los equipos donde se instale el <em>software</em> de manera ilegal se infecten y queden expuestos a robo de información.

        .tarjeta.color-gradient-b.d-flex.px-4.py-5.mb-4
          .icono-tarjeta.me-4
            img(src='@/assets/curso/flecha-hacia-abajo.svg')
          p.mb-0 No acceder a descarga de apps a través de #[em links] dispuestos en páginas donde se promocionan estas aplicaciones o #[em software], normalmente este tipo de #[em links] llevarán a un sitio predeterminado o previamente configurado para que se descarguen las #[em apps] con algún tipo de infección con #[em malware] o virus.

        .tarjeta.color-gradient-b.d-flex.px-4.py-5.mb-4
          .icono-tarjeta.me-4
            img(src='@/assets/curso/flecha-hacia-abajo.svg')
          p.mb-0 Cuando se realicen descargas de aplicaciones tener siempre activo el antivirus, esto permitirá hacer una revisión de la descarga a fin de examinar e identificar posibles virus, <em>malware</em> y <em>spyware</em>.

    Separador

    #t1-5.titulo-segundo
      h2 1.5 Datos personales y datos de terceros 

    p Los datos personales son toda aquella información que describe, identifica y caracteriza a una persona.

    p.mb-5
      b Algunos ejemplos de los datos personales son:


    .row.align-items-center.justify-content-center.mb-5
      .d-sm-none.col-6
        img(src='@/assets/curso/t1-25.svg')
      .col-sm-6.col-lg-3
        .tarjeta.color-secundario.px-4.py-3.mb-3
          p.mb-0 Nombres y apellidos.
        .tarjeta.color-secundario.px-4.py-3.mb-3
          p.mb-0 Edad.
        .tarjeta.color-secundario.px-4.py-3.mb-3
          p.mb-0 Dirección o domicilio.
        .tarjeta.color-secundario.px-4.py-3.mb-3
          p.mb-0 Correo electrónico.
        .tarjeta.color-secundario.px-4.py-3.mb-3
          p.mb-0 Número de teléfono.
        .tarjeta.color-secundario.px-4.py-3.mb-3
          p.mb-0 Educación o perfil académico.
        .tarjeta.color-secundario.px-4.py-3.mb-3.mb-lg-0
          p.mb-0 Patrimonio.
      .d-none.d-lg-block.col-lg-4
        img(src='@/assets/curso/t1-25.svg')
      .col-sm-6.col-lg-3
        .tarjeta.color-secundario.px-4.py-3.mb-3
          p.mb-0 Estado de salud.
        .tarjeta.color-secundario.px-4.py-3.mb-3
          p.mb-0 Origen étnico.
        .tarjeta.color-secundario.px-4.py-3.mb-3
          p.mb-0 Creencia religiosa.
        .tarjeta.color-secundario.px-4.py-3.mb-3
          p.mb-0 Ideología política.
        .tarjeta.color-secundario.px-4.py-3.mb-3
          p.mb-0 Preferencias sexuales.
        .tarjeta.color-secundario.px-4.py-3
          p.mb-0 Documento de identidad.

    p.mb-5 Es muy útil reconocer la importancia que tiene la protección de los datos personales, para evitar que estos datos sean utilizados con una finalidad distinta a la que inicialmente fueron suministrados, evitando que se vulneren los derechos y libertades de los usuarios en red; esto implica que siempre que se use un sitio físico o virtual, que requiera de un registro, es necesario poner especial atención en que se identifique claramente cuál será el propósito o finalidad que tienen para el manejo de los datos personales registrados.

    .bloque-texto-a.color-primario.p-4.p-md-5.mb-5 
      .row.m-0.align-items-center.justify-content-center
        .col-6.col-lg-3.mb-4.mb-lg-0
          img(src='@/assets/curso/t1-26.svg')
        .col-lg-9
          .bloque-texto-a__texto.px-4.py-5
            p Para este propósito, el Estado colombiano desarrolló la Ley Estatutaria 1581 de 2012, que constituye el marco general de la protección de los datos personales en Colombia. Entre otras cosas, esta Ley manifiesta el derecho que tienen todas las personas a autorizar el uso de la información personal almacenada en bases de datos y archivos administrados por personas naturales o jurídicas, públicas o privadas, así como su posterior actualización, modificación y rectificación.

    p 
      b Para recordar: 
      | toda empresa, sitio, página o portal web que requiera el registro de los datos personales, debe (sin ninguna excepción), solicitar la autorización a todas las personas para el tratamiento de sus datos personales.
    p.mb-5
      b Esta autorización requiere:

    .cajon.color-secundario.p-5.mb-5
      ul.lista-ul.mb-0
        li.d-flex
          i.fas.fa-check
          p.mb-0 Tener un 
            b consentimiento informado
            | , lo que significa que antes de solicitar datos personales, debe ser expresada e informada la solicitud de tratamiento de los datos personales.
        li.d-flex
          i.fas.fa-check
          div Determinar de manera clara para qué serán usados los datos que buscan ser obtenidos.
        li.d-flex
          i.fas.fa-check
          div Especificar claramente los derechos y los medios a través de los cuales puede el usuario ejercerlos.
        li.mb-0.d-flex
          i.fas.fa-check
          div Respetar las condiciones de seguridad y privacidad de la información, sin obviar el trámite de consultas, solicitudes y reclamos por parte de los sujetos que se puedan ver afectados por la obtención de sus datos personales sin previa autorización.

    p.mb-5 Es importante mencionar que las empresas que reciben los datos a través de registros realizados por terceros, tienen que cumplir con los mismos criterios de solicitud de autorización, pero adicionalmente se deben priorizar las siguientes actividades.

    .cajon.color-secundario.p-5
      ul.lista-ul.mb-0
        li 
          i.fas.fa-check
          | Creación de la política de protección de datos personales.
        li 
          i.fas.fa-check
          | Creación del consentimiento informado.
        li 
          i.fas.fa-check
          | Levantamiento de las bases de datos.
        li.mb-0
          i.fas.fa-check
          | Registro nacional de las bases de datos ante la Superintendencia de Industria y Comercio.

    Separador

    #t1-6.titulo-segundo
      h2 1.6 Compras por Internet

    .row.justify-content-center.align-items-center.mb-5    
      .col-md.mb-4.mb-md-0
        p.mb-0 Internet y la masificación del uso de las Tecnologías de la Información y las Comunicaciones (TIC) ha potenciado e incrementado el mercado digital; cada vez es mayor y mejor el acceso a la oferta y compra de productos y servicios en línea, lo que conlleva a identificar cuál o cuáles serán las mejores prácticas o recomendaciones a tener en cuenta al momento de realizar algún tipo de transacción que incluya movimientos financieros.

      .col-6.col-md-3
        img(src='@/assets/curso/t1-27.svg')

    .row.justify-content-center.mb-5
      .col-10.text-center
        h3 En la actualidad, gran parte de las transacciones diarias se realizan por Internet desde dispositivos móviles o electrónicos. Algunas de las transacciones que se pueden hacer en línea son:


    .row.align-items-center.mb-5
      .col-3.d-none.d-lg-block
        img(src='@/assets/curso/t1-28.svg')

      .col-lg-9
        .row.mb-5.justify-content-center
          .col-sm-7.mb-4.mb-sm-0
            div
              .tarjeta.color-secundario--claro.d-inline-block.p-4.mb-3
                h5.mb-0 Pago de impuestos.

            div
              .tarjeta.color-secundario--claro.d-inline-block.p-4.mb-3
                h5.mb-0 Compra de ropa y accesorios.

            div
              .tarjeta.color-secundario--claro.d-inline-block.p-4.mb-3
                h5.mb-0 Compra de tiquetes aéreos.

            div
              .tarjeta.color-secundario--claro.d-inline-block.p-4.mb-3
                h5.mb-0 Compra de cursos y formación  virtual o autogestionada.

            div
              .tarjeta.color-secundario--claro.d-inline-block.p-4.mb-3
                h5.mb-0 Servicio de domicilio de comidas, bebidas, productos de la canasta familiar, entre otros.

          .col-6.col-sm-5
            img(src='@/assets/curso/t1-29.svg')

        p Cuando se realizan compras por Internet, es importante tener presente las siguientes buenas prácticas o consejos:


    .row.justify-content-center
      .col-lg-10
        AcordionA(tipo="a" clase-tarjeta="tarjeta color-acento-contenido")
          div(titulo="Saber exactamente qué tipo de producto o servicio se requiere")
            p.mb-0 Al momento de hacer la compra, se debe tener claridad frente a las características del producto o servicio que se desea adquirir, porque debido a la gran oferta que existe, no siempre el mejor precio corresponde a productos más confiables.
          div(titulo="Revisar y comparar las referencias y comentarios")
            p.mb-0 Estos son hechos por otros compradores del mismo producto, para validar la calidad y cumplimiento y seriedad del proveedor.
          div(titulo="Navegar e interactuar con las plataformas o sitios donde se hará la compra")
            p.mb-0 Se recomienda hacer una navegación detallada dentro de las plataformas para identificar sus contenidos, periodos de actualización, comentarios o algo que permita identificar si efectivamente es un sitio válido, confiable y seguro.
          div(titulo="Validación de la seguridad básica de la plataforma o sitio de comercio")
            p.mb-0 Todo sitio serio debe contar con unas medidas de seguridad técnicas que son básicas y requeridas, por ejemplo, se debe validar que cuente con un certificado digital que garantice que la información, datos o transacciones se hagan protegidas y cifradas, para esto se valida que la URL cuente con un protocolo seguro como lo es #[strong https://], si se cuenta con este requisito básico en la URL previo al nombre, debe mostrar un candado, lo cual indica que el sitio es seguro.
          div(titulo="Pagos seguros")
            p.mb-0 El momento de realizar el pago por el producto o servicio adquirido, se debe realizar la validación que se cuenta con una pasarela de pagos reconocida y certificada. Las siguientes son pasarelas de pago certificadas y aprobadas en el país: PayU, Mercado Pago, En Línea Pagos, Pagos Inteligentes, Opacó, Interpagos, Pago Digital, Recaudo Express, Mercado Libre, PSE, Paypal.
          div(titulo="Política de privacidad y devoluciones")
            p.mb-0 En toda plataforma de comercio se debe contar una clara política de privacidad, devoluciones y de fácil acceso, que facilite al usuario en un momento determinado saber cuál es el proceso para una devolución, qué debe hacer y tener claridad frente al manejo de sus datos personales.
          div(titulo="Acceso a canales de soporte y servicio al cliente")
            p.mb-0 Una página o sitio confiable donde se pueden realizar compras #[em online], debe contar con las estrategias y canales de atención como redes sociales, página web, teléfonos y direcciones, esto permitirá determinar si el sitio es seguro, operativo y confiable.
          div(titulo="Términos y condiciones")
            p.mb-0 El sitio o plataforma donde se realicen las compras debe contar con espacio claramente determinado con los términos y condiciones donde se especifique claramente las condiciones para los pagos, políticas de devoluciones y reembolsos, envíos, costos de transporte, tiempos de entrega, entre otros, de esta manera se evitará tener inconvenientes y experiencias no favorables con la compra.
      
</template>

<script>
export default {
  name: 'Tema1',
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
