<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido(data-aos="flip-up")
      .titulo-principal__numero
        span 2
      h1 Muelles de las válvulas
    .row.justify-content-center.mb-4(data-aos="fade-down")
      .col-lg-5.col-xl-4.bg-c10.mb-4.mb-xl-0
        .row.h-100.align-items-center
          .col-12
            .p-4
              p.mb-0 Para que una válvula pueda estar cerrada en su asiento, se necesitan de muelles helicoidales que las mantengan en esta posición; cuando la válvula no es atacada por el empuje de la leva.
      .col-lg-5.col-xl-4.ps-lg-0.mb-4.mb-xl-0
        figure
          img(src='@/assets/curso/tema2/img1.png', alt='', style="width: 420px").m-auto
      .col-xl-4
        .row.h-100.align-items-end
          .col-12
            figure.d-none.d-xl-block
              img(src='@/assets/curso/tema2/img2.png', alt='', style="width: 100px")
            p.mb-0 Así, cuando la leva empieza a atacar al balancín o al propulsor de válvula, el muelle debe permitir desplazarla en todo su recorrido, permitiendo con ello la entrada o la salida de los gases.
    .row.align-items-center.mb-4
      .col-lg-4.mb-4.mb-lg-0(data-aos="fade-right")
        figure
          img(src='@/assets/curso/tema2/img3.png', alt='', style="width: 370px").m-auto
      .col-lg-8(data-aos="fade-left")
        .row.align-items-center.mb-4
          .col-auto.d-none.d-lg-block
            figure
              img(src='@/assets/curso/tema2/img1.svg', alt='', style="width: 90px").m-auto
          .col
            p.mb-0 Este muelle está apoyado en su extremo bajo sobre una rodela plana de acero, la misma que está asentada sobre la superficie de la culata y especialmente, cuando está elaborada de metal liviano, como el aluminio, rodela que soporta la presión y evita el desgaste de esta superficie de apoyo.
        .row
          .col-md-8.bg-c12
            .row.h-100.align-items-center
              .col-12
                .p-3
                  p.mb-0 En su parte alta, el muelle está apoyado con el platillo de la válvula y mediante los seguros logra impulsarla hacia arriba, en contra del empuje de la leva.
          .col-md-4.bg-c9
            .p-3
              figure
                img(src='@/assets/curso/tema2/img2.svg', alt='', style="width: 100px").m-auto
    p.mb-4(data-aos="fade-right") Ampliemos la información sobre este tema:
    TabsC.color-acento-contenido(data-aos="fade-left")
      .p-4.p-lg-5(titulo="Muelles dobles y triples")
        .row.justify-content-center.align-items-center
          .col-lg-6.mb-4.mb-lg-0
            p #[b Muelles dobles y triples]
            p Cuando un motor moderno necesita mejorar su rendimiento, se instalan en las válvulas más de un muelle, ya que la tensión que uno solo puede aportar se vería reducida, especialmente si se piensa en el trabajo más exigente y con mayor número de revoluciones de estos motores.
            p Este diseño permite a la válvula asegurar su cierre hermético en el asiento, inclusive en elevadas revoluciones del motor, cuando el rebote de ella contra su asiento se produce.
            p Además de este factor, un solo muelle requeriría de una mayor sección del alambre; en el caso de utilizarse dos o tres muelles, esta sección se puede reducir. Lo que permite inclusive, un mayor recorrido de la válvula, sin que las espiras de cada muelle topen entre sí.
            p.mb-0 Para instalar dos o más muelles en una válvula del motor se requiere un platillo especial, que dispone de dos alturas en su superficie de apoyo, así como en la rodela de apoyo en su base.
          .col-lg-5
            figure
              img(src='@/assets/curso/tema2/img4.png', alt='', style="width: 400px").m-auto
      .p-4.p-lg-5(titulo="Tensión previa de los muelles")
        .row.justify-content-center.align-items-center
          .col-lg-6.mb-4.mb-lg-0
            p #[b Tensión previa de los muelles]
            p Debido a que el muelle de válvula debe obligar a la válvula a sellar en contra de su asiento, tanto en bajas revoluciones, como altas del giro del motor, los muelles deben mantener una tensión previa el momento de instalarlos.
            p Esta tensión previa se refiere a que el muelle debe ser comprimido previamente para instalar los platillos de válvula; cuando se los descomprime, deberán aún mantenerla empujando al platillo y con él, a la válvula. Para ello, se requiere de una herramienta apropiada, que puede comprimirlos con facilidad, mientras permite instalar los platillos y los seguros en su posición.
            p.mb-0 Luego de instalados, se podrá retirar la herramienta, asegurándonos antes de que tanto los seguros, los platillos y los mismos muelles están en su posición correcta y asegurados debidamente.
          .col-lg-5
            figure
              img(src='@/assets/curso/tema2/img5.png', alt='', style="width: 400px").m-auto
      .p-4.p-lg-5(titulo="Retenedores de las válvulas")
        .row.justify-content-center.align-items-center
          .col-lg-6.mb-4.mb-lg-0
            p #[b Retenedores de las válvulas]
            p Todas y cada una de las partes de un motor deben estar adecuadamente lubricadas, para que su trabajo en todas las condiciones, especialmente con altas temperaturas y grandes esfuerzos mecánicos, no puedan dañarlas o desgastarlas.
            p.mb-0 También que entre la válvula y la guía de las válvulas de admisión se producirán depresiones fuertes, ya que están localizadas en el flujo de entrada de los gases y forman parte de la depresión del motor durante el ciclo de admisión. En cambio, entre las válvulas de escape y sus guías podrán ingresar los gases de escape, pudiendo estos atravesar hasta la cámara de la tapa, válvulas a través de esta holgura, por lo que se hacen necesarios sellos o retenedores que no permitan este paso, y en el caso de las válvulas de admisión, no permitan la succión del aceite de lubricación.
          .col-lg-5
            figure
              img(src='@/assets/curso/tema2/img6.png', alt='', style="width: 400px").m-auto

</template>

<script>
export default {
  name: 'Tema2',
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
