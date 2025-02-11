# RC-Wirless
Este repositorio sirve como archivo digital de un proyecto para la creación de una Red de Comunicaciones Inalámbricas, privada y de corto alcance para usar en zonas remotas, fuera de cobertura.

---

### **Sección 1: Conceptos Básicos y Planificación**  

## **1.1 ¿Qué es una red telefónica privada?**  

Una **red telefónica privada** es un sistema de comunicación que permite a los usuarios de un grupo determinado (en este caso, una red que involucra teléfonos celulares) comunicarse entre sí sin depender de operadores externos como compañías de telefonía móvil.  

En otras palabras, los dispositivos dentro de esta red no necesitan estar conectados a redes públicas como 4G o 5G. Todo sucede dentro de la red privada, por lo tanto, no hay costos asociados a las operadoras móviles y la comunicación es más segura.

### **Ventajas principales**:  
1. **Control total sobre las conexiones**: Tú gestionas todo el tráfico de llamadas y datos dentro de la red.  
2. **Costos reducidos**: Al no depender de operadoras comerciales, ahorras en tarifas de comunicación.  
3. **Mayor privacidad**: La información no se transmite a través de redes públicas, por lo que está más protegida.  
4. **Flexibilidad y personalización**: Puedes agregar más usuarios y funciones según las necesidades de tu red.

### **¿Cómo se conectan los teléfonos celulares?**  
Los teléfonos celulares en la red privada se conectan mediante **Wi-Fi** o **redes de radiofrecuencia** configuradas específicamente para este propósito. Utilizan tecnología **VoIP (Voice over IP)** o tecnologías de comunicaciones inalámbricas, que se detallarán más adelante.

---

## **1.2 ¿Cómo funcionan las telecomunicaciones inalámbricas?**  

Las telecomunicaciones inalámbricas transmiten información a través de **ondas de radio**. Estas ondas viajan a través del aire y se reciben mediante **antenas** o **puntos de acceso**. El proceso de transmisión y recepción ocurre en frecuencias específicas.  

### **Componentes principales de la red inalámbrica**:  
- **Antenas**: Son las encargadas de emitir y recibir las señales de radio.  
- **Repetidores**: Amplifican la señal para que llegue más lejos y sin perder calidad, especialmente en áreas grandes o con obstáculos.  
- **Servidor PBX (Private Branch Exchange)**: Este servidor gestiona las llamadas dentro de la red privada. Piensa en él como el **intercambiador central** que decide qué teléfono llama a qué otro.

### **Funcionamiento de la red**:  
1. Las **antenas** emiten ondas de radio que contienen las señales de voz o datos.  
2. Los teléfonos conectados a la red reciben estas señales mediante antenas receptoras.  
3. El **servidor PBX** organiza el tráfico de llamadas entre los usuarios. Si hay una llamada, el PBX se asegura de que se enrute correctamente dentro de la red.  

Este sistema no depende de cables, por lo que puedes mover y agregar teléfonos fácilmente sin tener que cambiar las conexiones físicas.

---

## **1.3 Bandas de uso libre y su importancia**  

Las **bandas de frecuencia** son rangos de ondas de radio utilizadas para transmitir señales. Algunas bandas están disponibles para su uso **sin necesidad de pagar licencias** a organismos gubernamentales. Estas se llaman **bandas de uso libre**.

### **Bandas de uso libre más comunes**:  
- **2.4 GHz y 5 GHz**: Estas frecuencias son utilizadas para **Wi-Fi**. Son ideales para cubrir áreas de corto a mediano alcance, y son perfectas para la comunicación de voz y datos dentro de la red privada.  
- **915 MHz**: Utilizada para **comunicaciones de largo alcance**. Se usa para sistemas como LoRa (Long Range), que son perfectos para conectar dispositivos a grandes distancias.  
- **433 MHz**: Es una frecuencia más baja que puede ser usada para aplicaciones de **bajo consumo de energía**, como sensores o dispositivos IoT.

### **¿Por qué usar estas bandas?**  
Usar **frecuencias libres** te permite construir la red sin necesidad de pagar a operadoras, lo que reduce enormemente el costo. Además, estas frecuencias están reguladas para evitar interferencias, lo que te permite operar de forma segura y legal.

---

## **1.4 Planificación del alcance y cobertura de la red**  

Antes de comenzar a construir la red, es crucial planificar ciertos elementos para asegurarte de que la cobertura sea adecuada. Aquí tienes los pasos fundamentales:

### **Pasos para la planificación**:  

1. **Ubicación de las antenas**: Las **antenas** deben estar en **lugares altos** para obtener la mejor cobertura posible. Si es posible, ponlas en techos, postes o estructuras elevadas. Esto ayudará a que la señal viaje más lejos sin obstáculos.  
2. **Cantidad de repetidores**: Si el área a cubrir es grande, necesitarás **repetidores**. Estos amplifican la señal y permiten que llegue a lugares más alejados, sin perder calidad. Si la zona es pequeña, con solo una antena y un repetidor podría ser suficiente.  
3. **Selección de la frecuencia adecuada**: Las frecuencias más altas (como 5 GHz) ofrecen mayor velocidad pero menor alcance. Las frecuencias más bajas (como 915 MHz) tienen un alcance más largo pero una velocidad menor.  

### **Redes de cobertura local**:  
Si la red solo cubrirá una zona pequeña (como una casa, oficina o comunidad), entonces **antenas Wi-Fi** y **repetidores básicos** deberían ser suficientes. Esto se conoce como una red de **corto alcance**.

### **Redes de cobertura extensa**:  
Si la red debe cubrir áreas más grandes (como diferentes edificios o zonas rurales), puedes considerar el uso de **globos aerostáticos** o **drones de comunicaciones**. Estos dispositivos flotantes pueden actuar como **puntos de acceso flotantes**, proporcionando cobertura en áreas muy amplias. Esto se explicará más adelante, en la sección sobre alternativas a satélites.

---
