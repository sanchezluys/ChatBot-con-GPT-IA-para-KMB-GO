# 📌 Resumen de los 4 Casos Básicos para tu Documentación

## ✅ Caso #1: Trayecto directo  

El origen del cliente coincide con el origen del registro .
El destino del cliente coincide con el destino del registro .
Incluso si ambas ciudades están en la misma provincia.

➡️ Resultado:
✅ Sí hay pasaje disponible.

## ✅ Caso #2: Escala en ruta (ida)  

El origen del cliente coincide con el origen del registro .
El destino del cliente aparece en "Puntos Intermedios" y está antes del destino final .
Las provincias son distintas.

➡️ Resultado:
✅ Sí hay pasaje disponible (viaje parcial).

## ✅ Caso #3: Subida en punto intermedio (vuelta)  

El destino del cliente coincide con el destino del registro .
El origen del cliente aparece en "Puntos Intermedios".
Las provincias son distintas.

➡️ Resultado:
✅ Sí hay pasaje disponible (viaje parcial).

## ✅ Caso #4: Ambos puntos en puntos intermedios, en orden correcto  

El origen y destino del cliente aparecen en "Puntos Intermedios".
El origen está antes que el destino  en la ruta completa.
Las provincias son distintas.

➡️ Resultado:
✅ Sí hay pasaje disponible entre esos dos puntos intermedios.


exite origen y destino:

SI HAY RUTA:

pasaje de santa rosa a cordoba
pasaje retiro a general pico
pasaje rosario a montevideo
pasaje cordoba a florianopolis
pasaje santa rosa neuquen
pasaje de camboriu a parana
pasaje santa fe a cordoba

NO HAY RUTA:

- pasaje cordoba a la pampa
- pasaje Santo Tomé a Carlos Paz

caso 1:

origen = origen del cliente
destino = ruta intermedia con diferente provincia

SI HAY RUTA:
- 

NO HAY RUTA:
pasaje retiro a trenque