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
      .col-8.bloque-texto-c.color-acento-contenido.p-4
          i.fas.fa-quote-right
          h5.mb-2 Los modelos se estructuran según la realidad y la abstracción, y estos factores permiten desde un problema presentado en la realidad, permite que la abstracción simule por medio de una formulación la proyección de modelos que serán verificados en la realidad. 
          span NAHMIAS, 1999
          i.fas.fa-quote-right.quite-pa

    .row.justify-content-center.align-items-center.mt-5
      .col-lg-8
        .BorTit.mt-5 Figura 5. Modelos de sistemas de producción.
        img.img-t.img-a.mt-4(src='@/assets/ilustraciones/img8.svg', alt='')            

    .h4.my-5 Tipos de Modelos
    p Un modelo tiene como función principal la representación o explicación de una realidad, lo que permite entenderse como una réplica de los factores que caracterizan un proceso. En un modelo se evidencia la relación entre la causa y el efecto, además de las metas a alcanzar y las posibles restricciones. 

    .row.justify-content-center.align-items-center
      .col-10
        .bloque-texto-b.color-primario.p-4
          .bloque-texto-b__texto
            i.fas.fa-quote-left
            h4.mb-4 A través del uso de modelos es como se identifican posibles soluciones, teniendo en cuenta la magnitud o dificultad de un determinado problema, por consiguiente, al definir en qué radica el dicho problema es cómo se reconocen los tipos de modelos que se ajustan mejor a la situación planteada
            span NAHMIAS, 1999
            i.fas.fa-quote-right.quite-pa

    .row.justify-content-center.align-items-center.mt-5
      .col-lg-10
        p.text-center De esta forma, se evidencian tres tipos:
        img.img-t.img-a.mt-4(src='@/assets/ilustraciones/img9.svg', alt='')            

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
