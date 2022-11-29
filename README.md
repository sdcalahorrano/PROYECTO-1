# PROYECTO 1

-Aguirre Johan

-Calahorrano Sarahi

-Lara Melany

1. OBEJTIVOS

  * Objetivo General:
    
    - Demostrar la función del potenciómetro y el transistor bipolar, mediante la elaboración de un circuito, el cual nos permitirá regular la intensidad de la luz de un diodo LED, además de controlar el encendido y el apagado del LED utilizando un fotorresistor el cual detectará el paso de luz o a su vez no detectará nada. 
    
  * Objetivos Específicos:

    - Verificar el funcionamiento de un transistor de unión bipolar en corriente directa
    - Conocer su composición, y su funcionamiento
    - Comprender la función de una fotorresistencia y el proceso que realiza
    
2. MARCO TEÓRICO

  TRANSISTOR BIPOLAR NPN 2N 3904 
  
   - Está diseñado para funcionar a bajas intensidades, bajas potencias, tensiones medias, y puede operar a velocidades razonablemente altas. 
   - Es activado por corriente positiva polarizada en la base para controlar el flujo de corriente del Colector al Emisor

  DIODOS LED 
   
  -	Es una fuente de luz que emite fotones cuando se recibe una corriente eléctrica de muy baja intensidad.
  - La terminal positiva, o ánodo, por lo general es la más larga de las dos terminales, algunos diodos leds tienen una base plana que sirve para identificar la terminal negativa, o cátodo.
  - Es importante recordar que un LED tiene una caída de voltaje de 1.5 a 2.5V al ser polarizado directamente

  FOTO RESISITENCIA

   - Su componente principal, el sulfuro de cadmio.
   - La composición química es un semiconductor que puede cambiar su resistencia según la cantidad de luz irradiada sobre él.
   - Cuanto mayor sea la intensidad de la luz que incide sobre el sulfuro de cadmio, menor será la resistencia.

  POTENCIOMETRO DE 100K
  
   - Es una resistencia de tres terminales con un contacto deslizante o giratorio que forma un divisor de tensión ajustable. 
   - Utilizado para medir el potencial eléctrico, habitualmente para controlar dispositivos eléctricos, como los controles de volumen de los equipos de audio.
   
   FUENTE DE ALIMENTACION
  
   - Es un componente esencial de cualquier dispositivo electrónico ya que es ella quien se encarga de darle vida. En cualquier equipo, por pequeño que sea, siempre hay una FA.
   
3.	EXPLICACIÓN DEL PROCEDIMIENTO

   3.1.  MATERIAL Y EQUIPO REQUERIDO
   
   - Transistor Bipolar NPN 2N 3904
   - Diodos Led
   - Foto resistencia 
   - Potenciómetro de 100K
   - Resistencia 220 ohmios
   - Resistencia 10kohmios
   - Fuente de Alimentación 9V
   
   3.2.  PROCEDIMIENTO
   
   ![image](https://user-images.githubusercontent.com/105056762/204443991-12b45d67-4797-4ffb-bfc7-345c0029ec46.png)

   - En el protoboard, el transistor se polariza a negativo en su pin emisor, en el colector se conecta dos diodos led con una conexión en serie, hasta llegar al positivo mediante una resistencia de 220Ω 
   - Se desactiva constantemente el transistor por su base, usando una foto celda o foto resistencia conectada hacia negativo, ya que el transistor se activa por una señal positiva.
   - Se envía una señal positiva mediante un potenciómetro de 100k y una resistencia de 10kΩ , la línea azul se le considera como positivo principal y la roja como positivo de los leds
   - Se conecta la resistencia y el potenciómetro en serie, hasta llegar a la base del transistor desde el pin medio del potenciómetro.
   - Se conecta la resistencia de 220Ω a los led´s, se alimenta el circuito con 9 v
   - La fotocelda al recibir luz, mantendrá apagado al transistor, pero al momento de obstruir la luz, su valor subirá, permitiendo pasar la señal positiva de las resistencias al transistor activando los led´s 

   I) SIMULAR EL CIRCUITO EN EL SOFTWARE TINKERCAD
   
   ![image](https://user-images.githubusercontent.com/105056762/204444184-646afc81-cefb-44c6-8ac5-fd513ba38556.png)
   
   II) ARMAR EL CIRCUITO CORRESPONDIENTE AL DIAGRAMA
   
   ![image](https://user-images.githubusercontent.com/105056762/204444248-d7550389-9b69-4ca2-8655-f1d63f2bc707.png)
   
   III) ANALIZAR CADA ELEMENTO DEL CIRCUITO
   
   ¿Cuál es la función de cada elemento?
   
   - TRANSISTOR 2N 3904: Funciona como un interruptor digital, al momento en que la fotorresistencia no detecta luz, la base recibe una pequeña señal la cual conecta el Emisor y el Colector.
   - FOTORESISTENCIA DE 5mm: Su función es detectar los lúmenes y enviar una señal a la base del transistor.
   - POTENCIOMETRO DE 100kΩ: Sirve para regular la sensibilidad del sensor que vendría siendo la fotorresistencia.
   - RESISTENCIA DE 10kΩ: Para enviar señal positiva, cuando el potenciómetro se encuentra en 0, provocando una división de voltaje estable. 
   - RESISTENCIA DE 220Ω: Limita la corriente que entra al Diodo Led para evitar que se queme.
   - DIODO LED: Es un indicador de que nuestro circuito electrónico funciona correctamente, se enciende a la ausencia de luz y se apaga a la presencia de lúmenes. 

4.	RESPUESTA A INTERROGANTES

¿Qué es lo que sucede cuando La fotorresistencia recibe luz?

- Cuando la luz del día ilumina la fotorresistencia, éste conduce y el voltaje en su emisor se eleva para que el nivel de voltaje en la base del transistor cause que éste no conduzca.

¿Qué es lo que sucede cuando La fotorresistencia recibe no luz?

- Cuando llega la noche, la fotorresistencia deja de conducir y el voltaje que aparece en su emisor disminuye. Es como si el fototransistor se hubiera desconectado.

5.	VIDEO

 
6.	CONCLUSIONES

    -	El transistor es un componente electrónico que ayuda a amplificar los impulsos eléctricos dando así una mayor salida de electrones para que la pieza que está conectada al final de la conexión se pueda prender si problema alguno.
    - El potenciómetro se puede definir como una resistencia regulable en un circuito eléctrico, los cuales son encontrados en la mayoría de los sistemas donde se requiere variar algún parámetro de operación, en el caso de esta práctica, la intensidad con la cual se enciende y se apaga el foco.

 7.	BIBLIOGRAFÍA
    -	MecatronicaLatam. (2019). Tecnologia Led. Recuperado de: https://www.mecatronicalatam.com/es/tutoriales/electronica/componentes-electronicos/diodo/diodo-led/
    - Practica “El Potenciómetro.” (2022). 1library.co. https://1library.co/document/zlvl80gy-practica-el-potenciometro.html 
    - Ingenieria MecaFenix. (2022). ¿Qué es una fotorresistencia.?  Recuperado de: https://www.ingmecafenix.com/automatizacion/fotoresistencia/ 
    - Arduino – UAEH. (2021). Sensores. Recuperado de: http://ceca.uaeh.edu.mx/informatica/oas_final/OA4/sensores.html 

