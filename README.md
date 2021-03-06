# Informe-Circuitos
- Objetivos:

  1.- Objetivo General
   
     - Observar y estudiar las leyes de Kirchhoff con la ayuda de simuladores de circuitos electricos para expandir los conocimientos prácticos y teóricos.
     
  1.1.- Objetivos Específicos
   
     - Evidenciar que las leyes de voltaje y corriente de Kirchhoff son demostradas en la practica.
     
     - Analizar los margenes de errores que pueden presentarse en las mediciones de los voltajes y corrientes.
     
     - Demostrar la diferencia e importancia de la conexcion en paralelo y serie.
     
  2.- Marco Teórico   
     
![Diagrama en blanco](https://user-images.githubusercontent.com/76134214/102702370-ef436680-422f-11eb-9551-46e5a5d370a2.png)
   
   3.- Diagramas
   
   - Circuito General
   
   ![image](https://user-images.githubusercontent.com/76134214/102729920-af987f80-4300-11eb-9ece-5d53efa9d3b2.png)

   - Circuito Voltajes
   
   ![image](https://user-images.githubusercontent.com/76134214/102729927-b1fad980-4300-11eb-9de3-11b39391ea64.png)
   
   - Circuito Intensidades/Corriente
   
   ![image](https://user-images.githubusercontent.com/76134214/102729929-b45d3380-4300-11eb-80d7-d5b28da34e1c.png)
   
   4.- Material y Equipo requerido

   ![image](https://user-images.githubusercontent.com/76134214/102844939-792f3300-43da-11eb-84e0-ac18c8f02a5b.png)

   
   5.- Explicación
        - Realizar un circuito en Tinkercad
        
   1. Se ingresa a la plataforma Tinkercad, se crea una cuenta, a continuación en el apartado de circuitos seleccionar nuevo circuito.
        
   2. Se seleccionan los materiales que vamos a utilizar, una placa de pruebas, 5 resistencias, multimetros digitales y una fuente de voltaje.
        
   3. Se coloca el respectivo voltaje a la fuente de voltaje y el respectivo valor a las resistencias.
        
   4. Se conecta la fuente de voltaje al positivo y negativo de la placa de pruebas.
        
   5. Se procede a conectar la resistencia R1 al positivo de la fuente y del otro extremo se conecta la resistencia R2.
        
   6. Del extremo de la resistencia R2 se conecta la resistencia R5 y del extremo de esta hacia el negativo.
        
   7. La resistencia R3 se conecta a un punto comúm entre las resistencias R1 y R2 y del otro extremo de la resistencia R3 se conecta la resistencia R4.
        
   8. La resistencia R4 se conecta a un punto común de las resistencias R5 y R2.
        
   9. Finalmente se conecta el voltímetro y el amperímetro en cada resistencia.
        
       Una vez tomados los valores de cada resistencia se procedera a tabularlos en la tabla de voltajes e intensidad en la sección de "medido", con la ayuda de la ley de Ohm y la ley de Kirchhoff se procedera a sacar los valores calculados y se anotaran en la tabla en la sección correspondiente.
       
   - Tabla 1.1. Resultados obtenidos de voltaje y corriente, en cada elemento del circuito.
   
   ![image](https://user-images.githubusercontent.com/76134214/102844442-7b44c200-43d9-11eb-97da-cddb4f84f7f4.png)
   
   - Verifique si se cumple la Ley de Kirchhoff de Voltajes en cada trayectoria cerrada, considerando las elevaciones de voltaje con signo positivo y las caídas de voltaje con signo negativo. Anote los resultados en la tabla 1.2.
        
  Tabla 1.2. Verificación de la LVK.
     
  ![image](https://user-images.githubusercontent.com/76134214/102841870-bd6b0500-43d3-11eb-8a6c-a004e478b986.png)
  
  Compare los resultados medidos con los valores obtenidos al analizar el circuito analíticamente y concluya al respecto.
  
  Los resultados medidos y calculados en las trayectorias 1 y 2, presentan un mínimo margen de error, debido a que dentro del simulador Tinkercad los valores medidos
  ya son redondeados automaticamente delimitandose a maximo dos decimales; de esta forma al aplicar la ley de Kirchhoff para voltaje en los valores calculados, llega a aproximarse al cero absoluto pero presentando un porcentaje de -0.01% de error el cual no es muy amplio. Por otro lado en la trayectoria 3 al ser un circuito cerrado, tanto el valor calculado como medido seran los mismos, dando asi el cero absoluto.
  
  ![image](https://user-images.githubusercontent.com/76132461/102846072-13907600-43dd-11eb-956d-d290b722e801.png)
 
        
   - Verifique si se cumple la Ley de Kirchhoff de Corrientes en cada nodo, tomando con signo positivo las corrientes que entran al nodo y con signo negativo las que salen
del nodo. Anote los resultados en la tabla 1.3.

  Tabla 1.3. Verificación de la LCK.
  
  ![image](https://user-images.githubusercontent.com/76134214/102841701-741ab580-43d3-11eb-99dd-ac7e7d338b38.png)
  
  Compare los resultados medidos con los valores obtenidos al analizar el circuito analíticamente y concluya al respecto.
  
   
 
  Los resultados medidos y resultados calculados en el nodo 1 y en el nodo 2, tienen un mínimo margen de error, esto es debido a que en el caso de los resultados medidos el propio simulador redondea los valores, de esta forma cuando se realiza la ley de Kirchhoff para corriente, no se llega a un cero absoluto teniendo un error de -0.24%, mediante que en los resultados calculados, omitmimos muchos decimales los cuales son cruciales para tener el valor exacto y debido a esto se tiene un error del -0.19%, pero si se obtiene el valor de todos los decimales es muy probable que tengamos un resultado muy aproximado hacia el cero, de esa forma se comprueba la ley de Kirchhoff.
  
  ![image](https://user-images.githubusercontent.com/76132461/102841570-2c942980-43d3-11eb-9a22-c0e6354e5478.png)
   
   
   6.- Conclusiones
   
   * En el circuito serie se observó que la intensidad de la corriente era la misma para cada una de las resistencias, al contrario del voltaje el cual se calculo independientemente en cada una de ellas. A diferencia del circuito serie, en el circuito paralelo, se observo que la intensidad de corriente total se divide entre resistencias y nodos; en el caso del voltaje se dio el mismo valor en los extremos de cada resistencia.
   * En conclusión, las leyes de voltaje y de corriente de Kirchhoff se pueden evidenciar con un pequeño margen de error, esto debido por lo antes mencionado los cuales son los redondeos y decimales, igualmente se puede comprobar en los simuladores cada voltaje y corriente que fluye por cada elemento con el fin de tener en cuenta que en el simulador también puede tener ciertos errores, pero aun así se evidencia que se cumple la ley de Kircchoff.
   * En las tablas se pudo concluir que las leyes de Kirchhoff se están cumpliendo tanto con la corriente como con el voltaje, ya que las sumas de las corrientes que entran a un nodo son igual a la suma de las corrientes que salen del dicho nodo, mientras que el voltaje tiende a cero cuando se suman por trayectorias, demostrando de esta forma las leyes anteriormente mencionadas. 
   
   7.- Biografía
   
   - Floyd, T.L. (2007). Principios de circuitos eléctricos (Octava ed.)
   


   

