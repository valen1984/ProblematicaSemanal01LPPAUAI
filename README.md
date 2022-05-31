# ProblematicaSemanal6 - Cont. Problematica 9 Javascript
# Creacion de archivo index.html, style.css y mediaqueries.css

La problemática de la clase 09 consiste en agregar una página de suscripción al diario online desarrollado en la clase 06. Manteniendo el repositorio original, agregar un nuevo archivo html que mantenga la estética del diario, su cabecera y pie de página, y que contenga un formulario de suscripción para lectores o directamente reutilizar el formulario realizado en la actividad 6. El formulario debe contener los siguientes campos: Nombre, apellido, email, contraseña, teléfono y dirección (sin ciudad y codigo postal) . Además debe contar con un botón “Enviar”. El diseño debe ser responsive, de modo que si se visualiza el formulario desde un celular se deben mostrar los campos uno abajo del otro, pero si se ve desde un monitor de PC los campos se deben mostrar separados en dos columnas, con el botón enviar solo al final del formulario y centrado en medio de las dos columnas.

Se debe validar cada campo y mostrar un mensaje de error descriptivo abajo del campo que falló. Realizar las siguientes validaciones:

Nombre y apellido: Debe tener más de 3 letras 
Email: Debe tener un formato de email válido.
Contraseña: Al menos 8 caracteres, formados por letras y números.
Teléfono: Número de al menos 7 dígitos, no aceptar espacios, guiones ni paréntesis.
Dirección: Al menos 5 caracteres, con letras, números y un espacio en el medio.


La validación de cada campo se debe realizar en el evento “blur” de cada uno de los campos. Además, si algún campo tiene un error de validación, en el evento “focus” de dicho campo debe desaparecer el mensaje porque se asume que el usuario está corrigiendo el error.

Al presionar el botón “Enviar” se debe mostrar los errores debajo de cada campo (si lo hubiera). 

En caso de que haya pasado todas las validaciones, se puede optar de mostrar el éxito de la manera que quieran (cartel emergente, cambio de color de un titulo, mensaje de éxito). Este último punto no es obligatorio.





CRITERIO DE EVALUACIÓN



En este trabajo práctico se introducen los conceptos de selectores, atributos y Layout para agregar estilos a la noticia:

Correcta implementación de flexbox para lograr diseño responsivo.
Subir el archivo al repositorio creado previamente en GitHub.


Crear la portada de un diario (página principal) sin copiar ningún diario en particular sino armar un diseño propio de portada utilizando FlexBox como principal herramienta para la creación de un Responsive Design siguiendo el concepto de Mobile First. La portada debe contener el nombre del diario, fecha, noticias principales con imágenes, título, breve descripción y link a la noticia, noticias secundarias con o sin imagen y sólo el título y link a la noticia, un menú de navegación a las diferentes secciones del diario y publicidades. La ultima sección de la barra de navegación se debe llamar "Suscribirse" y la misma nos debe dirigir a un nuevo archivo HTML, el cual va a contener un formulario con los siguientes inputs:

 

Nombre.
Apellido.
Correo electrónico.
Contraseña.
 

Tener en cuanta que si estamos en la sección del formulario, en la barra de navegación debemos tener un link que nos lleve a la página principal (HOME). El menú principal debe ser una barra horizontal con links cuando se visualiza desde una pc de escritorio, pero al mirar la web desde un celular la barra horizontal debe desaparecer y sólo mostrarse el ícono de “hamburguesa” ☰ (no es necesario que se le haga click por ahora dado que eso se resuelve con JavaScript).

El layout del diario deberá cumplir con el siguiente formato de Layout Design.

Los pasos a seguir son:

 

Crear un repositorio nuevo en GitHub.
Crear una carpeta nueva, donde se trabajará el portal de noticias.
Utilizar Git Init para iniciar Git.
Utilizar Git Remote Add para vincularlo.
Imaginar una portada de un diario que siga el concepto de Website Layout expuesto por W3School. No está permitido copiar un diario, deben crear un diseño propio.
Incluir un normalizador de css como reset.css o normalize.css para obtener consistencia en la visualización del sitio en diferentes navegadores.
Comenzar desarrollando la versión para celulares y aplicar reglas CSS Flexbox para que el mismo contenido se adapte para tablets, monitores y televisores. 
Crear el contenido de la portada del diario, con varias noticias de diferente relevancia.
Hacer commits con el progreso y subir el código al nuevo repositorio creado en el paso 3.
Habilitar Github Pages para poder visualizar la portada online desde la página de Github.
Crear un documento Readme que incluya el link de Github Pages para visualizar el resultado.
Enviar el link de Github Pages de este repositorio como respuesta a la problemática semanal.
 

ENTREGA

El resultado deberá ser subido a un repositorio nuevo en Github.

 

Breakpoints recomendados:

Celulares: min 768px
PC: min 1024px
