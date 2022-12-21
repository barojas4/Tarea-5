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

Respuestas optenidas transformadas a decimal

I1 = -511 mA

I2 = -3.52 mA


 ## 4. Video
 
 link del video: 
 
 ## 5.Conlusión 
 
 * En conclusión se tiene que un sistema de ecuaciones lineales es un conjunto de dos o más ecuaciones de primer grado, en el cual se relacionan dos o más incógnitas. Los cuales se pueden resolver por distintos metodos tales como matrices, metodo de determinantes, sustitucion, igualacion, suma y resta entre otros métodos.

* El método de análisis de mallas y nodos nos permite ver de manera simplificada el comportamiento de la corriente y voltaje de un circuito.
  
* Se realizo un trabajo eficiente que permite reconocer los conceptos de la electrónica fundamental, en beneficio del trabajo se logró definir formulas muy importantes.


## 6. Bibliografía

* Floyd, T.(2007). Principios de circuitos electricos(Octava edi). México Pearson
