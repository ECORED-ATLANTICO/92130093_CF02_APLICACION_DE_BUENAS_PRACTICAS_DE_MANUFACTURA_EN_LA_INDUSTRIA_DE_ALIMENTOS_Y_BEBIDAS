<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span
          i.fas.fa-info
      h1 Introducción

    .row.mb-5.justify-content-center.align-items-center
      .col-lg-4.col-md-8.mb-0.mb-lg-0.order-2.order-lg-1
        figure
          img(src="@/assets/curso/intro/img01.png", data-aos="zoom-in")
      .col-lg-8.order-1.order-lg-2.mb-4.mb-lg-0
        p.mb-0(data-aos="fade-right") En la industria de alimentos, la confianza del consumidor y el éxito de una marca se construyen sobre una base inquebrantable: la inocuidad. Cada día, millones de personas confían en que los productos que llegan a su mesa son seguros para el consumo. Esta confianza no es producto de la casualidad, sino del resultado de procesos rigurosos, personal capacitado y una vigilancia constante de cada etapa de la cadena productiva. Es precisamente en este contexto donde la verificación, el control y el análisis de riesgos sanitarios se convierten en pilares fundamentales para garantizar que los alimentos no representen un riesgo para la salud. Sin estos elementos, cualquier proceso productivo estaría expuesto a fallos que podrían generar consecuencias graves para la salud pública y la estabilidad de las empresas.

    .row.mb-5.justify-content-center.align-items-center
      .col-lg-3.col-md-8.mb-0.mb-lg-0.order-2.order-lg-2
        figure
          img(src="@/assets/curso/intro/img02.png", data-aos="zoom-in")
      .col-lg-9.order-1.order-lg-1.mb-4.mb-lg-0
        .bg-color-0.p-4.br-15.mb-3
          p.mb-0 Este componente formativo presenta los fundamentos conceptuales y procedimentales necesarios para comprender la verificación de los programas de saneamiento, el control de los factores de contaminación y el análisis de los riesgos sanitarios en la industria alimentaria. El estudio de estos contenidos fortalece las competencias relacionadas con la protección de la salud pública, el aseguramiento de la calidad de los procesos y productos, y el cumplimiento de la normatividad sanitaria vigente. Asimismo, resalta la importancia del verificador sanitario como actor clave en la implementación de sistemas de gestión de la inocuidad y en la prevención de riesgos durante la producción de alimentos.

        p.mb-0(data-aos="fade-right") El desarrollo del componente se organiza mediante una estructura lógica y progresiva. En primer lugar, se aborda la verificación de los programas de saneamiento, los cuales constituyen la base de cualquier sistema de calidad. Posteriormente, se analizan los principales factores de contaminación de los alimentos, su clasificación y su origen, desde peligros físicos hasta microorganismos patógenos. Finalmente, se estudian las medidas preventivas que, a partir del diagnóstico sanitario, permiten anticipar los peligros y establecer acciones orientadas al control de los riesgos, incluyendo una introducción al sistema de Análisis de Peligros y Puntos Críticos de Control (HACCP). El contenido se complementa con ejemplos aplicados a la industria de alimentos y bebidas, tablas explicativas y recursos gráficos que favorecen la comprensión de los temas y su aplicación en contextos productivos.

</template>

<script>
export default {
  name: 'Introduccion',
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
