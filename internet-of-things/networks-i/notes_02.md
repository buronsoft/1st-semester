# Notas de Redes I (24/08/22)
## Métodos de Acceso
Es el procedimiento que sigue un dispositivo dentro de una red para acceder a los servicios de la misma. En redes solamente existen dos métodos de acceso:
- **Método por contención** (probabilístico, 99%)
    1. Solamente un dispositivo de la red puede transmitir a la vez. 
    2. El dispositivo transmitirá cuando el canal o medio de transmisión se encuentre *libre* (esto es, sin transmisiones).
    3. Si dos o más equipos transmiten simultáneamente se produce una *colisión* (esto es, una degradación de información).
    4. Después de la colisión, todos los dispositivos bloquean su transmisión por un tiempo.
    5. Una vez liberado el circuito de transmisión, transmite el primero que llegue a la línea de transmisión y se regresa al paso 2.
- **Método de acceso por poleo** (determinístico, 1%)
    - En este método se cumplen las siguientes normas:
        - Hay un administrador del sistema
        - No existen las colisiones porque los dispositivos esperan a que se termine la transmisión del anterior 
    1. Solo un dispositivo transmite en toda la red. 
    2. El dispositivo deberá cumplir con lo siguiente para transmitir:
        - Debe tener *jerarquía*
        - Debe tener *permiso*
        - Debe tener *tiempo*
    3. Si deja de cumplir con alguno de los elementos anteriores, no puede transmitir.
    4. Se entrega el turno al siguiente equipo o dispositivo en la jerarquía. Se regresa al paso 2 y se continúa el cíclo.

### Comparaciones entre los métodos de acceso

| Método por poleo                           | Método por contención |
|--------------------------------------------|-----------------------|
| Armadora de bienes en líneas de producción | Resto del mundo       |
| Aeropuertos                                |                       |
| Sistema Financiero Word                    |                       |

## Tipos de conexión
En las redes solo existen dos formas de conectar los equipos. 
- **Punto a Punto**
    - Cuando un dispositivo se conecta a otro sin ningún intermediario
- **Multipunto**
    - Cuando más de dos dispositivos compartan el canal de comunicación

## Modos de transmisión
Se refiere al sentido que la información toma para viajar de un dispositivo a otro
- **Simplex**: Cuando solo hay difusión de información y no hay retorno.
- **Half Duplex**: Cuando hay transmisión y recepeción sobre un mismo canal.
- **Full Duplex**: Cuando hay transmisión y recepción en dos canales diferentes.

## Próximamente...
Métodos de transmisión