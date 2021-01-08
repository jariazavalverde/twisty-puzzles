# Rompecabezas de combinación

Colección de conmutadores y conjugados para rompecabezas de combinación. Aunque la mayoría de estos algoritmos no son prácticos para *speedcubing*, la ventaja es que una vez entendida la idea subyacente, no es necesario memorizarlos.

## Lista de rompecabezas

* [Venganza de Rubik (4x4x4)](4x4x4.md)

## Notación

* El inverso se representa por el operador postfijo (`'`) en la forma `A'`, para indicar que se debe realizar la secuencia inversa de `A`.

* Un conjugado se representa por el operador infijo (`^`) en la forma `A^B`, para indicar que se debe realizar la secuencia `ABA'`, esto es: la primera secuencia `A`, seguida de la segunda secuencia `B`, seguida del inverso de la primera secuencia `A'`.

* Un conmutador se representa entre corchetes en la forma `[A, B]`, para indicar que se debe realizar la secuencia `ABA'B'`, esto es: la primera secuencia `A`, seguida de la segunda secuencia `B`, seguida del inverso de la primera secuencia `A'`, seguido del inverso de la segunda secuencia `B'`.
