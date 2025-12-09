# Tipos Booleanos en Python

Este módulo introduce los tipos booleanos en Python, fundamentales para la lógica y la programación condicional. Comprender cómo funcionan los booleanos es esencial para construir programas que tomen decisiones basadas en condiciones.

## Conceptos Fundamentales

Los booleanos representan valores de verdad: `True` (verdadero) o `False` (falso). Se utilizan en expresiones lógicas para controlar el flujo de ejecución del programa.

### Operadores Booleanos

Python proporciona operadores para realizar operaciones booleanas:

*   **Operadores de Comparación:**  `==`, `!=`, `<`, `>`, `<=`, `>=`.  Comparan dos valores y devuelven un booleano.
*   **Operadores Lógicos:** `and`, `or`, `not`. Combinan o niegan booleanos.

## Leyes de De Morgan

Las Leyes de De Morgan simplifican expresiones booleanas complejas.  Son útiles para optimizar el código y entender la lógica en situaciones más avanzadas.

*   **Negación del `and`:** `not A or not B = not(A and B)`
*   **Negación del `or`:** `not A and not B = not(A or B)`

El uso correcto de estas leyes permite simplificar expresiones booleanas y mejorar la legibilidad del código.
