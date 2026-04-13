Sistema de Gestión de Tareas Pendientes


Este programa es una aplicación desarrollada en C que permite gestionar tareas organizadas por categorías,

utilizando Tipos de Datos Abstractos (TDAs) para el manejo de memoria dinámica.



La aplicacion funciona ejecutando el siguiente comando en el terminal

gcc tdas/*.c tarea1.c -Wno-unused-result -o tarea1

ese comando se encaega de compilar la tarea, ahi apareceran los errores, para iniciar la aplicacion se aplica: 

./tarea1


Este sistema cuenta con 8 opciones: 

Opción 1: Nueva Categoría. Permite registrar un nombre de categoría en el sistema. 

Opción 2: Eliminar Categoría. Elimina una categoría y todas las tareas que pertenecen a ella. 

Opción 3: Mostrar Categorías. Despliega el listado de todas las categorías creadas. 

Opción 4: Registrar Pendiente. Añade una tarea con descripción y hora de registro a una categoría existente. 

Opción 5: Atender Siguiente. Muestra y elimina la tarea más antigua que haya sido registrada. 

Opción 6: Visualización del Tablero General. Muestra todas las tareas guardadas, agrupadas por sus respectivas categorías.

Opción 7: Filtrado por Categoría. Muestra únicamente las tareas de una categoría específica que el usuario elija.

Opción 8: Salir. Finaliza la ejecución del programa . 


A continuacion hay una interaccion de prueba que podria tener cualquier usuario:

Paso 1: El usuario selecciona la opción 1 e ingresa el nombre de una nueva categoría, por ejemplo: Estudios.

Paso 2: El usuario selecciona la opción 1 e ingresa el nombre de una nueva categoría, por ejemplo: Casa.

Paso 3: El usuario selecciona la opción 4 para registrar una tarea. Ingresa la descripción: Repasar para la prueba, y la asigna a la categoría: Estudios. A las 10:00

Paso 4: El usuario selecciona la opción 4 para registrar una tarea. Ingresa la descripción: Barrer la casa y la asigna a la categoría: Casa A las 12:00

Paso 5: El usuario selecciona la opción 4 para registrar una tarea. Ingresa la descripción: Cocinar, y la asigna a la categoría: Casa A las 4:00

Paso 6: El usuario selecciona la opción 6 para ver el Tablero General y confirmar que las tareas aparezcan en orden y con su respectivo tiempo.

Paso 7: El usuario selecciona la opción 5 para Atender Siguiente, lo que muestra los datos de la tarea y la elimina de la lista de pendientes: Estudios, Repasar para la prueba, 10:00.

Paso 8: El usuario selecciona la opción 5 para Atender Siguiente, lo que muestra los datos de la tarea y la elimina de la lista de pendientes: Casa, Barrer la casa, 12:00.

Paso 9: El usuario selecciona la opción 5 para Atender Siguiente, lo que muestra los datos de la tarea y la elimina de la lista de pendientes: Casa, Cocinar, 4:00.

Paso 10: El usuario selecciona la opción 5 para Atender Siguiente, lo que muestra el mensaje ¡Libre de pendientes!.

Paso 11: El usuario selecciona la opción 8 para cerrar el sistema.
