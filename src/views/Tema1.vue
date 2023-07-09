<template lang="pug">
.curso-main-container.pb-3.tema1
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-botones
      .titulo-principal__numero
        span 1
      h1 Probabilidad y estadística

    p.mb-5(data-aos="fade-down") La estadística forma parte del comportamiento histórico de todos los fenómenos naturales que ocurren en el mundo:
      

    .bloque-texto-g.color-primario.p-3.p-sm-4.p-md-5.mb-5(data-aos="fade-down-right")
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/temas/tema1/tema1-01.png')})`}"
      )
      .bloque-texto-g__texto.p-4
        p.mb-0 El procesamiento y el análisis de datos conllevan, anticipadamente, procedimientos de recopilación, limpieza y clasificación de estos, para luego llevar a cabo la transformación y el modelado de datos, bajo diferentes métodos tanto cualitativos como cuantitativos con el objetivo de descubrir la información requerida. 
          br
          br
          | Los resultados así obtenidos se comunican, sugiriendo conclusiones y apoyando la toma de decisiones. La visualización de datos se utiliza, a veces, para representar los datos para facilitar el descubrimiento de patrones útiles en los datos. Los términos Modelado de datos y Análisis de datos significan lo mismo. 

  
    .row.justify-content-center.align-items-center.mb-5
      .col-12(data-aos="fade-right")
        ul.lista-ul.mb-2
          li.mb-0
            i.fas.fa-play(style="color:#25FFFF")
            | Moda, media, mediana y desviación típica, estudio de variables continuas.

    p.mb-5(data-aos="fade-down") La media, la mediana y la moda son tres tipos de "promedios". Hay muchos "promedios" en estadística, pero estos son los tres más comunes, y ciertamente son los tres más utilizados al momento de llevar a cabo aplicaciones y procesos estadísticos.


    AcordionA.mb-5(tipo="a" clase-tarjeta="tarjeta tarjeta--azul")
      .row(titulo="Media")
        .col-md-12.mb-4.mb-md-0
          p La media resume un conjunto de datos completo con un solo número que representa el punto central de los datos o el valor típico. También se conoce como promedio aritmético y es una de varias medidas de tendencia central.
          p Encontrar la media es muy sencillo. Simplemente sume todos los valores y divídalos por el número de observaciones; la fórmula está a continuación.
          div.formulas.mb-3
            img(src='@/assets/curso/temas/tema1/tema1-02.svg', alt='')

          p Por ejemplo, si las alturas de cinco personas son 48, 51, 52, 54 y 56 pulgadas, su altura promedio es de 52,2 pulgadas.
          p.text-center 48 + 51 + 52 + 54 + 56/5 = 52,2
      .row(titulo="Idealmente")
        .col-md-12.mb-4.mb-md-0
          p La media indica la región donde caen la mayoría de los valores en una distribución. Los estadísticos se refieren a ella como la ubicación central de una distribución. Puede pensar en ello como la tendencia de los datos a agruparse en torno a un valor medio. Sin embargo, la media no siempre encuentra el centro de los datos. Es sensible a datos sesgados y valores extremos. Por ejemplo, cuando los datos están sesgados, pueden fallar.

      .row(titulo="Media aritmética (AM)")
        .col-md-12.mb-4.mb-md-0
          p La media aritmética (o simplemente media) de una lista de números, es la suma de todos los números divididos por el número de números. De manera similar, la media de una muestra x1, x2, ..., xn, generalmente denotado por  es la suma de los valores muestreados dividida por el número de elementos de la muestra:
          div.formulas.mb-3
            img(src='@/assets/curso/temas/tema1/tema1-03.svg', alt='')
          p Por ejemplo, la media aritmética de cinco valores: 4, 36, 45, 50, 75 es:
          div.formulas.mb-3
            img(src='@/assets/curso/temas/tema1/tema1-04.svg', alt='')

      .row(titulo="Media geométrica (GM)")
        .col-md-12.mb-4.mb-md-0
          p La media geométrica es una media útil para conjuntos de números positivos, que se interpretan según su producto (como es el caso de las tasas de crecimiento) y no su suma (como es el caso de la media aritmética):
          div.formulas.mb-3
            img(src='@/assets/curso/temas/tema1/tema1-05.svg', alt='')
          p Por ejemplo, la media geométrica de cinco valores: 4, 36, 45, 50, 75 es:
          div.formulas.mb-3
            img(src='@/assets/curso/temas/tema1/tema1-06.svg', alt='')

      .row(titulo="Media armónica (HM)")
        .col-md-12.mb-4.mb-md-0
          p La media armónica es un promedio que es útil para conjuntos de números que se definen en relación con alguna unidad, como en el caso de la velocidad (es decir, distancia por unidad de tiempo):
          div.formulas.mb-3
            img(src='@/assets/curso/temas/tema1/tema1-07.svg', alt='')
          p Por ejemplo, la media armónica de los cinco valores: 4, 36, 45, 50, 75 es:
          div.formulas.mb-3
            img(src='@/assets/curso/temas/tema1/tema1-08.svg', alt='')

      .row(titulo="Relación entre AM, GM y HM")
        .col-md-12.mb-4.mb-md-0
          p AM, GM y HM satisfacen estas desigualdades:
          div.formulas.mb-3
            img(src='@/assets/curso/temas/tema1/tema1-09.svg', alt='')
          p La igualdad se mantiene si todos los elementos de la muestra dada son iguales.


    Separador
    #t_1_1.titulo-segundo.color-acento-botones(data-aos="fade-right")
      h2 1.1 Moda, media, mediana y desviación típica, estudio de variables continuas
          
    p.mb-4(data-aos="fade-down") A continuación, se definirá la moda, media, mediana y desviación típica, así como el estudio de variables continuas.


    .row.justify-content-center.align-items-center.mb-3
      .col-12(data-aos="fade-right")
        ul.lista-ul.mb-2
          li.mb-0
            i.fas.fa-play(style="color:#25FFFF")
            | Mediana

    p.mb-5(data-aos="fade-down") La mediana es la observación intermedia en un conjunto de datos. Para contextualizar qué significa, se calcula la mediana de un conjunto de datos de muestra sobre el peso infantil, así:


    .row.mb-5.align-self-stretch.justify-content-center
      .col-12.col-lg-10.mb-5.mb-lg-0(data-aos="fade-right")
        figure
          img(src='@/assets/curso/temas/tema1/tema1-10.svg', alt='')  

          
    .row.mb-5.align-self-stretch.justify-content-center
      .col-12.col-md-4.mb-5.mb-lg-0(data-aos="fade-right")
        figure
          img(src='@/assets/curso/temas/tema1/tema1-11.png', alt='')  
      .col-12.col-md-8.mb-5.mb-lg-0(data-aos="fade-left")
        div.formulas.mb-3
          img(src='@/assets/curso/temas/tema1/tema1-12.svg', alt='')
        p En el conjunto de datos anterior, ¿cuál es la observación intermedia? Bueno, antes que pueda resolver esto, tenemos que ordenar correctamente las observaciones de una manera lógica para que tengan sentido. Los ordenaremos de menor a mayor, como se muestra a continuación:
        div.formulas.mb-3
          img(src='@/assets/curso/temas/tema1/tema1-13.svg', alt='')
        .cajon.color-acento-botones.p-4.mb-2
          p.mb-0 Ahora que nuestros datos están ordenados correctamente, podemos encontrar la observación intermedia.
    

          
    .row.justify-content-center.align-items-center.mb-5
      .col-12.col-md-8.mb-5.mb-lg-0(data-aos="fade-left")
        LineaTiempoD.color-primario
          .row(numero="1" titulo="Número impar de observaciones")
            .col-12.mb-4.mb-md-0
              p.text-small En un conjunto de datos que tiene un número impar de observaciones, esto es muy fácil; es simplemente el número justo en el medio (el que tiene el mismo número de observaciones arriba y abajo).
              div.formulas.mb-3
                img(src='@/assets/curso/temas/tema1/tema1-16.svg', alt='')
              div.formulas.mb-3
                img(src='@/assets/curso/temas/tema1/tema1-15.svg', alt='')
          .row(numero="2" titulo="Número par de observaciones")
            .col-12.mb-4.mb-md-0
              p.text-small Sin embargo, en nuestro caso tenemos 12 observaciones, que es un número par. Esto significa que debemos tomar las dos observaciones del centro y promediarlas. En este caso, las dos observaciones en el medio son 42 y 49. Cuando tomamos el promedio de estos dos números (recuerde, para hacer un promedio, sume los dos números (42 + 49 = 91) y divida ese número por la cuenta, que en este caso es 2), obtenemos 45,5. Entonces nuestra mediana es 45,5.
              div.formulas.mb-3
                img(src='@/assets/curso/temas/tema1/tema1-17.svg', alt='')
              div.formulas.mb-3
                img(src='@/assets/curso/temas/tema1/tema1-18.svg', alt='')
          .row(numero="3" titulo="Entonces, ¿qué significa la mediana?")
            .col-12.mb-4.mb-md-0
              p.text-small Bueno, al igual que la media, proporciona una medida útil del centro de nuestro conjunto de datos. Ahora sabemos que el peso medio de los niños de nuestro grupo es de 45,5. Pero también es útil comparar la mediana con la media. 45,5 es obviamente menor que la media, que fue 53,5. A menudo, la media y la mediana serán las mismas en un conjunto de datos, pero a veces son diferentes, como en nuestro caso. Cuando la media y la mediana son iguales, se sabe que el conjunto de datos está " distribuido normalmente ". Cuando la media y la mediana son diferentes, sabe que los datos están " sesgados " de alguna manera.
              div.formulas.mb-3
                img(src='@/assets/curso/temas/tema1/tema1-19.svg', alt='')
          .row(numero="4" titulo="¿Qué se quiere decir con sesgado? ")
            .col-12.mb-4.mb-md-0
              p.text-small Bueno, a diferencia de la media, que era un cálculo matemático que usaba todas las observaciones del conjunto de datos, la mediana ignora lo que dicen los números y solo usa la observación del medio. ¿Cuál es la correcta? Ambos lo son. Ninguno es necesariamente mejor que el otro. Entonces, ¿por qué usar una mediana? Bueno, hay ciertos tipos de datos en los que le preocupará el sesgo. El sesgo es cuando la media sube o baja por encima de la mediana debido a valores muy altos o muy bajos.
              div.formulas.mb-3
                img(src='@/assets/curso/temas/tema1/tema1-20.svg', alt='')
      .col-12.col-md-4.mb-5.mb-lg-0.d-none.d-sm-none.d-md-block(data-aos="fade-right")
        figure
          img(src='@/assets/curso/temas/tema1/tema1-14.svg', alt='')  

    .row.justify-content-center.align-items-center.mb-3
      .col-12(data-aos="fade-right")
        ul.lista-ul.mb-2
          li.mb-0
            i.fas.fa-play(style="color:#25FFFF")
            | Moda

    p.mb-5(data-aos="fade-down") Es el valor que aparece con mayor frecuencia en un conjunto de valores de datos. Si X es una variable aleatoria discreta, la moda es el valor x (es decir, X = x) en el que la función de masa de probabilidad toma su valor máximo. En otras palabras, es el valor que es más probable que se muestree. De esta manera:

    .bloque-texto-g.color-primario.p-3.p-sm-4.p-md-5.mb-5(data-aos="fade-down-right")
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/temas/tema1/tema1-21.png')})`}"
      )
      .bloque-texto-g__texto.p-4
        p.mb-0 Al igual que la media y la mediana estadísticas, la moda es una forma de expresar, en un número (normalmente) único, información importante sobre una variable aleatoria o una población. El valor numérico de la moda es el mismo que el de la media y la mediana en una distribución normal y puede ser muy diferente en distribuciones muy asimétricas. La moda no es necesariamente única para una distribución discreta dada, ya que la función de masa de probabilidad puede tomar el mismo valor máximo en varios puntos x1 x2, etc. El caso más extremo ocurre en distribuciones uniformes, donde todos los valores ocurren con la misma frecuencia.

    .tarjeta.tarjeta--azul.p-4.mb-5(data-aos="fade-down-left")
      SlyderA
        .row.justify-content-center.align-items-center
          .col-md-6.mb-4.mb-md-0
            p Cuando la función de densidad de probabilidad de una distribución continua tiene múltiples máximos locales, es común referirse a todos los máximos locales como modos de la distribución. Esta distribución continua se denomina multimodal (en contraposición a unimodal). Un modo de una distribución de probabilidad continua se considera a menudo como cualquier valor x en el que su función de densidad de probabilidad tiene un valor máximo localmente, por lo que cualquier pico es un modo.
          .col-md-6
            figure
              img(src='@/assets/curso/temas/tema1/tema1-22.svg', alt='')
        .row.justify-content-center.align-items-center
          .col-md-6
            figure
              img(src='@/assets/curso/temas/tema1/tema1-23.svg', alt='')
          .col-md-6.mb-4.mb-md-0
            p En distribuciones unimodales simétricas, como la distribución normal, la media (si está definida), la mediana y la moda coinciden. Para las muestras, si se sabe que se extraen de una distribución unimodal simétrica, la media de la muestra se puede utilizar como una estimación de la moda poblacional.
        .row.justify-content-center.align-items-center
          .col-md-6.mb-4.mb-md-0
            p #[strong Moda de una muestra:] La moda de una muestra es el elemento que aparece con mayor frecuencia en la colección. Por ejemplo, la moda de la muestra [1, 3, 6, 6, 6, 6, 7, 7, 12, 12, 17] es 6. Dada la lista de datos [1, 1, 2, 4, 4] su modo no es único. En tal caso, se dice que un conjunto de datos es bimodal, mientras que un conjunto con más de dos modos puede describirse como multimodal.
          .col-md-6
            figure
              img(src='@/assets/curso/temas/tema1/tema1-24.svg', alt='')
        .row.justify-content-center.align-items-center
          .col-md-6
            figure
              img(src='@/assets/curso/temas/tema1/tema1-25.svg', alt='')
          .col-md-6.mb-4.mb-md-0
            p Para una muestra de una distribución continua, como [0.935 ..., 1.211 ..., 2.430 ..., 3.668 ..., 3.874 ...], el concepto es inutilizable en su forma bruta, ya que no hay dos valores será exactamente el mismo, por lo que cada valor ocurrirá exactamente una vez. Para estimar la moda de la distribución subyacente, la práctica habitual es discretizar los datos asignando valores de frecuencia a intervalos de igual distancia, como para hacer un histograma, reemplazando efectivamente los valores por los puntos medios de los intervalos a los que están asignados. El modo es entonces el valor en el que el histograma alcanza su pico. 
        .row.justify-content-center.align-items-center
          .col-md-6.mb-4.mb-md-0
            p Para muestras pequeñas o medianas, el resultado de este procedimiento es sensible a la elección del ancho del intervalo si se elige demasiado estrecho o demasiado ancho; por lo general, se debe tener una fracción considerable de los datos concentrada en un número relativamente pequeño de intervalos (5 a 10), mientras que la fracción de los datos que quedan fuera de estos intervalos también es considerable. Un enfoque alternativo es la estimación de la densidad del núcleo, que esencialmente difumina las muestras puntuales para producir una estimación continua de la función de densidad de probabilidad que puede proporcionar una estimación del modo.
          .col-md-6
            figure
              img(src='@/assets/curso/temas/tema1/tema1-26.svg', alt='')
        

    .row.justify-content-center.align-items-center.mb-3
      .col-12(data-aos="fade-right")
        ul.lista-ul.mb-2
          li.mb-0
            i.fas.fa-play(style="color:#25FFFF")
            | Comparación de media, mediana y moda

    p.mb-4(data-aos="fade-right") A diferencia de la media y la mediana, el concepto de moda también tiene sentido para los “datos nominales” (es decir, que no constan de valores numéricos en el caso de la media, ni siquiera de valores ordenados en el caso de la mediana). Por ejemplo, tomando una muestra de apellidos coreanos, uno podría encontrar que “Kim” aparece con más frecuencia que cualquier otro nombre. Entonces “Kim” sería la moda de la muestra. En cualquier sistema de votación donde una pluralidad determina la victoria, un único valor modal determinar al vencedor, mientras que un resultado multimodal requeriría algún procedimiento de desempate.  

    .row.justify-content-center.align-items-center.mb-4
      .col-12.col-lg-10(data-aos="fade-right")
        .titulo-sexto.color-acento-botones
          p.titulo.pb-0.mb-0 #[b Figura 1.] #[i Diferencias entre mediana, media y moda] 
          figure
            img(src='@/assets/curso/temas/tema1/tema1-27.svg', alt='')  
            figcaption Nota. Tomada de https://www.nobbot.com/educacion/no-te-quedes-en-la-media-y-aprende-a-calcular-la-mediana-asi-se-hace/
        
    .row.justify-content-center.align-items-center.mb-4
      .col-12(data-aos="fade-down-right")
        .cajon.color-acento-botones.p-4.mb-4
          p A diferencia de la mediana, el concepto de moda tiene sentido para cualquier variable aleatoria que asuma valores de un espacio vectorial, incluidos los números reales (un espacio vectorial unidimensional) y los enteros (que pueden considerarse incrustados en los reales). Por ejemplo, una distribución de puntos en el plano normalmente tendrá una media y una moda, pero el concepto de mediana no se aplica. La mediana tiene sentido cuando existe un orden lineal en los valores posibles.


    .tabla-b.color-acento-contenido.mb-5
      .tabla-b__header
        h5.mb-0 Las generalizaciones del concepto de mediana a espacios de dimensiones superiores son la mediana geométrica y el punto central.
      table
        thead
          tr(style="background-color: #7125C8;color: #FFFFFF;")
            th Tipo
            th(style="width:40%") Descripción
            th Ejemplo
            th(style="width:15%") Resultado
        tbody
          tr
            th Media Aritmética
            td Suma de valores de un conjunto de datos dividida por el número de elementos o cantidad de números.
            td (1 + 2 + 2 + 3 + 4 + 7 + 9) / 7
            td 4
          tr
            th Mediana
            td Valor medio o central que separa las mitades menor y mayor de un conjunto de elementos numéricos.
            td 1, 2, 2, 3, 4, 7, 9
            td 3
          tr
            th Moda
            td Valor más frecuente en un conjunto de elementos numéricos.
            td 1, 2, 2, 3, 4, 7, 9
            td 2

    hr

    .row.justify-content-center.align-items-center.mb-3
      .col-12(data-aos="fade-right")
        ul.lista-ul.mb-2
          li.mb-0
            i.fas.fa-play(style="color:#25FFFF")
            | Varianza y desviación típica o estándar

    .bloque-texto-g.color-primario.p-3.p-sm-4.p-md-5.mb-5(data-aos="fade-down-right")
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/temas/tema1/tema1-28.png')})`}"
      )
      .bloque-texto-g__texto.p-4
        p.mb-0 La varianza es la expectativa de la desviación al cuadrado de una variable aleatoria de su media poblacional o muestral. La varianza es una medida de dispersión, lo que significa que es una medida de qué tan lejos se separa un conjunto de números de su valor promedio y se define de manera detallada así:


    .row.justify-content-center.align-items-center.mb-5
      .col-12.col-md-8.mb-5.mb-lg-0(data-aos="fade-left")
        LineaTiempoD.color-primario
          .row(numero="1" titulo="Varianza y desviación típica o estándar")
            .col-12.mb-4.mb-md-0
              p.text-small La varianza es la expectativa de la desviación al cuadrado de una variable aleatoria de su media poblacional o muestral. La varianza es una medida de dispersión, lo que significa que es una medida de qué tan lejos se separa un conjunto de números de su valor promedio. La varianza tiene un papel central en la estadística, donde algunas ideas que la usan incluyen estadística descriptiva, inferencia estadística, prueba de hipótesis y muestreo de Monte Carlo. 
              div.formulas.mb-3
                img(src='@/assets/curso/temas/tema1/tema1-30.svg', alt='')
          .row(numero="2" titulo="La varianza…")
            .col-12.mb-4.mb-md-0
              p.text-small Es una herramienta importante en las ciencias, donde el análisis estadístico de datos es común. La varianza es el cuadrado de la desviación estándar, el segundo momento central de una distribución y la covarianza de la variable aleatoria consigo misma, y a menudo se representa por #[strong #[em σ2, s2, Var(x) o V(x)].]
              div.formulas.mb-3
                img(src='@/assets/curso/temas/tema1/tema1-31.svg', alt='')
          .row(numero="3" titulo="Una ventaja de la varianza como medida de dispersión es…")
            .col-12.mb-4.mb-md-0
              p.text-small Que es más susceptible de manipulación algebraica que otras medidas de dispersión, como la desviación absoluta esperada; por ejemplo, la varianza de una suma de variables aleatorias no correlacionadas es igual a la suma de sus varianzas. Una desventaja de la varianza para aplicaciones prácticas es que, a diferencia de la desviación estándar, sus unidades difieren de la variable aleatoria, por lo que la desviación estándar se informa más comúnmente como una medida de dispersión una vez finalizado el cálculo.
              h6.text-center Medidas de dispersión
              div.formulas.mb-3
                img(src='@/assets/curso/temas/tema1/tema1-32.svg', alt='')
          .row(numero="4" titulo="La desviación estándar en las estadísticas ")
            .col-12.mb-4.mb-md-0
              p.text-small Está típicamente denotada por σ, es una medida de variación o dispersión (se refiere al grado de estiramiento o compresión de una distribución) entre valores en un conjunto de datos. Cuanto menor es la desviación estándar, más cerca tienden a estar los puntos de datos de la media (o valor esperado), μ. Por el contrario, una desviación estándar más alta indica una gama más amplia de valores. De manera similar a otros conceptos matemáticos y estadísticos, existen muchas situaciones diferentes en las que se puede usar la desviación estándar y, por lo tanto, muchas ecuaciones diferentes. 
              div.formulas.mb-3
                img(src='@/assets/curso/temas/tema1/tema1-33.svg', alt='')
              h6.text-center Además de expresar la variabilidad de la población
              p.text-small La desviación estándar también se usa a menudo para medir resultados estadísticos como el margen de error. Cuando se usa de esta manera, la desviación estándar a menudo se denomina error estándar de la media o error estándar de la estimación con respecto a una media.  
          .row(numero="5" titulo="Desviación estándar de población ")
            .col-12.mb-4.mb-md-0
              p.text-small La desviación estándar de la población, la definición estándar de σ se usa cuando se puede medir una población completa y es la raíz cuadrada de la varianza de un conjunto de datos dado.
              p.text-small #[strong En los casos en que se pueda muestrear a cada miembro de una población], se puede utilizar la siguiente ecuación para encontrar la desviación estándar de toda la población:
              div.formulas.mb-3
                img(src='@/assets/curso/temas/tema1/tema1-34.svg', alt='')
              h6 Donde:
              ul.lista-ul.mb-2
                li.mb-0.text-small
                  i.lista-ul__vineta(style="color:#AD84FF")
                  | #[strong xi] es un valor individual
                li.mb-0.text-small
                  i.lista-ul__vineta(style="color:#AD84FF")
                  | #[strong μ] es el valor medio / esperado
                li.mb-0.text-small
                  i.lista-ul__vineta(style="color:#AD84FF")
                  | #[strong N] es el número total de valores
              p.text-small #[strong Para aquellos] que no están familiarizados con la notación de suma, la ecuación anterior puede parecer desalentadora, pero cuando se aborda a través de sus componentes individuales, esta suma no es particularmente complicada. 
              h6 Para entender más…
              p.text-small El i = 1 en la suma indica el índice inicial, es decir, para el conjunto de datos 1, 3, 4, 7, 8, i = 1 sería 1, i = 2 sería 3, y así sucesivamente. Por lo tanto, la notación de suma simplemente significa realizar la operación de (xi – μ)2 en cada valor a través de N, que en este caso es 5 ya que hay 5 valores en este conjunto de datos.
              h6 Ejemplo:
              ul.lista-ul.mb-2
                li.mb-0.text-small
                  i.lista-ul__vineta(style="color:#AD84FF")
                  | #[strong μ] = (1 + 3 + 4 + 7 + 8) / 5 = 4,6.  
                li.mb-0.text-small
                  i.lista-ul__vineta(style="color:#AD84FF")
                  | #[strong σ] = √ [(1 - 4,6)2 + (3 - 4,6)2 + … + (8 - 4,6)2] / 5.  
                li.mb-0.text-small
                  i.lista-ul__vineta(style="color:#AD84FF")
                  | #[strong σ] = √ (12,96 + 2,56 + 0,36 + 5,76 + 11,56) / 5 = 2,577.
          .row(numero="6" titulo="Desviación estándar de la muestra")
            .col-12.mb-4.mb-md-0
              p.text-small En muchos casos, no es posible muestrear a todos los miembros dentro de una población, lo que requiere que se modifique la ecuación anterior para que la desviación estándar se pueda medir a través de una muestra aleatoria de la población que se está estudiando. Un estimador común para σ es la desviación estándar de la muestra, normalmente denotada por s. Vale la pena señalar que existen muchas ecuaciones diferentes para calcular la desviación estándar de la muestra, ya que, a diferencia de la media de la muestra, la desviación estándar de la muestra no tiene un estimador único que sea insesgado, eficiente y con una probabilidad máxima.
              div.formulas.mb-3
                img(src='@/assets/curso/temas/tema1/tema1-35.svg', alt='')
              .cajon.color-acento-botones.p-4.mb-4
                p.text-small #[strong La ecuación proporcionada a continuación es] la “desviación estándar de la muestra corregida”. Es una versión corregida de la ecuación obtenida al modificar la ecuación de desviación estándar de la población utilizando el tamaño de la muestra como el tamaño de la población, lo que elimina parte del sesgo de la ecuación. Sin embargo, la estimación imparcial de la desviación estándar es muy complicada y varía según la distribución.
              div.formulas.mb-3
                img(src='@/assets/curso/temas/tema1/tema1-36.svg', alt='')
              p.text-small #[strong Como tal] la “desviación estándar de la muestra corregida” es el estimador más comúnmente utilizado para la desviación estándar de la población, y generalmente se la denomina simplemente “desviación estándar de la muestra”. Es una estimación mucho mejor que su versión sin corregir, pero aún tiene un sesgo significativo para tamaños de muestra pequeños (N <10).
              h6 Donde:
              ul.lista-ul.mb-2
                li.mb-0.text-small
                  i.lista-ul__vineta(style="color:#AD84FF")
                  | #[strong xi] es un valor de la muestra
                li.mb-0.text-small
                  i.lista-ul__vineta(style="color:#AD84FF")
                  | #[strong x̄] es la media de la muestra
                li.mb-0.text-small
                  i.lista-ul__vineta(style="color:#AD84FF")
                  | #[strong N] es el tamaño de la muestra
      .col-12.col-md-4.mb-5.mb-lg-0.d-none.d-sm-none.d-md-block(data-aos="fade-right") 
        figure
          img(src='@/assets/curso/temas/tema1/tema1-29.png', alt='')  

    .row.justify-content-center.align-items-center.mb-4
      .col-12(data-aos="fade-down-right")
        .cajon.color-acento-botones.p-4.mb-4
          p La desviación estándar se usa ampliamente en entornos experimentales e industriales para probar modelos con datos del mundo real; un ejemplo de esto es el control de calidad de algunos productos. A continuación, se informa acerca de sus usos:


    .row.justify-content-center.align-items-center.mb-3
      .col-12(data-aos="fade-right")
        ul.lista-ul.mb-2
          li.mb-0
            i.fas.fa-play(style="color:#25FFFF")
            | Aplicaciones de la desviación estándar 

    .row.mb-5.justify-content-center.align-items-center
      .col-12.col-md-4.mb-5.mb-lg-0(data-aos="fade-right")
        figure
          img(src='@/assets/curso/temas/tema1/tema1-37.svg', alt='')  
      .col-12.col-md-8.mb-5.mb-lg-0(data-aos="fade-left")
        p La desviación estándar se usa ampliamente en entornos experimentales e industriales para probar modelos con datos del mundo real. Un ejemplo de esto en aplicaciones industriales es el control de calidad de algunos productos. La desviación estándar se puede utilizar para calcular un valor mínimo y máximo dentro del cual algún aspecto del producto debería caer en un alto porcentaje del tiempo. En los casos en que los valores estén fuera del rango calculado, puede ser necesario realizar cambios en el proceso de producción para garantizar el control de calidad.
        .cajon.color-acento-botones.p-4.mb-2
          p.mb-0 La desviación estándar también se usa en el clima para determinar las diferencias en el clima regional. Imagínese dos ciudades, una en la costa y otra tierra adentro, que tienen la misma temperatura media de 75 ° F. Si bien esto puede generar la creencia de que las temperaturas de estas dos ciudades son prácticamente las mismas, la realidad podría enmascararse si solo se aborda la media y se ignora la desviación estándar. 
    

    p.mb-3(data-aos="fade-right") Las ciudades costeras tienden a tener temperaturas mucho más estables debido a la regulación de grandes masas de agua, ya que el agua tiene una mayor capacidad calorífica que la tierra; esencialmente, esto hace que el agua sea mucho menos susceptible a los cambios de temperatura, y las áreas costeras permanecen más cálidas en invierno y más frescas en verano debido a la cantidad de energía requerida para cambiar la temperatura del agua. 
    p.mb-5(data-aos="fade-right") Otra área en la que se usa ampliamente la desviación estándar es la de las finanzas, donde a menudo se usa para medir el riesgo asociado en las fluctuaciones de precios de algún activo o cartera de activos.

    .row.justify-content-center.align-items-center.mb-4
      .col-md-11.col-12(data-aos="fade-down")
        .tarjeta-avatar-b.mb-4
          .color-secundario.pasos-custom.px-5
            .pasos-a__circle
              .h2.text-white 1
          .tarjeta.tarjeta--custom
            .p-4
              p.mb-0 El uso de la desviación estándar en estos casos proporciona una estimación de la incertidumbre de los rendimientos futuros de una inversión determinada.
      .col-md-11.col-12(data-aos="fade-down")
        .tarjeta-avatar-b.mb-4
          .color-secundario.pasos-custom.px-5
            .pasos-a__circle
              .h2.text-white 2
          .tarjeta.tarjeta--custom
            .p-4
              p.mb-0 Por ejemplo, al comparar la acción A que tiene un rendimiento promedio del 7% con una desviación estándar del 10% contra la acción B, que tiene el mismo rendimiento promedio pero una desviación estándar del 50%, la primera acción sería claramente la opción más segura. dado que la desviación estándar de la acción B es significativamente mayor, para el mismo rendimiento exacto.
      .col-md-11.col-12(data-aos="fade-down")
        .tarjeta-avatar-b.mb-4
          .color-secundario.pasos-custom.px-5
            .pasos-a__circle
              .h2.text-white 3
          .tarjeta.tarjeta--custom
            .p-4
              p.mb-0 Eso no quiere decir que la acción A sea definitivamente una mejor opción de inversión en este escenario, ya que la desviación estándar puede sesgar la media en cualquier dirección.
      .col-md-11.col-12(data-aos="fade-down")
        .tarjeta-avatar-b.mb-4
          .color-secundario.pasos-custom.px-5
            .pasos-a__circle
              .h2.text-white 4
          .tarjeta.tarjeta--custom
            .p-4
              p.mb-0 Estos son solo algunos ejemplos de cómo se puede usar la desviación estándar, pero existen muchos más. Generalmente, calcular la desviación estándar es valioso en cualquier momento que se desee saber qué tan lejos de la media puede estar un valor típico de una distribución.

    .row.justify-content-center.align-items-center.mb-3
      .col-12(data-aos="fade-right")
        ul.lista-ul.mb-2
          li.mb-0
            i.fas.fa-play(style="color:#25FFFF")
            | Estudio de variables continuas

    p.mb-5(data-aos="fade-right") Una variable continua es un tipo específico de variable cuantitativa que se utiliza en estadística para describir datos que se pueden medir de alguna manera. Si sus datos tratan de medir la altura, el peso o el tiempo, entonces tiene una variable continua.

    .row.mb-5.justify-content-center.align-items-center
      .col-12.col-md-4.mb-5.mb-lg-0(data-aos="fade-right")
        figure
          img(src='@/assets/curso/temas/tema1/tema1-38.svg', alt='')  
      .col-12.col-md-8.mb-5.mb-lg-0(data-aos="fade-left")
        .cajon.color-acento-botones.p-4.mb-2
          p.mb-0 Definamos más un par de términos utilizados en nuestra definición. Una variable en estadística no es lo mismo que una variable en álgebra. En estadística, una variable es algo que nos da datos. Algunos ejemplos de variables en las estadísticas pueden incluir edad, color de ojos, altura, número de hermanos, sexo o número de mascotas. Nuestra definición de variable continua también menciona que es cuantitativa. Los datos cuantitativos involucran cantidades o números. En los ejemplos de variables enumerados anteriormente, su edad, altura, número de hermanos y número de mascotas son todas variables cuantitativas.

    
    .tarjeta--container.row.mb-5
      .col-md.tarjeta.color-acento-botones.px-5.py-3
        .row.justify-content-center.mb-4
          .col-6
            div.formulas.mb-3
              img(src='@/assets/curso/temas/tema1/tema1-39.svg', alt='')
        p La definición también menciona que los datos se pueden medir de alguna manera. Para comprender esto, debe comprender las variables discretas. Los datos se consideran discretos si son un recuento. Cuando contamos cosas, usamos números enteros como 0, 1, 2 y 3. Mi ejemplo favorito de una variable discreta es cuántos huevos pone una gallina. Cada día una gallina puede o no poner un huevo, pero hay dos cosas que nunca pueden suceder. Nunca puede haber un número negativo de huevos, y nunca puede haber una fracción o una porción de un huevo.
      .col-md.tarjeta.color-acento-contenido.px-5.py-3
        .row.justify-content-center.mb-4
          .col-6
            div.formulas.mb-3
              img(src='@/assets/curso/temas/tema1/tema1-40.svg', alt='')
        p Las variables continuas son variables que miden algo. Un buen ejemplo de variable continua es cuántos galones de leche da una vaca. Hasta donde se sabe, las vacas no saben cómo dejar de producir o dar leche después de exactamente 4 galones. Bessie puede dar 4,17 galones el lunes, 3,89 galones el martes y 4,2 galones el miércoles. Observe que las variables continuas nos permiten tener decimales o fracciones.





    








</template>

<script>
export default {
  name: 'Tema1',
  components: {},
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
