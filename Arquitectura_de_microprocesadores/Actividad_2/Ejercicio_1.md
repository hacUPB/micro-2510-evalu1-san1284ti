## 1.  ¿Qué es y para qué sirve el mapa de memoria de un microprocesador?
El mapa de memoria de un microprocesador es una representación de la organización y distribución de la memoria en el sistema. Permite visualizar qué direcciones están reservadas para memoria RAM, ROM, dispositivos de entrada/salida y otros periféricos. Sirve para estructurar el acceso a los datos y optimizar el rendimiento del sistema al asignar correctamente los espacios de memoria.
## 2. Basándote en la figura 3, responde: 
- #### ¿Cuántos pines del bus de direcciones del MC6802 se utilizan en esta conexión? ¿Cuáles son los nombres utilizados para representarlos?

Se utilizan 16 pines del bus de direcciones en la conexión del MC6802. Los nombres que los representan son A0 a A15.
- #### ¿De qué valor es la memoria total de almacenamiento del MC6846? Incluye los cálculos que realizaste.

El MC6846 utiliza un bus de direcciones de 10 bits, lo que permite direccionar 2^10 = 1024 ubicaciones de memoria. Si cada ubicación almacena 8 bits (1 byte), la memoria total de almacenamiento del MC6846 es de 1024 bytes.
- #### ¿Cuántos bits ocupa cada dato al que se puede acceder en la memoria MC6846? ¿Cómo lo dedujiste?

Cada dato ocupa 8 bits (1 byte), ya que el MC6846 maneja un bus de datos de 8 bits, lo que significa que cada dirección de memoria almacena un byte de información.
## 3. ¿Cuáles son las características más relevantes de la arquitectura von Newman y Harvard?
- Von Neumann: Unifica memoria de datos y de instrucciones en un solo espacio. Utiliza un bus compartido para acceder tanto a datos como a código, lo que puede generar cuellos de botella.
- Harvard: Separa la memoria de datos y de instrucciones, permitiendo acceso simultáneo a ambos. Ofrece un mejor rendimiento en sistemas embebidos y aplicaciones que requieren alta velocidad de procesamiento.

## 4. ¿Cuáles son las características más relevantes de la arquitectura CISC y RISC?
- CISC (Complex Instruction Set Computing): Cuenta con un conjunto de instrucciones amplio y complejo, permitiendo ejecutar tareas con menos líneas de código. Es eficiente en procesamiento de instrucciones complejas pero puede ser más lento en ejecución debido a la decodificación compleja.
- RISC (Reduced Instruction Set Computing): Utiliza un conjunto reducido de instrucciones simples y optimizadas. Permite una ejecución más rápida gracias a la simplificación del hardware y a la optimización del uso del pipeline.

## 5. ¿Cuál es tu opinión sobre los tipos de arquitecturas que se observan en los microprocesadores?
Las arquitecturas de microprocesadores han evolucionado para adaptarse a distintas aplicaciones. La selección de una arquitectura depende del equilibrio entre complejidad, rendimiento y eficiencia energética.
