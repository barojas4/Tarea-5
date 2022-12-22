                                                        UNIVERSIDAD DE LAS FUERZAS ARMADAS - ESPE
                                                                ELECTRICA Y ELECTRONICA

Nombre: Brayan Rojas

NRC: 10067

MATERIA: Fundamentos de Circuitos Electricos 

## 1.Objetivos


* Objetivo General

Analizar los distintos métodos de ramas, lazos, voltajes nodos y electromagnetismo mediante el libro de Floyd "Principios de circuitos eléctricos" 


* Objetivos especificos

Resumir el capitulo nueve y diez en organizadores gráficos del libro de Floyd "Principios de Circuitos Eléctricos", para comprender los temas descritos en el objetivo general 

Definir de manera correcta cada ecuación que vayamos a utilizar para resolver el sistema de ecuaciones en cada uno de los ejercicios de tevenin y norton

Aplicar los conocimientos adquiridos en ánalisis de ramas,lazos y nodos propuestos en el libro de Floyd

## 2.Marco Teorico (Resumen)

## 3. Explicacion y resolución de ejercicios

1. Con el método de sustitución, resuelva el siguiente conjunto de ecuaciones para IR1 e IR2.

![image](https://user-images.githubusercontent.com/116810935/209013918-fb46566a-0c1f-4a2c-a5ae-e41f87c3752c.png)

![image](https://user-images.githubusercontent.com/116810935/209015258-529a2930-3f4c-4693-b714-68fa73cf7c8a.png)

3. Utilizando determinantes, resuelva el siguiente conjunto de ecuaciones para ambas corrientes:

![image](https://user-images.githubusercontent.com/116810935/209015455-4e95b0bb-9932-4907-a299-74f706c3806b.png)

![image](https://user-images.githubusercontent.com/116810935/209016005-ab000944-b0b2-4414-b6b2-5c2b7c72c913.png)

5. Evalúe cada uno de los determinantes:

![image](https://user-images.githubusercontent.com/116810935/209017248-67cab316-f461-4ffe-a7e9-c2e7eef3122f.png)

![image](https://user-images.githubusercontent.com/116810935/209017286-f11cee00-f032-40ee-a940-1f31139d03aa.png)

![image](https://user-images.githubusercontent.com/116810935/209018428-459a5801-7626-456a-87be-8112a758e1ed.png)

7. Resuelva para I1, I2,I3 en el siguiente conjunto de ecuaciones con determinantes:

![image](https://user-images.githubusercontent.com/116810935/209020188-cccbdba2-af4a-4e9d-a34d-81f229978a24.png)

![image](https://user-images.githubusercontent.com/116810935/209020634-498ea92d-72de-4180-9674-c3bf01048d17.png)

![image](https://user-images.githubusercontent.com/116810935/209020652-f4bc0274-2325-4492-8903-0472791a0916.png)

![image](https://user-images.githubusercontent.com/116810935/209020695-db5020bb-fdee-41d3-a33c-3b09458e5b4c.png)

![image](https://user-images.githubusercontent.com/116810935/209020715-64fbcd81-1650-43ad-b6dd-da62924081f4.png)

9. Resuelva las dos ecuaciones simultáneas del problema 1 con su calculadora.

![image](https://user-images.githubusercontent.com/116810935/209020888-dbd4b28d-2292-46c1-9b3e-a4660f994902.png)

11. Escriba la ecuación de la corriente de Kirchhoff para la asignación de corriente mostrada en el nodo A
en la figura 9-26.

![image](https://user-images.githubusercontent.com/116810935/209021168-cd15056f-b89c-4d77-a3d2-480863b2535b.png)

Respuesta: I1 - I2 - I3 = 0

13. Determine la caída de voltaje entre los extremos de cada resistor mostrado en la figura 9-26 e indique
la polaridad real.

![image](https://user-images.githubusercontent.com/116810935/209022089-97597374-8720-470b-a92c-6919ba3e4df9.png)

Ecuación
R1I1 + R2I2 - Vs1 = 0
R2I2 + R3I3 - Vs2 = 0
I1 - I2 + I3 = 0

Reemplazando
8.2I1 + 10I2 = 12
10I2 + 5.6I3 = 6
I1 - I2 + I3 = 0

![image](https://user-images.githubusercontent.com/116810935/209022342-57cf3191-3e5d-481f-acdc-3a847bcb2317.png)

I1 = 0.692
I3 = 0.6329
I4 = -0.0587

Usando la ley de ohm para encontrar los voltajes V = IR
V1 = 8.2(0.692)
V1 = 5.66V

V2 = 10(0.6329)
V2 = 6.33V

V3 = 5.6(-0.0587)
V3 = 325mV

15. En la figura 9-27, determine el voltaje entre las terminales de la fuente de corriente (puntos A y B). 

![image](https://user-images.githubusercontent.com/116810935/209021411-d99ef15e-a892-46e3-b16e-06618576f470.png)

V = I/R

V = 100/68

V = -1.84V

17. Con el método de la corriente en lazos, determine las corrientes en los lazos que aparecen en la figura 9-28.

![image](https://user-images.githubusercontent.com/116810935/209022834-a8ab5451-26db-457d-a09f-d2bcb01f511b.png)

Ec 1)

1000I1 + 560I1 - 560I2 = -6

1560I1 - 560I2 = -6

Ec 2)

560I2 -560I1 +820I2 = -2

-560I1 + 1380I2 = -2

![image](https://user-images.githubusercontent.com/116810935/209023180-82d289f5-16ec-41c3-9959-b9731f3c4b89.png)

Respuestas obtenidas transformadas a decimal

I1 = -511 mA

I2 = -3.52 mA

19. Determine los voltajes y sus polaridades apropiadas en cada uno de los resistores mostrados en la figura 9-28.

![image](https://user-images.githubusercontent.com/116810935/209023370-63f8297c-ec78-4bb6-b1c0-657c6a34e9c6.png)


∑Vs =∑Vx

Siendo Vx = I * Rx

∑Vs =∑[I*Vx ]

Desarrollo

-2-4=1000 Ω I1+560Ω I1-560 I2

-6 V=1560Ω I1-560 I2

Hallar para la otra ecuación

+4- 6=-820 Ω I2+560Ω I2-560 I1

-2 V=1380Ω I2-560 I1

![image](https://user-images.githubusercontent.com/116810935/209023180-82d289f5-16ec-41c3-9959-b9731f3c4b89.png)

Respuestas obtenidas transformadas a decimal

I1 = -511 mA

I2 = -3.52 mA

1) 1000 Ω : Vx = (-0.00511 A) * (1000 Ω) = -5.11 V

2) 820 Ω : Vx = (-0.00352 A) * (820 Ω) = -2.8864 V

3) 1000 Ω : Vx = (-0.00511 A + 0.00352 A ) * (560 Ω) = -0.89 V

21. Resuelva para las corrientes de lazo en la figura 9-29 con su calculadora.

![image](https://user-images.githubusercontent.com/116810935/209024003-62bc6f9f-75f6-4a2c-965b-fecdfa64fd85.png)

Ley de voltaje de Kirchoff

∑Vs =∑Vx

Vx = I * Rx

∑V_s =∑[I*Vx ]

1.5 V=47 Ω IA+10 Ω IA-10 IB

Ec1: 1.5 V=57 Ω IA-10 IB

-3 V=27 Ω IB+10 Ω IB-10Ω IA+4.7Ω IB-4.7Ω IC

Ec 2: -3 V=41.7 Ω IB-10Ω IA-4.7Ω IC

3 V-1.5 V=15 Ω IC+4.7 Ω IC-4.7Ω IB

Ec 3: 1.5 V=19.7 Ω IC-4.7Ω IB


![image](https://user-images.githubusercontent.com/116810935/209024536-b453facf-3d37-44f9-931e-05d91bd6ec66.png)


Respuesta: 

IA = 0.0155 A

IB = -0.0613 A 

IC = 0.0615 A

23. Determine el voltaje entre las terminales del puente abierto, A y B, en la figura 9-30.

![image](https://user-images.githubusercontent.com/116810935/209024718-b905ae2d-4d9c-431f-9f37-b8424f31e4ac.png)

Ley de voltajes de Kirchhoff

∑Vs =∑Vx

Vx = I * Rx

∑V_s =∑[I*Vx ]

Ec 1)

8V=10Ω I1+4.7Ω I1+2.2Ω I1-4.7ΩI2-2.2ΩI2

8V=16.9Ω I1-6.9 Ω I2

Ec 2)

0V=-4.7Ω I1-2.2Ω I1+4.7ΩI2+2.2ΩI2+8.2 ΩI2+3.9 ΩI2

0V=-6.9 Ω I1+19 ΩI2


![image](https://user-images.githubusercontent.com/116810935/209025436-f48e4e89-aaac-4c3e-9610-c16cffd54529.png)


I1 = 0.57 A

I2 = 0.202 A


VA = 0.0202 A * (4.7Ω+2.2Ω) = 0.139 V


VB = 0.0202 A *(8.2 Ω+ 3.9 Ω) = 0.24 V

25. Escriba las ecuaciones de lazo en la forma estándar para el circuito puente T mostrado en la figura 9-31. 

![image](https://user-images.githubusercontent.com/116810935/209029555-17202680-ce9b-4aed-a7aa-08e6dcf36ed9.png)

Utilizamos la ley de voltajes de Kirchhoff

∑Vs =∑Vx

Vx = I * Rx

∑V_s =∑[I*Vx ]

Ec 1)
0 V=680 Ω IA+3300Ω IA-3300Ω IB+1500 Ω IA-1500 Ω IC

 0 V=5480 Ω IA-3300 IB-1500 Ω IC
Ec 2)

15 V=-3300 Ω IA+3300Ω IB+820Ω IB-820 Ω IC

15 V=-3300 Ω IA+4120Ω IB-820 Ω IC

Ec 3)

0 V=-1500 Ω IA-820Ω IB+1500 Ω IC+820 Ω IC+2200 Ω IC

0 V=-1500 Ω IA-820Ω IB+4520 Ω IC


![image](https://user-images.githubusercontent.com/116810935/209029998-180c218b-0202-4654-8f2e-34b7d7afe602.png)

![image](https://user-images.githubusercontent.com/116810935/209030166-297eb3b4-9e0f-4062-8d7f-bec7678995d9.png)

Respuestas:

IA = 0.0076 A

IB = 0.0106 A

IC= 0.0044 A

27. ¿Cuáles son los valores de corriente de rama en la figura 9-32? En cada rama, muestre la dirección real
de la corriente. 

![image](https://user-images.githubusercontent.com/116810935/209031313-1d33c9b6-4018-4bc6-8977-f3556307553f.png)

∑Ixsalida=∑Ixentrada

Ix = Vs/Rx

Desarrollo

Habiendo un solo nodo habrá solo una ecuación

(40V-VA)/68Ω=(VA-30V)/82Ω+VA/(47Ω+100Ω)

(40 V)/68Ω-VA/68Ω=VA/82Ω-(30 V)/82Ω+VA/147Ω

-VA/82Ω-VA/147Ω-VA/68Ω=-(30 V)/82Ω-(40 V)/68Ω

-0.0337 VA=-665/697 V

VA=28.311 V

Cálculo de ramas

I1 = (40V-VA)/68Ω=(40V-28.311V)/68Ω = 0.17 A

I2 = (VA+30 V)/82Ω=(28.311V+30V)/82Ω = 0.71 A

I3 = VA/147Ω=28.311V/147Ω= 0.19 A

29. Use el análisis de nodos para determinar el voltaje en los puntos A y B con respecto a tierra en la figura 9-33.

![image](https://user-images.githubusercontent.com/116810935/209032753-ca781556-db8c-43d8-9717-f643b2d8d424.png)

Utilizar la ley de la corriente de Kirchhoff

∑Ixsalida=∑Ixentrada

Siendo Ix = Vs/Rx

Desarrollo

Habrá dos ecuaciones debido a que existen dos nodos

(9V-VA)/(56000 Ω)=VA/(27000 Ω)+(VA-VB)/(91000 Ω)

9V/(56000 Ω)-VA/(56000 Ω)=VA/(27000 Ω)+VA/(91000 Ω)-VB/(91000 Ω)

9V/(56000 Ω)=VA/(56000 Ω)+VA/(27000 Ω)+VA/(91000 Ω)-VB/(91000 Ω)

Primera ecuación: 9V/(56000 Ω)=(37 VA)/561600-VB/(91000 Ω)

(VA-VB)/(91000 Ω)+(4.5V-VB)/(33000 Ω)=(VB-15V)/(82000 Ω)

VA/(91000 Ω)-VB/(91000 Ω)+4.5V/(33000 Ω)-VB/(33000 Ω)=VB/(82000 Ω)-15V/(82000 Ω)

4.5V/(33000 Ω)+15V/(82000 Ω)=-VA/(91000 Ω)+VB/(82000 Ω)+VB/(91000 Ω)+VB/(33000 Ω)

La segunda ecuación: 18V/(56375 Ω)=-VA/(91000 Ω)+0.000053487 VB

Entonces

VA = 3.557 V

VB= 6.700 V

31. Use el análisis de nodos, el de lazos, o cualquier otro procedimiento para determinar las corrientes y
los voltajes en cada nodo desconocido en la figura 9-35.

![image](https://user-images.githubusercontent.com/116810935/209033703-44f6c92d-d2dc-4f33-99a9-e7c3217899e6.png)

Nodo A

(20-VA)/(10 000 Ω)=(VA+5.25V)/(8 000 Ω)+(VA-VB)/(12 000 Ω)

(-VA)/(10 000 Ω)+(-VA)/(8 000 Ω)+(-VA)/(12 000 Ω)=5.25V/(8 000 Ω)+VB/(12 000 Ω)+(-20V)/(10 000 Ω)

(37 00)/(12 Ω) VA+VB/(12 000 Ω)=(43 000V)/32Ω

Nodo B

VB/(4 000 Ω)=(VA-VB)/(12 000 Ω)+(VC+5.25 V)/(6 000 Ω)

VB/(10 000 Ω)+VB/(12 000 Ω)=VA/(12 000 Ω)+VC/(6 000 Ω)+5.25V/(6 000 Ω)

1100/(6 Ω) VB-VA/(12 000 Ω)-VC/(6 000 Ω)=5.25V/6000Ω

Nodo C

VC/(2 000 Ω)=(VC-VB)/(6 000 Ω)+(5.25V-VC)/(20 000 Ω)

VC/(2 000 Ω)-VC/(6 000 Ω)+VC/(20 000 Ω)=(-VB)/(6 000 Ω)+(-5.25V)/(20 000 Ω)

(17 00)/(6 Ω) VC-VB/(12 000 Ω)=+5.25V/(20 000Ω)

![image](https://user-images.githubusercontent.com/116810935/209034005-3db67a06-2674-4a41-a43a-e66e58977cfb.png)


![image](https://user-images.githubusercontent.com/116810935/209033968-2a660295-ce72-4893-8b91-fa7f5e2e46fd.png)


VA = 4.35 V

VB = 0.000006754 V

VC = 0.000000926 V

Nodo A **I1= (20-4.35V)/10000=0.001565 A

I2= (5.25V+4.35V)/8000= 0.0012A

I3= (4.35V-0.000006754V)/12000=0.001565 A

Nodo B **I1=0.000006754V/4000=0.000000002 A

I2= I3 del nodo A

I3=(0.00000096V+5.25V)/20000=0.0002625 A

Nodo C

I1=0.00000096V/2000=0.00000034 A

I2=(0.00000096V-0.000006754)/(6 000 Ω)=-0.00000001 A

I3=(5.25V-0.00000096V)/(20 000 Ω)=0.0002625 A

### SECCIÓN 10–1 El campo magnético

1. El área de sección transversal de un campo magnético se incrementa, pero el flujo no cambia. ¿La densidad
de flujo aumenta o disminuye?

La densidad disminuye por que si el flujo se mantiene constante el area transversal de un campo mágnetico se incrementa 

3. ¿Cuál es el flujo en un material magnético cuando la densidad de flujo es de 2500 x 10 ^-6 T y el área de sección transversal mide 150 cm^2?

![image](https://user-images.githubusercontent.com/116810935/209039544-2ff37810-e729-48b0-a18c-b27ad12b31d4.png)


5. Un imán permanente muy fuerte tiene un campo magnético de 100,000 uT. Exprese esta densidad de flujo en gauss. 


![image](https://user-images.githubusercontent.com/116810935/209042018-6a4247d7-1cd9-4769-ac1f-16548dbc0a36.png)


7. ¿Cuál es la permeabilidad relativa de un material ferromagnético cuya permeabilidad absoluta es de 750 x 10^-6 Wb/At-m?

![image](https://user-images.githubusercontent.com/116810935/209042341-d36fe6aa-9a83-4817-9209-66fd81ccf1ed.png)


9. ¿Cuál es la fuerza magnetomotriz en una bobina de 50 vueltas de hilo cuando hay 3 A de corriente a través de él?

![image](https://user-images.githubusercontent.com/116810935/209042982-680d1429-1989-432a-a905-d40caa8a5600.png)

11. (a) ¿Qué fuerza mueve el émbolo de imán cuando se activa un solenoide?


El émbolo es atraído hacia los topes (en un tira y afloja continuo) a través de la concentración del campo magnético que proporciona la fuerza mecánica para realizar el trabajo

 Respuesta: Campo Electromagnético



(b) ¿Qué fuerza hace que el émbolo de imán regrese a su posición de reposo?

Como el embolo se mueve hacia arriba o hacia abajo la fuerza que hace que ingrese a su posición de reposo es la fuerza del resorte

Respuesta: Resorte

13. ¿Qué ocasiona que la aguja instalada en un movimiento de d’Arsonval se deflexione cuando circula corriente a través de la bobina?

![image](https://user-images.githubusercontent.com/116810935/209043727-c37e7e3c-66bd-4b88-9144-024f78be742e.png)

Fuerzas producidas por la interacción del campo electromagnético y el campo magnético permanente


15. ¿Cómo se puede cambiar la densidad de flujo en la figura 10-44 sin alterar las características físicas del
núcleo?

![image](https://user-images.githubusercontent.com/116810935/209046055-78a78dbb-3a3a-4b51-9104-4fbdf45760e2.png)

Se podria cambiar la densidad del flujo cambiando la corriente 


17. Determine a partir de las curvas de histéresis mostradas en la figura 10-45 qué material tiene más retentividad.

![image](https://user-images.githubusercontent.com/116810935/209046323-b9178c2c-feae-4ae2-9bc7-74a753213a20.png)



La retentividad de un material representa el flujo máximo que puede ser retenido después de que el material ha sido magnetizado hasta la saturación y se indica mediante la relación de Br a Bsat

De este modo en la imagen el material que tiene más retentividad es el Materia A.


19. ¿Cuáles son los tres factores que determinan el voltaje en un conductor que se mueve en dirección perpendicular
al campo magnético?

Respuesta:

La longitud del conductor expuesta al campo

La intensidad del campo magnético

La velocidad de rotación del conductor

21. ¿Cómo complementa la ley de Lenz a la ley de Faraday?

Respuesta:

La ley de Faraday establece que un campo magnético cambiante induce un voltaje en una bobina que es directamente proporcional a la velocidad de cambio del campo magnético y al número de vueltas que haya en la bobina. La ley de Lenz hace referencia a la dirección fluye la corriente, y establece que la dirección siempre es tal que se opone al cambio de flujo que la produce.

De este modo la ley de Lenz complementa a la ley de Faraday definiendo la polaridad del voltaje inducido.

23. Explique el propósito del conmutador y de las escobillas en la figura 10-35. 

![image](https://user-images.githubusercontent.com/116810935/209047490-5b36d145-adfb-4096-b586-a057981f04c9.png)

Respuesta:

El ensamble de conmutador y escobillas conecta eléctricamente la espira al circuito externo.

Puesto que el conmutador proporcionar una conexión eléctrica entre las escobillas presentes y la escobilla se trata de elementos cuya finalidad es realizar la presión necesaria.

25. Suponga que se agrega otra espira, a 90 grados de la primera, al generador de cd del problema 24. Trace
una gráfica del voltaje contra el tiempo para mostrar cómo aparece el voltaje de salida. Sea de 10 V el
voltaje máximo. 

![image](https://user-images.githubusercontent.com/116810935/209047674-6845fdd3-a6a8-4920-974a-ce368c5d33b4.png)





































 ## 4. Video
 
 link del video: 
 
 ## 5.Conlusión 
 
 * En conclusión se tiene que un sistema de ecuaciones lineales es un conjunto de dos o más ecuaciones de primer grado, en el cual se relacionan dos o más incógnitas. Los cuales se pueden resolver por distintos metodos tales como matrices, metodo de determinantes, sustitucion, igualacion, suma y resta entre otros métodos.

* El método de análisis de mallas y nodos nos permite ver de manera simplificada el comportamiento de la corriente y voltaje de un circuito.
  
* Se realizo un trabajo eficiente que permite reconocer los conceptos de la electrónica fundamental, en beneficio del trabajo se logró definir formulas muy importantes.


## 6. Bibliografía

* Floyd, T.(2007). Principios de circuitos electricos(Octava edi). México Pearson
