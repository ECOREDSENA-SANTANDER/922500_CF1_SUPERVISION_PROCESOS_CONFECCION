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
        img.img-t.img-a.my-2(src='@/assets/curso/Tema6/1.png', alt='') 
      .col-lg-8
        p.mb-4  La orden de producción es un documento esencial para rastrear la trazabilidad de los productos a confeccionar en la organización, ya que recopila toda la información de la prenda de vestir durante el proceso de confección. Además, permite controlar individualmente cada pedido o trabajo en desarrollo. Normalmente, hay una orden de producción para cada tarea o pedido.
        p Este documento es utilizado por el área de diseño y producción, y contiene información sobre muestras, prototipos y la producción en curso. Puede utilizarse para cualquier prenda. Los datos incluidos en la orden de producción son el número de orden, tipo de prenda, fecha de inicio, fecha prevista de finalización, cumplimiento, director de producción y jefe de sector. Además, la sección de materiales especifica la clase, cantidad, consumo, precio unitario, presupuesto y cuenta con la firma del encargado del almacén, así como la entrega del producto terminado. Algunas empresas también incluyen la hoja de costos, que detalla los materiales, mano de obra, costos indirectos, producción, unidades y costos unitarios.

    .row.justify-content-center.align-items-center.mt-5
      .col-lg-10
        .BorTit  #[b Figura 11.]  Orden de producción camiseta tipo polo dama. Fuente: SENA 2021, Fernellis Mauricio Echeverry.
        img.img-t.img-a.mt-4(src='@/assets/curso/Tema6/2.svg', alt='La imagen muestra una orden de producción para camisetas tipo polo dama, expedida el 26 de marzo de 2021 con destino a Almacenes ABC. Detalla la producción de 2469 unidades y lista los materiales necesarios, como tela, botones y hilo, junto con sus cantidades y costos.') 

    


    .row 
      .col-10.m-auto
        p.mt-5 Para profundizar en este tema se recomienda descargar y visitar los siguientes archivos:
        .tarjeta.tarjeta-color-primera.p-4.mb-5
          .row.justify-content-around.align-items-center
            .col-3.col-sm-2.col-lg-1.d-none.d-lg-block
              img(src="@/assets/curso/Tema6/3.svg")
            .col
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0
                  h3.mb-1 Anexo
                  p.text-small Para profundizar en este tema se recomienda descargar y visitar el siguiente archivo, la orden de producción.
                .col-sm-auto
                  a.boton.color-boton.texto-blanco(:href="obtenerLink('downloads/1_La_Orden_de_Produccion.xlsx')" target="_blank")
                    span Descargar
                    i.fas.fa-file-download

    .row 
      .col-10.m-auto
        .tarjeta.tarjeta-color-segunda.p-4.mb-5
          .row.justify-content-around.align-items-center
            .col-3.col-sm-2.col-lg-1.d-none.d-lg-block
              img(src="@/assets/curso/Tema6/4.svg")
            .col
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0
                  h3.mb-1 Estudio del trabajo
                  p.text-small Visite el siguiente enlace web: Estudio del trabajo: una nueva visión, del sistema de Bibliotecas SENA.
                .col-sm-auto
                  a.boton.color-boton.texto-blanco(href='https://elibro-net.bdigital.sena.edu.co/es/lc/senavirtual/titulos/39442' target="_blank")
                    span Ir al sitio
                    i.fas.fa-globe

     

    Separador

    .titulo-segundo.color-acento-botones#t_6_1
      .h4 6.1  Hojas de Ruta     

    .row.bg2.bg-norepeat
      .col-sm-2.col-lg-3.medida-imagen.m-5.d-none.d-lg-block
        img(src="@/assets/curso/Tema6/11.png")
      .col-sm-12.col-lg-8.m-1.p-All-cus
        .p-All-cus.mb-5.bg8
            p.mb-3 La hoja de ruta en confección es un documento que muestra el tiempo que toma cada fase del proceso productivo, en este punto es importante identificar cada fase y su respectivo tiempo de desarrollo en días, ya que el orden del proceso es crucial, por ejemplo: trazo, corte de piezas, realización de contra muestra, confección y terminación.
            p.mb-3 La hoja de ruta ayuda a identificar la trazabilidad del producto.
            p La siguiente tabla muestra las definiciones del tiempo aproximado de cada proceso plasmado en una hoja de ruta.

    .row.justify-content-center.align-items-center.mt-5.mb-5
      .col-lg-8
        .BorTit  #[b Figura 12.]   Hoja de Ruta. Fuente: SENA 2021, Fernellis Mauricio Echeverry.
        .tabla-b.mt-4
          .tabla-b__header.bg-table
            h5.mb-0.text-color Hoja de Ruta
          table(alt='La imagen muestra una "Hoja de Ruta" titulada "Figura 12. Hoja de Ruta. Fuente: SENA 2021, Fernellis Mauricio Echeverry." Presenta una tabla con cuatro etapas del proceso de producción de camisetas tipo polo dama, cada una con su duración en días: 1. Diseño - 1 día, 2. Patronaje - 1 día, 3. Tiempos de reposo de las telas - 2 días, 4. Extendido de la tela - 1 día')
            tr.celda-oscura
              th.text-center 
                h4 Orden
              th.text-center 
                h4 Ruta
              th.text-center 
                h4 Días
            tr.celda-clara
              th.text-center 1
              th Diseño 
              th.text-center 1
            tr.celda-oscura
              th.text-center 2 
              th Patronaje
              th.text-center 1
            tr.celda-clara
              th.text-center 3 
              th Tiempos de reposo de las telas 
              th.text-center 2
            tr.celda-oscura
              th.text-center 4 
              th Extendido de la tela
              th.text-center 
                
    p.mb-4 A continuación, en el siguiente video a partir de las imágenes tomadas del sitio web Lafayette Sports, se observan los procesos de la empresa que intervienen en la construcción de una prenda de vestir, la cual hace parte del desarrollo del proceso productivo y también de la hoja de ruta. 
                                        

    .row.justify-content-center.align-items-center.mb-5
      .col-lg-12(data-aos="fade-left")
        figure
          .video
            iframe(width="560" height="315" src="https://www.youtube.com/embed/IQDv_lj6XsI" title="Description" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
          figcaption Video. Sena 2024


    .row 
      .col-sm-12.col-lg-10.m-auto
        .tarjeta.tarjeta-color-segunda.p-3.mb-5
          .row.justify-content-around.align-items-center
            .col-3.col-sm-2.col-lg-1.d-none.d-lg-block
              img(src="@/assets/curso/Tema6/5.svg")
            .col
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0
                  h3.mb-1 Procesos productivos de la empresa
                  p.text-small Para abordar en profundidad la explicación de los procesos productivos de la empresa, visitar el portal web de Lafayette Sports.
                .col-sm-auto
                  a.boton.color-boton.texto-blanco(href="https://www.lafayettesports.com.co/noticias/confeccion-deportiva/como-lograr-colecciones-deportivas-a-traves-de-un-proceso-de-confeccion-efectivo/2/" target="_blank")
                    span Ir al sitio
                    i.fas.fa-file-download

    Separador

    .titulo-segundo.color-acento-botones#t_6_2
      .h4 6.2  Fichas Técnicas
    p.mb-3 La Ficha técnica es un documento indispensable para mejorar la comunicación de la organización y esto se debe a que en ella se encuentra toda la información de cada etapa por la cual deben pasar las prendas de vestir en el desarrollo del proceso productivo.
    p La ficha cuenta con el orden específico en que se van realizando las prendas: diseño, patronaje, trazo, corte, tiqueteado, confección, y terminación. De esta forma, la ficha técnica es un elemento primordial para el departamento de diseño al informar de una manera estandarizada y sencilla las características técnicas de un producto a confeccionar, es de destacar que esta información tiene utilidad a nivel comercial y productivo.

    .row.justify-content-center.align-items-stretch.mt-5.mb-5
      .col-lg-4
        .bloque-texto-d.color-acento-contenido.p-4
          .bloque-texto-d__texto.mb-2
            i.fas.fa-quote-left
            h3.text-regular Es el documento que da facilidad y precisión en la producción de una prenda de vestir.
            i.fas.fa-quote-right
          .bloque-texto-d__autor 
            .h5.mb-0 Pinilla (2006, p. 51).
          

      .col-lg-8
        .bloque-texto-d.color-acento-contenido.p-4
          .bloque-texto-d__texto.mb-2
            i.fas.fa-quote-left
            h3.text-regular Es un documento escrito (Gráfico), en la cual se registran todas las características técnicas del producto prenda, es el documento que registra todos los procesos de fabricación considerando información relevante desde que nace el requerimiento del cliente (Spec) o idea propia, siguiendo por la fase de desarrollo, producción y despacho.
            i.fas.fa-quote-right
          .bloque-texto-d__autor 
            .h5.mb-0 Huertas (2019, p. 54)
          


    p.mb-4 Los componentes de una ficha técnica en el desarrollo del formato no son fijos y se definirán de acuerdo a las necesidades puntuales de cada empresa, sin embargo, todas las fichas tienen encabezado, en este apartado se encuentra información importante como: la descripción de la prenda, código del producto, diseñador, tipo de colección, fechas, nombre de la colección, autor del diseño, descripción detallada del diseño, a quien va dirigido, material textil, colores del material textil, tallas a realizar, accesorios.
    p En resumen, la ficha técnica se compone de varios elementos, en los que se muestra cada una de las fases que se desarrollan en la producción o el prototipo inicial y son las siguientes:

    .row.justify-content-center.align-items-center.mt-5.mb-5
      .col-12.col-md-3.mb-5.mb-md-0
        img.img-t.img-a(src='@/assets/curso/Tema6/6.png', alt='')

      .col-12.col-md-7.mb-5.mb-md-0
        LineaTiempoD.color-primario
          p(numero="1" titulo="Diseño de la prenda") Aquí se encuentra el dibujo de la prenda, tanto del frente como de la parte trasera o posterior.
          
          p(numero="2" titulo="Corte") Se define las telas, insumos, avíos de la prenda.
          
          p(numero="3" titulo="Molderia") Se realizan los moldes que comprende la prenda a escala y se especifica cantidad de piezas por molde.
          
          p(numero="4" titulo="Especificaciones de confección") Orden operacional en que se encuentra el nombre de las operaciones, máquinas a utilizar, el tipo de costura, puntadas por pulgada, los aditamentos o guías que se utilizarán y tiempos estándar de la producción.

    .row 
      .col-10.m-auto
        .tarjeta.tarjeta-color-tercera.p-4.mb-5
          .row.justify-content-around.align-items-center
            .col-3.col-sm-2.col-lg-1.d-none.d-lg-block
              img(src="@/assets/curso/Tema6/7.svg")
            .col
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0
                  h3.mb-1 Anexo
                  p.text-small Se recomienda explorar más el archivo de “Formato de ficha técnica”.
                .col-sm-auto
                  a.boton.color-boton.texto-blanco(:href="obtenerLink('downloads/2_FORMATO_DE_FICHA_TECNICA_EN_EXCEL.rtf')" target="_blank")
                    span Descargar
                    i.fas.fa-file-download

    Separador

    .titulo-segundo.color-acento-botones#t_6_3
      .h4 6.3  Consumo de Materiales    

    p.mb-3 El consumo de materiales se define como los elementos que se utilizan en la producción de prendas de vestir los cuales de acuerdo con el diseño tienen unas cantidades específicas de uso. Por un lado, conocer los consumos y costos de materiales de una empresa conlleva a manejar los recursos con mayor responsabilidad, por ello, se hace indispensable identificar los consumos y los costos de materiales utilizados en el proceso, estos consumos se miden en unidad de medida, ubicación, valor matriz con código empresa, cantidad, talla, además del valor de los materiales e insumos con los cuales se desarrolla la producción.

    .row.cajon.color-secundario.p-4.mt-5.mb-5
      p.mb-0 De igual manera, en una empresa se puede realizar el consumo por prendas de insumos, materiales y los costos de la fabricación por prenda, también el consumo de material (Tela), sesgos e insumos, a través de tablas de Excel. De esta forma, se recuerda la empresa COATS CADENA que desde hace años facilita una plantilla en Excel y el software denominado SEAMWORKS para el correcto cálculo de hilo en la producción de prendas de vestir.



    .row.justify-content-center.align-items-center.mb-5
      .col-lg-12(data-aos="fade-left")
        figure
          .video
            iframe(width="560" height="315" src="https://www.youtube.com/embed/27428pA7t3I" title="Description" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
          figcaption Video. Sena 2024


    p.mb-5 Aprender a generar el consumo de sesgos tiene suma importancia para la fabricación de cualquier prenda de vestir y con el formato adecuado se minimiza el tiempo del cálculo, para ello se necesita:

    .row.justify-content-center.align-items-center.mt-5.mb-5
      .col-lg-10
        ImagenInfografica.color-acento-contenido
          template(v-slot:imagen)
            figure
              img(src='@/assets/curso/Tema6/8.svg', alt='Consumo de Materiales')
          .tarjeta.color-botones.p-3(x="12%" y="41%")
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

    p.mb-5 Por último, para llegar al consumo por unidad se necesita número de unidades por retazo y este proceso genera metros que es el valor que se necesita en el consumo de sesgos. 

       
    .row 
      .col-10.m-auto
        .tarjeta.tarjeta-color-tercera.p-4.mb-5
          .row.justify-content-around.align-items-center
            .col-3.col-sm-2.col-lg-1.d-none.d-lg-block
              img(src="@/assets/curso/Tema6/9.svg")
            .col
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0
                  h3.mb-1 Anexo
                  p.text-small Explorar el siguiente documento llamado “Formato de consumo de hilos”.
                .col-sm-auto
                  a.boton.color-boton.texto-blanco(:href="obtenerLink('downloads/3_FORMATO_DE_CONSUMO_DE_HILOS.xls')" target="_blank")
                    span Descargar
                    i.fas.fa-file-download


        .tarjeta.tarjeta-color-tercera.p-4.mb-5
          .row.justify-content-around.align-items-center
            .col-3.col-sm-2.col-lg-1.d-none.d-lg-block
              img(src="@/assets/curso/Tema6/9.svg")
            .col
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0
                  h3.mb-1 Anexo
                  p.text-small Explorar el siguiente documento llamado “Formato de consumo de sesgos”.
                .col-sm-auto
                  a.boton.color-boton.texto-blanco(:href="obtenerLink('downloads/4_FORMATOS_DE_CONSUMO_DE_SESGOS.xlsx')" target="_blank")
                    span Descargar
                    i.fas.fa-file-download




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
