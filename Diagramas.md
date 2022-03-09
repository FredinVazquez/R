<h1>Diagrama de tallo y hoja</h1>
<p>
  Función a usar: stem(), al parecer ya viene de forma nativa<hr><br>
  Es para representación gráfica de datos no agrupados, o sea variables cuantitativas.
  Ténica de recuento y ordenación de los datos, además de cómo se comportan los datos, muy útil para agrupar datos no agrupados, o sea hacer una representación en una tabla 
  de frecuencias.
  El diagrama de tallo y hoja permite clasificar un conjunto de datos de acuerdo a su expresión decimal de cada dato, por lo cual el modo de obtener dicho diagrama es diviendo el 
  número por decimales, si el número es 98 entonces el tallo es 9 y la hoja 8. Dentro de R las cosas se fácilitan más debido a que solo se necesita poner la variable que 
  contiene a los datos dentro de la función stem.
  <br><img src="./Images/12"><br>
  
</p>

<div>
  <h2>Cambiar la escala del diagrama<h2>
    <p>
      Existe otros parámetros para colocar en stem:
      <ul>
        <li>stem(variable, scale="número")<li>
        Yo entiendo este parámetro como que realiza una división, puesto que scale es para modificar la longitud de cada renglón, y podemos observar lo siguiente
        <br><img src="./Images/13"><br>
        
        Se observa como se hace una especie de partición de cada renglón, anteriormente el tallo een cada renglón iba de 2 en 2, ahora al aplicar un scale=2 hubo una especie de 
        partición por lo cual ahora renglón va de 1 en 1.
        
        Ahora, si aplicamos un scale=4 se tendría que tener que cada renglón va de 0.5 a 0.5, y es lo que se observa
        <br><img src="./Images/14"><br>
        
        <li>width<li>
        Hacce referencia al ancho de la parcela
        
        <li>atom</li>
        Es para modificar la tolerancia.
      </ul>
    Nota: los datos del diagrama pueden ser copiados
      </p>
</div>

<div>
  <h2>Diagrama de barras</h2>
  <p>
    Dentro de R la representación de esto se hace por medio de la función barplot()<hr><br>
    
    Es un diagrama empleado para la representación gráfica de variables cualitativas, aquellas en donde son cualidades o características que pueden ser medidas por medio de 
    números, no obstante no habrá una continuidad entre dichos valores lo cual se explica al tener en el daigrama las barras separadas, a diferencia de un histograma en donde
    las barras son juntas debido a la existencia de una continuidad entre los datos, o sea una variable cuantitativa para datos agrupados.
    La creación de este diagrama va de forma que en cada intervalo se va levantar un rectángulo hasta una marca el cual es la cantidad de datos que se tiene de cada cosa tratada,
    como el tipo de mascotas, religiones, marcas bebidas por mexicanos, etc.
    
    Las diagramas de barras deberían de diferentes colores debido a que representan frecuencias diferentes.
    
  <h2>Argumentos/parámetros en la función</h2>
   <p>
     Para poder realizar este diagrama en R se debe de contemplar que la función necesita de los siguientes parámetros:
     <ul>
       <li>nombre_variable</li>
       Aquí se va incorporar el nombre de la variable de la cual se quiere realizar el diagrama, de modo que entonces se tendrá que haber cargado o 
       escaneado dichos datos en una variable, es obligatorio que esté en la posición inicial.
       <li>xlab</li> 
       Este será la etiqueta que tendrá el eje 'x', de ahí viene el nombre de x label, de modo que será el nombre de la etiqueta 'x'.
       <li>ylab</li>
       También viene de y label, y es la etiqueta del eje 'y'.
       <li>main</li>
       Este es el título que llevará nuestro diagrama de barras
       <li>color</li>
       Será el color de las barras, por defecto si se coloca un solo color todas tendrán un solo color, en caso de querer varios se debe de colocar un vector con nombre de 
       colores: vector_colores<-c("blue","red","orange")
       Recoradndo que c es para Combinar valores en un vector o lista.
         
    </ul>
  Nota: las etiquetas y colores van escritos entre comillas debido a que son string. 
       
       Ejemplo realizado:<br>
       <br><img src="./Images/15"><br>
       
       Se observa que cada barra aparece sin nombre alguno, para que aparezca con un nombre será necesario asociar un vector con los valores, y esto se hace de la siguiente 
       forma: names(variable)<-c("Barra1","Barra2","Barra3") Se observa de nuevo el uso de c puesto que se trata de un vector
        <br><img src="./Images/16"><br>
  </p>
</div>
    

<h2>Referencias</h2
  <ul>
    <li>http://www.estadisticaparatodos.es/taller/graficas/tallos_hojas.html<li>
  </ul>
