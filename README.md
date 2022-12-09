# LAB_No.3

![image](https://user-images.githubusercontent.com/117781491/206603670-ef0969de-36b0-4078-b665-a134bd12a43c.png)

Integrantes: Joel Oña, Cristian Toaquiza, Dylan Taco.

NRC: 10063

Sangolquí, 09 de Diciembre del 2022


                                                        PRACTICA-No.-3-ANALISIS DE NODOS
                                                        
                                                        
1.  OBJETIVOS

OBJETIVO GENERAL:

-  Comprobar experimentalmente el analisis de nodos mediante el puesto en marcha del circuito del laboratorio 3 para el perfecto conocimiento del tema.

OBJETIVOS ESPECIFICOS:

- Armar el circuito de forma fisica y virtual.
- Verificar si los voltajes obtenidos en cada nodo del circuito es igual o similar tanto de la forma analitica, fisica y simulada.
-  Aplicar la ley de Ohm y la la L.C.K para realizar el analisis de nodos.
-  Aplicar la teoria de nodos para simplificar las operaciones a realizar.

2. MARCO TEÓRICO

![image](https://user-images.githubusercontent.com/117781491/206720183-ef1ee358-7d6b-4aed-8e82-2962cc263c9e.png)


3. EXPLICACION DEL PROCEDIMIENTO

MATERIAL Y EQUIPO REQUERIDO

![image](https://user-images.githubusercontent.com/117781491/206606935-b3d5475b-03a2-49e1-a8cf-3f6341dc08ac.png)


Descripcion de equipo y material

- Protoboard: Un protoboard es una placa de pruebas se pueden insertar componentes electrónicos y cables en este se puede ensamblar un circuito sin la necesidad de soldar ningún componente.


![image](https://user-images.githubusercontent.com/117781491/206608929-78d594bc-a293-43e4-8c36-e7f5a02952f3.png)


- Resistores: Una resistencia se utiliza para introducir una resistencia eléctrica determinada entre dos puntos de un circuito eléctrico.

![image](https://user-images.githubusercontent.com/117781491/206608961-ae19f43f-55d2-4cf8-8731-a9f67cac70ef.png)


-  Fuente de voltaje: El elemento activo que puede transferir energía se llama fuente de voltaje, y hay dos tipos, uno puede generar una diferencia de potencial entre sus dos extremos y el otro proporciona corriente para que funcionen otros circuitos.

![image](https://user-images.githubusercontent.com/117781491/206609039-db0729c1-8dd5-4f95-8427-6700a5e168a9.png)


- Multímetro digital: Un multímetro digital es una herramienta que sirve para medir dos o más valores eléctricos se puede medir corriente, resistencias y voltaje.


![image](https://user-images.githubusercontent.com/117781491/206609282-7fef4cdd-04e0-4424-997d-c4df9f29e872.png)

Explicacion de los calculos analiticos para la obtencion de los voltajes en los nodos del circuito

a) En primer lugar identificamos el numero de nodos existentes en el circuito

![image](https://user-images.githubusercontent.com/117781491/206610203-31d9bfee-911b-4ebb-b518-604920b7cab7.png)

En  este caso existen 5 nodos, por lo tanto deberemos hallar el voltaje de esos 5 nodos.

NODO  1 y 4 : FANTASMA

NODO 2 y 3 : PRINCIPAL

NODO 5 : PRINCIPAL Y DE REFERENCIA

b) Despues ponemos  un nombre al voltaje que vamos a encontrar en cada nodo, y luego identificamos las corrientes que entran y salen en cada nodo, asi como el sentido en el que va la corriente para identificar las polaridades.


![image](https://user-images.githubusercontent.com/117781491/206611268-3f23b1c7-31a3-4a3d-bac1-109ca9a6db3c.png)

c) Una vez hecho esto, procedemos a  encontara el voltaje en cada nodo:

![image](https://user-images.githubusercontent.com/117781491/206612691-ece9ea73-19cb-4247-b20f-26320df3f6b6.png)

Como los nodos  1 y 4 son  del tipo fantasma , su voltaje sera igual a l valor de tension  que tiene la bateria o fuente de volatje a la que esta conectada .


![image](https://user-images.githubusercontent.com/117781491/206614075-3a31d3e1-8915-41e3-8334-f7361f7c3f96.png)


en el caso del nodo 5 ,  éste es del tipo principal y  de referencia  ya que  se encuentra mas cerca del polo negativo de la bateria y ademas  la mayoria  de componentes  se  unen en  este nodo, es por ello  que se le asigna un valor de cero voltios.


![image](https://user-images.githubusercontent.com/117781491/206614160-111a4018-e799-4189-a962-5dcd57d9a075.png)


![image](https://user-images.githubusercontent.com/117781491/206614211-ba44b285-2de7-4302-a12e-3f8194c1d797.png)

![image](https://user-images.githubusercontent.com/117781491/206614276-241bc1bc-c5db-4194-839c-0ff5b898e944.png)

![image](https://user-images.githubusercontent.com/117781491/206614305-779effdd-0e72-4a6f-831c-7f173cc6ab5a.png)


![image](https://user-images.githubusercontent.com/117781491/206614928-1f508902-b72f-45a7-b913-2c8e4c11a5a9.png)

Una vez que hemos encontardo los valores de Vb y Vc, podemos afirama los siguriente:

VOLTAJE DEL NODO 2:

![image](https://user-images.githubusercontent.com/117781491/206615314-e3c36b22-7380-40d3-a372-891ef4b76e38.png)

VOLTAJE DEL  NODO 3:

![image](https://user-images.githubusercontent.com/117781491/206615388-5a3c7d7e-837d-467c-b725-178912c24706.png)

![image](https://user-images.githubusercontent.com/117781491/206615420-d477dd97-74f8-4f0a-9498-0ad956743d63.png)


4. RESPUESTA A INTERROGANTES Y CÁLCULO DEL ERROR

4.1  Implemente  el circuito que se presenta en la figura 3.1.

![image](https://user-images.githubusercontent.com/117781491/206617459-947e3dbd-59d1-4fd4-98bc-f465aa156f61.png)

CICRCUITO ARMADO FISICAMENTE:

![image](https://user-images.githubusercontent.com/117781491/206720880-46ccf64b-fefc-4547-ac07-4eaccdc5267a.png)



4.2  Mida  cada uno de los voltajes de nodo y anote los resultados en la tabla 3.1.

4.3  Simule en el software Thinkercad, el circuito de la figura 3.1, obteniendo los valores de los voltajes de nodo. Anote los resultados en la tabla 3.1.

VOLTAJE DEL NODO 1:

![image](https://user-images.githubusercontent.com/117781491/206617729-a35e3008-2985-4359-abe9-da2bfaf2f906.png)

VOLTAJE DEL NODO 2:

![image](https://user-images.githubusercontent.com/117781491/206617818-dc2af893-034b-4732-b464-1bb845354ddb.png)

VOLTAJE DEL NODO 3:

![image](https://user-images.githubusercontent.com/117781491/206617854-07a049a3-ba4d-4d02-ae73-c4ac30d8f4dc.png)

VOLTAJE DEL NODO 4:

![image](https://user-images.githubusercontent.com/117781491/206617874-ae306dab-37d5-49a1-87c8-d79a3836c5f5.png)

VOLTAJE DEL NODO 5:

![image](https://user-images.githubusercontent.com/117781491/206617904-fed68277-6ae8-4bca-bda3-a45525a94970.png)


4.4 Compare los valores de la tabla 3.1 y realice sus conclusiones.

![image](https://user-images.githubusercontent.com/117781491/206618039-c3a2330c-1b3f-4781-8ff7-18de797a3193.png)

4.5 CALCULO DEL ERROR:

![image](https://user-images.githubusercontent.com/117781491/206618583-73c1c6f2-8a1e-412c-8fd2-da1755cb24b1.png)


5. VIDEO

Link del video:

https://youtu.be/VyHA3etxlH4

6. CONCLUSIONES

Mediante el presente laboratorio se llegó a concluir lo siguiente:

•	Para determinar el sentido por la cual circula corriente dentro de nuestro circuito es necesario ver la polaridad del mismo para saber las direcciones de las corrientes.

•	El número de nodos determina el número de ecuaciones que tendrá nuestro circuito.

•	El voltaje de referencia siempre va a tener un voltaje de cero al estar conectado a tierra.

•	Mediante la ley de Ohm la remplazamos en la ley de corriente de Kirchhoff, ya que en el método de nodos las variables son los voltajes, para asi trabajar de mejor manera.

•	Para verificar nuestro circuito debemos saber que por la ley e voltajes de Kirchhoff la suma de todas las caídas de voltajes es igual a cero.


7. BIBLIOGRAFÍA

Darwin, I. [@IngEDarwin]. (2019, junio 26). LEY DE KIRCHHOFF 

(NODOS) / EJERCICIO 1. Youtube. https://www.youtube.com/watch?v=KiKMwEG-l3I




                                                        
                                                        
                                                        
                                                        
