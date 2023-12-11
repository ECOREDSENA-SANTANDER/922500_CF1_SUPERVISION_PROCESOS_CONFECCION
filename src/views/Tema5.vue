<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    .titulo-principal.color-acento-botones
      .titulo-principal__numero
        span.numero 5
      h1.text-in Máquinas de producción

    .row.justify-content-center.align-items-center
      .col-lg-10
        img.img-t.img-a(src='@/assets/ilustraciones/img19.png', alt='')
        p.mt-5 Las máquinas de producción son los aparatos que permiten procesar y ensamblar materiales transformados mediante el sistema de producción, lo que podría decirse que son un elemento fundamental para llevar a cabo los procesos. Estas se clasifican en las siguientes:   
        img.img-t.img-a.mt-5(src='@/assets/ilustraciones/img20.svg', alt='')

</template>

<script>
export default {
  name: 'Tema5',
  data: () => ({
    // variables de vue
  }),
}
</script>

<style lang="sass" scoped></style>
