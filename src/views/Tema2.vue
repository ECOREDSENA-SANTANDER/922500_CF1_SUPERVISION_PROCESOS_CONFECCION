<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    .titulo-principal.color-acento-botones
      .titulo-principal__numero
        span.numero 2
      h1.text-in Estructura del Sistema de Producción
    .row.justify-content-center.align-items-stretch.mb-4
      .col-12.bloque-texto-c.color-acento-contenido.p-4
          i.fas.fa-quote-right
          h5.mb-2 La estructura del sistema de producción se define como la composición de insumos interrelacionados, que se acogen del medio externo y se manipulan para transformarse en elementos con valor agregado, con el fin de alcanzar metas comunes al desarrollar una salida de modo tangible o intangible hacia el exterior.  
          span Everett E. (1991).
          i.fas.fa-quote-right.quite-pa

    p Este concepto puede entenderse a través de un esquema que grafica su funcionamiento dentro de la empresa por medio de un conjunto como el que se presenta a continuación:
              

    .row.justify-content-center.align-items-center.mt-5.mb-5
      .col-lg-8
        .BorTit.mt-5 Figura 5. Estructura del Sistema de Producción.
        img.img-t.img-a.mt-4(src='@/assets/curso/Tema2/1.svg', alt='') 


    .tarjeta.bg6.py-4.mb-5
      .row.ml-1-cus
        .col-lg-12
          p Analizando la gráfica de un sistema de producción podemos visualizar que lo integra un conjunto de elementos que interactúan entre sí y se retroalimentan constantemente, teniendo como núcleo de ese conjunto a la producción. Cada subconjunto suministra información al conjunto de producción y esta suministra información a los demás subconjuntos con una retroalimentación constante entre ellos.  

    img.img-t.img-a.mt-5(src='@/assets/curso/Tema2/2.png', alt='')    


    Separador


    .titulo-segundo.color-acento-botones#t_2_1
      .h4 2.1  Componentes de un sistema de producción

    

    .row.justify-content-center.align-items-stretch.mb-4
      .col-6.p-8
        p.mt-5 Para que un sistema de producción funcione adecuadamente, es fundamental contar con un equipo humano idóneo, dotado de las aptitudes necesarias para operar las máquinas de producción, junto con las herramientas y la tecnología requeridas. Además, se necesitan sistemas de manejo de materiales y sistemas computacionales que permitan coordinar y controlar estos componentes.
      .col-5.p-8
        img.img-t.img-a.mt-5(src='@/assets/curso/Tema2/3.svg', alt='')


    Separador


    .titulo-segundo.color-acento-botones#t_2_1
      .h4 2.2  Clasificación de los sistemas de producción

    p Los sistemas de producción presentan diversas características que permiten clasificarlos, para ello se especifican cuatro factores evidentes en un sistema de producción.

    .tarjeta.row.mb-5
    .col-md.tarjeta.bg4.p-5
      .row
        .col-10

      .row.justify-content-center.align-items-center(data-aos="left")
        .col-lg-8
          .BorTit Figura 6. Estructura del Sistema de Producción.
          img.img-t.img-a.mt-4(src='@/assets/curso/Tema2/4.svg', alt='')

    
</template>

<script>
export default {
  name: 'Tema2',
  data: () => ({
    // variables de vue
  }),
}
</script>

<style lang="sass" scoped></style>
