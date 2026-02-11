<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido.mb-0(data-aos="flip-up")
      .titulo-principal__numero
        span 2
      h1 Norma Internacional de Información Financiera (NIIF)
    
    .bg-full-width.bg-color-21.mb-5
      .p-4.p-md-5
        .titulo-con-imagen.mb-5(data-aos="fade-right")
          .titulo-con-imagen__fondo
            img.titulo-con-imagen__imagen(src="@/assets/componentes/1.png")
            h3.titulo-con-imagen__texto OBJETIVO
        
        .row.mb-5
          .col-lg-5.order-lg-2.mb-5.mb-lg-0
            figure
              img(src="@/assets/curso/tema2/1.png", data-aos="zoom-in", style="max-width: 500px").mx-auto
          .col-lg-7.order-lg-1(data-aos="fade-left")
            ol.lista-ol--cuadro.ms-4
              li.d-flex.mb-3 
                .lista-ol--cuadro__vineta
                  span 1
                | Esta NIIF: (a) define valor razonable; (b) establece en una sola NIIF un marco para la medición del valor razonable; y (c) requiere información a revelar sobre las mediciones del valor razonable.
              li.d-flex.mb-3 
                .lista-ol--cuadro__vineta
                  span 2
                | El valor razonable es una medición basada en el mercado, no una medición específica de la entidad. Para algunos activos y pasivos, pueden estar disponibles transacciones de mercado observables o información de mercado. Para otros activos y pasivos, pueden no estar disponibles transacciones de mercado observables e información de mercado. Sin embargo, el objetivo de una medición del valor razonable en ambos casos es el mismo: estimar el precio al que tendría lugar una transacción ordenada para vender el activo o transferir el pasivo entre participantes del mercado en la fecha de la medición en condiciones de mercado presentes (es decir, un precio de salida en la fecha de la medición desde la perspectiva de un participante de mercado que mantiene el activo o debe el pasivo). 
        
        .row.mb-5
          .col-lg-5.mb-5.mb-lg-0(data-aos="fade-right")
            figure
              img(src="@/assets/curso/tema2/2.png", data-aos="zoom-in", style="max-width: 500px").mx-auto
          .col-lg-7(data-aos="fade-left")
            ol.lista-ol--cuadro.ms-4
              li.d-flex.mb-3 
                .lista-ol--cuadro__vineta
                  span 3
                | Cuando un precio para un activo o pasivo idéntico es no observable, una entidad medirá el valor razonable utilizando otra técnica de valoración que maximice el uso de datos de entrada observables relevantes y minimice el uso de datos de entrada no observables. Puesto que el valor razonable es una medición basada en el mercado, se mide utilizando los supuestos que los participantes del mercado utilizarían al fijar el precio del activo o pasivo, incluyendo los supuestos sobre riesgo. En consecuencia, la intención de una entidad de mantener un activo o liquidar o satisfacer de otra forma un pasivo no es relevante al medir el valor razonable. 
              li.d-flex.mb-3 
                .lista-ol--cuadro__vineta
                  span 4
                | La definición de valor razonable se centra en los activos y pasivos porque son un objeto principal de la medición en contabilidad. Además, esta NIIF se aplicará a instrumentos de patrimonio propios de una entidad, medidos a valor razonable.  Consejo Técnico de la Contaduría Pública (CTCP) (2020, 5 de noviembre). Norma Internacional de Información Financiera 13 Medición del Valor Razonable.
        
        .titulo-con-imagen.mb-5(data-aos="fade-right")
          .titulo-con-imagen__fondo
            img.titulo-con-imagen__imagen(src="@/assets/componentes/1.png")
            h3.titulo-con-imagen__texto ALCANCE
        
        .row.mb-5
          .col-lg-5.order-lg-2.mb-5.mb-lg-0
            figure
              img(src="@/assets/curso/tema2/3.png", data-aos="zoom-in", style="max-width: 500px").mx-auto
          .col-lg-7.order-lg-1(data-aos="fade-left")
            ol.lista-ol--cuadro.ms-4
              li.d-flex.mb-3 
                .lista-ol--cuadro__vineta
                  span 1
                | Esta NIIF se aplicará cuando otra NIIF requiera o permita mediciones a valor razonable o información a revelar sobre mediciones a valor razonable (y mediciones, tales como valor razonable menos costos de venta, basadas en el valor razonable, o información a revelar sobre esas mediciones), excepto por lo que se especifica en los párrafos 6 y 7. 
              li.d-flex.mb-3 
                .lista-ol--cuadro__vineta
                  span 2
                | Los requerimientos sobre medición e información a revelar de esta NIIF no se aplicarán a los elementos siguientes: (a) transacciones con pagos basados en acciones que queden dentro del alcance de la NIIF 2 Pagos basados en Acciones; (b) transacciones de arrendamiento contabilizados de acuerdo con la NIIF 16 Arrendamientos; y (c) mediciones que tengan alguna similitud con el valor razonable, pero que no sean valor razonable, tales como el valor neto realizable de la NIC 2 Inventarios o el valor en uso de la NIC 36 Deterioro del valor de los Activos.  
        
        .row.mb-5
          .col-lg-5.mb-5.mb-lg-0
            figure
              img(src="@/assets/curso/tema2/4.png", data-aos="zoom-in", style="max-width: 500px").mx-auto
          .col-lg-7(data-aos="fade-left")
            ol.lista-ol--cuadro.ms-4
              li.d-flex.mb-3 
                .lista-ol--cuadro__vineta
                  span 3
                | La información a revelar requerida por esta NIIF no se requiere para los siguientes elementos: (a) activos del plan medidos a valor razonable de acuerdo con la NIC 19 beneficios a los empleados; (b) inversiones en un plan de beneficios por retiro medidos a valor razonable de acuerdo con la NIC 26 contabilización e información financiera sobre planes de beneficio por retiro; y (c) activos para los que el importe recuperable es el valor razonable menos los costos de disposición de acuerdo con la NIC 36. 
              li.d-flex.mb-3 
                .lista-ol--cuadro__vineta
                  span 4
                | Si el valor razonable se requiere o permite por otras NIIF, el marco de medición del valor razonable descrito en esta NIIF se aplicará a la medición inicial y posterior.

        .bloque-texto-a.color-secundario.p-4.p-md-5 
          .row.m-0.align-items-center.justify-content-between
            .col-lg-3.mb-4.mb-lg-0.order-lg-2
              figure
                img(src="@/assets/curso/tema2/5.svg", data-aos="zoom-in")
            .col-lg-9.order-lg-1
              .bloque-texto-a__texto.p-4
                p.mb-0 El valor razonable es una medida basada en el mercado, para registrar su valor es importante indagar en el mercado si el elemento ha presentado cambios que requieran una actualización conforme con las variaciones presentadas. Algunos activos que deben ser medidos a valor razonable son: instrumentos financieros, propiedades, planta y equipo, activos biológicos e inversiones.
    
    p(data-aos="fade-down") <b>Ejemplo:</b> La empresa Supercueros SAS adquiere 1.000 acciones el 11 de noviembre de 2020, a $2.500 cada una. Se cancela comisión por valor de $500.000.

    p.mb-4(data-aos="fade-down") A 31 de diciembre de 2020, el valor de la acción disminuye hasta $2.200 por acción.  Realizar la medición inicial y posterior.
  
    .row.mb-5.justify-content-center
      .col-lg-10
        div.tarjeta.bg-color-16.p-4.mb-5
          .row.justify-content-center.align-items-center
            .col-lg-4.mb-3.mb-lg-0.mb-4.mb-lg-0
              figure
                img(src="@/assets/curso/tema2/6.svg", data-aos="zoom-in", style="max-width: 300px").mx-auto
              
            .col-lg-8.mb-3.mb-lg-0(data-aos="fade-left")
              h5 Medición Inicial: 11 de noviembre de 2020
              .titulo-sexto.color-acento-contenido
                h5 Tabla 11.
                span Cálculo del valor total de una inversión en acciones
              .tabla-a.color-acento-botones.mb-3
                table
                  thead
                    tr
                      th.bg-color-6.text-center  Concepto  
                      th.bg-color-6.text-center  Valor 

                  tbody
                    tr.bg-color-white
                      td Inversión en acciones  
                      td.text-right $ 2.500.000 

                    tr.bg-color-18
                      td Más costo transacción   
                      td.text-right $ 500.000 
                    tr.bg-color-18
                      td.text-bold Total Inversión   
                      td.text-right $ 3.000.000 
              .titulo-sexto.color-acento-contenido
                h5 Tabla 12.
                span Registro contable de la compra de acciones
              .tabla-a.color-acento-botones
                table
                  thead
                    tr
                      th.bg-color-6.text-center  Cuenta  
                      th.bg-color-6.text-center  Debe 
                      th.bg-color-6.text-center  Haber 

                  tbody
                    tr.bg-color-white
                      td Activos financieros (acciones)  
                      td.text-right $ 3.000.000
                      td

                    tr.bg-color-18
                      td Efectivo  
                      td.text-right -
                      td.text-right $ 3.000.000
                    tr.bg-color-18
                      td.text-bold Total  
                      td.text-right $ 3.000.000
                      td.text-right $ 3.000.000
    
    .row.justify-content-center
      .col-lg-10
        div.tarjeta.bg-color-8.p-4.mb-5
          .row.justify-content-center.align-items-center
            .col-lg-4.mb-3.mb-lg-0.order-lg-2.mb-4.mb-lg-0
              figure
                img(src="@/assets/curso/tema2/7.svg", data-aos="zoom-in", style="max-width: 300px").mx-auto
              
            .col-lg-8.mb-3.mb-lg-0.order-lg-1.mb-3.mb-lg-0(data-aos="fade-left")
              h5 Medición posterior: 31 de diciembre de 2020
              .titulo-sexto.color-acento-contenido
                h5 Tabla 13.
                span Cálculo de pérdida por desvalorización de acciones
              .tabla-a.color-acento-botones.mb-3
                table
                  thead
                    tr
                      th.bg-color-6.text-center  Concepto  
                      th.bg-color-6.text-center  Valor 

                  tbody
                    tr.bg-color-white
                      td Valor razonable 31/12/2020
                      td.text-right $ 2.200.000 


                    tr.bg-color-18
                      td Valor costo de adquisición 11/11/2020  
                      td.text-right $ 2.500.000 

                    tr.bg-color-18
                      td.text-bold Valor pérdida de acciones  
                      td.text-right -$ 300.000 
              .titulo-sexto.color-acento-contenido
                h5 Tabla 14.
                span Asiento contable por desvalorización de acciones
              .tabla-a.color-acento-botones
                table
                  thead
                    tr
                      th.bg-color-6.text-center  Cuenta  
                      th.bg-color-6.text-center  Debe 
                      th.bg-color-6.text-center  Haber 

                  tbody
                    tr.bg-color-white
                      td Gasto por pérdida
                      td.text-right $ 300.000
                      td

                    tr.bg-color-18
                      td Activos financieros (acciones) 
                      td.text-right -
                      td.text-right $ 300.000
                    tr.bg-color-18
                      td.text-bold Total  
                      td.text-right $ 300.000
                      td.text-right $ 300.000
    
    .row.justify-content-center
      .col-lg-4.mb-5.mb-lg-0
        figure
          img(src="@/assets/curso/tema2/8.svg", data-aos="zoom-in")
              
      .col-lg-6(data-aos="fade-left")
        P Esta norma proporciona los criterios de aplicación del valor razonable que se utilizan en el reconocimiento y medición de hechos económicos.  Los invito a ampliar la información revisando la Norma Internacional de Contabilidad número trece (NIIF 13) - “Medición del valor razonable” en el siguiente enlace:
        a.anexo.mb-4.mb-lg-0(href="https://www.ctcp.gov.co/proyectos/contabilidad-e-informacion-financiera/documentos-organismos-internacionales/compilacion-marcos-tecnicos-de-informacion-financi/1534363802-6328" target="_blank")
          .anexo__icono
            img(src="@/assets/template/icono-link.svg")
          .anexo__texto
            p <b>Enlace web.</b> Consejo Técnico de la Contaduría Pública (CTCP) (2020, 5 de noviembre) Norma Internacional de Información Financiera 13 Medición del Valor Razonable.


</template>

<script>
export default {
  name: 'Tema2',
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
