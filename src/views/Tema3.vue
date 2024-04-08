<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    .titulo-principal.color-acento-botones
      .titulo-principal__numero
        span.numero 3
      h1.text-in Modelos de Sistemas de Producción 

    p Antiguamente se desarrollaron actividades rudimentarias en materia de procesos de producción, pero a medida que el tiempo fue avanzando, los investigadores encontraron mejores formas de organizar los sistemas a medida que se tornaron más complicados. Para ello, se hizo uso de los pasos realizados por las ciencias físicas, al encontrar mayor organización y precisión. De esta manera, se ha evidenciado un gran avance desde la administración científica, hasta la que hoy se conoce como ciencia de la administración, caracterizada por una mayor planeación en la construcción, manejo e interpretación de modelos. (NAHMIAS, 1999).



    .row.justify-content-center.align-items-stretch.mt-5
      .col-sm-12.col-lg-8.bloque-texto-c.color-acento-contenido.p-4
          i.fas.fa-quote-right
          h5.mb-2 Los modelos se estructuran según la realidad y la abstracción, y estos factores permiten desde un problema presentado en la realidad, permite que la abstracción simule por medio de una formulación la proyección de modelos que serán verificados en la realidad. 
          span NAHMIAS, 1999
         

    .tarjeta.row.mb-5
    .col-md.tarjeta.bg5.p-5
      .row
        .col-10

      .row.justify-content-center.align-items-center(data-aos="left")
        .col-lg-8
          .BorTit  #[b Figura 7.]  Modelos de sistemas de producción.
          img.img-t.img-a.mt-4.d-none.d-lg-block(src='@/assets/curso/Tema3/1.svg', alt='Se exponen dos modelos denominados Realidad y Abstracción, en el primero se incluyen Problemas Datos Modelos, de los cuales se subdividen 4 términos que se ubican en el lado derecho de Abstracción y son Formulación, Manipulación, Evaluación, Pronostico, Finalmente termina en el modelo realidad con Verificación.')   
          img.img-t.img-a.mt-4.d-block.d-lg-none(src='@/assets/curso/Tema3/3.svg', alt='Se exponen dos modelos denominados Realidad y Abstracción, en el primero se incluyen Problemas Datos Modelos, de los cuales se subdividen 4 términos que se ubican en el lado derecho de Abstracción y son Formulación, Manipulación, Evaluación, Pronostico, Finalmente termina en el modelo realidad con Verificación.')   
          

    Separador


    .titulo-segundo.color-acento-botones#t_3_1
      .h4 3.1  Tipos de Modelos

    p La función principal de un modelo es representar o explicar una realidad, sirviendo como una réplica de los factores que caracterizan un proceso, por ello en un modelo se destacan las relaciones entre causa y efecto, así como las metas a alcanzar y las posibles restricciones.

    .row.justify-content-center.align-items-center
      .col-sm-12.col-lg-10
          .bloque-texto-b.color-primario.p-4
            .bloque-texto-b__texto
              i.fas.fa-quote-left
              h4.mb-4 <br> A través del uso de modelos es como se identifican posibles soluciones, teniendo en cuenta la magnitud o dificultad de un determinado problema, por consiguiente, al definir en qué radica el dicho problema es cómo se reconocen los tipos de modelos que se ajustan mejor a la situación planteada.
              <br>
              span NAHMIAS, 1999
              i.fas.fa-quote-right

           

    .row.justify-content-center.align-items-center.mt-5
      .col-lg-10
        p De esta forma, se evidencian tres tipos:
        img.img-t.img-a.mt-4.d-none.d-lg-block(src='@/assets/curso/Tema3/2.svg', alt='')            
        img.img-t.img-a.mt-4.d-block.d-lg-none(src='@/assets/curso/Tema3/4.svg', alt='')            

</template>

<script>
export default {
  name: 'Tema3',
  data: () => ({
    // variables de vue
  }),
}
</script>

<style lang="sass" scoped></style>
