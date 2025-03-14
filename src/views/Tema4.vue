<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido(data-aos="flip-up")
      .titulo-principal__numero
        span 4
      h1 Empaque de la culata
    .row.bg-c13.mb-4
      .col-12
        .px-5
          .row.align-items-center.mb-4
            .col-lg-7.bg-c12.mb-4.mb-lg-0(data-aos="fade-right")
              .row.h-100.align-items-center
                .col-12
                  .p-4
                    figure
                      img(src='@/assets/curso/tema4/img1.png', alt='', style="width: 100px")
                    p.mb-0 Entre la superficie plana de la culata y la superficie plana del bloque de cilindros se necesita de una empaquetadura, diseñada para evitar fugar la compresión del motor y a su vez para permitir el paso de lubricación desde el bloque de cilindros hasta los conductos de la culata, el paso del agua de refrigeración y los orificios para los pernos o espárragos de ajuste.
            .col-lg-5(data-aos="fade-left")
              figure
                img(src='@/assets/curso/tema4/img2.png', alt='', style="width: 460px").m-auto
          .row.justify-content-center
            .col-lg-10(data-aos="fade-up")
              .p-4.bg-c16
                p Como el esfuerzo de temperatura y presión es muy grande, el empaque del cabezote debe estar diseñado de manera muy especial. Para ello se lo construye de una lámina de ‘asbesto’, tejida de malla fina de alambre (o chapa dentada) y en los bordes de los cilindros tiene unos anillos de metal, que puede ser de cobre, acero o aluminio, y que se encargan de protegerlo contra la alta temperatura de la cámara de combustión.
                .row
                  .col-lg-6.mb-4.mb-lg-0
                    figure
                      img(src='@/assets/curso/tema4/img3.png', alt='', style="width: 460px").m-auto
                  .col-lg-6
                    p En algunos casos, en los bordes de los orificios de lubricación también se instalan anillos metálicos, que sellan las posibles fugas hacia los costados, pudiendo tener adicionalmente sellos de goma (#[i O-rings]).
                    .titulo-sexto.color-acento-contenido.mb-3
                      p.mb-0 #[b Figura 4]. Junta de culata
                    figure
                      img(src='@/assets/curso/tema4/img4.png', alt='La imagen muestra una junta de culata, un componente esencial en los motores de combustión interna.', style="width: 460px").m-auto
    .row.justify-content-center.mb-4(data-aos="fade-down")
      .col-md-7.col-lg-7.col-xl-4.bg-c17
        .row.h-100.align-items-center
          .col-12
            .p-3
              p.mb-0 También según del diseño del motor, el empaque es construido totalmente de metal. No obstante, para generar un mejor sello, se troquela con formas ondeadas en las partes que debe mejorarse el sellado, en especial en el contorno de los cilindros del motor y en los bordes externos; lo que evita las posibles fugas del refrigerante y el aceite de lubricación.
      .col-md-7.col-lg-7.col-xl-4.px-0
        figure
          img(src='@/assets/curso/tema4/img5.png', alt='', style="width: 460px").m-auto
      .col-md-7.col-lg-7.col-xl-4.bg-c18
        .row.h-100.align-items-center
          .col-12
            .p-3
              p.mb-0 El espesor del empaque de la culata está definido por el fabricante, ya que de él también depende la relación de compresión que posea el motor. Algunos fabricantes producen empaques con variados espesores, para que sirva de reemplazo en caso de rectificación de la superficie, compensando el incremento del índice de compresión que se generaría.
    .row.align-items-center
      .col-lg-4.mb-4.mb-lg-0(data-aos="fade-right")
        figure
          img(src='@/assets/curso/tema4/img1.svg', alt='', style="width: 400px").m-auto
      .col-lg-8(data-aos="fade-left")
        p.mb-0 Esta variación en el espesor del empaque también puede tomarse en cuenta para aumentar o disminuir el índice de compresión, cuando se necesita modificarlo sin dañar las partes originales del motor, como la misma culata o los pistones. Generalmente, y para formar un sello más hermético, sobre algunas partes del empaque se impregna un pegante especial, que se adhiere de mejor forma con las superficies del bloque y de la culata.

</template>

<script>
export default {
  name: 'Tema4',
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
