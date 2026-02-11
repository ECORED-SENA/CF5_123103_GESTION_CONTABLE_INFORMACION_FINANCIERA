<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido(data-aos="flip-up")
      .titulo-principal__numero
        span
          i.fas.fa-info
      h1 Introducción

    .bloque-texto-a.color-secundario.p-4.p-md-5.mb-5(data-aos="fade-right")
      .row.m-0.align-items-center.justify-content-between
        .col-lg-3.mb-4.mb-lg-0.order-lg-2
          figure
            img(src="@/assets/curso/intro/1.svg", style="max-width: 300px").mx-auto
        .col-lg-9.order-lg-1
          .bloque-texto-a__texto.p-4
            p.mb-0 En este componente formativo se desarrollan los temas relacionados con la fundamentación y aplicación de las matemáticas financieras en el sector productivo, se analiza la clasificación de las tasas de interés, el valor del dinero en el tiempo, equivalencia de tasas, tablas de amortización y alternativas de inversión como lo son el Valor Presente Neto (VPN) y Tasa Interna de Retorno (TIR).
    
    .row
      .col-lg-3.mb-4.mb-lg-0.d-none.d-md-block(data-aos="fade-right")
        figure
          img(src="@/assets/curso/intro/2.svg", data-aos="zoom-in", style="max-width: 300px").mx-auto
      .col-lg-9(data-aos="fade-left")
        .row.align-items-start.mb-3
          .col-md-auto.mb-3.mb-lg-0
            img(src="@/assets/curso/intro/3.svg", style="max-width: 90px").mx-auto
          .col-md
            p.mb-0 Se profundiza en la Norma Internacional de Información Financiera (NIIF) 13 – Medición del Valor Razonable, teniendo en cuenta la importancia de su análisis y aplicación en el registro de los hechos económicos bajo los estándares internacionales.
    
        .bg-color-3.p-5
          p.mb-0 Finalmente, el análisis del componente le permite adquirir conocimientos en el manejo de herramientas ofimáticas, contribuyendo en el logro de los objetivos propuestos, fortaleciendo sus competencias y habilidades en el área de ofimática, contable y financiera.

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
