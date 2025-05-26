## 1. **¿Por qué usamos un temporizador (30 ms) para validar el estado del pulsador?**
  Porque el pulsador puede generar múltiples señales erráticas  al presionarse. El retardo de 30 ms permite que estas oscilaciones se estabilicen antes de validar el estado real del botón, evitando lecturas falsas.
## 2. **En qué se diferencia una MEF de tipo Moore de una Mealy y por qué en antirrebote es más común Moore?**
 En una MEF Moore, las salidas dependen solo del estado actual. En una Mealy, dependen del estado y de las entradas. En antirrebote se prefiere Moore porque ofrece salidas estables, independientes de entradas ruidosas como un pulsador con rebote.
## 3. **¿Cómo podrías escalar este código para manejar múltiples pulsadores en simultáneo?**
 Creando una estructura de datos que contenga el estado y temporizador de cada pulsador, y adaptando la función de actualización para recorrer y procesar todos los botones individualmente.

## 4. **¿Por qué es importante actualizar el `lastChangeTime` cuando se pasa a un estado de debounce?**

Esta variable marca el momento en que comenzó el rebote. Al actualizarla, se establece el punto de referencia para esperar los 30 ms antes de aceptar un cambio de estado, asegurando una lectura estable.