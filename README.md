# InformeLaboratorio5

1. OBJETIVOS

Objetivo General:

* Realizar una simulación y comprobar el Teorema de Thévenin en un circuito resistivo. 

Objetivos Específicos:

* Explicar en que consiste el Teorema de Thévenin.

* Anotar los resultados del VTH Y RTH obtenidos del circuito equivalente de Thévenin.  

2. MARCO TEÓRICO 

![image](https://user-images.githubusercontent.com/93733175/149200541-b5d3f6f6-aed0-4064-a066-719b595b7812.png)

3. EXPLICACIÓN DEL PROCEDIMIENTO

![image](https://user-images.githubusercontent.com/93734334/148687457-5296c779-0821-4a1e-807a-084685e3aed6.png)

* Calculamos el voltaje y la corriente del resistor 5 usando análisis de mallas.

![image](https://user-images.githubusercontent.com/93734334/148687652-9b260482-0507-4e19-bec9-16a70ab49e36.png)

* Usamos una calculadora que nos permita calular un sistema de ecuaciones

![image](https://user-images.githubusercontent.com/93734334/148687716-e55b0bb3-4fd0-48d3-8359-fd6089c8e30a.png)

![image](https://user-images.githubusercontent.com/93734334/148687736-40e3a52a-2e6a-4799-bbc2-697746efd278.png)

* Por lo tanto se tiene que 

![image](https://user-images.githubusercontent.com/93734334/148688006-a2282100-7acd-4d44-a2ca-23108f923384.png)

![image](https://user-images.githubusercontent.com/93734334/148687965-b5e7202c-4bd8-412e-b0db-6d0db268015f.png)

* Se tiene que la corriente y el voltaje de R5 son:

![image](https://user-images.githubusercontent.com/93734334/148688033-a5e2a9d1-665c-47e2-b9fd-5c09bfb068a2.png)

* Para encontrar el volatje de Thévenin lo primero que se va a hacer es eliminar R5

![image](https://user-images.githubusercontent.com/93734334/148689038-cdd1bf39-3d70-4e31-8363-44b530067c0f.png)

* Se va a usar las ecuciones del analiss de mallas, tomando en cuando que solo va a existir dos mallas ya que en R5 caen 0V porque no hay corriente, entonces esta resistencia no va a afectar los calculos

![image](https://user-images.githubusercontent.com/93734334/148690111-dd358e87-af13-4a88-bbd5-045f6ff44c02.png)

* Usando una claculadora que nos ayude a resolver sistemas de ecuaciones.

![image](https://user-images.githubusercontent.com/93734334/148690141-1f3c0e4f-844f-409e-94c2-2289561c9066.png)

![image](https://user-images.githubusercontent.com/93734334/148690152-d562e4d5-2ec5-4bb0-9f39-cf9e8fbb5688.png)

* Por lo tanto se tiene que

![image](https://user-images.githubusercontent.com/93734334/148691027-92f4ff32-57cf-4343-9735-968a790f9edd.png)

![image](https://user-images.githubusercontent.com/93734334/148691563-b21cdd03-b948-446d-b46d-041062aaced1.png)

* Para encontrar la resistencia de Thévenin, lo primero que se va a hacer es reemplazar las fuentes de voltajes por sus resistencias internas para posteriormente encontrar las resistencia total.

![image](https://user-images.githubusercontent.com/93734334/148691894-24773115-d651-42a4-9d6e-be59fb1ee924.png)

![image](https://user-images.githubusercontent.com/93734334/148692210-12e83d46-8e64-4d5f-b555-7ee990c09f87.png)

* Enonces se tiene que el voltaje y la resistencia de Thévenin son:

![image](https://user-images.githubusercontent.com/93734334/148692257-edebce63-52d3-4c09-bc07-7dedcf4c364d.png)

* El circuito equivalente.

![image](https://user-images.githubusercontent.com/93734334/148692499-28200d07-68ba-4a3c-98eb-b867032c4324.png)

* Encontrando el voltaje y la resitencia de R5

![image](https://user-images.githubusercontent.com/93734334/148692766-4d36c2f0-ede5-4d1e-9ac5-33f6821a33a9.png)

4. RESPUESTA A INTERROGANTES Y CALCULO DEL ERROR

5.5.1. Arme el circuito que se muestra en la figura 5.1.

![image](https://user-images.githubusercontent.com/93734334/148687457-5296c779-0821-4a1e-807a-084685e3aed6.png)

5.5.2. Mida el voltaje y la corriente en el resistor R5, anote los resultados en la tabla 5.2.

![image](https://user-images.githubusercontent.com/93734334/148693094-4960c703-42b8-45f1-8ea7-8663cfddcdce.png)

5.5.3. Desconecte el resistor R5 y mida el voltaje en el circuito abierto. Anote el valor medido en la tabla 5.1.

![image](https://user-images.githubusercontent.com/93734334/148693145-180d3597-37dd-44b1-bc02-496b333311aa.png)

5.5.4. Anule el efecto de las fuentes de alimentación. Desconecte R5 y desde el circuito abierto resultante mida la resistencia equivalente. Anote el valor medido en la tabla 5.1.

![image](https://user-images.githubusercontent.com/93734334/148693177-c0cef2ea-eb55-4e64-b32d-d7dbca029d1e.png)

5.5.5. Implemente el circuito equivalente de Thévenin, agregue el resistor R5 y mida la corriente y el voltaje en el mismo, anote los resultados en la tabla 5.2.

![image](https://user-images.githubusercontent.com/93734334/149236330-1fb54bd2-fe01-45a2-b0d8-60ab782bceb4.png)

Tabla 5.1. Valores del Circuito Equivalente de Thévenin

![image](https://user-images.githubusercontent.com/93734334/148693627-57de7d92-40c7-44b3-97ff-257e85d93637.png)

Tabla 5.2. Comprobación del Teorema de Thévenin.

![image](https://user-images.githubusercontent.com/93734334/149236386-19a9451b-7b65-4b11-84f5-a5a0d4badccc.png)

* Como se observa, en los valores tanto de la tabla 5.1, como los de la tabla 5.2, los valores calculados y los valores medidos en el simulador no difieren, es decir que no existe error.

(3.89-3.89/3.89) x 100

El error es de un 0%

5. VIDEO

https://youtu.be/gH6GBtD7-Uk

6. CONCLUSIONES
* EL teorema de thévenin trata de hallar un circuito equivalente con fuente de voltaje y para ello es necesario calcular el voltaje y la resistencia que se emplearan en otro circuito junto a la resistencia RL para crear un circuito que al tomar la medidas de voltaje y corriente en RL sean las mismas que las del circuito original.
* Las medidas obtenidas analiticamente y en un simulador coinciden, por lo tanto el teorema de Thevenin si funciona para hallar un circuito equivalente al determinar los valores de RTH y VTH. 

7. BIBLIOGRAFÍA

Floyd, T. (2007). Principios de circuitos eléctricos. PEARSON Educación. https://drive.google.com/file/d/15UCq2JrPEKKB8SwajlmtTcE07nMiowaK/view

RUBRICA

![](https://github.com/doalulema/InformeLaboratorio/blob/main/Laboratorio.png)
