<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    .titulo-principal.color-acento-botones
      .titulo-principal__numero
        span.numero 2
      h1.text-in Estructura del Sistema de Producción
    .row.justify-content-center.align-items-stretch
      .col-12.bloque-texto-c.color-acento-contenido.p-4
          i.fas.fa-quote-right
          h5.mb-2 La estructura del sistema de producción se define como la composición de insumos interrelacionados, que se acogen del medio externo y se manipulan para transformarse en elementos con valor agregado, con el fin de alcanzar metas comunes al desarrollar una salida de modo tangible o intangible hacia el exterior.  
          span Everett E. (1991).
          i.fas.fa-quote-right.quite-pa

    .row.justify-content-center.align-items-center.mt-5
      .col-lg-8
        p Este concepto puede entenderse a través de un esquema que grafica su funcionamiento dentro de la empresa por medio de un conjunto como el que se presenta a continuación:
        .BorTit.mt-5 Figura 4. Estructura del Sistema de Producción.
        img.img-t.img-a.mt-4(src='@/assets/ilustraciones/img6.svg', alt='')    
        p.mt-5 Analizando la gráfica de un sistema de producción podemos visualizar que lo integra un conjunto de elementos que interactúan entre sí y se retroalimentan constantemente, teniendo como núcleo de ese conjunto a la producción. Cada subconjunto suministra información al conjunto de producción y esta suministra información a los demás subconjuntos con una retroalimentación constante entre ellos.  

    img.img-t.img-a.mt-5(src='@/assets/ilustraciones/img7.png', alt='')    

    .row.justify-content-center.align-items-stretch
      .col-lg-6.mt-5
        .titulo-segundo.color-acento-botones#t_2_1
          .h4 2.1  Componentes de un sistema de producción
        p Para que un sistema de producción se maneje adecuadamente, es necesario que adopte un talento humano idóneo, con aptitudes propias de lo que se requiere para el manejo de máquinas de producción, con las herramientas necesarias y la tecnología dispuesta. Igualmente, se requieren sistemas de manejo de materiales, además de sistemas computacionales que permitan la coordinación y control de dichos componentes. 
      .col-lg-6.borde-left.mt-5
        .titulo-segundo.color-acento-botones#t_2_2
          .h4 2.2  Clasificación de los sistemas de producción
        p Los sistemas de producción presentan diversas características que permiten clasificarlos, para ello se especifican cuatro factores evidentes en un sistema de producción. El primero se enfoca al tipo de operación que se realiza en el proceso, el segundo factor se basa en la cantidad de estaciones de trabajo y su distribución, el tercero apunta al grado de automatización y el cuarto especifica la variedad de los productos. 

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
