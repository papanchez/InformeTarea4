# InformeTarea4


1. OBJETIVOS 

* Comprender y reconocer las distintas formas en las que las resistencias se pueden presentar un circuito en serie-paralelo.

* Aplicar las diferentes leyes y fórmulas aprendidas en clases con el objetivo de resolver ejericicios,

* Entender y aplicar los teoremas de Thevenin y Norton presentados en los presentes capítulos. 

* Comprender como el proceso para realizar las conversiones Y a Delta o Delta a Y. 

2.MARCO TEÓRICO

![2](https://user-images.githubusercontent.com/116771507/208791473-229b11c6-7d23-4cb6-b9f9-4c9138fb7139.png)

![3](https://user-images.githubusercontent.com/116771507/208791497-fba7dbd6-ea02-495f-9094-516475c089b7.png)

![4](https://user-images.githubusercontent.com/116771507/208791521-69cb0e9e-3834-45cd-b74b-e3640e132c6e.png)

![7](https://user-images.githubusercontent.com/116771507/208791560-1176ca05-b679-4eaf-8219-ac27b2cfc215.png)

![8](https://user-images.githubusercontent.com/116771507/208791633-246283fc-6649-4880-9f18-afab6299f504.png)

![9](https://user-images.githubusercontent.com/116771507/208791643-1ceae257-e811-40a6-9f2f-ba4d77bcd709.png)

![10](https://user-images.githubusercontent.com/116771507/208791653-7484d85a-1370-40ab-97df-8de562d0fe3d.png)

![11](https://user-images.githubusercontent.com/116771507/208791661-4b24daf5-85c0-4b51-8b0f-d5883c7e2f03.png)

![11](https://user-images.githubusercontent.com/116771507/208791676-5a1a57f5-e07f-4d80-b07c-a0177dc28e5d.png)


3. RESOLUCIÓN DE EJERCICIOS

SECCIÓN 7–1 Identificación de relaciones en serie-paralelo

2. Visualice y trace los siguientes circuitos en serie-paralelo:

(a) Una combinación en paralelo de tres ramas, cada rama con dos resistores en serie

![image](https://user-images.githubusercontent.com/116771507/207495235-8d7ba657-8c4c-4ec0-bf39-8dc8b76e6305.png)

(b) Una combinación serie de tres circuitos en paralelo, cada circuito con dos resistores

![image](https://user-images.githubusercontent.com/116771507/207495891-6a9106aa-aeea-4410-af1c-4d9fdee71c0f.png)


4. En cada uno de los circuitos de la figura 7-63, identifique las relaciones en serie-paralelo de los resistores vistas desde la fuente.

![image](https://user-images.githubusercontent.com/116771507/207490796-0f49a01f-c88a-4afc-825d-1a80c772cca6.png)

a) Las resistencias R1 Y R3 están concetadas en serie con la combinación de R2 Y 24 que están en paralelo. 

b) La resitencia R1 está en serie con la combinación en paralelo de las resistencias R2, R3, y R4. 

c) Hay una combinación en paralelo de las resistencias R2 Y R3 con la combinación en paralelo de R4 Y R5. 

*6. Desarrolle un diagrama esquemático de la tarjeta de circuito impreso de doble cara mostrada en la figura 7-65, y marque los valores de resistor.

![image](https://user-images.githubusercontent.com/116771507/207490841-bde62bae-73fa-4213-9714-ffac975672e7.png)

![image](https://user-images.githubusercontent.com/116771507/208796257-12598417-61e2-4b56-9a89-9ca80b119e24.png)


SECCIÓN 7–2 Análisis de circuitos resistivos en serie-paralelo

8. Un cierto circuito se compone de dos resistores en paralelo. La resistencia total es de 667 Ω. Uno de los resistores es de 1.0 kΩ. ¿Cuál es el otro resistor?

R2= (R1*RT)/(R1-RT)

R2= (1*667)/(1-667)

R2= 2KΩ

10. Repita el problema 9 para cada uno de los circuitos mostrados en la figura 7-63

RT= 1KΩ||(1KΩ+2.2KΩ||3.3KΩ)= 699 Ω

RT=(1/(1+1+1/3.3+1/6.2= 406 kΩ

12. Determine la corriente a través de cada resistor en cada circuito de la figura 7-63; luego calcule cada caída de voltaje

a) IT= 1/699= 1.43 mA

I1=(2.32/3.32)*1.43= 1 mA

I2=(1/3.32)*1.43= 431 mA 

I3=(3.3/5.5)*431= 259 mA

I4= (570/3.3)=173 mA

V1= 1*1= 1V

v2=431*1=431mV

V3=259*2.2=570mV

V4= 570mV

b) V1=V2=V3=V4=2V

I1=2= 2 mA

I2=(2/3.3)= 606 mA

I3=(2/6.2)=323 mA

I4=2/1= 2mA

c) IT= (5/3.23)=1.55 mA

I5= (5.2/13.7)*1.55= 588 mA

V5= 588*3.3= 1.94 V

I6=I7= 588/2=294 mA

V6=V7=294*6.8= 2v

I8= I5= 588 mA

V6= 588*1.81= 1.6V

I1=I2= (8.5/13.7)*1.55= 962 mA

V1=V2=962*1= 692mA

I3= (4.7/14.7)*962= 308 mA

V3= V4=308*10= 3.08 V

I4= (10/14.7)*962= 654 mA


14. Determine la resistencia entre A y B en la figura 7-67 sin la fuente

![image](https://user-images.githubusercontent.com/116771507/207491067-5ecccdc0-c99f-4d65-8035-519652c60f6a.png)

RAB=(10+5.6)||4.7

RAB=15.6||4.7= 3.61 KΩ

16. Determine el voltaje en cada nodo con respecto a tierra en la figura 7-68

![image](https://user-images.githubusercontent.com/116771507/207491117-543161d8-d139-4afb-b6aa-865134358ba4.png)

NODO A

VA= (56/100+560+56)*50= 3.91 V

NODO B

VB= (56+560/100+560+56)*50= 43V

NODO C

Vc= Vs= 50V

NODO D

VD= (616*1100)*50=4.55V


18. Determine la resistencia del circuito mostrado en la figura 7-67 como se ve desde la fuente de voltaje.

RT= (10||(94.7+5.6))+(1.8||(1+1))

RT= 10||10.3+1.8||2= 5.07+947= 6.02 kΩ

20. Determine el voltaje, VAB, en la figura 7-69. 

![image](https://user-images.githubusercontent.com/116771507/207491193-66b506ee-e8e0-4733-bf4f-ea307894517b.png)

Rama Derecha: 330+600+680+100=1710 Ω

I= (1030/2740)*60.9 mA= 22.9 mA

Rama Izquierda: R=470+560=1030Ω

R= (1030/2740) *60.9= 38 mA

RT= R1+1030||1710=1640Ω

IT= 100(1.64)= 60.9 mA

22.En la figura 7-71, determine la resistencia entre el nodo A y cada uno de los demás nodos (RAB, RAC, RAD, RAE, RAF, y RAG).

![image](https://user-images.githubusercontent.com/116771507/207491317-42ce0c46-dac2-47e3-bf53-2fd4e415b957.png)

RAB= (2.2+3.3+4.7)= 1||10.2=911Ω

RAG= 4.7||(1+2.2+3.3)=2.73kΩ

RAC= (1+2.2)||(3.3+4.7)= 2.29KΩ

RAD= 2.29+1||10.2=320KΩ

RAF= 2.29+4.7||6.5=5.02KΩ

* 24. Determine el valor de cada resistor mostrado en la figura 7-73

![image](https://user-images.githubusercontent.com/116771507/207491357-40661a34-ef08-47a1-b828-da310438e5d4.png)

V2=V5-V6= 5V-1V= 4V

I2=I5= 2W/4V= 0.5A

I5= I8-I6= 1A-0.5A= 0.5A

I1= I2+I5+I4 = 0.5 A+0.5 A+ 1A= 2A

I3= IT-I1=4A-2A=2A

V7= Vs-V3=40V-20V=20V

V1= 20W/2A=10V

V4= V3-V1=10V

V8=V4-V5= 5V

R1= 10/2=5Ω;        R2= 4/0.5=8Ω;        R3= 20/2= 10Ω

R4=10/1=10Ω;        R5=5/0.5= 10Ω;       R6=1/0.5=2Ω

R7=20/4=5Ω;         R8=5/1=5Ω

SECCIÓN 7–3 Divisores de voltaje con cargas resistivas

26. La salida de una batería de 12 V se divide para obtener dos voltajes de salida. Se utilizan tres resistores de 3.3 kΩ para proporcionar dos tomas. Determine los voltajes de salida. Si se conecta una carga de 10 kΩ a la más alta de las salidas, ¿cuál será su valor con carga?

VA= (6.6/9.9)*12= 8V

VB= (3.3/9.9)*12= 4V

Con 10 kΩ:

RAB= (6.6*10/6.6+10)=3.98KΩ

VA= (3.98/7.28)*12= 6.56 V

28. En la figura 7-74, determine el voltaje de salida sin carga entre las terminales de salida. Con una carga de 100 kΩ conectada de A a B, ¿cuál es el voltaje de salida?

![image](https://user-images.githubusercontent.com/116771507/207491564-96fd8d8d-639d-4eaa-899d-ec229983d52b.png)

RT= 10+5.6+2.7= 18.3KΩ

Vsalida= (R2+R3)/(R1+R2+R3)*Vs= (8.3/18.33)*22=9.98V

con 100kΩ

RT= R1+(R2+R3)RL/R2+R3+RL= 10KΩ+8.3*100/108.3=17.7KΩ

Vsalida= 7.7/17.7*22=9.57 V

30. En la figura 7-74, determine la corriente continua extraída de la fuente sin carga entre las terminales de salida. Con una carga de 33 kÆ, ¿cuál es la corriente extraída?

RT= 10+5.6+2.7= 18.3 kΩ

I= 22/18.3= 1.2 mA

RT= 10+8.3*33/8.33+33=16.6kΩ

I= 22/16.6= 1.33mA

32. El divisor de voltaje de la figura 7-75 tiene una carga controlada por interruptor. Determine el voltaje en cada toma (V1, V2 y V3) para cada posición del interruptor.

![image](https://user-images.githubusercontent.com/116771507/207491667-b54ff985-61ac-4aab-bb67-1dd8d110519e.png)

Posición 1:

RT= 10+30

68=10+20.82=30.8 KΩ

V1=(20.8/30.8)*120= 81 V

V2= (20/30)*81=54V

V3=(10/30)*81= 27V

Posición 2:

RT=20+20

68=20+15.5=35.5 KΩ

V1= (10+15.5)/35.5*120= 86.2V

V2= (15.5/35.5)*81=52.4V

V3= (10/20)*52.4=26.2V

POSICIÓN 3:

RT= 30+10

68=30+8.72=38.7

V1=(20+8.72)/38.7*120=89V

V2= (10+8.72)/38.7*81=58V

V3= (8.72/38.7)*81= 27V

*34. Diseñe un divisor de voltaje que produzca una salida de 6 V sin carga y un mínimo de 5.5 V entre los extremos de una carga de 1.0 kÆ. El voltaje de fuente es de 24 V y la corriente extraída sin carga no debe exceder de 100 mA

Imax= 100mA

RT= 24/100=240 Ω

(R2/RT)*24V=6V

24R2=6RT

R2= 6*240/24=60Ω

R1= 240-60=180Ω

RL=60Ω

1000Ω=56.6Ω

Vsalida= 56.6/180+56.6*24= 5.74V

SECCIÓN 7–4 Efecto de carga de un voltímetro

36. Determine la resistencia interna de un voltímetro de 20,000 Æ/V en cada uno de los siguientes ajustes
de intervalo.

(a) 0.5 V; R=20000Ω/0.5V= 10KΩ

(b) 1 V; R=20000Ω/1V= 20KΩ

(c) 5 V;  R=20000Ω/5V= 100KΩ

(d) 50 V;  R=20000Ω/50V= 1MΩ

(e) 100 V; R=20000Ω/100V= 2MΩ

(f) 1000 V; R=20000Ω/1000V= 20MΩ

38. Repita el problema 37 si se utiliza el voltímetro para medir voltaje entre los extremos de R4 en el circuito de la figura 7-62(b).

![image](https://user-images.githubusercontent.com/116771507/207491920-55b4c367-1770-4493-ac08-fc60b7888e35.png)

VR4= (R2||R3||R4)(R2||R3||R4+R1)3V

VR4= (99.4Ω/779.4Ω)3V=0.383V

a) Usando 0.5V el rango es de 0.383V

b) R=20000 Ω/0.5V=10KΩ

99.4Ω||10KΩ=98.4Ω

VR4= (98.4Ω/778.4Ω)3V= 0.379V

0.383V-0.379V=0.004V

SECCIÓN 7–5 Redes en escalera

40. Determine la resistencia total y el voltaje en los nodos A, B y C de la red en escalera mostrada en la figura 7-78.

![image](https://user-images.githubusercontent.com/116771507/207492009-87dbe77c-a609-418e-aaac-7d93f36dbf68.png)

RT=6.66KΩ => Va=(1.06/6.6)*18=2.86V

Vb= (1.05/2.05)*2.86= 1.47V

Vc= (1/2)*1.74=735mV

42. En la figura 7-79, ¿cuál es el voltaje entre los extremos de cada resistor con 10 V entre A y B?

![image](https://user-images.githubusercontent.com/116771507/207492048-ef5bf9e8-b253-4453-bd54-85936095191f.png)

V1=IT*R1= 16.*100=1.61V

V2=I2*R2=8.27*820=6.78V

V3=I3R3=7.84*220=1.73V

V4= I4*R4= 4.06*820=3.33V

V5= I5*R5=3.78*100=0.378V

V6=I6*R6= 3.78*680=2.57V

V7= I7*R7=3.78*100=0.378V

V8=I8*R8=7.84*220=1.73V

V9=I9*R9=16.1*100=1.61V

44. Determine VSALIDA para la red R/2R en escalera mostrada en la figura 7-81 para las siguientes condiciones:

![image](https://user-images.githubusercontent.com/116771507/207492181-4548b8ff-9b5f-492a-a2dc-26923ab388fa.png)

(a) Interruptor SW2 conectado a +12 V y los demás conectados a tierra

Vsalida= 12v/8=1.5V

(b) Interruptor SW1 conectado a +12 V y los demás conectados a tierra

Vsalida= 12V/16=0.75V

SECCIÓN 7–6 El puente Wheatstone

46. Se conecta un resistor de valor desconocido a un circuito puente Wheatstone. Los parámetros del puente en equilibrio se establecen como sigue: RV 5 18 kΩ y R2/R4 5 0.02. ¿Cuál es RX?

Rx= RV(R2/R4)=18*0.02=360Ω

48. Determine el voltaje de salida para el puente desequilibrado mostrado en la figura 7-83 a una temperatura de 60oC. La característica de resistencia según la temperatura del termistor se muestra en la figura 7-60.

![image](https://user-images.githubusercontent.com/116771507/207492499-d693d150-1dfd-4f04-9c71-b8e26ade0e67.png)

Vi= (27/32)*9=7.59V

Vj= (27/54)*9=4.5V

V=7.59-4.5=3.09V

SECCIÓN 7–7 Localización de fallas

50. ¿Son correctas las lecturas del medidor mostrado en la figura 7-85?

![image](https://user-images.githubusercontent.com/116771507/207492571-60518836-0e89-4447-b497-cd936213f606.png)

Ambas mediciones son correctas.


52. Vea los medidores ilustrados en la figura 7-87 y determine si hay una falla en el circuito. Si la hay, identifíquela.

![image](https://user-images.githubusercontent.com/116771507/207492625-0656f37d-3da8-4ee9-8448-8d6d29463945.png)

SE podría decir que el multímetro que está al lado izquierdo está incorrecto.

54. Si en la figura 7-89 R2 se abre, ¿qué voltajes se leerán en los puntos A, B y C?

Va=15V

Vb=0V

Vc=0V

![image](https://user-images.githubusercontent.com/116771507/207492668-08e45bac-809f-45a4-8481-60f24cae4d8d.png)


*SECCIÓN 8–3 Conversiones de fuente* 

2. Convierta las fuentes de voltaje prácticas de la figura 8-67 en fuentes de corriente equivalentes.

![image](https://user-images.githubusercontent.com/116771507/207493115-e1ff6e00-99ea-4704-b613-997f160a9de5.png)

a) Is= 5/100= 50A

b) Is=12/2.2= 5.45A

4. Trace los circuitos equivalentes de fuentes de voltaje y corriente para la batería tipo D del problema 3.

REq= R1+R2+R3= 70Ω+35Ω+100Ω=205Ω

I0= V0/REq=100V/205Ω=0.49A

V1= 70Ω*0.49A= 34.3V

V2= 35Ω*0.49A= 17.15V

V3= 100Ω*0.49A= 49V

6. Convierta las fuentes de corriente prácticas de la figura 8-68 en fuentes de voltaje equivalentes

![image](https://user-images.githubusercontent.com/116771507/207493224-5f0db124-d17b-4f0b-8684-feadd5a2f47f.png)

REq= 1/(1/100Ω+1/100Ω+1/100Ω+1/100Ω)= 25Ω

VR1=(R1/R1+REq)V0= (10Ω/(10Ω+25Ω))*50V= 14.3V

VREq= (25Ω/(25+10)Ω)*50V=35.7V

I1= VR1/R1=14.3V/10Ω=1.13A

I2=VREq/Req=35.7V/25Ω=1.43A

Ix=I1-I2=1.43A-1.43A=0

SECCIÓN 8–4 El teorema de superposición

8. Use el teorema de superposición para determinar la corriente a través, y el voltaje entre, los extremos de la rama R2 de la figura 8-69.

![image](https://user-images.githubusercontent.com/116771507/207493285-13dc3ba5-8ea4-4de4-a3aa-218e34a2e979.png)

Haciendo que los 3V valgan 0 => RT=1.955KΩ

IT=2/1.955=1.02mA

I2= 1.69/3.89=1.02mA=443uA

Quitando 2V => I=(2.2/3.89)1.53= 865uA

I2=(1/3.2)*865=270uA

IT= 443uA+270uA=713uA

10. Con el teorema de superposición, determine la corriente de carga en cada uno de los circuitos mostrados en la figura 8-71.

![image](https://user-images.githubusercontent.com/116771507/207493321-68eef29f-f829-4da4-bf19-7ea4d2410a10.png)

a) Pasa 1 Aa traves de RI => IT=(2.2/6.1)*1=361mA 

b) VL=(1.5/2.06)*60=43.7V

IL=(43.7/1.5)=29.1 mA

IT=0+0+29.1=29.1 mA


12. Repita el problema 11 si R2 es de 10 kÆ

![image](https://user-images.githubusercontent.com/116771507/207493365-e07d65da-6af1-4e9b-84f0-c44a4fdfd87d.png)

Volyaje de referencia máxima:

V= ((R2+R3)/(R1+R2+R3))30V-15V

V=((10KΩ+6.8KΩ)/(4.7KΩ+10KΩ+6.8KΩ))*30V-15=8.44V

Voltaje de referencia mínimo:

V=(R3/(R1+R2+R3))30V-15V

V=(6.8KΩ/(4.7KΩ+10KΩ+6.8KΩ)30V-15V=-5.51V

14. Los interruptores mostrados en la figura 8-74 se cierran en secuencia, SW1 primero. Determine la corriente a través de R4 después del cierre de cada interruptor. 

![image](https://user-images.githubusercontent.com/116771507/207493419-1bd60b0f-6f3d-4700-854c-8e316a9b0138.png)

a) IL= 12V/(5.6kΩ+18kΩ)508uA

b) 

Cuando la fuente de 12V es igual a 0

RT=5.6kΩ+8.2kΩ||18kΩ=11.2kΩ

IT=(12V/11.2kΩ)=1.07mA

IL=(8.2kΩ/26.2kΩ)*1.07mA=335uA

Cuando la fuente de 12V es igual a 0

RT=8.2kΩ+5.6kΩ||18kΩ=12.47kΩ

IT=6V/12.47kΩ=481uA

IL=(5.6kΩ/23.6kΩ)481uA=114uA

IL(Total)=335uA+114uA=449uA

C)

Cuando las fuentes de 6V y 9Y se hacen 0

RT=5.6kΩ+8.2kΩ||12kΩ||18kΩ=9.43kΩ

IT=(12V/9.43kΩ)=1.27mA

IL= (3.83kΩ/18kΩ)*1.27mA= 270uA

Cuando las fuentes de 9V y 12V se hacen 0

RT=8.2kΩ+5.6kΩ||12kΩ||18kΩ=11.35kΩ

IT=6V/11.35kΩ=529uA

Cuando las fuentes de 6V y 12 V se hacen 0

RT=12kΩ+5.6kΩ||8.2kΩ||18kΩ=14.8kΩ

IT=9V/14.85kΩ=608uA

IL= (2.81kΩ/18kΩ=608uA=95uA

IL(Total)=270uA+93uA=458uA



SECCIÓN 8–5 Teorema de Thevenin


16. Para cada uno de los circuitos de la figura 8-76, determine el equivalente de Thevenin como se ve desde las terminales A y B.

![image](https://user-images.githubusercontent.com/116771507/207493499-75633470-4e56-4cc8-a3d2-ef06c1142560.png)

a) RT= 27+75||147=76.7Ω

VT= (75/222)*25=8.45V

b) RT=100||270=73Ω

VT=(100/370)*3=811mV

c)RT=56||100=35.9KΩ

VT=(56/156)*5=1.79V

d) RT=2.2||(1+2.2)=1.3KΩ

IAB= 40.7mA

VT=40.7*2.2=89.5V

*18. Con el teorema de Thevenin, determine el voltaje entre los extremos de R4 en la figura 8-78. 

![image](https://user-images.githubusercontent.com/116771507/207493535-3251e187-4910-4f2d-a497-5337889dc7d3.png)

Quitando R4

RT=5.6||(1+1.65)=5.6||2.65=1.8kΩ

VT=(2.65/8.25)*50=16.1V

VA=13.6V

Si la fuente de voltaje vale 9 y remuevo R4, RT=1.8KΩ

I3=(2.65/8.25)*10=3.2mA

VT=3.2*5.6=17.9V

V4=(10/11.8)*17.9=15.2V

V4=13.6+15.2=28.8V

20. Determine la corriente que se dirige al punto A cuando R8 es de 1.0 kÆ, 5 kÆ, y 10 kÆ en la figura 8-80. 

![image](https://user-images.githubusercontent.com/116771507/207493581-a5aeec0d-cc2b-489b-b515-54ad6cf09257.png)

Ia= 42.8/9.72=4.41mA

Ib=42.8/10.8=3.97mA

Ic=42.8/11.78=3.66mA

22. Determine el equivalente de Thevenin del circuito mostrado en la figura 8-82 visto desde las terminales A y B.

![image](https://user-images.githubusercontent.com/116771507/207493617-965f3edf-bf3d-4cf0-a9aa-85c193eb3f1f.png)

VR3= 0.2*15=3V

R4=(10-3/0.2)=35KΩ

VA= (12/22)*10=7V

VB=7-5.46=1.54V

VT=7-5.56=1.54V

RT=5.56+10.5=15.96KΩ

SECCIÓN 8–6 Teorema de Norton

24. Con el teorema de Norton, determine la corriente que circula a través del resistor de carga RL en la figura 8-77.

![image](https://user-images.githubusercontent.com/116771507/207493691-ea0e220a-0fe1-4b79-95dc-345251454c86.png)

RN=14KΩ; RT=14KΩ

IT=32/14=2.29mA

IT=(5.6/19.2)*2.29=668uA

Ix=(5.6/15.6)*668=240uA

26. Con el teorema de Norton, determine la corriente que circula a través de R1 en la figura 8-80 cuando R8 5 8 kÆ

![image](https://user-images.githubusercontent.com/116771507/207493755-52a02b67-97d5-4c7d-abe5-ce51b114bed0.png)

RN= 6.8||(10+4.7)||(1+6.89)=4.46kΩ

RT=6.8||(4.7+10)||(1+6.89)=3.89KΩ

IT=12.3mA

I1= 3.18mA

I2= 7.07mA

I4=5.27mA

I3= 2.62 mA

IN=9.69mA

28. En la figura 8-83, reduzca el circuito entre las terminales A y B a su equivalente Norton.

![image](https://user-images.githubusercontent.com/116771507/207493784-566a2d5b-9373-428c-ab87-31592e46c32a.png)

VR3=0.2*15=3V

R4= (10-3/0.2)=35kΩ

VA= (12/22)*10=5.46V

VB= (35/50)*10=7V

VT=7-5.46=1.54V

RT=5.46+10.5=15.94KΩ

SECCIÓN 8–7 Teorema de transferencia de potencia máxima

30. En cada circuito mostrado en la figura 8-85, se tiene que transferir potencia máxima a la carga RL. Determine el valor apropiado de RL en cada caso.

![image](https://user-images.githubusercontent.com/116771507/207493829-4f2a2b4a-3ca8-4684-ba39-540f61ecec0a.png)

a) R=12Ω

b)R=8.2Ω

c)R=6.37Ω

d)R=727Ω

32. ¿Cuánta potencia se suministra a la carga cuando RL es un 10% más alta que su valor para transferencia de potencia máxima en el circuito de la figura 8-86?

![image](https://user-images.githubusercontent.com/116771507/207493850-4b26ecef-5c1b-4951-9dd4-2aa8150c4521.png)

VTH=((15||16.4)Ω/(4.7+15||16.4)Ω)*1.5V= 936mV

IL=936mV/23.4Ω=40mA

IR3= ((4.7||16.4)Ω/(15+4.7||16.4)Ω)*1mA= 196uA

VTH= (2.94mV/23.4Ω)=126mA

I=40mA+16uA=40.126mA

PL= I^2L*RL=((40.126mA)^2)*12.21Ω=19.7mW

SECCIÓN 8–8 Conversiones delta a Y (D a Y) y Y a D

34. En la figura 8-88, convierta cada red delta en una red Y

![image](https://user-images.githubusercontent.com/116771507/207493922-2527e0ba-768e-45e9-8e2e-2aa1533cd4f8.png)

a) RA= 560kΩ; RB=1500KΩ; RC=1000KΩ

R1= (560kΩ*1000kΩ)/(560+1500+1000)KΩ=183kΩ

R2=(560kΩ*1500kΩ)/(560+1500+1000)KΩ=275KΩ

R3=(1000kΩ*1500kΩ)/(560+1500+1000)KΩ=490KΩ

b)RA=1Ω; RB=2.7Ω; RC=2.2Ω

R1=(1Ω*2.7Ω)/(1+2.7+2.2)Ω=0.45Ω

R2=(1Ω*2.2Ω)/(1+2.7+2.2)Ω=0.373Ω

R3=(2.2Ω*2.7Ω)/(1+2.7+2.2)Ω=1.007Ω

* 36. Determine todas las corrientes que circulan en el circuito de la figura 8-90

![image](https://user-images.githubusercontent.com/116771507/207493950-6fdc3d7d-7a53-4043-986a-dba2fc48e6c0.png)

Ry1= (22kΩ*12kΩ)/(22+12+9.1)kΩ=6.13kΩ

Ry2=(22kΩ*9.1kΩ)/(22+12+9.1)=4.65kΩ

Ry3=(12kΩ*9.1kΩ)/(22+12+9.1)kΩ=2.53kΩ

RT= ((R1+Ry1)||(R2+Ry2))+Ry3= ((10kΩ+6.13kΩ)||(39kΩ+4.65kΩ))+2.53kΩ=14.3kΩ

IT= 136V/14.3kΩ=9.5mA

IR1-IRy1= ((39kΩ+4.65kΩ)/(10kΩ+6.13kΩ+39kΩ+4.65))*9.5mA=6.94mA

IR2=9.5mA-6.94mA=2.56mA

VB= 136V-(6.94mA*10kΩ)=66.6V

VC=136V-(2.56mA*39kΩ)=36.16V

IR4=66.6V/12kΩ=5.55mA

IR5= 36.16V/9.1kΩ=3.97mA

I3=(66.6V-36.16V)/22kΩ=1.38mA


VIDEO


CONCLUSIONES

Tras la realización de este informe puede concluir que:

* Se comprendió la forma en la que las resistencias actuan en un circuito serie paralelo, lo que fue de gran ayuda al momento de resolver los ejercicios propuesto. 

* Mediante la aplicación tanto de leyes como la Ley de Ohm y las leyes de Kirchhoff,  y formulas como la de divisor de corriente y voltaje se aprendió a resolver problemas, demostrando que muchas veces se puede encontrar una respuesta a pesar de que aparentemente puede ser imposible a simple vista, simplemente hya que hacer un análisis más detallado del circuito. 

* Los teoremas de Norton y Thevenin pueden ayudar de gran manera a la resolución de ejercicios.

* Las conversiones de delta a Y o Y a delta, son útiles en ciertas combinaciones de resistores que no se pueden manejar por medio de las ecuaciones en serie o en paralelo.


BIBLIOGRAFÍA

FLOYD, THOMAS L. Principios de circuitos eléctricos. Octava edición. PEARSON EDUCACIÓN, México, 2007.

Aprende Electrónica. (2018, 23 abril). El puente de Wheatstone. YouTube. https://www.youtube.com/watch?v=1Xm04pC-lIY

IngE Darwin. (2019, abril 24). TEOREMA DE THEVENIN (CIRCUITOS ELÉCTRICOS) / EJERCICIO 1. YouTube. https://www.youtube.com/watch?v=yoGGTfONnwE

IngE Darwin. (2019, julio 28). TEOREMA DE SUPERPOSICIÓN (circuitos eléctricos) - EJEMPLO 1. YouTube. https://www.youtube.com/watch?v=Ygx2dQIwe7Q

IngE Darwin. (2019, octubre 10). TEOREMA DE NORTON - EJERCICIO 1. YouTube. https://www.youtube.com/watch?v=PIA7oywgQR8
