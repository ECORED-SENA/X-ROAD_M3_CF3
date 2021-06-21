<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    .titulo-principal
      .titulo-principal__numero
        span 2
      h1 Construcción de servicios web: REST Y SOAP
    img.img-t.img-a(src='@/assets/ilustraciones/img5.svg', alt='')

    .titulo-segundo#t_2_1.mt-5
      .h4 2.1 Arquitectura  
    .row.justify-content-center.align-items-center
      .col-4
        img.img-t.img-a(src='@/assets/ilustraciones/img6.svg', alt='')

    .titulo-segundo#t_2_2.mt-5
      .h4 2.2 Componente lógico: subarquitectura 
    .row.justify-content-center.align-items-center
      .col-8     
        ImagenInfografica.color-acento-botones.mb-5

          template(v-slot:imagen)
            figure
              img(src='@/assets/ilustraciones/img7.svg', alt='Texto que describa la imagen')

          .tarjeta.color-acento-botones.p-3(x="66%" y="23%")
            p El Segmento de Capa REST es el responsable de definir los elementos necesarios para exponer un servicio web, usando el estilo arquitectónico REST y las operaciones expuestas por la Capa Servicio.

          .tarjeta.color-acento-botones.p-3(x="92.8%" y="23%")
            p El Segmento de Capa SOAP es el responsable de definir los elementos necesarios para exponer un servicio web, usando el protocolo SOAP y las operaciones expuestas por la Capa Servicio.

          .tarjeta.color-acento-botones.p-3(x="75%" y="37.6%")
            p La Capa Recurso es la responsable de crear los interfaces que el componente expondrá a otros componentes (u otros sistemas de software). 

          .tarjeta.color-acento-botones.p-3(x="96.5%" y="59.6%")
            p La Capa Servicio es la responsable de definir las reglas y la lógica de negocio (la funcionalidad del sistema), tomando como base las operaciones expuestas por la Capa Repositorio. 

          .tarjeta.color-acento-botones.p-3(x="66.3%" y="81%")
            p La Capa Repositorio es la responsable de manejar la entrada y salida de datos del almacén de datos, permitiendo obtener sus diferentes operaciones CRUD.
            p «Cada repositorio opera con un único elemento del modelo (entidad)».               

          .tarjeta.color-acento-botones.p-3(x="96.5%" y="81%")
            p La Capa Modelo es la responsable de abstraer las entidades de datos de la base de datos. Esta abstracción contiene tanto la representación de los datos que maneja el sistema, como sus mecanismos de persistencia.


    .tarjeta.bg-llamado.text-white.p-3.mb-5
      .row.justify-content-around.align-items-center
        .col-3.col-sm-2.col-lg-1
          img(src="@/assets/ilustraciones/img8.svg")
        .col
          .row.justify-content-between.align-items-center
            .col.mb-3.mb-sm-0
              h3.mb-1 Guía de implementación de servicios Web REST y SOAP
              p.text-small Te recomendamos leer el siguiente recurso.
            .col-sm-auto
              a.boton.color-acento-botones.texto-blanco(:href="obtenerLink('/downloads/anexo_cf3.pdf')" target="_blank")
                span Descargar
                i.fas.fa-file-download
</template>

<script>
export default {
  name: 'Tema2',
  data: () => ({
    // variables de vue
  }),
}
</script>

<style lang="sass" scoped></style>
