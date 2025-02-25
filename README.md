# HydroEdge Firmware

Este repositorio contiene el firmware para el microcontrolador **ESP8266** utilizado en el sistema hidropónico automatizado **HydroEdge**. El firmware es responsable de la gestión de sensores y actuadores, asegurando un control en tiempo real de los parámetros críticos del entorno de cultivo.

## Tecnologías Utilizadas

- **Arduino Framework**: Utilizado para desarrollar el firmware del ESP8266, proporcionando una base sólida y accesible para la programación de microcontroladores.
- **MQTT**: Protocolo de mensajería ligera utilizado para la transmisión de datos en tiempo real entre el ESP8266 y el servidor.
- **WiFi**: Integrado en el ESP8266 para la conectividad inalámbrica, permitiendo la comunicación remota con el sistema.
- **PlatformIO**: Entorno de desarrollo que facilita la gestión de proyectos, compilación, y depuración del código.

## Funcionalidades Clave

- **Gestión de Sensores**: Recopila datos de sensores de temperatura, humedad, pH, y electroconductividad (EC), enviándolos al servidor para su monitoreo.
- **Control de Actuadores**: Activa o desactiva actuadores como bombas y ventiladores en función de las condiciones del entorno.
- **Comunicación en Tiempo Real**: Utiliza MQTT para enviar datos y recibir comandos desde el servidor, garantizando un control preciso y en tiempo real.
- **Conexión WiFi**: Establece una conexión segura y estable con la red local para la transmisión de datos.
- **Configuración Personalizable**: Permite ajustar parámetros de operación y umbrales directamente desde el servidor o a través de una interfaz de usuario conectada.

## Instalación y Configuración

1. **Clonar el repositorio:**
   ```bash
   git clone https://github.com/RamaGV/HydroEdge_IoT.git
   cd HydroEdge_IoT
#   H y d r o E d g e _ I o T  
 