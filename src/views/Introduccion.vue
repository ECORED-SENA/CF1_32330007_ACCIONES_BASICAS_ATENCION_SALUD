<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
  
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span
          i.fas.fa-info
      h1 Introducción
    p.mb-5(data-aos='fade-right') La formación en primeros auxilios es fundamental para garantizar una respuesta rápida y eficaz en situaciones de emergencia. Este componente formativo ofrece una comprensión integral de la evaluación de la escena, que es crucial para asegurar la seguridad del primer respondiente y del paciente. Al identificar y mitigar posibles peligros, se crea un entorno seguro para proporcionar la atención necesaria de manera efectiva. 
    .row.justify-content-center.mb-5
      .col-lg-4.col-7.mb-lg-0.mb-3(data-aos="fade-right"): img(src='@/assets/curso/temas/1.png', alt='')
      .col-lg-8(data-aos="fade-left")
        .p-4(style="background-color: #EEFAD1")
          p.mb-0 Además, se detallan las características y acciones esenciales que debe tomar un primer respondiente. Desde identificarse y tranquilizar a los presentes hasta prevenir riesgos adicionales, alertar a los servicios de emergencia, examinar a los pacientes y vigilar su evolución, estos pasos son vitales para el manejo adecuado de cualquier incidente. La guía también explora la cinemática del trauma, ayudando a los auxiliadores a entender y analizar la escena de un accidente para determinar las posibles lesiones y proporcionar el tratamiento más adecuado. 
    .row.justify-content-center.mb-5
      .col-lg-10(data-aos="fade-left")
        .p-4(style="background-color: #FAFDF2")
          p.mb-0 Finalmente, el componente incluye instrucciones detalladas para la preparación y uso de botiquines de primeros auxilios, adaptados a diferentes contextos como vehículos, entornos básicos y empresariales. Estos botiquines contienen elementos indispensables para la atención inicial de las víctimas. 
      .col-lg-2.col-7.mb-lg-0.mb-3(data-aos="fade-right"): img(src='@/assets/curso/temas/2.svg', alt='')
    
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
