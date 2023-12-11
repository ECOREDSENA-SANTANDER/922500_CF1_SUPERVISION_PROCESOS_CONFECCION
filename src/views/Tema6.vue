<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    .titulo-principal.color-acento-botones
      .titulo-principal__numero
        span.numero 6
      h1.text-in Ordenes de producción

    .row.justify-content-center.align-items-center
      .col-lg-4
        img.img-t.img-a.my-2(src='@/assets/ilustraciones/img21.png', alt='') 
      .col-lg-8
        p La orden de producción es una plantilla o documento indispensable para identificar la trazabilidad de productos que se deben confeccionar en la organización, esto se debe a que en él se recopila toda la información de la prenda de vestir; en el desarrollo de la confección. Así mismo, permite llevar un control individualizado de cada pedido o trabajo que se está elaborando, por lo general, hay una orden de producción para cada tarea o para cada pedido.

        p Esta plantilla es del uso del área de diseño y de producción, en donde aparece la información no solo de las muestras o prototipos, sino también de la producción que se está desarrollando en el proceso productivo, esta orden puede utilizarse para cualquier prenda.

    p.mt-5 A continuación, se muestran los datos que se encuentran en la orden de producción como número de orden, tipo de prenda a elaborar, fecha de inicio, fecha prevista de terminación, cumplimiento, director de producción y jefe de sector. Por otro lado, en cuanto a la columna de materiales se especifica la clase de material, cantidad consumo, precio unitario, presupuesto, firma del encargado del depósito o almacén y producto terminado entregado. Dependiendo de la empresa, en la orden de producción se podría incluir la hoja de costos; que mide el valor de los materiales, mano de obra, costos indirectos, costos de producción, unidades producidas y costo unitario.
    .row.justify-content-center.align-items-center.mt-5
      .col-lg-10
        .BorTit Figura 9. Orden de producción camiseta tipo polo dama. Fuente: SENA 2021, Fernellis Mauricio Echeverry.
        img.img-t.img-a.mt-4(src='@/assets/ilustraciones/img22.svg', alt='')  
        p.mt-5.text-center Para profundizar en este tema se recomienda descargar y visitar los siguientes archivos
        .row.justify-content-between.align-items-center.mt-5
          .col-lg-4
            a.anexo(:href="obtenerLink('/downloads/1_La_Orden_de_Producción_en_Excel.xlsx')" target="_blank")
              .anexo__icono
                img(src="@/assets/template/icono-xls.svg")
              .anexo__texto
                p #[b Anexo]. La orden de producción. 
          .col-lg-6
            a.anexo.mb-4.mb-lg-0(href="https://elibro-net.bdigital.sena.edu.co/es/lc/senavirtual/titulos/39442" target="_blank")
              .anexo__icono
                img(src="@/assets/template/icono-link.svg")
              .anexo__texto
                p #[b Enlace web]. Estudio del trabajo: una nueva visión, del sistema de Bibliotecas SENA. 

    Separador

    .titulo-segundo.color-acento-botones#t_6_1
      .h4 6.1  Hojas de Ruta     

    p La hoja de ruta en confección es el documento que permite verificar cuánto tiempo toma cada una de las fases del proceso productivo: Por lo tanto, es importante identificar cada fase del proceso y su respectivo tiempo de desarrollo en días.

    p Es importante saber que en la hoja de ruta es relevante el orden del proceso, por ejemplo: trazo, corte de piezas, realización de contra muestra, confección y terminación, todo esto para llevar un mejor control del producto. De esta manera, la hoja de ruta ayuda a la identificación de la trazabilidad del producto utilizando un diagrama de Gantt para identificar en qué etapa del proceso se desarrolla la ejecución del producto y si se están cumpliendo los tiempos previstos inicialmente.

    p La siguiente tabla muestra las definiciones del tiempo aproximado de cada proceso plasmado en una hoja de ruta.

    .row.justify-content-center.align-items-center.mt-5
      .col-lg-8
        .BorTit Figura 10. Hoja de Ruta. Fuente: SENA 2021, Fernellis Mauricio Echeverry.
        .tabla-b.mt-4
          .tabla-b__header.bg-table
            h5.mb-0.text-color Niveles del lenguaje
          table

            tr
              th.text-center 
                h4 Orden
              th.text-center 
                h4 Ruta
              th.text-center 
                h4 Días
            tr
              th.text-center 1
              th Diseño 
              th.text-center 1
            tr
              th.text-center 2 
              th Patronaje
              th.text-center 1
            tr
              th.text-center 3 
              th Tiempos de reposo para las telas 
              th.text-center 2
            tr
              th.text-center 4 
              th Extendido de la tela
              th.text-center 1
            tr
              th.text-center 5
              th Corte de la tela 
              th.text-center 1
            tr
              th.text-center 6
              th Tiqueteado de las piezas
              th.text-center 1
            tr
              th.text-center 7
              th Fusionado de entretelas
              th.text-center 1
            tr
              th.text-center 8 
              th Estampación
              th.text-center 2
            tr
              th.text-center 9
              th Confección
              th.text-center 1
            tr
              th.text-center 10
              th Terminación
              th.text-center 1     
            tr
              th.text-center 
              th 
                h4 Total días
              th.text-center 12                          

    .row.justify-content-center.align-items-center.mt-5
      .col-lg-6
        p Para abordar en profundidad la explicación de los procesos productivos de la empresa, visitar el portal web de Lafayette Sports.
        a.anexo.mt-4.mb-lg-0(href="https://www.lafayettesports.com.co/noticias/confeccion-deportiva/como-lograr-colecciones-deportivas-a-traves-de-un-proceso-de-confeccion-efectivo/2/" target="_blank")
          .anexo__icono
            img(src="@/assets/template/icono-link.svg")
          .anexo__texto
            p #[b Enlace web]. Estudio del trabajo: una nueva visión, del sistema de Bibliotecas SENA. 

    Separador

    .titulo-segundo.color-acento-botones#t_6_2
      .h4 6.2  Fichas técnicas
    p La Ficha técnica es un documento indispensable para mejorar la comunicación de la organización y esto se debe a que en ella se encuentra toda la información de cada etapa por la cual deben pasar las prendas de vestir en el desarrollo del proceso productivo.

    p La ficha cuenta con el orden específico en que se van realizando las prendas: diseño, patronaje, trazo, corte, tiqueteado, confección, y terminación. De esta forma, la ficha técnica es un elemento primordial para el departamento de diseño al informar de una manera estandarizada y sencilla las características técnicas de un producto a confeccionar, es de destacar que esta información tiene utilidad a nivel comercial y productivo.

    .row.justify-content-center.align-items-stretch.mt-5
      .col-lg-4.bloque-texto-c.color-acento-contenido.p-4
          i.fas.fa-quote-right
          h5.mb-2 Es el documento que da facilidad y precisión en la producción de una prenda de vestir 
          span Pinilla (2006, p. 51).
          i.fas.fa-quote-right.quite-pa

      .col-lg-8.bloque-texto-c.color-acento-contenido.p-4
          i.fas.fa-quote-right
          h5.mb-2 “Es un documento escrito (Gráfico), en la cual se registran todas las características técnicas del producto prenda, es el documento que registra todos los procesos de fabricación considerando información relevante desde que nace el requerimiento del cliente (Spec) o idea propia, siguiendo por la fase de desarrollo, producción y despacho” 
          span Huertas (2019, p. 54)
          i.fas.fa-quote-right.quite-pa


    p Los componentes de una ficha técnica en el desarrollo del formato no son fijos y se definirán de acuerdo a las necesidades puntuales de cada empresa, sin embargo, todas las fichas tienen encabezado, en este apartado se encuentra información importante como: la descripción de la prenda, código del producto, diseñador, tipo de colección, fechas,  nombre de la colección, autor del diseño, descripción detallada del diseño, a quien va dirigido, material textil, colores del material textil, tallas a realizar, accesorios.

    p En resumen, la ficha técnica se compone de varios elementos, en los que se muestra cada una de las fases que se desarrollan en la producción o el prototipo inicial y son las siguientes:

    .row.justify-content-center.align-items-center.mt-5
      .col-12.col-md-4.mb-5.mb-md-0
        img.img-t.img-a(src='@/assets/ilustraciones/img24.png', alt='')

      .col-12.col-md-6.mb-5.mb-md-0
        LineaTiempoD.color-primario
          p.text-small(numero="1" titulo="Diseño de la prenda") Aquí se encuentra el dibujo de la prenda, tanto del frente como de la parte trasera o posterior.
          
          p.text-small(numero="2" titulo="Corte") Se define las telas, insumos, avíos de la prenda.
          
          p.text-small(numero="3" titulo="Molderia") Se realizan los moldes que comprende la prenda a escala y se especifica cantidad de piezas por molde.
          
          p.text-small(numero="4" titulo="Especificaciones de confección") Orden operacional en que se encuentra el nombre de las operaciones, máquinas a utilizar, el tipo de costura, puntadas por pulgada, los aditamentos o guías que se utilizarán y tiempos estándar de la producción.

    .row.justify-content-center.align-items-center.mt-5
      .col-lg-6
        a.anexo(:href="obtenerLink('/downloads/2_FORMATO_DE_FICHA_TECNICA_EN_EXCEL.rtf')" target="_blank")
          .anexo__icono
            img(src="@/assets/template/icono-doc.svg")
          .anexo__texto
            p #[b Anexo]. Se recomienda explorar más el archivo de “Formato de ficha técnica”.

    Separador

    .titulo-segundo.color-acento-botones#t_6_3
      .h4 6.3  Consumo de Materiales   

    p El consumo de materiales se define como los elementos que se utilizan en la producción de prendas de vestir los cuales de acuerdo con el diseño tienen unas cantidades específicas de uso. Por un lado, conocer los consumos y costos de materiales de una empresa conlleva a manejar los recursos con mayor responsabilidad, por ello, se hace indispensable identificar los consumos y los costos de materiales utilizados en el proceso, estos consumos se miden en unidad de medida, ubicación, valor matriz con código empresa, cantidad, talla, además del valor de los materiales e insumos con los cuales se desarrolla la producción.

    .row.cajon.color-secundario.p-4.mt-5
      p.mb-0 De igual manera, en una empresa se puede realizar el consumo por prendas de insumos, materiales y los costos de la fabricación por prenda, también el consumo de material (Tela), sesgos e insumos, a través de tablas de Excel. De esta forma, se recuerda la empresa COATS CADENA que desde hace años facilita una plantilla en Excel y el software denominado SEAMWORKS para el correcto cálculo de hilo en la producción de prendas de vestir.
      .row.justify-content-center.align-items-center
        .col-lg-6
          a.anexo.mt-4.mb-lg-0(href="https://www.youtube.com/watch?v=gZb3vgnGYk8" target="_blank")
            .anexo__icono
              img(src="@/assets/template/icono-link.svg")
            .anexo__texto
              p #[b Enlace web]. Explorar el tutorial del software SEAMWORKS.      
    
    .row.justify-content-center.align-items-center.mt-5
      .col-lg-10
        p.text-center Aprender a generar el consumo de sesgos tiene suma importancia para la fabricación de cualquier prenda de vestir y con el formato adecuado se minimiza el tiempo del cálculo, para ello se necesita:

    .row.justify-content-center.align-items-center.mt-5
      .col-lg-10
        ImagenInfografica.color-acento-contenido
          template(v-slot:imagen)
            figure
              img(src='@/assets/ilustraciones/img25.svg', alt='Consumo de Materiales')
          .tarjeta.color-acento-botones.p-3(x="12%" y="41%")
            .h5.mb-2 1. Datos de la tela
            p Ancho bruto, ancho neto, elongación.

          .tarjeta.color-acento-botones.p-3(x="36.5%" y="47%")
            .h5.mb-2 2. Datos del sesgo
            p Ancho entrada de la guía, sentido.

          .tarjeta.color-acento-botones.p-3(x="68%" y="48%")
            .h5.mb-2 3. Datos del corte
            p Ancho bruto rollo (al través), ancho bruto rollo (al sesgo), sobrante extremos rollo, sobrante por cuchilla, longitud de cada empate.    

          .tarjeta.color-acento-botones.p-3(x="80%" y="21%")
            .h5.mb-2 4. Datos de confección
            p Desperdicio entre piezas, piezas a sesgar, escote frente, escote espalda.

          .tarjeta.color-acento-botones.p-3(x="89%" y="90%")
            .h5.mb-2 5. Número de tiras
            p Desperdicios, por tela, por corte, por confección.    

    .row.justify-content-center.align-items-center.mt-5
      .col-lg-10
        p.text-center Por último, para llegar al consumo por unidad se necesita número de unidades por retazo y este proceso genera metros, que es el valor que se necesita en el consumo de sesgos. 

        .row.justify-content-center.align-items-center.mt-5
          .col-lg-6
            a.anexo(:href="obtenerLink('/downloads/3_FORMATO_DE_CONSUMO_DE_HILOS.xls')" target="_blank")
              .anexo__icono
                img(src="@/assets/template/icono-xls.svg")
              .anexo__texto
                p #[b Anexo]. Explorar el siguiente documento llamado “Formato de consumo de hilos”.    
          .col-lg-6
            a.anexo(:href="obtenerLink('/downloads/4_FORMATOS_DE_CONSUMO_DE_SESGOS .xlsx')" target="_blank")
              .anexo__icono
                img(src="@/assets/template/icono-xls.svg")
              .anexo__texto
                p #[b Anexo]. Explorar el siguiente documento llamado “Formato de consumo de sesgos”.

</template>

<script>
export default {
  name: 'Tema6',
  data: () => ({
    // variables de vue
  }),
}
</script>

<style lang="sass" scoped></style>
