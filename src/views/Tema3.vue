<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido(data-aos="flip-up")
      .titulo-principal__numero
        span 3
      h1 Cámaras de combustión en la culata
    .row.bg-c13
      .col-12
        .px-5
          .row.align-items-center.mb-4
            .col-lg-7(data-aos="fade-right")
              p En los motores de dos ciclos, a gasolina, la combustión que se produce dentro de la cámara de combustión, es la encargada de empujar con gran fuerza al pistón hacia el PMI.
              .row.mb-4.mb-lg-0
                .col-md-4.bg-c9
                  .row.h-100.align-items-center
                    .col-12
                      .p-3
                        figure
                          img(src='@/assets/curso/tema3/img1.svg', alt='', style="width: 100px").m-auto
                .col-md-8.bg-c14
                  .row
                    .col-12
                      .p-3
                        p.mb-0 Así pues, para que la mezcla ingrese hasta la cámara de combustión, la válvula de admisión se abre y la mezcla aire y combustible ingresa por el dueto o tobera de admisión, se cierra la válvula, se comprime la mezcla dentro de la cámara y una chispa eléctrica salta entre los electrodos de una bujía, para dar inicio a la combustión.
            .col-lg-5(data-aos="fade-left")
              figure
                img(src='@/assets/curso/tema3/img2.png', alt='', style="width: 460px").m-auto
          p.mb-4(data-aos="fade-right") La expansión de los gases de la combustión empuja con gran fuerza al pistón hacia el PM1 y cuando el pistón inicia su ascenso, la válvula de escape se abre para que salgan los gases combustionados hacia la atmósfera, por medio del dueto o tobera de escape.
          .row.justify-content-center.mb-4
            .col-lg-4(data-aos="fade-right")
              .titulo-sexto.color-acento-contenido.mb-3
                p.mb-0 #[b Figura 3]. Cámara de combustión
              figure
                img(src='@/assets/curso/tema3/img3.png', alt='La imagen muestra un esquema del proceso de admisión en un motor de combustión interna, destacando el flujo de aire y combustible hacia la cámara de combustión.', style="width: 400px").m-auto
            .col-lg-5.d-none.d-lg-block(data-aos="fade-left")
              figure
                img(src='@/assets/curso/tema3/img4.png', alt='', style="width: 400px").m-auto
    p(data-aos="fade-down") A continuación, conozcamos los diferentes tipos de cámaras:
    .row.bg-c15
      .col-12
        .p-5
          .tarjeta.tarjeta--azul1.p-4.p-md-5(data-aos="fade-right")
            SlyderA(tipo="b")
              .row.justify-content-center.align-items-center
                .col-lg-6.mb-4.mb-lg-0
                  p #[b Cámara de combustión de dos válvulas por cilindro]
                  p La cámara de combustión en los motores a gasolina está formada por una cavidad en la culata, además de alojar a las válvulas de admisión y escape. Esta permite que los electrodos de la bujía estén en contacto con los gases comprimidos y la tobera del inyector se proyecte dentro de la cámara en los motores de inyección directa.
                  p.mb-0 La forma de dicha cámara puede ser diseñada por cada fabricante, pero fundamentalmente debe responder a la relación de compresión que requiere este tipo de motor respecto al diseño de la cabeza del pistón; para que el flujo del ingreso de la mezcla hasta el cilindro se produzca sin restricciones y el combustible inyectado en el aire aspirado se vaya mezclando homogéneamente, y así al final del trabajo del motor, los gases combustionados salgan con gran facilidad hacia la atmósfera.
                .col-lg-4
                  figure
                    img(src='@/assets/curso/tema3/img6.png', alt='', style="width: 400px").m-auto
              .row.justify-content-center.align-items-center
                .col-lg-6.mb-4.mb-lg-0
                  p #[b Cámara de combustión de tres válvulas por cilindro]
                  p Fácilmente se puede suponer que una sola válvula de admisión solamente podrá permitir el ingreso de una cierta cantidad limitada de mezcla y por esta razón cada fabricante ha buscado la forma de mejorar esta respiración del motor, diseñando las culatas del motor con más de dos válvulas por cilindro.
                  p.mb-0 Sin embargo, una culata puede ser diseñada para que disponga de tres válvulas, dos de ellas de admisión con diámetros menores y una válvula de escape de mayor dimensión. Con este aumento de válvulas de admisión se logra el mayor llenado del cilindro y con ello mayores potencias del motor.
                .col-lg-4
                  figure
                    img(src='@/assets/curso/tema3/img7.png', alt='', style="width: 400px").m-auto
              .row.justify-content-center.align-items-center
                .col-lg-6.mb-4.mb-lg-0
                  p #[b Cámaras combustión cuatro válvulas por cilindro]
                  p Al aumentar el número de válvulas por cada cilindro del motor estaremos permitiendo un mayor ingreso y salida de los gases hasta el cilindro; con ello una mayor potencia del motor.
                  p Si se tiene un motor con cuatro válvulas por cilindro, dos de ellas de admisión, estaremos aumentando el volumen de la mezcla que puede ingresar; pero, para poder dar mayor dimensión a las válvulas, se les instala inclinadas o en forma de tejado.
                  p.mb-0 También se han instalado dentro de esta cámara a dos válvulas de escape, que a pesar de tener menor diámetro que las válvulas de admisión.
                .col-lg-4
                  figure
                    img(src='@/assets/curso/tema3/img8.png', alt='', style="width: 400px").m-auto

</template>

<script>
export default {
  name: 'Tema3',
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
