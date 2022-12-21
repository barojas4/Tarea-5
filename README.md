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


































 ## 4. Video
 
 link del video: 
 
 ## 5.Conlusión 
 
 * En conclusión se tiene que un sistema de ecuaciones lineales es un conjunto de dos o más ecuaciones de primer grado, en el cual se relacionan dos o más incógnitas. Los cuales se pueden resolver por distintos metodos tales como matrices, metodo de determinantes, sustitucion, igualacion, suma y resta entre otros métodos.

* El método de análisis de mallas y nodos nos permite ver de manera simplificada el comportamiento de la corriente y voltaje de un circuito.
  
* Se realizo un trabajo eficiente que permite reconocer los conceptos de la electrónica fundamental, en beneficio del trabajo se logró definir formulas muy importantes.


## 6. Bibliografía

* Floyd, T.(2007). Principios de circuitos electricos(Octava edi). México Pearson
