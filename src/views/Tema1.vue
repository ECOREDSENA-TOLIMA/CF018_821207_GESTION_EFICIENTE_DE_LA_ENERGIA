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
        p.mb-0 La probabilidad y la estadística son las ramas de las matemáticas relacionadas con las leyes que gobiernan los eventos aleatorios, incluida la recopilación, análisis, interpretación y visualización de datos numéricos. La probabilidad tiene su origen en el estudio del juego y los seguros en el siglo XVII, y ahora es una herramienta indispensable de las ciencias sociales y naturales.
          br
          br
          | Se puede decir que las estadísticas tienen su origen en los censos realizados hace miles de años; Sin embargo, como disciplina científica distinta, se desarrolló a principios del siglo XIX como el estudio de poblaciones, economías y acciones morales y, más tarde en ese siglo, como herramienta matemática para analizar tales números.

  
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
          p La media aritmética (o simplemente media) de una lista de números, es la suma de todos los números divididos por el número de números. De manera similar, la media de una muestra x1, x2, ..., xn, generalmente denotado por #[em n] es la suma de los valores muestreados dividida por el número de elementos de la muestra:
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
      .col-12.col-md-4.mb-5.mb-lg-0.d-none.d-sm-none.d-md-block(data-aos="fade-right")
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
      SlyderA(tipo="b")
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
          p.titulo.pb-0.mb-0 #[b Figura 1.] #[i Diferencias entre mediana, media y moda.] 
        figure
          img(src='@/assets/curso/temas/tema1/tema1-27.svg', alt='')  
          figcaption.mt-2 Nota. Tomada de https://www.nobbot.com/educacion/no-te-quedes-en-la-media-y-aprende-a-calcular-la-mediana-asi-se-hace/
        
    .row.justify-content-center.align-items-center.mb-4
      .col-12(data-aos="fade-down-right")
        .cajon.color-acento-botones.p-4.mb-4
          p A diferencia de la mediana, el concepto de moda tiene sentido para cualquier variable aleatoria que asuma valores de un espacio vectorial, incluidos los números reales (un espacio vectorial unidimensional) y los enteros (que pueden considerarse incrustados en los reales). Por ejemplo, una distribución de puntos en el plano normalmente tendrá una media y una moda, pero el concepto de mediana no se aplica. La mediana tiene sentido cuando existe un orden lineal en los valores posibles.


    .titulo-sexto.color-acento-contenido
      p.titulo.pb-0.mb-0 #[b Tabla 1.] #[i Las generalizaciones del concepto de mediana a espacios de dimensiones superiores son la mediana geométrica y el punto central.] 
    .tabla-a.color-acento-contenido.mb-5
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
            td.text-center (1 + 2 + 2 + 3 + 4 + 7 + 9) / 7
            td.text-center 4
          tr
            th Mediana
            td Valor medio o central que separa las mitades menor y mayor de un conjunto de elementos numéricos.
            td.text-center 1, 2, 2, 3, 4, 7, 9
            td.text-center 3
          tr
            th Moda
            td Valor más frecuente en un conjunto de elementos numéricos.
            td.text-center 1, 2, 2, 3, 4, 7, 9
            td.text-center 2

    hr

    .row.justify-content-center.align-items-center.mb-3
      .col-12(data-aos="fade-right")
        ul.lista-ul.mb-2
          li.mb-0
            i.fas.fa-play(style="color:#25FFFF")
            | Varianza y desviación típica o estándar

    //- .bloque-texto-g.color-primario.p-3.p-sm-4.p-md-5.mb-5(data-aos="fade-down-right")
    //-   .bloque-texto-g__img(
    //-     :style="{'background-image': `url(${require('@/assets/curso/temas/tema1/tema1-28.png')})`}"
    //-   )
    //-   .bloque-texto-g__texto.p-4
    //-     p.mb-0 La varianza es la expectativa de la desviación al cuadrado de una variable aleatoria de su media poblacional o muestral. La varianza es una medida de dispersión, lo que significa que es una medida de qué tan lejos se separa un conjunto de números de su valor promedio y se define de manera detallada así:


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
              p.mb-0 Por ejemplo, al comparar la acción A que tiene un rendimiento promedio del 7% con una desviación estándar del 10% contra la acción B, que tiene el mismo rendimiento promedio, pero una desviación estándar del 50%, la primera acción sería claramente la opción más segura. Dado que la desviación estándar de la acción B es significativamente mayor, para el mismo rendimiento exacto.
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
        .titulo-sexto.color-acento-botones
          p.titulo.pb-0.mb-0 #[b Figura 2.] #[i Ejemplo Variable continua.]
        figure
          img(src='@/assets/curso/temas/tema1/tema1-38.svg', alt='')  
      .col-12.col-md-8.mb-5.mb-lg-0(data-aos="fade-left")
        .cajon.color-acento-botones.p-4.mb-2
          p.mb-0 Definamos más un par de términos utilizados en nuestra definición. Una variable en estadística no es lo mismo que una variable en álgebra. En estadística, una variable es algo que nos da datos. Algunos ejemplos de variables en las estadísticas pueden incluir edad, color de ojos, altura, número de hermanos, sexo o número de mascotas. Nuestra definición de variable continua también menciona que es cuantitativa. Los datos cuantitativos involucran cantidades o números. En los ejemplos de variables enumerados anteriormente, su edad, altura, número de hermanos y número de mascotas son todas variables cuantitativas.

    
    .tarjeta--container.row.mb-5(data-aos="fade-down-right")
      .col-md.tarjeta.tarjeta--azul.px-5.py-3
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


    Separador
    #t_1_2.titulo-segundo.color-acento-botones(data-aos="fade-right")
      h2 1.2 Distribuciones bidimensionales, diagramas de dispersión y rectas de regresión

    p.mb-5(data-aos="fade-right") En el siguiente recurso, se invita a descubrir todo sobre las distribuciones bidimensionales, diagramas de dispersión y rectas de regresión.

    .row.mb-4.justify-content-center
      .col-12.mb-3(data-aos="fade-right")
        ol.lista-ol--cuadro
          li 
            .lista-ol--cuadro__vineta
              span a
            | Distribuciones Bidimensionales
      .col-12.col-md-8.mb-4(data-aos="fade-right")
        p.mb-4 En la estadística, a la distribución donde interceden dos variables, x e y, se le denomina distribución bidimensional, esto significa que a cada individuo le pertenecen dos valores, xi, yi. Y al momento de ser representados en un plano o diagrama cartesiano se les debe considerar como coordenadas de un solo punto (xi, yi). Así, toda esta distribución se visualizará como un conjunto de puntos y cada punto corresponde a un individuo de la distribución. 
        .cajon.color-acento-botones.p-4.mb-2
          p.mb-0 Como ejemplo típico de distribución bidimensional, se pueden tomar los errores de precisión del fuego de artillería. El error total se compone de dos desviaciones independientes: error en la distancia de disparo X y desviación lateral Y de la dirección de disparo. Un número tan relativamente pequeño de puntos clasifica esta distribución entre las distribuciones discretas. 
      .col-12.col-md-4.mb-5(data-aos="fade-right")
        .titulo-sexto.color-acento-botones
          p.titulo.pb-0.mb-0.text-small #[b Figura 3.] #[i Ejemplo Distribuciones Bidimensionales.]
        figure
          img(src='@/assets/curso/temas/tema1/tema1-41.svg', alt='')
      
      .col-12.mt-4.mb-0(data-aos="fade-right")
        ol.lista-ol--cuadro
          li 
            .lista-ol--cuadro__vineta
              span b
            | Correlación
      .col-12.col-md-8.mb-4(data-aos="fade-right")
        p La correlación es una medida estadística que indica la relación lineal entre dos variables. No implica una relación de causa y efecto, sino que cuantifica la fuerza de la relación. Se utiliza un coeficiente de correlación, r, para medir la correlación. Además, se pueden realizar pruebas estadísticas para determinar la significancia de la correlación. Sin embargo, la correlación tiene limitaciones, ya que no puede tener en cuenta otras variables que puedan influir en la relación entre las dos variables analizadas. 
      .col-12.col-md-4.mb-4(data-aos="fade-right")
        figure
          img(src='@/assets/curso/temas/tema1/tema1-42.png', alt='')
          
    p.mb-5(data-aos="fade-right") La correlación no implica causalidad y no describe relaciones curvilíneas. Sin embargo, es útil para analizar relaciones simples entre datos. Por ejemplo, al examinar datos de campings en un parque de montaña, se puede utilizar la correlación para determinar si hay una relación entre la elevación del camping y la temperatura alta en verano. Una correlación negativa indica que a medida que aumenta la elevación, la temperatura tiende a descender. 


    .row.justify-content-center.align-items-center.mb-3
      .col-12(data-aos="fade-right")
        ul.lista-ul.mb-2
          li.mb-0
            i.fas.fa-play(style="color:#25FFFF")
            | Diagramas de dispersión


    .row.mb-5.justify-content-center.align-items-center
      .col-12.col-md-4.mb-5.mb-lg-0(data-aos="fade-right")
        figure
          img(src='@/assets/curso/temas/tema1/tema1-43.png', alt='')  
      .col-12.col-md-8.mb-5.mb-lg-0(data-aos="fade-left")
        p Los diagramas de dispersión son herramientas matemáticas convenientes para estudiar la correlación entre dos variables aleatorias. Como su nombre indica, son una forma de hoja de papel sobre la que se encuentran dispersos los puntos de datos correspondientes a las variables de interés. 
        .cajon.color-acento-botones.p-4.mb-2
          p.mb-0 A juzgar por la forma del patrón que forman los puntos de datos en esta hoja de papel, podemos determinar la asociación entre las dos variables y aplicar la técnica de análisis de correlación más adecuada.

    .row.justify-content-center.align-items-center.mb-5
      .col-12.col-lg-10(data-aos="fade-right")
        .titulo-sexto.color-acento-botones
          p.titulo.pb-0.mb-0 #[b Figura 4.] #[i a. Correlación débil, b. Correlación fuerte, c. correlación inversa] 
        figure
          img(src='@/assets/curso/temas/tema1/tema1-44.svg', alt='')  
          figcaption.mt-2 Nota. Tomada de https://www.monografias.com/trabajos82/regresion-y-correlacion-lineal/regresion-y-correlacion-lineal2.shtml
        

    .row.justify-content-center.align-items-center.mb-3
      .col-12(data-aos="fade-right")
        ul.lista-ul.mb-2
          li.mb-0
            i.fas.fa-play(style="color:#25FFFF")
            | Interpretación de diagramas de dispersión
            

    .row.mb-5.justify-content-center.align-items-center
      .col-12.col-md-9.mb-5.mb-lg-0(data-aos="fade-left")
        p Los diagramas de dispersión entre dos variables aleatorias presentan las variables como sus ejes x e y. Podemos tomar cualquier variable como variable independiente en tal caso (la otra variable es la dependiente) y, en consecuencia, graficar cada punto de datos en el gráfico (xi, yi). La totalidad de todos los puntos graficados forma el diagrama de dispersión. Basándonos en las diferentes formas que puede asumir el diagrama de dispersión, podemos sacar diferentes inferencias. Podemos calcular un coeficiente de correlación para los datos dados. Es una medida cuantitativa de la asociación de las variables aleatorias. Su valor es siempre menor que 1 y puede ser positivo o negativo.
      .col-12.col-md-3.mb-5.mb-lg-0(data-aos="fade-right")
        figure
          img(src='@/assets/curso/temas/tema1/tema1-45.svg', alt='')  


    .tarjeta--container.row.mb-5(data-aos="fade-down-right")
      .col-md.tarjeta.color-acento-contenido.px-5.py-3
        .row.justify-content-center.mb-4
          .col-6
            div.formulas.mb-3
              img(src='@/assets/curso/temas/tema1/tema1-39.svg', alt='')
        p En el caso de una correlación positiva, los puntos graficados se distribuyen desde la esquina inferior izquierda a la esquina superior derecha (en el patrón general de estar distribuidos uniformemente sobre una línea recta con una pendiente positiva), y en el caso de una correlación negativa, los puntos trazados se extienden sobre una línea recta de una pendiente negativa desde la parte superior izquierda hacia la parte inferior derecha.
      .col-md.tarjeta.tarjeta--azul.px-5.py-3
        .row.justify-content-center.mb-4
          .col-6
            div.formulas.mb-3
              img(src='@/assets/curso/temas/tema1/tema1-40.svg', alt='')
        p Si los puntos están distribuidos aleatoriamente en el espacio, o distribuidos casi por igual en todos los lugares sin representar ningún patrón en particular, es el caso de una correlación muy pequeña, que tiende a 0.


    .row.justify-content-center.align-items-center.mb-3
      .col-12(data-aos="fade-right")
        ul.lista-ul.mb-2
          li.mb-0
            i.fas.fa-play(style="color:#25FFFF")
            | Regresión

    .row.mb-5.justify-content-center.align-items-center
      .col-12.col-md-3.mb-5.mb-lg-0(data-aos="fade-right")
        figure
          img(src='@/assets/curso/temas/tema1/tema1-46.svg', alt='') 
      .col-12.col-md-9.mb-5.mb-lg-0(data-aos="fade-left")
        p Consiste en una técnica estadística para estimar las relaciones entre variables. Incluye muchas técnicas para modelar y analizar varias variables cuando el foco está en la relación entre una variable dependiente y una o más variables independientes. Más específicamente, el análisis de regresión ayuda a comprender cómo cambia el valor típico de la variable dependiente cuando se varía cualquiera de las variables independientes, mientras que las otras variables independientes se mantienen fijas. Más comúnmente, el análisis de regresión estima la expectativa condicional de la variable dependiente dadas las variables independientes, es decir, el valor promedio de la variable dependiente cuando las variables independientes son fijas. Con menos frecuencia, la atención se centra en un cuantil, u otro parámetro de ubicación de la distribución condicional de la variable dependiente dadas las variables independientes. 


    .row.mb-5.justify-content-center.align-items-center
      .col-12.mb-5.mb-lg-0(data-aos="fade-right")
        .cajon.color-acento-contenido.p-4.mb-2
          p.mb-0 En todos los casos, el objetivo de estimación es una función de las variables independientes, llamada función de regresión. En el análisis de regresión, también es interesante caracterizar la variación de la variable dependiente alrededor de la función de regresión, que puede describirse mediante una distribución de probabilidad. Una aplicación muy común de la regresión es ayudar a los administradores financieros y de inversiones a valorar los activos y comprender las relaciones entre las variables, como los precios de los productos básicos y las acciones de las empresas que comercian con esos productos básicos.
          
    .row.justify-content-center.align-items-center.mb-5
      .col-12.col-lg-10(data-aos="fade-right")
        .titulo-sexto.color-acento-botones
          p.titulo.pb-0.mb-0 #[b Figura 5.] #[i Ejemplo función de regresión.] 
        figure
          img(src='@/assets/curso/temas/tema1/tema1-47.svg', alt='')  

    p.mb-3(data-aos="fade-right") El #[i software] no es solo para buscar filtros de caras divertidas o aprender nuevos movimientos de baile. Puede ayudar a su equipo a aumentar su eficiencia y ser más productivo y capaz en su trabajo. Una solución de #[i software] personalizada puede ayudar a eliminar el cuello de botella del seguimiento de los recibos y gastos del personal, o puede facilitar que su equipo administre los contactos de #[i marketing].
    p.mb-5(data-aos="fade-right") Y el #[i software] personalizado también puede servir como una solución para sus clientes. Por ejemplo, una opción de chat en vivo en su sitio web proporciona un contacto inmediato para clientes o prospectos con una necesidad urgente o que están listos para realizar una compra. Un #[i software] personalizado también podría ayudar a sus clientes a rastrear a su representante de servicio en el camino a su hogar, o enviar una solicitud de soporte técnico.


    .row.justify-content-center.align-items-center.mb-3
      .col-12(data-aos="fade-right")
        ul.lista-ul.mb-2
          li.mb-0
            i.fas.fa-play(style="color:#25FFFF")
            | Rectas de regresión

    p.mb-5(data-aos="fade-right") Están definidas de la siguiente manera:


    .row.justify-content-center.align-items-center.mb-4
      .col-12(data-aos="fade-down")
        .tarjeta-avatar-b.mb-4
          .color-primario.pasos-custom.grande.px-5
            .pasos-a__circle
              .h2.text-white A
          .tarjeta.tarjeta--custom
            .p-4
              p.mb-0 Las rectas de regresión son líneas que se utiliza para describir el comportamiento de un conjunto de datos. En otras palabras, da la mejor tendencia de los datos proporcionados. Las rectas de regresión son útiles en los procedimientos de pronóstico. Su propósito es describir la interrelación de la variable dependiente (variable y) con una o muchas variables independientes (variable x).
              .titulo-sexto.color-acento-botones.mt-3
                p.titulo.pb-0.mb-0 #[b Figura 6.] #[i Ejemplo rectas de regresión.] 
              figure
                img(src='@/assets/curso/temas/tema1/tema1-48.svg', alt='') 
                figcaption.mt-2 Fuente.  http://halweb.uc3m.es/esp/Personal/personas/aarribas/esp/docs/estII/tema4esp(2).pdf
      .col-12(data-aos="fade-down")
        .tarjeta-avatar-b.mb-4
          .color-primario.pasos-custom.px-5
            .pasos-a__circle
              .h2.text-white B
          .tarjeta.tarjeta--custom
            .p-4
              p.mb-0 El uso de la ecuación obtenida de la recta de regresión actúa como un analista que puede pronosticar comportamientos futuros de las variables dependientes ingresando diferentes valores para las independientes. Los dos tipos básicos de regresión son la recta de regresión normal o simple y la recta de regresión múltiple, aunque existen métodos de regresión no lineal para datos y análisis más complicados. 
      .col-12(data-aos="fade-down")
        .tarjeta-avatar-b.mb-4
          .color-primario.pasos-custom.px-5
            .pasos-a__circle
              .h2.text-white C
          .tarjeta.tarjeta--custom
            .p-4
              p.mb-0 La recta de regresión simple usa una variable independiente para explicar o predecir el resultado de la variable dependiente Y, mientras que la recta de regresión múltiple usa dos o más variables independientes para predecir el resultado. 
      .col-12(data-aos="fade-down")
        .tarjeta-avatar-b.mb-4
          .color-primario.pasos-custom.grande.px-5
            .pasos-a__circle
              .h2.text-white D
          .tarjeta.tarjeta--custom
            .p-4
              p.mb-0 La forma general de cada tipo de regresión es: fórmula de la recta de regresión simple: #[strong Y = a + bX + u]
              p Fórmula de la recta de regresión múltiple: #[strong Y = a + b1X1 + b2 X2 + b3 X3 + … + bt Xt + u]

              h6 Donde:
              ul.lista-ul.mb-2
                li.mb-0.text-small
                  i.lista-ul__vineta(style="color:#AD84FF")
                  | Y = la variable que está intentando predecir (variable dependiente).
                li.mb-0.text-small
                  i.lista-ul__vineta(style="color:#AD84FF")
                  | X = la variable que está utilizando para predecir Y (variable independiente).
                li.mb-0.text-small
                  i.lista-ul__vineta(style="color:#AD84FF")
                  | a = la intersección.
                li.mb-0.text-small
                  i.lista-ul__vineta(style="color:#AD84FF")
                  | b = la pendiente.
                li.mb-0.text-small
                  i.lista-ul__vineta(style="color:#AD84FF")
                  | u = el residual de regresión.

    .row.justify-content-center.align-items-center.mb-5
      .col-md-11.col-lg-10.mb-4.mb-md-0(data-aos="fade-left")
        .tarjeta.color-primario.p-3
          .row.justify-content-around.align-items-center
            .col-3.col-sm-2.col-lg-1
              img(src="@/assets/curso/temas/pdf.svg")
            .col
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0
                  h4 Para profundizar aún más en este ítem, diríjase al: 
                  p.text-small Anexo 1 - Distribuciones bidimensionales y rectas de regresión.
                .col-sm-auto
                  a.boton.color-acento-botones(:href="obtenerLink('/downloads/anexo_1_distribuciones_bidimensionales_y_rectas_de_regresion.pdf')" target="_blank")
                    span Descargar
                    i.fas.fa-file-download


    Separador
    #t_1_3.titulo-segundo.color-acento-botones(data-aos="fade-right")
      h2 1.3 Distribuciones discretas, distribución binomial, distribuciones continuas, distribución normal

    p.mb-5(data-aos="fade-left") A continuación, se exponen los diferentes tipos de distribución y cómo aplicarlos en la vida profesional. 


    .bloque-texto-g.color-primario.p-3.p-sm-4.p-md-5.mb-5(data-aos="fade-down-right")
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/temas/tema1/tema1-49.png')})`}"
      )
      .bloque-texto-g__texto.p-4
        p.mb-0 En estadística, las distribuciones parecen infinitas con docenas de distribuciones compitiendo por su atención y con poca o ninguna base intuitiva para diferenciarlas. Las descripciones tienden a ser abstractas y enfatizan propiedades estadísticas como los momentos, funciones características y distribuciones acumulativas.


    .row.justify-content-center.align-items-center.mb-3
      .col-12(data-aos="fade-right")
        ul.lista-ul.mb-2
          li.mb-0
            i.fas.fa-play(style="color:#25FFFF")
            | Distribuciones discretas

    p.mb-5(data-aos="fade-left") Una distribución discreta es una distribución de probabilidad que representa la ocurrencia de resultados discretos (contables individualmente), como 1, 2, 3 … o 0 contra 1. 

    .row.mb-5.justify-content-center.align-items-center
      .col-12.mb-5.mb-lg-0(data-aos="fade-right")
        .cajon.color-acento-contenido.p-4.mb-2
          p.mb-0 Por ejemplo, es una distribución discreta que evalúa la probabilidad de que ocurra un resultado “sí” o “no” en un número determinado de intentos, dada la probabilidad del evento en cada intento, como lanzar una moneda cien veces y teniendo el resultado “cabezas”. 


    .row.justify-content-center.align-items-center.mb-5
      .px-3.mb-0
        .titulo-sexto.color-acento-botones.mt-3
          p.titulo.pb-0.mb-0 #[b Figura 7.] #[i Ejemplo distribución discreta.] 
      .col-12.col-md-6.mb-3(data-aos="fade-right")
        figure
          img(src='@/assets/curso/temas/tema1/tema1-50.svg', alt='') 
      .col-12.col-md-6.mb-3(data-aos="fade-left")
        figure
          img(src='@/assets/curso/temas/tema1/tema1-51.svg', alt='') 
      .col-12.col-md-6.mb-3(data-aos="fade-right")
        figure
          img(src='@/assets/curso/temas/tema1/tema1-52.svg', alt='') 
      .col-12.col-md-6.mb-3(data-aos="fade-left")
        figure
          img(src='@/assets/curso/temas/tema1/tema1-53.svg', alt='') 

    p.mb-5(data-aos="fade-right") Las distribuciones estadísticas pueden ser discretas o continuas. Una distribución continua se construye a partir de resultados que caen en un continuo, como todos los números mayores que 0 (que incluirían números cuyos decimales continúan indefinidamente, como pi = 3,14159265 …). En general, los conceptos de distribuciones de probabilidad discretas y continuas y las variables aleatorias que describen son la base de la teoría de la probabilidad y el análisis estadístico.


    .row.justify-content-center.align-items-center.mb-3
      .col-12(data-aos="fade-right")
        ul.lista-ul.mb-2
          li.mb-0
            i.fas.fa-play(style="color:#7125C8")
            | Características principales

    .row.mb-5
      .col-12.col-md-4.mb-4(data-aos="fade-down")
        .tarjeta.tarjeta-slide.arriba.color-secundario(@mouseover="indicadorTarjetaSlide = false")
          .indicador--hover(v-if="indicadorTarjetaSlide")
          .tarjeta-slide__contenedor
            .tarjeta-slide__img(:style="{'background-image': `url(${require('@/assets/curso/temas/tema1/tema1-54.svg')})`}")
            .tarjeta-slide__contenido.p-4.p-xl-5
              p Una distribución de probabilidad discreta cuenta las ocurrencias que tienen resultados contables o finitos.
      .col-12.col-md-4.mb-4(data-aos="fade-down")
        .tarjeta.tarjeta-slide.abajo.color-primario(@mouseover="indicadorTarjetaSlide = false")
          .tarjeta-slide__contenedor
            .tarjeta-slide__img(:style="{'background-image': `url(${require('@/assets/curso/temas/tema1/tema1-55.svg')})`}")
            .tarjeta-slide__contenido.p-4.p-xl-5
              p Esto contrasta con una distribución continua, donde los resultados pueden caer en cualquier parte de un continuo.
      .col-12.col-md-4.mb-4(data-aos="fade-down")
        .tarjeta.tarjeta-slide.arriba.color-secundario(@mouseover="indicadorTarjetaSlide = false")
          .indicador--hover(v-if="indicadorTarjetaSlide")
          .tarjeta-slide__contenedor
            .tarjeta-slide__img(:style="{'background-image': `url(${require('@/assets/curso/temas/tema1/tema1-56.svg')})`}")
            .tarjeta-slide__contenido.p-4.p-xl-5
              p Los ejemplos comunes de distribución discreta incluyen las distribuciones binomiales, binomial negativa, beta-binomial, Poisson, hipergeométrica y Bernoulli.
      .col-12.col-md-4.mb-4(data-aos="fade-down")
        .tarjeta.tarjeta-slide.abajo.color-primario(@mouseover="indicadorTarjetaSlide = false")
          .tarjeta-slide__contenedor
            .tarjeta-slide__img(:style="{'background-image': `url(${require('@/assets/curso/temas/tema1/tema1-57.svg')})`}")
            .tarjeta-slide__contenido.p-4.p-xl-5
              p Estas distribuciones a menudo involucran análisis estadísticos de “conteos” o “cuántas veces” ocurre un evento.
      .col-12.col-md-4.mb-4(data-aos="fade-down")
        .tarjeta.tarjeta-slide.abajo.color-secundario(@mouseover="indicadorTarjetaSlide = false")
          .tarjeta-slide__contenedor
            .tarjeta-slide__img(:style="{'background-image': `url(${require('@/assets/curso/temas/tema1/tema1-58.svg')})`}")
            .tarjeta-slide__contenido.p-4.p-xl-5
              p En finanzas, las distribuciones discretas se utilizan en la fijación de precios de opciones y en la previsión de shocks o recesiones del mercado.


    .row.justify-content-center.align-items-center.mb-3
      .col-12(data-aos="fade-right")
        ul.lista-ul.mb-2
          li.mb-0
            i.fas.fa-play(style="color:#25FFFF")
            | Distribución binomial


    .row.justify-content-center.align-items-center.mb-5
      .col-12.col-md-11.col-lg-10(data-aos="fade-right")
        p Suponer que X1, X2, …, Xn son variables aleatorias de Bernoulli independientes e idénticamente distribuidas (iid), cada una con la distribución. 
      .col-12.col-md-11.col-lg-10(data-aos="fade-right")
        div.formulas.mb-3
          img(src='@/assets/curso/temas/tema1/tema1-59.svg', alt='')
      .col-12.col-md-11.col-lg-10(data-aos="fade-right")
        p Entonces se dice que X tiene una distribución binomial con parámetros n y p:
      .col-12.col-md-11.col-lg-10(data-aos="fade-right")
        .row 
          .col-12.col-md-7
            div.formulas.mb-3
              img(src='@/assets/curso/temas/tema1/tema1-61.svg', alt='')
            p Suponga que un experimento e x consiste en n ensayos repetidos tipo Bernoulli, cada ensayo resulta en un “éxito” con probabilidad π y un “fracaso” con probabilidad 1 – π. Por ejemplo, lanza una moneda 100 veces n = 100. Cuente el número de veces que observa cabezas, por ejemplo, X = # de cabezas. Si todos los ensayos son independientes, es decir, si la probabilidad de éxito en cualquier ensayo no se ve afectada por el resultado de cualquier otro ensayo, entonces el número total de éxitos en el experimento tendrá una distribución binomial, por ejemplo, dos lanzamientos de moneda no lo hacen afectarse unos a otros. La distribución binomial se puede escribir como:
            div.formulas.mb-3
              img(src='@/assets/curso/temas/tema1/tema1-62.svg', alt='')
            p La distribución de Bernoulli es un caso especial del binomio con n = 1. Es decir,
            div.formulas.mb-3
              img(src='@/assets/curso/temas/tema1/tema1-63.svg', alt='')
          .col-12.col-md-5.d-none.d-sm-none.d-md-block
            figure
              img(src='@/assets/curso/temas/tema1/tema1-60.svg', alt='')
      .col-12-col-md-11.col-lg-10(data-aos="fade-right")
        p Ello significa que X tiene una distribución de Bernoulli con probabilidad de éxito π. Se puede demostrar algebraicamente que si se cumple la ecuación anterior entonces:
      .col-12.col-md-11.col-lg-10(data-aos="fade-right")
        div.formulas.mb-3
          img(src='@/assets/curso/temas/tema1/tema1-64.svg', alt='')
      .col-12.col-md-11.col-lg-10(data-aos="fade-right")
        p Una forma más sencilla de llegar a estos resultados es tener en cuenta que dónde son variables aleatorias de Bernoulli. Entonces, por las propiedades aditivas de media y varianza, X= X1, X2, …, Xn donde X1, X2, …, Xn son variables aleatorias de Bernoulli. Entonces, por las propiedades aditivas de media y varianza,
      .col-12.col-md-11.col-lg-10(data-aos="fade-right")
        div.formulas.mb-3
          img(src='@/assets/curso/temas/tema1/tema1-65.svg', alt='')
        div.formulas.mb-3
          img(src='@/assets/curso/temas/tema1/tema1-66.svg', alt='')

    .row.mb-5(data-aos="fade-down-right")
      .col-12.col-md-5.col-lg-4.d-none.d-sm-none.d-md-block
        figure
          img(src='@/assets/curso/temas/tema1/tema1-67.svg', alt='')
      .col-12.col-md-7.col-lg-8
        p Tenga en cuenta que X no tendrá una distribución binomial si la probabilidad de éxito π no es constante de un ensayo a otro, o si los ensayos no son completamente independientes (es decir, un éxito o fracaso en un ensayo altera la probabilidad de éxito en otro ensayo).
        div.formulas.mb-3
          img(src='@/assets/curso/temas/tema1/tema1-68.svg', alt='')
        p A medida que n aumenta, para fijo π, la distribución binomial se aproxima a la distribución normal:
        div.formulas.mb-3
          img(src='@/assets/curso/temas/tema1/tema1-69.svg', alt='')

    p.mb-5(data-aos="fade-down-right") Por ejemplo, si se toman muestras sin reemplazo de una población finita, entonces la distribución hipergeométrica es apropiada. 


    .row.justify-content-center.align-items-center.mb-5
      .col-md-11.col-lg-10.mb-4.mb-md-0(data-aos="fade-left")
        .tarjeta.color-primario.p-3
          .row.justify-content-around.align-items-center
            .col-3.col-sm-2.col-lg-1
              img(src="@/assets/curso/temas/pdf.svg")
            .col
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0
                  h4 Para profundizar aún más en este ítem, diríjase al: 
                  p.text-small Anexo 2 - Modelos de probabilidad discretos.
                .col-sm-auto
                  a.boton.color-acento-botones(:href="obtenerLink('/downloads/anexo_2_modelos_de_probabilidad_discretos.pdf')" target="_blank")
                    span Descargar
                    i.fas.fa-file-download

    .row.justify-content-center.align-items-center.mb-3
      .col-12(data-aos="fade-right")
        ul.lista-ul.mb-2
          li.mb-0
            i.fas.fa-play(style="color:#25FFFF")
            | Distribuciones continuas

    p.mb-5(data-aos="fade-down-right") Estas pueden tomar cualquier valor dentro de un rango definido. Este rango puede ser infinito (por ejemplo, para la distribución normal) en cuyo caso se habla de una distribución limitada o si es finita (por ejemplo, la distribución uniforme) es una distribución delimitada.


    .row.justify-content-center.align-items-center.mb-5
      .col-12.col-lg-10(data-aos="fade-right")
        .titulo-sexto.color-acento-botones
          p.titulo.pb-0.mb-0 #[b Figura 8.] #[i Distribuciones continuas.] 
        figure
          img(src='@/assets/curso/temas/tema1/tema1-70.svg', alt='')  
          figcaption Nota. Tomada de: https://slideplayer.es/amp/1025784/


    .row.justify-content-center.align-items-center.mb-5
      .col-md-11.col-lg-10.mb-4.mb-md-0(data-aos="fade-left")
        .tarjeta.color-primario.p-3
          .row.justify-content-around.align-items-center
            .col-3.col-sm-2.col-lg-1
              img(src="@/assets/curso/temas/pdf.svg")
            .col
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0
                  h4 En el Anexo 3 - Distribuciones continuas
                  p.text-small Encontrarán una tabla que ofrece una descripción general de varias distribuciones continuas que se usan comúnmente en el modelado de análisis de riesgos, de modo que pueda enfocarse más fácilmente en cuáles podrían ser las más apropiadas para sus necesidades de modelado. Siga los enlaces para obtener una explicación detallada de cada uno. Se ha utilizado el nombre más común para cada distribución.
                .col-sm-auto
                  a.boton.color-acento-botones(:href="obtenerLink('/downloads/anexo_3_distribuciones_continuas.pdf')" target="_blank")
                    span Descargar
                    i.fas.fa-file-download


    .row.justify-content-center.align-items-center.mb-5
      .col-12.col-md-5.col-lg-3.d-none.d-sm-none.d-md-block(data-aos="fade-down-right")
        figure
          img(src='@/assets/curso/temas/tema1/tema1-71.svg', alt='')
      .col-12.col-md-7.col-lg-8(data-aos="fade-down-right")
        P Una distribución continua se utiliza para representar una variable que puede tomar cualquier valor dentro de un rango definido (dominio). Por ejemplo, la estatura de un inglés adulto escogido al azar tendrá una distribución continua, porque la estatura de una persona es esencialmente infinitamente divisible. Se podría medir su estatura en centímetro, milímetro, décimo de milímetro, etc.; la escala se puede dividir repetidamente generando cada vez más valores posibles.

      .col-lg-11.col-12.mt-3(data-aos="fade-down-right")
        .cajon.color-acento-contenido.p-4.mb-2
          p.mb-0 Propiedades como el tiempo, la masa y la distancia, que son infinitamente divisibles, se modelan utilizando distribuciones continuas. En la práctica, también se usan distribuciones continuas para modelar variables que son, en verdad, discretas, pero donde la brecha entre los valores permitidos es insignificante: por ejemplo, el costo del proyecto (que es discreto con pasos de un centavo, un centavo, etc.), tipo de cambio (que solo se cotiza a unas pocas cifras significativas), número de empleados en una gran organización, etc.
        
    .row.justify-content-center.align-items-center.mb-3
      .col-12(data-aos="fade-right")
        ul.lista-ul.mb-2
          li.mb-0
            i.fas.fa-play(style="color:#25FFFF")
            | Distribución normal

    p.mb-5(data-aos="fade-down-right") En la teoría de la probabilidad, la distribución normal (o gaussiana o Gauss o Laplace-Gauss) es un tipo de distribución de probabilidad continua para un valor real- variable aleatoria. La forma general de su función de densidad de probabilidad es:

    .row.justify-content-center.align-items-center.mb-5
      .col-12(data-aos="fade-right")
        div.formulas.mb-3
          img(src='@/assets/curso/temas/tema1/tema1-72.svg', alt='')

    p.mb-5(data-aos="fade-down-right") El parámetro μ es la media o expectativa de la distribución (y también su mediana y moda), mientras que el parámetro es su desviación estándar σ. La varianza de la distribución es σ2. Se dice que una variable aleatoria con una distribución gaussiana tiene una distribución normal y se denomina desviación normal.

    .row.justify-content-center.align-items-center.mb-5
      .col-12.col-lg-10(data-aos="fade-right")
        .titulo-sexto.color-acento-botones
          p.titulo.pb-0.mb-0 #[b Figura 9.] #[i Distribución normal.] 
        figure
          img(src='@/assets/curso/temas/tema1/tema1-73.svg', alt='')  
          figcaption Nota. Tomada de http://matepedia-estadistica.blogspot.com/2016/09/caracteristicas-de-una-distribucion.html

    .bloque-texto-a.color-primario.p-4.p-md-5.mb-5(data-aos="fade-down-right") 
      .row.m-0.align-items-center.justify-content-between
        .col-lg-12
          .bloque-texto-a__texto.p-4
            p Cualquier combinación lineal de una colección fija de desviaciones normales es una desviación normal. Muchos resultados y métodos, como la propagación de la incertidumbre y el ajuste de parámetros por mínimos cuadrados, pueden derivarse analíticamente de forma explícita cuando las variables relevantes se distribuyen normalmente. Una distribución normal a veces se denomina informalmente curva de campana. Sin embargo, muchas otras distribuciones tienen forma de campana (como las distribuciones de #[em Cauchy], de #[em Student] y logística).


    Separador
    #t_1_4.titulo-segundo.color-acento-botones(data-aos="fade-right")
      h2 1.4 Muestreo, distribución de medias muéstrales

    p.mb-5(data-aos="fade-down-right") Para este tema se invita a revisar de qué trata el muestreo y la distribución de medias muestrales.
    
    .tarjeta.tarjeta--azul.p-4.mb-5(data-aos="fade-down-left") 
      SlyderA(tipo="b")
        .row
          .col-md-5.mb-4.mb-md-0
            p El muestreo es un proceso para seleccionar una muestra representativa de una población. Se utiliza en situaciones donde no es factible obtener información de todos los miembros de la población, como en análisis biológicos, control de calidad o encuestas sociales. El método básico es el muestreo aleatorio simple, donde cada elemento tiene la misma probabilidad de ser seleccionado. El muestreo y la inferencia estadística son herramientas importantes en la investigación científica y el análisis de datos. 
          .col-md-7
            figure
              img(src='@/assets/curso/temas/tema1/tema1-74.png', alt='')
        .row
          .col-md-5.mb-4.mb-md-0
            p En una muestra aleatoria de una clase de 50 estudiantes, por ejemplo, cada estudiante tiene la misma probabilidad, 1/50, de ser seleccionado. Cada combinación de elementos extraídos de la población también tiene la misma probabilidad de ser seleccionados. El muestreo basado en la teoría de la probabilidad permite al investigador determinar la probabilidad que los hallazgos estadísticos son el resultado del azar. 
          .col-md-7
            figure
              img(src='@/assets/curso/temas/tema1/tema1-75.png', alt='')
        .row
          .col-md-5.mb-4.mb-md-0
            p Los métodos más utilizados, refinamientos de esta idea básica, son el muestreo estratificado (en el que la población se divide en clases y se extraen muestras aleatorias simples de cada clase), el muestreo por conglomerados (en el que la unidad de la muestra es un grupo, como un hogar) y muestreo sistemático (muestras tomadas por cualquier sistema que no sea una elección aleatoria, como cada décimo nombre en una lista). 
          .col-md-7
            figure
              img(src='@/assets/curso/temas/tema1/tema1-76.png', alt='')
        .row
          .col-md-5.mb-4.mb-md-0
            p Una alternativa al muestreo probabilístico es muestreo de juicio, en el que la selección se basa en el juicio del investigador y existe una probabilidad desconocida de inclusión en la muestra para cualquier caso dado. Por lo general, se prefieren los métodos de probabilidad porque evitan el sesgo de selección y permiten estimar el error de muestreo (la diferencia entre la medida obtenida de la muestra y la de toda la población de la que se extrajo la muestra). 
          .col-md-7
            figure
              img(src='@/assets/curso/temas/tema1/tema1-77.png', alt='')
        .row
          .col-md-5.mb-4.mb-md-0
            h4.mb-3 Algunas características de muestreo son:
            ul.lista-ul.mb-2
              li
                i.lista-ul__vineta(style="color:#AD84FF")
                | Los Contadores Públicos Certificados utilizan el muestreo durante las auditorías para determinar la precisión y la integridad de los saldos de las cuentas. 
              li
                i.lista-ul__vineta(style="color:#AD84FF")
                | Los tipos de muestreo incluyen muestreo aleatorio, muestreo por bloques, muestreo por juicio y muestreo sistemático.  
              li
                i.lista-ul__vineta(style="color:#AD84FF")
                | Las empresas utilizan el muestreo como una herramienta de #[i marketing] para identificar las necesidades y deseos de su mercado objetivo. 
          .col-md-7
            figure
              img(src='@/assets/curso/temas/tema1/tema1-78.png', alt='')
        .row
          .col-md-5.mb-4.mb-md-0
            p En auditorías financieras, los contadores públicos certificados utilizan el muestreo de auditoría para evaluar la precisión de los saldos de cuentas en los estados financieros. Este método se utiliza cuando la población de transacciones es grande. Además, los gerentes empresariales emplean el muestreo de clientes para evaluar la demanda de nuevos productos y el éxito del #[i marketing]. El muestreo es una herramienta útil en la toma de decisiones y evaluación de datos. 
          .col-md-7
            figure
              img(src='@/assets/curso/temas/tema1/tema1-79.png', alt='')
        .row
          .col-md-5.mb-4.mb-md-0
            p La muestra elegida debe ser una representación justa de toda la población. Al tomar una muestra de una población más grande, es importante considerar cómo se elige la muestra. Para obtener una muestra representativa, se debe extraer al azar y abarcar a toda la población. Por ejemplo, se podría usar un sistema de lotería para determinar la edad promedio de los estudiantes en una universidad tomando una muestra del 10% del cuerpo estudiantil. 
          .col-md-7
            figure
              img(src='@/assets/curso/temas/tema1/tema1-80.png', alt='')

    p.mb-5(data-aos="fade-down-right") Y ahora se sugiere complementar la información con la siguiente presentación.

    .row.justify-content-center.align-items-center.mb-5
      .col-12.col-md-8.mb-5.mb-lg-0(data-aos="fade-left")
        LineaTiempoD.color-primario
          .row(numero="1" titulo="Muestreo aleatorio")
            .col-12.mb-4.mb-md-0
              .row 
                .col-3.d-none.d-sm-none.d-md-block
                  div.formulas.mb-3
                    img(src='@/assets/curso/temas/tema1/tema1-82.svg', alt='')
                .col 
                  p.text-small Con el muestreo aleatorio, cada elemento de una población tiene la misma probabilidad de ser elegido. Es el más alejado de cualquier sesgo potencial porque no hay un juicio humano involucrado en la selección de la muestra.  Por ejemplo, una muestra aleatoria puede incluir elegir los nombres de 25 empleados de un sombrero en una empresa de 250 empleados. La población es de 250 empleados y la muestra es aleatoria porque cada empleado tiene la misma probabilidad de ser elegido.
          .row(numero="2" titulo="Muestreo discrecional o de juicio")
            .col-12.mb-4.mb-md-0
              p.text-small Se puede utilizar el juicio del auditor para seleccionar la muestra de la población completa. Un auditor solo puede estar preocupado por transacciones de naturaleza material. Por ejemplo, suponga que el auditor establece el umbral de importancia relativa para las transacciones de cuentas por pagar en $ 10,000. Si el cliente proporciona una lista completa de 15 transacciones de más de $ 10,000, el auditor puede optar por revisar todas las transacciones debido al pequeño tamaño de la población.
              div.formulas.mb-3
                img(src='@/assets/curso/temas/tema1/tema1-83.svg', alt='')
          .row(numero="3" titulo="Muestreo en bloque")
            .col-12.mb-4.mb-md-0
              p.text-small El muestreo por bloques toma una serie consecutiva de elementos dentro de la población para usar como muestra. Por ejemplo, una lista de todas las transacciones de ventas en un período contable podría clasificarse de varias formas, incluso por fecha o por monto en dólares.
              div.formulas.mb-3
                img(src='@/assets/curso/temas/tema1/tema1-84.svg', alt='')
              .cajon.color-acento-contenido.p-4.mb-2
                p.text-small.mb-0 Un auditor puede solicitar que el contador de la empresa proporcione la lista en un formato u otro para seleccionar una muestra de un segmento específico de la lista. Este método requiere muy poca modificación por parte del auditor, pero es probable que un bloque de transacciones no sea representativo de la población completa.
              .row 
                .col-3.d-none.d-sm-none.d-md-block
                  div.formulas.mb-3
                    img(src='@/assets/curso/temas/tema1/tema1-85.svg', alt='')
                .col 
                  p.text-small Alternativamente, un auditor puede identificar todas las cuentas del libro mayor con una variación mayor al 10% del período anterior. En este caso, el auditor está limitando la población de la que se deriva la selección de la muestra. Desafortunadamente, el juicio humano utilizado en el muestreo siempre conlleva la posibilidad de sesgo, ya sea explícito o implícito.
          .row(numero="4" titulo="Muestreo sistemático")
            .col-12.mb-4.mb-md-0
              p.text-small Los investigadores utilizan el método de muestreo sistemático para elegir los miembros de la muestra de una población a intervalos regulares. Requiere la selección de un punto de partida para la muestra y el tamaño de la muestra que pueda repetirse a intervalos regulares.
              .cajon.color-acento-contenido.p-4.mb-2
                p.text-small.mb-0 Este tipo de método de muestreo tiene un rango predefinido y, por lo tanto, esta técnica de muestreo es la que requiere menos tiempo.
              div.formulas.mb-3
                img(src='@/assets/curso/temas/tema1/tema1-86.svg', alt='')
              p.text-small Suponga que un auditor está revisando los controles internos relacionados con la cuenta de efectivo de una empresa y desea probar la política de la empresa que estipula que los cheques que superen los $ 10,000 deben estar firmados por dos personas. 
              p.text-small La población consiste en cada cheque de la compañía que exceda los $ 10,000 durante el año fiscal, que, en este ejemplo, fue de 300. El auditor usa estadísticas de probabilidad y determina que el tamaño de la muestra debe ser el 20% de la población o 60 cheques. El intervalo de muestreo es 5 (300 controles / 60 controles de muestra).
              .row 
                .col-3.d-none.d-sm-none.d-md-block
                  div.formulas.mb-3
                    img(src='@/assets/curso/temas/tema1/tema1-87.svg', alt='')
                .col 
                  p.text-small Por lo tanto, el auditor selecciona una de cada cinco verificaciones para probarlas. Suponiendo que no se encuentran errores en el trabajo de prueba de muestreo, el análisis estadístico le da al auditor una tasa de confianza del 95% de que el procedimiento de verificación se realizó correctamente. El auditor prueba la muestra de 60 cheques y no encuentra errores, por lo que concluye que el control interno sobre el efectivo está funcionando correctamente.
          .row(numero="5" titulo="Ejemplo de muestreo de <i>marketing</i>")
            .col-12.mb-4.mb-md-0
              p.text-small Las empresas tienen como objetivo vender sus productos y / o servicios a los mercados objetivo. Antes de presentar productos al mercado, las empresas generalmente identifican las necesidades y deseos de su público objetivo. Para hacerlo, pueden emplear un muestreo de la población del mercado objetivo para obtener una mejor comprensión de esas necesidades para luego crear un producto y / o servicio que satisfaga esas necesidades. En este caso, recoger las opiniones de la muestra ayuda a identificar las necesidades del conjunto.
      .col-12.col-md-4.mb-5.mb-lg-0.d-none.d-sm-none.d-md-block(data-aos="fade-right")
        figure
          img(src='@/assets/curso/temas/tema1/tema1-81.png', alt='')  
  
    .row.justify-content-center.align-items-center.mb-3
      .col-12(data-aos="fade-right")
        ul.lista-ul.mb-2
          li.mb-0
            i.fas.fa-play(style="color:#25FFFF")
            | Distribución de medias muestrales
            
    .row.mb-5.align-self-stretch.justify-content-center
      .col-12.col-md-4.mb-5.mb-lg-0.d-none.d-sm-none.d-md-block(data-aos="fade-right")
        figure
          img(src='@/assets/curso/temas/tema1/tema1-88.svg', alt='')  
      .col-12.col-md-8.mb-5.mb-lg-0(data-aos="fade-left")
        p La media muestral de un grupo de observaciones es una estimación de la media poblacional μ. Dada una muestra de tamaño n, considere n variables aleatorias independientes X1, X2, …, Xn, cada una de las cuales corresponde a una observación seleccionada al azar. Cada una de estas variables tiene la distribución de la población, con media μ y desviación estándar σ. La media muestral se define como:
        div.formulas.mb-3
          img(src='@/assets/curso/temas/tema1/tema1-89.svg', alt='')
        p Por las propiedades de las medias y las varianzas de las variables aleatorias, la media y la varianza de la media muestral son las siguientes:
        div.formulas.mb-3
          img(src='@/assets/curso/temas/tema1/tema1-90.svg', alt='')
        p Aunque la media de la distribución de μ es idéntica a la media de la distribución de la población, la varianza es mucho menor para tamaños de muestra grandes.
        
          
    .row.mb-5.align-self-stretch.justify-content-center
      .col-12
        .cajon.color-acento-botones.p-4.mb-2
          p.mb-0 Por ejemplo, suponga que la variable aleatoria X registra el puntaje de un estudiante seleccionado al azar en una prueba nacional, donde la distribución de la población para el puntaje es normal con una media de 70 y una desviación estándar de 5 (N (70,5)). Dada una muestra aleatoria simple (SRS) de 200 estudiantes, la distribución de la puntuación media de la muestra  tiene una media de 70 y una desviación estándar de 5 / sqrt (200) = 5 / 14,14 = 0,35.
    
    .row.mb-5.align-self-stretch.justify-content-center
      .col-12.col-md-8.mb-5.mb-lg-0(data-aos="fade-left")
        p La distribución de medias muestrales se define como el conjunto de medias de todas las posibles muestras aleatorias de un tamaño específico (n) seleccionadas de una población específica. Esta distribución tiene características bien definidas (y predecibles) que se especifican en el teorema del Límite central.
        .row.justify-content-center.align-items-center.mb-5
          .col-12.col-lg-11(data-aos="fade-right")
            .titulo-sexto.color-acento-botones
              p.titulo.pb-0.mb-0 #[b Figura 10.] #[i Distribución de medias muestrales.] 
            figure
              img(src='@/assets/curso/temas/tema1/tema1-92.svg', alt='')  
              figcaption.text-small Nota. Tomada de http://virtual.umng.edu.co/distancia/ecosistema/odin/odin_desktop.php?path=Li4vb3Zhcy9pbmdlbmllcmlhX2luZHVzdHJpYWwvZXN0YWRpc3RpY2FfaWkvdW5pZGFkXzEv#slide_2
        p Cuando la distribución de la población es normal, la distribución de la media muestral también es normal. Para una distribución de población normal con media μ y desviación estándar σ, la distribución de la media de la muestra es normal, con media μ y desviación estándar.
        div.formulas.mb-3
          img(src='@/assets/curso/temas/tema1/tema1-90.svg', alt='')
      .col-12.col-md-4.mb-5.mb-lg-0.d-none.d-sm-none.d-md-block(data-aos="fade-right")
        figure
          img(src='@/assets/curso/temas/tema1/tema1-91.svg', alt='')  

    .row.mb-5.align-self-stretch.justify-content-center(data-aos="fade-right")
      .col-12
        .cajon.color-acento-botones.p-4.mb-2
          p.mb-0 Este resultado se deriva del hecho de que cualquier combinación lineal de variables aleatorias normales independientes también se distribuye normalmente. Esto significa que para dos variables aleatorias normales independientes X, Y y cualquier constante a y b, Ax + By serán distribuidos normalmente. En el caso de la media muestral, la combinación lineal es = (1 / n) * (X1 + X2 + ... Xn).

    .row.justify-content-center.align-items-center.mb-3
      .col-12(data-aos="fade-right")
        ul.lista-ul.mb-2
          li.mb-0
            i.fas.fa-play(style="color:#25FFFF")
            | Teorema del Límite central

    .row.mb-5.align-self-stretch.justify-content-center
      .col-12.col-md-8.mb-5.mb-lg-0(data-aos="fade-left")
        p El resultado más importante sobre las medias muestrales es el teorema del Límite central. En pocas palabras, este teorema dice que para un tamaño de muestra n suficientemente grande, la distribución de la media muestral X se acercará a una distribución normal. Esto es cierto para una muestra de variables aleatorias independientes de cualquier distribución de población, siempre que la población tenga una desviación estándar finita σ. Una declaración formal del teorema del límite central es la siguiente:
        p Si X es la media de una muestra aleatoria X1, X2, ..., Xn de tamaño n de una distribución con una media finita μ y una varianza positiva finita σ², entonces la distribución de W =
        div.formulas.mb-3
          img(src='@/assets/curso/temas/tema1/tema1-95.svg', alt='')
        p es N (0,1) en el límite cuando n se acerca al infinito.
        p Esto significa que la variable σ se distribuye
        div.formulas.mb-3
          img(src='@/assets/curso/temas/tema1/tema1-96.svg', alt='')
        p Una aplicación bien conocida de este teorema es la aproximación normal a la distribución binomial.
      .col-12.col-md-4.mb-5.mb-lg-0.d-none.d-sm-none.d-md-block(data-aos="fade-right")
        figure
          img(src='@/assets/curso/temas/tema1/tema1-94.svg', alt='')  


    .row.justify-content-center.align-items-center.mb-4
      .col-12.col-lg-10(data-aos="fade-right")
        .titulo-sexto.color-acento-botones
          p.titulo.pb-0.mb-0 #[b Figura 11.] #[i Teorema del Límite central.] 
        figure
          img(src='@/assets/curso/temas/tema1/tema1-97.svg', alt='')  
          figcaption Nota. Tomada de  http://virtual.umng.edu.co/distancia/ecosistema/odin/odin_desktop.php?path=Li4vb3Zhcy9pbmdlbmllcmlhX2luZHVzdHJpYWwvZXN0YWRpc3RpY2FfaWkvdW5pZGFkXzEv#slide_3

    p.mb-5(data-aos="fade-down-right") El concepto de distribución de medias muestrales y sus características deben ser intuitivamente razonables:

    .tarjeta--container.row.mb-5(data-aos="fade-down-right")
      .col-md.tarjeta.tarjeta--azul.px-5.py-3
        .row.justify-content-center.mb-4
          .col-6
            div.formulas.mb-3
              img(src='@/assets/curso/temas/tema1/tema1-39.svg', alt='')
        p Es de notar que las medias muestrales son variables. Si se seleccionan dos (o más) muestras de la misma población, es probable que las dos muestras tienen medias diferentes.
      .col-md.tarjeta.tarjeta--gris.px-5.py-3
        .row.justify-content-center.mb-4
          .col-6
            div.formulas.mb-3
              img(src='@/assets/curso/temas/tema1/tema1-39.svg', alt='')
        p Aunque las muestras tendrán medias diferentes, se debe esperar que las medias muestrales estén cerca de la media de la población. Es decir, las medias de la muestra deberían “acumularse” alrededor de μ. Por tanto, la distribución de las medias muestrales tiende a adoptar una forma normal con un valor esperado de μ.
      .col-md.tarjeta.tarjeta--azul.px-5.py-3
        .row.justify-content-center.mb-4
          .col-6
            div.formulas.mb-3
              img(src='@/assets/curso/temas/tema1/tema1-39.svg', alt='')
        p Debe darse cuenta de que la media de una muestra individual probablemente no será idéntica a la media de su población; es decir, habrá algún “error” entre X y μ. Algunas medias de muestra estarán relativamente cerca de μ y otras relativamente lejos. El error estándar proporciona una medida de la distancia estándar entre X y μ.

    .row.justify-content-center.align-items-center.mb-3
      .col-12(data-aos="fade-right")
        ul.lista-ul.mb-2
          li.mb-0
            i.fas.fa-play(style="color:#25FFFF")
            | Puntuaciones Z y ubicación dentro de la distribución de medias muestrales

    .row.mb-3.align-self-stretch
      .col-12.col-md-12.mb-5.mb-lg-0(data-aos="fade-left")
        ul.lista-ul.mb-2
          li
            i.lista-ul__vineta(style="color:#AD84FF")
            | Dentro de la distribución de las medias muestrales, la ubicación de cada media muestral se puede especificar mediante una puntuación Z,
        div.formulas.mb-3
          img(src='@/assets/curso/temas/tema1/tema1-98.svg', alt='')
        ul.lista-ul.mb-2
          li
            i.lista-ul__vineta(style="color:#AD84FF")
            | Debe darse cuenta de que la media de una muestra individual probablemente no será idéntica a la media de su población; es decir, habrá algún “error” entre X y μ. Algunas medias de muestra estarán relativamente cerca de μ y otras relativamente lejos. El error estándar proporciona una medida de la distancia estándar entre X y μ.
            //Como siempre, una puntuación Z positiva indica una media muestral mayor que μ y una puntuación Z negativa corresponde a una media muestral menor que μ.
      .col-12.text-center.py-3(data-aos="fade-left")
        h5 El valor numérico de la puntuación Z indica la distancia entre X y μ medida en términos del error estándar.
        

    Separador
    #t_1_5.titulo-segundo.color-secundario(data-aos="fade-right")
      h2 1.5 Estimación y prueba de hipótesis

    .bloque-texto-g.color-primario.p-3.p-sm-4.p-md-5.mb-5(data-aos="fade-down-right")
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/temas/tema1/tema1-99.png')})`}"
      )
      .bloque-texto-g__texto.p-4
        p.mb-0 Un área de preocupación en la estadística inferencial es la estimación del parámetro de población a partir de la estadística de la muestra; aquí es importante darse cuenta del orden. La estadística de muestra se calcula a partir de los datos de muestra y el parámetro de población se infiere (o estima) a partir de esta estadística de muestra:

    p.mb-5(data-aos="fade-left") Otra área de la estadística inferencial es la determinación del tamaño de la muestra. Es decir, qué tamaño de muestra debe tomarse para hacer una estimación precisa. En estos casos, las estadísticas no se pueden utilizar, ya que aún no se ha tomado la muestra.

    .row.justify-content-center.align-items-center.mb-5
      .col-12.col-md-8.mb-5.mb-lg-0(data-aos="fade-left")
        LineaTiempoD.color-primario
          .row(numero="1" titulo="Estimaciones puntuales")
            .col-12.mb-4.mb-md-0
              p.text-small Hay dos tipos de estimaciones que encontraremos: estimaciones puntuales y estimaciones de intervalo. La estimación puntual es el mejor valor individual. Un buen estimador debe satisfacer tres condiciones:
              ul.lista-ul.mb-2
                li.mb-0
                  i.fas.fa-check(style="color:#25FFFF")
                  | #[strong Insesgado:] el valor esperado del estimador debe ser igual a la media del parámetro.
                li.mb-0
                  i.fas.fa-check(style="color:#25FFFF")
                  | #[strong Consistente:] el valor del estimador se acerca al valor del parámetro a medida que aumenta el tamaño de la muestra.
                li.mb-0
                  i.fas.fa-check(style="color:#25FFFF")
                  | #[strong Relativamente eficiente:] el estimador tiene la varianza más pequeña de todos los estimadores que podrían usarse.
          .row(numero="2" titulo="Intervalos de confianza")
            .col-12.mb-4.mb-md-0
              p.text-small La estimación puntual va a ser diferente del parámetro de población porque debido al error de muestreo, y no hay forma de saber quién se acerca al parámetro real. Por esta razón, a los estadísticos les gusta dar una estimación de intervalo que es un rango de valores utilizados para estimar el parámetro. Un intervalo de confianza es una estimación de intervalo con un nivel de confianza específico. Un nivel de confianza es la probabilidad de que la estimación del intervalo contenga el parámetro. El nivel de confianza es 1-alfa y esta se encuentra dentro del intervalo de confianza.
          .row(numero="3" titulo="Error máximo de la estimación")
            .col-12.mb-4.mb-md-0
              p.text-small El error máximo de la estimación se indica con E y es la mitad del ancho del intervalo de confianza. El intervalo de confianza básico para una distribución simétrica se establece para que sea la estimación puntual menos el error máximo de la estimación es menor que el parámetro de población real que es menor que la estimación puntual más el error máximo de la estimación. Esta fórmula funcionará para medias y proporciones, porque usarán las distribuciones Z o T que son simétricas.
          .row(numero="4" titulo="Prueba de hipótesis")
            .col-12.mb-4.mb-md-0
              p.text-small Cuando evalúas una hipótesis, debes tener en cuenta tanto la variabilidad de tu muestra como el tamaño de la muestra. La prueba de hipótesis se usa generalmente cuando se comparan dos o más grupos. Por ejemplo, puede implementar protocolos para realizar la intubación en pacientes pediátricos en el entorno prehospitalario. Para evaluar si estos protocolos tuvieron éxito en mejorar las tasas de intubación, podría medir la tasa de intubación a lo largo del tiempo en un grupo asignado aleatoriamente a la capacitación en los nuevos protocolos y compararla con la tasa de intubación a lo largo del tiempo en otro grupo de control que no recibió capacitación en los nuevos protocolos.
              div.formulas.mb-3
                img(src='@/assets/curso/temas/tema1/tema1-101.svg', alt='')
              .cajon.color-acento-botones.p-4.mb-2
                p.text-small.mb-0 Cuando evalúas una hipótesis, debes tener en cuenta tanto la variabilidad de tu muestra como el tamaño de la muestra.  Con base en esta información, le gustaría hacer una evaluación de si las diferencias que ve son significativas o si es probable que se deba a la casualidad. Esto se hace formalmente a través de un proceso llamado prueba de hipótesis.
              div.formulas.mb-3
                img(src='@/assets/curso/temas/tema1/tema1-102.svg', alt='')
      .col-12.col-md-4.mb-5.mb-lg-0.d-none.d-sm-none.d-md-block(data-aos="fade-right")
        figure
          img(src='@/assets/curso/temas/tema1/tema1-100.svg', alt='')  


    .row.justify-content-center.align-items-center.mb-3
      .col-12(data-aos="fade-right")
        ul.lista-ul.mb-2
          li.mb-0
            i.fas.fa-play(style="color:#25FFFF")
            | Cinco pasos en la prueba de hipótesis:

    .row.mb-5.align-self-stretch.justify-content-center
      .col-sm-6.col-lg-2.col-md-4.mb-4.mb-lg-0
        .tarjeta--boton.color-acento-contenido.text-white--hover.p-3(style="height:100%")
          .row.justify-content-center.mb-3
            .col-7
              figure
                img(src='@/assets/curso/temas/tema1/tema1-103.svg', alt='')
          .text-small.text-center #[strong Especificar la hipótesis nula]

      .col-sm-6.col-lg-2.col-md-4.mb-4.mb-lg-0
        .tarjeta--boton.color-secundario.p-3(style="height:100%")
          .row.justify-content-center.mb-3
            .col-7
              figure
                img(src='@/assets/curso/temas/tema1/tema1-104.svg', alt='')
          .text-small.text-center #[strong Especificar la hipótesis alternativa]

      .col-sm-6.col-lg-2.col-md-4.mb-4.mb-lg-0
        .tarjeta--boton.color-primario.p-3(style="height:100%")
          .row.justify-content-center.mb-3
            .col-7
              figure
                img(src='@/assets/curso/temas/tema1/tema1-105.svg', alt='')
          .text-small.text-center #[strong Establecer el nivel de significación (α)]

      .col-sm-6.col-lg-2.col-md-4.mb-4.mb-lg-0
        .tarjeta--boton.color-acento-contenido.text-white--hover.p-3(style="height:100%")
          .row.justify-content-center.mb-3
            .col-7
              figure
                img(src='@/assets/curso/temas/tema1/tema1-106.svg', alt='')
          .text-small.text-center #[strong Calcule la estadística de prueba y el valor P correspondiente]
          
      .col-sm-6.col-lg-2.col-md-4.mb-4.mb-lg-0
        .tarjeta--boton.color-primario.p-3(style="height:100%")
          .row.justify-content-center.mb-3
            .col-7
              figure
                img(src='@/assets/curso/temas/tema1/tema1-107.svg', alt='')
          .text-small.text-center #[strong Esbozando una conclusión]

    .row.justify-content-center.align-items-center.mb-3
      .col-12(data-aos="fade-right")
        ul.lista-ul.mb-2
          li.mb-0
            i.fas.fa-play(style="color:#25FFFF")
            | Para ampliar la información sobre estos importantes pasos en la estimación y la prueba de hipótesis, se invita a revisar: 
    
    
    TabsA.color-acento-botones.mb-5
      .tarjeta.tarjeta--azul.p-4(titulo="Especifique la hipótesis nula")
        h4 Especifique la hipótesis nula 
        p La hipótesis nula (H0) es una declaración de ningún efecto, relación o diferencia entre dos o más grupos o factores. En los estudios de investigación, un investigador suele estar interesado en refutar la hipótesis nula.
        h5 Ejemplos
        ul.lista-ul.mb-2
          li.mb-0
            i.fas.fa-check(style="color:#7125C8")
            | No hay diferencia en las tasas de intubación entre las edades de 0 a 5 años.
          li.mb-0
            i.fas.fa-check(style="color:#7125C8")
            | Los grupos de intervención y control tienen la misma tasa de supervivencia (o la intervención no mejora la tasa de supervivencia).
          li.mb-0
            i.fas.fa-check(style="color:#7125C8")
            | No existe asociación entre el tipo de lesión y si el paciente recibió o no una vía intravenosa en el entorno prehospitalario.
      .tarjeta.tarjeta--azul.p-4(titulo="Especifique la hipótesis alternativa")
        h4 Especifique la hipótesis alternativa 
        p La hipótesis alternativa (HA) es la afirmación de que existe un efecto o diferencia. Esta suele ser la hipótesis que el investigador está interesado en probar. La hipótesis alternativa puede ser unilateral (solo proporciona una dirección, por ejemplo, inferior) o bilateral. A menudo, utilizamos pruebas de dos caras incluso cuando nuestra verdadera hipótesis es unilateral, porque requiere más evidencia en contra de la hipótesis nula para aceptar la hipótesis alternativa.
        h5 Ejemplos
        ul.lista-ul.mb-2
          li.mb-0
            i.fas.fa-check(style="color:#7125C8")
            | La tasa de éxito de la intubación difiere según la edad del paciente tratado (bilateral).
          li.mb-0
            i.fas.fa-check(style="color:#7125C8")
            | El tiempo hasta la reanimación de un paro cardíaco es menor para el grupo de intervención que para el control (unilateral).
          li.mb-0
            i.fas.fa-check(style="color:#7125C8")
            | Existe una asociación entre el tipo de lesión y si el paciente recibió o no una vía intravenosa en el entorno prehospitalario (bilateral).
      .tarjeta.tarjeta--azul.p-4(titulo="Establecer el nivel de significancia (α)")
        h4 Establecer el nivel de significancia (α)
        p El nivel de significancia (denotado por la letra griega alfa α) generalmente se establece en 0,05. Esto significa que hay 5% de probabilidad de que acepte su hipótesis alternativa cuando su hipótesis nula sea realmente cierta. Cuanto menor sea el nivel de significancia, mayor será la carga de la prueba necesaria para rechazar la hipótesis nula o, en otras palabras, para respaldar la hipótesis alternativa.
        div.formulas.mb-3
          img(src='@/assets/curso/temas/tema1/tema1-108.svg', alt='')
      .tarjeta.tarjeta--azul.p-4(titulo="Calcule la estadística de prueba y el valor P correspondiente")
        h4 Calcule la estadística de prueba y el valor P correspondiente
        p En otra sección presentamos algunas estadísticas de prueba básicas para evaluar una hipótesis. La prueba de hipótesis generalmente utiliza una estadística de prueba que compara grupos o examina asociaciones entre variables. Cuando se describe una sola muestra sin establecer relaciones entre variables, se suele utilizar un intervalo de confianza.
        .cajon.color-acento-contenido.p-4.mb-2
          p.mb-0 El valor p describe la probabilidad de obtener un estadístico de muestra tan o más extremo por casualidad solo si su hipótesis nula es cierta. Este valor p se determina en función del resultado de su estadística de prueba. Sus conclusiones sobre la hipótesis se basan en su valor p y su nivel de significancia.
        h5 Ejemplos
        ul.lista-ul.mb-2
          li.mb-0
            i.fas.fa-check(style="color:#7125C8")
            | #[strong Valor p = 0,01.] Esto sucederá 1 de cada 100 veces por pura casualidad si su hipótesis nula es cierta. No es probable que suceda estrictamente por casualidad.
          li.mb-0
            i.fas.fa-check(style="color:#7125C8")
            | #[strong Valor p = 0,75.] Esto sucederá 75 de cada 100 veces por pura casualidad si su hipótesis nula es cierta. Es muy probable que ocurra estrictamente por casualidad.

    .row.justify-content-center.align-items-center.mb-3
      .col-12(data-aos="fade-right")
        ul.lista-ul.mb-2
          li.mb-0
            i.fas.fa-play(style="color:#25FFFF")
            | Precauciones sobre los valores p 
      
    p.mb-5(data-aos="fade-right") El tamaño de la muestra afecta directamente su valor p. Los tamaños de muestra grandes producen valores p pequeños incluso cuando las diferencias entre los grupos no son significativas. Siempre debe verificar la relevancia práctica de sus resultados. Por otro lado, un tamaño de muestra demasiado pequeño puede provocar que no se identifique una diferencia cuando realmente existe. 

    .bloque-texto-g.color-primario.p-3.p-sm-4.p-md-5.mb-5(data-aos="fade-down-right")
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/temas/tema1/tema1-109.png')})`}"
      )
      .bloque-texto-g__texto.p-4
        p.mb-0 Se debe planificar el tamaño de la muestra con anticipación para tener  suficiente información de su muestra para mostrar una relación o diferencia significativa, si existe. Consulte el cálculo de un tamaño de muestra para obtener más información.


    .tarjeta--container.row.mb-5(data-aos="fade-down-right")
      .col-md.tarjeta.color-acento-contenido.px-5.py-3
        .row.justify-content-center.mb-4
          .col-6
            div.formulas.mb-3
              img(src='@/assets/curso/temas/tema1/tema1-110.svg', alt='')
        h4 Ejemplo 1
        p Las edades medias fueron significativamente diferentes entre los dos grupos (16,2 años frente a 16,7 años; p = 0,01; n = 1.000). ¿Es esta una diferencia importante? Probablemente no, pero el gran tamaño de la muestra ha dado como resultado un valor p pequeño.
      .col-md.tarjeta.color-acento-botones.px-5.py-3
        .row.justify-content-center.mb-4
          .col-6
            div.formulas.mb-3
              img(src='@/assets/curso/temas/tema1/tema1-110.svg', alt='')
        h4 Ejemplo 2
        p Las edades medias no fueron significativamente diferentes entre los dos grupos (10,4 años frente a 16,7 años; p = 0,40, n = 10). ¿Es esta una diferencia importante? Podría ser, pero debido a que el tamaño de la muestra es pequeño, no se puede determinar con certeza si se trata de una verdadera diferencia o simplemente sucedió debido a la variabilidad natural en la edad dentro de estos dos grupos.
      
    p.mb-5(data-aos="fade-right")  Si realiza una gran cantidad de pruebas para evaluar una hipótesis (lo que se denomina prueba múltiple), debe controlar esto en su designación del nivel de significancia o en el cálculo del valor p. Por ejemplo, si tres resultados miden la efectividad de un fármaco u otra intervención, tendrá que ajustar estos tres análisis.

    .row.justify-content-center.align-items-center.mb-3
      .col-12(data-aos="fade-right")
        ul.lista-ul.mb-2
          li.mb-0
            i.fas.fa-play(style="color:#25FFFF")
            | Sacar una conclusión

    .row.mb-3.align-self-stretch
      .col-12.col-md-12.mb-5.mb-lg-0(data-aos="fade-left")
        ul.lista-ul.mb-2.px-4
          li
            i.fas.fa-check(style="color:#AD84FF")
            | Valor p < = nivel de significancia (a) = >, rechaza su hipótesis nula a favor de su hipótesis alternativa. El resultado es estadísticamente significativo.
          li
            i.fas.fa-check(style="color:#AD84FF")
            | Valor p > nivel de significancia (a) = > no rechaza su hipótesis nula. El resultado no es estadísticamente significativo.

    .bloque-texto-a.color-primario.p-4.p-md-5.mb-5(data-aos="fade-down-right") 
      .row.m-0.align-items-center.justify-content-between
        .col-lg-12
          .bloque-texto-a__texto.p-4
            p La prueba de hipótesis no está configurada para que pueda probar absolutamente una hipótesis nula. Por lo tanto, cuando no se encuentra evidencia en contra de la hipótesis nula, no se puede rechazar la hipótesis nula. Cuando se encuentra evidencia suficientemente fuerte en contra de la hipótesis nula, se rechaza la hipótesis nula. Sus conclusiones también se traducen en una declaración sobre su hipótesis alternativa. Cuando presente los resultados de una prueba de hipótesis, incluya también las estadísticas descriptivas en sus conclusiones. Informe valores p exactos en lugar de un rango determinado. Por ejemplo, “La tasa de intubación difirió significativamente según la edad del paciente y los pacientes más jóvenes tienen una tasa más baja de intubación exitosa (p = 0,02)”. Aquí hay dos ejemplos más con la conclusión expresada de varias formas diferentes.


    .row.mb-5.align-self-stretch.justify-content-center
      .col-12.col-md-8.mb-5.mb-lg-0(data-aos="fade-left")
        .cajon.tarjeta--azul.p-4
          h5 Ejemplo
          p.mb-0 H0: no hay diferencia en la supervivencia entre el grupo de intervención y el de control.
          p.mb-0 HA: existe una diferencia en la supervivencia entre el grupo de intervención y el de control. 
          p.mb-0 α = 0,05: aumento del 20% en la supervivencia para el grupo de intervención; valor p = 0,002.
        .cajon.tarjeta--gris.p-4
          h5 Conclusión
          p.mb-0 Rechace la hipótesis nula a favor de la hipótesis alternativa.
          p.mb-0 La diferencia en la supervivencia entre el grupo de intervención y el de control fue estadísticamente significativa. Hubo un aumento del 20% en la supervivencia para el grupo de intervención en comparación con el control (p = 0,001).
      .col-12.col-md-4.mb-5.mb-lg-0.d-none.d-sm-none.d-md-block(data-aos="fade-right")
        figure
          img(src='@/assets/curso/temas/tema1/tema1-111.svg', alt='')  

    .row.mb-5.align-self-stretch.justify-content-center
      .col-12.col-md-4.mb-5.mb-lg-0.d-none.d-sm-none.d-md-block(data-aos="fade-right")
        figure
          img(src='@/assets/curso/temas/tema1/tema1-112.svg', alt='')  
      .col-12.col-md-8.mb-5.mb-lg-0(data-aos="fade-left")
        .cajon.tarjeta--azul.p-4
          h5 Ejemplo
          p.mb-0 H0: no hay diferencia en la supervivencia entre el grupo de intervención y el de control.
          p.mb-0 HA: existe una diferencia en la supervivencia entre el grupo de intervención y el de control.
          p.mb-0 α = 0,05: aumento del 5% en la supervivencia entre el grupo de intervención y el de control; valor p = 0,20.
        .cajon.tarjeta--gris.p-4
          h5 Conclusión
          p.mb-0 No rechace la hipótesis nula.
          p.mb-0 La diferencia en la supervivencia entre el grupo de intervención y el de control no fue estadísticamente significativa.
          p.mb-0 No hubo un aumento significativo en la supervivencia para el grupo de intervención en comparación con el control (p = 0,20).


    Separador
    #t_1_6.titulo-segundo.color-secundario(data-aos="fade-right")
      h2 1.6 Formulario de muestreo y estimación

    .bloque-texto-g.color-primario.p-3.p-sm-4.p-md-5.mb-5(data-aos="fade-down-right")
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/temas/tema1/tema1-113.png')})`}"
      )
      .bloque-texto-g__texto.p-4
        p.mb-0 Las fórmulas que se usan para calcular la media muestral y todas las demás estadísticas muestrales son ejemplos de fórmulas de estimación o estimadores. El valor particular que calculamos a partir de observaciones de muestra utilizando un estimador se denomina estimación. Por ejemplo, el valor calculado de la media muestral en una muestra determinada se denomina estimación puntual de la media poblacional. Las tres propiedades deseables de un estimador son:

    .row.mb-5.align-self-stretch.justify-content-center
      .col-md-6.col-lg.tarjeta--tabla.p-4
        .row.justify-content-center.mb-3
          .col-4
            img(src='@/assets/curso/temas/tema1/tema1-114.svg' alt='AvatarTop')
        h2.text-center Insesgado
        p.text-center Tu valor esperado es igual al parámetro que se está estimando.

      .col-md-6.col-lg.tarjeta--tabla.p-4
        .row.justify-content-center.mb-3
          .col-4
            img(src='@/assets/curso/temas/tema1/tema1-115.svg' alt='AvatarTop')
        h2.text-center Eficiencia
        p.text-center Tiene la varianza más baja en comparación con otros estimadores insesgados del mismo parámetro.

      .col-md-6.col-lg.tarjeta--tabla.p-4
        .row.justify-content-center.mb-3
          .col-4
            img(src='@/assets/curso/temas/tema1/tema1-116.svg' alt='AvatarTop')
        h2.text-center Coherencia
        p.text-center A medida que aumenta el tamaño de la muestra, el error muestral disminuye y las estimaciones se acercan al valor real.

    .row.justify-content-center.align-items-center.mb-5
      .col-md-11.col-lg-10.mb-4.mb-md-0(data-aos="fade-left")
        .tarjeta.color-primario.p-3
          .row.justify-content-around.align-items-center
            .col-3.col-sm-2.col-lg-1
              img(src="@/assets/curso/temas/pdf.svg")
            .col
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0
                  p.text-small #[strong En el Anexo 4 - Formulario de muestreo,] se puede encontrar una clasificación por tablas de fórmulas más utilizadas y necesarias para llevar a cabo todo lo relacionado a procesos de muestreo de datos.
                .col-sm-auto
                  a.boton.color-acento-botones(:href="obtenerLink('/downloads/anexo_4_formulario_de_muestreo.pdf')" target="_blank")
                    span Descargar
                    i.fas.fa-file-download

    Separador
    #t_1_7.titulo-segundo.color-secundario(data-aos="fade-right")
      h2 1.7 Probabilidad de sucesos compatibles e incompatibles

    .bloque-texto-g.color-primario.p-3.p-sm-4.p-md-5.mb-5(data-aos="fade-down-right")
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/temas/tema1/tema1-117.png')})`}"
      )
      .bloque-texto-g__texto.p-4
        p.mb-0 Dos o más eventos son compatibles, si pueden cumplirse simultáneamente; es decir, si tienen al menos un resultado común. Por el contrario, son incompatibles o mutuamente excluyentes y su intersección es el conjunto vacío Ø si se analiza el siguiente experimento de lanzar un dado. 


    .row.mb-4.align-self-stretch.justify-content-center
      .col-12.col-md-8.mb-5.mb-lg-0(data-aos="fade-left")
        p #[b Comencemos con el siguiente experimento:] tiramos un dado de seis caras y vemos cuál es el resultado. Consideremos los siguientes eventos A= {2, 3}, B= {1,2}, C= {5}.
        p Observamos que, si extraemos 2, luego A está satisfecho, así como B. Decimos que los eventos son compatibles, esto significa que pueden ocurrir simultáneamente. Por el contrario, los eventos B y C son incompatibles, ya que los dos no pueden suceder simultáneamente.
        .cajon.color-acento-contenido.p-4.mb-2
          p.mb-0 Para ver cuando dos eventos son compatibles o no, podemos observar que A y B tienen un elemento común: 2, por lo tanto, serán compatibles. De lo contrario, A y C no tienen ningún elemento común y, por tanto, son incompatibles. Expresamos esto diciendo que dos eventos A y B son compatibles si:
        div.formulas.mb-3
          img(src='@/assets/curso/temas/tema1/tema1-119.svg', alt='')
        p y, por el contrario, son incompatibles si:
        div.formulas.mb-3
          img(src='@/assets/curso/temas/tema1/tema1-120.svg', alt='')
      .col-12.col-md-4.mb-5.mb-lg-0.d-none.d-sm-none.d-md-block(data-aos="fade-right")
        figure
          img(src='@/assets/curso/temas/tema1/tema1-118.svg', alt='')  
        
    p.mb-4(data-aos="fade-down") Si tenemos tres o más eventos, decimos que son incompatibles de dos en dos si dos eventos son incompatibles (de manera similar, son compatibles de dos en dos si dos eventos son compatibles). En nuestro caso A, B y C no son incompatibles de dos en dos, ya que, aunque A y C, al igual que B y C son incompatibles, A y B son compatibles.

    .row.mb-5.align-self-stretch.justify-content-center
      .col-12(data-aos="fade-left")
        .cajon.color-acento-botones.p-4.mb-2
          h5 Eventos
          p.mb-0 A = {2,3} B = {1,2} C = {4,5} cumplen con lo siguiente: 
          p A y B son compatibles, y B y C son incompatibles, B Ո C = Ø
        
    .tarjeta--container.row.mb-5(data-aos="fade-down-right")
      .col-md.tarjeta.tarjeta--azul.px-5.py-3
        h5 Evento compatible
        .titulo-sexto.color-acento-botones
          p.titulo.pb-0.mb-0 #[b Figura 12.] #[i Eventos.] 
        div.formulas.mb-3
          img(src='@/assets/curso/temas/tema1/tema1-121.svg', alt='')
      .col-md.tarjeta.tarjeta--gris.px-5.py-3
        h5 Evento incompatible
        .titulo-sexto.color-acento-botones
          p.titulo.pb-0.mb-0 #[b Figura 13.] #[i Evento incompatible.] 
        div.formulas.mb-3
          img(src='@/assets/curso/temas/tema1/tema1-122.svg', alt='')
      

    Separador
    #t_1_8.titulo-segundo.color-secundario(data-aos="fade-right")
      h2 1.8 Cálculo de probabilidades y probabilidad condicionada

    .row.mb-5.align-self-stretch.justify-content-center
      .col-12.col-md-4.mb-5.mb-lg-0.d-none.d-sm-none.d-md-block(data-aos="fade-right")
        figure
          img(src='@/assets/curso/temas/tema1/tema1-123.svg', alt='')  
      .col-12.col-md-8.mb-5.mb-lg-0(data-aos="fade-left")
        p Una probabilidad es un modelo representado matemáticamente de un fenómeno aleatorio. Las probabilidades pueden ser marginales, conjuntas o condicionales.
        p Comprender sus diferencias y cómo manipularlas es clave para tener éxito en la comprensión de los fundamentos de las estadísticas.
        .row.justify-content-center.align-items-center.mb-3
          .col-12(data-aos="fade-right")
            ul.lista-ul.mb-2
              li.mb-0
                i.fas.fa-play(style="color:#25FFFF")
                | Cálculo de probabilidades de eventos compatibles e incompatibles
        p Se explicará cómo calcular la probabilidad de un evento aislado con la ley de Laplace y calcular la probabilidad de la unión de dos eventos cuando son compatibles y cuándo son incompatibles.

    .row.justify-content-center.align-items-center.mb-3
      .col-12(data-aos="fade-right")
        ul.lista-ul.mb-2
          li.mb-0
            i.fas.fa-play(style="color:#25FFFF")
            | Ley de Laplace:

    .row.justify-content-center.align-items-center.mb-5
      .col-12.mb-3(data-aos="fade-right")
        .cajon.tarjeta--azul.p-4 
          p No es más que la fórmula para calcular la probabilidad de que ocurra un evento aislado. Cuando en un experimento aleatorio, todos los eventos tienen la misma probabilidad de ocurrir, la probabilidad de que ocurra un evento A es:
          div.formulas.mb-3
            img(src='@/assets/curso/temas/tema1/tema1-124.svg', alt='')
          p En el numerador colocamos el número de casos favorables para que ocurra el evento A y en el denominador colocamos el número de eventos posibles. Por ejemplo, en un dado, ¿cuál es la probabilidad de obtener un 2?
      .col-12.mb-3(data-aos="fade-right")
        .cajon.tarjeta--gris.p-4 
          p En este caso, el número de casos favorables es 1, ya que el dado tiene solo un 2. El número de casos posibles es 6, que son los números que tiene un dado. Por lo tanto, la probabilidad de que salga un 2 se puede escribir como P(2) y es igual a:
          div.formulas.mb-3
            img(src='@/assets/curso/temas/tema1/tema1-125.svg', alt='')
      .col-12.mb-3(data-aos="fade-right")
        .cajon.tarjeta--gris.p-4 
          div.formulas.mb-3
            img(src='@/assets/curso/temas/tema1/tema1-126.svg', alt='')
          p Siendo 1 la probabilidad del evento seguro (siempre ocurrirá) y 0 es la probabilidad del evento imposible (nunca ocurrirá).


    .row.mb-5.align-self-stretch.justify-content-center.align-items-center
      .col-12.col-md-7.mb-5.mb-lg-0(data-aos="fade-left")
        p Cómo calcular la probabilidad de ocurrencia de A o B, si los eventos son incompatibles: Si A y B son dos eventos incompatibles, es decir, no pueden ocurrir al mismo tiempo, la probabilidad de que ocurra A o B será la suma de las probabilidades de que cada evento ocurra por separado.
        div.formulas.mb-3
          img(src='@/assets/curso/temas/tema1/tema1-128.svg', alt='')
        p La probabilidad de obtener una bola blanca es:
        div.formulas.mb-3
          img(src='@/assets/curso/temas/tema1/tema1-129.svg', alt='')
        p La probabilidad de obtener una bola negra es:
        div.formulas.mb-3
          img(src='@/assets/curso/temas/tema1/tema1-130.svg', alt='')
        p Por lo tanto, la probabilidad de obtener una bola blanca o una bola negra es:
        div.formulas.mb-1
          img(src='@/assets/curso/temas/tema1/tema1-131.svg', alt='')
        div.formulas.mb-3
          img(src='@/assets/curso/temas/tema1/tema1-132.svg', alt='')
      .col-12.col-md-5.mb-5.mb-lg-0.d-none.d-sm-none.d-md-block(data-aos="fade-right")
        figure
          img(src='@/assets/curso/temas/tema1/tema1-127.svg', alt='')  

          
    .row.mb-5.align-self-stretch.justify-content-center.align-items-center
      .col-12.col-md-4.mb-5.mb-lg-0.d-none.d-sm-none.d-md-block(data-aos="fade-right")
        figure
          img(src='@/assets/curso/temas/tema1/tema1-133.svg', alt='') 
      .col-12.col-md-8.mb-5.mb-lg-0(data-aos="fade-left")
        p Cómo calcular la probabilidad de que ocurra A o B, si los eventos son compatibles: si A y B son dos eventos compatibles, es decir, pueden ocurrir al mismo tiempo, entonces la probabilidad de que ocurran A o B será:
        div.formulas.mb-3
          img(src='@/assets/curso/temas/tema1/tema1-134.svg', alt='')
        p P (A ∩ B) dice: la probabilidad de que ocurran A y B.

    .bloque-texto-a.color-primario.p-3.mb-5(data-aos="fade-down-right") 
      .row.m-0.align-items-center.justify-content-between
        .col-lg-12
          .bloque-texto-a__texto.p-3
            p Esta vez, la suma de las probabilidades de que cada evento ocurra por separado debe restarse de la probabilidad de que los dos eventos ocurran al mismo tiempo. Por ejemplo, calcular la probabilidad de que al lanzar un dado el número obtenido sea par o que sea un 4. En este caso, el evento “obtener un número par” y el evento “obtener un 4” son compatibles, porque si obtenemos un 4 están sucediendo ambos eventos a la vez. Por lo tanto, la probabilidad de obtener 4 o un número par se calculará con la fórmula:


    .row.mb-5.align-self-stretch.justify-content-center.align-items-center
      .col-12.col-md-6.mb-5.mb-lg-0(data-aos="fade-left")
        div.formulas.mb-3
          img(src='@/assets/curso/temas/tema1/tema1-136.svg', alt='')
        p La probabilidad de obtener un número par es:
        div.formulas.mb-3
          img(src='@/assets/curso/temas/tema1/tema1-137.svg', alt='')
        p La probabilidad de obtener un 4 es:
        div.formulas.mb-3
          img(src='@/assets/curso/temas/tema1/tema1-138.svg', alt='')
        p La probabilidad de obtener un número par y un 4 es:
        div.formulas.mb-3
          img(src='@/assets/curso/temas/tema1/tema1-139.svg', alt='')
      .col-12.col-md-6.mb-5.mb-lg-0.d-none.d-sm-none.d-md-block(data-aos="fade-right")
        figure
          img(src='@/assets/curso/temas/tema1/tema1-135.svg', alt='')  

    .row.mb-5.align-self-stretch.justify-content-center.align-items-center
      .col-12.col-md-4.mb-5.mb-lg-0.d-none.d-sm-none.d-md-block(data-aos="fade-right")
        figure
          img(src='@/assets/curso/temas/tema1/tema1-140.svg', alt='') 
      .col-12.col-md-8.mb-5.mb-lg-0(data-aos="fade-left")
        p Solo hay una posibilidad entre 6 ya que 4 es el único número que cumple ambos eventos al mismo tiempo. Finalmente, la probabilidad de obtener un número par o 4 es:
        div.formulas.mb-3
          img(src='@/assets/curso/temas/tema1/tema1-141.svg', alt='')
        p Que la sustitución de cada término por su valor nos queda a nosotros:
        div.formulas.mb-3
          img(src='@/assets/curso/temas/tema1/tema1-142.svg', alt='')


    .row.justify-content-center.align-items-center.mb-3
      .col-12(data-aos="fade-right")
        ul.lista-ul.mb-2
          li.mb-0
            i.fas.fa-play(style="color:#25FFFF")
            | Probabilidad condicionada

            
    .bloque-texto-g.color-primario.p-3.p-sm-4.p-md-4.mb-5(data-aos="fade-down-right")
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/temas/tema1/tema1-143.png')})`}"
      )
      .bloque-texto-g__texto.p-4
        p.mb-0 En la teoría de la probabilidad, la probabilidad condicionada o condicional es una medida de la probabilidad de que ocurra un evento, dado que ya ha ocurrido otro evento (por suposición, presunción, afirmación o evidencia). Veamos: 

    .row.mb-5.align-self-stretch.justify-content-center.align-items-center
      .col-12.col-md-8.mb-5.mb-lg-0(data-aos="fade-left")
        p Si el evento de interés es A y se sabe o se supone que ocurrió el evento B, “la probabilidad condicional de A dado B “, o “la probabilidad de A bajo la condición B “, generalmente se escribe como P (A | B) y ocasionalmente PB(A). Esto también se puede entender como la fracción de probabilidad B que se cruza con A:
      .col-12.col-md-4.mb-5.mb-lg-0(data-aos="fade-right")
        figure
          img(src='@/assets/curso/temas/tema1/tema1-144.svg', alt='') 


    .row.mb-5.align-self-stretch.justify-content-center.align-items-center
      .col-12.col-md-8.mb-5.mb-lg-0(data-aos="fade-left")
        .row.justify-content-center.align-items-center.mb-3
          .col-12(data-aos="fade-right")
            ul.lista-ul.mb-2
              li.mb-0
                i.fas.fa-play(style="color:#25FFFF")
                | Por ejemplo…
        p La probabilidad de que una persona determinada tenga tos en un día determinado puede ser solo del 5%. Pero si sabemos o asumimos que la persona está enferma, es mucho más probable que esté tosiendo. Por ejemplo, la probabilidad condicional de que alguien no esté bien tosiendo podría ser del 75%, en cuyo caso tendríamos que P (Tos) = 5% y P (Tos | Enfermo) = 75%. Aunque, no tiene que haber relación o dependencia entre A y B, y no tienen que ocurrir simultáneamente. 
        .row.justify-content-center.align-items-center.mb-3
          .col-12(data-aos="fade-right")
            ul.lista-ul.mb-2
              li.mb-0
                i.fas.fa-play(style="color:#25FFFF")
                | Teniendo en cuenta que… 
        p P (A | B) puede o no ser igual a P (A) (la probabilidad incondicional de A). Si P (A | B) = P (A), entonces se dice que los eventos A y B son independientes: en tal caso, el conocimiento sobre cualquiera de los eventos no altera la probabilidad de los demás. P (A | B) (la probabilidad condicional de A dado B) típicamente difiere de P (B | A). 
      .col-12.col-md-4.mb-5.mb-lg-0.d-none.d-sm-none.d-md-block(data-aos="fade-right")
        figure
          img(src='@/assets/curso/temas/tema1/tema1-145.svg', alt='') 


    .row.mb-5.align-self-stretch.justify-content-center.align-items-center
      .col-12.col-md-4.mb-5.mb-lg-0.d-none.d-sm-none.d-md-block(data-aos="fade-right")
        .titulo-sexto.color-acento-botones
          p.titulo.pb-0.mb-0 #[b Figura 14.] #[i Ejemplo Probabilidad condicionada.] 
        figure
          img(src='@/assets/curso/temas/tema1/tema1-146.svg', alt='') 
      .col-12.col-md-8.mb-5.mb-lg-0(data-aos="fade-left")
        .row.justify-content-center.align-items-center.mb-3
          .col-12(data-aos="fade-right")
            ul.lista-ul.mb-2
              li.mb-0
                i.fas.fa-play(style="color:#25FFFF")
                | Por ejemplo…
        p Si una persona tiene fiebre del dengue, podría tener 90% de probabilidades de dar positivo en la prueba de la enfermedad. En este caso, lo que se está midiendo es que si ha ocurrido el evento B (tener dengue), la probabilidad de A (resultado positivo) dado que B ocurrió es del 90%: P (A | B) = 90%. Alternativamente, si una persona da positivo en la prueba del dengue, es posible que solo tenga 15% de probabilidades de tener esta rara enfermedad debido a las altas tasas de falsos positivos. 
        .row.justify-content-center.align-items-center.mb-3
          .col-12(data-aos="fade-right")
            ul.lista-ul.mb-2
              li.mb-0
                i.fas.fa-play(style="color:#25FFFF")
                | En este caso… 
        p La probabilidad del evento B (tener dengue) dado que el evento A (resultado positivo) que ha ocurrido es 15%: P (B | A) = 15% Ahora debería ser evidente que igualar falsamente las dos probabilidades puede conducir a varios errores de razonamiento, lo que comúnmente se ve a través de falacias de tasa base.


    .row.mb-5.align-self-stretch.justify-content-center.align-items-center
      .col-12.col-md-8.mb-5.mb-lg-0(data-aos="fade-left")
        .row.justify-content-center.align-items-center.mb-3
          .col-12(data-aos="fade-right")
            ul.lista-ul.mb-2
              li.mb-0
                i.fas.fa-play(style="color:#25FFFF")
                | Si bien las probabilidades condicionales pueden proporcionar información extremadamente útil…
        p A menudo se proporciona o se dispone de información limitada. Por lo tanto, puede ser útil revertir o convertir una probabilidad de condición usando el teorema de Bayes:
        div.formulas.mb-3
          img(src='@/assets/curso/temas/tema1/tema1-148.svg', alt='')
        p Otra opción es mostrar probabilidades condicionales en una tabla de probabilidad condicional para iluminar la relación entre eventos.
      .col-12.col-md-4.mb-5.mb-lg-0.d-none.d-sm-none.d-md-block(data-aos="fade-right")
        figure
          img(src='@/assets/curso/temas/tema1/tema1-147.svg', alt='')


    Separador
    #t_1_9.titulo-segundo.color-secundario(data-aos="fade-right")
      h2 1.9 Combinatoria: variaciones, permutaciones y combinaciones

    p.mb-3(data-aos="fade-right") La combinatoria se ocupa de conjuntos finitos y sus objetos básicos son permutaciones, variaciones y combinaciones (y se refieren tanto a las operaciones como a los resultados de estas operaciones). Dado que siempre es posible identificar m y n elementos conjuntos con los conjuntos {1, 2, …, m} y {1, 2, …, n}, es suficiente considerar estos conjuntos, y esta situación es una a uno estándar. Recordamos estas tres nociones (en sus dos apariencias: cuándo se permiten las repeticiones y cuándo no). 
    p.mb-5(data-aos="fade-right") Esto se hace comenzando con variaciones sin repeticiones (validando esta decisión por una relación directa con la cardinalidad de todos los mapas finitos), aunque se podría comenzar con combinaciones o con permutaciones. Al cumplir con la permutación, hay que prestar una especial atención a las operaciones con factorial.

    .row.justify-content-center.align-items-center.mb-5
      .col-md-11.col-lg-10.mb-4.mb-md-0(data-aos="fade-left")
        .tarjeta.color-primario.p-3
          .row.justify-content-around.align-items-center
            .col-3.col-sm-2.col-lg-1
              img(src="@/assets/curso/temas/pdf.svg")
            .col
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0
                  p.text-small #[sttrong En el Anexo 5 - Combinatoria - Variaciones, permutaciones y combinaciones,] se encuentran las respectivas fórmulas para un caso determinado y su respectivo ejemplo. 
                .col-sm-auto
                  a.boton.color-acento-botones(:href="obtenerLink('/downloads/anexo_5_combinatoria_variaciones_permutaciones_y_combinaciones.pdf')" target="_blank")
                    span Descargar
                    i.fas.fa-file-download
    




</template>

<script>
export default {
  name: 'Tema1',
  components: {},
  data: () => ({
    // variables de vue
    indicadorTarjetaSlide: true,
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
