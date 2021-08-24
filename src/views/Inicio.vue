<template lang="pug">
section
  .banner-principal.mb-5
    .container.tarjeta.p-4.p-sm-5(
      :style="{'background-image': `url(${require('@/assets/curso/fondo-banner-principal.png')})`}"
    )
      .row.justify-content-around.align-items-center
        .col-lg-7.col-xxl-6.banner-principal__info
          .banner-principal__programa
            .h1.mb-0 Técnico de integración de contenidos digitales
          
          .h2 Información del programa
          .banner-principal__datos
            ul
              li.mb-2.banner-principal__datos__item
                p.h6.mb-0.me-3.banner-principal__datos__item__titulo Nombre del programa: 
                p.banner-principal__datos__item__texto Técnico de integración de contenidos digitales
              li.mb-2.banner-principal__datos__item
                p.h6.mb-0.me-3.banner-principal__datos__item__titulo Código: 
                p.banner-principal__datos__item__texto 524704
              li.mb-2.banner-principal__datos__item
                p.h6.mb-0.me-3.banner-principal__datos__item__titulo Total Horas: 
                p.banner-principal__datos__item__texto 2208 horas
              li.mb-2.banner-principal__datos__item
                p.h6.mb-0.me-3.banner-principal__datos__item__titulo Duración en semanas: 
                p.banner-principal__datos__item__texto 52 Semanas
              li.mb-2.banner-principal__datos__item
                p.h6.mb-0.me-3.banner-principal__datos__item__titulo Modalidad: 
                p.banner-principal__datos__item__texto virtual
              li.mb-3.banner-principal__datos__item
                p.h6.mb-0.me-3.banner-principal__datos__item__titulo Requisito de ingreso: 
                p.banner-principal__datos__item__texto nivel académico básica secundaria (certificación académica de grado 9) y edad mínima 14 años.   
              
        .d-none.d-lg-block.col-lg-5
          //- img(src="@/assets/curso/banner-princiapal.svg")
          .video
            | <iframe data-v-1f9e4816="" width="560" height="315" src="https://www.youtube.com/embed/2L91WMqw96A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen="allowfullscreen"></iframe>

  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 1. Presentación

    p La industria 4.0 se refiere a una nueva fase en la Revolución industrial que se centra principalmente en la interconectividad, la automatización y los datos en tiempo real.
    p La educación en la Industria 4.0 o Cuarta Revolución Industrial se identifica como un término integrador que abarca temas como la programación científica, el desarrollo empresarial enfocado en la innovación y el aprendizaje analítico. Todo esto enfocado en proyectos que permitirán formar a los aprendices en competencias avanzadas en tecnología, en los campos digitales y aplicables a todas las industrias.
    p El SENA, en el programa de formación Técnico en Integración de Contenidos Digitales desarrolla elementos sociales, tecnológicos y culturales, a través de la formación profesional integral, que incentivan el desarrollo de competencias y el aprendizaje por proyectos. El fortalecimiento y crecimiento socioeconómico tanto a nivel regional como nacional dependen en gran medida del capital humano cualificado, capaz de responder integralmente a la dinámica del sector.
    p Brinda al sector productivo nacional, relacionado con la industria de la comunicación, la posibilidad de incorporar personal con altas calidades laborales y profesionales que contribuyan al desarrollo económico, social y tecnológico de su entorno. Así mismo, ofrecer a los aprendices formación en tecnologías y metodologías para el diseño e integración de proyectos multimediales, factores muy importantes para una utilización efectiva de estas tecnologías.


  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 2. Justificación del programa

    p De acuerdo con los datos arrojados por Min Tic y ProColombia, las exportaciones de las industrias 4.0 evidencian el crecimiento exponencial de la industria TI y de contenidos digitales donde claramente, el país cuenta con potencial productivo para el desarrollo de contenidos digitales, en el marco de SENA es economía naranja y alineados a las estrategias en torno a esta industria del gobierno nacional. 
    p Esto debido a que se trata de proyectos que pueden ser aplicables a cualquier sector y cuya implementación requiere de una infraestructura tecnológica específica conformada por equipos de cómputo de alta gama, accesorios para interactividad y software que permita integrar todas las herramientas en la ejecución de estos proyectos, donde todo está al alcance de los entes gubernamentales locales, regionales y nacionales. 
    p El SENA integra dentro de este programa de formación, elementos sociales, tecnológicos y culturales, a través de la formación profesional integral, que incentivan el desarrollo de competencias y el aprendizaje por proyectos. El fortalecimiento y crecimiento socioeconómico tanto a nivel regional como nacional dependen en gran medida del capital humano cualificado, capaz de responder integralmente a la dinámica del sector.


  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 3. Población objetivo

    p Aprendices técnicos, estudiantes de articulación con la media, empresas familiares, unipersonales, mi Pymes, sociedades, personas naturales productivas, pymes, grandes empresas, organizaciones sociales, organizaciones defensoras de derechos humanos, otras comunidades, organizaciones locales, nacionales e internacionales del sector público y privado.


  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 4. Estrategia metodológica

    p Está centrada en la construcción de autonomía para garantizar la calidad de la formación en el marco de la formación por competencias, el aprendizaje por proyectos y el uso de técnicas didácticas activas que estimulan el pensamiento para la resolución de problemas simulados y reales; soportadas en la utilización de las tecnologías de la información y la comunicación, integradas en ambientes virtuales de aprendizaje que, en todo caso recrean el contexto productivo y vinculan al aprendiz con la realidad cotidiana y el desarrollo de las competencias. 
    p Igualmente, debe estimular de manera permanente la autocrítica y la reflexión del aprendiz sobre el que hacer y los resultados de aprendizaje que logra a través de la vinculación activa de las cuatro fuentes de información para la construcción de conocimiento:
    ul.px-4.lista-ul--color.mt-2
      li 
        i.fas.fa-circle
        span El instructor - Tutor.
      li 
        i.fas.fa-circle
        span El entorno.
      li 
        i.fas.fa-circle
        span Las TIC.
      li 
        i.fas.fa-circle
        span El trabajo colaborativo.    


  //- Créditos
  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 Créditos

    
    .creditos
      div(
        v-for="(creditoKey, index) of Object.keys(creditosData)"
        :class="index != Object.keys(creditosData).length -1 ? 'mb-4' : ''" 
      )
        .creditos__titulo {{configTitulos[creditoKey]}}
        table
          tbody
            tr(
              v-for="(item, idx) of creditosData[creditoKey]" 
              :key="creditoKey+idx"
            )
              td.text-bold(colspan='2' v-html="renderText(item.nombre)")
              td(colspan='2' v-html="renderText(item.cargo)")
              td(colspan='3' v-html="renderText(item.centro)")

  Footer

</template>
<script>
export default {
  name: 'Inicio',
  data: () => ({
    configTitulos: {
      liderEquipo: 'ECOSISTEMA DE RECURSOS EDUCATIVOS DIGITALES',
      contenidoInstruccional: 'CONTENIDO INSTRUCCIONAL',
      desarrolloProducto:
        'DISEÑO Y DESARROLLO DE RECURSOS EDUCATIVOS DIGITALES',
      gestoresRepositorio: 'GESTORES DE REPOSITORIO',
    },
  }),
  computed: {
    creditosData() {
      return this.$config.creditos
    },
  },
  methods: {
    renderText(textObj) {
      let newText = ''
      if (Array.isArray(textObj)) {
        textObj.forEach((texto, index) => {
          newText += (index ? '<br/>' : '') + texto
        })
      } else {
        newText += textObj
      }
      return newText
    },
  },
}
</script>

<style lang="sass">
.creditos
  td, th
    border-color: $color-sistema-c
</style>
