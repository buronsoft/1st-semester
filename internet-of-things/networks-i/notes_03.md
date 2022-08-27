# Notas de Redes I (26/08/22)
## Métodos de Transmisión
- **Baseband**. Transmisión de una sola señal sin modular, es decir, digital que opcupa todo el ancho de banda de la línea de transmisión; su velocidad se expresa en b.p.s. (Trabaja con cable coaxial, STP, UTP y fibra óptica).

![Figura 01: Diagrama Baseband](images/fig_01.PNG)

- **Broadband**. Transmisión de varias señales moduladas antes de llegar a la línea transmisión. Requieren de un gran ancho de banda en la línea de transmisión; su velocidad se expresa en Hz. (Trabaja con cable coaxial y fibra óptica)

![Figura 02: Diagrama Broadband](images/fig_02.PNG)

## Topologías
Formas en las que se conectan los dispositivos de una red. 
### **Bus**
- Tipo de conexión: Multipunto
- Modo de transmisión: Half Duplex
- Método de acceso: Contención
- Método de transmisión: Baseband

![Figure 03: Topología de Bus](images/fig_03.PNG)

### **Anillo simple**
- Tipo de conexión: Multipunto
- Modo de transmisión: Half Duplex
- Método de acceso: Contención
- Método de transmisión: Baseband

![Figure 04: Topología de Anillo simple](images/fig_04.PNG)

### **Anillo doble**
- Tipo de conexión: Multipunto
- Modo de transmisión: Full Duplex
- Método de acceso: Contención 
- Método de transmisión: Baseband

![Figure 05: Topología de Anillo doble](images/fig_05.PNG)

### **Estrella**
- Tipo de conexión: Punto punto
- Modo de transmisión: Half Duplex
- Método de acceso: Contención
- Método de transmisión: Baseband

![Figure 06: Topología de Estrella](images/fig_06.PNG)

### **MAU**
- Tipo de conexión: Punto a punto
- Modo de transmisión: Full Duplex
- Método de acceso: Por poleo
- Método de transmisión: Baseband

![Figure 07: Topología MAU](images/fig_07.PNG)

### Tips rápidos
- El tipo de conexión de una topología es **Multipunto** si para cada línea de comunicación existen más de dos dispositivos. Este es el caso de todas las topologías básicas excepto las de tipo *estrella simple y doble*, las cuales son **Punto a punto**

- El modo de transmisión de una topología es **Half Duplex** si para cada conexión hay solo un canal, como es el caso de las topologías *simples, ya sea anillo o estrella, o bus*. Las otras topologías con dos canales de comunicación son **Full Duplex**.

- El método de acceso de una topología simpple será siempre **Contención o probablístico** a menos que sea una topología *MAU/estrella doble* el cual es **Por poleo o determinístico**

- El método de transmisión de una topología simple será siempre **Baseband**, ya que la comunicación se da por medio de cables de cobre con señales dígitales (incluso el UTP)