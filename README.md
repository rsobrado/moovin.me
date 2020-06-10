# moovin.me
moovin.me web development assessment 

### Tecnologías a utilizar:
● Javascript
● CSS3
● HTML5
● JQuery
● Bootstrap
● API's necesarias

## Desarrollo:
Diseñar una página web ÚNICA responsive, estilo "wizard guide" u "Horizontal Slide Views" con 5 sliders (uno opcional).
NOTA 1: Se adjunta ejemplo de diseño al final del documento.
NOTA 2 : La prueba cuenta con una parte opcional.


## Moovin Mensajería Express S.R.L

### Step #1 ( Formulario )
Crear un formulario con sus respectivas validaciones y máscaras.
● Fecha (obligatorio, máscara dd-mm-yy)
● Cédula de identidad nacional (obligatorio, máscara 0 -0000-0000 )
● Teléfono (máscara 0000-0000)
● Selección de rango de edad
● Selección de sexo (obligatorio)
● Descripción (obligatorio, no más de 200 caracteres)

Agregar un botón para "simular" que se guardan los datos, al seleccionar el botón se muestra una "barra de progreso" que carga
de 0 a 100 en un tiempo aleatorio, al terminar de cargar la barra de progreso mostrar un mensaje tipo resumen, con los datos
ingresados en el formulario. Ejemplo de barra de progreso:

### Step #2 ( Tareas )
Crear un administrador de tareas.
Se debe utilizar una librería de Javascript para el efecto sortable, más NO la librería de JQuery .
Se deben crear tres columnas para representar los estados de las tareas:
● Pendientes
● En progreso
● Terminadas
Agregar un campo de texto en donde se ingresa la tarea y un botón "Crear tarea", las tareas que se crean se añaden
automáticamente a la columna de "Pendientes".
Crear mínimo 5 tareas y al menos mover una tarea a las demás columnas "En progreso y Terminadas".

### Step #3 ( Mapa )
Mostrar un mapa de Google.
Agregar una barra de autocompletar para buscar ubicaciones de manera más rápida. Al seleccionar una sugerencia de la
búsqueda mostrar una marca en ese lugar.
Al darle click en el mapa se crea una marca.
En el mapa únicamente puede haber un máximo de 2 marcas, si se crea una nueva marca se debe eliminar la marca más antigua.
Mostrar un contador del total de todas marcas que han sido agregadas.
Es opcional poder agregar la librería " Marker Clustering ", ejemplo:
Moovin Mensajería Express S.R.L

### Step #4 ( Imagen - Opcional )
Poder subir una imagen y seguidamente permitir recortarla únicamente en una relación de aspecto 1:1 (cuadrada)

### Step #5 ( Resumen )
Mostrar un resumen de los demás sliders:
● Formulario : Mostrar únicamente los datos ingresados de los campos obligatorios .
● Tareas : Mostrar las tareas de las columnas "En progreso y Terminadas".
● Mapa : Mostrar las coordenadas (latitude y longitude) de cada marca.
● Imagen (opcional): Mostrar la imagen recortada.
