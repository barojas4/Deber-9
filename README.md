                                               UNIVERSIDAD DE LAS FUERZAS ARMADAS - ESPE
                                                                ELECTRICA Y ELECTRONICA

Nombre: Brayan Rojas

NRC: 10067

MATERIA: Fundamentos de Circuitos Electricos 

## 1.Objetivos


* Objetivo General

Analizar la teoria e identificar los conceptos de  RLC y resonancia mediante la lectura de los capítulos 17 y 18 del libro "Principios de circuitos eléctricos" de Floyd, para aplicarlos en la práctica y resolución de ejercicios.

* Objetivos especificos

Analizar conceptos básicos de los temas circuitos RCL y resonancia, así como, Filtros pasivos, correspondientes al capítulo 17 y 18 del libro de Floyd, que nos adentren al mundo de los circuitos eléctricos.

mplear los conocimientos aprendidos con la lectura del capítulo 17 y 18 para la resolución de los ejercicios pares propuestos en el libro "Principios de circuitos eléctricos" de Floyd.

## 2.Marco Teorico (Resumen)

![imagen](https://user-images.githubusercontent.com/116810935/221340857-4dd7b42c-a656-43ff-8865-4a58a0688cd1.png)

![imagen](https://user-images.githubusercontent.com/116810935/221340871-44888174-39fc-4e09-84a0-3fa18635f5e0.png)

![imagen](https://user-images.githubusercontent.com/116810935/221340876-ca72d54f-7495-4053-816c-2ed55bdc08d7.png)

![imagen](https://user-images.githubusercontent.com/116810935/221340878-ca3c40f5-3349-491b-b606-9d4c372d7f5a.png)

![imagen](https://user-images.githubusercontent.com/116810935/221340884-42d606c0-81e2-4f96-bf2d-e3ac834628e7.png)

![imagen](https://user-images.githubusercontent.com/116810935/221340887-0f6ffc0b-792f-40f8-b45e-7805e4a01c4a.png)

![imagen](https://user-images.githubusercontent.com/116810935/221340890-c1fa61c8-da27-47b9-ade6-291e15c8e0a3.png)

![imagen](https://user-images.githubusercontent.com/116810935/221340895-4e6ff622-48fd-4261-8182-4fa8542e587d.png)




## 3. Explicacion y resolución de ejercicios

PARTE 1: CIRCUITOS EN SERIE SECCIÓN 17–1 Impedancia de circuitos RLC en serie

 1.  Cierto circuito RLC en serie tiene los siguientes valores: R = 10ohm, C = 0.047uF, y L = 5mH. Determine la impedancia en forma polar. ¿Cuál es la reactancia neta? La frecuencia de la fuente es de 5 kHz.

R = 10 ohm
C = 0.047 uF => 4.7x10^-8 F
L = 5 mH => 0.005 H
f = 5 kHz => 5000 Hz

Xc = 1/2πfC
Xc = 1/2π(5000)(4.7x10^-8)
Xc = 677.255 ohm

XL = 2πfC
XL = 2π(5000)(0.005)
XL = 157.08 ohm

Xtot = |157.08 - 677.255|
Xtot = 520 ohm => Capacitiva

Z = √R^2 + Xtot^2 ∠ tan^-1 (Xtot/R)
Z = √(10)^2 + (250)^2 ∠ tan^-1 (250/10)
Z = 520 ∠ -88.90° ohm

  3. Si en la figura 17-59 la frecuencia del voltaje de fuente se duplica a partir del valor que producen las reactancias indicadas, ¿cómo cambia la magnitud de la impedancia?

![imagen](https://user-images.githubusercontent.com/116810935/221341038-96c91e00-e3e9-4980-94ef-71531978d721.png)

Xtot = |80 - 35|
Xtot = 45 ohm => Inductivo

Z = √R^2 + Xtot^2 ∠ tan^-1 (Xtot/R)
Z = √(47)^2 + (45)^2 ∠ tan^-1 (45/47)
Z = 65.07 ∠ 43.75° ohm

Respuesta

La impedancia se incrementa a 150 ohm

SECCIÓN 17–2 Análisis de circuitos RLC en serie

 5.  Para el circuito de la figura 17-59, determine Itot, VR, VL y VC en forma polar.

![imagen](https://user-images.githubusercontent.com/116810935/221341079-a9cd0332-e02a-4bdd-96ac-0f81ed12466a.png)

Z = R + jXL - jXc Z = 47 + j80 -j35 Z = 47 + j45 ohm

Z = √R^2 + Xtot^2 ∠ tan^-1 (Xtot/R)
Z = √(47)^2 + (45)^2 ∠ tan^-1 (45/47)
Z = 65.07 ∠ 43.75° ohm

Itot = Vs/Z
Itot = (4 ∠ 0°)/(65.07 ∠ 43.75°)
Itot = 61.4 ∠ -43.75° mA

VR = IR
VR = (61.4 ∠ -43.75°)(47 ∠ 0°)
VR = 2.89 ∠ -43.75° V

VL = IXL
VL = (61.4 ∠ -43.75°)(80 ∠ 90°)
VL = 4.91 ∠ 46.25° V

Vc = IXc
Vc = (61.4 ∠ -43.75°)(35 ∠ -90°)
VL = 2.15 ∠ -134° V


   7. Analice el circuito de la figura 17-60 para determinar lo siguiente (f = 25 kHz):

(a) Itot (b) Preal (c) Pr (d) Pa

![imagen](https://user-images.githubusercontent.com/116810935/221341099-4bed5c35-5f7b-4d39-9aa3-41aa1e915234.png)

1/R = 1/220 + 1/390
RT = 140.656 ohm

LT = 0.5 + 1
LT = 1.5 mH => 0.0015 H

CT = 10000 + 1800
CT = 11800 pF => 1.18x10^-8 F

f = 25 kHz => 25000 Hz

Xc = 1/2πfC
Xc = 1/2π(25000)(1.18x10^-8)
Xc = 539.51 ohm

XL = 2πfC
XL = 2π(25000)(0.0015)
XL = 235.62 ohm

Xtot = |235.62 - 539.51|
Xtot = 303.9 ohm => Capacitiva

Z = √R^2 + Xtot^2 ∠ tan^-1 (Xtot/R)
Z = √(140.656)^2 + (303.9)^2 ∠ tan^-1 (303.9/140.656)
Z = 334.87 ∠ -65.2° ohm

Itot = Vs/Z
Itot = (12 ∠ 0°)/(334.87 ∠ -65.2°)
Itot = 35.8 ∠ 65.2° mA

Preal = I^2R
Preal = 181 mW

Pr = I^2 Xc
Pr = 390 mVAR

Pa = I^2 Z
Pa = 430 mVA

SECCIÓN 17–3 Resonancia en serie

   9. Para el circuito de la figura 17-61, ¿cuál es el voltaje a través de R en condición de resonancia?

![imagen](https://user-images.githubusercontent.com/116810935/221341132-64b091d8-3e97-4434-8263-17eb3298de23.png)

I = Vs/R
I = 12/22
I = 0.54 A

VR = IR
VR = (0.5454)(22)
VR = 12 V

11. Cierto circuito resonante dispuesto en serie tiene una corriente mínima de 50 mA y un VL de 100 V. El voltaje aplicado es de 10 V. ¿Cuál es el valor de Z? ¿Cuáles los valores de XL y XC?


I = 0.05 A
VL = 100 V
Vs = 10 V

VL = IXL
10 = 0.05(XL)
XL = 100/0.05
XL = Xc = 2000 ohm

I = Vs/Z
0.05 = 10/Z
Z = 200 ohm

13. Para la figura 17-62, ¿cuál es el valor de la corriente en los puntos de potencia media?

![imagen](https://user-images.githubusercontent.com/116810935/221341166-891b2852-add2-49dc-a4e1-1e4f6f7448ca.png)


I = Vs/R
I = 7.07/10
I = 707 mA

15.  Diseñe un circuito en el cual las siguientes frecuencias resonantes en serie se puedan seleccionar con un conmutador:

(a) 500 kHz (b) 1000 kHz (c) 1500 kHz (d) 2000 kHz

![imagen](https://user-images.githubusercontent.com/116810935/221341177-280277e6-1938-4cce-b7ea-c3abead2f909.png)

17. ¿Es capacitivo o inductivo el circuito de la figura 17-63? Explique su respuesta.

![imagen](https://user-images.githubusercontent.com/116810935/221341187-5218ffeb-1142-47a6-a17c-394232d97614.png)

L = 15 mH => 0.015 H
C = 0.022 uF => 2.2x10^-8
f = 12000 Hz

Xc = 1/2πfC
Xc = 1/2π(12000)(2.2x10^-8)
Xc = 602.86 ohm

XL = 2πfC
XL = 2π(12000)(0.015)
XL = 1130.97 ohm

G = 1/(R ∠ 0°) G = 1/(5 ∠ 0°) G = 200 ∠ 0° uS

Bc = 1/(Xc ∠ -90°) Bc = 1/(602.86 ∠ -90°) Bc = 1.66 ∠ 90° uS

BL = 1/(XL ∠ 90°) BL = 1/(1130.97 ∠ 90°) BL = 0.884 ∠ -90° uS

Ytot = G + jBc - jBL Ytot = 200 + j1.66 - j0.884 Ytot = 200 uS - j0.776

Ytot = √G^2 + Btot^2 ∠ tan^-1 (Btot/G)
Ytot = √(200)^2 + (0.776)^2 ∠ tan^-1 (0.776/200)
Ytot = 200 ∠ -4.43° uS

El ángulo de fase de -4.43° indica un circuito levemente capacitivo.

SECCIÓN 17–5 Análisis de circuitos RLC en paralelo

   19. Para el circuito de la figura 17-63, determine todas las corrientes y los voltajes en forma polar

![imagen](https://user-images.githubusercontent.com/116810935/221341198-42d5cec7-bf7a-4f7e-99f3-129819481235.png)

L = 15 mH => 0.015 H
C = 0.022 uF => 2.2x10^-8
f = 12000 Hz

Xc = 1/2πfC
Xc = 1/2π(12000)(2.2x10^-8)
Xc = 602.86 ohm

XL = 2πfC
XL = 2π(12000)(0.015)
XL = 1130.97 ohm

VR = VL = Vc = 5 ∠ 0°

IR = Vs/R
IR = (5 ∠ 0°)/(100 ∠ 0°)
IR = 50 ∠ 0° mA

Ic = Vs/Xc
Ic = (5 ∠ 0°)/(602.86 ∠ -90°)
Ic = 8.29 ∠ 90° mA

IL = Vs/XL
IL = (5 ∠ 0°)/(1130.97 ∠ 90°)
IL = 4.42 ∠ 90° mA

Itot = IR + Ic + IL
Itot = 50 + j8.29 - j4.42
Itot = 50 mA + j3.87 mA

Itot = √IR^2 + (Ic - IL)^2 ∠ tan^-1 (IcL/IR)
Itot = √50^2 + (3.87)^2 ∠ tan^-1 (3.87/50)
Itot = 50.15 ∠ 4.43° mA

21 Cambie la frecuencia a 100 kHz en la figura 17-63 y repita el problema 19.

![imagen](https://user-images.githubusercontent.com/116810935/221341212-1973a73e-3b5b-4d83-bcad-d6dd80827e77.png)

L = 15 mH => 0.015 H
C = 0.022 uF => 2.2x10^-8
f = 1000000 Hz

Xc = 1/2πfC
Xc = 1/2π(100000)(2.2x10^-8)
Xc = 72.34 ohm

XL = 2πfC
XL = 2π(100000)(0.015)
XL = 9424.78 ohm

VR = VL = Vc = 5 ∠ 0°

IR = Vs/R
IR = (5 ∠ 0°)/(100 ∠ 0°)
IR = 50 ∠ 0° mA

Ic = Vs/Xc
Ic = (5 ∠ 0°)/(72.34 ∠ -90°)
Ic = 69.11 ∠ 90° mA

IL = Vs/XL
IL = (5 ∠ 0°)/(9424.78 ∠ 90°)
IL = 0.53 ∠ 90° mA

Itot = IR + Ic + IL
Itot = 50 + j69.11 - j0.53
Itot = 50 mA + j68.58 mA

Itot = √IR^2 + (Ic - IL)^2 ∠ tan^-1 (IcL/IR)
Itot = √50^2 + (68.58)^2 ∠ tan^-1 (68.58/50)
Itot = 84.9 ∠ 53.9° mA

SECCIÓN 17–6 Resonancia en paralelo

23. Determine Z en condición de resonancia y fr para el circuito tanque de la figura 17-64.

![imagen](https://user-images.githubusercontent.com/116810935/221341231-40151024-bd24-49fe-a180-8f006f7badcc.png)

R = 20 ohm
L = 50 mH => 0.05 H
C = 47 pF => 4.7x10^-11

fr = (√1 - Rw^2C/L)/2π√LC
fr = (√1 - (20)^2(4.7x10-11)/(0.05))/2π√(4.7x10-11)(0.05)
fr = 103821.21 Hz
fr = 104 kHz
Z = 53.5 Mohm

SECCIÓN 17–6 Resonancia en paralelo

  25. Determine Preal, Pr y Pa en el circuito de la figura 17-64 en condición de resonancia.

![imagen](https://user-images.githubusercontent.com/116810935/221341244-34ec5e51-e30b-45a7-b4ad-67d95c93714b.png)

![imagen](https://user-images.githubusercontent.com/116810935/221341248-fd16163a-3319-4816-9c55-0fa6adf1e588.png)

PARTE 3: CIRCUITOS EN SERIE-PARALELO

SECCIÓN 17–7 ANÁLISIS DE CIRCUITOS RLC EN SERIE-PARALELO

27.  Para cada circuito de la figura 17-65, determine el ángulo de fase entre el voltaje de fuente y la corriente total.


![imagen](https://user-images.githubusercontent.com/116810935/221341260-0fa40a7f-64b8-46b3-965b-3323ac274579.png)

![imagen](https://user-images.githubusercontent.com/116810935/221341266-0ef0f7cf-557d-487e-b358-22b1f5700526.png)

Circuito a

![imagen](https://user-images.githubusercontent.com/116810935/221341277-ece3d6a6-ed43-48fc-96ac-bbe4121ccd83.png)

![imagen](https://user-images.githubusercontent.com/116810935/221341287-bbea6c49-d5db-4842-9d7a-5d45c3a1bc76.png)

Circuito b

![imagen](https://user-images.githubusercontent.com/116810935/221341295-0a27968f-8c89-4821-a80a-1e3cf0c222a4.png)

29. Convierta el circuito de la figura 17-66 a una forma equivalente dispuesta en serie.

![imagen](https://user-images.githubusercontent.com/116810935/221341305-e8f3dfda-3073-4f49-a7c1-91c7fc7b8756.png)

![imagen](https://user-images.githubusercontent.com/116810935/221341310-b78a9d8e-e25b-4143-9831-483cc40559d7.png)

Respuesta

El nuevo circuito tiene como resistencia 49.03kΩ

valor de inductancia de 17.44kH.

31. En la figura 17-67, ¿cuál es el ángulo de fase entre I2 y el voltaje de fuente?

![imagen](https://user-images.githubusercontent.com/116810935/221341350-640c7863-b1f3-4a0c-a169-b7be264b877c.png)

![imagen](https://user-images.githubusercontent.com/116810935/221341354-0072003a-6ab3-4d45-83ba-2d6f4a603c40.png)

33. Determine la corriente a través de cada componente mostrado en la figura 17-68. Encuentre el voltaje entre las terminales de cada componente.


![imagen](https://user-images.githubusercontent.com/116810935/221341361-04052181-2549-4ff7-83c5-9d9cf6ebd2be.png)

![imagen](https://user-images.githubusercontent.com/116810935/221341365-0ca48b01-f3ca-456f-b600-624e37da1425.png)

35. Si el valor de C es de 0.22 µF, ¿cuál es la corriente a través de un resistor de 100 Ω conectado de a a b en la figura 17-69?

Calcular la impedancia del conductor e inductor:

![imagen](https://user-images.githubusercontent.com/116810935/221341388-dba7d4ff-c1d4-476c-859f-ecdfbcf2770d.png)

Calcular la resistencia total:

![imagen](https://user-images.githubusercontent.com/116810935/221341396-8f67c894-7d7e-4498-b333-571e0fddd311.png)

Calcular la corriente total:


![imagen](https://user-images.githubusercontent.com/116810935/221341406-5daebddf-5e49-4744-b2a1-4b04a0b0d8c5.png)

Calculo de la corriente por la resistencia de 100Ω

![imagen](https://user-images.githubusercontent.com/116810935/221341417-4d3a2291-c424-4963-b2ca-88db831d169d.png)

37. Determine las frecuencias resonantes y el voltaje de salida en cada frecuencia mostrada en la figura 17-70.


![imagen](https://user-images.githubusercontent.com/116810935/221341437-681d00ca-e1ea-4b83-9cc4-7f0876fa1133.png)


Frecuencia en serie

![imagen](https://user-images.githubusercontent.com/116810935/221341444-21e9f7dd-e736-4878-acdd-5278f7936fb8.png)

Frecuencia en paralelo

![imagen](https://user-images.githubusercontent.com/116810935/221341452-beca3626-e230-45f7-b871-70b7750d3397.png)

SECCIÓN 17–8 Ancho de banda de circuitos resonantes

   39.En condición de resonancia, XL = 2 kΩ y RW 25Ω en un circuito RLC en paralelo. La frecuencia resonante es de 5 kHz. Determine el ancho de banda.

Para la resolución del problema se tiene las siguientes formulas:

El factor Q:

![imagen](https://user-images.githubusercontent.com/116810935/221341465-002ed306-892c-4435-8a1a-42a54b799cff.png)

Un valor alto de Q produce un ancho de banda más angosto. Un valor bajo de Q produce un ancho de banda más amplio. En la siguiente ecuación se establece una fórmula para el ancho de banda de un circuito resonante en función de Q:

![imagen](https://user-images.githubusercontent.com/116810935/221341471-7931d6c4-5d3b-4efb-adb2-23d6271f4955.png)

41. En cierto circuito RLC, la potencia en condición de resonancia es de 2.75 W. ¿Cuál es la potencia a la frecuencia crítica baja?

En condición de resonancia:

![imagen](https://user-images.githubusercontent.com/116810935/221341484-3ef94259-6317-4dc1-abbc-811dcd437719.png)

![imagen](https://user-images.githubusercontent.com/116810935/221341487-6de6dca6-d850-480a-8d7a-e451d37c51f0.png)

De forma tal que la potencia a la frecuencia crítica baja es:

![imagen](https://user-images.githubusercontent.com/116810935/221341491-8738edb6-d1a6-4aca-87db-7a6868d1f254.png)

  43.  Cierto circuito resonante en paralelo tiene un factor Q de 50 y un AB de 400 Hz. Si Q se duplica, ¿cuál es el ancho de banda a la misma fr?

En la siguiente ecuación se establece una fórmula para el ancho de banda de un circuito resonante en función de Q

![imagen](https://user-images.githubusercontent.com/116810935/221341506-42ef64ed-c41e-4041-bb65-513182c71926.png)

Para ello se calcula primeramente frecuencia de resonancia:

![imagen](https://user-images.githubusercontent.com/116810935/221341513-9c465ef6-4a2b-48e3-b9bf-3c33e806956f.png)

Ahora según el enunciado nos dice que el factor Q se ha duplicado entonces de 50 pasa a 100 y se determina con este valor el ancho de banda de fr:

![imagen](https://user-images.githubusercontent.com/116810935/221341524-26570fbb-bf83-40a8-b8ad-3f4908132315.png)

SECCIÓN 18–1 Filtros pasabajas

   1. En cierto filtro pasabajas, XC = 500 Ω y R = 2.2 kΩ. ¿Cuál es el voltaje de salida (Vsal) cuando la entrada es de 10 V rms?

Al aplicar la fórmula del divisor de voltaje, la magnitud del voltaje de salida es:

![imagen](https://user-images.githubusercontent.com/116810935/221341541-da06c757-742f-41dc-be23-a4f0821187e5.png)

3.Determine el voltaje de salida (Vsal) de cada filtro mostrado en la figura 18-38 a la frecuencia especificada cuando Vent = 10 V

![imagen](https://user-images.githubusercontent.com/116810935/221341560-4155a5aa-b5f6-4880-bf90-9d4e37156906.png)

![imagen](https://user-images.githubusercontent.com/116810935/221341565-a0112542-beb3-4b7c-a66d-7334879e7623.png)

![imagen](https://user-images.githubusercontent.com/116810935/221341570-bfd40cc2-72cf-44a7-b6b3-11a667f83cad.png)

![imagen](https://user-images.githubusercontent.com/116810935/221341573-9bf80101-6e71-4878-be0e-3fad7ce91c3f.png)

5. Para el filtro de la figura 18-39, calcule el valor de C requerido para cada una de las siguientes frecuencias críticas:

![imagen](https://user-images.githubusercontent.com/116810935/221341583-63bfa5e4-26e1-456f-8dc3-602d82b5eb22.png)

fc=1/2πRC

fc2πR=1/C

C= 1/(fc2πR)

Reemplazando valores

(a) 60 Hz

C= 1/(60Hz2π220Ω)

C= 0.000012057 F=12.1 μF

(b) 500 Hz

C= 1/(500Hz2π220Ω)

C= 0.000001447 F=1.45 μF

(c) 1 kHz

C= 1/(1000 Hz2π220Ω)

C= 0.000000723 F=0.72 μF

(d) 5 kHz

C= 1/(5000 Hz2π220Ω)

C= 0.000000145 F=0.145 μF

   7. Trace una curva de Bode para cada una de las partes del problema 5.

![imagen](https://user-images.githubusercontent.com/116810935/221341595-f7647c80-2826-4723-81d9-ce367c4cc9e7.png)

![imagen](https://user-images.githubusercontent.com/116810935/221341604-be430381-55a0-4bcf-ae68-2105d18f01c0.png)

![imagen](https://user-images.githubusercontent.com/116810935/221341607-d9b4cc53-9ef4-457d-85cc-91976ddb6b4e.png)

![imagen](https://user-images.githubusercontent.com/116810935/221341613-38fa2eb7-2267-4810-828b-bd6a561e6ea9.png)

  9.  l voltaje de entrada a un filtro RC pasabajas es de 8 V rms. Determine el voltaje de salida a los siguientes niveles de dB:

20*log⁡(Vsalida/Ventrada)=dB

log⁡(Vsalida/(8 Vrms))=dB/20

Vsalida/(8 Vrms)=e^(dB/20)

Vsalida=8 Vrms* e^(dB/20)

Reemplazando valores

(a) -1 dB

Vsalida=8 Vrms* e^((-1)/20)

Vsalida=7.61 V

(b) -3 dB

Vsalida=8 Vrms* e^((-3)/20)

Vsalida=6.89 V

(c) -6 dB

Vsalida=8 Vrms* e^((-6)/20)

Vsalida=5.92 V

(d) -20 dB

Vsalida=8 Vrms* e^((-20)/20)

Vsalida=2.94 V

SECCIÓN 18–2 Filtros pasaaltas


   11. l voltaje de entrada a un filtro RC pasabajas es de 8 V rms. Determine el voltaje de salida a los siguientes niveles de dB:

20*log⁡(Vsalida/Ventrada)=dB

log⁡(Vsalida/(8 Vrms))=dB/20

Vsalida/(8 Vrms)=e^(dB/20)

Vsalida=8 Vrms* e^(dB/20)

Reemplazando valores

(a) -1 dB

Vsalida=8 Vrms* e^((-1)/20)

Vsalida=7.61 V

(b) -3 dB

Vsalida=8 Vrms* e^((-3)/20)

Vsalida=6.89 V

(c) -6 dB

Vsalida=8 Vrms* e^((-6)/20)

Vsalida=5.92 V

(d) -20 dB

Vsalida=8 Vrms* e^((-20)/20)

Vsalida=2.94 V

SECCIÓN 18–2 Filtros pasaaltas

13. Determine el voltaje de salida de cada filtro mostrado en la figura 18-41 a la frecuencia especificada cuando Vent = 10 V.

![imagen](https://user-images.githubusercontent.com/116810935/221341668-0803f8dc-e574-4237-82c3-82ae4226d252.png)

Reactancia capacitiva

Xc=1/(2πfC)

Xc=1/(2π60Hz10μF)=265 Ω

Vsalida=(R/√(R^2+〖Xc〗^2 ))*Ventrada

Vsalida=(100/√(100^2+265^2 ))*10

Vsalida=3.53 Vrms

Desplazamiento de fase

φ=〖tan〗^(-1) (Xc/R)

φ=〖tan〗^(-1) (265/100)

φ=69.33°

El voltaje

Vsalida=3.53∠69.33° V

![imagen](https://user-images.githubusercontent.com/116810935/221341682-45787d25-0444-42f5-9715-5d141b066da6.png)

Reactancia capacitiva

Xc=1/(2πfC)

Xc=1/(2π400Hz4.7μF)=84.6 Ω

Vsalida=(R/√(R^2+〖Xc〗^2 ))*Ventrada

Vsalida=(47/√(47^2+〖84.6〗^2 ))*10

Vsalida=4.85 Vrms

Desplazamiento de fase

φ=〖tan〗^(-1) (Xc/R)

φ=〖tan〗^(-1) (84.6/47)

φ=60.95°

El voltaje

Vsalida=4.85∠60.95° V



![imagen](https://user-images.githubusercontent.com/116810935/221341691-ca33e42a-22fd-463e-989d-ecbb657983c1.png)

Rw=2πf*L

Rw=2π1000 Hz*,005 H=31.42

Vsalida=(R/(R+Rw))*Ventrada

Vsalida=(330/(330+31.42))*10

Vsalida=9.47mVrms

Desplazamiento de fase

φ=〖tan〗^(-1) (Rw/R)

φ=〖tan〗^(-1) (3142/330)

φ=84°

El voltaje

Vsalida=9.4∠84° mV

![imagen](https://user-images.githubusercontent.com/116810935/221341706-b072c580-eccb-4732-9c03-9f48bf7bc713.png)

Rw=2πf*L

Rw=2π2000 Hz*0.08 H=1005.3

Vsalida=(R/(R+Rw))*Ventrada

Vsalida=(10/(10+1005.3))*10

Vsalida=995 mVrms

Desplazamiento de fase

φ=〖tan〗^(-1) (Rw/R)

φ=〖tan〗^(-1) (1005.3/10)

φ=84.3°

El voltaje

Vsalida=995∠84.3° mV

15. Trace la curva de Bode para cada filtro mostrado en la figura 18-41.

a) 

![imagen](https://user-images.githubusercontent.com/116810935/221341727-50939d99-e86d-4422-bea4-9064bed8d95b.png)

b)

![imagen](https://user-images.githubusercontent.com/116810935/221341730-30e27d11-afa6-45b6-b57e-c5464d18cd81.png)

c)

![imagen](https://user-images.githubusercontent.com/116810935/221341736-2f94b3b6-0240-49b1-9ce9-95a03db29458.png)

d)

![imagen](https://user-images.githubusercontent.com/116810935/221341740-cc7519a5-fe34-417c-ad7c-85d54d7a52ab.png)

SECCIÓN 18–3 Filtros pasabanda

   17. Determine la frecuencia central para cada filtro de la figura 18-43.

![imagen](https://user-images.githubusercontent.com/116810935/221341745-abac8da8-ef14-4bed-8fd1-fdbfe489fb7a.png)

fo=√(1-(〖Rw〗^2C/L))/(2π√(LC))

fo=√(1-(0^20.01μF/12mH))/(2π√(12mH0.01μF))

fo=14.5 kHz

![imagen](https://user-images.githubusercontent.com/116810935/221341749-1ddb6629-67a0-48c8-83c7-fca105179ad1.png)

fo=√(1-(〖Rw〗^2C/L))/(2π√(LC))

fo=√(1-(0^20.022μF/2mH))/(2π√(2mH0.022μF))

fo=24.0 kHz

   19. ¿Cuáles son las frecuencias críticas alta y baja para cada filtro de la figura 18-43? Suponga que la respuesta es simétrica con respecto a f0.

![imagen](https://user-images.githubusercontent.com/116810935/221341767-fcad4435-ade1-4d02-a872-13830d08b0f2.png)

fc=1/(2π*L/R)

fc=1/(2π*1H/680Ω)

fc=15.06 kHz

fc=1/(2πRC)

fc=1/(2π680Ω10μF)

fc=13.94 kHz

![imagen](https://user-images.githubusercontent.com/116810935/221341780-2a6bc891-02ab-4434-a19e-75854a147d58.png)

fc=1/(2π*L/R)

fc=1/(2π*(2.5 μH)/(1 kΩ))

fc=25.3 kHz

fc=1/(2πRC)

fc=1/(2π1 kΩ25pF)

fc=22.7 kHz

   21. Si la resistencia de devanado de las bobinas que aparecen en la figura 18-44 es de 4 Ω, ¿cuál es el voltaje de salida en condición de resonancia cuando Vent = 120 V?

![imagen](https://user-images.githubusercontent.com/116810935/221341798-5731f41d-9bca-4983-963c-a367d85934b9.png)

Vsalida=(R/(R+Rw))*Ventrada

Vsalida=(680/(680+4))*120V

Vsalida=119.29V

![imagen](https://user-images.githubusercontent.com/116810935/221341807-c3640a3a-efe7-4e38-9c16-eef133921a52.png)

Vsalida=(R/(R+Rw))*Ventrada

Vsalida=(1000/(1000+4))*120V

Vsalida=119.52V

23. Diseñe un filtro pasabanda utilizando un circuito resonante paralelo que satisfaga las siguientes especificaciones: AB = 500 Hz; Q = 40; e IC(máx) =20 mA, VC(máx) =2.5 V. Entonces

el valor de la capaitancia es 0.064 uF

La inductancia debe ser de 989 uH

la frecuencia f= 20 kHz

   25. Para cada filtro de la figura 18-47, determine la frecuencia central de la banda de rechazo

![imagen](https://user-images.githubusercontent.com/116810935/221341830-5c880e67-7dba-4157-8912-b931facddadb.png)

F0=sqrt(1-R^2*C/L)/2piSqrt(LC)

F0= sqrt(1-1000^26.8/0,5)/2piSqrt(0.56,8)

F0=318Hz

![imagen](https://user-images.githubusercontent.com/116810935/221341845-af8e5bf1-7fb8-47d7-9e13-7c6b97ff17f8.png)

F0=sqrt(1-R^2*C/L)/2piSqrt(LC)

F0= sqrt(1-2200^247/10)/2piSqrt(1047)

F0=10,21Hz

27. Determine los valores de L1 y L2 en la figura 18-48 para dejar pasar una señal con frecuencia de 1200 kHz y rechazar una señal con frecuencia de 456 kHz.

![imagen](https://user-images.githubusercontent.com/116810935/221341853-ebfd423d-ca68-4c39-9aa2-0e278e475010.png)


fo=√(1-(〖Rw〗^2C/L))/(2π√(LC))

Si Rw = 0 ohmios

fo=1/(2π√(L*C))

2πfo=1/√(LC)

√(2πfo)=1/(LC)

L=C/√(2π*fo )

Reemplazando datos

Fo = 1200 kHz

L=(0.22 μF)/√(2π*1200 kHz )

L=0.0025 μH

Fo = 456 kHz

L=(0.22 μF)/√(2π*456 kHz )

L=0.004 μH






 ## 4. Video
 
 link del video: https://www.youtube.com/watch?v=S2la1igGjh8
 
 ## 5.Conlusión 
 
 * En conclusión en la tarea presente se logró alcanzar los objetivos plantados anteriormente  para un mejor entendimiento de los circuitos eléctricos, mostrando un uso correcto los conocimientos para la resolucion de circuitos con bases solidas en la solucion de sistemas ecuaciones con numeros complejos que brindan ayuda en los cálculos de voltajes, corrientes y resistencias, además gracias al calculo de impedancias se puede analizar circuitos de corriente alterna.
  
* Se realizo un trabajo eficiente que permite reconocer los conceptos de la electrónica fundamental, en beneficio del trabajo se logró definir formulas muy importantes.


## 6. Bibliografía

* Floyd, T.(2007). Principios de circuitos electricos(Octava edi). México Pearson




























