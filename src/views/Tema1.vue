<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido(data-aos="flip-up")
      .titulo-principal__numero
        span 1
      h1 Matemáticas financieras

    .row.mb-5
      .col-lg-1.mb-3.mb-lg-0
        figure
          img.d-none.d-lg-flex(src="@/assets/curso/tema1/1.svg", data-aos="zoom-in")
      .col-lg-11
        p.mb-0 El objetivo del presente componente es el análisis de la fundamentación y aplicación de las matemáticas financieras; para lo cual se fortalecerán las habilidades y competencias en el manejo y aplicación de tasas de interés, tablas de amortización, herramientas de Excel y criterios del valor razonable. Logrando de esta manera adquirir destrezas en el área contable y financiera para su desempeño en el ámbito empresarial. 
    
    #t_1_1.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 1.1 Concepto
    
    .row
      .col-lg-5.order-lg-2.mb-3.mb-lg-0
        figure
          img(src="@/assets/curso/tema1/2.png", data-aos="zoom-in", style="max-width: 500px").mx-auto
      .col-lg-7.order-lg-1(data-aos="fade-left")
        p Es el campo de las matemáticas que aplica un ente económico para el análisis, la valoración de los mercados financieros y el valor del dinero en el tiempo, mediante la aplicación de cálculos aritméticos. 
        p Es una herramienta muy importante en el ámbito empresarial, la cual ha tomado fuerza con la implementación de las Normas Internacionales de Información Financiera. Su finalidad es contribuir en la toma de decisiones de forma útil, transparente y confiable sobre los proyectos, inversiones, rentabilidad y amortización de deudas. 

    
        .bg-color-15.p-4(data-aos="fade-left")
          .row.align-items-start
            .col-lg-auto.mb-3.mb-lg-0
              img(src="@/assets/curso/tema1/3.svg", style="max-width: 90px").mx-auto
            .col-lg
              p.mb-0 De acuerdo con la convergencia de Normas Internacionales de Información Financiera, mediante la expedición de la Ley 1314 de 2009, se presentan cambios en la valoración de los instrumentos financieros, donde se tiene en cuenta los criterios de medición de costo amortizado y valor razonable, utilizando el método de interés efectivo.

    separador

    #t_1_2.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 1.2 Tasas de interés
    
    p.mb-4 Antes de abordar el tipo de tasas de interés, los invito a analizar los conceptos básicos con el fin de avanzar significativamente en las temáticas que le permitan desarrollar esta unidad.

    .bg-full-width.bg-fondo-slider.mb-5
      .p-4.p-md-5
        SlyderA(tipo="b").bg-white.p-4.tarjeta(data-aos="fade-left")
          .row.align-items-center.p-4.p-md-5
            .col-lg-5.order-2
              figure
                img(src="@/assets/curso/tema1/4.png")
            .col-lg-7.order-1.mb-3.mb-lg-0
              h4 Interés
              p Es el valor que se cancela por utilizar un capital durante un periodo determinado, teniendo en cuenta las condiciones acordadas entre deudor y acreedor. 
          .row.align-items-center.p-4.p-md-5
            .col-lg-5.order-2
              figure
                img(src="@/assets/curso/tema1/5.png")
            .col-lg-7.order-1.mb-3.mb-lg-0
              h4 Valor Presente (VP)
              p Es el valor actual (VA) de la inversión, denominado también capital inicial. 
          .row.align-items-center.p-4.p-md-5
            .col-lg-5.order-2
              figure
                img(src="@/assets/curso/tema1/6.png")
            .col-lg-7.order-1.mb-3.mb-lg-0
              h4 Tiempo (n)
              p Periodo en el cual se lleva a cabo en la operación financiera. 
          .row.align-items-center.p-4.p-md-5
            .col-lg-5.order-2
              figure
                img(src="@/assets/curso/tema1/7.png")
            .col-lg-7.order-1.mb-3.mb-lg-0
              h4 Diagrama flujo de caja
              p Esquema gráfico que representa el capital invertido (el valor final en un tiempo determinado y tasa acordada). 
          .row.align-items-center.p-4.p-md-5
            .col-lg-5.order-2
              figure
                img(src="@/assets/curso/tema1/8.png")
            .col-lg-7.order-1.mb-3.mb-lg-0
              h4 Valor Futuro (VF)
              p Es el valor final de la inversión, teniendo en cuenta los intereses generados en un periodo determinado.
          .row.align-items-center.p-4.p-md-5
            .col-lg-5.order-2
              figure
                img(src="@/assets/curso/tema1/9.png")
            .col-lg-7.order-1.mb-3.mb-lg-0
              h4 Tasa de interés (i)
              p Interés que genera el capital inicial en un periodo dado.    

    .titulo-con-imagen.mb-5(data-aos="fade-right")
      .titulo-con-imagen__fondo
        img.titulo-con-imagen__imagen(src="@/assets/componentes/1.png")
        h3.titulo-con-imagen__texto Interés simple
    
    p.mb-5(data-aos="fade-down") Es el interés que se genera en un periodo determinado. Se calcula sobre el capital inicial y no es capitalizable; es decir, no se acumula con el capital para originar nuevos intereses.

    .row.mb-5
      .col-lg-5.mb-4.mb-lg-0.d-none.d-md-block
        figure
          img(src="@/assets/curso/tema1/10.svg", data-aos="zoom-in", style="max-width: 400px").mx-auto
      .col-lg-7
        .row.align-items-start.mb-3
          .col-md-auto.mb-3.mb-lg-0
            img(src="@/assets/curso/tema1/11.svg", style="max-width: 90px").mx-auto
          .col-md
            p <b>Ejemplo 1:</b> Carolina invierte hoy $12.000.000 en una cuenta que paga el 9 % simple anual, ¿qué cantidad podrá retirar dentro de 3 años?
        .bg-color-16.p-4.tarjeta.mb-3(data-aos="fade-left")
          p.mb-0(data-aos="fade-left") Para desarrollar el ejercicio, es importante tener en cuenta los datos suministrados; por ello, no olvide analizar la información y observar que se tiene la necesidad de hallar el valor futuro, mediante el interés simple. Recordemos que este no capitaliza como sucede en el interés compuesto.
        p La fórmula que debe usarse es:
        .titulo-sexto.color-acento-contenido.mb-3
          h5 Figura 1.
          span Cálculo del valor futuro con interés simple
        .row.justify-content-center.mb-3
          .col-lg-9
            figure
              img(src="@/assets/curso/tema1/12.svg", data-aos="zoom-in", alt="Diagrama con fórmula de valor futuro usando interés simple, que incluye la expresión matemática VF=VA(1+n*i), un ejemplo numérico con valor actual de $12.000.000, tasa del 9 % anual y un periodo de 3 años, y una línea de tiempo que representa el crecimiento hasta un valor futuro de $15.240.000.")
        .bg-color-16.p-4.tarjeta.mb-3(data-aos="fade-left")
          p.mb-0(data-aos="fade-left") <b>Respuesta:</b> Carolina con una inversión inicial de $12.000.000 recibirá $15.240.000, dentro de tres años aplicando interés simple.
    
    .row.mb-5
      .col-lg-5.mb-4.mb-lg-0.d-none.d-md-block
        figure
          img(src="@/assets/curso/tema1/13.png", data-aos="zoom-in", style="max-width: 500px").mx-auto
      .col-lg-7
        .row.align-items-start.mb-3
          .col-md-auto.mb-3.mb-lg-0
            img(src="@/assets/curso/tema1/11.svg", style="max-width: 90px").mx-auto
          .col-md
            p <b>Ejemplo 2:</b> Andrés recibirá en 10 meses $35.000.000, correspondientes a una inversión realizada. Si la tasa de interés que le están pagando es del 2,5 % mensual, ¿cuál es el valor inicial de la inversión, aplicando el tipo de interés simple?
        .bg-color-1.p-4.tarjeta.mb-3(data-aos="fade-left")
          p.mb-0(data-aos="fade-left") De acuerdo con el análisis, se observa que se debe determinar el valor presente o actual de la inversión realizada, utilizando el tipo de interés compuesto; por lo tanto, se usará la siguiente fórmula: 
        p La fórmula que debe usarse es:
        .titulo-sexto.color-acento-contenido.mb-3
          h5 Figura 2.
          span Cálculo del valor actual con interés simple
        .row.justify-content-center.mb-3
          .col-lg-9
            figure
              img(src="@/assets/curso/tema1/15.svg", data-aos="zoom-in", alt="Fórmula para calcular el valor actual con interés simple, representada como VA=VF/(1+i*n), acompañada de un ejemplo con un valor futuro de $35.000.000, tasa de interés del 2,5 % y plazo de 10 años, que da como resultado un valor actual de $28.000.000.")
        .bg-color-1.p-4.tarjeta.mb-3(data-aos="fade-left")
          p.mb-0(data-aos="fade-left") <b>Respuesta:</b> Respuesta: Para obtener un monto de $35.000.000 durante 10 meses a la tasa del 2,5 % de invertir $28.000.000. 
  
    .titulo-con-imagen.mb-5(data-aos="fade-right")
      .titulo-con-imagen__fondo
        img.titulo-con-imagen__imagen(src="@/assets/componentes/1.png")
        h3.titulo-con-imagen__texto Interés compuesto
    
    p.mb-5(data-aos="fade-down") Interés generado en un periodo de tiempo, con la característica especial de ser capitalizable; es decir, se acumula, con el capital, presentando un interés mayor al final del periodo. 

    .row.mb-5
      .col-lg-5.mb-4.mb-lg-0.order-lg-2.d-none.d-md-block
        figure
          img(src="@/assets/curso/tema1/17.png", data-aos="zoom-in", style="max-width: 500px").mx-auto
      .col-lg-7.order-lg-1
        .row.align-items-start.mb-3
          .col-md-auto.mb-3.mb-lg-0
            img(src="@/assets/curso/tema1/11.svg", style="max-width: 90px").mx-auto
          .col-md
            p <b>Ejemplo 1:</b> Carolina invierte hoy $12.000.000 en una cuenta que paga el 9 % compuesto anual, ¿qué cantidad podrá retirar dentro de 3 años?
        .bg-color-8.p-4.tarjeta.mb-3(data-aos="fade-left")
          p.mb-0(data-aos="fade-left") El enunciado anterior refleja la necesidad de hallar el valor futuro, teniendo en cuenta que se conoce el valor inicial de la inversión y se desea saber el valor final dentro de 3 años. Recuerde que la tasa de interés se manejará en decimales para efectos de su cálculo.
        p.mb-4 La fórmula que debe usarse es:
        .titulo-sexto.color-acento-contenido.mb-3
          h5 Figura 3.
          span Cálculo del valor futuro con interés compuesto
        .row.justify-content-center.mb-3
          .col-lg-9
            figure
              img(src="@/assets/curso/tema1/16.svg", data-aos="zoom-in", alt="Diagrama con fórmula de valor futuro usando interés compuesto, representada como VF=VA(1+i)n, con un ejemplo que parte de $12.000.000, una tasa del 9 % anual y un periodo de 3 años, resultando en un valor futuro de $15.540.348, ilustrado con línea de tiempo.")
        .bg-color-8.p-4.tarjeta.mb-3(data-aos="fade-left")
          p.mb-0(data-aos="fade-left") <b>Respuesta:</b> Carolina con una inversión inicial de $12.000.000 recibirá $15.540.348, dentro de tres años aplicando interés compuesto.

    p.mb-4(data-aos="fade-down") Así mismo se puede obtener el Valor Futuro (VF), utilizando la fórmula financiera de Excel llamada VF, la cual se presenta a continuación:

    div.tarjeta.bg-color-8.p-4.mb-5
      .row.justify-content-center.align-items-center
        .col-lg-6.mb-3.mb-lg-0(data-aos="fade-right")
          .titulo-sexto.color-acento-contenido
            h5 Figura 4.
            span Cálculo del valor futuro (VF) en función financiera de Excel
          figure
            img(src="@/assets/curso/tema1/18.png", data-aos="zoom-in", alt=" Ventana de argumentos de función en Excel para calcular el valor futuro (VF) de una inversión, con campos para ingresar tasa de interés, número de periodos (Nper), pago periódico, valor actual (Va) y tipo de vencimiento. Incluye una breve descripción de cada parámetro.")
          
        .col-lg-6.mb-3.mb-lg-0(data-aos="fade-left")
          p <b>VF(tasa;nper;pago;(va);tipo),</b> teniendo en cuenta que:
          ul.lista-ul--color.mb-5
            li.mb-3.d-flex
              i.fas.fa-chevron-right.bg-color-17
              p.mb-0 <b>Tasa:</b> es la tasa de interés del período acordado.
            li.mb-3.d-flex
              i.fas.fa-chevron-right.bg-color-17
              p.mb-0 <b>Nper:</b> es el número total de períodos.
            li.mb-3.d-flex
              i.fas.fa-chevron-right.bg-color-17
              p.mb-0 <b>Pago:</b> es el pago efectuado en cada período.
            li.mb-3.d-flex
              i.fas.fa-chevron-right.bg-color-17
              p.mb-0 <b>Va:</b> es el valor actual o suma total del valor de una serie de pagos.
            li.mb-3.d-flex
              i.fas.fa-chevron-right.bg-color-17
              p.mb-0 <b>Tipo:</b> es un valor lógico. Se registra “0” para una tasa vencida y “1” para tasa anticipada.
          p Es importante señalar que, para realizar los cálculos en Excel, debe estar registrada información, con el fin de ser tomada de cada una de las celdas y de esta manera refleje la formulación para su respectiva interpretación.

    .row.mb-5
      .col-lg-5.mb-4.mb-lg-0.order-lg-2.d-none.d-md-block
        figure
          img(src="@/assets/curso/tema1/20.svg", data-aos="zoom-in", style="max-width: 400px").mx-auto
      .col-lg-7.order-lg-1
        .row.align-items-start.mb-3
          .col-md-auto.mb-3.mb-lg-0
            img(src="@/assets/curso/tema1/11.svg", style="max-width: 90px").mx-auto
          .col-md
            p <b>Ejemplo 2:</b> Andrés recibirá en 10 meses $35.000.000, correspondientes a una inversión realizada. Si la tasa de interés que le están pagando es del 2,5 % mensual, ¿cuál es el valor inicial de la inversión, aplicando el tipo de interés compuesto? 
        .bg-color-1.p-4.tarjeta.mb-3(data-aos="fade-left")
          p.mb-0(data-aos="fade-left") De acuerdo con el análisis, se observa que se debe determinar el valor presente o actual de la inversión realizada, utilizando el tipo de interés compuesto; por lo tanto, se usará la siguiente fórmula: 
        .titulo-sexto.color-acento-contenido.mb-3
          h5 Figura 5.
          span Valor actual con fórmula de interés compuesto
        .row.justify-content-center.mb-3
          .col-lg-9
            figure
              img(src="@/assets/curso/tema1/19.svg", data-aos="zoom-in", alt="Fórmula del valor actual bajo interés compuesto representada como VA=VF/(1+i)^n,  aplicada a un valor futuro de $35.000.000 con una tasa del 2,5 % durante 10 años, obteniendo un valor actual de $27.341.944,06.")
        .bg-color-1.p-4.tarjeta.mb-3(data-aos="fade-left")
          p.mb-0(data-aos="fade-left") <b>Respuesta:</b>  para obtener un monto de $35.000.000 durante 10 meses, a la tasa del 2,5 %, debe invertir $27.341.944,06. 
    
    p.mb-4(data-aos="fade-down") También se puede obtener el Valor Actual (VA), utilizando la fórmula financiera de Excel llamada VA, la cual se presenta a continuación:

    div.tarjeta.bg-color-1.p-4.mb-5
      .row.justify-content-center.align-items-center
        .col-lg-6.mb-3.mb-lg-0(data-aos="fade-right")
          .titulo-sexto.color-acento-contenido
            h5 Figura 6.
            span  Cálculo del valor actual (VA) en función financiera de Excel
          figure
            img(src="@/assets/curso/tema1/21.png", data-aos="zoom-in", alt="Ventana de argumentos de función en Excel para calcular el valor actual (VA) de una inversión, con campos para ingresar tasa, número de periodos (Nper), pago periódico, valor futuro (Vf) y tipo de vencimiento")
          
        .col-lg-6.mb-3.mb-lg-0(data-aos="fade-left")
          p <b>VA(tasa;nper;pago;(vf);tipo),</b> teniendo en cuenta que:
          ul.lista-ul--color.mb-5
            li.mb-3.d-flex
              i.fas.fa-chevron-right.bg-color-17
              p.mb-0 <b>Tasa:</b> es la tasa de interés del período acordado.
            li.mb-3.d-flex
              i.fas.fa-chevron-right.bg-color-17
              p.mb-0 <b>Nper:</b>  es el número total de períodos.
            li.mb-3.d-flex
              i.fas.fa-chevron-right.bg-color-17
              p.mb-0 <b>Pago:</b> es el pago efectuado en cada período.
            li.mb-3.d-flex
              i.fas.fa-chevron-right.bg-color-17
              p.mb-0 <b>Vf:</b> valor futuro o suma total de lo que se desea obtener después de efectuar el último pago.
            li.mb-3.d-flex
              i.fas.fa-chevron-right.bg-color-17
              p.mb-0 <b>Tipo:</b> es un valor lógico. Se registra “0” para una tasa vencida y “1” para tasa anticipada.
    
    .row.mb-5
      .col-lg-5.mb-4.mb-lg-0.order-lg-2.d-none.d-md-block
        figure
          img(src="@/assets/curso/tema1/23.svg", data-aos="zoom-in", style="max-width: 400px").mx-auto
      .col-lg-7.order-lg-1
        .row.align-items-start.mb-3
          .col-md-auto.mb-3.mb-lg-0
            img(src="@/assets/curso/tema1/11.svg", style="max-width: 90px").mx-auto
          .col-md
            p <b>Ejemplo 3:</b> María realiza una inversión por valor de $750.000, por un periodo de 3 años. Al finalizar el tiempo le entregan $868.219. ¿Cuál es la tasa de interés compuesto aplicada? Una vez despejada la fórmula principal, se utilizará la siguiente fórmula: 
        .titulo-sexto.color-acento-contenido.mb-3
          h5 Figura 7.
          span Fórmula, solución analítica ejemplo 3
        .row.justify-content-center.mb-3
          .col-lg-9
            figure
              img(src="@/assets/curso/tema1/22.svg", data-aos="zoom-in", alt="Fórmula de la tasa de interés compuesta aplicada en el ejemplo 3, representada como i = (868.219 / 750.000)^(1 / 3) - 1, donde 868.219 es el valor final recibido, 750.000 el valor invertido inicialmente, y 3 el número de años de la inversión.")
        .bg-color-10.p-4.tarjeta.mb-3(data-aos="fade-left")
          p.mb-0(data-aos="fade-left") <b>Respuesta:</b>  la tasa aplicada en la inversión es del 5 % anual.
    
    div.tarjeta.bg-color-10.p-4.mb-5
      .row.justify-content-center.align-items-center
        .col-lg-6.mb-3.mb-lg-0(data-aos="fade-right")
          .titulo-sexto.color-acento-contenido
            h5 Figura 8.
            span  Cálculo de la tasa de interés en función financiera de Excel
          figure
            img(src="@/assets/curso/tema1/24.png", data-aos="zoom-in", alt="Ventana de argumentos de función en Excel para calcular la tasa de interés por periodo de un préstamo o inversión, con campos para ingresar número de periodos (Nper), pago periódico, valor actual (Va), valor futuro (Vf) y tipo de vencimiento.)")
          
        .col-lg-6.mb-3.mb-lg-0(data-aos="fade-left")
          p <b>Tasa(nper;pago;va;(vf);tipo),</b> teniendo en cuenta que:
          ul.lista-ul--color.mb-5
            li.mb-3.d-flex
              i.fas.fa-chevron-right.bg-color-17
              p.mb-0 <b>Nper:</b>  es el número total de períodos.
            li.mb-3.d-flex
              i.fas.fa-chevron-right.bg-color-17
              p.mb-0 <b>Pago:</b> es el pago efectuado en cada período.
            li.mb-3.d-flex
              i.fas.fa-chevron-right.bg-color-17
              p.mb-0 <b>Va:</b> es el valor actual o suma total del valor de una serie de pagos.
            li.mb-3.d-flex
              i.fas.fa-chevron-right.bg-color-17
              p.mb-0 <b>Vf:</b> valor futuro o suma total de lo que se desea obtener después de efectuar el último pago.
            li.mb-3.d-flex
              i.fas.fa-chevron-right.bg-color-17
              p.mb-0 <b>Tipo:</b> es un valor lógico. Se registra “0” para una tasa vencida y “1” para tasa anticipada.
    
    .row.mb-5
      .col-lg-5.mb-4.mb-lg-0.order-lg-2.d-none.d-md-block
        figure
          img(src="@/assets/curso/tema1/26.png", data-aos="zoom-in", style="max-width: 500px").mx-auto
      .col-lg-7.order-lg-1
        .row.align-items-start.mb-3
          .col-md-auto.mb-3.mb-lg-0
            img(src="@/assets/curso/tema1/11.svg", style="max-width: 90px").mx-auto
          .col-md
            p <b>Ejemplo 4:</b> Sofía realiza un préstamo de $2.000.000, al final del período paga $3.443.143, la tasa cobrada es del 2,5 % mensual. Hallar el tiempo del préstamo.  Teniendo en cuenta la fórmula principal, se realiza el proceso para despejarla; por ende, se utilizará la siguiente fórmula:
        .titulo-sexto.color-acento-contenido.mb-3
          h5 Figura 9.
          span Cálculo del tiempo en operaciones financieras con logaritmos
        .row.justify-content-center.mb-3
          .col-lg-9
            figure
              img(src="@/assets/curso/tema1/25.svg", data-aos="zoom-in", alt="Ejemplo resuelto que muestra cómo calcular el tiempo de un préstamo usando logaritmos, con fórmula despejada n=log(VF/VA)log(1+i) valores aplicados a un préstamo de $2.000.000 con tasa del 2,5 % mensual y valor futuro de $3.443.143, resultando en un plazo de 22 meses.")
        .bg-color-16.p-4.tarjeta.mb-3(data-aos="fade-left")
          p.mb-0(data-aos="fade-left") <b>Respuesta:</b>  el tiempo del préstamo es de 22 meses.

    div.tarjeta.bg-color-16.p-4.mb-5
      .row.justify-content-center.align-items-center
        .col-lg-6.mb-3.mb-lg-0(data-aos="fade-right")
          .titulo-sexto.color-acento-contenido
            h5 Figura 10.
            span Cálculo del número de periodos (Nper) en función financiera de Excel
          figure
            img(src="@/assets/curso/tema1/27.png", data-aos="zoom-in", alt="Ventana de argumentos de función en Excel para calcular el número de pagos de una inversión, con campos para ingresar tasa de interés, pago periódico, valor actual (Va), valor futuro (Vf) y tipo de vencimiento.")
          
        .col-lg-6.mb-3.mb-lg-0(data-aos="fade-left")
          p <b>Nper(nper;pago;va;(vf);tipo),</b> teniendo en cuenta que:
          ul.lista-ul--color.mb-5
            li.mb-3.d-flex
              i.fas.fa-chevron-right.bg-color-17
              p.mb-0 <b>Nper:</b>  es el número total de períodos.
            li.mb-3.d-flex
              i.fas.fa-chevron-right.bg-color-17
              p.mb-0 <b>Pago:</b> es el pago efectuado en cada período.
            li.mb-3.d-flex
              i.fas.fa-chevron-right.bg-color-17
              p.mb-0 <b>Va:</b> es el valor actual o suma total del valor de una serie de pagos.
            li.mb-3.d-flex
              i.fas.fa-chevron-right.bg-color-17
              p.mb-0 <b>Vf:</b> valor futuro o suma total de lo que se desea obtener después de efectuar el último pago.
            li.mb-3.d-flex
              i.fas.fa-chevron-right.bg-color-17
              p.mb-0 <b>Tipo:</b> es un valor lógico. Se registra “0” para una tasa vencida y “1” para tasa anticipada.
    
    separador

    #t_1_3.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 1.3 Tasa nominal, periódica y efectiva
    
    p.mb-5(data-aos="fade-down") Para aplicar adecuadamente las matemáticas financieras en los diferentes hechos económicos que se presentan en una empresa, surge la necesidad de identificar los conceptos y políticas para realizar los cálculos aritméticos. En el desarrollo de este proceso, es importante diferenciar las tasas de interés nominal, efectiva y periódica, las cuales pueden presentarse de forma anticipada o vencida; por lo tanto, a continuación, se relacionan las siguientes definiciones:

    .row
      .col-lg-4.mb-4.mb-lg-0
        figure
          img(src="@/assets/curso/tema1/28.png", data-aos="zoom-in", style="max-width: 500px").mx-auto
      .col-lg-8(data-aos="fade-left")
        AcordionA.mb-5(tipo="a" clase-tarjeta="tarjeta bg-color-11")
          div(titulo=" Tasa nominal")
            p.mb-0 Tasa que se genera en un periodo de tiempo y que no capitaliza; por lo tanto, se dice que se asemeja al interés simple. (Vidaurri, 2017)
          div(titulo="Tasa efectiva")
            p.mb-0 Tasa que efectivamente se reconoce en la transacción financiera. Es capitalizable en el periodo de tiempo, haciendo referencia al interés compuesto. (Vidaurri, 2017).
          div(titulo="Tasa periódica")
            p.mb-0 Hace referencia al periodo de capitalización en el cual se realiza la operación financiera, la cual puede ser: diaria, mensual, bimestral, trimestral, cuatrimestral, semestral, anual, etc. (Vidaurri, 2017).
    
    h3.bg-color-4.tarjeta.p-3.mb-5  Tasa anticipada y vencida

    p.mb-4(data-aos="fade-down") Como se había mencionado, las tasas de interés se presentan de forma anticipada o vencida. A continuación se relaciona el significado de cada una:

    .bg-full-width.bg-fondo-2
      .px-4.px-md-5.pb-md-3
        .row.justify-content-center.mb-4
          .col-lg-10(data-aos="fade-right")
            .row.justify-content-center.align-items-center
              .col-lg-auto.mb-3.mb-lg-0.order-2
                figure
                  img(src='@/assets/curso/tema1/29.svg', alt='', style="max-width: 500px").mx-auto
              .col-lg.order-1.mb-3.mb-lg-0.align-content-center.pe-0
                div.bg-color-1.p-4
                  ul.lista-ul--color.mb-0.mt-2
                    li.mb-3.d-flex
                      i.fas.fa-chevron-right.bg-color-17
                      p.mb-0 <b>Anticipada (A):</b> se calcula el interés de forma anticipada en el respectivo periodo. (Vidaurri, 2017)
                    li.mb-3.d-flex
                      i.fas.fa-chevron-right.bg-color-17
                      p.mb-0 <b>Vencida (V):</b> se calcula el interés de forma vencida en el periodo. (Vidaurri, 2017)
        
        p.mb-5(data-aos="fade-down") Para aplicar los tipos de tasas de interés es importante conocer los periodos de capitalización, que se reconocen de la siguiente manera:
        .row.justify-content-center.align-items-center
          .col-lg-3.mb-3.mb-lg-0(data-aos="fade-right")
            figure
              img(src='@/assets/curso/tema1/30.png', alt='', style="max-width: 300px").mx-auto
          .col-lg-5(data-aos="fade-left")
            .titulo-sexto.color-acento-contenido
              h5 Tabla 1.
              span Frecuencias de capitalización y sus respectivas abreviaturas
            .tabla-a.color-acento-botones
              table
                thead
                  tr
                    th.bg-color-6.text-center Frecuencia de capitalización 
                    th.bg-color-6.text-center  Abreviatura
                    th.bg-color-6.text-center  Capitalización anual
                tbody
                  tr.bg-color-18
                    td.text-center 1
                    td.text-center A
                    td.text-center Anual
                  tr.bg-color-white
                    td.text-center 12
                    td.text-center M
                    td.text-center Mensual
                  tr.bg-color-18
                    td.text-center 6
                    td.text-center B
                    td.text-center Bimestral
                  tr.bg-color-white
                    td.text-center 4
                    td.text-center T
                    td.text-center Trimestral
                  tr.bg-color-18
                    td.text-center 3
                    td.text-center C
                    td.text-center Cuatrimestral
                  tr.bg-color-white
                    td.text-center 2
                    td.text-center S
                    td.text-center Semestral
                  tr.bg-color-18
                    td.text-center 24
                    td.text-center Q
                    td.text-center Quincenal
                  tr.bg-color-white
                    td.text-center 365
                    td.text-center D
                    td.text-center Diaria
      
    .titulo-con-imagen.mb-5(data-aos="fade-right")
      .titulo-con-imagen__fondo
        img.titulo-con-imagen__imagen(src="@/assets/componentes/1.png")
        h3.titulo-con-imagen__texto Equivalencia de tasas

    .row.mb-5
      .col-lg-3.order-2
        figure
          img(src="@/assets/curso/tema1/31.png", data-aos="zoom-in", style="max-width: 500px").mx-auto
      .col-lg-9.order-1.mb-3.mb-lg-0
        p(data-aos="fade-left") Hace referencia a la igualdad que debe existir entre el periodo de capitalización y el periodo de tiempo; para ejemplarizar, si la tasa se presenta de forma trimestral, el periodo debe darse de igual manera. Por lo tanto, de acuerdo con la operación se realizará la conversión de tasas con el fin de lograr su equivalencia (Vidaurri, 2017).
    
        .cajon.color-secundario.bg-color-1.p-4.mb-4
          p.mb-0 Para profundizar en la temática, recuerde explorar en la biblioteca del Servicio Nacional de Aprendizaje (SENA), donde encuentra libros de apoyo. 

    .titulo-con-imagen.mb-5(data-aos="fade-right")
      .titulo-con-imagen__fondo
        img.titulo-con-imagen__imagen(src="@/assets/componentes/1.png")
        h3.titulo-con-imagen__texto Fórmulas
      
    .row
      .col-lg-8.mb-5.mb-lg-0(data-aos="fade-right")
        LineaTiempoD.color-secundario
          div(numero="1" titulo="Conversión de tasa efectiva a tasa efectiva en periodos diferentes") 
            .titulo-sexto.color-acento-contenido.mb-3
              h5 Figura 11.
              span Conversión de tasa efectiva entre periodos distintos
            figure.mt-3.mb-3
              img(src="@/assets/curso/tema1/33.svg", data-aos="zoom-in", alt="Fórmula para convertir una tasa efectiva entre distintos periodos, expresada como ie=((1+i)(n1/n2)-1), acompañada de la definición de variables: tasa efectiva deseada, tasa conocida, y periodos correspondientes de ambas tasas.")
            p <b>Ejemplo:</b> convertir el 8 % Efectivo Mensual (EF) a Efectivo Semestral (ES).
            h5 i<sub>e</sub> = ((1+0,08) (12/2)) – 1
            h5 i<sub>e</sub> = 58, 69 % Efectivo semestral (ES)
          div(numero="2" titulo="Conversión de tasa efectiva a tasa nominal") 
            .titulo-sexto.color-acento-contenido.mb-3
              h5 Figura 12.
              span Conversión de tasa efectiva a nominal
            figure.mt-3.mb-3
              img(src="@/assets/curso/tema1/33-1.svg", data-aos="zoom-in", alt="Fórmula de conversión de tasa efectiva a nominal, representada como j = ((1 + iₑ)^(n1 / n2) - 1) x n, donde j es la tasa nominal, iₑ es la tasa efectiva conocida, n1 es el periodo de la tasa conocida, n2 el periodo al que se quiere convertir, y n el número de periodos en el año.")
            p <b>Ejemplo:</b> se tiene una tasa del 24 % Efectiva Anual (EA), realizar la conversión a nominal mensual equivalente.
            h5 j = ((1+ 0,24 ) (1/12)   -1 ) * 12
            h5 j = 21,71 % Nominal Mensual (NM)
          div(numero="3" titulo="Conversión de tasa nominal vencida a tasa efectiva") 
            .titulo-sexto.color-acento-contenido.mb-3
              h5 Figura 13.
              span Conversión de tasa nominal vencida a efectiva
            figure.mt-3.mb-3
              img(src="@/assets/curso/tema1/33-2.svg", data-aos="zoom-in", alt="Fórmula para convertir una tasa nominal vencida a efectiva, expresada como ie=(1+in1)(n1/n2)-1, junto con la definición de sus variables: tasa efectiva, tasa conocida, y periodos asociados a ambas tasas.")
            p <b>Ejemplo:</b> se tiene una tasa del 24 % nominal anual mes vencido, hallar la tasa efectiva anual.
            h5 i<sub>e</sub> = (1+ 0,24/12 ) (12/1)  -1 
            h5 i<sub>e</sub> = 26,82 % Efectiva Anual (EA) 
          div(numero="4" titulo="Conversión de tasa nominal anticipada a efectiva") 
            .titulo-sexto.color-acento-contenido.mb-3
              h5 Figura 14.
              span Conversión de tasa nominal anticipada a tasa efectiva
            figure.mt-3.mb-3
              img(src="@/assets/curso/tema1/33-3.svg", data-aos="zoom-in", alt="Fórmula para convertir una tasa nominal anticipada a efectiva, representada como ie=(1-in1)(-n1/n2)-1, acompañada de las definiciones de la tasa efectiva, tasa conocida y los periodos correspondientes a cada una.")
            p <b>Ejemplo:</b> convertir el 23 % Nominal anual trimestral anticipada (NATA) a efectiva anual.
            h5 i<sub>e</sub> = (1-( 0,23/4 ) )(- 4/1)  -1 
            h5 i<sub>e</sub> = 26,72 % Efectiva Anual (EA) 
          div(numero="5" titulo="Conversión de tasa nominal a otra tasa nominal") 
            .titulo-sexto.color-acento-contenido.mb-3
            p Para convertir una tasa nominal a otra nominal, simplemente se multiplica o divide dependiendo de las condiciones. Una forma de realizar la conversión es, primero, hallar la nominal anual, y después, dividir en el periodo al cual se quiere llegar.
            p.mb-2 Pasos:
            ol.lista-ol--cuadro.ms-4
              li.d-flex 
                .lista-ol--cuadro__vineta
                  span 1
                | Hallar la tasa anual.
              li.d-flex 
                .lista-ol--cuadro__vineta
                  span 2
                | Luego, hallar el periodo buscado.
            p <b>Ejemplo:</b> se tiene una tasa 12 % Nominal Trimestral (NT), se solicita hallar la tasa Nominal Anual (NA).
            h5.ms-3.mb-0 n = 12 * 4
            h5.ms-3 n = 48 % Nominal Anual (NA)
            p.mb-0 Se multiplica por cuatro (4), teniendo en cuenta que son los trimestres de un año.
      .col-lg-4.order-2(data-aos="fade-left")
        figure
          img(src="@/assets/curso/tema1/32.png", data-aos="zoom-in", style="max-width: 380px").mx-auto

    separador

    #t_1_4.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 1.4 Tablas de amortización
    
    .row.mb-5
      .col-lg-4.order-2
        figure
          img(src="@/assets/curso/tema1/34.svg", data-aos="zoom-in")
      .col-lg-8.order-1.mb-3.mb-lg-0(data-aos="fade-right")
        .bloque-texto-b.color-secundario.p-4
          .bloque-texto-b__texto.mb-2
            i.fas.fa-quote-left
            h4.text-regular Es una matriz que presenta las cuotas periódicas de un préstamo, teniendo en cuenta el capital inicial, los intereses generados y el abono que se realiza, conforme al acuerdo entre deudor y acreedor 
            i.fas.fa-quote-right
          .bloque-texto-d__autor 
            .h5.mb-0 (Meza, 2017).

    p.mb-4(data-aos="fade-down") Para elaborar la tabla de amortización, es importante analizar los siguientes conceptos:

    .row.mb-4
      .col-sm-6.col-lg-3.mb-4.mb-lg-0(data-aos="fade-down")
        .tarjeta--boton.bg-color-3.p-4.h-100
          .row.justify-content-center.mb-3
            .col-7
              figure
                img(src='@/assets/curso/tema1/35.svg', alt='Texto que describa la imagen')

          h3.text-center Tasa (i)
          p Porcentaje que se aplica al valor de la deuda, teniendo en cuenta la igualdad entre el periodo de capitalización y periodo de tiempo.
      .col-sm-6.col-lg-3.mb-4.mb-lg-0(data-aos="fade-up")
        .tarjeta--boton.bg-color-3.p-4.h-100
          .row.justify-content-center.mb-3
            .col-7
              figure
                img(src='@/assets/curso/tema1/36.svg', alt='Texto que describa la imagen')

          h3.text-center Capital prestado (C<sub>0</sub>)
          p Valor del préstamo, este se tiene en cuenta para determinar la cuota junto con las condiciones pactadas.
      .col-sm-6.col-lg-3.mb-4.mb-lg-0(data-aos="fade-down")
        .tarjeta--boton.bg-color-3.p-4.h-100
          .row.justify-content-center.mb-3
            .col-7
              figure
                img(src='@/assets/curso/tema1/37.svg', alt='Texto que describa la imagen')
          h3.text-center Periodicidad (n)
          p Tiempo acordado para cancelar la deuda, se define en número de cuotas.
      .col-sm-6.col-lg-3.mb-4.mb-lg-0(data-aos="fade-down")
        .tarjeta--boton.bg-color-3.p-4.h-100
          .row.justify-content-center.mb-3
            .col-7
              figure
                img(src='@/assets/curso/tema1/38.svg', alt='Texto que describa la imagen')
          h3.text-center Cuota periódica constante (a)
          p Corresponde al valor de la cuota fija.
    
    .row.mb-5
      .col-lg-5.mb-4.mb-lg-0.order-lg-2.d-none.d-md-block
        figure
          img(src="@/assets/curso/tema1/38.png", data-aos="zoom-in", style="max-width: 500px").mx-auto
      .col-lg-7.order-lg-1(data-aos="fade-left")
        .row.align-items-start.mb-3
          .col-md-auto.mb-3.mb-lg-0
            img(src="@/assets/curso/tema1/11.svg", style="max-width: 90px").mx-auto
          .col-md
            p <b>Ejemplo 1:</b>  la siguiente tabla de amortización presenta el método francés, donde se establece la cuota fija en el periodo de pago acordado.
        .cajon.color-acento-contenido.p-4.mb-4
          p.mb-0 La empresa Supercueros SAS, realiza un préstamo por valor de $12.000.000, a una tasa del 1,7 % EM, por un periodo de tiempo de 6 meses.
        .row.justify-content-center
          .col-lg-12
            .titulo-sexto.color-acento-contenido
                h5 Tabla 2.
                span Condiciones de un préstamo con tasa mensual
            .tabla-a.color-acento-botones
              table
                thead
                  tr
                    th.bg-color-6.text-center Concepto 
                    th.bg-color-6.text-center  Valor
                    th.bg-color-6.text-center  Frecuencia
                tbody
                  tr.bg-color-18
                    td Préstamo
                    td.text-center $12.000.000
                    td.text-center - 
                  tr.bg-color-white
                    td Tasa
                    td.text-center 1,70 %
                    td.text-center Mensual
                  tr.bg-color-18
                    td Periodo
                    td.text-center 6
                    td.text-center -

    .row.justify-content-center.align-items-center.mb-5
      .col-lg-3.mb-3.mb-lg-0(data-aos="fade-right")
        figure
          img(src='@/assets/curso/tema1/39.png', alt='', style="max-width: 300px").mx-auto
      .col-lg-8(data-aos="fade-left")
        .titulo-sexto.color-acento-contenido
          h5 Tabla 3.
          span Tabla de amortización para un préstamo a seis meses
        .tabla-a.color-acento-botones
          table
            thead
              tr
                th.bg-color-6.text-center No 
                th.bg-color-6.text-center CUOTA
                th.bg-color-6.text-center INTERÉS
                th.bg-color-6.text-center AMORTIZACIÓN
                th.bg-color-6.text-center SALDO
            tbody
              tr.bg-color-white
                td.text-center 0
                td.text-right -
                td.text-right -
                td.text-right -
                td.text-right $12.000.000 
              tr.bg-color-18
                td.text-center 1
                td.text-right $2.120.671,37
                td.text-right $204.000 
                td.text-right $1.916.671,37
                td.text-right $10.083.329 

              tr.bg-color-white
                td.text-center 2
                td.text-right $2.120.671,37
                td.text-right $171.417 
                td.text-right $1.949.254,78
                td.text-right $8.134.074 

              tr.bg-color-18
                td.text-center 3
                td.text-right $2.120.671,37
                td.text-right $138.279  
                td.text-right $1.982.392,12
                td.text-right $6.151.682 

              tr.bg-color-white
                td.text-center 4
                td.text-right $2.120.671,37
                td.text-right $104.579 
                td.text-right $2.016.092,78
                td.text-right $4.135.589 
 
              tr.bg-color-18
                td.text-center 5
                td.text-right $2.120.671,37
                td.text-right $70.305 
                td.text-right $2.050.366,36
                td.text-right $2.085.223 
 
              tr.bg-color-white
                td.text-center 6
                td.text-right $2.120.671,37
                td.text-right $35.449
                td.text-right $2.085.222,59
                td.text-right $0
              tr.bg-color-18
                td.text-center 
                td.text-right $12.724.028,23
                td.text-right $724.028,23
                td.text-right $12.000.000,00
                td.text-right -

    .bg-full-width.bg-fondo-slider.mb-5
      .p-4.p-md-5
        SlyderA(tipo="b").bg-white.p-4.tarjeta(data-aos="fade-left")
          .row.align-items-center.p-4.p-md-5
            .col-lg-5.order-2
              figure
                img(src="@/assets/curso/tema1/40.png", alt="")
            .col-lg-7.order-1.mb-3.mb-lg-0
              h4 Procedimiento
              ol.lista-ol--cuadro.ms-4
                li.d-flex.mb-3 
                  .lista-ol--cuadro__vineta
                    span 1
                  | El valor de la cuota fija se calcula aplicando la siguiente fórmula:
                .row.justify-content-center.mb-3
                  .col-lg-6.mb-3.mb-lg-0
                    figure
                      img(src="@/assets/curso/tema1/41.svg", alt="Fórmula para calcular el valor de la cuota fija, representada como a = C₀ x [i / (1 - (1 + i)^-n)], donde a es la cuota fija, C₀ es el capital inicial, i es la tasa de interés por periodo, y n es el número total de periodos.")
                li.d-flex 
                  .lista-ol--cuadro__vineta
                    span 2
                  | El interés se calcula multiplicando el saldo anterior del préstamo por la tasa acordada.
                li.d-flex 
                  .lista-ol--cuadro__vineta
                    span 3
                  | La amortización se determina restando el valor de la cuota, menos el interés.
                li.d-flex 
                  .lista-ol--cuadro__vineta
                    span 4
                  | El saldo se obtiene restando el saldo anterior, menos el valor de la amortización.

          .row.align-items-center.p-4.p-md-5
            .col-lg-6.mb-3.mb-lg-0.order-2
              figure
                img(src="@/assets/curso/tema1/42.png", alt="Ventana de Excel para ingresar argumentos de la función financiera PAGO, que incluye campos para Tasa, Nper, Va, Vt y Tipo, con una descripción sobre el cálculo del pago de un préstamo con tasa de interés constante.")
            .col-lg-6.mb-3.mb-lg-0.order-1.mb-3.mb-lg-0
              p Así mismo, se puede obtener el valor de la cuota fija, utilizando la fórmula financiera de Excel llamada PAGO, la cual se presenta a continuación:
              p <b>PAGO(tasa;nper;va;vf,tipo),</b> teniendo en cuenta que:
              ul.lista-ul--color.mb-5
                li.mb-3.d-flex
                  i.fas.fa-chevron-right.bg-color-17
                  p.mb-0 <b>Tasa:</b> es la tasa acordada al adquirir la obligación.
                li.mb-3.d-flex
                  i.fas.fa-chevron-right.bg-color-17
                  p.mb-0 <b>Nper:</b> es el número de períodos.
                li.mb-3.d-flex
                  i.fas.fa-chevron-right.bg-color-17
                  p.mb-0 <b>Va:</b> Valor actual (valor del préstamo).
                li.mb-3.d-flex
                  i.fas.fa-chevron-right.bg-color-17
                  p.mb-0 <b>Vf:</b>  Valor futuro.
                li.mb-3.d-flex
                  i.fas.fa-chevron-right.bg-color-17
                  p.mb-0 <b>Tipo:</b> es un valor lógico. Se registra “0” para una tasa vencida y “1” para tasa anticipada.
    
    .row.align-items-start.mb-3
      .col-md-auto.mb-3.mb-lg-0
        img(src="@/assets/curso/tema1/11.svg", style="max-width: 90px").mx-auto
      .col-md
        p <b>Ejemplo 2:</b>  Teniendo en cuenta la información del ejercicio anterior, se supone un periodo de gracia de 2 meses.

    .row.justify-content-center.mb-5
      .col-lg-8.mb-3.mb-lg-0(data-aos="fade-right")
        .titulo-sexto.color-acento-contenido
            h5 Tabla 4.
            span Condiciones del préstamo con período de gracia
        .tabla-a.color-acento-botones
          table
            thead
              tr
                th.bg-color-6.text-center Concepto 
                th.bg-color-6.text-center  Valor
                th.bg-color-6.text-center  Frecuencia
            tbody
              tr.bg-color-18
                td Préstamo
                td.text-center $12.000.000
                td.text-center - 
              tr.bg-color-white
                td Tasa
                td.text-center 1,70 %
                td.text-center Mensual
              tr.bg-color-18
                td Período
                td.text-center 6
                td.text-center -
              tr.bg-color-white
                td Período De Gracia
                td.text-center 2
                td.text-center Meses
    .row.mb-5.justify-content-center
      .col-lg-8(data-aos="fade-left")
        .titulo-sexto.color-acento-contenido
          h5 Tabla 5.
          span  Tabla de amortización con período de gracia para un préstamo a seis meses
        .tabla-a.color-acento-botones
          table
            thead
              tr
                th.bg-color-6.text-center No 
                th.bg-color-6.text-center CUOTA
                th.bg-color-6.text-center INTERÉS
                th.bg-color-6.text-center AMORTIZACIÓN
                th.bg-color-6.text-center SALDO
            tbody
              tr.bg-color-white
                td.text-center 0
                td.text-right -
                td.text-right -
                td.text-right -
                td.text-right $12.000.000 
              tr.bg-color-18
                td.text-center 1
                td.text-right $0,00
                td.text-right $204.000  
                td.text-right.bg-color-20 -$204.000,00
                td.text-right $12.204.000 


              tr.bg-color-white
                td.text-center 2
                td.text-right $0,00
                td.text-right $207.468 
                td.text-right.bg-color-20 -$207.468,00
                td.text-right $12.411.468 
 

              tr.bg-color-18
                td.text-center 3
                td.text-right $3.235.850,25
                td.text-right $210.995  
                td.text-right $3.024.855,29
                td.text-right $3.024.855,29

              tr.bg-color-white
                td.text-center 4
                td.text-right $3.235.850,25
                td.text-right $159.572 
                td.text-right $3.076.277,83
                td.text-right $6.310.335  
 
              tr.bg-color-18
                td.text-center 5
                td.text-right $3.235.850,25
                td.text-right $107.276 
                td.text-right $3.128.574,55
                td.text-right $3.181.760  
 
              tr.bg-color-white
                td.text-center 6
                td.text-right $3.235.850,25
                td.text-right $54.090 
                td.text-right $3.181.760,32
                td.text-right $0
              tr.bg-color-18
                td.text-center.text-bold TOTAL
                td.text-right $12.943.400,99
                td.text-right $943.401 
                td.text-right $12.000.000,00
                td.text-right -

   
    .row.justify-content-center.mb-5
      .col-lg-10(data-aos="fade-right")
        .row.justify-content-center
          .col-lg-auto.mb-3.mb-lg-0.order-2.ps-0
            figure
              img(src='@/assets/curso/tema1/43.svg', alt='')
          .col-lg.order-1.mb-3.mb-lg-0.pe-0
            div.bg-color-9.p-4.h-100
              p Procedimiento
              ol.lista-ol--cuadro.ms-4
                li.d-flex.mb-3 
                  .lista-ol--cuadro__vineta
                    span 1
                  | Teniendo en cuenta que no hay cuota, se calculan los intereses, incrementando el saldo final.
                li.d-flex 
                  .lista-ol--cuadro__vineta
                    span 2
                  | Se calcula la cuota a partir del tercer mes, utilizando la fórmula de cuota fija, analizada en el ejercicio anterior. Se tiene en cuenta el número de periodos faltantes y el último saldo, con el fin de que coincida con el tiempo del préstamo.
                li.d-flex 
                  .lista-ol--cuadro__vineta
                    span 3
                  | Finalmente, se procede a elaborar la tabla, teniendo en cuenta el procedimiento realizado en la tabla de amortización de cuota fija. 
    
    .row.align-items-start.mb-3
      .col-md-auto.mb-3.mb-lg-0
        img(src="@/assets/curso/tema1/11.svg", style="max-width: 90px").mx-auto
      .col-md
        p <b>Ejemplo 3:</b>  continuamos con el ejercicio anterior, se presenta un abono a capital.

    .row.justify-content-center.mb-5
      .col-lg-8.mb-3.mb-lg-0(data-aos="fade-right")
        .titulo-sexto.color-acento-contenido
            h5 Tabla 6.
            span Condiciones del préstamo con abono extraordinario en el mes 3
        .tabla-a.color-acento-botones
          table
            thead
              tr
                th.bg-color-6.text-center Concepto 
                th.bg-color-6.text-center  Valor
                th.bg-color-6.text-center  Frecuencia
            tbody
              tr.bg-color-18
                td.text-bold Préstamo
                td.text-center $12.000.000
                td.text-center - 
              tr.bg-color-white
                td.text-bold Tasa
                td.text-center 1,70 %
                td.text-center Mensual
              tr.bg-color-18
                td.text-bold Período
                td.text-center 6
                td.text-center -
              tr.bg-color-white
                td.text-bold Abono
                td.text-center 3
                td.text-center Meses
              tr.bg-color-white
                td.text-bold Valor del abono
                td.text-center $2.000.000 
                td.text-center -
    .row.mb-5.justify-content-center
      .col-lg-8(data-aos="fade-left")
        .titulo-sexto.color-acento-contenido
          h5 Tabla 7.
          span Tabla de amortización con abono extraordinario en el mes 3
        .tabla-a.color-acento-botones
          table
            thead
              tr
                th.bg-color-6.text-center No 
                th.bg-color-6.text-center CUOTA
                th.bg-color-6.text-center INTERÉS
                th.bg-color-6.text-center AMORTIZACIÓN
                th.bg-color-6.text-center SALDO
            tbody
              tr.bg-color-white
                td.text-center 0
                td.text-right -
                td.text-right -
                td.text-right -
                td.text-right $12.000.000 
              tr.bg-color-18
                td.text-center 1
                td.text-right $2.120.671,37
                td.text-right $204.000  
                td.text-right $1.916.671,37
                td.text-right $10.083.329 

              tr.bg-color-white
                td.text-center 2
                td.text-right $2.120.671,37
                td.text-right $171.417 
                td.text-right $1.949.254,78
                td.text-right $8.134.074 
 

              tr.bg-color-18
                td.text-center 3
                td.text-right $4.120.671,37
                td.text-right $138.279   
                td.text-right $3.982.392,12
                td.text-right $4.151.682 

              tr.bg-color-white
                td.text-center 4
                td.text-right $1.431.210,68
                td.text-right $70.579  
                td.text-right $1.360.632,09
                td.text-right $2.791.050   
 
              tr.bg-color-18
                td.text-center 5
                td.text-right $1.431.210,68
                td.text-right $47.448 
                td.text-right $1.383.762,84
                td.text-right $1.407.287   
 
              tr.bg-color-white
                td.text-center 6
                td.text-right $1.431.210,68
                td.text-right $23.924 
                td.text-right $1.407.286,80
                td.text-right -
              tr.bg-color-18
                td.text-center.text-bold TOTAL
                td.text-right $12.655.646,15
                td.text-right $655.646 
                td.text-right $12.000.000,00
                td.text-right -
   
    .row.justify-content-center
      .col-lg-10(data-aos="fade-right")
        .row.justify-content-center
          .col-lg-auto.mb-3.mb-lg-0.order-2.ps-0
            figure
              img(src='@/assets/curso/tema1/44.svg', alt='')
          .col-lg.order-1.mb-3.mb-lg-0.pe-0
            div.bg-color-9.p-4
              p Procedimiento
              ol.lista-ol--cuadro.ms-4.mt-0
                li.d-flex.mb-3 
                  .lista-ol--cuadro__vineta
                    span 1
                  | Se calcula la cuota de igual forma como en el ejemplo 1, mediante cuota fija o pagos iguales.
                li.d-flex 
                  .lista-ol--cuadro__vineta
                    span 2
                  | De acuerdo con el mes y valor del abono, se suma el valor del abono a la cuota.
                li.d-flex 
                  .lista-ol--cuadro__vineta
                    span 3
                  | Se calcula nuevamente la cuota, teniendo en cuenta los periodos faltantes y el último saldo del préstamo. 
    
    separador

    #t_1_5.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 1.5 Alternativas de inversión
    
    
    figure.mb-5(data-aos="fade-down")
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/nHjl83QvSUw?si=PYOSxqLdAk88V5nb" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)

    .bg-full-width.bg-color-2
      .px-4.px-md-5.py-4
        .titulo-con-imagen.mb-5(data-aos="fade-right")
          .titulo-con-imagen__fondo
            img.titulo-con-imagen__imagen(src="@/assets/componentes/1.png")
            h3.titulo-con-imagen__texto Valor presente neto (VPN) 
        .row.mb-5
          .col-lg-5.order-lg-2.mb-3.mb-lg-0
            figure
              img(src="@/assets/curso/tema1/45.png", data-aos="zoom-in", style="max-width: 400px").mx-auto
          .col-lg-7.order-lg-1
            .bloque-texto-b.color-secundario.p-4.mb-3
              .bloque-texto-b__texto.mb-2
                i.fas.fa-quote-left
                h4.text-regular El valor presente neto es una cifra monetaria que resulta de comparar el valor presente de los ingresos con el valor presente de los ingresos. 
                i.fas.fa-quote-right
              .bloque-texto-d__autor 
                .h5.mb-0 (Meza, 2017).
            .cajon.color-secundario.bg-color-1.p-4.mb-4
              p.mb-0 El VPN es una alternativa de inversión utilizada frecuentemente para medir el desempeño de la inversión. Para su aplicación se tiene en cuenta la siguiente fórmula:

            .titulo-sexto.color-acento-contenido
              h5 Figura 15.   
              span Fórmula del Valor Presente Neto (VPN)
            .row.justify-content-center.mb-3
              .col-lg-10
                figure
                  img(src="@/assets/curso/tema1/45-1.svg", data-aos="zoom-in" alt="Expresión matemática del Valor Presente Neto que incluye el desembolso inicial negativo y la suma de flujos netos de efectivo futuros descontados a una tasa de oportunidad, representados como VPN=-P+FNE1(1+TO)^1+FNE2(1+TO)^2+⋯+FNEn(1+TO)^n")
            .row
              .col-lg-6.mb-3.mb-lg-0
                p.mb-0 P: inversión inicial
                p.mb-0 FNE: flujos netos de efectivo
                p TO: tasa de oportunidad del inversionista.
              .col-lg-6.mb-3.mb-lg-0
                p.mb-0 Interpretación:
                p.mb-0 VPN < cero “0” = No es viable (pérdida)
                p.mb-0 VPN > cero “0”  = Es viable (Ganancia)
                p.mb-0 VPN = cero “0”  = Indiferente 
        
        .row.mb-5
          .col-lg-5.mb-5.mb-lg-0.d-none.d-md-block
            figure
              img(src="@/assets/curso/tema1/46.svg", data-aos="zoom-in", style="max-width: 400px").mx-auto
          .col-lg-7(data-aos="fade-left")
            .row.align-items-start.mb-3
              .col-md-auto.mb-3.mb-lg-0
                img(src="@/assets/curso/tema1/11.svg", style="max-width: 90px").mx-auto
              .col-md
                p <b>Ejemplo:</b>  se desea realizar una inversión de $12.000.000, durante 4 años, a una tasa de descuento del 15 % anual. Los beneficios (flujos) recibidos por cada año son los siguientes:
            .row.justify-content-center.mb-3
              .col-lg-9
                .titulo-sexto.color-acento-contenido
                    h5 Tabla 8.
                    span Flujos de caja proyectados para evaluar una inversión de $12.000.000
                .tabla-a.color-acento-botones
                  table
                    thead
                      tr
                        th.bg-color-6.text-center Concepto 
                        th.bg-color-6.text-center  Valor
                      tr.bg-color-18
                        td.text-center Inversión
                        td.text-right $12.000.000
                      tr.bg-color-white
                        td.text-center Flujo Año 1
                        td.text-right $2.500.000
                      tr.bg-color-18
                        td.text-center Flujo Año 2
                        td.text-right $3.600.000
                      tr.bg-color-white
                        td.text-center Flujo Año 3
                        td.text-right $4.200.000
                      tr.bg-color-18
                        td.text-center Flujo Año 4
                        td.text-right $5.000.000

            .cajon.color-acento-contenido.p-4.mb-4
              p.mb-0 <b>NOTA:</b> determinar la viabilidad del proyecto, aplicando la fórmula de VPN o VNA.
            .row.justify-content-center.mb-3
              .col-lg-10
                figure
                  img(src="@/assets/curso/tema1/46-1.svg", data-aos="zoom-in")
            h5 VPN= -$1.483.635,35
        
        p(data-aos="fade-down") De acuerdo con la información suministrada, se observa que el proyecto no es viable, teniendo en cuenta que se genera una pérdida, sin recuperar el dinero invertido.

        p.mb-4(data-aos="fade-down") Así mismo se puede obtener el valor presente neto, utilizando la fórmula financiera de Excel llamada VNA, la cual se presenta a continuación:

        div.tarjeta.bg-color-16.p-4.mb-5
          .row.justify-content-center.align-items-center
            .col-lg-6.mb-3.mb-lg-0(data-aos="fade-right")
              .titulo-sexto.color-acento-contenido
                h5 Figura 16.
                span Ventana de argumentos de la función VNA en Excel
              figure
                img(src="@/assets/curso/tema1/47.png", data-aos="zoom-in", alt="Ventana de Excel para ingresar argumentos de la función financiera VNA, con campos para Tasa, Valor1 y Valor2. Incluye una descripción sobre el cálculo del valor neto presente de una inversión y botones para aceptar o cancelar.")
              
            .col-lg-6.mb-3.mb-lg-0(data-aos="fade-left")
              p <b>VNA(tasa;valor1;valor2;…),</b> teniendo en cuenta que:
              ul.lista-ul--color.mb-5
                li.mb-3.d-flex
                  i.fas.fa-chevron-right.bg-color-17
                  p.mb-0 <b>Tasa:</b> es la tasa de descuento.
                li.mb-3.d-flex
                  i.fas.fa-chevron-right.bg-color-17
                  p.mb-0 <b>Valor1:</b> corresponde a los pagos e ingresos, los cuales se presentan entre 1 y 254.
    
    .titulo-con-imagen.mb-5(data-aos="fade-right")
      .titulo-con-imagen__fondo
        img.titulo-con-imagen__imagen(src="@/assets/componentes/1.png")
        h3.titulo-con-imagen__texto Tasa Interna de Retorno (TIR)

    p.mb-4(data-aos="fade-down") La tasa interna de retorno TIR, es un indicador de rentabilidad que se utiliza en su mayoría para evaluar proyectos de inversión. Su cálculo se basa en los flujos de caja esperados del proyecto en determinados tiempos.

    .row.mb-5
      .col-lg-5.mb-3.mb-lg-0
        figure
          img(src="@/assets/curso/tema1/48.svg", data-aos="zoom-in", style="max-width: 450px").mx-auto
      .col-lg-7(data-aos="fade-left")
        .bloque-texto-b.color-secundario.p-4.mb-3
          .bloque-texto-b__texto.mb-2
            i.fas.fa-quote-left
            h4.text-regular Podemos definir, entonces, la TIR como aquella que es la máxima tasa de interés a la que un inversionista estaría dispuesto a pedir prestado dinero para financiar la totalidad del proyecto, pagando con los beneficios (flujos de efectivo) la totalidad del capital y de sus intereses, sin perder un solo centavo. 
            i.fas.fa-quote-right
          .bloque-texto-d__autor 
            .h5.mb-0 (Meza, 2017).
        p La fórmula aplicable en este caso es:

        .titulo-sexto.color-acento-contenido
          h5 Figura 17.
          span Fórmula de la Tasa Interna de Retorno (TIR)
        .row.justify-content-center.mb-3
          .col-lg-10
            figure
              img(src="@/assets/curso/tema1/49.svg", data-aos="zoom-in" alt="Ecuación que representa la Tasa Interna de Retorno, donde la inversión inicial se iguala a la suma de los flujos netos de efectivo descontados por la TIR en distintos periodos, expresados como Inversion=FNE1(1+TIR)^1+FNE2(1+TIR)^2+⋯+FNEn(1+TIR)^n")
        p.mb-0 Interpretación:
        p.mb-0 Tasa de descuento > TIR = No es viable (pérdida)
        p.mb-0 Tasa de descuento < TIR = Es viable (Ganancia)
        p.mb-0 Tasa de descuento = TIR = Indiferente 

    .row.align-items-start.mb-3
      .col-md-auto.mb-3.mb-lg-0
        img(src="@/assets/curso/tema1/11.svg", style="max-width: 90px").mx-auto
      .col-md
        p <b>Ejemplo:</b>  Iván Méndez desea realizar una inversión de $20.000.000, el proyecto le ofrece los siguientes beneficios durante 6 años, de igual forma genera los presentes gastos:

    
    .titulo-sexto.color-acento-contenido(data-aos="fade-right")
        h5 Tabla 9.
        span Evaluación financiera de proyecto con flujo de caja proyectado y cálculo de VAN y TIR

    .tabla-a.color-acento-botones.mb-3(data-aos="fade-left")
      table
        thead
          tr
            th.bg-color-6.text-center Concepto 
            th.bg-color-6.text-center 0
            th.bg-color-6.text-center 1
            th.bg-color-6.text-center 2
            th.bg-color-6.text-center 3
            th.bg-color-6.text-center 4
            th.bg-color-6.text-center 5
            th.bg-color-6.text-center 6
            th.bg-color-6.text-center Indicador
            th.bg-color-6.text-center Valor
        tbody
          tr.bg-color-18
            td.text-center.text-bold Inversión
            td.text-right $20.000.000
            td.text-right $4.000.000 
            td.text-right $6.000.000 
            td.text-right $7.200.000 
            td.text-right $8.000.000 
            td.text-right $9.200.000 
            td.text-right $13.000.000 
            td.text-center.text-bold VAN  
            td.text-right $2.738.265 

          tr.bg-color-white
            td.text-center.text-bold Costos
            td.text-right -
            td.text-right $800.000 
            td.text-right $1.200.000 
            td.text-right $1.440.000  
            td.text-right $1.600.000  
            td.text-right $1.840.000 
            td.text-right $2.600.000  
            td.text-center.text-bold TIR   
            td.text-center 18 % 
          tr.bg-color-18
            td.text-center.text-bold Flujo neto del proyecto
            td.text-center -$20.000.000 
            td.text-right $3.200.000 
            td.text-right $4.800.000  
            td.text-right $5.760.000   
            td.text-right $6.400.000   
            td.text-right $7.360.000  
            td.text-right $10.400.000   
            td.text-right -   
            td.text-right -
                
    p.mb-4(data-aos="fade-down") Para hallar el Valor Presente Neto (VPN o VNA) y la Tasa Interna de Retorno (TIR) se realizará a través de Microsoft Excel, para ello es importante relacionar la información con el fin de desarrollar las fórmulas básicas:

    .bg-full-width.bg-fondo-slider.mb-5
      .p-4.p-md-5
        SlyderA(tipo="b").bg-white.p-4.tarjeta(data-aos="fade-left")
          .row.align-items-center.p-4.p-md-5
            .col-lg-5.order-2
              figure
                img(src="@/assets/curso/tema1/50.png", alt="Ventana de Excel con la función financiera VNA aplicada, que contiene valores ingresados en los campos Tasa y Valor1.")
            .col-lg-7.order-1.mb-3.mb-lg-0
              h5 <b>VNA(tasa;valor1;valor2;…),</b> teniendo en cuenta que:
              ul.lista-ul--color.mb-5
                li.mb-3.d-flex
                  i.fas.fa-chevron-right.bg-color-17
                  p.mb-0 <b>Tasa:</b> es la tasa de descuento.
                li.mb-3.d-flex
                  i.fas.fa-chevron-right.bg-color-17
                  p.mb-0 <b>Valor1:</b> corresponde a los pagos e ingresos, los cuales se presentan entre 1 y 254.

          .row.align-items-center.p-4.p-md-5
            .col-lg-6.mb-3.mb-lg-0.order-2
              figure
                img(src="@/assets/curso/tema1/51.png", alt=" Ventana de Excel para ingresar argumentos de la función financiera TIR, con campos para Valores y Estimar. Incluye una serie de flujos de efectivo y muestra el resultado calculado de la tasa interna de retorno, junto con botones para aceptar o cancelar.")
            .col-lg-6.mb-3.mb-lg-0.order-1.mb-3.mb-lg-0
              h5 <b>TIR (valores;estimar),</b> teniendo en cuenta que:
              ul.lista-ul--color.mb-5
                li.mb-3.d-flex
                  i.fas.fa-chevron-right.bg-color-17
                  p.mb-0 <b>Valores:</b> corresponde a los números que se desea calcular la TIR.

                li.mb-3.d-flex
                  i.fas.fa-chevron-right.bg-color-17
                  p.mb-0 <b>Valor1:</b>  es el número que el usuario estima se aproximará a la TIR.

    .row
      .col-lg-6.mb-4.mb-lg-0(data-aos="fade-right")
        div.tarjeta.bg-color-8.p-4
          .row.justify-content-center.align-items-center
            .col-lg-12.mb-3.mb-lg-0
              p Respuesta:
              .titulo-sexto.color-acento-contenido
                h5 Tabla 10.
                span Indicadores de rentabilidad del proyecto
              .tabla-a.color-acento-botones
                table
                  thead
                    tr
                      th.bg-color-6.text-center  Indicador  
                      th.bg-color-6.text-center  Valor 

                  tbody
                    tr.bg-color-white
                      td.text-center.text-bold  VAN  
                      td.text-center.text-bold $2.738.264,85
                    tr.bg-color-18
                      td.text-center.text-bold  TIR   
                      td.text-center.text-bold 18 %
      .col-lg-6(data-aos="fade-left")
        P.mb-4 De acuerdo con lo anterior, se observa que el proyecto es viable, teniendo en cuenta que se recupera la inversión, además de generar una ganancia. La TIR (18 %) es mayor que la tasa de descuento (14 %).
        P Para ampliar esta información, usted deberá ingresar a la biblioteca del Servicio Nacional de Aprendizaje (SENA), donde encuentra libros de apoyo.

</template>

<script>
export default {
  name: 'Tema1',
  data: () => ({
    mostrarIndicadorTarjetaAudio: true,
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
