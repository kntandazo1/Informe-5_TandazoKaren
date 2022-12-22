# Informe-5_TandazoKaren

## UNIVERSIDAD DE LAS FUERZAS ARMADAS-ESPE
NOMBRE: Karen Tandazo

NRC: 10067

### 1. OBJETIVOS:

OBJETIVOS GENERALES:

- Utilizar los métodos existentes de análisis de circuitos para llegar a determinar la corriente y voltaje que va a circular por el circuito.

- Analizar la relación que existe entre electricidad y magnetismo mediante la introducción a la electromagnética y el electroimán.

OBJETIVOS ESPECÍFICOS:

• Determinar la corriente dentro de un circuito aplicando métodos como el de la corriente en ramas, análisis de lazos y análisis de nodos.

• Identificar de forma adecuada la ecuación que se vaya a implementar para la resolución de ejercicios de Thevenin y Norton.

• Aplicar correctamente los métodos y resolver a detalle los ejercicios para comprender mejor los temas.

### 2. MARCO TEÓRICO:



### 3. EXPLICACIÓN Y RESOLUCIÓN DE EJERCICIOS O PROBLEMAS:
#### ---------------------------- CAPÍTULO 9 ---------------------------------------

##### SECCIÓN 9–1 Ecuaciones simultáneas en el análisis de circuitos

1. Con el método de sustitución, resuelva el siguiente conjunto de ecuaciones para IR1 e IR2.

