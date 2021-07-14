# Laboratorio4

Morales Carrillo Henry Dario, Flores Castillo Nicolas Fabian, Montenegro Aguilar Edwin Ivan.

1. OBJETIVOS

1.1. Objetivo General.

•	Demostrar correctamente el teorema de la superposición mediante la simulación del circuito planteado el cual se simulará y después comprobará teóricamente mediante los respectivos cálculos de manera que se logre entender completamente el tema y su funcionalidad dentro de la recolección de datos.

1.2. Objetivos Especificos.

•	Solucionar el circuito eléctrico planteado mediante el teorema de superposición y analizar el   comportamiento que tienen las fuentes independientes de voltaje y corriente cuando se aplica el teorema de superposición mediante la simulación online en la página web TikerCAD.

•	Verificar experimentalmente el teorema de superposición en el circuito eléctrico dado en la práctica haciendo uso de los conocimientos adquiridos previamente en otros laboratorios parala toma de medidas y cálculos correspondientes al laboratorio.

•	Identificar la importancia de la aplicación del teorema de superposición cuando se tiene más de una fuente de alimentación y determinar las ventajas y desventajas de la aplicación del teorema de superposición en los circuitos eléctricos. 

2. MARCO TEORICO

![WhatsApp Image 2021-07-14 at 02 01 17](https://user-images.githubusercontent.com/85144847/125585789-200f995b-05c9-4296-8d62-6349eacbe57c.jpeg)

3. EXPLICACION DEL LABORATORIO EN FORMA TEORICA


4. RESOLUCION DEL LABORATORIO EN FORMA MATEMATICA

•	Para el desarrollo de la siguiente presente lo primero que vamos a realizar es un análisis de los componentes eléctricos que tiene el siguiente circuito electrico, que tipo de circuito es, el teorema que vayamos a utilizar para su respectiva resolución y que es lo que nos pide encontrar.

![Captura de pantalla (1620)](https://user-images.githubusercontent.com/85144847/125577883-8502d84e-8437-4b3b-b321-d6f5fe2e302d.png)

•	Como hemos logrado apreciar el circuito es mixto (resistencias o fuentes conectadas en serie y paralelo) conformado por 4 resistencias tambien nos damos cuenta que existen dos fuentes de voltaje y por ultimo tenemos una placa de pruebas (Protoboard) en donde realizaremos las diferentes conexiones, los valores de cada resistencia que se encontraran en el circuito serán los siguientes: 

![Captura de pantalla (1619)](https://user-images.githubusercontent.com/85144847/125576673-036ca238-f7b0-4c93-8852-9060fba79fb6.png)

•	Para la presente practica el teorema que vamos a utilizar para su resolución es el de Superposición y para ello debemos tener algo muy en cuenta acerca del teorema y es que: 

El voltaje o corriente a través de cualquier elemento del circuito puede obtenerse sumando algebraicamente todos los voltajes o corrientes individuales generados por cada fuente actuando por sí sola, con todas las demás fuentes igualadas a cero.

•	Para la finalizacion del analisis del circuito electrico concluiremos que esta practica numero 4 nos pide encontrar Ix y VA del circuito señalado.

•	Desarrollo:

![image](https://user-images.githubusercontent.com/85144847/125579381-19bcf863-4775-436d-bc12-f3a89419f120.png)

4.1. Estableceremos dos casos de circuito el A y B esto con el fin de poder aplicar correctamente el teorema de superposición en cada caso una fuente estará cortocircuitada.

4.2. CASO A:

•	En este caso tomaremos solamente la fuente de 20 voltios y cortocircuitaremos la fuente de 12 voltios esto con la finalidad de una mejor apreciación y respectivo cálculo, al momento de realizar lo señalado todo lo que este conectado a dicha fuente se eliminara es decir dejara de pasar corriente eléctrica. 

![image](https://user-images.githubusercontent.com/85144847/125585264-3f5c7829-07f3-4883-b762-9c686f04bf76.png)

•	El circuito quedaría así quitando todo lo cortocircuitado.

![image](https://user-images.githubusercontent.com/85144847/125585321-3fde281f-fdb3-44e2-ad79-6c473932fe57.png)

•	Ahora resolviendo el circuito por resistencias equivalente nos queda

![Captura de pantalla (1632)](https://user-images.githubusercontent.com/85144847/125585447-1952d26c-39e8-4c80-bae4-897915f13c39.png)

•	Encontramos la intensidad total y voltaje VA del circuito 

![Captura de pantalla (1641)](https://user-images.githubusercontent.com/85144847/125627675-12199a6a-e946-4533-9757-0ddd76cb0e54.png)

•	Como podemos darnos cuenta en este caso Ix = 0 porque al momento de cortocircuitar la fuente de 12 voltios la resistencia de 470 ohmios por donde pasaba dicha corriente desapareció. 

4.3.	CASO B:

•	En este caso es igualito al anterior con la diferencia que ahora tomaremos solamente la fuente de 12 voltios y cortocircuitaremos la fuente de 20 voltios esto con la finalidad de una mejor apreciación y respectivo cálculo, al momento de realizar lo señalado todo lo que esté conectado a dicha fuente se eliminara es decir dejara de pasar corriente eléctrica. 

![image](https://user-images.githubusercontent.com/85144847/125589472-af006878-bab0-4978-a308-c4fd189af244.png)

•	El circuito quedaría así quitando todo lo cortocircuitado.

![image](https://user-images.githubusercontent.com/85144847/125589510-5ef029e4-f06a-4273-8624-1470d156cdc4.png)

![Captura de pantalla (1638)](https://user-images.githubusercontent.com/85144847/125589712-2777bc36-e620-4f65-847e-471d28a45dd3.png)

![Captura de pantalla (1639)](https://user-images.githubusercontent.com/85144847/125589717-b55d3b05-3ff6-4a39-bd64-ac3d38bbd0a2.png)

•	Encontramos la intensidad total y voltaje VA del circuito 

![Captura de pantalla (1642)](https://user-images.githubusercontent.com/85144847/125628792-910179a4-bfef-4cf9-a918-4e9cc270f8b2.png)

•	Como podemos darnos cuenta en este caso Ix = 25.53 mA porque al momento de cortocircuitar la fuente de 20 voltios la resistencia de 470 ohmios no se elimino y por donde pasa la corriente Ix es por esa resistencia.

• Por ultimo según el teorema de superposición procedemos a sumar o restar los resistores o voltajes que se calcularon en el Caso A y B para dar con un valor total que represente al mismo resistor dentro del circuito original.

![Captura de pantalla (1643)](https://user-images.githubusercontent.com/85144847/125632825-7b3d2356-940d-4818-b624-e625f325620c.png)

• Tabla de Medición de voltaje aplicando superposición.

![Captura de pantalla (1646)](https://user-images.githubusercontent.com/85144847/125634045-53d70b6b-4f1b-4ae8-8c76-904a17fba49d.png)

• Tabla de Medición de corriente aplicando superposición.

![Captura de pantalla (1648)](https://user-images.githubusercontent.com/85144847/125634659-89068a32-098c-4dc4-87d4-7a70be47e0f4.png)

5. VIDEO DE YOUTUBE


6. CONCLUSIONES

•	Tras realizar la práctica se corroboró el   método   de   superposición   de un circuito, donde se   especifica que se pueden hacer cortocircuitos o circuitos abiertos dependiendo si es una fuente de corriente o de voltaje respectivamente, donde la suma de cada calculo determinándolo para cada fuente será igual al voltaje o corriente total que circula por el circuito. 

•	Mediante la simulación pudimos entender e implementar de manera práctica el teorema de la superposición utilizando una sola fuente de alimentación para la toma de medidas requeridas y así poder verificar los sistemas de ecuaciones encontrados provenientes del circuito planteado, ya que nos permitió evaluar los datos proporcionados de cada una de las fuentes en las diferentes resistencias del sistema, para luego calcular estos datos y hallar valores significativos solicitados para la práctica. 

•	Se comprobó que los resultados obtenidos mediante el método de superposición son similares a los datos obtenidos en la simulación ya que el error porcentual se verá reflejado en la perdida de decimales, lo que causará que los resultados calculados tengan una pequeña variación de los obtenidos en la simulación del circuito.

7. BIBLIOGRAFIA

• Análisis de Circuitos – Robbins.pdf

• Cuaderno de circuitos eléctricos I – Ing. Wilmer Loza

• Cuaderno de Electrotecnia I – Ing. Wilmer Loza
