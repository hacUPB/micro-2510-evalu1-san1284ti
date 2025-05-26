## 1. ¿Cuántos pines del bus de direcciones del MC6802 se utilizan en esta conexión? ¿Cuáles son los nombres utilizados para representarlos?
- El MC6802 es un microprocesador de 8 bits que utiliza un bus de direcciones de 16 bits, lo que permite direccionar hasta 64 KB de memoria.
- En esta conexión, se utilizan 13 pines del bus de direcciones, denominados A0 a A12.
- Estos pines permiten direccionar 2^13 = 8,192 direcciones (8 KB) de memoria.

## 2. ¿De qué valor es la memoria total de almacenamiento del MC6846? Incluye los cálculos que realizaste.
- El MC6846 es un circuito integrado que incluye 2 KB de ROM, 128 bytes de RAM y un temporizador programable.
- La memoria total de almacenamiento es la suma de la ROM y la RAM:
ROM: 2 KB = 2,048 bytes.
RAM: 128 bytes.
Total: 2,048 + 128 = 2,176 bytes.

## 3. ¿Cuántos bits ocupa cada dato al que se puede acceder en la memoria MC6846? ¿Cómo lo dedujiste?
- El MC6846 es un dispositivo de 8 bits, lo que significa que cada dato accesible en la memoria ocupa 8 bits (1 byte).
- Esto se deduce porque el MC6846 está diseñado para trabajar con el bus de datos de 8 bits del MC6802, lo que implica que cada acceso a la memoria maneja un byte completo.
