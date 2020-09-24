# Tarea-MVC
Investigación ¿Que es un modelo MVC?






 # Instituto Tecnológico Milpa Alta II

 
# INGENIERÍA EN SISTEMAS COMPUTACIONALES


# Investigacion de Modelo MVC

 
# Alumnos:García Hernández Noé Antonio



# Docente: Ing. JULIO CESAR CASTOR DIAZ







El MVC es un patrón de diseño arquitectónico de software, que sirve para clasificar la información, la lógica del sistema y la interfaz que se le presenta al usuario. En este tipo de arquitectura existe un sistema central o controlador que gestiona las entradas y la salida del sistema, uno o varios modelos que se encargan de buscar los datos e información necesaria y una interfaz que muestra los resultados al usuario final.
Su fundamento es la separación del código en tres capas diferentes, acotadas por su responsabilidad, en lo que se llaman Modelos, Vistas y Controladores, o lo que es lo mismo, Model, Views & Controllers.
 
# Modelo: 
Este componente se encarga de manipular, gestionar y actualizar los datos. Si se utiliza una base de datos aquí es donde se realizan las consultas, búsquedas, filtros y actualizaciones.

# Vista: 
Este componente se encarga de mostrarle al usuario final las pantallas, ventanas, páginas y formularios; el resultado de una solicitud. Desde la perspectiva del programador este componente es el que se encarga del frontend; la programación de la interfaz de usuario si se trata de un aplicación de escritorio, o bien, la visualización de las páginas web (CSS, HTML, HTML5 y Javascript).

# Controlador: 
Este componente se encarga de gestionar las instrucciones que se reciben, atenderlas y procesarlas. Por medio de él se comunican el modelo y la vista: solicitando los datos necesarios; manipulándolos para obtener los resultados; y entregándolos a la vista para que pueda mostrarlos.

# Framewor que utilizan el mvc son: 

Ruby: ruby on rails, Sinatra

JS : express, sails, backbone, angular

PHP: cakePhp, code Igniter, laravel

PYTHON: Django, Flask

NET: ASP MVC

# Ventajas de patrón MVC

•	El uso del patrón MVC ofrece múltiples ventajas sobre otras maneras de desarrollar aplicaciones con interfaz de usuario, y en especial para la Web

•	La clara separación de responsabilidades impuesta por el uso del patrón MVC hace que los componentes de las aplicaciones tengan sus misiones bien definidas. Por lo tanto, los sistemas serán más limpios, simples, más fácilmente mantenibles y, a la postre, más robustos.

•	Mayor velocidad de desarrollo en equipo, ya que al estar separado en tres partes tan diferenciadas, diferentes programadores pueden ocuparse de cada parte en paralelo. Esto la hace ideal para el desarrollo de aplicaciones grandes.

•	Múltiples vistas a partir del mismo modelo, pudiendo reaprovechar mucho mejor los desarrollos y asegurando consistencia entre ellas.

•	Facilidad para realización de pruebas unitarias.





# Otros variantes de los patrones de diseño

Dependiendo de su finalidad pueden ser:

•	Patrones de creación: utilizados para crear y configurar de clases y objetos.

•	Patrones estructurales: su objetivo es desacoplar las interfaces e implementar clases y objetos. Crean grupos de objetos.

•	Patrones de comportamiento: se centran en la interacción entre asociaciones de clases y objetos definiendo cómo se comunican entre sí.
 

# Observer 

Es un patrón de comportamiento que permite relacionar diferentes objetos entre si en torno a uno Principal.

# Adapter

Permite la cooperación entre clases para extender sus funcionalidades a clases de diferentes tipos, que no pueden usarlas por mecanismos comunes como la herencia.

# Decorator

Este patrón permite agregar funcionalidades o responsabilidades a objetos de forma transparente y dinámica, sin ser dependiente de la herencia en su totalidad.



Ejemplifique un modelo MVC en el lenguaje de preferencia (Se consideran la organización de los archivos)

# EL modelo a utilizar el en php 
>MVC
	>Controladores
	>Modulos
	>Views
		>Usuario
	Index.php
