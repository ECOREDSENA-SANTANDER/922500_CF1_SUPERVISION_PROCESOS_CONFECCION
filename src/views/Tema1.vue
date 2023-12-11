<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    .titulo-principal.color-acento-botones
      .titulo-principal__numero
        span 1
      h1.text-in Sistemas de Producción  
    .row.justify-content-center.align-items-center.mt-5(data-aos="fade-left")
      .col-12.col-md-8
        p Para hablar de sistemas de producción es importante analizar los factores que integran todos los elementos para transformar la materia prima en productos terminados. Entre los factores que intervienen, se destaca el talento humano con los conocimientos adquiridos, el estilo de administración o gestión de los procesos, los procedimientos, el uso de herramientas como máquinas y materiales, además de las tecnologías.
        .row.cajon.color-secundario.p-4.mt-5
          p.mb-0 En el desarrollo de este componente formativo se realizará una contextualización de los términos y conceptos de los sistemas de producción y su importancia para el desempeño del supervisor de procesos de confección de prendas de vestir.
  
      .col-12.col-md-4.my-2(data-aos="fade-left")
        img.img-t.img-a(src='@/assets/ilustraciones/img1.png', alt='')   

    .titulo-segundo.color-acento-botones#t_1_1.mt-5
      .h4.text-in 1.1  Producción: Concepto y terminología 
    
    p Para entender el significado de sistemas de producción primero se revisará el concepto de #[b “producción”]. 
    .row.justify-content-center.align-items-stretch
      .col-lg-4.bloque-texto-c.color-acento-contenido.p-4.mt-5
          i.fas.fa-quote-right
          h5.mb-2 La producción se define como un componente importante de la empresa al desarrollar o fabricar un bien intangible. 
          span - Tawfik (1987).
          i.fas.fa-quote-right.quite-pa

      .col-lg-4.bloque-texto-c.color-acento-contenido.p-4.mt-5
          i.fas.fa-quote-right
          h5.mb-2 La define como un hecho realizado con la intención de transformar diversos elementos para generar un bien tangible e intangible que satisfaga una necesidad humana. 
          span Everett E. (1991).
          i.fas.fa-quote-right.quite-pa

    .row.justify-content-center.align-items-center.mt-5
      .col-lg-8
        .BorTit Figura 1. Producción.
        img.img-t.img-a.mt-4(src='@/assets/ilustraciones/img2.svg', alt='' data-aos="slide-left")  
    .h4.my-5 Función de la producción
    .row.justify-content-center.align-items-stretch.mt-5
      .col-lg-7.bg-color-1.p-4
        p La función de la producción consta de tres sectores que se interrelacionan entre sí y son complemento el uno del otro. El sector primario conocido como la industria extractiva está integrado por el agro, la minería, entre otros, los cuales son insumos para el segundo sector, es decir, el manufacturero que se define como el que transforma los productos de la extractiva en productos de consumo para las necesidades de los clientes y a su vez, son el insumo de la terciaria que se enfoca a los servicios. (Tawfik, 1987).
      .col-5.d-none.d-lg-block.px-0.text-in
        img.p-0.mx-0.img-t.img-a(src='@/assets/ilustraciones/img3.svg', alt='') 
      
    .row.justify-content-center.align-items-center.mt-5
      .col-lg-8
        p.text-center Es de destacar que la importancia de la función de la producción en los procesos productivos es vital para el desarrollo de productos y servicios requeridos por el mercado.
        .BorTit.mt-5 Figura 2. Esquema de producción.
        img.img-t.img-a.mt-4(src='@/assets/ilustraciones/img4.svg', alt='')  
    .h4.my-5 Objetivo de la producción
    p De acuerdo con Nahmias (1999), las actividades llevadas a cabo en la producción con relación a las operaciones en una empresa significan el aprovechamiento al máximo del valor creado. Es decir, el valor de los inputs y la diferencia de valor de los outputs representa el valor desarrollado por medio de las actividades de producción. 
    p Por lo tanto, esta interacción se establece de manera continua desde los insumos, el proceso de conversión y los productos generados que pueden estar representados en bienes o servicios, lo que a su vez continúa en una constante retroalimentación.

    .row.justify-content-center.align-items-center.mt-5(data-aos="left")
      .col-lg-8
        .BorTit Figura 3. Objetivo de la producción. 
        img.img-t.img-a.mt-4(src='@/assets/ilustraciones/img5.svg', alt='')  
        
</template>

<script>
export default {
  name: 'Tema1',
  components: {},
  data: () => ({}),
}
</script>

<style lang="sass" scoped></style>
