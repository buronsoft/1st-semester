# Notas de Redes I (17/08)
## El modelo OSI
(Open System Interconnection) Modelo de referencia para la intercomunicación de dispositivos electrónicos. Posee 7 capas
1. Física
    - Transmite la información físicamente bit por bit.
2. Enlace
    - Se encarga de distinguir si el paquete era para el dispostivo indicado.
3. Red
    - Redirecciona la información. Se encarga de codificar remitentes y destinatarios.
4. Transporte
    - Lleva toda la información a todos lados dentro del dispositivo.
5. Sesión
    - Informa la existencia de una nueva información.
6. Presentación 
    - Algoritmo asociado con la aplicación en donde la información fue creada (extensión).
7. Aplicación
    - Es la capa donde se genera nueva información. Es la capa donde se produce un interacción con los usuarios. 

Los 7 niveles están funcionando de forma síncrona todo el tiempo. Los equipos que son desarrollados bajo el modelo de referencia OSI pueden ser: 

**DTE**: Data Terminal Equipment <br>
**DCE**: Data Communication Equipment

Decimos que el modelo OSI es un Modelo Lógico y Funcional porque cada una de las capas posee una función única e irrepetible.

## La IEEE vs el modelo OSI
En algún momento, la IEEE cuestionó el modelo de referencia OSI propuesto por la ISO. El nuevo modelo de referencia propuso una partición en la capa de enlace en dos secciones:
- MAC: Media Access Control.
- LLC: Logical Link Control.

Aunado a este cambio, se desarrolló un nuevo modelo de referencia llamado "Modelo IEEE 802" (02 - febrero, 80 - 1980) para atender los elementos que no consideró el modelo OSI, particularmente en la capa física. El modelo de referencia 802 está distribuido en comités:
- IEEE 802.1 estudia MAC
- IEEE 802.2 estudia LLC
- IEEE 802.3 estudia CSMA/CD
- IEEE 802.4 estudia Token Bus
- IEEE 802.5 estudia Token Ring
- ...
- IEEE 802.11 estudia Wireless
    - Posee subestándares: a, b, g, n, ac, ax.
- ...
- IEEE 802.22 es el estándar más reciente

## Tareas
Revisar el classroom. El profesor subirá unas asignaciones ahí.