<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    .titulo-principal
      .titulo-principal__numero
        span 1
      h1 X-Road Academy 
  
    .row.justify-content-center.align-items-center
      .col-10
        .row.justify-content-center.align-items-stretch
          .col-md-6.col-lg.mb-5.mb-lg-0
            .tarjeta-avatar
              img.mt-5(src='@/assets/ilustraciones/img1.svg' alt='AvatarTop')
              .tarjeta.bg-color-terciario
                .text-white.p-4
                  p.mt-4 #[b X-Road Academy] ofrece capacitación en línea para cualquier persona que desee aprender más sobre la capa de intercambio de datos de X-Road.

          .col-md-6.col-lg.mb-5.mb-lg-0
            .tarjeta-avatar
              img.mt-4(src='@/assets/ilustraciones/img2.svg' alt='AvatarTop')
              .tarjeta.bg-color-terciario
                .text-white.p-4
                  p.mt-4 #[b Laboratorios oficiales del NIIS] (Nordic Institute for Interoperability Solutions), subtitulados al español.
        .row.justify-content-start.align-items-center.mt-3
          .col-5
            a.anexo.mb-4.mb-lg-0(href="https://x-road.thinkific.com/" target="_blank")
              .anexo__icono
                img(src="@/assets/template/icono-link.svg")
              .anexo__texto
                p Enlace web.  X-Road Academy. (Falta enlace)


    .titulo-segundo#t_1_1.mt-5
      .h4 1.1 Arquitectura X-Road

    figure
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/z15a7Z5qw7c" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
    p.text-center.mt-4 Video disponible desde #[b X-Road Academy]. Close Captions (traducción) Universidad Nacional de Colombia.   

    .titulo-segundo#t_1_2.mt-5
      .h4 1.2 Instalación y configuración inicial de X-Road
    
    .row.justify-content-start.align-items-center
      .col-12.col-md-10
        p El uso de contenedores Docker solo se recomienda para #[b entornos de desarrollo] y #[b ejercicios de capacitación] en la plataforma #[b X-Road].

        p Para la instalación y configuración de los componentes del ecosistema X-Road en #[b entornos de producción], se recomienda seguir la guía oficial presentada por X-Road Academy; y en el caso colombiano, los lineamientos técnicos dados por el #[b articulador] de los SCD (Servicios Ciudadanos Digitales), es decir, por la  
          a.link(href="https://and.gov.co/" target="_blank")
            | Agencia Nacional Digital - AND. 

      .col-12.col-md-2
        img.img-t.img-a(src='@/assets/ilustraciones/img3.svg', alt='') 

    figure.mt-5
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/vfowfv_Kb0Y" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
    p.text-center.mt-4 Video disponible desde #[b X-Road Academy]. Close Captions (traducción) Universidad Nacional de Colombia.  


    .titulo-segundo#t_1_3.mt-5
      .h4 1.3 Configuración del servidor central
    
    .row.justify-content-start.align-items-center
      .col-12.col-md-10
        p El uso de contenedores Docker solo se recomienda para entornos de desarrollo y ejercicios de capacitación en la plataforma X-Road.

        p Para la instalación y configuración de los componentes del ecosistema X-Road en entornos de producción, se recomienda seguir la guía oficial presentada por X-Road Academy; y en el caso colombiano, los lineamientos técnicos dados por el articulador de los SCD (Servicios Ciudadanos Digitales), es decir, por la 
          a.link(href="https://and.gov.co/" target="_blank")
            | Agencia Nacional Digital - AND. 

      .col-12.col-md-2
        img.img-t.img-a(src='@/assets/ilustraciones/img4.svg', alt='') 

    figure.mt-5
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/2E5uc8OKjyM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
    figure.mt-5
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/Vs90UYzx0aE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)         
    p.text-center.mt-4 Video disponible desde #[b X-Road Academy]. Close Captions (traducción) Universidad Nacional de Colombia.


    .titulo-segundo#t_1_4.mt-5
      .h4 1.4 Configuración del servidor de seguridad
    
    .row.justify-content-start.align-items-center
      .col-12
        p El uso de contenedores Docker solo se recomienda para #[b entornos de desarrollo] y #[b ejercicios de capacitación] en la plataforma #[b X-Road].

        p Para la instalación y configuración de los componentes del ecosistema X-Road en #[b entornos de producción], se recomienda seguir la guía oficial presentada por X-Road Academy; y en el caso colombiano, los lineamientos técnicos dados por el #[b articulador] de los SCD (Servicios Ciudadanos Digitales), es decir, por la  
          a.link(href="https://and.gov.co/" target="_blank")
            | Agencia Nacional Digital - AND. 

    figure.mt-5
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/PFM3jJsd-Ek" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
    p.text-center.mt-4 Video disponible desde #[b X-Road Academy]. Close Captions (traducción) Universidad Nacional de Colombia. 

</template>

<script>
export default {
  name: 'Tema1',
  components: {},
  data: () => ({
    // variables de vue
  }),
}
</script>

<style lang="sass" scoped></style>
