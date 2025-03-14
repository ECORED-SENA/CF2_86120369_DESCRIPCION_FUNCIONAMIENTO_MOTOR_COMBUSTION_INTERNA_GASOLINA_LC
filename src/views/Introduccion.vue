<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido.mb-0(data-aos="flip-up")
      .titulo-principal__numero
        span
          i.fas.fa-info
      h1 Introducción
    .row.bg-c1
      .col-12
        .p-5
          .row.mb-4
            .col-lg-4.mb-4.mb-lg-0(data-aos="fade-right")
              .row.bg-c2.h-100.align-items-center
                .col-12
                  .p-4
                    p.mb-0 Un árbol de levas es un mecanismo formado por un eje en el que se ubican distintas levas, que a su vez pueden tener diferentes formas, tamaños y estar orientadas de diferente manera, para activar mecanismos a intervalos repetitivos, como ocurre con las válvulas. Dicho de otro modo, un árbol de levas se constituye en un temporizador mecánico cíclico.
            .col-lg-8(data-aos="fade-left")
              figure
                img(src='@/assets/curso/intro/img2.png', alt='', style="width: 790px").m-auto
          .row.align-items-center
            .col-lg-6.order-2.order-lg-1(data-aos="fade-right")
              figure
                img(src='@/assets/curso/intro/img3.png', alt='', style="width: 790px").m-auto
            .col-lg-6.mb-4.mb-lg-0.order-1.order-lg-2(data-aos="fade-left")
              figure.d-none.d-lg-block
                img(src='@/assets/curso/intro/img4.png', alt='', style="width: 120px")
              p Su aplicación más desarrollada tiene que ver con el motor de combustión interna. Donde regula la carrera de apertura, el cierre de las válvulas, como la duración de esta fase de apertura; lo que permite la renovación de la carga en las fases de admisión y escape de gases en los cilindros.
              p.mb-0 #[b ¡Muchos éxitos en esta experiencia de aprendizaje!]

</template>

<script>
export default {
  name: 'Introduccion',
  data: () => ({
    // variables de vue
  }),
}
</script>

<style lang="sass"></style>
