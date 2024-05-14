<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    .titulo-principal.color-acento-botones
      .titulo-principal__numero
        span.numero 2
      h1.text-in Estructura del Sistema de Producción
    .row.justify-content-center.align-items-stretch.mb-4
      .bloque-texto-d.color-acento-contenido.p-4
        .bloque-texto-d__texto.mb-2
          i.fas.fa-quote-left
          h3.text-regular La estructura del sistema de producción se define como la composición de insumos interrelacionados, que se acogen del medio externo y se manipulan para transformarse en elementos con valor agregado, con el fin de alcanzar metas comunes al desarrollar una salida de modo tangible o intangible hacia el exterior.  
          i.fas.fa-quote-right
        .bloque-texto-d__autor 
          .h5.mb-0 (Everett E. Adam, 1991).

    p Este concepto puede entenderse a través de un esquema que grafica su funcionamiento dentro de la empresa por medio de un conjunto como el que se presenta a continuación:
              

    .row.justify-content-center.align-items-center.mt-5.mb-5
      .col-lg-8
        .BorTit.mt-5  #[b Figura 5.]  Estructura del Sistema de Producción.
        img.img-t.img-a.mt-4.d-none.d-lg-block(src='@/assets/curso/Tema2/1.svg', alt='Se expone la palabra sub- producto de donde se desprenden cinco términos que lo rodean:   Sub- Inversión, Sub - Información, Sub - Recursos Humanos, Sub - Dirección, Sub - Comercial') 
        img.img-t.img-a.mt-4.d-block.d-lg-none(src='@/assets/curso/Tema2/5.svg', alt='En la imagen se describe tres sectores de la economía que llevan al proceso de producción, en el primer sector denominado Primario se ubica la agricultura o industria extractiva, el siguiente es el sector Secundario que hace referencia a la industria manufacturera, para finalmente llegar al sector Terciario en donde se ubica el comercio, servicios públicos, transporte Créditos, Turismo entre otros')  
    

    .tarjeta.bg6.py-4.mb-5
      .row.ml-1-cus
        .col-lg-12
          p Analizando la gráfica de un sistema de producción podemos visualizar que lo integra un conjunto de elementos que interactúan entre sí y se retroalimentan constantemente, teniendo como núcleo de ese conjunto a la producción. Cada subconjunto suministra información al conjunto de producción y esta suministra información a los demás subconjuntos con una retroalimentación constante entre ellos.  

    img.img-t.img-a.mt-5(src='@/assets/curso/Tema2/2.png', alt='')    


    Separador


    .titulo-segundo.color-acento-botones#t_2_1
      .h4 2.1  Componentes de un sistema de producción

    

    .row.justify-content-center.align-items-stretch.mb-4
      .col-sm-12.col-lg-6
        p.mt-2 Para que un sistema de producción funcione adecuadamente, es fundamental contar con un equipo humano idóneo, dotado de las aptitudes necesarias para operar las máquinas de producción, junto con las herramientas y las tecnologías requeridas. Además, se necesitan sistemas de manejo de materiales y sistemas computacionales que permitan coordinar y controlar estos componentes.
      .col-sm-12.col-lg-5
        img.img-t.img-a.mt-2(src='@/assets/curso/Tema2/3.svg', alt='')


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
          .BorTit  #[b Figura 6.]  Clasificación.
          img.img-t.img-a.mt-4.d-none.d-lg-block(src='@/assets/curso/Tema2/4.svg', alt='Clasificación de los sistemas de producción que se convierten en factores del mismo sistema')
          img.img-t.img-a.mt-4.d-block.d-lg-none(src='@/assets/curso/Tema2/6.svg', alt='Clasificación de los sistemas de producción que se convierten en factores del mismo sistema')

    
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
