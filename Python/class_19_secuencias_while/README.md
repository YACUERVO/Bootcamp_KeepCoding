# Bucles While en Python

Este módulo explora el uso del bucle `while` en Python, una herramienta fundamental para la iteración. Aprenderás a comprender su estructura y cómo implementarlo eficazmente, especialmente en situaciones donde la condición de finalización no es predecible como con el bucle `for`.

## Conceptos Fundamentales

El bucle `while` permite ejecutar un bloque de código repetidamente mientras una condición sea verdadera.  Es crucial comprender cómo establecer esa condición y manejar la salida del bucle para evitar bucles infinitos.  La función `input()` es esencial para permitir que el usuario controle la condición de finalización del bucle.

## Estructura y Uso

La estructura básica de un bucle `while` es:

```python
while <expresión booleana>:
    # Código a ejecutar
La `expresión booleana` determina si el bucle continúa o finaliza.  Es vital que esta condición eventualmente se evalúe como `False` para terminar la iteración.  La función `break` permite salir del bucle prematuramente.

**Conceptos Clave:**

* Condición de interrupción: La lógica que controla la ejecución del bucle.
* Bucle infinito: Un bucle `while` sin una condición de finalización adecuada.
* Función `input()`:  Recibe entrada del usuario para influir en la condición.
* `break`:  Termina la ejecución del bucle.

El módulo proporciona un ejemplo práctico para crear una función que determina si hay al menos un número par en una lista, demostrando el uso del bucle `while` para resolver problemas donde la iteración no se basa en una secuencia predefinida.
