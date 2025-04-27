<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido(data-aos="flip-up")
      .titulo-principal__numero
        span 5
      h1 Sistema de distribución válvulas
    .row.bg-c19
      .col-12
        .px-5.pb-5
          .row.mb-4(data-aos="fade-down")
            .col-lg-auto.pe-0.d-none.d-xl-block
              figure
                img(src='@/assets/curso/tema5/img1.png', alt='', style="width: 470px").m-auto
            .col-lg.bg-c14
              .row.h-100.align-items-center
                .col-12
                  .p-3
                    p.mb-0 La distribución de un motor de combustión interna tiene por objeto comandar a las válvulas de admisión y de escape; estas permiten el ingreso de la mezcla aire y combustible al cilindro y a la cámara de combustión, permitiendo luego la salida de los gases combustionados. Este comando de las válvulas lo realiza un eje de levas (árbol de levas), eje que como su nombre lo indica, dispone de tantas levas como número de válvulas que debe obligar a abrir y cerrar. Cada leva se encarga de empujar a la válvula a través de mecanismos, como balancines, propulsores, varillas de empuje, o sencillamente de forma directa sobre un propulsor mecánico o hidráulico.
          .row.align-items-start.mb-4(data-aos="fade-right")
            .col-auto
              figure
                img(src='@/assets/curso/tema5/img1.svg', alt='', style="width: 70px").m-auto
            .col
              p.mb-0 El ángulo que la leva mantiene empujada a la válvula depende de su diseño particular, el mismo que ha sido cuidadosamente estudiado por el constructor, para conseguir con ello la mejor potencia del motor. Este ángulo está relacionado con la posición del pistón, para que, de forma sincronizada se abran o cierren las válvulas, produciéndose las etapas de admisión de los gases y la salida.
          .row.justify-content-center(data-aos="fade-left")
            .col-lg-3.mb-4.mb-lg-0.d-none.d-lg-block
              figure
                img(src='@/assets/curso/tema5/img4.png', alt='', style="width: 300px").m-auto
            .col-lg-5
              .titulo-sexto.color-acento-contenido.mb-3
                p.mb-0 #[b Figura 5.] Etapas de admisión de los gases y la salida
              figure
                img(src='@/assets/curso/tema5/img3.png', alt='La imagen muestra un esquema del funcionamiento del sistema de admisión y escape en un motor de combustión interna, resaltando los componentes clave involucrados en la mezcla de combustible y la expulsión de gases quemados.', style="width: 480px").m-auto
              figcaption.mt-2 #[b Nota.] Etapas de admisión de los gases y la salida (s.f.). [Imagen].

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
