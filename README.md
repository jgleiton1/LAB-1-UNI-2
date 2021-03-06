# LAB-1-UNI-2

1. Objetivos

1.1. Objetivo general

Analizar el circuito propuesto en la respectiva guia de laboratorios, mediante el uso de una herramienta digital  armarlo, para poder realizar los respectivos items que corresponen al trabajo. 

1.2. Objetivos específicos

Conocer la definición principal sonbre la superposición para proceguir a realizar el trabajo. 

Armar correctamente el circuito y así poder trabajar con él. 

Identificar las formulas principales para poder resolver manualmente el circuito planteado. 

2. Marco Teoríco 

![image](https://user-images.githubusercontent.com/94153604/148007000-debf8926-7a0c-45ce-b34a-b2da2ef8ada8.png)

3. Requerimientos Previos

![image](https://user-images.githubusercontent.com/93958596/148009620-469c75af-838b-486b-acd7-5c3ed40ff48c.png)
![image](https://user-images.githubusercontent.com/93958596/148009630-280717ef-b4ff-4bc8-9dcb-8dc1530fd4ba.png)
![image](https://user-images.githubusercontent.com/93958596/148009653-de50a538-18a1-485e-844b-068d05861b64.png)
![image](https://user-images.githubusercontent.com/93958596/148009666-357383ea-0f66-417e-8f2c-d25577be1500.png)
![image](https://user-images.githubusercontent.com/93958596/148009674-20c4e77d-5997-4e48-944d-207c3208cb35.png)
![image](https://user-images.githubusercontent.com/93958596/148009682-95a09dcb-4ca6-4eca-97e8-bd6e1121caac.png)
![image](https://user-images.githubusercontent.com/93958596/148009696-f302f679-5073-410f-974e-69ce7722ba12.png)


4. Materiales y Equipos Requeridos

![image](https://user-images.githubusercontent.com/93958596/148009719-8a28b48f-108e-4c44-b460-d238f9d1a56a.png)

5. Respuesta a interrogantes y calculo del error

Cuando la fuente de voltaje V2 = 0

![image](https://user-images.githubusercontent.com/93958596/148107988-1567e662-2d8b-4cd9-bccd-a8ce0c0f82e7.png)

    Para hallar la resistencia total:
      Req1 = 820 Ω + 470 Ω = 1290 Ω = 1.29 kΩ
      1/Req2 = 1/1.29 kΩ + 1/2.2 kΩ = 1.23 kΩ
      Req2 = 1/1.23 kΩ = 0.813 kΩ
      RT = 0.813 kΩ + 1 kΩ = 1.813 kΩ
    
    Aplicando la ley de OHM se halla la corriente total:
      IT = Vs / RT = 20 V / 1.813 kΩ = 11.03 mA

    Hallamos la corriente en la resistencia de 2.2 kΩ (I1) con la fórmula de divisor de corriente:
      I1 = (0.813 kΩ / 2.2 kΩ) * 11.03 mA = 4.08 mA

    Aplicando la ley de las corrientes de Kirchoff, hallamos la corriente que circula por la resistencia de 820 Ω que, en este caso es la misma corriente Ix:
      IT – I1 – Ix = 0, entonces: Ix = IT – I1 = 11.03 mA – 4.08 mA = 6.95 mA

    Ahora hallamos el voltaje VA:
      VA = 6.95 mA * 0.82 kΩ = 5.699 V = 5.7 V

    Pero como el voltaje está en sentido contrario a como circula, VA = -5.7 V y la corriente es Ix = 6.95 mA

Cuando la fuente de voltaje V1 = 0

![image](https://user-images.githubusercontent.com/93958596/148107958-bb31e687-2a92-48fb-b828-430bf3086526.png)

    Para hallar la resistencia total:
      1/Req1 = 1/1 kΩ + 1/2.2 kΩ = 1.45 kΩ
      Req1 = 1/1.45 kΩ = 0.69 kΩ
      Req2 = 0.82 kΩ + 0.69 kΩ = 1.51 kΩ
      1/RT= 1/1.51 kΩ + 1/0.47 kΩ = 2.79 kΩ
      RT = 1/2.79 kΩ = 0.36 kΩ

    Aplicando la ley de OHM se halla la corriente total:
      IT = Vs / RT = 12 V / 0.36 kΩ = 33.33 mA

    Hallamos la corriente Ix con la fórmula de divisor de corriente:
      Ix = (0.36 kΩ / 0.47 kΩ) * 33.33 mA = 25.53 mA

    Aplicando la ley de las corrientes de Kirchoff, hallamos la corriente (IA) que circula por la resistencia de 820 Ω
      IT – IA – Ix = 0, entonces: IA = IT – Ix = 33.33 mA – 25.53 mA = 7.8 mA

    Aplicando la ley de OHM hallamos el voltaje VA:
      VA = 7.8 mA * 0.82 kΩ = 6.396 V = 6.4 V

    Entonces VA = 6.4 V y la corriente Ix = 25.53 mA 

Realizando la suma algebraica entre los voltajes encontrados:

    VA = 6.4 V – 5.7 V = 0.7 V = 700 mV

Realizando la suma algebraica entre las corrientes encontradas:

    Ix = 25.53 mA + 6.52 mA = 32.05 mA

![image](https://user-images.githubusercontent.com/93958596/148009826-f2fb4d89-ca6c-434d-ad17-333e018610b2.png)

6. Video

https://www.youtube.com/watch?v=qPJ4qUvgeig

7. Conclusiones 

El metodo de superposición  es una manera de  determinar corrientes en un circuito con varias fuentes, trabajando con una fuente para ello se reemplaza por la resitencia interna de la fuente de voltaje ideal que es cero y de la fuente de correinte ideal que es infinita , por ello todas las fuentes deben ser trabajadas como ideales para que se pueda simplificar su uso.

Para armar el circuito es de gran importancia conocer a la perfección los componenes que se encuentran presentes y como se los debe conectar, para ello con el uso de una herramiente virtual como lo es tinker card es de gran utilidad , sin embargo, es fundamental analizar el circuito para que se lo arme sin nigun inconveniente. 

Primero se debe obtener la resistencia total y para ello  se debe analizar como se encuentran las resistencias ya sea en paralelo o en serio y de ello depende para aplicar cualquier formula, para hallar la corriente total se aplica directamente la le de OHM y para hallar la corriente en Ix se debe aplicar la fulmula del divisor de corriente  Ix=(RT/Rx)*IT
