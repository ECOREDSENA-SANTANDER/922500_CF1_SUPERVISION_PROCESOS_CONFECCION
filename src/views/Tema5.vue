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
        img.img-t.img-a(src='@/assets/curso/Tema5/1.png', alt='')
        p.mt-5.mb-4 Las máquinas de producción son fundamentales para llevar a cabo los procesos, ya que procesan y ensamblan materiales transformados. Se clasifican de la siguiente manera.
        p Así mismo la imagen no cuenta con numeración como figura, por ello se recomienda omitir, teniendo en cuenta los cuadros que se anexan por parte del experto.
        img.img-t.img-a.mt-5(src='@/assets/curso/Tema5/2.svg', alt='')

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
