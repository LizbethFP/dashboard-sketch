# Dibujar sketch de dashboard

* **Track:** _Common Core_
* **Curso:** _Creando un sitio web interactivo con JavaScript_
* **Unidad:** _Intro a User Experience Design_

## Objetivo
---
El reto consiste en dibujar el sketch de un dashboard de Laboratoria al tener en cuenta lo siguiente:

El dashboard es una herramienta utilizada por profesores, training managers, directores y gerentes de Laboratoria para ver rápidamente qué está pasando en el salón de clases de Laboratoria. En el dashboard, los usuarios mencionados pueden ver rápidamente estadísticas y datos en tiempo real como:

1. Número de alumnas inscritas
2. Número de alumnas que desertaron
3. Número y porcentaje de alumnas que pasan el criterio mínimo de evaluación
4. Promedio de notas por sprint
5. Promedio de notas HSE
6. Promedio de notas técnicas

Además, dado que Laboratoria tiene muchas generaciones, regularmente 2 generaciones por año (estas generaciones empezaron en el 2014), y que opera en 4 sedes (Arequipa, Ciudad de México, Lima y Santiago de Chile), es posible que los usuarios quieran ver datos de sedes / generaciones anteriores para poder hacer comparaciones.

### Dashboard propuesto
#### Dashboard N° 1
![Sin titulo](docs/dashboard-lab1.jpg)
En esta primera parte del dashboard, se encuentra lo siguiente:
1. Un menú desplegable a la izquierda, señalizado con un símbolo de menor, el cual contiene lo siguiente:
  1. Imagen del usuario.
  2. Notificación en la parte superior derecha de la imagen del usuario, la cual se diferencia con un color rojo de fondo.
  3. Despliegue de sedes por países y ciudades, los que se subdividen en años de promociones de manera descendente y que marcan un checkbox ovalado con fondo rojo.
  4. Una barra de íconos que comprende la configuración del usuario, acceso a las notificaciones y cerrar sesión.
2. Un título situado en el centro: "Dashboard de Laboratoria".
3. Una indicación de la sede y el año que se visita.
4. Una gráfica de la información de las estudiantes y las notas correspondientes a lo anterior, como se explica a continuación:
  1. En la primera parte, se ve la información de las estudiantes:
    1.  A la izquierda, se ve el número total de inscritas con fuente negra, el número de desertoras con fuente roja y estudiantes que continúan con fuente azul.
    2. A la derecha, se ve el número y porcentaje de aprobadas con fuente verde y el número y porcentaje de desaprobadas con fuente morada.
  2. En la segunda parte, se ve la información de las notas:
    1. El primer gráfico de fondo amarillo indica el porcentaje máximo y promedio, con fuente negra y naranja respectivamente, correspondientes a HSE.
    2. El segundo gráfico de fondo amarillo indica el porcentaje máximo y promedio, con fuente negra y naranja respectivamente, correspondientes al área técnica.
    3. El tercer gráfico de fondo amarillo indica el porcentaje máximo y promedio, con fuente negra y naranja respectivamente, correspondientes al sprint.


#### Dashboard N° 2
![Sin titulo](docs/dashboard-lab2.jpg)
En la segunda parte del dashboard, se encuentra lo siguiente:
1. Un menú desplegable a la izquierda, señalizado con un símbolo de mayor, el cual contiene lo siguiente:
  1. Imagen del usuario.
  2. Notificación en la parte superior derecha de la imagen del usuario, la cual se diferencia con un color rojo de fondo.
  3. Despliegue de sedes por países.
  4. Una barra de íconos que comprende la configuración del usuario, acceso a las notificaciones y cerrar sesión.
2. Un título situado en el centro: "Dashboard de Laboratoria".
3. Cuatro áreas de selección de opciones, como se explica a continuación:
  1. La primera presenta un despliegue de las sedes, subdividida en países y ciudades.
  2. La segunda presenta un despliegue de los años de las promociones.
  3. La tercera presenta un despliegue de las estudiantes, donde se observa el número de inscritas, número de desertoras, número de estudiantes que contiaron y el número y porcentaje de aprobadas y desaprobadas.
  4. La cuarta presenta un despliegue de las notas, donde se observa las categorías de HSE, técnico y sprint.
4. Una gráfica comparativa del número y porcentaje de aprobadas y desaprobadas de los años 2016-1 y 2016-2 entre Lima y Santiago de Chile en la categoría de sprint. En esta gráfica, se asigna el color de verde para las aprobadas y morado para las desaprobadas, lo cual se representa en la parte inferior de la gráfica a modo de leyenda.

## Contenido

Este proyecto contiene:

1. Un archivo  **`README.md`** que explica el contenido del repositorio.

2. Una carpeta `docs` donde se encuentran las imágenes que representan el dashboard de Laboratoria en formato **jpg**.

## Autora
Lizbeth Félix Peña

## Fecha
25/11/2017
