# Unicheck

## Descripción del Problema

Los estudiantes de 2º Bachillerato de Andalucía,siempre se encuentran con la preocupación de si con la nota media que tienen, pueden entrar en la carrera de sus sueños o no, sobre todo aquellos que suelen tener una nota baja. Además, no saben qué asignaturas de la PAU les benefician más o menos y cuáles deberían preparar mejor. 

Muchos de los estudiantes no saben muy bien por dónde orientarse cuando deben elegir una carrera. Tienen asignaturas que se les dan mejor y otras que se les dan peor, pero no tienen una preferencia o elección por una carrera concreta.

## Datos necesarios

Los datos necesarios para resolver este problema los obtendremos de la página web del Distrito Único Andaluz, donde obtendremos los datos de los grados de las universidades públicas de Andalucía.

De esta fuente obtendremos principalmente la ponderación de cada asignatura(valor extra de una asignatura para una titulación) para los distintos grados y las notas de corte o de admisión correspondientes a cada grado y curso académico.

El usuario proporcionará su nota media de Bachillerato y, dependiendo de la funcionalidad utilizada, sus calificaciones o estimaciones de las materias de la PAU.

## Funcionamiento previsto del problema

Nuestro programa necesitará extraer la información de los grados (ponderación de cada asignatura y nota de corte o admisión de cada grado) del HTML de la página del Distrito Único Andaluz.

También deberá filtrar aquellos grados en los que el usuario pueda alcanzar la nota de admisión necesaria con su nota media de Bachillerato (60%), es decir, aquellos en los que, obteniendo la máxima puntuación posible en la PAU, pueda alcanzar o superar la nota de corte correspondiente.

Por último, el programa permitirá al usuario seleccionar las asignaturas que se le dan mejor y mostrar los grados en los que dichas asignaturas tengan una mayor ponderación. 

## Juego de Rol

![Fotografía de la tarjeta de rol cliente](cliente.jpeg)

## Configuración 

![Captura del enlace por ssh con github](confi.png)


