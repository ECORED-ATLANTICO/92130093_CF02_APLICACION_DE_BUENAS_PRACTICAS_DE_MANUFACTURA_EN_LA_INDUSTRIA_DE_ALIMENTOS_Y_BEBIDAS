<template lang="pug">
.curso-main-container.pb-3
  BannerInterno(icono="fas fa-sitemap" titulo="Síntesis")
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    p Las Buenas Prácticas de Manufactura constituyen el fundamento esencial para garantizar la inocuidad en la industria de alimentos y bebidas. Este componente formativo ha desarrollado los conceptos clave sobre su definición, objetivos y relación con otros sistemas como POES y HACCP, así como el marco normativo colombiano que las respalda, destacando la Ley 9 de 1979, el Decreto 3075 de 1997 y la Resolución 2674 de 2013 como ejes centrales. Se abordó la importancia de la planeación documental a través de los programas de saneamiento - limpieza y desinfección, control de plagas, abastecimiento de agua y manejo de residuos - y los criterios para el correcto diligenciamiento de registros. Finalmente, se exploró la ejecución práctica de las BPM, incluyendo la higiene del personal, las técnicas de limpieza y desinfección, el manejo de materias primas con rotación PEPS y la verificación de variables del proceso, cerrando con los mecanismos de identificación de no conformidades y la implementación de acciones correctivas y preventivas que impulsan la mejora continua en la organización.
    
    .row.justify-content-center
      .col-lg-12.mb-5.bgs.p-4.brad
        figure
          img(src="@/assets/curso/sintesis.svg", alt="Este componente formativo aborda las Buenas Prácticas de Manufactura (BPM) como fundamento para garantizar la inocuidad en la industria de alimentos y bebidas. Presenta los conceptos relacionados con su definición, objetivos y relación con los programas prerrequisito y el sistema HACCP, así como el marco normativo colombiano que sustenta su aplicación. También desarrolla la planeación documental mediante los programas de saneamiento y los criterios para el diligenciamiento de registros. Finalmente, explica la ejecución de las BPM a través de la higiene del personal, los procedimientos de limpieza y desinfección, el manejo de materias primas con rotación PEPS, la verificación de variables del proceso y la aplicación de acciones correctivas y preventivas para fortalecer la mejora continua y la producción de alimentos inocuos.")
      .col-auto
        a.anexo.mb-5(:href="obtenerLink('/downloads/Sintesis.pdf')" target="_blank")
          .anexo__icono
            img(src="@/assets/bullets/icono-pdf.svg")
          .anexo__texto
            p Anexo. Síntesis

</template>

<script>
export default {
  name: 'Sintesis',
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
