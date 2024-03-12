<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    .titulo-principal.color-acento-botones
      .titulo-principal__numero
        span.numero 7
      h1.text-in Sistemas de gestión de calidad
    .tarjeta.row.mb-5.bg7
      .tarjeta.py-5.mb-1
        .row.ml-1-cus
          .col-12
            p.mb-4 El sistema de gestión profundizado en la calidad plantea herramientas que permite a las organizaciones planear, implementar, controlar y realizar seguimientos a las actividades de la organización empresarial a través de estándares de calidad, lo cual dicha información proporciona desarrolla indicadores de alerta o normalidad de los procesos.
            
            .row.justify-content-center.align-items-center.mb-5
              .col-lg-6(data-aos="fade-left")

                p.mb-4 Los objetivos de aprendizaje con que se desarrollan los sistemas de gestión de calidad son los siguientes:

                ol.lista-ol--cuadro
                  li 
                    .lista-ol--cuadro__vineta
                      span 1
                    |   Aplicar herramientas adecuadas para la evaluación de riesgos.
                  li 
                    .lista-ol--cuadro__vineta
                      span 2
                    | Participar en evaluaciones de riesgo.
                  li 
                    .lista-ol--cuadro__vineta
                      span 3
                    | Conocer las diferentes categorías de riesgo.
                  li 
                    .lista-ol--cuadro__vineta
                      span 4
                    |  Conocer e interpretar la terminología y requisitos legales en la normatividad.  
                  li 
                    .lista-ol--cuadro__vineta
                      span 5
                    | Dicha información está diseñada para aprender a evaluar riesgos que se presenten en los diversos puntos de los puestos de trabajo de la empresa.

              .col-lg-6
                img.img-t.img-a.my-2(src='@/assets/curso/Tema7/1.png', alt='') 


    .row.justify-content-center.align-items-stretch.mt-5
      .col-12.cuadro-gestion.p-4
          p.mb-2 Por otro lado, el manejo del riesgo es un proceso que está definido de manera secuencial, monitoreando el control de riesgo interno de los diversos cargos laborales de la organización. De esta forma, se ha diseñado diversas estrategias que proporcionan metodologías a procesos de trabajo, bien sea de procesos manufacturados como procesos de prestación de servicio, siempre en pro de evaluar las mejores prácticas de trabajo basados en la mejora continua.
    
    
    
    .row.justify-content-center.align-items-center.mt-5

      .col-7.d-none.d-lg-block
        img.img-t.img-a(src='@/assets/curso/Tema7/2.png', alt='')

      .col-lg-5
        ol.lista-ol--cuadro.mt-5
          li 
            .lista-ol--cuadro__vineta
              span 1
            | Cumplimiento enfocado a las necesidades del cliente.
          li 
            .lista-ol--cuadro__vineta
              span 2
            | Liderazgo y planeación.
          li 
            .lista-ol--cuadro__vineta
              span 3
            | Participación del equipo de trabajo.
          li 
            .lista-ol--cuadro__vineta
              span 4
            | Visión de las tareas y actividades a desarrollar.
          li 
            .lista-ol--cuadro__vineta
              span 5
            | Implementación de la organización al sistema hacia la gestión.
          li 
            .lista-ol--cuadro__vineta
              span 6
            | Planes de mejora continua.
          li 
            .lista-ol--cuadro__vineta
              span 7
            | Alianzas estratégicas con proveedores.
      

   
    .mt-5.d-flex
      .d-flex.flex-wrap.align-items-center.pe-4
        h3.col.px-4.mb-0.text-white.bg-img-blue(style='width: 450px;') Sistemas de gestión de calidad en la salud
        img.col-lg.d-flex(src='@/assets/curso/temas/icon-bot.svg').icon-img-blue
    p.my-5 Desarrollando la gestión de calidad en la salud y seguridad en el trabajo, se fundamenta desde la mejora continua planteando políticas organizacionales, enfocadas a la planeación organizacional, donde se desarrollan implementaciones de la aplicabilidad de los fundamentos inicialmente proyectados, para proceder a unas inspecciones y evaluaciones de cumplimiento e iniciar a controlar los puntos que se encuentran funcionando de manera óptima, sin descuidar los riesgos que afecten la seguridad y salud de las personas que conforman el equipo de trabajo.
    p Se representan por las siguientes etapas:

    .row.justify-content-center.align-items-stretch.mt-5
      .col-lg-3        
        .imagen.indicador__container
          img.yoyo.img-t.img-a(src='@/assets/curso/Tema7/4.svg', alt='' @mouseover="mostrarIndicador = false")
          .indicador--click(v-if="mostrarIndicador")           
          .info
            p.descripcion.p-3.mb-0 Es todo evento no deseado o no esperado que ocasiona una pérdida.
      .col-lg-3        
        .imagen
          img.yoyo-1.img-t.img-a(src='@/assets/curso/Tema7/5.svg', alt='')
          .info-1
            p.descripcion.p-3.mb-0 Evento no deseado que da lugar a la muerte, enfermedad o lesión, bien sea del personal de trabajo o de los equipos e instalaciones de la empresa.
      .col-lg-3        
        .imagen
          img.yoyo.img-t.img-a(src='@/assets/curso/Tema7/6.svg', alt='')
          .info-2
            p.descripcion.p-3.mb-0 Es la fuente de causar una lesión, daño o enfermedad en el ambiente de trabajo. Los peligros suelen ser de dos tipos: físicos y químicos; donde los físicos son ruido, radiación, iluminación, temperaturas altas y vibraciones. Por otro lado, los peligros químicos son sustancias tóxicas, polución y material particulado.                     
              

    .row.justify-content-center.align-items-center.mt-5
      .col-lg-6
        .BorTit  #[b Figura 12.]  Etapas de sistema de gestión de calidad en salud. Fuente: SENA 2021, Fernellis Mauricio Echeverry.

        img.img-t.img-a.mt-4(src='@/assets/curso/Tema7/7.svg', alt='')  
    
    Separador

    .titulo-segundo.color-acento-botones#t_7_1
      .h4 7.1  Seguridad e higiene en la industria

    p.mb-4 La seguridad e higiene en la industria se refiere a las actividades identificadas al seguimiento y control de los factores que representan un riesgo y alteran la salud del equipo de trabajo de la organización empresarial, que puedan verse representadas en enfermedades profesionales o accidentes de trabajo. Esto se da al plantear puntos críticos de riesgo de acuerdo con las maquinas utilizadas o trabajos en alturas o al definir líneas de factores de riesgo para mantener una monitorización.
    p Para conocer la seguridad e higiene en la industria es importante identificar los siguientes elementos:

    .tarjeta.tarjeta--gris-bg-1.p-4.mt-5
      LineaTiempoC
        .row.justify-content-center.align-items-center(titulo="Medicina preventiva y del trabajo")
          .col-md-3
            figure
              img(src='@/assets/curso/Tema7/9.png', alt='Medicina preventiva y del trabajo')      
          .col-md-7.mb-4.mb-md-0
            p.mb-3 #[b Medicina preventiva y del trabajo]
            p.mb-3 Actividades fundamentadas a la calidad y seguridad de la vida de los empleados a través de mantenimientos predictivos, preventivos y correctivos de los equipos que se encuentren dentro de los activos de la empresa.
            p Se genera una relación entre equipos y maquinaria, donde se generan informes de salud y seguridad de los empleados que manipulan dichas maquinarias optimizando los recursos de las empresas, pero también en el autocuidado del personal operativo.
    
        .row.justify-content-center.align-items-center(titulo="Comité Paritario de Salud Ocupacional (COPASO)")
          .col-md-3
            figure
              img(src='@/assets/curso/Tema7/10.png', alt='Comité Paritario de Salud Ocupacional (COPASO)')      
          .col-md-7.mb-4.mb-md-0
            p #[b Comité Paritario de Salud Ocupacional (COPASO)]
            p “Resolución 2013 de 1986, en el Decreto 614 de 1984, y en el Decreto 1295 de 1994”. Donde se eligen un grupo de personas de la misma compañía en coordinación del empleador y sus empleados, este equipo de trabajo plantea, ejecuta y evalúa promover las leyes y normas que reglamentan la salud ocupacional en las organizaciones empresariales y el control de ética y desarrollo de clima laboral, desde las problemáticas comunes que se generan en el desarrollo diario de la vida laboral de la empresa. 
            p Los empleados y empleadores deben participar de manera activa del Comité Paritario, proponiendo la vigilancia y control del desarrollo de las actividades, asegurando el cumplimiento de la empresa al trabajar en pro de la higiene y seguridad industrial, cumpliendo con las normas vigentes y su respectiva divulgación a los integrantes del equipo de trabajo.
        .row.justify-content-center.align-items-center(titulo="Programa de salud ocupacional")
          .col-md-3
            figure
              img(src='@/assets/curso/Tema7/11.png', alt='Programa de salud ocupacional')      
          .col-md-7.mb-4.mb-md-0
            p #[b Programa de salud ocupacional] 
            p Este se conforma por la planeación, organización, ejecución y evaluación; actividades que desarrolla la empresa para su actividad económica, para la conservación y mejora de las condiciones de salud individual y colectiva de los trabajadores en sus ocupaciones.
        .row.justify-content-center.align-items-center(titulo="ARL")
          .col-md-3
            figure
              img(src='@/assets/curso/Tema7/31.png', alt='ARL')      
          .col-md-7.mb-4.mb-md-0
            p #[b ARL]
            p Se define como las entidades de carácter público o privado, además de las normas que velan por la prevención, protección y atención de los trabajadores ante las enfermedades profesionales o accidentes que podrían ocurrir dentro del ambiente laboral. 
        .row.justify-content-center.align-items-center(titulo="Factor de riesgo")
          .col-md-3
            figure
              img(src='@/assets/curso/Tema7/13.png', alt='Factor de riesgo')      
          .col-md-7.mb-4.mb-md-0
            p #[b Factor de riesgo]
            p todos los objetos y herramientas que se usan en los diversos puestos de trabajo, que puedan ocasionar condiciones de riesgo, al accionarlas y manipularlas por las personas. Pueden generar riesgos de tipo medioambiental, lesiones o daños a las instalaciones.
            .tarjeta.tarjeta-color-cuarta.p-3.mb-5
              .row.justify-content-around.align-items-center
                .col-3.col-sm-2.col-lg-1
                  img(src="@/assets/curso/Tema7/8.svg")
                .col
                  .row.justify-content-between.align-items-center
                    .col.mb-3.mb-sm-0
                      h3.mb-1 Anexo
                      p.text-small Explorar el siguiente documento llamado “Formato de consumo de sesgos”.
                    .col-sm-auto
                      a.boton.color-boton.texto-blanco(:href="obtenerLink('downloads/prueba.pdf')" target="_blank")
                        span Descargar
                        i.fas.fa-file-download


                    
        .row.justify-content-center.align-items-center(titulo="Higiene Industrial")
          .col-md-3
            figure
              img(src='@/assets/curso/Tema7/24.png', alt='Higiene Industrial')      
          .col-md-7.mb-4.mb-md-0
            p #[b Higiene industrial]
            p Se persevera a mantener unos objetivos definidos para prevenir enfermedades profesionales y tener el mínimo impacto en el medio ambiente, en actuación de los agentes contaminantes medioambientales y sociales a la salud de los trabajadores, en consecuencia, al desarrollo productivo de las compañías.

        .row.justify-content-center.align-items-center(titulo="Seguridad Industrial")
          .col-md-3
            figure
              img(src='@/assets/curso/Tema7/25.png', alt='Seguridad Industrial')      
          .col-md-7.mb-4.mb-md-0
            p #[b Seguridad industrial]
            p Normas técnicas que definen objetivos para proteger la vida, salud e integridad física y mental de las personas que componen el equipo de trabajo, proponiendo las mejores condiciones de productividad entre las condiciones de los trabajadores y los resultados planteados. 

        .row.justify-content-center.align-items-center(titulo="Ergonomía")
          .col-md-3
            figure
              img(src='@/assets/curso/Tema7/26.png', alt='Ergonomía')      
          .col-md-7.mb-4.mb-md-0
            p #[b Ergonomía]
            p La ergonomía desarrolla esquemas de medición y posición de los trabajadores en los diversos puestos de trabajo, considerando la adaptación y evaluando el porcentaje de fatiga física que este pueda desarrollar en sus actividades diarias de trabajo. 

        .row.justify-content-center.align-items-center(titulo="Riesgo profesional")
          .col-md-3
            figure
              img(src='@/assets/curso/Tema7/27.png', alt='Riesgo profesional')      
          .col-md-7.mb-4.mb-md-0
            p #[b Riesgo profesional]
            p Son evidencias que ponen en riesgo a un trabajador en una actividad de alta vulnerabilidad por la actividad a desarrollar a diario en su ámbito profesional. 

        .row.justify-content-center.align-items-center(titulo="Señalización de evacuación")
          .col-md-3
            figure
              img(src='@/assets/curso/Tema7/28.png', alt='Señalización de evacuación')      
          .col-md-7.mb-4.mb-md-0
            p #[b Señalización de evacuación]
            p La señalización en las organizaciones funciona de manera preventiva para evitar accidentes o también son señales de información para saber en qué punto están ubicadas las cosas en las organizaciones, por ejemplo, una de las herramientas más señalizadas son los extintores, por su gran importancia en el ámbito de confección y textil, por lo que la maquinaria y los recursos utilizados presentan un riesgo bastante alto.

            p Las señalizaciones están consideradas por los siguientes tipos:

            ul.lista-ul--color.p-left
              li 
                i.lista-ul__vineta
                | Señalización precaución.
              li 
                i.lista-ul__vineta
                | Señalización de peligro y prohibición.
              li 
                i.lista-ul__vineta
                | Señalización de motivación.


        .row.justify-content-center.align-items-center(titulo="Extintores")
          .col-md-3
            figure
              img(src='@/assets/curso/Tema7/29.png', alt='Extintores')      
          .col-md-7.mb-4.mb-md-0
            p #[b Extintores]
            p Son elementos portables que permiten luchar contra fuegos incipientes o principios de incendios, los cuales permiten ser dominados y extinguidos en forma breve.

            p Clasificación:
            ul.lista-ul--color.p-left
              li 
                i.lista-ul__vineta
                | Tipo ABC Extintores de Polvo químico seco 
              li 
                i.lista-ul__vineta
                | Tipo A Extintores de espuma 
              li 
                i.lista-ul__vineta
                | Tipo A B Extintores de dióxido de carbono

        .row.justify-content-center.align-items-center(titulo="Evacuación")
          .col-md-3
            figure
              img(src='@/assets/curso/Tema7/30.png', alt='Evacuación')      
          .col-md-7.mb-4.mb-md-0
            p #[b Evacuación]
            p Es la acción de organizar una manera ordenada para abandonar un determinado lugar, esto puede darse por razones de actos inseguros ante un peligro potencial o contingencia. El principal objetivo es prevenir la pérdida de la vida de las personas que conforman un equipo de trabajo, evitando lesiones y proteger bienes de la compañía.

            p La proyección y planeación de la ruta de evacuación es de vital importancia para que los trabajadores conozcan cual es el lugar seguro hacia donde deben dirigirse en caso de una evacuación de emergencia, bien sea por actos inseguros de la compañía o por riesgos ambientales. Se debe proporcionar evacuaciones de manera preventiva y llegar al punto de encuentro de manera calmada y ordenada, atendiendo la emergencia.

            p Se cataloga como fenómenos perturbadores los sismos o temblores, incendios, inundaciones deslizamientos de tierras, explosiones (sabotaje y otros como actos terroristas). 

    Separador
    .titulo-segundo.color-acento-botones#t_7_2
      .h4 7.2 Normas técnicas de salud

    p.mb-5 Para determinar aspectos importantes que toda empresa de textil debe tener en cuenta para llevar a cabo sus procesos con respecto a la seguridad y salud en el trabajo, es necesario identificar y entender las siguientes normas técnicas de salud:

    .row.justify-content-center.align-items-center.mt-5
      .col-lg-10
        AcordionA(tipo="b" clase-tarjeta="tarjeta tarjeta-inactiva")
          .row.justify-content-center.align-items-center(titulo="Norma técnica ISO 14001")
            .col-md-3
              figure
                img.my-3(src='@/assets/curso/Tema7/14.svg', alt='Norma técnica ISO 14001') 
        
            .col-md-6.mb-4.mb-md-0
              h5 ISO 14001 Reglamento para la Apertura y Control Sanitario de Plantas confección y textil 
              p La norma establece condiciones sanitarias constructivas para los ambientes de trabajo. Establece en sus anexos las concentraciones máximas permisibles de gases, vapores y los límites permisibles de acumulación de radiación en órganos críticos. (emisión de gases, residuos sólidos y vertimientos de aguas y aceites).

              p Fuente: (https://www.nueva-iso-14001.com/pdfs/FDIS-14001.pdf.).

          .row.justify-content-center.align-items-center(titulo="Ley 1972 de 2019")
            .col-md-3
              figure
                img.my-3(src='@/assets/curso/Tema7/15.svg', alt='Ley 1972 de 2019') 
        
            .col-md-6.mb-4.mb-md-0
              h5 Emisión de gases contaminantes 
              p La norma tiene como objetivo garantizar las condiciones de seguridad de los trabajadores y conservación del medio ambiente en todos los lugares donde desarrollen sus actividades. Establece la responsabilidad del titular de la industria fomentando la participación del personal, la capacitación y las obligaciones de los trabajadores. 
              p Asimismo, establece consideraciones técnicas de seguridad para locales y establecimientos industriales, como normas sobre prevención y protección contra incendios, maquinarias, equipo eléctrico, herramientas, calderos de vapor, transporte de materiales, sustancias peligrosas, radiaciones peligrosas, mantenimiento, reparación y equipo de protección personal.

              p Fuente: (https://www.minambiente.gov.co/index.php/asuntos-ambientales-sectorial-y-urbana/gestion-del-aire/emisiones-contaminantes).

          .row.justify-content-center.align-items-center(titulo="Decreto 1713 de 2002")
            .col-md-3
              figure
                img.my-3(src='@/assets/curso/Tema7/16.svg', alt='Decreto 1713 de 2002') 
        
            .col-md-6.mb-4.mb-md-0
              h5 Residuos sólidos 
              p Colombia cuenta con unas legislaciones muy desarrolladas, con unas normas  bien constituidas basadas en la conservación y mitigación de los recursos naturales y su impacto en el medio ambiente. 

              p Fuente: (http://www.pasocierto.com.br/assets/dd22-co_legislaci%C3%B3n-municipal_colombia.pdf).

          .row.justify-content-center.align-items-center(titulo="Resolución 0631 de 2015 reglamenta el artículo 28 del Decreto 3930 de 2010 y actualiza el Decreto 1594 de 1984")
            .col-md-3
              figure
                img.my-3(src='@/assets/curso/Tema7/17.svg', alt='Resolución 0631 de 2015 reglamenta el artículo 28 del Decreto 3930 de 2010 y actualiza el Decreto 1594 de 1984') 
        
            .col-md-6.mb-4.mb-md-0
              h5 Vertimiento de aguas y aceites contaminantes 
              p El agua es primordial para todas las actividades económicas y para el consumo humano, mayormente para esos aspectos se utiliza agua dulce, por lo que es necesario conservarla, restaurarla y protegerla.

              p Fuente: (https://www.minambiente.gov.co/images/normativa/app/resoluciones/f8-Resoluci%C3%B3n%20415%20de%201998%20-%20Aceites%20Usados.pdf.).
              p (http://www.ideam.gov.co/documents/24024/36843/Dec_1594_1984.pdf/aacbcd5d-fed8-4273-9db7-221d291b657f).  
          .row.justify-content-center.align-items-center(titulo="Normatividad Ambiental - Salud")
            .col-md-3
              figure
                img.my-3(src='@/assets/curso/Tema7/18.svg', alt='Normatividad Ambiental - Salud') 
        
            .col-md-6.mb-4.mb-md-0
              h5 Salud ambiental 
              p Otra de las principales obligaciones de las empresas textiles es el cumplimiento de esta Ley a fin de fomentar la promoción de una cultura de prevención de riesgos laborales, que no solo involucre la participación de los trabajadores y empleadores sino también a las organizaciones sindicales.

              p Fuente: (https://www.minambiente.gov.co/index.php/salud-ambiental).

          .row.justify-content-center.align-items-center(titulo="Normatividad Ambiental - Economía")
            .col-md-3
              figure
                img.my-3(src='@/assets/curso/Tema7/19.svg', alt='Normatividad Ambiental - Economía') 
        
            .col-md-6.mb-4.mb-md-0
              h5 Economía circular 
              p Colombia introduce con la Estrategia Nacional de Economía Circular nuevos elementos para fortalecer el modelo de desarrollo económico, ambiental y social del país, a partir de la lógica de “producir conservando y conservar produciendo”. En línea con los fundamentos del desarrollo sostenible y tendencias internacionales, con la estrategia se promueve la eficiencia en el uso de materiales, agua y energía, teniendo en cuenta la capacidad de recuperación de los ecosistemas y el uso circular de los flujos de materiales.

              p Fuente:(https://www.minambiente.gov.co/index.php/estrategia-nacional-de-economia-circular-ec).

    Separador
    .titulo-segundo.color-acento-botones#t_7_3
      .h4 7.3 Ambientales para plantas de confección    

    p.mb-5 La construcción y parametrización de la dimensión ambiental para procesos de confección y textil, permite la identificación, organización y digitalización de la información ambiental, proyectando indicadores de control con respecto al impacto medioambiental, con ello se definen los siguientes elementos:

    .row.mb-5
      .col-md-6.col-lg.mb-5.mb-lg-0
        .tarjeta-avatar
          img(src='@/assets/curso/Tema7/20.svg' alt='AvatarTop')
          .tarjeta.color-tarjeta-avatar
            .p-4
              h2.text-center.titulo-caracteristicas Línea de base ambiental sectorial
              p La construcción está basada en metodologías que dimensionen y parametricen aspectos medio ambientales, organizando las pautas de identificación para la organización y digitalizar la información de esta. El estado sectorial de la información del gremio, condicionando siguientes variables que tienen como factor común las organizaciones textileras y confeccionistas, (producción de residuos sólidos, líquidos, gaseosos y generación de impacto social). Donde proyecta un control por parte de los entes de planeación territorial.

      .col-md-6.col-lg.mb-5.mb-lg-0
        .tarjeta-avatar
          img(src='@/assets/curso/Tema7/21.svg' alt='AvatarTop')
          .tarjeta.color-tarjeta-avatar
            .p-4
              h2.text-center.titulo-caracteristicas Diagnósticos modo sectorial
              p Busca la estrategia entre el Estado y la gestión empresarial dentro de las pautas medio ambientales, clasificando características que potencialmente generen problemas de alto impacto. Planteando posibles soluciones de acuerdo con las necesidades económicas y sociales.

      .col-md-6.col-lg.mb-5.mb-lg-0
        .tarjeta-avatar
          img(src='@/assets/curso/Tema7/22.svg' alt='AvatarTop')
          .tarjeta.color-tarjeta-avatar
            .p-4
              h2.text-center.titulo-caracteristicas Visión ambiental por sectores
              p La visión ambiental sectorizada construye de manera participativa y consensuada planes de trabajo a corto, mediano y largo plazo; a partir de un diagnostico estratégico, que permite definir objetivos, optimizando y mejorando estrategias optimas de trabajo dentro de los sectores textiles y confeccionistas. 



    p.mb-5 En el siguiente esquema, se encuentran las temáticas de capacitación del personal o equipo de trabajo. Se desarrolla la parte de salud ocupacional, seguridad y salud en el trabajo y la clasificación de procesos industriales donde se generan residuos y contaminantes tanto para al ambiente como para la afectación de las personas que componen la organización empresarial. 


    .row.justify-content-center.align-items-center.mt-5
      .col-lg-8
        .BorTit  #[b Figura 12.]  Plan de capacitación plantas de confección. Fuente: SENA 2021, Erika Blanco.

        img.img-t.img-a.mt-4(src='@/assets/curso/Tema7/23.svg', alt='') 



</template>

<script>
export default {
  name: 'Tema7',
  data: () => ({
    mostrarIndicador: true,
    modal1: false,
    modal2: false,
    modal3: false,
  }),
}
</script>

<style lang="sass" scoped></style>
