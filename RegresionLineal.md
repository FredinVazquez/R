<h1>Regresión lineal usando R</h1>
<p>
  <img src="https://www.iartificial.net/wp-content/uploads/2018/12/ejemplo-error-cuadratico-medio2.png">
  <br><br>
  Lo primero a tener en cuenta es que se tiene el siguiente comportamiento gráfico dado por el modelo de regresión lineal dado por medio del siguiente modelo
  <br><hr>
  <h2>y = a + bx</h2>
  <hr><br>
  Tal que:
  <ul>
    <li>Variable dependiente es 'y'</li>
    <li>Variable independiente es 'x'</li>
    <li>El interceptor es 'a'</li>
    <li>La pendiente es 'b'</li>
  </ul>
  Aquí es necesario tener presenten la pregunta sobre ¿qué evento estará dependiendo del otro evento? Esto con la finalidad de identificar a las variables x & y.
  <hr><br>
  
  <h2>Comandos a usar - Linear Regression</h2>
  <ol>
    <li>lm(y~x)   ** Alt + 126**   Build Linear Model</li>
    <li>plot(x,y)     Función usada para dibujar puntos, marcadores, en un diagrama.</li>
    <li>abline(lm(y~x),col="_nombreColor_")      Es una función que puede ser usada para añadir rectas verticales, horizontales o rectas de regresión lineal a una gráfica.</li>    
    <li>cor(x,y)        Función usada para obtener el coeficiente de correlación y así conocer la medida de relación lineal entre los datos de las variables</li>
  </ol>
  
  <h3>Recordando los criterios de Coeficiente de correción</h3>
  <ul>
    <li>r = 1     Correlación positiva perfecta o directamente proporcional</li>
    <li> 0 < r < 1        Correlación positiva</li>
    <li>r = 0          No existe relación lineal</li>
    <li>-1 < r < 0        Correlación negativa</li>
    <li>r = -1         Correlación negativa perfecta o inversamente proporcional</li>
  </ul>
  <br>
  <img src="https://www.curriculumnacional.cl/614/articles-224433_imagen_01.png">
  <br>
  <h2>Interpretación del coeficiente de correlación lineal</h2>
  <br> <img src="https://i.pinimg.com/originals/35/5b/eb/355bebdea7ee98aa54d72ffc40f6e8cd.png"> <br>
  
  
  </p>
