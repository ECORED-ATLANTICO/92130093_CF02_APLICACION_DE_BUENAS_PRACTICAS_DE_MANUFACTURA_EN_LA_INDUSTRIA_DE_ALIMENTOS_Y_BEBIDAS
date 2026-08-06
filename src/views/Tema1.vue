<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 1
      h1 Fundamentos de los programas de saneamiento en la industria alimentaria

    

    .bg-full-width.bg-fondo-3.px-5.py-4
      img(src="@/assets/curso/tema1/img02.png", alt="")
    .row.justify-content-center.align-items-center.z-2.mb-5
      .col-lg-11(data-aos="fade-right")
        p.banner-text Antes de abordar la verificación y el control, es necesario establecer un marco conceptual sólido sobre los programas de saneamiento y su importancia dentro de la industria alimentaria. Estos programas no corresponden a documentos que se elaboran únicamente para dar cumplimiento a un requisito normativo, sino que representan el compromiso permanente de una organización con la protección de la salud pública y la inocuidad de los alimentos. Su implementación, ejecución y seguimiento constituyen la base para garantizar que los alimentos procesados sean aptos para el consumo humano y cumplan con los requisitos de calidad e inocuidad establecidos por la normativa vigente y las exigencias del mercado.

    separador
    
    #t_1_1.titulo-segundo.color-acento-contenido(data-aos="flip-up")
      h2 1.1 Concepto e importancia de los programas de saneamiento

    .row.mb-4.justify-content-center.align-items-center
      .col-lg-6.col-md-12.mb-4.mb-lg-0
        figure
          img(src="@/assets/curso/tema1/img03.png", data-aos="zoom-in")
      .col-lg-6
        p.mb-0 Los programas de saneamiento son un conjunto de actividades, procedimientos y controles documentados que tienen como objetivo mantener las instalaciones, equipos y procesos en condiciones higiénicas óptimas, previniendo así la contaminación de los alimentos. Son considerados prerrequisitos, es decir, las condiciones y prácticas básicas que deben estar implementadas y funcionando correctamente antes de aplicar sistemas más complejos como el Análisis de Peligros y Puntos Críticos de Control (HACCP). La palabra "prerrequisito" es clave: sin ellos, no se puede construir nada sólido en materia de inocuidad.

    .row.mb-5.justify-content-center.align-items-center
      .col-lg-12
        .bg-color-01.p-4.br-15
          p.mb-0 Su importancia radica en que actúan como la primera y más importante barrera contra los peligros de contaminación. Un programa de limpieza deficiente, por ejemplo, puede convertir una superficie de trabajo en un foco de microorganismos patógenos que luego contaminarán lotes enteros de producción. De la misma manera, la falta de control de plagas puede resultar en la contaminación física (pelos, excrementos, fragmentos de insectos) y microbiológica de materias primas y productos terminados, generando pérdidas económicas y un riesgo sanitario inaceptable. Por lo tanto, la verificación constante de estos programas no es un trámite burocrático, sino una acción directa de salud pública y de aseguramiento de la calidad. Sin una base sólida de saneamiento, cualquier otro esfuerzo por controlar la inocuidad será insuficiente y estará en constante riesgo de fracasar.
    
    
    .bg-full-width.bg-fondo-1
      .row.justify-content-center.align-items-center.z-2.mb-5
        .col-lg-10
          .titulo-sexto.color-acento-contenido.mb-4
            h5 Figura 1.
            span La pirámide de la inocuidad: programas de saneamiento como base
          img.mb-2(data-aos="fade-up", src="@/assets/curso/tema1/img04.png", alt="La figura 1 describe cómo los programas de saneamiento y las BPM son la base fundamental sobre la que se construyen sistemas más avanzados y se alcanza la competitividad.")
          figcaption Nota. SENA, (2026).

    separador
    
    #t_1_2.titulo-segundo.color-acento-contenido(data-aos="flip-up")
      h2 1.2 Marco normativo colombiano aplicable a los programas de saneamiento




    .row.mb-5.justify-content-center.align-items-center
      .col-lg-3.col-md-8.mb-0.mb-lg-0.order-2.order-lg-2.d-none.d-lg-block
        figure
          img(src="@/assets/curso/tema1/img05.png", data-aos="zoom-in")
      .col-lg-9.order-1.order-lg-1.mb-0.mb-lg-0
        p.mb-4(data-aos="fade-right") En Colombia, el cumplimiento de los programas de saneamiento es de carácter obligatorio y se encuentra respaldado por un marco normativo que establece los requisitos sanitarios para la producción, el procesamiento, el almacenamiento y la comercialización de alimentos. Estas disposiciones constituyen el referente para la implementación de los programas de saneamiento, así como para la ejecución de inspecciones sanitarias oficiales, auditorías internas y procesos de verificación.

        .bg-color-02.p-4.br-15.mb-0
          p.mb-2 La Resolución 2674 de 2013, expedida por el Ministerio de Salud y Protección Social, establece los requisitos sanitarios que deben cumplir los establecimientos dedicados a la fabricación, procesamiento, preparación, envase, almacenamiento, transporte, distribución y comercialización de alimentos. Entre sus disposiciones, contempla la implementación y el mantenimiento de programas de saneamiento relacionados con:

          .row.align-items-center.justify-content-center
            .col-lg-7.mb-3.mb-lg-0
              ul.lista-ul--color.mb-0
                li 
                  i.fas.fa-circle-check
                  | Limpieza y desinfección (artículo 24).
                li 
                  i.fas.fa-circle-check
                  | Control de plagas (artículo 25).
                li 
                  i.fas.fa-circle-check
                  | Manejo de residuos sólidos y líquidos (artículo 20).
                li 
                  i.fas.fa-circle-check
                  | Abastecimiento de agua potable (artículo 11).
                li 
                  i.fas.fa-circle-check
                  | Mantenimiento de instalaciones y equipos (artículo 15).
            .col-lg-5.col-md-8
              figure
                img(src="@/assets/curso/tema1/img06.png", data-aos="zoom-in").mx-auto

    p.mb-5 Por su parte, el Decreto 60 de 2002 promueve la aplicación del Sistema de Análisis de Peligros y Puntos Críticos de Control (HACCP) en los establecimientos de alimentos y establece los lineamientos para los programas prerrequisito, los cuales constituyen la base para la implementación de este sistema preventivo. En consecuencia, la verificación del cumplimiento de los programas de saneamiento se realiza tomando como referencias estas y otras disposiciones normativas, las cuales sirven de fundamento para las inspecciones oficiales, las auditorías internas y los procesos de aseguramiento de la inocuidad alimentaria.

    

    .row.mb-5.justify-content-center.align-items-center
      .col-lg-12.col-md-12.mb-0.mb-lg-0
        .titulo-sexto.color-acento-contenido.mb-3
          h5 
            b Tabla 1.
          span Requisitos normativos clave para programas de saneamiento
        .tabla-a.color-acento-contenido.tb-custom.mb-0
          table
            caption <span style="font-weight: normal">Nota. SENA, (2026).</span>
            thead
              tr
                th Norma
                th Artículo / capítulo
                th Requisito asociado
                th Implicación para la planta
            tbody
              tr
                td Res. 2674/2013
                td Artículo 11
                td Abastecimiento de agua potable con presión y temperatura adecuadas.
                td Instalación de tanques de almacenamiento, sistemas de cloración y red de distribución en buen estado.
              tr
                td Res. 2674/2013
                td Artículo 20
                td Manejo de residuos: recipientes identificados, remoción frecuente.
                td Contar con un programa de residuos, recipientes en buen estado y rutas de recolección definidas.
              tr
                td Res. 2674/2013
                td Artículo 24
                td Procedimientos de limpieza y desinfección escritos (POES).
                td Elaborar y mantener actualizados los POES, y tener registros de su ejecución y verificación.
              tr
                td Res. 2674/2013
                td Artículo 25
                td Control integrado de plagas: programa con enfoque preventivo.
                td Contratar una empresa autorizada o tener personal capacitado, con un plan que incluya barreras físicas y químicas.
              tr
                td Decreto 60/2002
                td Artículo 3
                td Implementación de prerrequisitos (BPM, POES) antes del HACCP.
                td Demostrar que los programas de saneamiento están funcionando antes de pasar a un sistema HACCP.

    separador
    
    #t_1_3.titulo-segundo.color-acento-contenido(data-aos="flip-up")
      h2 1.3 Relación de los programas de saneamiento con las Buenas Prácticas de Manufactura (BPM)



    .row.mb-5.justify-content-center.align-items-center
      .col-lg-4.col-md-8.mb-0.mb-lg-0.order-2.order-lg-1
        figure
          img(src="@/assets/curso/tema1/img07.png", data-aos="zoom-in")
      .col-lg-8.order-1.order-lg-1.mb-4.mb-lg-0
        p.mb-4 Las Buenas Prácticas de Manufactura (BPM) son los principios básicos y prácticas generales de higiene en la manipulación, preparación, elaboración, envasado y almacenamiento de alimentos para consumo humano. Son el punto de partida de cualquier sistema de calidad. Los programas de saneamiento son, en esencia, la materialización operativa y detallada de los principios de higiene que las BPM exigen.
        .bg-color-0.p-4.br-15.mb-0
          p.mb-0 Mientras las BPM dictan, por ejemplo, que "las instalaciones deben mantenerse limpias", el programa de limpieza y desinfección (contenido en los POES) especifica cómo (procedimiento paso a paso, incluyendo técnicas de cepillado, enjuague, etc.), cuándo (frecuencia diaria, semanal, mensual, asociada a la producción), con qué (productos específicos, concentraciones, tiempos de contacto y temperatura de la solución) y quién (responsable de ejecutar y responsable de verificar) se llevará a cabo esa limpieza. De esta manera, los programas de saneamiento le dan un carácter sistemático, medible y verificable a los principios generales establecidos en las BPM. En conjunto, forman un sistema coherente que garantiza un ambiente de producción higiénico y controlado.

    separador
    
    #t_1_4.titulo-segundo.color-acento-contenido(data-aos="flip-up")
      h2 1.4 Estructura documental de un programa de saneamiento

    .row.mb-5.justify-content-center.align-items-center
      .col-lg-3.col-md-8.mb-0.mb-lg-0.order-2.order-lg-2.d-none.d-lg-block
        figure
          img(src="@/assets/curso/tema1/img08.png", data-aos="zoom-in")
      .col-lg-9.order-1.order-lg-1.mb-4.mb-lg-0
        p.mb-4(data-aos="fade-right") Para que un programa de saneamiento sea verificable, debe estar correctamente documentado. La documentación no es un fin en sí misma, pero es la herramienta que permite estandarizar, comunicar y demostrar lo que se hace. Un programa de saneamiento típico debe contener los siguientes elementos:
        
        ol.lista-ol--cuadro.lista-ol--separador
          li 
            .lista-ol--cuadro__vineta
              span A
            | Objetivo: ¿para qué sirve el programa?
          li 
            .lista-ol--cuadro__vineta
              span B
            | Alcance: ¿a qué áreas, equipos o procesos aplica?
          li 
            .lista-ol--cuadro__vineta
              span C
            | Responsabilidades: ¿quién hace qué? (ejecuta, supervisa, verifica, aprueba).
          li 
            .lista-ol--cuadro__vineta
              span D
            | Procedimientos (POES): descripción detallada de las actividades, paso a paso.
          li 
            .lista-ol--cuadro__vineta
              span E
            | Frecuencias: ¿cada cuánto se realiza cada actividad?
          li 
            .lista-ol--cuadro__vineta
              span F
            | Productos e insumos: listado de productos químicos utilizados, con sus fichas técnicas y hojas de seguridad (SDS).
          li 
            .lista-ol--cuadro__vineta
              span G
            | Registros: formatos diseñados para dejar evidencia de la ejecución y verificación (ej. listas de chequeo, bitácoras).
          li 
            .lista-ol--cuadro__vineta
              span H
            | Indicadores: ¿cómo se mide la eficacia del programa? (ej. % de resultados microbiológicos conformes).

    .bg-full-width.bg-fondo-1
      .row.mb-5.justify-content-center.align-items-center
        .col-lg-4.mb-4.mb-lg-0.col-md-8.order-1.order-lg-1
          figure
            img(src="@/assets/curso/tema1/img09.png", data-aos="zoom-in")
        .col-lg-8.order-2.order-lg-2.col-md-12.mb-4.mb-lg-0
          SlyderF(columnas="col-lg-6 col-xl-6 col-md-12 col-sm-12 p-2")
            .tarjeta.tarjeta--blanca.shadow-sm.p-4.h-100
              .row.justify-content-center.mb-3
                .col-8
                  img(src='@/assets/curso/tema1/img11.svg' alt='', style="width: 100px; height: 100px; ").mx-auto
              h4.text-center Planificar (Plan)
              p.text-center Establecer los objetivos y procedimientos del programa de saneamiento, incluyendo el programa escrito y los Procedimientos Operativos Estandarizados de Saneamiento (POES).

            .tarjeta.tarjeta--blanca.shadow-sm.p-4.h-100
              .row.justify-content-center.mb-3
                .col-8
                  img(src='@/assets/curso/tema1/img12.svg' alt='', style="width: 100px; height: 100px; ").mx-auto
              h4.text-center Hacer (Do)
              p.text-center Ejecutar las actividades de acuerdo con lo planificado y diligenciar los registros correspondientes.

            .tarjeta.tarjeta--blanca.shadow-sm.p-4.h-100
              .row.justify-content-center.mb-3
                .col-8
                  img(src='@/assets/curso/tema1/img13.svg' alt='', style="width: 100px; height: 100px; ").mx-auto
              h4.text-center Verificar (Check)
              p.text-center Realizar verificaciones visuales, operacionales y analíticas, comparando los resultados con los criterios de aceptación establecidos.

            .tarjeta.tarjeta--blanca.shadow-sm.p-4.h-100
              .row.justify-content-center.mb-3
                .col-8
                  img(src='@/assets/curso/tema1/img14.svg' alt='', style="width: 100px; height: 100px; ").mx-auto
              h4.text-center Actuar (Act)
              p.text-center Implementar acciones correctivas y preventivas para fortalecer el desempeño de los programas de saneamiento y promover la mejora continua.


    //- .bloque-texto-g.bg-color-2.p-3.p-sm-4.p-md-5.mb-5
    //-   .bloque-texto-g__img(
    //-     :style="{'background-image': `url(${require_src('@/assets/curso/tema1/img03.png')})`}"
    //-   )
    //-   .bloque-texto-g__texto.p-4
    //-     p.mb-0 Las Buenas Prácticas de Manufactura (BPM) constituyen un conjunto de principios, requisitos y procedimientos de cumplimiento obligatorio, orientados a garantizar la inocuidad y la calidad de los alimentos durante todas las etapas de la cadena productiva. Su aplicación se fundamenta en el manejo higiénico de los alimentos, con el propósito de obtener productos seguros para el consumo humano.


    //- .row.mb-5.justify-content-center.align-items-center
    //-   .col-lg-12
    //-     .bg-color-3.p-4.br-15
    //-       p.mb-0.text-center Los objetivos principales de la implementación de las BPM en una empresa de alimentos y bebidas son:
    

    //- .bg-full-width.bg-fondo-7.px-5.py-5
    //-   SlyderA(tipo="b").bg-color-white.p-4.tarjeta
    //-     .tarjeta.p-4.h-100
    //-       .row.align-items-center.mb-0
    //-         .col-12.col-lg-6.mb-4.mb-lg-0
    //-           h4 Garantizar la inocuidad
    //-           p.mb-0 Es el principal objetivo de las Buenas Prácticas de Manufactura. Consiste en prevenir la contaminación de los alimentos durante todas las etapas del proceso productivo, garantizando que sean aptos para el consumo humano y no representen un riesgo para la salud.
    //-         .col-12.col-lg-6
    //-           figure
    //-             img(src="@/assets/curso/tema1/img05.png", alt="Garantizar la inocuidad").img-fluid

    //-     .tarjeta.p-4.h-100
    //-       .row.align-items-center.mb-0
    //-         .col-12.col-lg-6.mb-4.mb-lg-0
    //-           h4 Asegurar la calidad
    //-           p.mb-0 Las BPM permiten obtener productos con características uniformes y acordes con los estándares de calidad establecidos por la organización, favoreciendo la satisfacción del cliente y el mejoramiento continuo de los procesos.
    //-         .col-12.col-lg-6
    //-           figure
    //-             img(src="@/assets/curso/tema1/img06.png", alt="Asegurar la calidad").img-fluid

    //-     .tarjeta.p-4.h-100
    //-       .row.align-items-center.mb-0
    //-         .col-12.col-lg-6.mb-4.mb-lg-0
    //-           h4 Cumplir con la normativa sanitaria
    //-           p.mb-0 La implementación de las BPM garantiza el cumplimiento de la legislación sanitaria vigente, asegurando que los procesos de producción se desarrollen conforme a los requisitos establecidos por las autoridades competentes.
    //-         .col-12.col-lg-6
    //-           figure
    //-             img(src="@/assets/curso/tema1/img07.png", alt="Cumplir con la normativa sanitaria").img-fluid

    //-     .tarjeta.p-4.h-100
    //-       .row.align-items-center.mb-0
    //-         .col-12.col-lg-6.mb-4.mb-lg-0
    //-           h4 Fortalecer la cultura de calidad
    //-           p.mb-0 Las BPM promueven hábitos de trabajo responsables y fortalecen el compromiso del personal con la higiene, la inocuidad y la mejora continua, favoreciendo una cultura organizacional orientada a la calidad.
    //-         .col-12.col-lg-6
    //-           figure
    //-             img(src="@/assets/curso/tema1/img08.png", alt="Fortalecer la cultura de calidad").img-fluid

    //-     .tarjeta.p-4.h-100
    //-       .row.align-items-center.mb-0
    //-         .col-12.col-lg-6.mb-4.mb-lg-0
    //-           h4 Generar confianza en el consumidor
    //-           p.mb-0 La producción de alimentos inocuos y de calidad fortalece la confianza de los consumidores, mejora la reputación de la organización y contribuye a la permanencia de sus productos en el mercado.
    //-         .col-12.col-lg-6
    //-           figure
    //-             img(src="@/assets/curso/tema1/img09.png", alt="Generar confianza en el consumidor").img-fluid

    //- separador
    
    //- #t_1_2.titulo-segundo.color-acento-contenido(data-aos="flip-up")
    //-   h2 1.2 Importancia de la inocuidad como pilar fundamental

    //- .bloque-texto-g.bg-color-2.p-3.p-sm-4.p-md-5.mb-5
    //-   .bloque-texto-g__img(
    //-     :style="{'background-image': `url(${require_src('@/assets/curso/tema1/img10.png')})`}"
    //-   )
    //-   .bloque-texto-g__texto.p-4
    //-     p.mb-0 La inocuidad de los alimentos es la garantía de que un alimento no causará daño al consumidor cuando se prepare o ingiera de acuerdo con el uso al que se destina. Es, por tanto, un derecho fundamental de los consumidores y una responsabilidad ineludible de todos los actores de la cadena alimentaria, desde el productor primario hasta el consumidor final.



    //- p.mb-4 La falta de inocuidad tiene graves consecuencias:

    //- .row.justify-content-center.mb-5
    //-   .col-lg-6.col-xl-4.mb-4.mb-lg-4.mb-xl-0
    //-     .tarjeta-avatar-b.h-100
    //-       .tarjeta-avatar-b__img
    //-         img(src='@/assets/curso/tema1/img11.svg' alt='')
    //-       .tarjeta.bg-color-6.h-100
    //-         .p-4
    //-           p <strong>Para la salud pública:</strong> las Enfermedades Transmitidas por Alimentos (ETA) son una causa importante de morbilidad y mortalidad en todo el mundo. Pueden variar desde leves malestares estomacales hasta enfermedades crónicas graves e incluso la muerte.

    //-   .col-lg-6.col-xl-4.mb-4.mb-lg-4.mb-xl-0
    //-     .tarjeta-avatar-b.h-100
    //-       .tarjeta-avatar-b__img
    //-         img(src='@/assets/curso/tema1/img12.svg' alt='')
    //-       .tarjeta.bg-color-6.h-100
    //-         .p-4
    //-           p <strong>Para la economía:</strong> los brotes de ETA pueden generar costos enormes en atención médica, pérdida de productividad, demandas legales, retiro de productos del mercado y el cierre de empresas.

    //-   .col-lg-6.col-xl-4.mb-0.mb-lg-0.mb-xl-0
    //-     .tarjeta-avatar-b.h-100
    //-       .tarjeta-avatar-b__img
    //-         img(src='@/assets/curso/tema1/img13.svg' alt='')
    //-       .tarjeta.bg-color-6.h-100
    //-         .p-4
    //-           p <strong>Para la sociedad:</strong> generan desconfianza en el sistema alimentario y pueden afectar el comercio nacional e internacional.

    //- separador
    
    //- #t_1_3.titulo-segundo.color-acento-contenido(data-aos="flip-up")
    //-   h2 1.3 Relación de las BPM con otros prerrequisitos

    //- .row.align-items-center.mb-5
    //-   .col-lg-auto.d-none.d-lg-flex
    //-     img(src="@/assets/curso/tema1/img14.svg").mx-auto
    //-   .col-lg
    //-     p.mb-0 Las Buenas Prácticas de Manufactura (BPM) constituyen el cimiento de un sistema integral de gestión de la inocuidad y no un sistema aislado. Representan el primer eslabón y el más importante, sobre el cual se construyen otros programas prerrequisito y sistemas de calidad.


    //- .row.justify-content-center.mb-5
    //-   .col-lg-6.col-md-12.mb-4.mb-lg-0
    //-     .bg-color-2.p-4.h-100.br-15
    //-       .row.align-items-center.mb-0.h-100
    //-         .col-12.col-lg-auto.mb-3.mb-lg-0
    //-           img(src="@/assets/curso/tema1/img15.svg", style="max-width: 150px;").mx-auto
    //-         .col-lg
    //-           h4 POES (Procedimientos Operativos Estandarizados de Saneamiento): 
    //-           p.mb-0 Mientras que las BPM son un conjunto amplio de principios, los POES son procedimientos específicos y detallados que describen cómo llevar a cabo las tareas de limpieza y desinfección. Unas buenas BPM exigen que existan POES bien definidos y que se apliquen correctamente.

    //-   .col-lg-6.col-md-12.mb-4.mb-lg-0
    //-     .bg-color-2.p-4.h-100.br-15
    //-       .row.align-items-center.mb-0.h-100
    //-         .col-12.col-lg-auto.mb-3.mb-lg-0
    //-           img(src="@/assets/curso/tema1/img16.svg", style="max-width: 150px;").mx-auto
    //-         .col-lg
    //-           h4 HACCP (Análisis de Peligros y Puntos Críticos de Control):
    //-           p.mb-0 Este es un sistema preventivo de mayor complejidad que identifica peligros específicos y establece controles en puntos críticos para garantizar la inocuidad. Para que un sistema HACCP funcione, es absolutamente necesario que los prerrequisitos, como las BPM y los POES, estén sólidamente implementados. Sin una base sólida de BPM, el sistema HACCP se vuelve inestable e ineficaz.

    //- .row.justify-content-center.mb-5
    //-   .col-xl-4.col-lg-6.col-md-12.col-12.mb-4.mb-xl-0
    //-     .crd_hover_txt(data-aos="flip-left").tarjeta
    //-       .crd_hover_txt--img
    //-         figure
    //-           img(src="@/assets/curso/tema1/img17.png", alt="HACCP")
    //-       .crd_hover_txt--body
    //-         h4.mb-3.text-center Nivel superior
    //-         h4 Sistema de Análisis de Peligros y Puntos Críticos de Control (HACCP)
    //-         p.mb-0 Sistema preventivo orientado al control de peligros específicos en los puntos críticos del proceso, con el fin de garantizar la inocuidad de los alimentos.

    //-   .col-xl-4.col-lg-6.col-md-12.col-12.mb-4.mb-xl-0
    //-     .crd_hover_txt(data-aos="flip-left").tarjeta
    //-       .crd_hover_txt--img
    //-         figure
    //-           img(src="@/assets/curso/tema1/img18.png", alt="POES")
    //-       .crd_hover_txt--body
    //-         h4.mb-3.text-center Nivel intermedio
    //-         h4 Procedimientos Operativos Estandarizados de Saneamiento (POES)
    //-         p.mb-0 Comprenden los procedimientos específicos y documentados de limpieza y desinfección que permiten mantener las condiciones higiénico-sanitarias durante el proceso de producción de alimentos.

    //-   .col-xl-4.col-lg-6.col-md-12.col-12.mb-4.mb-xl-0
    //-     .crd_hover_txt(data-aos="flip-left").tarjeta
    //-       .crd_hover_txt--img
    //-         figure
    //-           img(src="@/assets/curso/tema1/img19.png", alt="BPM")
    //-       .crd_hover_txt--body
    //-         h4.mb-3.text-center Nivel base
    //-         h4 Buenas Prácticas de Manufactura (BPM)
    //-         p.mb-0 Establecen las condiciones higiénicas generales que deben cumplir la planta, el personal y los procesos de producción. Constituyen el fundamento obligatorio para la implementación de los sistemas de calidad e inocuidad alimentaria.


    //- .row.mb-5.justify-content-center.align-items-center
    //-   .col-lg-3.col-md-8.mb-0.mb-lg-0.order-2.order-lg-1
    //-     figure
    //-       img(src="@/assets/curso/tema1/img20.png", data-aos="zoom-in")
    //-   .col-lg-9.order-1.order-lg-2.mb-4.mb-lg-0
    //-     p.mb-4(data-aos="fade-right") Las <b>Buenas Prácticas de Manufactura (BPM)</b> constituyen la base sobre la cual se implementan los Procedimientos Operativos Estandarizados de Saneamiento (POES) y el sistema de Análisis de Peligros y Puntos Críticos de Control (HACCP). Esta relación permite fortalecer la gestión de la calidad e inocuidad alimentaria mediante la implementación progresiva de medidas preventivas y de control.

    //-     .cajon.bg-color-c1.p-4.mb-0
    //-       p.mb-0 Dentro de este sistema, las Buenas Prácticas de Manufactura se sustentan en cinco pilares fundamentales, los cuales representan las áreas críticas que toda empresa de alimentos debe gestionar para garantizar la inocuidad de sus productos. Estos pilares abarcan la infraestructura de la planta, los equipos y utensilios, el personal manipulador, las condiciones de saneamiento y el control de las materias primas. El cumplimiento de cada uno de estos pilares contribuye al funcionamiento integral del sistema y a la producción de alimentos seguros. A continuación, se presentan los cinco pilares de las Buenas Prácticas de Manufactura.


    //- .row.mb-5.justify-content-center.align-items-center
    //-   .col-lg-12
    //-     AcordionA(tipo="b" clase-tarjeta="tarjeta bg-color-c1")
    //-       div(titulo="Instalaciones físicas")
    //-         .row.align-items-center.justify-content-center
    //-           .col-lg-5.col-md-10.order-2.mb-0.mb-lg-0
    //-             figure
    //-               img(src="@/assets/curso/tema1/img21.png", data-aos="zoom-in").mx-auto
    //-           .col-lg-7.order-1.mb-3.mb-lg-0
    //-             p.mb-3 Las instalaciones físicas deben diseñarse y mantenerse en condiciones que faciliten la limpieza, la desinfección y la prevención de la contaminación durante la producción de alimentos.
    //-             p.mb-2 <b>Aspectos clave:</b>
    //-             ul.lista-ul
    //-               li 
    //-                 i.lista-ul__vineta(style="color: #8AB064")
    //-                 | Pisos, paredes y techos lisos e impermeables. 
    //-               li 
    //-                 i.lista-ul__vineta(style="color: #8AB064")
    //-                 | Iluminación y ventilación adecuadas. 
    //-               li 
    //-                 i.lista-ul__vineta(style="color: #8AB064")
    //-                 | Flujo del proceso sin contaminación cruzada. 

    //-       div(titulo="Equipos y utensilios")
    //-         .row.align-items-center.justify-content-center
    //-           .col-lg-5.col-md-10.order-2.mb-0.mb-lg-0
    //-             figure
    //-               img(src="@/assets/curso/tema1/img22.png", data-aos="zoom-in").mx-auto
    //-           .col-lg-7.order-1.mb-3.mb-lg-0
    //-             p.mb-3 Los equipos y utensilios deben estar fabricados con materiales apropiados y mantenerse en condiciones que garanticen la inocuidad de los alimentos y faciliten las operaciones de limpieza y desinfección.
    //-             p.mb-2 <b>Aspectos clave:</b>
    //-             ul.lista-ul
    //-               li 
    //-                 i.lista-ul__vineta(style="color: #8AB064")
    //-                 | Materiales lisos, resistentes y no tóxicos. 
    //-               li 
    //-                 i.lista-ul__vineta(style="color: #8AB064")
    //-                 | Fácil limpieza y desinfección. 
    //-               li 
    //-                 i.lista-ul__vineta(style="color: #8AB064")
    //-                 | Mantenimiento preventivo programado. 

    //-       div(titulo="Higiene del personal")
    //-         .row.align-items-center.justify-content-center
    //-           .col-lg-5.col-md-10.order-2.mb-0.mb-lg-0
    //-             figure
    //-               img(src="@/assets/curso/tema1/img23.png", data-aos="zoom-in").mx-auto
    //-           .col-lg-7.order-1.mb-3.mb-lg-0
    //-             p.mb-3 El personal manipulador debe adoptar hábitos de higiene que prevengan la contaminación de los alimentos durante todas las etapas del proceso productivo.
    //-             p.mb-2 <b>Aspectos clave:</b>
    //-             ul.lista-ul
    //-               li 
    //-                 i.lista-ul__vineta(style="color: #8AB064")
    //-                 | Uniforme completo y limpio. 
    //-               li 
    //-                 i.lista-ul__vineta(style="color: #8AB064")
    //-                 | Uñas cortas, sin esmalte ni joyas. 
    //-               li 
    //-                 i.lista-ul__vineta(style="color: #8AB064")
    //-                 | Lavado frecuente y correcto de manos. 

    //-       div(titulo="Saneamiento básico")
    //-         .row.align-items-center.justify-content-center
    //-           .col-lg-5.col-md-10.order-2.mb-0.mb-lg-0
    //-             figure
    //-               img(src="@/assets/curso/tema1/img24.png", data-aos="zoom-in").mx-auto
    //-           .col-lg-7.order-1.mb-3.mb-lg-0
    //-             p.mb-3 El saneamiento básico comprende las actividades orientadas a mantener condiciones sanitarias adecuadas en las instalaciones y procesos de producción.
    //-             p.mb-2 <b>Aspectos clave:</b>
    //-             ul.lista-ul
    //-               li 
    //-                 i.lista-ul__vineta(style="color: #8AB064")
    //-                 | POES documentados. 
    //-               li 
    //-                 i.lista-ul__vineta(style="color: #8AB064")
    //-                 | Control integrado de plagas. 
    //-               li 
    //-                 i.lista-ul__vineta(style="color: #8AB064")
    //-                 | Manejo de residuos y agua potable. 

    //-       div(titulo="Materias primas")
    //-         .row.align-items-center.justify-content-center
    //-           .col-lg-5.col-md-10.order-2.mb-0.mb-lg-0
    //-             figure
    //-               img(src="@/assets/curso/tema1/img25.png", data-aos="zoom-in").mx-auto
    //-           .col-lg-7.order-1.mb-3.mb-lg-0
    //-             p.mb-3 Las materias primas deben recibirse, almacenarse y controlarse adecuadamente para garantizar su calidad e inocuidad antes de incorporarlas al proceso productivo.
    //-             p.mb-2 <b>Aspectos clave:</b>
    //-             ul.lista-ul
    //-               li 
    //-                 i.lista-ul__vineta(style="color: #8AB064")
    //-                 | Recepción con inspección. 
    //-               li 
    //-                 i.lista-ul__vineta(style="color: #8AB064")
    //-                 | Almacenamiento por tipo (secos y fríos). 
    //-               li 
    //-                 i.lista-ul__vineta(style="color: #8AB064")
    //-                 | Rotación PEPS obligatoria. 


</template>

<script>
export default {
  name: 'Tema1',
  data: () => ({
    mostrarIndicadorTarjetaAudio: true,
  }),
}
</script>

<style lang="sass"></style>
