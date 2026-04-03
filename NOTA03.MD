<h1 align="center">📁 Preservación y manejo de la evidencia digital</h1>

<p align="center">
  <em>Fundamentos esenciales para comprender la naturaleza, características y preservación de la evidencia digital en el ámbito forense.</em>
</p>

---

## 1.1 ¿Qué es la evidencia digital?

La evidencia digital comprende todo dato o información con potencial valor probatorio que se encuentre representado en formato digital y que pueda ser almacenado, procesado o transmitido a través de dispositivos electrónicos, sistemas informáticos o redes de comunicación.

Sin embargo, no toda información digital constituye evidencia de manera automática. Su valor probatorio dependerá de la valoración realizada por la autoridad competente o por los profesionales intervinientes en el proceso de investigación, quienes determinarán su relevancia, pertinencia y utilidad en relación con los hechos analizados.


## 1.2 Características de la evidencia digital

La evidencia digital posee características propias derivadas de su naturaleza tecnológica, las cuales representan desafíos importantes en aquellos escenarios en los que se busca garantizar su conservación, autenticidad, integridad y eventual admisibilidad.

En ese sentido, resulta fundamental aplicar técnicas forenses adecuadas y mantener una correcta cadena de custodia, a fin de preservar la información y reducir el riesgo de alteración o pérdida.

### Principales características

- **Volátil:** puede desaparecer o modificarse rápidamente, especialmente si depende del estado activo del sistema.
- **Anónima:** en determinados contextos, puede dificultar la identificación directa de su autor o fuente de origen.
- **Duplicable:** puede copiarse sin alterar aparentemente su contenido original.
- **Alterable o modificable:** puede ser editada, manipulada o transformada con relativa facilidad.
- **Eliminable:** puede ser borrada de forma intencional o accidental, aunque en algunos casos sea posible su recuperación.


## 1.3 Naturaleza de la evidencia digital

La información digital puede ser creada, procesada, almacenada, modificada, transmitida, copiada, eliminada e incluso recuperada desde diversas fuentes y sistemas. Por ello, antes de aplicar medidas de preservación, resulta necesario identificar la naturaleza de la potencial evidencia digital.

Esta identificación permite reconocer sus características particulares y establecer si corresponde a información de naturaleza **persistente**, **volátil** o **en tránsito**, lo cual es clave para definir la técnica de adquisición, preservación y análisis más adecuada.


## 1.3.1 Naturaleza persistente

Corresponde a aquellos datos o información que permanecen almacenados de forma estable en medios no volátiles, por lo que su conservación no depende de que el sistema se encuentre encendido o en ejecución. En consecuencia, este tipo de información puede subsistir luego del apagado del equipo y ser examinada posteriormente.

### Ejemplos de evidencia digital de naturaleza persistente

- Archivos de usuario, tales como documentos, hojas de cálculo, presentaciones, imágenes, videos y archivos comprimidos.
- Registros de eventos y archivos de log conservados en el sistema, como bitácoras del sistema operativo, registros de autenticación, logs de aplicaciones y eventos de seguridad.
- Artefactos de actividad del usuario almacenados localmente, como historial de navegación, cookies, descargas, caché y sesiones registradas por navegadores o aplicaciones.
- Repositorios persistentes de configuración y operación del sistema o de aplicaciones, como claves del Registro de Windows, archivos `plist` y bases de datos SQLite utilizadas por aplicaciones y sistemas.
- Mensajes, correos y otros registros almacenados localmente, como correos descargados, bases de datos de mensajería, historiales de uso y respaldos o copias de seguridad preservadas para análisis posterior.


## 1.3.2 Naturaleza volátil

Corresponde a aquellos datos o información cuya existencia, integridad o disponibilidad dependen del estado de funcionamiento del sistema. Por ello, pueden alterarse o perderse al apagarse, reiniciarse o modificarse las condiciones de ejecución del entorno tecnológico.

### Ejemplos de evidencia digital de naturaleza volátil

- Contenido de la memoria RAM, incluyendo datos temporales del sistema y de las aplicaciones que solo permanecen disponibles mientras el equipo se encuentra encendido.
- Procesos y servicios en ejecución, como aplicaciones abiertas, tareas activas del sistema y procesos asociados a actividad legítima o maliciosa observables en tiempo real.
- Conexiones de red activas, tales como sesiones TCP/UDP abiertas, puertos en uso, comunicaciones establecidas y relaciones activas entre el equipo y otros sistemas.
- Sesiones de usuario y contexto operativo activo, como usuarios conectados, sesiones iniciadas, variables de entorno y otra información dependiente del estado actual del sistema.
- Memoria de aplicaciones y datos temporales de ejecución, como fragmentos de conversaciones, claves cargadas en memoria, contenido temporal de programas y otra información mantenida únicamente durante la operación del sistema o de una aplicación.


## 1.3.3 Naturaleza en tránsito

Corresponde a aquellos datos que se encuentran circulando a través de redes, canales o servicios de comunicación al momento de su observación o captura. Su relevancia radica en que permiten analizar intercambios activos entre sistemas, usuarios, servicios o dispositivos, incluyendo tráfico, paquetes, flujos, sesiones y metadatos asociados a la comunicación.

### Ejemplos de evidencia digital de naturaleza en tránsito

- Paquetes de red capturados durante una comunicación, que permiten observar el intercambio de datos entre equipos, servicios o usuarios en un momento determinado.
- Flujos de tráfico de red, como comunicaciones entre direcciones IP, puertos, protocolos y volúmenes de transferencia observados en la red.
- Sesiones activas de comunicación, tales como conexiones web, sesiones remotas, tráfico cliente-servidor o comunicaciones entre aplicaciones distribuidas.
- Consultas y respuestas de servicios de red, como solicitudes DNS, intercambios HTTP/HTTPS, tráfico de correo o autenticaciones transmitidas entre sistemas.
- Registros derivados del monitoreo de red o de seguridad perimetral, como trazas de firewall, IDS/IPS, proxy, VPN, NDR o SIEM, que reflejan comunicaciones, intentos de conexión, transferencias o eventos detectados durante el tránsito de la información.


## Reflexión final

Comprender la evidencia digital no implica únicamente identificar archivos o datos con posible valor probatorio, sino también reconocer su comportamiento, su medio de conservación y los riesgos asociados a su alteración, pérdida o desaparición. Por ello, el manejo adecuado de la evidencia digital exige criterios técnicos, metodológicos y jurídicos que permitan preservar su integridad y autenticidad desde el primer momento de su identificación.
