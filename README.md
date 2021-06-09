# Laboratorio 2

__1. Objetivos__

Objetivos Generales 
* Explicar y demostrar experimentalmente la Ley de Kirchhoff de Voltajes y la Ley de
Kirchhoff de Corrientes.

Objetivos Específicos 
* Comprobar experimentalmente el análisis de mallas.
* Comparar los valores obtenidos experimentalmente, con los obtenidos del cálculo aplicando las leyes de Kirchhoff.
* Afianzar experimentalmente las leyes de conservación de la energía eléctrica
* Verificar las leyes de Kirchhoff: Ley de Mallas y Ley de Nodos.

__2. Marco Teórico__ 

![](https://github.com/ItzAdoc/Imagenes_L2/blob/main/Marco.PNG)


__3. Explicación del Procedimiento__

1. Se crea el circuito en un software, en este caso proteus.
![](https://github.com/ItzAdoc/Imagenes_L2/blob/main/Circuito.PNG)
2. Se mide las intensidades en cada malla con un amperímetro en serie y se anota en la tabla.
![](https://github.com/ItzAdoc/Imagenes_L2/blob/main/Medidas.PNG)

3. Se determina el sentido de corriente de cada una de las mallas. 
![](https://github.com/ItzAdoc/Imagenes_L2/blob/main/Sentido.PNG)

4. Se usa ley de Kirchhoff para plantear las ecuaciones de cada una de las mallas. 

Primero se deja todo en las mismas unidades, en este caso todas las resistencias en  kΩ y luego se analizan las mallas.
![](https://github.com/ItzAdoc/Imagenes_L2/blob/main/1.PNG)
![](https://github.com/ItzAdoc/Imagenes_L2/blob/main/2.PNG)

5. Se resuelve el sistemas de ecuaciones en este caso por Regla de Cramer.

![](https://github.com/ItzAdoc/Imagenes_L2/blob/main/Ecu.PNG)

* Se saca el determinante del sistema a partir de los coeficientes con la regla de Sarrus, la cual nos dice que dupliquemos las 2 primeras filas y se las ubica después de la última fila. Lugo se multiplica en diagonal, los productos de las líneas rojas se restan con los productos de las líneas azules.
 
![](https://github.com/ItzAdoc/Imagenes_L2/blob/main/3.1.PNG)

Luego para sacar el determinante de la primera incógnita en este caso I1, se reemplaza los términos independientes en la columna donde va I1, las 2 columnas restantes se mantienen y se resuelve con Sarrus.

![](https://github.com/ItzAdoc/Imagenes_L2/blob/main/3.2.PNG)

Se hace lo mismo que en I1 con I2 y I3 
![](https://github.com/ItzAdoc/Imagenes_L2/blob/main/4.PNG)

Por último con todos los datos se reemplaza en las fórmulas para obtener los valores de las 3 corrientes.

![](https://github.com/ItzAdoc/Imagenes_L2/blob/main/5.PNG)

Los valores negativos de las respuestas señala que los sentidos de la corriente son al contrario. 

__4. Respuesta a Interrogantes y Calculo de Error__

2.5.2. Mida cada una de las corrientes de malla y anote los resultados en la tabla 2.1.

![](https://github.com/ItzAdoc/Imagenes_L2/blob/main/Medidas.PNG)

2.5.3. Simule en el software Multisim, Proteus, o cualquier otro simulador, el circuito
de la figura 2.1, obteniendo los valores de las corrientes de malla. Anote los resultados
en la tabla 2.1.
![](https://github.com/ItzAdoc/Imagenes_L2/blob/main/Medidas.PNG)

2.5.4. Compare los valores de la tabla 2.1 y realice sus conclusiones.

Tabla 2.1. Resultados obtenidos para el circuito de la figura 2.1.
![](https://github.com/ItzAdoc/Imagenes_L2/blob/main/tablaA.PNG)

Cálculo de Error

![](https://github.com/ItzAdoc/Imagenes_L2/blob/main/error.PNG)

__5. Video__


__6. Coclusiones__ 
* Existe un pequeño porcentaje de error en cuanto las corrientes halladas  analíticamente con las medidas en la práctica, pero es debido a que en la analítica se ignoran muchos decimales en el proceso.
* La ley de nodos se cumple en ambos casos del circuito.
* La ley de mallas se cumplió con los valores experimentales del circuito.
* La ley de nodos está relacionada en la ley de la conservación de la carga así como la ley de mallas está relacionada con la ley de la conservación de la energía.
* 
__7. Bibliografía__
* *Las leyes de Kirchhoff (artículo). (s. f.).* Khan Academy. Recuperado 2 de junio de 2021, de https://es.khanacademy.org/science/physics/circuits-topic/circuits-resistance/a/ee-kirchhoffs-laws
*  *El método de la corriente de malla (artículo).* (s. f.). Khan Academy. Recuperado 9 de junio de 2021, de https://es.khanacademy.org/science/electrical-engineering/ee-circuit-analysis-topic/ee-dc-circuit-analysis/a/ee-mesh-current-method
