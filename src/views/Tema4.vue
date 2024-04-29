<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    .titulo-principal.color-acento-botones
      .titulo-principal__numero
        span.numero 4
      h1.text-in Tipos de sistemas de producción para procesos de Confección

    p.mb-4 Al comprender los sistemas de producción y su contexto, resulta importante identificar los tipos de sistemas, teniendo en cuenta factores como los productos y la demanda asociada a estos.  
    p Se representan de la siguiente forma: 


    .row.justify-content-center.align-items-center.mt-5
      .col-lg-10    
        img.img-t.img-a.d-none.d-lg-block(src='@/assets/curso/Tema4/1.svg', alt='')  
        img.img-t.img-a.d-block.d-lg-none(src='@/assets/curso/Tema4/11.svg', alt='')  
    
    Separador    

    .titulo-segundo.color-acento-botones#t_4_1
      .h4.text-in 4.1  Sistema de producción lineal        

    .tarjeta.tarjeta--azul-1.p-3.bg1
      SlyderA
        .row.justify-content-center.align-items-center
          .col-md-5.my-2.mb-md-0
            p Un sistema de producción se define como un proceso organizado y secuencial que abarca desde el tratamiento de la materia prima hasta la obtención del producto final, sin dejar vacíos. Este tipo de sistema se distingue por su operación continua y repetitiva, como se observa en empresas como refinerías o fábricas de electrodomésticos.
        
          .col-md-5
            figure
              img(src='@/assets/curso/Tema4/2.svg', alt='Sistema de producción lineal')

        .row.justify-content-center.align-items-center
          .col-md-5.my-2.mb-md-0
            p Este sistema se destaca por ubicar las máquinas de manera seguida en la medida que cada una cumpla una fase en la línea de producción que, al trabajar en conjunto, permiten que el producto final pase por cada una de las estaciones determinadas. (Lockyer, 1998). 
        
          .col-md-5
            figure
              img(src='@/assets/curso/Tema4/3.svg', alt='Sistema de producción lineal')

        .row.justify-content-center.align-items-center
          .col-md-5.my-2.mb-md-0
            p Entre sus características más significativas se encuentra la reducción en el manejo de materiales, la poca o mínima existencia de trabajos en curso, reducción de lapsos de tiempo para la fabricación, además de la simplificación de tareas, al establecer sistemas de planificación y control concretos. 
        
          .col-md-5
            figure
              img(src='@/assets/curso/Tema4/4.svg', alt='Sistema de producción lineal')

        .row.justify-content-center.align-items-center
          .col-md-5.my-2.mb-md-0
            p Por otro lado, en este sistema se encuentran algunos inconvenientes como la rigidez en los procesos, implicando una alta inversión, por lo que la conexión de todas las partes generan el conjunto general, igualmente se presenta mínima flexibilidad en los periodos de fabricación y el trabajo puede resultar monótono ya que todo está organizado. 
        
          .col-md-5
            figure
              img(src='@/assets/curso/Tema4/6.svg', alt='Sistema de producción lineal')

        .row.justify-content-center.align-items-center
          .col-12
            figure
              img(src='@/assets/curso/Tema4/12.png', alt='Sistema de producción lineal') 


    Separador    

    .titulo-segundo.color-acento-botones#t_4_2
      .h4 4.2  Sistemas de producción por celdas

    .row.justify-content-center.align-items-stretch.mt-5
      .col-12.bloque-texto-c.color-acento-contenido.p-4
          i.fas.fa-quote-right
          h5.mb-2 Dentro de los sistemas de producción por celdas, el trabajo en equipo es fundamental, donde se integran tanto máquinas como talento humano para llevar a cabo una serie de operaciones. Esta distribución facilita el desarrollo de las relaciones profesionales, poniendo a prueba la experticia de los operadores, lo que se traduce en una polivalencia. Este tipo de sistema reduce los periodos de trabajo en la fabricación y preparación, lo que optimiza la supervisión y facilita el control visual.
          span Sekine, 1993
      
    p.mt-5 Para una distribución eficiente en la creación de celdas, es crucial considerar la selección de las familias de productos, la definición de las celdas y el establecimiento de su secuencia. Sin embargo, es importante tener en cuenta que esta organización puede incrementar el tiempo de inactividad de las máquinas, ya que estas se concentran en las tareas de la celda y es probable que no se utilicen de forma continua e ininterrumpida. 

    .row.justify-content-center.align-items-center.mt-5
      .col-lg-8
        .BorTit  #[b Figura 9.]  Sistema de producción por celda.
        img.img-t.img-a.mt-4(src='@/assets/curso/Tema4/8.svg', alt='El sistema de producción por celdas, el cual se subdivide  en  5 operaciones cada una con un recuadro que simulan las celdas cada una con un color de referencia y al frente se detallan cuatro fases  enumeradas así: Punto 1, punto 2, punto 3 y punto 4, las cuatro fases cuentan con las celdas de colores indicando que tienen las 5 Operaciones.')  


    Separador    



    .titulo-segundo.color-acento-botones#t_4_3
      .h4 4.3  Sistemas de producción modular


    .row.justify-content-center.align-items-center.mt-5
      .col-lg-5
        img.img-t.img-a.my-2(src='@/assets/curso/Tema4/9.png', alt='') 
      .col-lg-7
        p.mb-4 Según Huamán Oscco (2003), un módulo puede definirse como un grupo específico de trabajadores asignados a una tarea particular. Esta estructura organizativa permite una mayor fluidez y sincronización en la producción, asegurando que los productos se generen siguiendo el orden establecido de las operaciones.  
        p Por otro lado, Bonilla Pastor (2007) describe la producción modular como aquella en la que el personal asume diversas funciones dentro de un módulo de procesamiento, integrado por equipos de trabajadores que realizan diversas actividades necesarias para obtener el producto final. Esta metodología favorece un movimiento continuo y flexible, permitiendo la combinación de modelos dentro de una misma familia de productos. Así, la producción modular minimiza la acumulación de inventario en proceso y fomenta el movimiento del talento humano a lo largo de las distintas etapas del proceso, lo que indica que la producción no sigue un enfoque de producción en serie.

    .h4.mt-5.titulo-caracteristicas Características

    p Según Bonilla Pastor (2007), el sistema de producción modular incorpora varios criterios para su implementación. Estos incluyen la necesidad de una máquina para operaciones específicas y la definición del producto final después de pasar por toda la secuencia de producción. De esta manera, cada trabajador utiliza la máquina en un momento determinado sin interrupciones hasta finalizar la prenda. Además, el talento humano contribuye a una eficiencia total del 100%, y las piezas que inician el proceso están cortadas cerca del lugar designado para iniciar.

    .tarjeta.row.mb-5
    .col-md.tarjeta.bg3.p-5
      .row
        .col-10

      .row.justify-content-center.align-items-center.mt-5(data-aos="left")
        .col-lg-10
          .BorTit  #[b Figura 10.]  Sistema de producción modular.
          img.img-t.img-a.mt-4(src='@/assets/curso/Tema4/10.svg', alt='Se describe el sistema de producción modular, en donde siete personas están sentadas en una mesa ovalada uno en la cabecera, tres personas al lado derecho y tres personas al lado izquierdo, estas ultimas personas de este lado izquierdo tiene la numeración de izquierda a derecha del 1 al 3, quien esta en la cabecera tiene el numero 4,  los tres de la derecha de la mesa tienen en su orden los números 5, 6 y 7 de derecha a izquierda.  La imagen cuenta con una flecha  que inicia detrás de la persona  1, va de izquierda a derecha, por detrás de las personas 1, 2,  3 y 4   y continua girando, detrás de los números 5, 6 y 7 bordeando la  mesa, hasta terminar en el número 7.  En medio de cada uno de ellos existe un espacio y en la mesa encima cuentan con una llave inglesa')  
</template>

<script>
export default {
  name: 'Tema4',
  data: () => ({
    // variables de vue
  }),
}
</script>

<style lang="sass" scoped></style>
