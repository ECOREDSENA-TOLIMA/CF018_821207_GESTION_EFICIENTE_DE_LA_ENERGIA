<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-botones
      .titulo-principal__numero
        span 2
      h1 Métodos para procesar, graficar y analizar datos

    .bloque-texto-g.color-primario.p-3.p-sm-4.p-md-5.mb-5(data-aos="fade-down-right")
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/temas/tema2/tema2-01.png')})`}"
      )
      .bloque-texto-g__texto.p-4 
        p.mb-0 Después de la recolección de datos, limpieza inicial y clasificación de los mismos se sigue un conjunto de procedimientos para obtener los datos / información deseados del trabajo de campo que se desea ejecutar, para procesar, graficar y analizar los hechos de manera lógica y científica.

    Separador
    #t_2_1.titulo-segundo.color-acento-botones(data-aos="fade-right")
      h2 2.1 Métodos de investigación


    .row.mb-5.align-self-stretch.justify-content-center.align-items-center
      .col-12.col-md-4.mb-5.mb-lg-0.d-none.d-sm-none.d-md-block(data-aos="fade-right")
        figure
          img(src='@/assets/curso/temas/tema2/tema2-02.png', alt='')
      .col-12.col-md-8.mb-5.mb-lg-0(data-aos="fade-left")
        p Estos métodos son procesos que se utilizan para recopilar datos. Puede utilizar estos datos para analizar métodos o procedimientos actuales y encontrar información adicional sobre un tema. Los profesionales utilizan métodos de investigación mientras estudian medicina, comportamiento humano y otros temas académicos. Hay dos categorías principales de métodos de investigación: métodos de investigación cualitativa y métodos de investigación cuantitativa; ahora se ejemplifica la mirada cuantitativa:
        .row.justify-content-center.align-items-center.mb-3
          .col-12(data-aos="fade-right")
            ul.lista-ul.mb-2
              li.mb-0
                i.fas.fa-play(style="color:#25FFFF")
                | Los métodos de investigación cuantitativa…
        p Implican el uso de números para medir datos. Los investigadores pueden utilizar el análisis estadístico para encontrar conexiones y significado en los datos. Los métodos de investigación cualitativa implican explorar información y datos no numéricos. Estos métodos de investigación también examinan cómo las personas pueden conectar el significado con sus experiencias y emociones. 

    .row.justify-content-center.align-items-center.mb-5
      .col-12(data-aos="fade-right")
        ul.lista-ul.mb-2
          li.mb-0
            i.fas.fa-play(style="color:#25FFFF")
            | #[strong Tipos de métodos de investigación:]


    TabsA.color-acento-contenido.mb-5
      .tarjeta.tarjeta--azul.p-4(titulo="Método sintético")
        h4 Método sintético 
        p Busca la reconstrucción de componentes dispersos de un objeto o evento para estudiarlos en profundidad y crear un resumen de cada detalle. El proceso de este método se desarrolla de lo abstracto a lo concreto para aglutinar cada segmento que conforma una unidad y poder comprenderlo.
      .tarjeta.tarjeta--azul.p-4(titulo="Método analítico")
        h4 Método analítico 
        p Se encarga de desagregar los apartados que componen el conjunto del caso a estudiar, estableciendo las relaciones de causa, efecto y naturaleza. A partir de los análisis realizados, se pueden generar analogías y nuevas teorías para comprender los comportamientos.
        p Se desarrolla en la comprensión de lo concreto a lo abstracto, descomponiendo los elementos que constituyen la teoría general para estudiar con mayor profundidad cada elemento por separado y, de esta manera, conocer la naturaleza del fenómeno de estudio para revelar su esencia. Mediante el razonamiento y la síntesis se enfatiza la profundidad del análisis de forma metódica y concisa para obtener un conocimiento profundo de cada parte y particularidad de lo estudiado.
      .tarjeta.tarjeta--azul.p-4(titulo="Método inductivo")
        h4 Método inductivo
        p Con este método se pueden analizar situaciones particulares a través de un estudio individual de los hechos que formule conclusiones generales, que ayudan al descubrimiento de temas y teorías generalizadas que parten de la observación sistemática de la realidad. Es decir, se refiere a la formulación de hipótesis a partir de lo vivido y observado de los elementos de estudio para definir leyes generales. Consiste en la recogida de datos ordenados en variables en busca de regularidades.
      .tarjeta.tarjeta--azul.p-4(titulo="Método deductivo")
        h4 Método deductivo
        p Se refiere a un método desde lo general para enfocarse en lo específico a través de razonamientos lógicos e hipótesis que pueden sustentar conclusiones. Este proceso se basa en los análisis anteriores, leyes y principios validados y probados para ser aplicados a casos particulares.
        p En este método, todo el esfuerzo de investigación se basa en las teorías recopiladas, no en lo observado o experimentado; forma parte de una premisa para delinear y concluir la situación de estudio, deduciendo el camino a seguir para implementar las soluciones. 
      .tarjeta.tarjeta--azul.p-4(titulo="Método comparativo")
        h4 Método comparativo
        p Es una búsqueda de similitudes y comparaciones sistemáticas que sirve para la verificación de hipótesis para encontrar parentesco y se basa en la documentación de múltiples casos para realizar análisis comparativos. Básicamente consiste en poner dos o más elementos uno al lado del otro para encontrar diferencias y relaciones y así definir un caso o problema y poder actuar en el futuro.
        p El uso de la comparación es útil para comprender un tema, ya que puede conducir a nuevas hipótesis o teorías de crecimiento y mejora. Tiene varias etapas en las que destaca la observación, descripción, clasificación, comparación en sí y su conclusión.


    Separador
    #t_2_2.titulo-segundo.color-acento-botones(data-aos="fade-right")
      h2 2.2 Métodos de procesamiento de datos más conocidos

    .bloque-texto-a.color-acento-botones.p-3.mb-5(data-aos="fade-down-right") 
      .row.m-0.align-items-center.justify-content-between
        .col-lg-12
          .bloque-texto-a__texto.p-3
            p La recopilación, manipulación y procesamiento de datos recopilados para el uso requerido se conoce como procesamiento de datos, es una técnica realizada normalmente por una computadora; el proceso incluye la recuperación, transformación o clasificación de información. Sin embargo, el procesamiento de datos depende en gran medida de lo siguiente:

    .row.mb-5.align-self-stretch.justify-content-center(data-aos="fade-down-left") 
      .col-sm-6.col-lg-2.col-md-4.mb-4.mb-lg-0
        .tarjeta--boton.color-primario.text-white--hover.p-3(style="height:100%")
          .row.justify-content-center.mb-3
            .col-7
              figure
                img(src='@/assets/curso/temas/tema2/tema2-03.svg', alt='')
          .text-small.text-center #[strong El volumen de datos que deben procesarse]

      .col-sm-6.col-lg-2.col-md-4.mb-4.mb-lg-0
        .tarjeta--boton.color-acento-contenido.text-white--hover.p-3(style="height:100%")
          .row.justify-content-center.mb-3
            .col-7
              figure
                img(src='@/assets/curso/temas/tema2/tema2-04.svg', alt='')
          .text-small.text-center #[strong La complejidad de las operaciones de procesamiento de datos]

      .col-sm-6.col-lg-2.col-md-4.mb-4.mb-lg-0
        .tarjeta--boton.color-primario.p-3(style="height:100%")
          .row.justify-content-center.mb-3
            .col-7
              figure
                img(src='@/assets/curso/temas/tema2/tema2-05.svg', alt='')
          .text-small.text-center #[strong Capacidad y tecnología incorporada del sistema informático respectivo]

      .col-sm-6.col-lg-2.col-md-4.mb-4.mb-lg-0
        .tarjeta--boton.color-acento-contenido.text-white--hover.p-3(style="height:100%")
          .row.justify-content-center.mb-3
            .col-7
              figure
                img(src='@/assets/curso/temas/tema2/tema2-06.svg', alt='')
          .text-small.text-center #[strong Habilidades técnicas]
          
      .col-sm-6.col-lg-2.col-md-4.mb-4.mb-lg-0
        .tarjeta--boton.color-primario.p-3(style="height:100%")
          .row.justify-content-center.mb-3
            .col-7
              figure
                img(src='@/assets/curso/temas/tema2/tema2-07.svg', alt='')
          .text-small.text-center #[strong Limitaciones de tiempo]
  
    p.mb-5(data-aos="fade-right") Para completar la temática, se invita a realizar un recorrido por los diferentes métodos de procesamiento de datos:

    .row.justify-content-center.align-items-center.mb-5
      .col-12.col-md-8.mb-5.mb-lg-0(data-aos="fade-left")
        LineaTiempoD.color-primario
          .row(numero="1" titulo="Programación de usuario único")
            .col-12.mb-4.mb-md-0
              p.text-small Generalmente lo hace una sola persona para su uso personal. Esta técnica es adecuada, incluso, para oficinas pequeñas.
          .row(numero="2" titulo="Programación múltiple")
            .col-12.mb-4.mb-md-0
              p.text-small Esta técnica proporciona la posibilidad de almacenar y ejecutar más de un programa en la Unidad Central de Procesamiento (CPU) simultáneamente. Además, la técnica de programación múltiple aumenta la eficiencia de trabajo global del ordenador respectivo.
          .row(numero="3" titulo="Procesamiento en tiempo real")
            .col-12.mb-4.mb-md-0
              p.text-small Esta técnica facilita que el usuario tenga un contacto directo con el sistema informático, y el procesamiento de datos. Esta técnica también se conoce como el modo directo o la técnica del modo interactivo y se desarrolla exclusivamente para realizar una tarea. Es una especie de procesamiento en línea, que siempre permanece en ejecución.
          .row(numero="4" titulo="Procesamiento en línea")
            .col-12.mb-4.mb-md-0
              p.text-small Esta técnica facilita la entrada y ejecución de datos directamente; por lo tanto, no se almacena ni se acumula primero y luego se procesa. La técnica está desarrollada de tal manera que reduce los errores de entrada de datos, ya que valida los datos en varios puntos y también asegura que solo se ingresen los datos corregidos. Esta técnica se usa ampliamente para aplicaciones en línea.
          .row(numero="5" titulo="Procesamiento de tiempo compartido")
            .col-12.mb-4.mb-md-0
              p.text-small Esta es otra forma de procesamiento de datos en línea que facilita a varios usuarios compartir los recursos de un sistema informático en línea. Esta técnica se adopta cuando se necesitan resultados rápidamente. Además, como sugiere el nombre, este sistema se basa en el tiempo.
              .cajon.color-acento-botones.p-4.mb-2
                p.text-small.mb-0 A continuación, se presentan algunas de las principales ventajas del procesamiento de tiempo compartido:
              ul.lista-ul.mb-2
                li.mb-0.text-small
                  i.fas.fa-check(style="color:#25FFFF")
                  | Se pueden atender varios usuarios simultáneamente.
                li.mb-0.text-small
                  i.fas.fa-check(style="color:#25FFFF")
                  | Todos los usuarios tienen casi la misma cantidad de tiempo de procesamiento.
                li.mb-0.text-small
                  i.fas.fa-check(style="color:#25FFFF")
                  | Existe la posibilidad de interacción con los programas en ejecución.
          .row(numero="6" titulo="Procesamiento distribuido")
            .col-12.mb-4.mb-md-0
              p.text-small Esta es una técnica de procesamiento de datos especializada en la que varias computadoras (que están ubicadas de forma remota) permanecen interconectadas con una sola computadora host que forma una red de computadoras.
              .cajon.color-acento-botones.p-4.mb-2
                p.text-small Todos estos sistemas informáticos permanecen interconectados con una red de comunicaciones de alta velocidad. Esto facilita la comunicación entre computadoras, sin embargo, el sistema informático central mantiene la base de datos maestra y supervisa en consecuencia. 
      .col-12.col-md-4.mb-5.mb-lg-0.d-none.d-sm-none.d-md-block(data-aos="fade-right")
        figure
          img(src='@/assets/curso/temas/tema2/tema2-08.svg', alt='')  


    Separador
    #t_2_3.titulo-segundo.color-acento-botones(data-aos="fade-right")
      h2 2.3 Tipos de gráficas para el análisis de datos

    p.mb-5(data-aos="fade-right") Es necesario conocer las diferentes gráficas para realizar un análisis de datos; a saber:


    .tarjeta.tarjeta--azul.p-4.mb-5(data-aos="fade-down-left")
      SlyderA
        .row.justify-content-center.align-items-center
          .col-md-7.mb-4.mb-md-0
            h4 Tipos de gráficas para el análisis de datos
            p Las investigaciones muestran que creamos 2,5 trillones de bytes de datos todos los días. ¿Qué tipos de visualización de datos utiliza para digerir correctamente todos esos datos?
          .col-md-5
            div.formulas.mb-3
              figure
                img(src='@/assets/curso/temas/tema2/tema2-09.svg', alt='')
        .row.justify-content-center.align-items-center
          .col-md-5
            div.formulas.mb-3
              figure
                img(src='@/assets/curso/temas/tema2/tema2-10.svg', alt='')
          .col-md-7.mb-4.mb-md-0
            h4 Si bien esta es una cifra asombrosa,
            p Solo aumentará a medida que evoluciona Internet de las cosas. De hecho, el 90% de los datos del mundo se generaron solo en los últimos dos años. Con tanta información accesible al alcance de la mano, es importante comprender cómo organizarla en información analizable y procesable. 
        .row.justify-content-center.align-items-center
          .col-md-7.mb-4.mb-md-0
            h4 Sin embargo,
            p Si administra varios activos de contenido con múltiples fuentes de datos, puede resultar difícil determinar cómo dar forma a su estrategia de análisis. Aquí es donde ayuda conocerlos mejores tipos de visualización de datos. 
          .col-md-5
            div.formulas.mb-3
              figure
                img(src='@/assets/curso/temas/tema2/tema2-11.svg', alt='')
        .row.justify-content-center.align-items-center
          .col-md-5
            div.formulas.mb-3
              figure
                img(src='@/assets/curso/temas/tema2/tema2-12.svg', alt='')
          .col-md-7.mb-4.mb-md-0
            h4 La visualización de datos…
            p Es el proceso de convertir sus datos en representaciones gráficas que comunican relaciones lógicas y conducen a una toma de decisiones más informada.
        .row.justify-content-center.align-items-center
          .col-md-7.mb-4.mb-md-0
            h4 En resumen,
            p La visualización de datos es la representación de datos en un formato gráfico o pictórico. Permite a los tomadores de decisiones clave ver análisis complejos en un diseño visual, para que puedan identificar nuevos patrones o comprender conceptos desafiantes. 
          .col-md-5
            div.formulas.mb-3
              figure
                img(src='@/assets/curso/temas/tema2/tema2-13.svg', alt='')

    .row.justify-content-center.align-items-center.mb-5
      .col-12.mb-4.mb-md-0(data-aos="fade-down-right")
        .cajon.color-acento-botones.p-4.mb-2
          p Desde las métricas del sitio web y el desempeño del equipo de ventas hasta los resultados de las campañas de marketing y las tasas de adopción de productos, existe una variedad de puntos de datos que su organización necesita rastrear. Cuando se tienen las manos ocupadas haciendo malabares con varios proyectos a la vez, se necesita un método de informes rápido y eficaz que le permita expresar un punto claro. ¿Se sabe qué tipo de método de visualización de datos utilizar?
      
    p.mb-5(data-aos="fade-right") Algunos de los tipos más comunes de gráficos y gráficos de visualización de datos incluyen:

    .row.justify-content-center.align-items-center.mb-5(data-aos="fade-down-right")
      .col-12.col-md-6.mb-5.mb-lg-0.d-none.d-sm-none.d-md-block(data-aos="fade-right")
        figure
          img(src='@/assets/curso/temas/tema2/tema2-14.svg', alt='') 
      .col-md-6.mb-4.mb-md-0.px-md-4
        ul.lista-ul.mb-2
          li.mb-0
            i.fas.fa-check(style="color:#7125C8")
            | Gráfico de columnas.
          li.mb-0
            i.fas.fa-check(style="color:#7125C8")
            | Gráfico de barras.
          li.mb-0
            i.fas.fa-check(style="color:#7125C8")
            | Gráfico de barras apiladas.
          li.mb-0
            i.fas.fa-check(style="color:#7125C8")
            | Gráfico de columnas apiladas.
          li.mb-0
            i.fas.fa-check(style="color:#7125C8")
            | Gráfico de área.
          li.mb-0
            i.fas.fa-check(style="color:#7125C8")
            | Gráfico de doble eje.
          li.mb-0
            i.fas.fa-check(style="color:#7125C8")
            | Gráfico de líneas.
          li.mb-0
            i.fas.fa-check(style="color:#7125C8")
            | Gráfico de Mekko.
          li.mb-0
            i.fas.fa-check(style="color:#7125C8")
            | Gráfico circular.
          li.mb-0
            i.fas.fa-check(style="color:#7125C8")
            | Gráfico de cascada.
          li.mb-0
            i.fas.fa-check(style="color:#7125C8")
            | Gráfico de burbujas.
          li.mb-0
            i.fas.fa-check(style="color:#7125C8")
            | Gráfico de diagrama de dispersión.
          li.mb-0
            i.fas.fa-check(style="color:#7125C8")
            | Gráfico de viñetas.
          li.mb-0
            i.fas.fa-check(style="color:#7125C8")
            | Gráfico de embudo.
          li.mb-0
            i.fas.fa-check(style="color:#7125C8")
            | Mapa de calor.

    .bloque-texto-a.color-acento-botones.p-3.mb-5(data-aos="fade-down-right") 
      .row.m-0.align-items-center.justify-content-between
        .col-lg-12
          .bloque-texto-a__texto.p-3
            p Si bien todos sirven para agilizar y mejorar la interpretación de datos, no todos son apropiados para el mismo trabajo. Elegir la ayuda visual adecuada es la clave para evitar la confusión del usuario y asegurarse de que su análisis sea preciso. Ahora se analizarán 10 de estos 15 tipos de tablas y gráficos.


    .row.justify-content-center.align-items-center.mb-5
      .col-12(data-aos="fade-right")
        ul.lista-ul.mb-2
          li.mb-0
            i.fas.fa-play(style="color:#25FFFF")
            | Explicación de 10 tipos de visualización de datos

    p.mb-5(data-aos="fade-down-right")  Existen innumerables tipos diferentes de tablas, gráficos y otras técnicas de visualización que pueden ayudar a los analistas a representar y transmitir datos importantes. Echemos un vistazo a 10 de los más comunes:









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
