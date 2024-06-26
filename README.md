Sistema de Gestión Inmobiliaria
Descripción
El Sistema de Gestión Inmobiliaria es una aplicación integral diseñada para gestionar
propiedades, ya sea para alquiler o venta. Este sistema permite la correcta gestión de
colecciones de datos y su preservación en el tiempo, facilitando la adición, modificación,
baja lógica de propiedades, así como la gestión de alquileres y ventas.
Funcionalidades Principales
● Gestión de Propiedades: Permite agregar, modificar y dar de baja (lógica)
propiedades.
● Gestión de Alquileres y Ventas: Se puede marcar una propiedad como alquilada o
vendida, gestionando los tiempos de alquiler y los boletos de compra-venta.
● Visualización y Gestión de Imágenes: El sistema está preparado para manejar
imágenes de las propiedades. Si no existen imágenes para una propiedad, el
sistema creará una carpeta donde se pueden cargar fotos. Al cerrar y reabrir el
formulario de imágenes, estas se podrán ver desde la UI.
Ejecución del Sistema
El sistema puede ser ejecutado desde tres puntos distintos, ofreciendo diferentes opciones
según las necesidades del usuario:
1. Ejecución desde el Main: Ejecutando el método main de la aplicación, se
desplegará un menú con opciones para acceder a diferentes funcionalidades del
sistema
2. Ejecución de la UI Interna: Para ejecutar únicamente la interfaz de usuario interna,
que está diseñada para el uso del personal administrativo de la inmobiliaria
3. Ejecución de la UI del Cliente: Para ejecutar únicamente la interfaz de usuario que
será visible para los clientes
Requisitos
● Java 8 o superior.
● Biblioteca Swing para interfaces gráficas.
● Librería maven
● Libreria jdk20
● Librería ApachePDF
Uso
Menú Principal
Al ejecutar el main, se presenta un menú que permite al usuario seleccionar entre las 2 UIs.
Interfaz de Usuario Interna
Esta interfaz está destinada al personal administrativo de la inmobiliaria. Aquí se pueden
realizar todas las operaciones relacionadas con la gestión de propiedades, alquileres y
ventas. Se puede ejecutar desde la clase InmobiliariaUI
Interfaz de Usuario del Cliente
Esta interfaz está diseñada para los clientes, permitiéndoles buscar y visualizar propiedades
disponibles para alquiler o venta. Se puede ejecutar desde la clase ClienteUI
Gestión de Imágenes
Para cada propiedad, el sistema permite gestionar imágenes. Si no existen imágenes, se
creará una carpeta específica para que el usuario pueda cargar fotos. Al reabrir el formulario
de imágenes, estas se podrán visualizar desde la interfaz de usuario.
