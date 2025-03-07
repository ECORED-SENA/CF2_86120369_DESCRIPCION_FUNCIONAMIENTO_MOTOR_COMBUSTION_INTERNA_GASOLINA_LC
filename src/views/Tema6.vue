<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido(data-aos="flip-up")
      .titulo-principal__numero
        span 6
      h1 Trabajo eje levas en el motor
    .row.bg-c20
      .col-12
        .p-5
          .row
            .col-12
              .row.align-items-center
                .col-lg-6.mb-4.mb-lg-0(data-aos="fade-right")
                  p.mb-0 Como un ciclo completo de trabajo de un motor de cuatro tiempos, corresponde a dos vueltas completas del eje cigüeñal, y el eje de levas necesita solamente una vuelta para cumplir su función de apertura y cierre de todas las válvulas, el cigüeñal está sincronizado con el eje de levas en relación de 2:1, lo que significa que el cigüeñal necesitará girar dos vueltas y el eje de levas girará solamente una, para que se cumplan los cuatro ciclos del motor. Para ello, todo motor dispone de un sistema de transmisión del movimiento del cigueñal hasta el eje de levas y esta transmisión puede darse por medio de piñones en toma constante, por medio de cadenas, bandas o cualquier otro sistema apropiado, pero lo más importante de esta transmisión es mantener la relación indicada.
                .col-lg-6(data-aos="fade-left")
                  .titulo-sexto.color-acento-contenido.mb-3
                    p.mb-0 #[b Figura 6.] Árbol de levas
                  figure
                    img(src='@/assets/curso/tema6/img1.png', alt='La imagen muestra un árbol de levas, un componente fundamental en los motores de combustión interna.', style="width: 520px").m-auto
    Separador
    .row.bg-c19
      .col-12
        .px-5.pb-5
          #t_6_1
          .titulo-segundo.color-acento-contenido
            h2 6.1 Eje de levas sencillo o doble eje de levas
          .row.mb-4
            .col-xl(data-aos="fade-right")
              p El eje de levas de un motor de cuatro ciclos dispone de tantas levas como válvulas del motor debe impulsar.
              .row.mb-3
                .col-lg-auto.pe-lg-0.d-none.d-lg-block
                  figure
                    img(src='@/assets/curso/tema6/img2.png', alt='', style="width: 350px").m-auto
                .col-lg.bg-c21
                  .p-3
                    figure
                      img(src='@/assets/curso/tema6/img3.png', alt='', style="width: 100px")
                    p.mb-0 El eje de levas sencillo, independiente de que el eje esté instalado en el mismo bloque de cilindros o en la parte superior de la culata, dispone tanto de las levas de admisión como las levas de escape en el mismo eje y estas se encargarán de impulsar a las válvulas por medio de propulsores, varillas, o balancines a cada una de las válvulas del motor, de acuerdo al sistema utilizado.
              p.mb-0 Cuando se utilizan dos ejes de levas en un motor, tendremos un eje de levas que impulsará a las válvulas de admisión únicamente y otro eje de levas que impulsará a las válvulas de escape.
            .col-xl-auto.d-none.d-xl-block(data-aos="fade-left")
              figure
                img(src='@/assets/curso/tema6/img4.png', alt='', style="width: 250px").m-auto
          .row(data-aos="fade-down")
            .col-md-auto.bg-c9
              .p-3
                figure
                  img(src='@/assets/curso/tema6/img1.svg', alt='', style="width: 100px").m-auto
            .col-md.bg-c14
              .row.h-100.align-items-center
                .col-12
                  .p-3
                    p.mb-0 El eje sencillo estará girando de forma sincronizada con el motor y requerirá una sola señal de sincronización. Cuando existen dos ejes de levas, deberán de igual forma estar sincronizados, pero existirá una señal en cada uno de ellos para su sincronización.

</template>

<script>
export default {
  name: 'Tema5',
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
