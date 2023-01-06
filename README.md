# PR-CTICA-No.-5-TEOREMA-DE-TH-VENIN

Integrantes:

- Jose Joaquin Silva Escobar
- Pamela Elizabeth Montatixe Almachi
- Mauricio Joseph Taco Cabrera


1. OBJETIVOS

- Definir el Teorema de Thevenin
- Aplicar el Teorema de Thevenin al circuito presentado.
- Reconocer como ayuda este Teorema al análisis de circuitos

2. MARCO TEÓRICO

TEOREMA DE THEVENIN

La forma Thevenin equivalente de cualquier circuito resistivo de dos terminales consta de una
fuente de voltaje equivalente (VTH) y una resistencia equivalente (RTH), dispuestas como indica
la figura 8-30. Los valores del voltaje y de la resistencia equivalentes dependen de los valores del
circuito original. Cualquier circuito resistivo puede ser simplificado, pese a su complejidad, con
respecto a dos terminales de salida.
El voltaje equivalente, VTH, es una parte del circuito equivalente de Thevenin completo. La
otra parte es RTH.

![image](https://user-images.githubusercontent.com/117045943/210676283-6a6f82aa-51bb-4339-a74c-f5ef62f9742b.png)

El voltaje Thevenin se expresa como sigue en este ejemplo particular:

![image](https://user-images.githubusercontent.com/117045943/210676353-9d563a4a-5a91-4895-ad43-8abb40b19e68.png)

Para encontrar el equivalente de Thevenin de cualquier circuito, se determina el voltaje equivalente, VTH, y la resistencia equivalente, RTH, vistos desde las terminales de salida. Como un
ejemplo, el equivalente de Thevenin para el circuito ubicado entre las terminales A y B se desarrolló en la figura 8-32.

![image](https://user-images.githubusercontent.com/117045943/210676406-74e75912-9e56-49d4-a4ed-528fdcbd3784.png)

Thevenización de un circuito puente 

La utilidad del teorema de Thevenin tal vez se ilustra mejor cuando se aplica a un circuito puente Wheatstone. Por ejemplo, cuando se conecta un resistor de carga a las terminales de salida de
un puente Wheatstone, como indica la figura 8-38, el circuito resulta difícil de analizar porque no
es una configuración en serie-paralelo directa. No hay resistores que estén en serie o en paralelo
con otro resistor.

![image](https://user-images.githubusercontent.com/117045943/210676482-7663d9b9-4b76-44ee-8086-c8ddf4d5784d.png)

El siguiente es un resumen de los pasos a seguir para aplicar el teorema de Thevenin:

Paso 1. Abrir las dos terminales (eliminar cualquier carga) entre las que se desea encontrar el
circuito equivalente de Thevenin.

Paso 2. Determinar el voltaje (VTH) entre las dos terminales abiertas.

Paso 3. Determinar la resistencia (RTH) entre las dos terminales abiertas con todas las fuentes
reemplazadas por sus resistencias internas (fuentes de voltaje ideales en cortocircuito

y fuentes de corriente ideales abiertas).
Paso 4. Conectar VTH y RTH en serie para producir el equivalente de Thevenin completo del
circuito original.

Paso 5. Reemplazar la carga eliminada en el paso 1 entre las terminales del circuito equivalente de Thevenin. Ahora se pueden calcular la corriente y el voltaje que haya en la
carga utilizando solamente la ley de Ohm. Tienen el mismo valor que la corriente y
el voltaje presentes en la carga del circuito original. 

3. EXPLICACIÓN DEL PROCEDIMIENTO

3.1 MATERIAL Y EQUIPO REQUERIDO

![image](https://user-images.githubusercontent.com/117045943/210269848-fd44ff45-bbf9-4d20-bb97-c00ef2b6810e.png)

3.2 Arme el circuito que se muestra en la figura 5.1.

![image](https://user-images.githubusercontent.com/117045943/210269861-14a4d7c7-55a7-486c-9ef3-fae4bc678b49.png)

3.3 Mida el voltaje y la corriente en el resistor R5

![image](https://user-images.githubusercontent.com/117045943/210269980-b44e1887-36e1-45f5-9744-910f03b0edfd.png)

![image](https://user-images.githubusercontent.com/117045943/210270022-0dbfad98-b521-41f3-9ce6-35dc2a5c81d6.png)

3.4 Desconecte el resistor R5 y mida el voltaje en el circuito abierto.

![image](https://user-images.githubusercontent.com/117045943/210659128-13f08ad1-cc20-41ab-9576-1bf99d32788a.png)

3.5 Anule el efecto de las fuentes de alimentación. Desconecte R5 y desde el circuito
abierto resultante mida la resistencia equivalente.

![image](https://user-images.githubusercontent.com/117045943/210659863-817e919a-028b-4418-b5a5-563c707df8da.png)

3.6 Implemente el circuito equivalente de Thévenin, agregue el resistor R5 y mida la
corriente y el voltaje en el mismo

![image](https://user-images.githubusercontent.com/117045943/210660703-2c9dd1cf-a057-4321-a96a-8c5d4b0adba9.png)

4. RESPUESTA A INTERROGANTES Y CALCULO DEL ERROR

4.1 Valores del Circuito Equivalente de Thévenin

![image](https://user-images.githubusercontent.com/117045943/210676053-712619d0-bab9-4db7-983d-7ce0ca11ca2d.png)

4.2 Comprobación del Teorema de Thévenin.

![image](https://user-images.githubusercontent.com/117045943/210676090-e82d1fe8-9838-421f-b7b9-e2d487ccf1ef.png)

4.3 Calculo de Error

![image](https://user-images.githubusercontent.com/117045943/210676122-89fe57cc-f2da-40ad-93ad-9ed1a1974ad1.png)
![image](https://user-images.githubusercontent.com/117045943/210676139-39e5ffe8-3db5-48b3-a252-87f80b07855c.png)

5. VIDEO

https://drive.google.com/file/d/1JVDtcWO2Zxs532KbZcoJ3sblLh5Oz7GI/view?usp=sharing

6. CONCLUSIONES

- El Theorema de Thevenin en un teorema que nos permite facilitar el análisis de circuitos ya que permite que este se simplifique.
- Para aplicar el teorema es importante conocer definiciones como Ley de Ohm, LVK y LCK.

7. BIBLIOGRAFÍA

Laboratorio de Física, I. I., & Skigin, D. Ley de Ohm y de Kirchhoff.

Floyd (8va Ed)(2007). Principios de circuitos electricos. Pearson Education
