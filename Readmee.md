
#  Dashboard de Productividad Personal

Proyecto **Grupo 3: Cofradía de Korotkevich** como práctica de la semana de JavaScript.  
Este dashboard fue creado con el objetivo de aprender conceptos clave como variables,botones, condicionales, funciones, estructuras repetitivas, manipulación del DOM y estructuras de datos de JavaScript, aplicados en una sola página web.



##  Descripción general

La interfaz está compuesta por **6 botones**, cada uno con una funcionalidad específica, desarrollada por un integrante del equipo. El diseño es minimalista y funcional, usando **HTML**, **CSS básico** y **JavaScript puro**, sin librerías externas.

---

##  Funcionalidades


* Andrés Restrepo
Botón contador de tareas
Incrementa un contador cada vez que se presiona.
Además, muestra mensajes personalizados como advertencia cuando se llega a 3 y 5 clics.
Hace uso de una variable global, if, y modificación dinámica del DOM.

Botón para mostrar días de la semana
Al hacer clic, se genera dinámicamente una lista con los días de la semana.
Usa un array y un bucle for para crear y mostrar cada día como un elemento li en el DOM.


* Juan David González
Botón para añadir tareas
Valida si el usuario escribió algo en el campo de texto:
Si está vacío: muestra un mensaje de advertencia.
Si tiene contenido: confirma que la tarea fue añadida correctamente.
Luego lo añade a la lista de tareas por hacer de la semana.
Utiliza trim(), condiciones truthy/falsy y clases CSS para el estilo del mensaje.

* Roxana Naranjo
Muestra un consejo de productividad aleatorio al hacer clic.
Utiliza un array de tips y selecciona uno al azar con Math.random() y Math.floor().
Manipula el contenido de un párrafo en pantalla.

* Cristian Henao P
Botón de saludo condicional
Este botón muestra un mensaje diferente según la hora del día.
Utiliza una función, una estructura condicional (if/else) y manipulación del DOM para mostrar saludos como "Buenos días", "Buenas tardes" o "Buenas noches".


* Juan Pablo Vargas
Botón de cambio de color de fondo
Permite cambiar el color del fondo con cada clic.
Se selecciona un color aleatoriamente desde un array predefinido utilizando condicionales y manipulación de estilos con JavaScript.

##  Tecnologías utilizadas

- JavaScript 
- HTML5
- CSS


##  Requisitos técnicos cumplidos

* Uso de variables  
* Condicionales (`if/else`)  
* Funciones reutilizables  
* Estructuras repetitivas (`for`)  
* Arrays  
* Validaciones con valores truthy/falsy  
* Manipulación del DOM  
* División de tareas y trabajo en ramas individuales desde GitHub  



##  Vista previa del proyecto

!Vista previa del dashboard  file:///C:/Users/Win10/OneDrive/Escritorio/RIWI/HTML/CELULA%20RIWI/Dashboard-de-Productividad-Personal-develop/index.htm