![image](https://user-images.githubusercontent.com/117767335/209017553-c133c387-1821-4fca-ac1c-5f2d912100f4.png)

3. Utilizando determinantes, resuelva el siguiente conjunto de ecuaciones para ambas corrientes:

![image](https://user-images.githubusercontent.com/117767335/209018509-2543f90c-b17b-47f3-be60-44e1de208ade.png)

![image](https://user-images.githubusercontent.com/117767335/209019895-2c133847-735a-4028-87aa-541e209236c5.png)

5. Evalúe cada uno de los determinantes:

![image](https://user-images.githubusercontent.com/117767335/209020623-adc27cd8-0b03-40d9-ac9d-4141d4cb67f5.png)

![image](https://user-images.githubusercontent.com/117767335/209022891-30430206-cb21-4051-9081-0fa87811fc25.png)

7. Resuelva para I1, I2, I3 en el siguiente conjunto de ecuaciones con determinantes:

![image](https://user-images.githubusercontent.com/117767335/209022951-db7af7f7-fb91-4ce2-afb8-9a323860f9bd.png)

Determinante Característico:

![image](https://user-images.githubusercontent.com/117767335/209023043-56af3a8d-4022-4d32-9939-6dbdfbeca8f1.png)

Encontrando el valor de I1:

![image](https://user-images.githubusercontent.com/117767335/209023104-637bbaa7-0adb-4996-8faa-2ad6eebddc30.png)

Encontrando el valor de I2:

![image](https://user-images.githubusercontent.com/117767335/209023921-3602c12f-284c-4780-909f-da390c26bd95.png)

Encontrando el valor de I3:

![image](https://user-images.githubusercontent.com/117767335/209023264-df2e0ebb-0be3-4cd1-8e9b-f6e52d45ddc9.png)

9. Resuelva las dos ecuaciones simultáneas del problema 1 con su calculadora.

![image](https://user-images.githubusercontent.com/117767335/209023724-f9826316-07ea-492a-b216-e165ea87d3a7.png)

I1 = 13/35 = 0.371A = 371mA

I2 = -1/7 = 0,143A = 143mA

##### SECCIÓN 9–2 Método de la corriente en ramas

11. Escriba la ecuación de la corriente de Kirchhoff para la asignación de corriente mostrada en el nodo A
en la figura 9-26

![image](https://user-images.githubusercontent.com/117767335/209024010-f42eed9c-4264-4a30-86f7-c54e20bbf124.png)

I1 - I2 - I3 = 0

13. Determine la caída de voltaje entre los extremos de cada resistor mostrado en la figura 9-26 e indique
la polaridad real.

![image](https://user-images.githubusercontent.com/117767335/209024010-f42eed9c-4264-4a30-86f7-c54e20bbf124.png)

Ecuación:

R1I1 + R2I2 - Vs1 = 0

R2I2 + R3I3 - Vs2 = 0

I1 - I2 + I3 = 0

Reemplazamos:

8.2I1 + 10I2 = 12

10I2 + 5.6I3 = 6

I1 - I2 + I3 = 0

![image](https://user-images.githubusercontent.com/117767335/209029758-41b00830-3566-42eb-a384-98cbd15142f1.png)

![image](https://user-images.githubusercontent.com/117767335/209029806-7214d0a7-75e8-4e99-b3a6-eaee046103d3.png)

I1 = 0,692

I3 = 0,6329

I4 = -0,0587

Usamos la ley de Ohm para encontrar los voltajes: V = IR

V1 = 8,2 (0,692)

V1 = 5,66 V

V2 = 10(0,6329)

V2 = 6,33 V

V3 = 5.6(-0.0587)

V3 = 325mV

15. En la figura 9-27, determine el voltaje entre las terminales de la fuente de corriente (puntos A y B).

![image](https://user-images.githubusercontent.com/117767335/209030016-f734747c-e30e-40b3-8042-23e8de550382.png)

Aplicando la ley de ohm para encontrar el voltaje: V = I/R

V = 100/68

V = -1,84 V

##### SECCIÓN 9–3 Método de la corriente en lazos

17. Con el método de la corriente en lazos, determine las corrientes en los lazos que aparecen en la figura 9-28.

![image](https://user-images.githubusercontent.com/117767335/209030386-b2105ab0-d767-462b-8152-0eeb37327c3d.png)

Ecuación 1:

1000I1 + 560I1 - 560I2 = -6

1560I1 - 560I2 = -6

Ecuacion 2:

560I2 -560I1 +820I2 = -2

-560I1 + 1380I2 = -2

![image](https://user-images.githubusercontent.com/117767335/209030788-75628b79-0de5-43c7-9ef7-7081614b58c7.png)

![image](https://user-images.githubusercontent.com/117767335/209030839-7cb7df7a-9057-4655-9d52-918779119097.png)

I1 = -511mA

I2 = -3,52mA

19. Determine los voltajes y sus polaridades apropiadas en cada uno de los resistores mostrados en la figura
9-28.

![image](https://user-images.githubusercontent.com/117767335/209031008-59e7fe3e-c748-4c3c-98f1-7676b759f4b1.png)

Usamos la ley de voltajes de Kirchhoff:

∑V_s =∑V_x

Siendo Vx = I * Rx

Entonces:

∑V_s =∑〖I*V_x〗

Resolución:

-2-4=1000 Ω I1+560 Ω I1-560 I2

-6 V=1560Ω I1-560 I2

Encontrar para la otra fórmula:

+4- 6=-820 Ω I2+560 Ω I2-560 I1

-2 V=1380Ω I2-560 I1

![image](https://user-images.githubusercontent.com/117767335/209030788-75628b79-0de5-43c7-9ef7-7081614b58c7.png)

![image](https://user-images.githubusercontent.com/117767335/209030839-7cb7df7a-9057-4655-9d52-918779119097.png)

I1 = -0,00511 A

I2 = -0,00352 A

Para los voltajes:

*En 1000 Ω : Vx = (-0,00511 A) * (1000 Ω) = -5,11 V

*En 820 Ω : Vx = (-0,00352 A) * (820 Ω) = -2,8864 V

*En 1000 Ω : Vx = (-0,00511 A + 0,00352 A ) * (560 Ω) = -0,89 V

21. Resuelva para las corrientes de lazo en la figura 9-29 con su calculadora.

![image](https://user-images.githubusercontent.com/117767335/209031500-23086ab5-26e2-4248-9ec9-f16dfc7724fb.png)

Usamos la ley de voltajes de Kirchhoff:

∑V_s =∑V_x

Siendo Vx = I * Rx

Entonces:

∑V_s =∑〖I*V_x〗

Resolución:

1,5 V=47 Ω IA+10 Ω IA-10 IB

Fórmula 1: 1.5 V=57 Ω IA-10 IB

-3 V=27 Ω IB+10 Ω IB-10 Ω IA+4,7 Ω IB-4,7 Ω IC

Fórmula 2: -3 V=41.7 Ω IB-10Ω IA-4.7Ω IC

3 V-1,5 V=15 Ω IC+4,7 Ω IC-4,7 Ω IB

Fórmula 3: 1.5 V=19.7 Ω IC-4.7Ω IB

![image](https://user-images.githubusercontent.com/117767335/209031667-85c54c1b-2fcb-4d5b-91a8-79ebd7433961.png)

![image](https://user-images.githubusercontent.com/117767335/209031705-88640e58-2c53-454e-a308-6fd0876ddd06.png)

*IA = 0.0156 A

*IB = -0,0613 A 

*IC = 0,0615 A

23. Determine el voltaje entre las terminales del puente abierto, A y B, en la figura 9-30.

![image](https://user-images.githubusercontent.com/117767335/209031842-7543d3d0-447a-4400-8ef6-96e635e2cbf8.png)

Usamos la ley de voltajes de Kirchhoff:

∑V_s =∑V_x

Siendo Vx = I * Rx

Entonces:

∑V_s =∑〖I*V_x〗

Resolución:

8V=10Ω I1+4.7Ω I1+2.2Ω I1-4.7ΩI2-2.2ΩI2

8 V = 16,9 Ω I1-6,9 Ω I2

0V=-4,7 Ω I1-2,2 Ω I1+4,7 ΩI2+2,2 ΩI2+8,2 ΩI2+3,9 ΩI2

0V=-6,9 ΩI1+19 ΩI2

![image](https://user-images.githubusercontent.com/117767335/209032392-db0686ef-4498-47d0-ae79-9e4a55bb367d.png)

![image](https://user-images.githubusercontent.com/117767335/209032415-8883eaab-534b-4e9c-8ce0-6e8a1020fa04.png)

I1 = 0,56 A

I2 = 0,202 A

Nodo A:

*VA = 0,0202 A (4,7 Ω+2,2 Ω)

*VA = 0,139 V

*VB = 0,0202 A (8,2 Ω+ 3,9 Ω)

*VB = 0,24 V

25. Escriba las ecuaciones de lazo en la forma estándar para el circuito puente T mostrado en la figura 9-31.

![image](https://user-images.githubusercontent.com/117767335/209031861-873ee740-db63-46ca-a01f-c296c30e8eaf.png)

Usamos la ley de voltajes de Kirchhoff:

∑V_s =∑V_x

Siendo Vx = I * Rx

Entonces:

∑V_s =∑〖I*V_x〗

Resolución:

0 V=680 Ω IA+3300 Ω IA-3300 Ω IB+1500 Ω IA-1500 Ω IC

Fórmula 1: 0 V=5480 Ω IA-3300 IB-1500 Ω IC

15 V=-3300 Ω IA+3300 Ω IB+820 Ω IB-820 Ω IC

Fórmula 2: 15 V=-3300 Ω IA+4120Ω IB-820 Ω IC

0 V=-1500 Ω IA-820 Ω IB+1500 Ω IC+820 Ω IC+2200 Ω IC

Fórmula 3: 0 V=-1500 Ω IA-820Ω IB+4520 Ω IC

Ecuaciones:

0 V=5480 Ω IA-3300 IB-1500 Ω IC

15 V=-3300 Ω IA+4120 Ω IB-820 Ω IC

0 V=-1500 Ω IA-820 Ω IB+4520 Ω IC

![image](https://user-images.githubusercontent.com/117767335/209033041-58b1db57-e5f1-4d9e-8910-2a299b70c4b7.png)

![image](https://user-images.githubusercontent.com/117767335/209033079-e13b1751-6e2b-4ed9-834e-f1944ee206f0.png)

*IA = 0,0076 A

*IB = 0,0106 A

*CI= 0.0044 A

##### SECCIÓN 9–4 Método del voltaje en nodos

27. ¿Cuáles son los valores de corriente de rama en la figura 9-32? En cada rama, muestre la dirección real
de la corriente.

![image](https://user-images.githubusercontent.com/117767335/209033798-8079e2e9-ab9d-4e7e-b392-56ee9cdf9ef4.png)

Usamos la ley de la corriente de Kirchhoff:

∑Ixsalida=∑Ixentrada

Siendo Ix = Vs/Rx

Resolución:

Como solo existe un nodo solo hay una ecuación:

(40V-VA)/68Ω=(VA-30V)/82Ω+VA/(47Ω+100Ω)

(40 V)/68 Ω-VA/68 Ω=VA/82 Ω-(30 V)/82 Ω+VA/147 Ω

-VA/82Ω-VA/147Ω-VA/68Ω=-(30 V)/82Ω-(40 V)/68Ω

-0,0337VA=-665/697V

VA=28.311V

Cálculo de las ramas:

*I1 = (40V-VA)/68Ω=(40V-28.311V)/68Ω=0.17 A

*I2 = (VA+30 V)/82 Ω=(28,311 V+30 V)/82 Ω=0,71 A

*I3 = VA/147Ω=28.311V/147Ω= 0.19A

29. Use el análisis de nodos para determinar el voltaje en los puntos A y B con respecto a tierra en la figura
9-33.

![image](https://user-images.githubusercontent.com/117767335/209034255-f7a97a25-e26e-4e8f-93da-2fc270b3bf1a.png)

Usamos la ley de la corriente de Kirchhoff:

∑Ixsalida=∑Ixentrada

Siendo Ix = Vs/Rx

Resolución:

Como existe dos nodos hay dos ecuaciones:

(9V-VA)/(56000 Ω)=VA/(27000 Ω)+(VA-VB)/(91000 Ω)

9V/(56000 Ω)-VA/(56000 Ω)=VA/(27000 Ω)+VA/(91000 Ω)-VB/(91000 Ω)

9V/(56000 Ω)=VA/(56000 Ω)+VA/(27000 Ω)+VA/(91000 Ω)-VB/(91000 Ω)

Ecuación 1: 9V/(56000 Ω)=(37 VA)/561600-VB/(91000 Ω)

(VA-VB)/(91000 Ω)+(4.5V-VB)/(33000 Ω)=(VB-15V)/(82000 Ω)

VA/(91000 Ω)-VB/(91000 Ω)+4,5 V/(33000 Ω)-VB/(33000 Ω)=VB/(82000 Ω)-15 V/(82000 Ω)

4,5 V/(33000 Ω)+15 V/(82000 Ω)=-VA/(91000 Ω)+VB/(82000 Ω)+VB/(91000 Ω)+VB/(33000 Ω)

Ecuación 2: 18V/(56375 Ω)=-VA/(91000 Ω)+0.000053487 VB

![image](https://user-images.githubusercontent.com/117767335/209036194-383d7173-c8ab-4987-bf05-3adba7a7fe44.png)

![image](https://user-images.githubusercontent.com/117767335/209036225-8f5b7f24-057d-4335-8167-6a27edd514b9.png)

*VA = 3,557 V

*VB= 6.700 V

31. Use el análisis de nodos, el de lazos, o cualquier otro procedimiento para determinar las corrientes y
los voltajes en cada nodo desconocido en la figura 9-35.

![image](https://user-images.githubusercontent.com/117767335/209032029-58d3a4a2-5302-4ffd-b5f2-95862d064c28.png)

Usamos la ley de corriente de Kirchhoff:

∑Ixsalida=∑Ixentrada

Siendo Ix = Vs/Rx

Resolición:

Debidos a que existen 3 nodos habrán 3 ecuaciones:

Nodo A:

(20-VA)/(10 000 Ω)=(VA+5,25 V)/(8 000 Ω)+(VA-VB)/(12 000 Ω)

(-VA)/(10 000 Ω)+(-VA)/(8 000 Ω)+(-VA)/(12 000 Ω)=5,25 V/(8 000 Ω)+VB/(12 000 Ω)+ (-20 V)/(10 000 Ω)

(37 00)/(12 Ω) VA+VB/(12 000 Ω)=(43 000 V)/32 Ω

Nodo B:

VB/(4 000 Ω)=(VA-VB)/(12 000 Ω)+(VC+5,25 V)/(6 000 Ω)

VB/(10 000 Ω)+VB/(12 000 Ω)=VA/(12 000 Ω)+VC/(6 000 Ω)+5,25 V/(6 000 Ω)

1100/(6 Ω) VB-VA/(12 000 Ω)-VC/(6 000 Ω)=5,25 V/6000 Ω

Nodo C:

CV/(2 000 Ω)=(VC-VB)/(6 000 Ω)+(5,25 V-VC)/(20 000 Ω)

VC/(2 000 Ω)-VC/(6 000 Ω)+VC/(20 000 Ω)=(-VB)/(6 000 Ω)+(-5,25 V)/(20 000 Ω)

(17 00)/(6 Ω) VC-VB/(12 000 Ω)=+5,25 V/(20 000 Ω)

### 4. VIDEO:


### 5. CONCLUSIONES:

- En conclusión, mediante el método de análisis de nodos y mallas, podemos observar como se comporta el voltaje y la corriente dentro del circuito siempre y cuando se haya planteando correctamente las ecuaciones que se obtengan de la aplicación de los métodos.

- Se logró realizar un análsis adecuado para los circuitos planteados y de esta manera encontrar la solución para encontrar el valor de cada componente requerido en el  circuito.

- Con la resolución de los ejercicios planteados en estos capítulos la compresión de los temas vistos fue más comprensible.

### 6. BIBLIOGRAFÍA:

Thomas L. Floyd (2007). Principios de circuitos electricos. octava edicion
