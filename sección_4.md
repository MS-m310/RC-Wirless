
---

## **4.1 Despliegue de la Red en el Terreno**

### **1. Ubicación de las Estaciones Base (BTS/NodeB)**

**Pasos detallados**:
1️⃣ **Evaluación de Ubicación**:
   - Antes de instalar cualquier equipo, evalúa el terreno donde deseas instalar las estaciones base. El objetivo es tener una señal lo más clara posible, sin obstáculos como edificios, árboles o montañas que bloqueen la señal.
   - Idealmente, las estaciones base deben colocarse en **lugares elevados** como **techos** o **torres**. Esto maximiza el alcance de la señal.

2️⃣ **Instalación de Antenas de Estación Base**:
   - **Antena omnidireccional**: Esta antena emite señales en todas las direcciones. Se debe instalar en un **punto alto** para garantizar que la señal se distribuya de manera uniforme.
     - **Paso 1**: Usa una base robusta para fijar la antena.
     - **Paso 2**: Asegúrate de que esté orientada correctamente (hacia el cielo y sin obstáculos alrededor).
   - **Antena direccional** (si es necesario): Se utiliza si se necesita una cobertura más precisa en una dirección específica.
     - **Paso 1**: Instala la antena hacia la dirección donde se necesita más cobertura.
     - **Paso 2**: Asegúrate de que no haya obstáculos que puedan interferir con la señal.

### **2. Conexión de la Estación Base al Sistema Principal (Core Network)**

**Pasos detallados**:
1️⃣ **Cableado para Conectar la Estación Base al Core**:
   - **Cable Ethernet** o **fibra óptica** son las mejores opciones para esta conexión.
   - Si no es posible usar fibra óptica (debido a limitaciones de presupuesto o distancia), el **cable Ethernet** de alta calidad es suficiente.
   - Asegúrate de que la longitud del cable no supere los límites recomendados para evitar pérdida de señal.

2️⃣ **Instalación de Dispositivo de Core (Servidor de Control)**:
   - Este es el corazón de tu red. El **servidor de control** se conecta con las estaciones base y coordina las comunicaciones.
   - Puedes usar un **servidor físico** o una **máquina virtual**. Si deseas algo más económico, las opciones **Raspberry Pi** o **PCs de bajo costo** pueden ser suficientes.
     - **Paso 1**: Instala el software necesario para gestionar la red (por ejemplo, **OpenBTS**, **OsmoBTS**, o **FreeSwitch**).
     - **Paso 2**: Configura el servidor para que se conecte con las estaciones base a través del **trunk SIP** o el protocolo adecuado para la gestión de las llamadas y la transferencia de datos.

---
