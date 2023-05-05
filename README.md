# **Modelo_ML_determinacion_comportamiento_clientes**

<p> La compañía móvil Megaline no está satisfecha al ver que muchos de sus clientes utilizan planes heredados. Quieren desarrollar un modelo que pueda analizar el comportamiento de los clientes y recomendar uno de los nuevos planes de Megaline: Smart o Ultra.</p>

<p> Se tiene acceso a los datos de comportamiento de los suscriptores que ya se han cambiado a los planes nuevos (del proyecto de Análisis estadístico de datos). </p>

<p>
Para esta tarea de clasificación se busca crear un modelo que escoja el plan correcto para cada usuario. 
</p>
 
 ## **Conclusión General**
 <p> 
La compañía móvil Megaline requería desarrollar un modelo capaz de analizar el comportamiento de los clientes y recomendar uno de los nuevos planes de Megaline: Smart o Ultra. 
</p>


<p> 
Para ello se realizaron pruebas con 3 modelos diferentes de clasificación, para poder determinar cual es ellos arrojó mejores resultados. Y así detemrinar basado en la data suministrada, cuales son los planes óptimos para cada usuario.</p>

### **Arbol de decisión**
<p>
El arbol de decisión en su mejor modelo consiguió una muy buena exactitud de 78.5381%, con una precisión 43.9153%, y una sensibilidad del 72.1739%, logrando un buen modelo, más no fué el elegido.
</p>

### **Bosque de árboles de decisón alreatorio**
<p>
Así mismo, empleando un bosque de árboles de decisón alreatorio que cuenta con 8 niveles de profundidad y 41 estimadores se logró obtener una exactitud de 80.7154%, con una precisión 48.6772%, y una sensibilidad del 77.3109%. Los cuales fueron valores excelentes para el objetivo que se quiere. Aunque un poco más lento nque la opción anterior, es razonable.
</p>

### **Regrsión logística**
<p>
Por último la regrasión logística dejo mucho que desear en este caso, con un 75.8942%, una presición de un 22.7513% y una sensibilidad elevada de un 82.6923% con lo cual se puede decir que no cumple como candidato para el caso de estudio
</p>


<p>
Es por ello que se optó por reentrenar el modelo empleando un bosque de árboles de decisón alreatorio el cual como se evidencia en la matriz de confusión tiene valores bastante buenos y nos permite recomendar correctamente a el plan a los clientes.
</p>
 
