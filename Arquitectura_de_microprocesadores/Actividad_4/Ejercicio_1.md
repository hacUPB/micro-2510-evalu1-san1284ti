## 1. ¿Por qué el código del programa se almacena en la memoria Flash y no en la RAM?
El código se almacena en memoria Flash porque esta es una memoria no volátil, lo que significa que mantiene su contenido incluso cuando el dispositivo se apaga. La RAM, en cambio, es volátil y pierde su contenido al apagar el sistema. 
## 2. ¿Qué sucede si se accede a una variable en la sección BSS antes de asignarle un valor?
La sección BSS contiene variables estáticas o globales que no están inicializadas explícitamente y que se inicializan automáticamente a cero en tiempo de carga. Por lo tanto, si accedes a una variable en la sección BSS antes de asignarle un valor, el valor será cero. Esto evita valores basura o indeterminados.
## 3. ¿Cómo se podría acceder al tercer elemento de lista usando ensamblador?
Suponiendo que se tienela  dirección base de la lista almacenada en un registro (por ejemplo, R0) y que cada elemento tiene un tamaño fijo (por ejemplo, 4 bytes si es un entero), para acceder al tercer elemento haría:
LDR R1, [R0, #8]

## 4. ¿Cuál es la diferencia principal entre LDR y STR?
- LDR (Load Register): carga datos desde memoria hacia un registro. Es decir, lee un valor en memoria y lo pone en un registro.
- STR (Store Register): almacena datos desde un registro hacia la memoria. Es decir, escribe el valor de un registro en una dirección de memoria.
## 5. ¿Cómo podría enviarse este arreglo de bytes a una matriz de LEDs 8x8 para visualizar la imagen?
Se envia cada byte del arreglo a las filas o columnas de la matriz y se hace un barrido rápido para que la imagen se vea fija.