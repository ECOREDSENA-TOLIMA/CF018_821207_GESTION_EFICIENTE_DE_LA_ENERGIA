<template lang="pug">
.curso-main-container.pb-3
  BannerInterno(icono="fas fa-sitemap" titulo="Síntesis")
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5

    p.mb-5 El procesamiento y análisis de datos son elementos clave en la toma de decisiones basada en información cuantitativa. Dentro de este campo, se abordan diversos subtemas, como la probabilidad y estadística, que incluyen el estudio de variables continuas, distribuciones bidimensionales, discretas y continuas, así como muestreo, estimación, prueba de hipótesis y combinatoria. Además, se exploran métodos para procesar, graficar y analizar datos, como métodos de investigación, tipos de gráficas y herramientas software ampliamente utilizadas en esta área. Estas habilidades permiten comprender mejor los datos, identificar patrones y tomar decisiones informadas en diversos campos.

    .row.justify-content-center
      .col-lg-10.mb-5
        figure
          img(src="@/assets/curso/temas/sintesis.svg", alt="alt")
      .col-auto
        a.anexo.mb-4(:href="obtenerLink('/downloads/sintesis.pdf')" target="_blank")
          .anexo__icono
            img(src="@/assets/template/icono-pdf.svg")
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
