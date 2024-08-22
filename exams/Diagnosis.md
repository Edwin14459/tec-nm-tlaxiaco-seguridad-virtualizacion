# Evaluación de Redes y Sistemas Operativos

|       Nombre:      |  Fecha:  | Matrícula: |
|--------------------|----------|------------|
|Edwin López Santiago|22/08/2024|  21620123  |

## Instrucciones

Responde las siguientes preguntas de manera clara y concisa. Cada sección tiene un peso específico, así que distribuye tu tiempo en consecuencia.

## Sección 1: Componentes de un Sistema de Red (20%)

Pregunta de Opción Múltiple:<br>
Identifica cuáles de los siguientes elementos son componentes fundamentales de un sistema de red:<br>

- [x] Switch
- [x] Router
- [ ] Monitor
- [x] Cableado
- [ ] CPU
- [x] Firewall

Pregunta Abierta:<br>
Explica la función de un router en una red y cómo se diferencia de un switch.<br>
El router es el que dirige el tráfico de datos entre diferentes redes usando direcciones IP para encontrar el mejor camino, en tanto el switch conecta dispositivos dentro de una única red local sin gestionar enrutamiento entre redes.

Pregunta de Emparejamiento:<br>
Relaciona los siguientes componentes de una red con su función principal:<br>

| Componente                      | Función principal |
|---------------------------------|-------------------|
| [D] Servidor                    | A) Protege la red de accesos no autorizados. |
| [A] Firewall                    | B) Facilita la conectividad inalámbrica. |
| [B] Punto de acceso inalámbrico | C) Transmite datos entre dispositivos de la red. |
| [C] Cable de par trenzado       | D) Proporciona recursos a los usuarios de la red. |

## Sección 2: Protocolo de Conexión TCP/IP (20%)

Pregunta Verdadero/Falso:<br>
TCP/IP es un protocolo que se utiliza exclusivamente para redes privadas, como las LANs.

- [ ] Verdadero
- [X] Falso

Justifique su respuesta.<br>
El protocolo TCP/IP es un protocolo estándar para redes, incluyendo tanto redes privadas (LANs) como redes públicas, como Internet. Ya que es el conjunto de protocolos más utilizado a nivel global para interconectar dispositivos y facilitar la comunicación entre ellos.

Pregunta Abierta:<br>
Describe las diferencias clave entre TCP y UDP en términos de fiabilidad y uso.<br>
El un protocolo TCP esta orientado a la conexión que garantiza la entrega fiable y ordenada de los datos, se utiliza en la transferencias de archivos y correos electrónicos. Por otra parte, el protocolo UDP no esta orientado a la conexión que no garantiza la entrega fiable ni el orden de los paquetes, lo que lo hace más rápido y eficiente para aplicaciones en tiempo real como juegos en línea o transmiciones en vivo, donde la velocidad es más importante que la fiabilidad.

Pregunta de Desarrollo:<br>
Explica cómo se utilizan las direcciones IP y las máscaras de subred en el protocolo TCP/IP para enrutar datos a través de una red.<br>
Las direcciones IP se identifican de manera única en cada dispositivo de una red, mientras que las máscaras de subred dividen la red en subredes más pequeñas para facilitar la gestión del tráfico y mejorar la eficiencia. En el protocolo TCP/IP, cuando un paquete de datos se envía, la dirección IP del destino y la máscara de subred se utilizan para determinar si el paquete debe ser enviado dentro de la misma subred o si necesita ser enrutado a otra subred o red externa.

## Sección 3: Normas y Estándares de la Industria (10%)

Pregunta de Selección Múltiple:<br>
¿Cuál de los siguientes es un estándar de la industria para redes inalámbricas?<br>

- [ ] IEEE 802.3
- [X] IEEE 802.11
- [ ] IEEE 802.15
- [ ] IEEE 802.16

Pregunta de Desarrollo:<br>
Explica la importancia de seguir normas y estándares de la industria al diseñar redes en una organización. Proporcione ejemplos de dos normas específicas.<br>
Las normas y estándares de la industria son la clave en el diseño de redes porque aseguran que los dispositivos de diferentes fabricantes sean compatibles y puedan comunicarse entre sí de manera segura. Esto facilita que la red crezca y se adapte a nuevas tecnologías sin complicaciones.

