<template lang="pug">
.curso-main-container.pb-3
  BannerInterno(icono="fas fa-sitemap" titulo="Síntesis")
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    p.mb-5 Los sistemas de producción integran elementos para transformar las materias primas en productos terminados, a partir de la interrelación de sus componentes talento humano, herramientas y tecnologías, teniendo en cuenta el sector primario (Industria extractiva), el sector secundario (Manufacturero) y el sector terciario (Los servicios). Estos sistemas de producción pueden ser clasificados a partir del tipo de operación, cantidad de estaciones de trabajo y su distribución, grado de automatización y variedad de los productos. Las organizaciones de producción de prendas de vestir deben determinar los materiales de consumo y los costos de operación para lograr calidad en el manejo de recursos teniendo en cuenta los sistemas de gestión de calidad. A continuación, se presenta un mapa conceptual que resume de manera visual estos aspectos:


</template>

<script>
export default {
  name: 'Sintesis',
  data: () => ({
    // variables de vue
  }),
  mounted() {
    this.$nextTick(() => {
      this.$aosRefresh()
    })
  },
  updated() {
    this.$aosRefresh()
  },
}
</script>

<style lang="sass"></style>
