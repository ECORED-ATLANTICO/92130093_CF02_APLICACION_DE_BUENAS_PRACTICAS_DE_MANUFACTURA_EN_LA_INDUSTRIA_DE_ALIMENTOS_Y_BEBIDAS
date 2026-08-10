<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 3
      h1 Factores de contaminación de los alimentos


    .bg-full-width.bg-fondo-3.px-5.py-4
      img(src="@/assets/curso/tema3/img01.png", alt="")
    .row.justify-content-center.align-items-center.z-2.mb-5
      .col-lg-11(data-aos="fade-right")
        p.banner-text Para prevenir eficazmente la contaminación de los alimentos, es indispensable conocer los agentes que pueden comprometer su inocuidad. Los factores de contaminación corresponden a todos aquellos agentes o elementos que, al estar presentes en un alimento, pueden representar un riesgo para la salud del consumidor. Su identificación, clasificación y análisis constituyen la base para establecer las medidas preventivas y los controles necesarios en cada etapa del proceso productivo.

    separador
    
    #t_3_1.titulo-segundo.color-acento-contenido(data-aos="flip-up")
      h2 3.1 Clasificación de los peligros: físicos, químicos y biológicos



    .row.mb-5.justify-content-center.align-items-center
      .col-lg-6.col-md-10.mb-0.mb-lg-0.order-2.order-lg-2
        figure
          img(src="@/assets/curso/tema3/img02.png", data-aos="zoom-in")
      .col-lg-6.order-1.order-lg-1.mb-4.mb-lg-0

        p.mb-4 La inocuidad alimentaria clasifica los peligros en tres categorías principales, de acuerdo con su naturaleza: físicos, químicos y biológicos. Esta clasificación	n constituye un referente internacional y representa la base para la implementación del sistema de Análisis de Peligros y Puntos Críticos de Control (HACCP). Un mismo alimento puede estar expuesto a uno o varios tipos de peligros durante las diferentes etapas de la cadena alimentaria.

        .bg-color-0.p-4.br-15.mb-0
          p.mb-0 Los peligros físicos corresponden a materiales u objetos extraños que no deberían estar presentes en los alimentos y que pueden ocasionar lesiones al consumidor, como cortes en la cavidad oral, fracturas dentales, laceraciones en el tracto digestivo o asfixia. Entre las fuentes más comunes de este tipo de peligro se encuentran:


    .row.mb-5.justify-content-center.align-items-center
      .col-lg-12
        .bg-color-01.p-4.br-15
          p.mb-0 <b>Fuentes comunes en la planta</b>: los peligros físicos pueden originarse en diferentes elementos presentes durante la producción de alimentos. A continuación, se presentan algunas de las fuentes más comunes que pueden introducir objetos extraños en los alimentos y comprometer su inocuidad.



    .bg-full-width.bg-fondo-1
      .row.mb-5.justify-content-center.align-items-center
        .col-lg-4.mb-4.mb-lg-0.col-md-8.order-1.order-lg-1
          figure
            img(src="@/assets/curso/tema3/img03.png", data-aos="zoom-in")
        .col-lg-8.order-2.order-lg-2.col-md-12.mb-4.mb-lg-0
          SlyderF(columnas="col-lg-6 col-xl-6 col-md-12 col-sm-12 p-2")
            .tarjeta.tarjeta--blanca.shadow-sm.p-4.h-100
              .row.justify-content-center.mb-3
                .col-8
                  img(src='@/assets/curso/tema3/img05.svg' alt='', style="width: 100px; height: 100px; ").mx-auto
              h4.text-center Metal
              p.mb-0 Virutas de maquinaria (por desgaste o fricción), grapas de empaques, arandelas, tuercas, agujas (en carnes) y cuchillas rotas.

            .tarjeta.tarjeta--blanca.shadow-sm.p-4.h-100
              .row.justify-content-center.mb-3
                .col-8
                  img(src='@/assets/curso/tema3/img06.svg' alt='', style="width: 100px; height: 100px; ").mx-auto
              h4.text-center Vidrio
              p.mb-0 Bombillos rotos, termómetros de vidrio quebrados y envases de vidrio rotos en áreas de producción cercanas.

            .tarjeta.tarjeta--blanca.shadow-sm.p-4.h-100
              .row.justify-content-center.mb-3
                .col-8
                  img(src='@/assets/curso/tema3/img07.svg' alt='', style="width: 100px; height: 100px; ").mx-auto
              h4.text-center Plástico
              p.mb-0 Fragmentos de empaques, de guantes rotos, de cortinas de tiras y de cintas transportadoras.

            .tarjeta.tarjeta--blanca.shadow-sm.p-4.h-100
              .row.justify-content-center.mb-3
                .col-8
                  img(src='@/assets/curso/tema3/img08.svg' alt='', style="width: 100px; height: 100px; ").mx-auto
              h4.text-center Madera
              p.mb-0 De estibas en mal estado, palés y cajas de madera (cada vez más prohibidas en plantas de alimentos).

            .tarjeta.tarjeta--blanca.shadow-sm.p-4.h-100
              .row.justify-content-center.mb-3
                .col-8
                  img(src='@/assets/curso/tema3/img09.svg' alt='', style="width: 100px; height: 100px; ").mx-auto
              h4.text-center Piedras o huesos
              p.mb-0 De materias primas mal seleccionadas o procesadas (ej. en granos y frutas deshuesadas).

            .tarjeta.tarjeta--blanca.shadow-sm.p-4.h-100
              .row.justify-content-center.mb-3
                .col-8
                  img(src='@/assets/curso/tema3/img10.svg' alt='', style="width: 100px; height: 100px; ").mx-auto
              h4.text-center Objetos personales
              p.mb-0 Joyas (anillos, aretes), botones, monedas y lapiceros.



    .row.mb-5.justify-content-center.align-items-center
      .col-lg-12
        .bg-color-01.p-4.br-15
          p.mb-0 <b>Medidas preventivas</b>: Instalación de imanes, detectores de metales, tamices y filtros; mantenimiento preventivo de equipos; inspección de materias primas; políticas estrictas sobre objetos personales y prohibición de madera en áreas de producción; uso de materiales irrompibles y protectores para iluminación.


    .bloque-texto-g.bloque-texto-g--inverso.bg-color-04.p-3.p-sm-4.p-md-5.mb-5
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require_src('@/assets/curso/tema3/img10.png')})`}"
      )
      .bloque-texto-g__texto.p-4
        p.mb-0 Los peligros químicos son sustancias que pueden estar presentes en los alimentos de forma accidental o intencional (pero no declarada) y causar intoxicaciones agudas o enfermedades crónicas. Su presencia puede originarse en diferentes etapas de la cadena productiva, por lo que es fundamental identificar sus fuentes y establecer medidas de control adecuadas. Entre los peligros químicos más comunes se encuentran: 


    .row.mb-5.justify-content-center.align-items-center
      .col-lg-12
        .bg-color-01.p-4.br-15
          p.mb-0 <b>Clasificación y fuentes comunes</b>: los peligros químicos pueden clasificarse según su origen y las fuentes que los generan durante la producción, el almacenamiento o la manipulación de los alimentos. A continuación, se presentan algunas de las fuentes más comunes de contaminación química que pueden comprometer la inocuidad alimentaria.


    .bg-full-width.bg-fondo-1
      .row.mb-5.justify-content-center.align-items-center
        .col-lg-4.mb-4.mb-lg-0.col-md-8.order-1.order-lg-1
          figure
            img(src="@/assets/curso/tema3/img11.png", data-aos="zoom-in")
        .col-lg-8.order-2.order-lg-2.col-md-12.mb-4.mb-lg-0
          SlyderF(columnas="col-lg-6 col-xl-6 col-md-12 col-sm-12 p-2")
            .tarjeta.tarjeta--blanca.shadow-sm.p-0.h-100
              img(src='@/assets/curso/tema3/img12.png' alt='').mx-auto
              .p-4
                h4.text-center Químicos de limpieza
                p.mb-0 Residuos de detergentes, desengrasantes o desinfectantes por enjuague deficiente después de la limpieza.

            .tarjeta.tarjeta--blanca.shadow-sm.p-0.h-100
              img(src='@/assets/curso/tema3/img13.png' alt='').mx-auto
              .p-4
                h4.text-center Lubricantes y mantenimiento
                p.mb-0 Fugas de aceites o grasas de equipos, especialmente si no son de grado alimenticio (NSF H1).

            .tarjeta.tarjeta--blanca.shadow-sm.p-0.h-100
              img(src='@/assets/curso/tema3/img14.png' alt='').mx-auto
              .p-4
                h4.text-center Plaguicidas y agroquímicos
                p.mb-0 Residuos en materias primas por malas prácticas agrícolas.

            .tarjeta.tarjeta--blanca.shadow-sm.p-0.h-100
              img(src='@/assets/curso/tema3/img15.png' alt='').mx-auto
              .p-4
                h4.text-center Toxinas naturales
                p.mb-0 Micotoxinas (aflatoxinas en granos, ocratoxinas en café), histamina (en pescado mal refrigerado), toxinas en hongos o mariscos.

            .tarjeta.tarjeta--blanca.shadow-sm.p-0.h-100
              img(src='@/assets/curso/tema3/img16.png' alt='').mx-auto
              .p-4
                h4.text-center Aditivos no permitidos o en exceso
                p.mb-0 Uso de conservantes, colorantes o saborizantes no autorizados, o en cantidades superiores a las permitidas.

            .tarjeta.tarjeta--blanca.shadow-sm.p-0.h-100
              img(src='@/assets/curso/tema3/img17.png' alt='').mx-auto
              .p-4
                h4.text-center Alérgenos
                p.mb-0 Proteínas de alimentos como maní, leche, huevo, soya, trigo (gluten), crustáceos, pescado, nueces, que pueden contaminar otros productos de forma cruzada (cambio de línea de producción sin limpieza profunda), generando un peligro grave para personas alérgicas.


    .row.mb-4.justify-content-center.align-items-center
      .col-lg-12
        .bg-color-01.p-4.br-15
          p.mb-0 <b>Medidas preventivas</b>: almacenamiento separado y etiquetado claro de químicos; uso exclusivo de lubricantes de grado alimenticio (NSF H1); procedimientos de limpieza (POES) que aseguren el enjuague; control de proveedores y análisis de materias primas; programas de manejo de alérgenos que incluyan limpieza profunda entre producciones, secuenciación de productos y etiquetado claro.

    p.mb-5 Los peligros biológicos son organismos vivos, generalmente microscópicos, que pueden multiplicarse en los alimentos y causar enfermedades. Constituyen la causa más frecuente y peligrosa de los brotes de Enfermedades Transmitidas por Alimentos (ETA), debido a su capacidad para sobrevivir o proliferar cuando las condiciones de procesamiento, almacenamiento o manipulación no son las adecuadas.


    .row.mb-5.justify-content-center.align-items-center
      .col-lg-12
        AcordionA(tipo="b" clase-tarjeta="tarjeta bg-color-03 bg-color-nuevo")
          div(titulo="Bacterias")
            .row.align-items-center.justify-content-center
              .col-lg-5.col-md-10.order-2.mb-0.mb-lg-0
                figure
                  img(src="@/assets/curso/tema3/img18.png", data-aos="zoom-in").mx-auto
              .col-lg-7.order-1.mb-4.mb-lg-0
                p.mb-3 Microorganismos unicelulares. Pueden ser patógenas (causan enfermedad) o saprofitas (descomponen el alimento). Algunas forman esporas resistentes al calor (ej. Clostridium botulinum, Bacillus cereus).
                p.mb-0 <b>Ejemplos clave:</b> Salmonella, Listeria monocytogenes, Escherichia coli patógena (STEC), Campylobacter jejuni y Staphylococcus aureus (produce toxina).

          div(titulo="Virus")
            .row.align-items-center.justify-content-center
              .col-lg-5.col-md-10.order-2.mb-0.mb-lg-0
                figure
                  img(src="@/assets/curso/tema3/img19.png", data-aos="zoom-in").mx-auto
              .col-lg-7.order-1.mb-4.mb-lg-0
                p.mb-3 Más pequeños que las bacterias, necesitan una célula huésped para multiplicarse. No se multiplican en los alimentos, pero pueden sobrevivir en ellos. Se transmiten principalmente por contaminación fecal de manipuladores o agua.
                p.mb-0 <b>Ejemplos clave:</b> virus de la hepatitis A, norovirus y rotavirus.

          div(titulo="Parásitos")
            .row.align-items-center.justify-content-center
              .col-lg-5.col-md-10.order-2.mb-0.mb-lg-0
                figure
                  img(src="@/assets/curso/tema3/img20.png", data-aos="zoom-in").mx-auto
              .col-lg-7.order-1.mb-4.mb-lg-0
                p.mb-3 Organismos que viven a expensas de otro organismo. Se ingieren a través de alimentos contaminados, principalmente carnes crudas o mal cocidas, pescado crudo o agua contaminada.
                p.mb-0 <b>Ejemplos clave:</b> Taenia solium (solitaria), Trichinella spiralis, Cryptosporidium parvum y Toxoplasma gondii.

          div(titulo="Hongos y levaduras")
            .row.align-items-center.justify-content-center
              .col-lg-5.col-md-10.order-2.mb-0.mb-lg-0
                figure
                  img(src="@/assets/curso/tema3/img21.png", data-aos="zoom-in").mx-auto
              .col-lg-7.order-1.mb-4.mb-lg-0
                p.mb-0 Aunque muchos son utilizados en la industria (pan, queso y cerveza), algunos producen micotoxinas (peligro químico). Su presencia en alimentos también puede indicar malas prácticas de almacenamiento.


    .row.mb-5.justify-content-center.align-items-center
      .col-lg-12.col-md-12.mb-0.mb-lg-0
        .titulo-sexto.color-acento-contenido.mb-3
          h5 
            b Tabla 3.
          span Comparación de los tipos de peligros biológicos
        .tabla-a.color-acento-contenido.tb-custom.mb-0
          table
            caption <span style="font-weight: normal">Nota. SENA, (2026).</span>
            thead
              tr
                th Característica
                th Bacterias
                th Virus
                th Parásitos
            tbody
              tr
                td Tamaño
                td Generalmente entre 1 y 5 μm.
                td Mucho más pequeños (20-300 nm).
                td Visibles al microscopio, algunos a simple vista.
              tr
                td Multiplicación en alimentos
                td Sí, pueden multiplicarse rápidamente.
                td No, solo sobreviven.
                td No, generalmente no se multiplican en el alimento.
              tr
                td Transmisión común
                td Alimentos crudos, contaminación cruzada.
                td Manipuladores infectados, agua contaminada.
                td Carnes y pescados crudos o mal cocidos, agua.
              tr
                td Ejemplo clave
                td Salmonella en pollo.
                td Hepatitis A en vegetales lavados con agua contaminada.
                td Taenia solium en carne de cerdo mal cocida.

    separador
    
    #t_3_2.titulo-segundo.color-acento-contenido(data-aos="flip-up")
      h2 3.2 Fuentes y rutas de contaminación en la cadena productiva



    .row.mb-5.justify-content-center.align-items-center
      .col-lg-4.col-md-10.mb-0.mb-lg-0.order-2.order-lg-1
        figure
          img(src="@/assets/curso/tema3/img22.png", data-aos="zoom-in")
      .col-lg-8.order-1.order-lg-2.mb-4.mb-lg-0

        p.mb-4 La contaminación de los alimentos puede presentarse en cualquier etapa de la cadena productiva, desde la producción primaria (el campo o la granja) hasta el consumidor final. Para prevenirla, es fundamental comprender las fuentes de contaminación y las rutas mediante las cuales los contaminantes pueden transferirse de un lugar a otro.

        .bg-color-02.p-4.br-15.mb-0
          p.mb-3 Una de las formas de contaminación corresponde a la contaminación primaria o directa, la cual ocurre cuando el peligro proviene directamente de la fuente del alimento o de su entorno natural inmediato. Algunos ejemplos son:
          ul.lista-ul--color.mb-0
            li 
              i.fas.fa-circle-check
              | Una fruta contaminada con residuos de plaguicidas en el campo. 
            li 
              i.fas.fa-circle-check
              | Un pescado que contiene parásitos de forma natural (anisakis). 
            li 
              i.fas.fa-circle-check
              | Un huevo contaminado con Salmonella desde el interior de la gallina. 
            li 
              i.fas.fa-circle-check
              | Granos que desarrollan micotoxinas debido a condiciones inadecuadas de humedad durante el cultivo o el almacenamiento primario. 

    p.mb-5 Por otra parte, la contaminación cruzada corresponde a la transferencia de peligros desde una superficie, alimento o persona contaminada hacia otro alimento que inicialmente no se encontraba contaminado. Constituye una de las causas más frecuentes y prevenibles de las enfermedades transmitidas por alimentos (ETA), y generalmente se origina por fallas en los programas de saneamiento o por el incumplimiento de las Buenas Prácticas de Manufactura.
    
    .row.mb-5.justify-content-center.align-items-center
      .col-lg-12.col-md-12.mb-0.mb-lg-0
        .bg-color-0.p-4.br-15.mb-0
          .row.align-items-center.justify-content-center
            .col-lg-8.mb-4.mb-lg-0
              p.mb-3 Las principales rutas de contaminación cruzada son:
              ul.lista-ul--color.mb-0
                li 
                  i.fas.fa-circle-check
                  | <b>De alimento a alimento:</b> ocurre cuando un alimento crudo, como el pollo, gotea sobre un alimento listo para el consumo, como una ensalada, durante el almacenamiento en refrigeración o la preparación sobre la misma superficie. 
                li 
                  i.fas.fa-circle-check
                  | <b>De superficie a alimento:</b> ocurre cuando un alimento cocido se corta sobre la misma tabla utilizada previamente para cortar pollo crudo, sin realizar el proceso de limpieza y desinfección entre usos. También puede presentarse cuando un alimento listo para el consumo entra en contacto con mesas, recipientes o cuchillos que no han sido adecuadamente higienizados. 
                li 
                  i.fas.fa-circle-check
                  | <b>Del manipulador al alimento:</b> ocurre cuando el personal manipula alimentos listos para el consumo sin realizar previamente el lavado de manos después de utilizar los servicios sanitarios, manipular dinero o tocarse el cabello o el rostro. Las manos constituyen uno de los principales vehículos de contaminación cruzada. 
                li 
                  i.fas.fa-circle-check
                  | <b>Del ambiente al alimento:</b> ocurre cuando partículas de polvo, salpicaduras de agua contaminada, aerosoles generados durante las actividades de limpieza o corrientes de aire transportan contaminantes desde áreas sucias hacia áreas limpias.

            .col-lg-4.col-md-8.mb-0
              figure
                img(src="@/assets/curso/tema3/img23.png", data-aos="zoom-in").mx-auto


    .row.mb-5.justify-content-center.align-items-center
      .col-lg-12.col-md-12.mb-0.mb-lg-0
        .bg-fondo-5.p-4
          SlyderA(tipo="b").bg-color-white.p-3.tarjeta
            .tarjeta.p-4.h-100.mb-0
              .row.align-items-center.justify-content-center
                .col-lg-4.col-md-10.order-2.order-lg-1.mb-0.mb-lg-0
                  figure
                    img(src="@/assets/curso/tema3/img24.png", data-aos="zoom-in").mx-auto
                .col-lg-8.order-1.order-lg-2.mb-4.mb-lg-0
                  h4 Fuente contaminada
                  p.mb-3 La contaminación cruzada inicia con una fuente que contiene un peligro físico, químico o biológico.
                  p.mb-3.text-bold Ejemplos
                  ul.lista-ul--color.mb-0
                    li 
                      i.fas.fa-circle-check
                      | Pollo crudo. 
                    li 
                      i.fas.fa-circle-check
                      | Manipulador con manos sucias. 
                    li 
                      i.fas.fa-circle-check
                      | Superficie contaminada. 

            .tarjeta.p-4.h-100.mb-0
              .row.align-items-center.justify-content-center
                .col-lg-4.col-md-10.order-2.order-lg-1.mb-0.mb-lg-0
                  figure
                    img(src="@/assets/curso/tema3/img25.png", data-aos="zoom-in").mx-auto
                .col-lg-8.order-1.order-lg-2.mb-4.mb-lg-0
                  h4 Mecanismo de transferencia
                  p.mb-3 El peligro se transfiere mediante contacto directo o a través de diferentes mecanismos.
                  p.mb-3.text-bold Ejemplos
                  ul.lista-ul--color.mb-0
                    li 
                      i.fas.fa-circle-check
                      | Contacto directo. 
                    li 
                      i.fas.fa-circle-check
                      | Goteo. 
                    li 
                      i.fas.fa-circle-check
                      | Salpicaduras. 
                    li 
                      i.fas.fa-circle-check
                      | Aerosoles. 
                    li 
                      i.fas.fa-circle-check
                      | Manos sucias. 

            .tarjeta.p-4.h-100.mb-0
              .row.align-items-center.justify-content-center
                .col-lg-4.col-md-10.order-2.order-lg-1.mb-0.mb-lg-0
                  figure
                    img(src="@/assets/curso/tema3/img26.png", data-aos="zoom-in").mx-auto
                .col-lg-8.order-1.order-lg-2.mb-4.mb-lg-0
                  h4 Alimento vulnerable
                  p.mb-3 El peligro alcanza un alimento que inicialmente no estaba contaminado.
                  p.mb-3.text-bold Ejemplos
                  ul.lista-ul--color.mb-0
                    li 
                      i.fas.fa-circle-check
                      | Alimento listo para consumo. 
                    li 
                      i.fas.fa-circle-check
                      | Producto cocido. 

            .tarjeta.p-4.h-100.mb-0
              .row.align-items-center.justify-content-center
                .col-lg-4.col-md-10.order-2.order-lg-1.mb-0.mb-lg-0
                  figure
                    img(src="@/assets/curso/tema3/img27.png", data-aos="zoom-in").mx-auto
                .col-lg-8.order-1.order-lg-2.mb-4.mb-lg-0
                  h4 Resultado
                  p.mb-3 Como consecuencia de la transferencia del peligro, el alimento queda contaminado.
                  p.mb-3.text-bold Ejemplos
                  ul.lista-ul--color.mb-0
                    li 
                      i.fas.fa-circle-check
                      | Peligro transferido. 
                    li 
                      i.fas.fa-circle-check
                      | Alimento contaminado. 
                  
    separador
    
    #t_3_3.titulo-segundo.color-acento-contenido(data-aos="flip-up")
      h2 3.3 Enfermedades Transmitidas por Alimentos (ETA): un enfoque en los peligros biológicos



    .row.mb-5.justify-content-center.align-items-center
      .col-lg-5.col-md-10.mb-0.mb-lg-0.order-2.order-lg-2
        figure
          img(src="@/assets/curso/tema3/img28.png", data-aos="zoom-in")
      .col-lg-7.order-1.order-lg-1.mb-4.mb-lg-0


        .bg-color-02.p-4.br-15.mb-4
          p.mb-0 Las ETA se definen como el síndrome originado por la ingestión de alimentos o agua que contienen agentes biológicos o químicos en cantidades tales que afectan la salud del consumidor. Los síntomas más comunes incluyen vómito, diarrea, fiebre, dolor abdominal y, en casos graves, deshidratación severa, daño neurológico, insuficiencia renal e incluso la muerte. Aunque para una persona sana una ETA puede ser una molestia pasajera, en poblaciones vulnerables (niños, ancianos, mujeres embarazadas y personas inmunodeprimidas) pueden tener consecuencias devastadoras y a menudo fatales.


        p.mb-0 Dentro de los peligros biológicos, las bacterias patógenas son los responsables de la mayoría de los brotes. La característica más peligrosa de muchas de ellas es su capacidad de multiplicarse rápidamente en el alimento si este se encuentra en la "zona de peligro" de temperaturas (entre 5 °C y 60 °C). Una sola bacteria presente en un alimento puede convertirse en millones en pocas horas si no se controla la temperatura de almacenamiento. Es crucial conocer las principales:


    .bg-full-width.bg-fondo-1
      .row.justify-content-center.mb-5
        .col-md-12.col-lg-10.col-xl-10.mb-4
          .tarjeta-avatar-b.h-100
            .tarjeta-avatar-b__img
              img(src='@/assets/curso/tema3/img29.svg' alt='')
            .tarjeta.bg-color-01.h-100
              .px-2.py-3
                p.mb-0.p-1 <b>Salmonella spp:</b> asociada a huevos crudos, pollo, carne, leche no pasteurizada, productos lácteos, vegetales contaminados. Causa salmonelosis: diarrea, fiebre, calambres abdominales.

        .col-md-12.col-lg-10.col-xl-10.mb-4
          .tarjeta-avatar-b.h-100
            .tarjeta-avatar-b__img
              img(src='@/assets/curso/tema3/img29.svg' alt='')
            .tarjeta.bg-color-01.h-100
              .px-2.py-3
                p.mb-0.p-1 <b>Listeria monocytogenes:</b> bacteria ambiental ubicua. Crece en refrigeración (psicotrofa). Asociada a lácteos no pasteurizados, carnes frías, patés, pescados ahumados, vegetales listos para consumo. Es especialmente peligrosa en embarazadas (abortos) y ancianos (meningitis).

        .col-md-12.col-lg-10.col-xl-10.mb-4
          .tarjeta-avatar-b.h-100
            .tarjeta-avatar-b__img
              img(src='@/assets/curso/tema3/img29.svg' alt='')
            .tarjeta.bg-color-01.h-100
              .px-2.py-3
                p.mb-0.p-1 <b>Escherichia coli:</b> productor de toxina Shiga (STEC), como O157:H7: asociada a carne molida mal cocida, leche sin pasteurizar, jugos no pasteurizados, vegetales regados con agua contaminada. Causa diarrea con sangre y puede derivar en Síndrome Urémico Hemolítico (insuficiencia renal).

        .col-md-12.col-lg-10.col-xl-10.mb-4
          .tarjeta-avatar-b.h-100
            .tarjeta-avatar-b__img
              img(src='@/assets/curso/tema3/img29.svg' alt='')
            .tarjeta.bg-color-01.h-100
              .px-2.py-3
                p.mb-0.p-1 <b>Campylobacter jejuni:</b> una de las causas más comunes de diarrea bacteriana. Asociada a pollo crudo o mal cocido, leche no pasteurizada, agua no tratada.

        .col-md-12.col-lg-10.col-xl-10.mb-4
          .tarjeta-avatar-b.h-100
            .tarjeta-avatar-b__img
              img(src='@/assets/curso/tema3/img29.svg' alt='')
            .tarjeta.bg-color-01.h-100
              .px-2.py-3
                p.mb-0.p-1 <b>Staphylococcus aureus:</b> bacteria que vive en la piel y fosas nasales humanas. Produce una toxina termoestable (resiste la cocción) en los alimentos si se dejan a temperatura ambiente. Asociada a alimentos manipulados por personas y luego mal refrigerados (ensaladas de papa, cremas, carnes frías). Causa vómitos violentos horas después del consumo.

        .col-md-12.col-lg-10.col-xl-10.mb-4
          .tarjeta-avatar-b.h-100
            .tarjeta-avatar-b__img
              img(src='@/assets/curso/tema3/img29.svg' alt='')
            .tarjeta.bg-color-01.h-100
              .px-2.py-3
                p.mb-0.p-1 <b>Clostridium botulinum:</b> bacteria formadora de esporas (resistentes al calor) que produce una toxina letal para el sistema nervioso (neurotoxina). Asociada a alimentos enlatados de baja acidez mal procesados (verduras, carnes, pescados), conservas caseras, miel (en bebés). Causa visión borrosa, parálisis muscular, fallo respiratorio.

        .col-md-12.col-lg-10.col-xl-10.mb-0
          .tarjeta-avatar-b.h-100
            .tarjeta-avatar-b__img
              img(src='@/assets/curso/tema3/img29.svg' alt='')
            .tarjeta.bg-color-01.h-100
              .px-2.py-3
                p.mb-0.p-1 <b>Bacillus cereus:</b> bacteria formadora de esporas. Asociada a dos tipos de intoxicación: una diarreica (por verduras, carnes, salsas) y una emética (vómito, asociada a arroz recalentado).


    .row.mb-5.justify-content-center.align-items-center
      .col-lg-5.col-md-10.mb-0.mb-lg-0.order-1.order-lg-1
        figure
          img(src="@/assets/curso/tema3/img30.png", data-aos="zoom-in")
      .col-lg-7.order-2.order-lg-2.mb-4.mb-lg-0

        p.mb-3 Además de las bacterias, los virus y parásitos también representan una importante causa de enfermedades transmitidas por alimentos:

        AcordionA(tipo="b" clase-tarjeta="tarjeta bg-color-03 bg-color-nuevo").mb-0
          div(titulo="Virus")
            p.mb-0 El virus de la Hepatitis A causa inflamación del hígado y se asocia a alimentos contaminados por manipuladores infectados (ej. ensaladas, sándwiches, frutas congeladas). El Norovirus es altamente contagioso y causa gastroenteritis aguda; se propaga rápidamente en lugares con alta densidad de personas (cruceros, restaurantes) a través de alimentos contaminados.

          div(titulo="Parásitos")
            p.mb-0 La Taenia solium (solitaria) se adquiere por consumo de carne de cerdo mal cocida. Trichinella spiralis se adquiere por consumo de carne de cerdo o de animales silvestres mal cocida. Cryptosporidium se asocia a agua contaminada y a vegetales frescos.


    
    .row.mb-5.justify-content-center.align-items-center
      .col-lg-3.col-md-8.mb-0.mb-lg-0.order-2.order-lg-2.d-none.d-lg-block
        figure
          img(src="@/assets/curso/tema3/img31.png", data-aos="zoom-in")
      .col-lg-9.order-1.order-lg-1.mb-0.mb-lg-0
        p.mb-4 La aparición de brotes de ETA no ocurre por casualidad; son el resultado de fallas en los controles. Los factores más comunes identificados por las autoridades sanitarias incluyen:

        ol.lista-ol--cuadro.lista-ol--separador.ps-3.ps-md-4
          li.d-flex.align-items-start
            .lista-ol--cuadro__vineta
              span A
            div.ms-2 Temperaturas inadecuadas de conservación: mantener los alimentos perecederos en la zona de peligro entre 5 °C y 60 °C por tiempo prolongado.
          li.d-flex.align-items-start
            .lista-ol--cuadro__vineta
              span B
            div.ms-2 Cocción insuficiente: no alcanzar la temperatura interna necesaria para matar los patógenos.
          li.d-flex.align-items-start
            .lista-ol--cuadro__vineta
              span C
            div.ms-2 Contaminación cruzada: transferir patógenos de alimentos crudos a alimentos cocidos o listos para consumir.
          li.d-flex.align-items-start
            .lista-ol--cuadro__vineta
              span D
            div.ms-2 Malas prácticas de higiene del personal: manipuladores enfermos o con mala higiene de manos.
          li.d-flex.align-items-start
            .lista-ol--cuadro__vineta
              span E
            div.ms-2 Materias primas contaminadas: recibir ingredientes que ya vienen contaminados del proveedor.
          li.d-flex.align-items-start
            .lista-ol--cuadro__vineta
              span F
            div.ms-2 Enfriamiento inadecuado: enfriar grandes volúmenes de alimentos cocidos muy lentamente, permitiendo el crecimiento bacteriano.
          li.d-flex.align-items-start
            .lista-ol--cuadro__vineta
              span G
            div.ms-2 Alimentos de alto riesgo: consumir alimentos crudos o poco cocidos de origen animal (ostiones, leche sin pasteurizar, carnes crudas).







    //- .bg-full-width.bg-fondo-3.px-5.py-4h4 
    //-   img(src="@/assets/curso/tema3/img01.png", alt="")
    //- .row.justify-content-center.align-items-center.z-2.mb-5
    //-   .col-lg-11(data-aos="fade-right")
    //-     p.banner-text "Lo que no se registra, no se hace". Esta frase es un lema fundamental en la industria alimentaria. La planeación del registro de información es tan importante como la ejecución misma de las tareas. Los registros son la evidencia objetiva del cumplimiento y la herramienta principal para verificar, rastrear y mejorar los procesos. 

    //- separador

    //- .bg-full-width.bg-fondo-1
    
    //-   #t_3_1.titulo-segundo.color-acento-contenido(data-aos="flip-up")
    //-     h2 3.1 Concepto de programa de saneamiento: objetivos y estructura


    
    //-   .row.mb-5.justify-content-center.align-items-center
    //-     .col-lg-6.col-md-12.mb-4.mb-lg-0.order-1.order-lg-1
    //-       figure
    //-         img(src="@/assets/curso/tema3/img02.png", data-aos="zoom-in")
    //-     .col-lg-6.order-2.order-lg-2
    //-       p.mb-3 Un Programa de Saneamiento es un documento formal, planificado y sistemático que reúne todas las actividades y procedimientos necesarios para mantener las condiciones higiénicas y sanitarias en un establecimiento de alimentos. Su objetivo principal es prevenir la contaminación de los alimentos, protegiendo así la salud del consumidor.
    //-       p.mb-0 Todo programa de saneamiento debe estar documentado y debe incluir, al menos, cuatro subprogramas o componentes esenciales:
      
    //- .row.justify-content-center.mb-5
    //-   .col-xl-3.col-lg-6.col-md-12.col-12.mb-4.mb-xl-0
    //-     .crd_hover_txt(data-aos="flip-left").tarjeta
    //-       .crd_hover_txt--img
    //-         figure
    //-           img(src="@/assets/curso/tema3/img03.png", alt="Programa de limpieza y desinfección")
    //-       .crd_hover_txt--body.bg-color-2.pd-1-2
    //-         h4.mb-3.text-center Programa de limpieza y desinfección
    //-         p.mb-0 Establece los procedimientos estandarizados de limpieza y desinfección de instalaciones, equipos y utensilios. Incluye fichas técnicas, concentraciones, frecuencias y responsables de cada actividad. Su eficacia se verifica mediante inspección visual, pruebas de ATP o análisis microbiológicos.

    //-   .col-xl-3.col-lg-6.col-md-12.col-12.mb-4.mb-xl-0
    //-     .crd_hover_txt(data-aos="flip-left").tarjeta
    //-       .crd_hover_txt--img
    //-         figure
    //-           img(src="@/assets/curso/tema3/img04.png", alt="Programa de control de plagas y vectores")
    //-       .crd_hover_txt--body.bg-color-2.pd-1-2
    //-         h4.mb-3.text-center Programa de control de plagas y vectores
    //-         p.mb-0 Comprende las actividades de manejo integrado de plagas (MIP), incluyendo monitoreo, medidas preventivas, controles físicos y químicos realizados por empresas autorizadas y el registro de las intervenciones.

    //-   .col-xl-3.col-lg-6.col-md-12.col-12.mb-4.mb-xl-0
    //-     .crd_hover_txt(data-aos="flip-left").tarjeta
    //-       .crd_hover_txt--img
    //-         figure
    //-           img(src="@/assets/curso/tema3/img05.png", alt="Programa de abastecimiento de agua potable")
    //-       .crd_hover_txt--body.bg-color-2.pd-1-2
    //-         h4.mb-3.text-center Programa de abastecimiento de agua potable
    //-         p.mb-0 Garantiza que el agua utilizada durante la producción cumpla con los requisitos de potabilidad mediante controles periódicos, mantenimiento de tanques y análisis fisicoquímicos y microbiológicos.

    //-   .col-xl-3.col-lg-6.col-md-12.col-12.mb-4.mb-xl-0
    //-     .crd_hover_txt(data-aos="flip-left").tarjeta
    //-       .crd_hover_txt--img
    //-         figure
    //-           img(src="@/assets/curso/tema3/img06.png", alt="Programa de manejo de residuos sólidos y líquidos")
    //-       .crd_hover_txt--body.bg-color-2.pd-1-2
    //-         h4.mb-3.text-center Programa de manejo de residuos sólidos y líquidos
    //-         p.mb-0 Establece los procedimientos para la separación en la fuente, el almacenamiento temporal, la recolección y la disposición final de los residuos generados durante el proceso productivo.



    //-   separador
    
    //- #t_3_2.titulo-segundo.color-acento-contenido(data-aos="flip-up")
    //-   h2 3.2 Tipos de formatos y registros: características y criterios de diligenciamiento

    //- .container
    //-   .row.align-items-center.bg-color-9.br-15.p-3.mb-5
    //-     .col-lg-auto.d-none.d-lg-flex
    //-       img(src="@/assets/curso/tema3/img07.svg").mx-auto
    //-     .col-lg
    //-       p.mb-0 Para planear el registro, es necesario diseñar los formatos adecuados. Un formato es el documento prediseñado que será diligenciado. Un registro es el formato ya diligenciado, que contiene datos y evidencia de una actividad realizada.


    //- p.mb-5 Características de un buen formato:
  
    //- .row.mb-4.justify-content-center.align-items-center
    //-   .col-lg-6.col-md-12.mb-4.mb-lg-0.order-1.order-lg-1
    //-     figure
    //-       img(src="@/assets/curso/tema3/img09.png", data-aos="zoom-in")
    //-   .col-lg-6.order-2.order-lg-2
    //-     p.mb-3 <b>Claro y sencillo:</b> debe ser fácil de entender para quien lo diligencie.
    //-     p.mb-3 <b>Identificable:</b> debe tener un código, nombre y fecha de versión únicos.
    //-     p.mb-3 <b>Estructurado:</b> debe tener espacios definidos para la información requerida (fecha, hora, actividad, responsable, observaciones, etc.).
    //-     p.mb-0 <b>Con campos para verificación:</b> debe permitir dejar constancia de que se realizó una actividad y que se cumplió con el parámetro esperado (ej. Casillas de verificación, espacios para anotar una medición).

    //- p.mb-5 Criterios para el correcto diligenciamiento de registros:

    //- .row.justify-content-center.mb-3
    //-   .col-lg-8.mb-0
    //-     AcordionA(tipo="b" clase-tarjeta="tarjeta bg-color-3 bg-color-nuevo")
    //-       div(titulo="Uso de lápiz")
    //-         p.mb-3 Un registro diligenciado con lápiz, con información borrosa, manchada y poco clara. Con el tiempo, la información puede perderse o alterarse.
    //-         p.mb-0 <b>Acción correcta:</b> utilizar siempre bolígrafo de tinta azul o negra. La tinta es permanente e indeleble, lo que garantiza que la información perdure en el tiempo y no pueda ser alterada.

    //-       div(titulo="Uso de corrector")
    //-         p.mb-3 Un formato en el que se utilizó corrector líquido (blanquero) para tapar un error. Esto genera desconfianza y puede interpretarse como un intento de ocultar información.
    //-         p.mb-0 <b>Acción correcta:</b> tachar el error con una línea horizontal (dejando visible el dato incorrecto), escribir el dato correcto al lado o encima, y firmar o colocar las iniciales de quien realiza la corrección.

    //-       div(titulo="Registro fuera de tiempo")
    //-         p.mb-3 Un formato diligenciado al final del día, con información genérica como "todo bien" o "todo en orden", sin horarios específicos ni detalles de las actividades realizadas.
    //-         p.mb-0 <b>Acción correcta:</b> diligenciar el registro en el momento exacto en que se realiza la actividad. Ejemplo: "10:30 a. m. - Inicio de pasteurización, temperatura: 72 °C; 11:00 a. m. - Verificación, temperatura: 72 °C."

    //-       div(titulo="Información incompleta")
    //-         p.mb-3 Un formato con espacios en blanco para datos fundamentales, como la fecha, la hora, el nombre del responsable o la firma de verificación.
    //-         p.mb-0 <b>Acción correcta:</b> asegurarse de que todo registro incluya y diligencie los campos obligatorios: fecha completa, hora exacta, nombre completo y legible, firma del responsable y, cuando aplique, visto bueno del supervisor.

    //-   .col-lg-4.col-md-8.mb-0
    //-     img(src="@/assets/curso/tema3/img10.png", data-aos="zoom-in")

    //- separador
    
    //- #t_3_3.titulo-segundo.color-acento-contenido(data-aos="flip-up")
    //-   h2 3.3 Elaboración de un plan de muestreo: técnicas, tamaños y conservación de muestras

    //- .row.align-items-center.mb-5
    //-   .col-lg-auto.d-none.d-lg-flex
    //-     img(src="@/assets/curso/tema3/img11.svg").mx-auto
    //-   .col-lg
    //-     p.mb-0 El muestreo es una actividad clave para verificar la calidad y la inocuidad de los insumos, los productos en proceso y los productos terminados. Planear el muestreo implica definir un "plan de muestreo", que es un protocolo que establece:

    //- .row.mb-5.justify-content-center.align-items-center
    //-   .col-lg-6.col-md-10.mb-4.mb-lg-0.order-1.order-lg-1
    //-     figure
    //-       img(src="@/assets/curso/tema3/img12.png", data-aos="zoom-in")
    //-   .col-lg-6.col-md-12.order-2.order-lg-2
    //-     .bg-fondo-5.p-4
    //-       SlyderA(tipo="b").bg-color-white.p-3.tarjeta
    //-         .tarjeta.p-4.h-100
    //-           h4 Objetivo del muestreo
    //-           p.mb-0 ¿Para qué se toma la muestra? (Ej. análisis microbiológico de rutina, verificación de un lote sospechoso, liberación de un producto terminado).

    //-         .tarjeta.p-4.h-100
    //-           h4 Tipo de muestra
    //-           p.mb-0 ¿Se toman muestras al azar, representativas de un lote, o muestras dirigidas a puntos específicos?

    //-         .tarjeta.p-4.h-100
    //-           h4 Tamaño de la muestra
    //-           p.mb-0 ¿Cuántas unidades o qué cantidad de producto se debe tomar para que la muestra sea representativa del lote? Esto puede basarse en normas técnicas (como las NTC) o en el criterio del experto. Por ejemplo, en un lote de 100 cajas de galletas, se podrían muestrear 5 cajas al azar.

    //-         .tarjeta.p-4.h-100
    //-           h4 Técnica de muestreo
    //-           p.mb-0 ¿Cómo se toma la muestra para evitar contaminarla? Se deben usar utensilios y recipientes estériles, y seguir procedimientos asépticos.

    //-         .tarjeta.p-4.h-100
    //-           h4 Conservación y transporte de la muestra
    //-           p.mb-0 ¿Cómo se preserva la muestra hasta que llegue al laboratorio para que sus condiciones no se alteren? Para análisis microbiológicos, las muestras deben refrigerarse (entre 2 °C y 8 °C) y transportarse en neveras portátiles. Para análisis fisicoquímicos, pueden requerir congelación o simplemente temperatura ambiente, dependiendo del análisis.

    //-         .tarjeta.p-4.h-100
    //-           h4 Rotulado de la muestra
    //-           p.mb-0 Toda muestra debe estar claramente identificada con una etiqueta que incluya, como mínimo: nombre del producto, fecha de muestreo, hora, lote (si aplica), tipo de análisis solicitado y nombre de quien tomó la muestra.

    //-         .tarjeta.p-4.h-100
    //-           h4 Registro de la información
    //-           p.mb-0 Se debe diligenciar un formato de "Acta de Toma de Muestras" donde se consigne toda la información anterior.



    //- .row.mb-5.justify-content-center.align-items-center
    //-   .col-lg-8.col-md-12.mb-0.mb-lg-0
    //-     .titulo-sexto.color-acento-contenido.mb-3
    //-       h5 
    //-         b Tabla 2.
    //-       span Ejemplo de plan de muestreo para la recepción de leche cruda
    //-     .tabla-a.color-acento-contenido.tb-custom.mb-0
    //-       table
    //-         caption <span style="font-weight: normal">Nota. SENA, (2026).</span>
    //-         thead
    //-           tr
    //-             th Variable
    //-             th Especificación
    //-         tbody
    //-           tr
    //-             td Objetivo
    //-             td Verificar la calidad microbiológica y fisicoquímica de la leche cruda al ingreso a planta.
    //-           tr
    //-             td Tipo de muestra
    //-             td Muestra compuesta representativa del carro tanque.
    //-           tr
    //-             td Tamaño de la muestra
    //-             td 1 litro de leche, tomado de diferentes puntos del tanque después de la agitación.
    //-           tr
    //-             td Técnica de muestreo
    //-             td Usar un muestreador de acero inoxidable previamente esterilizado. Verter la leche en un frasco de vidrio estéril de boca ancha.
    //-           tr
    //-             td Conservación
    //-             td Refrigerar inmediatamente a 4 °C en una nevera portátil con geles refrigerantes.
    //-           tr
    //-             td Rotulado
    //-             td Etiqueta con: "leche cruda", fecha, hora, proveedor, placa del vehículo, "análisis: recuento de mesófilos, grasa, proteína", "tomado por: [nombre]"

    //- separador
    
    //- #t_3_4.titulo-segundo.color-acento-contenido(data-aos="flip-up")
    //-   h2 3.4 Registro en el programa de limpieza y desinfección

    //- .row.align-items-center.mb-5
    //-   .col-lg-auto.d-none.d-lg-flex
    //-     img(src="@/assets/curso/tema3/img14.svg").mx-auto
    //-   .col-lg
    //-     p.mb-0 Este programa debe contar con registros que permitan hacer seguimiento a cada una de las actividades. Planear estos registros implica diseñar formatos para:

    //- .row.justify-content-center.mb-5
    //-   .col-xl-4.col-lg-6.col-md-12.col-12.mb-4.mb-xl-0
    //-     .crd_hover_txt(data-aos="flip-left").tarjeta
    //-       .crd_hover_txt--img
    //-         figure
    //-           img(src="@/assets/curso/tema3/img15.png", alt="Registro diario de limpieza")
    //-       .crd_hover_txt--body.pd-1-2
    //-         h4.mb-3.text-center Registro diario de limpieza y desinfección
    //-         p.mb-0 Un formato en el que, por cada área o equipo, el operario anote la fecha, la hora, la actividad realizada (ej. "limpieza de mesón de acero inoxidable"), los productos utilizados (nombre y concentración) y su firma como constancia.

    //-   .col-xl-4.col-lg-6.col-md-12.col-12.mb-4.mb-xl-0
    //-     .crd_hover_txt(data-aos="flip-left").tarjeta
    //-       .crd_hover_txt--img
    //-         figure
    //-           img(src="@/assets/curso/tema3/img16.png", alt="Preparación de soluciones desinfectantes")
    //-       .crd_hover_txt--body.pd-1-3
    //-         h4.mb-3.text-center Registro de preparación de soluciones desinfectantes
    //-         p.mb-0 Un formato para llevar el control de la preparación de las soluciones, verificando que se respeten las concentraciones indicadas (ej. "para preparar 10 litros de solución de hipoclorito a 200 ppm, se agregaron X ml de hipoclorito al 5 %").

    //-   .col-xl-4.col-lg-6.col-md-12.col-12.mb-4.mb-xl-0
    //-     .crd_hover_txt(data-aos="flip-left").tarjeta
    //-       .crd_hover_txt--img
    //-         figure
    //-           img(src="@/assets/curso/tema3/img17.png", alt="Verificación de limpieza y desinfección")
    //-       .crd_hover_txt--body.pd-1-3
    //-         h4.mb-3.text-center Registro de verificación de la limpieza y desinfección
    //-         p.mb-0 Un formato que puede ser diligenciado por un supervisor, mediante la toma de muestras con hisopos en superficies para verificar la eficacia de la limpieza (pruebas de ATP o recuento microbiológico) o simplemente mediante inspección visual.

    //- separador
    
    //- #t_3_5.titulo-segundo.color-acento-contenido(data-aos="flip-up")
    //-   h2 3.5 Registro en el programa de control de plagas y vectores

    //- .row.align-items-center.mb-5
    //-   .col-lg-auto.d-none.d-lg-flex
    //-     img(src="@/assets/curso/tema3/img23.svg").mx-auto
    //-   .col-lg
    //-     p.mb-0 La planeación de registros para este programa es vital para demostrar que se está llevando a cabo un control efectivo. Los registros típicos incluyen:

    //- .row.justify-content-center.align-items-center.mb-3
    //-   .col-lg-8.mb-0
    //-     AcordionA(tipo="b" clase-tarjeta="tarjeta bg-color-3 bg-color-nuevo")
    //-       div(titulo="Registro de inspección interna")
    //-         p.mb-0 Un formato para que el personal de la planta realice inspecciones periódicas (semanales o quincenales) y reporte cualquier evidencia de plagas (roedores, insectos, aves) o condiciones que puedan atraerlas (ej. huecos en paredes, residuos acumulados, agua estancada).

    //-       div(titulo="Registro de las actividades de la empresa externa de control de plagas")
    //-         p.mb-3 La empresa contratada debe dejar un registro detallado de cada visita, que incluya:
    //-         ul.lista-ul
    //-           li 
    //-             i.lista-ul__vineta(style="color: #B37900")
    //-             | Fecha y hora de la visita.
    //-           li 
    //-             i.lista-ul__vineta(style="color: #B37900")
    //-             | Nombre del técnico responsable.
    //-           li 
    //-             i.lista-ul__vineta(style="color: #B37900")
    //-             | Productos utilizados: nombre comercial, ingrediente activo, concentración, dosis aplicada y número de lote.
    //-           li 
    //-             i.lista-ul__vineta(style="color: #B37900")
    //-             | Equipos utilizados durante la intervención.
    //-           li 
    //-             i.lista-ul__vineta(style="color: #B37900")
    //-             | Ubicación de los cebos y trampas inspeccionados y/o reabastecidos.
    //-           li 
    //-             i.lista-ul__vineta(style="color: #B37900")
    //-             | Hallazgos, por ejemplo: "se encontró un roedor muerto en el cebo #5", "se observó actividad baja de moscas".
    //-           li 
    //-             i.lista-ul__vineta(style="color: #B37900")
    //-             | Recomendaciones para la planta, por ejemplo: "sellar grieta en pared del área de almacenamiento".
    //-           li 
    //-             i.lista-ul__vineta(style="color: #B37900")
    //-             | Firma del técnico y del responsable de la planta que recibe y verifica el servicio.

    //-   .col-lg-4.col-md-8.mb-0
    //-     img(src="@/assets/curso/tema3/img24.png", data-aos="zoom-in")


    //- .row.mb-5.justify-content-center.align-items-center
    //-   .col-lg-12.col-md-12.mb-0.mb-lg-0
    //-     .titulo-sexto.color-acento-contenido.mb-3
    //-       h5 
    //-         b Tabla 3.
    //-       span Ejemplo de formato de inspección interna de plagas
    //-     .tabla-a.color-acento-contenido.tb-custom.mb-0
    //-       table
    //-         caption <span style="font-weight: normal">Nota. SENA, (2026).</span>
    //-         thead
    //-           tr
    //-             th Área
    //-             th Fecha
    //-             th Inspeccionado por
    //-             th Evidencia de plagas (Sí/No)
    //-             th Tipo de plaga / Hallazgo
    //-             th Condiciones de riesgo
    //-             th Acción tomada / Observación
    //-         tbody
    //-           tr
    //-             td Bodega de secos
    //-             td 15/03/2026
    //-             td Juan Pérez
    //-             td Sí
    //-             td Roedores
    //-             td Heces pequeñas en esquina, cerca de estiba de harina.
    //-             td Se reportó a la empresa de control de plagas para revisión de trampas. Se limpió el área.
    //-           tr
    //-             td Área de producción
    //-             td 15/03/2026
    //-             td Juan Pérez
    //-             td No
    //-             td -
    //-             td Rejilla de piso levantada.
    //-             td Se solicitó a mantenimiento su reparación para evitar el ingreso de roedores.

    //- separador
    
    //- #t_3_6.titulo-segundo.color-acento-contenido(data-aos="flip-up")
    //-   h2 3.6 Registro en el programa de abastecimiento de agua potable

    
    //- .row.align-items-center.mb-5
    //-   .col-lg-auto.d-none.d-lg-flex
    //-     img(src="@/assets/curso/tema3/img18.svg").mx-auto
    //-   .col-lg
    //-     p.mb-0 El agua es un ingrediente fundamental y un medio de limpieza esencial. Los registros de este programa deben demostrar que el agua utilizada es potable y apta para el uso previsto. Se deben planear formatos para:



    //- .row.justify-content-center.mb-5
    //-   .col-lg-8
    //-     AcordionA(tipo="b" clase-tarjeta="tarjeta bg-color-3 bg-color-nuevo")
    //-       div(titulo="Registro de cloro residual")
    //-         p.mb-0 En plantas con tanques de almacenamiento propios, se debe medir y registrar diariamente el nivel de cloro residual libre en el agua al inicio de la jornada y, preferiblemente, en varios puntos de la planta. El valor debe estar dentro del rango establecido por la norma (generalmente entre 0,3 y 2,0 ppm).

    //-       div(titulo="Registro de mantenimiento de tanques de agua")
    //-         p.mb-0 Se debe llevar un control de las actividades de limpieza y desinfección periódicas de los tanques de almacenamiento (al menos cada seis meses), registrando la fecha, el procedimiento realizado, los productos utilizados y el responsable.

    //-       div(titulo="Registro de resultados de análisis microbiológicos y fisicoquímicos")
    //-         p.mb-0 La norma exige realizar análisis periódicos del agua para confirmar su potabilidad. Los resultados de estos análisis, realizados por un laboratorio acreditado, deben archivarse y registrarse para su control y seguimiento.

    //-   .col-lg-4.col-md-8
    //-     img(src="@/assets/curso/tema3/img19.png", data-aos="zoom-in")

    //- separador
    
    //- #t_3_7.titulo-segundo.color-acento-contenido(data-aos="flip-up")
    //-   h2 3.7 Registro en el programa de manejo de residuos sólidos y líquidos

    //- .row.align-items-center.mb-5
    //-   .col-lg-auto.d-none.d-lg-flex
    //-     img(src="@/assets/curso/tema3/img20.svg").mx-auto
    //-   .col-lg
    //-     p.mb-0 Un manejo inadecuado de residuos atrae plagas y contamina el ambiente. Los registros ayudan a controlar este aspecto. Se deben planear formatos para:

    //- .row.justify-content-center.mb-5
    //-   .col-lg-6.col-md-12.mb-4.mb-lg-0
    //-     .bg-color-2.p-4.h-100.br-15
    //-       .row.align-items-center.mb-0.h-100
    //-         .col-12.col-lg-auto.mb-4.mb-lg-0
    //-           img(src="@/assets/curso/tema3/img21.svg", style="max-width: 150px;").mx-auto
    //-         .col-lg
    //-           h4 Registro de generación y disposición de residuos: 
    //-           p.mb-0 Un formato sencillo donde se lleve un control diario o semanal de la cantidad de residuos generados (orgánicos, reciclables, peligrosos) y se registre su disposición final (ej. "entregado al servicio de recolección municipal", "entregado a gestor externo autorizado para aceite usado").

    //-   .col-lg-6.col-md-12.mb-4.mb-lg-0
    //-     .bg-color-2.p-4.h-100.br-15
    //-       .row.align-items-center.mb-0.h-100
    //-         .col-12.col-lg-auto.mb-4.mb-lg-0
    //-           img(src="@/assets/curso/tema3/img22.svg", style="max-width: 150px;").mx-auto
    //-         .col-lg
    //-           h4 Registro de limpieza de áreas de almacenamiento de residuos:
    //-           p.mb-0 Se debe registrar la limpieza y desinfección periódica de los contenedores y del cuarto de basuras para evitar malos olores y proliferación de plagas.


</template>

<script>
export default {
  name: 'Tema3',
  data: () => ({
    // variables de vue
  }),
}
</script>

<style lang="sass"></style>
