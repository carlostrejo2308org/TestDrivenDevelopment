# Test Driven Development
Test Driven Development (TDD) es un proceso de desarrollo de software el cual se enfoca en "primero las pruebas".

El ciclo de esta metodología se puede resumir de la siguiente manera:
1. Crear una prueba
2. Correr la prueba y asegurarse que falle
3. Escribir el código suficiente para hacer que la prueba pase
4. Correr las pruebas y asegurarse que todas pasen

Este proceso se repite hasta completar con la historia que nos estamos enfocando. Una vex terminado esto, se puede hacer un proceso de refactorización del código ya creado, el cual puede incluir:
- Mover el código a donde lógicamente hace mas sentido
- Eliminar duplicidad
- Renombrar variables / funciones
- Dividir funciones / métodos
- Re ordenar jerarquía de herencia / llamadas


## Lista
Utilizando el método "TDD". Crea una lista de tareas pendientes utilizando el lenguaje de programación de tu preferencia.

Una tarea esta compuesta por:
- Titulo
- Estado (definido, en progreso, en revision, terminado)
- Descripción
- Fecha límite

Un usuario de esta lista podrá ver, crear, editar o borrar cualquier tarea.

Ademas, el usuario podra cargar y guardar toda su lista en un archivo de texto.

### Bonus
Para puntos extra:
Ademas de cargar y guardar la lista en un archivo de texto, conéctela a una base de datos. No te olvides de usar también el TDD para ello.