Ejemplos:
Norma IEEE 802.3: Establece las normas para la transmisión de datos a través de cables de red Ethernet, garantizando que todos los dispositivos conectados puedan comunicarse de manera eficiente y con mínimas interferencias.

Estandar ISO/IEC 27001: Es un estándar internacional para la gestión de la seguridad de la información, asegurando que las redes estén protegidas contra amenazas y cumplan con los requisitos legales y regulatorios.

Pregunta de Análisis de Caso:<br>
Una empresa está planeando la expansión de su red. Describe cómo aplicarías las normas y estándares de la industria para garantizar la compatibilidad y el rendimiento.<br>
Pues apliacaria lo siguiente:
1.- Cableado: Usar normas para asegurar la calidad y durabilidad del cableado.
2.- Protocolos de Red: Implementa TCP/IP para la comunicación eficaz entre dispositivos.
3.- Seguridad: Aplicar estándares  para proteger la red y la información.
4.- Compatibilidad de Equipos: Verifica que los dispositivos sean compatibles y soporten los protocolos necesarios.
5.- Gestión de Redes: Usar protocolos simples de redes de gestión para una supervisión y control eficientes.

## Sección 4: Sistemas Operativos (10%)

Pregunta de Comparación:<br>
Compara las características principales de dos sistemas operativos populares (por ejemplo, Windows y Linux) en el contexto de su uso en redes.<br>
* Windows: Es conocido por su facilidad de uso, interfaz gráfica intuitiva y amplia compatibilidad con aplicaciones comerciales. Ofrece herramientas integradas como Active Directory para la gestión de redes y usuarios, lo que lo hace ideal para entornos empresariales con necesidades de administración centralizada.
* Linux: Es reconocido por su estabilidad, seguridad y flexibilidad. Es altamente configurable, lo que permite a los administradores de red personalizar el entorno según las necesidades específicas de la organización. Además, es una opción popular para servidores debido a su rendimiento eficiente y robusto.

Pregunta Abierta:<br>
Explica cómo se puede seleccionar un sistema operativo adecuado para un servidor en una organización.<br>
La elección del sistema operativo para un servidor depende de las necesidades de la organización, las aplicaciones a ejecutar, el presupuesto y las habilidades del equipo de Tecnologias de la Información. Windows Server es ideal para entornos fáciles de gestionar con soporte para aplicaciones comerciales, mientras que Linux ofrece más seguridad, estabilidad y flexibilidad. También se deben considerar el soporte técnico y las actualizaciones de seguridad.

Pregunta de Opción Múltiple:<br>
¿Cuál de los siguientes sistemas operativos es conocido por su estabilidad y seguridad en entornos de red?<br>

- [ ] Windows Server
- [ ] macOS
- [X] Linux
- [ ] Android

## Sección 5: Diseño de Redes Aplicando Normas y Estándares (10%)

Pregunta de Escenario:<br>
Tienes la tarea de diseñar una red para una oficina de 100 empleados. Describe los pasos que tomarías para asegurarte de que el diseño cumpla con las normas y estándares vigentes.<br>
1.- Recolección de Requisitos: Analizar las necesidades de la oficina, como dispositivos, aplicaciones, seguridad y escalabilidad.
2.- Selección de Normas: Asegurar que la red cumpla con normas como IEEE 802.11 para inalámbricas y IEEE 802.3 para cableadas.
3.- Planificación de la Infraestructura: Diseñar la topología con redundancia y sin puntos únicos de fallo.
4.-Implementación de Seguridad: Adoptar normas como ISO/IEC 27001 para proteger la red de amenazas.
5.- Pruebas y Validación: Realizar pruebas exhaustivas para garantizar el funcionamiento correcto y cumplimiento de estándares antes de la implementación.

