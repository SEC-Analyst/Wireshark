# Analisis de compromiso en servidor Apache Tomcat - Investigacion de shell inversa y persistencia

Este caso documenta el análisis forense de red de un compromiso exitoso contra un servidor Apache Tomcat expuesto en el puerto 8080. A través de la revisión de capturas de tráfico de red (PCAP) y evidencias obtenidas durante la investigación, se reconstruyó la cadena completa de ataque utilizada por el adversario.

La investigación permitió identificar las distintas fases del incidente, desde el reconocimiento inicial del servicio hasta la obtención de acceso remoto persistente sobre el sistema comprometido

# **Objetivos**
- Reconstruir cronológicamente la actividad del atacante.
- Identificar los servicios y recursos descubiertos durante la fase de reconocimiento.
- Analizar la enumeración del panel administrativo de Apache Tomcat.
- Investigar el acceso obtenido mediante autenticación exitosa.
- Analizar el despliegue de un archivo malicioso
- Identificar el establecimiento de una reverse shell.
- Determinar los mecanismos de persistencia implementados por el atacante.
- Mapear las actividades observadas mediante MITRE ATT&CK® Framework

# **MITRE ATT&CK® Framework**