Pregunta de Desarrollo:<br>
Explica el impacto de no seguir normas y estándares oficiales en el diseño de una red. Proporciona ejemplos de posibles problemas.<br>
Al no seguir normas y estándares en el diseño de una red puede causar lo siguiente:
- Problemas de interoperabilidad: Dispositivos incompatibles entre sí.
- Compatibilidad limitada: Protocolos no estándar pueden impedir la conexión de dispositivos.
- Riesgos de seguridad: Vulnerabilidades debido a estándares de seguridad no actualizados.
- Dificultades en mantenimiento y escalabilidad: Diseño caótico que complica la expansión y el mantenimiento.
- Rendimiento ineficiente: Problemas en la calidad de servicios.
- Soporte técnico complicado: Mayor dificultad para diagnosticar y solucionar problemas.

## Sección 6: Metodologías para el Análisis, Diseño e Instalación de Redes (10%)

Pregunta de Ensayo Corto:<br>
Describe brevemente una metodología comúnmente utilizada en el análisis y diseño de redes, como la metodología OSI.<br>
El modelo OSI divide la arquitectura de la red en siete capas, desde la física hasta la de aplicación, para estructurar el diseño y desarrollo de redes. Este enfoque facilita la identificación de problemas y mejora la compatibilidad e interoperabilidad entre sistemas.

Pregunta de Caso Práctico:<br>
Un cliente te ha pedido que diseñes e instales una red para su nueva sucursal. Explica cómo utilizarías una metodología para abordar este proyecto, desde el análisis de requerimientos hasta la instalación.<br>
Primero, analizaría los requerimientos del cliente, como usuarios, dispositivos y aplicaciones. Luego, diseñaría la red usando el modelo OSI, asegurando que cada capa cumpla con normas y estándares. Durante la instalación, seguiría una estructura ordenada desde el cableado hasta la configuración de protocolos. Finalmente, realizaría pruebas para garantizar que todo funcione según los objetivos del cliente.

## Sección 7: Seguridad en Redes (10%)

Pregunta de Opción Múltiple:<br>
¿Cuál de las siguientes medidas es más efectiva para proteger una red de accesos no autorizados?<br>

- [X] Cortafuegos
- [ ] Antivirus
- [ ] Actualizaciones de software
- [ ] Contraseñas seguras

Seleccione la respuesta correcta.

Pregunta de Desarrollo:<br>
Explica la importancia de implementar medidas de seguridad en una red y cómo estas pueden proteger la información confidencial de una organización.<br>
Implementar medidas de seguridad en una red es esencial para proteger la información de una organización, prevenir accesos no autorizados y amenazas cibernéticas, y asegurar que solo usuarios autorizados accedan a recursos sensibles. Esto también garantiza la continuidad del negocio y protege la reputación de la organización.

## Sección 8: Resolución de Problemas en Redes (10%)

Pregunta de Caso Práctico:<br>
Un usuario informa que no puede acceder a Internet desde su computadora. Describe los pasos que seguirías para identificar y resolver el problema.<br>
1.- Verificar la Conexión Física: Asegurarse de que todos los cables estén correctamente conectados y que el adaptador de red esté habilitado.
2.- Comprobar la Configuración de la Red: Revisar las configuraciones de IP, DNS y gateway en la computadora para asegurarse de que estén correctas.
3.- Diagnóstico del Sistema: Utilizar herramientas de diagnóstico como "ping" para verificar la conectividad con otros dispositivos en la red y con el servidor DNS.
4.- Reiniciar Equipos de Red: Reiniciar el router o el switch al que está conectada la computadora, en caso de que el problema sea general.
5.- Pruebas Adicionales: Si el problema persiste, probar con otro dispositivo o conexión para descartar fallos en el hardware de la computadora.

Pregunta de Desarrollo:<br>
Explica la importancia de tener habilidades para la resolución de problemas en redes y cómo estas pueden impactar en la eficiencia y productividad de una organización.<br>
Tener habilidades para resolver problemas de redes es crucial para mantener la operación continua de una organización, minimizando el tiempo de inactividad y su impacto en la productividad e ingresos, además de mejorar la confianza en el sistema y asegurar un entorno de trabajo estable.