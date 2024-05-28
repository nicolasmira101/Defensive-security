## Principios de Incidentes Cibernéticos

### Gestión de incidentes cibernéticos
- Proceso crítico desde la detección temprana hasta la resolución y recuperación.
- Desarrollado en varias fases clave con importancia y metodología específicas.

### Detección
- Primera línea de defensa en la gestión de incidentes.
- Identificación rápida para mitigar daños potenciales.
- Monitoreo constante de sistemas para identificar comportamientos anómalos o brechas de seguridad.
- Importancia de sistemas avanzados de detección para adaptarse y reconocer nuevas amenazas.

### Respuesta
- Crucial después de detectar el incidente.
- Contener el ataque para evitar daños mayores, erradicar la causa y recuperar los sistemas afectados.
- Necesidad de un plan de acción para la gestión de respuesta, estableciendo niveles de escalamiento y comunicación, y definiendo procedimientos para todas las fases.

### Recuperación
- Varía en duración dependiendo de la severidad del ataque y la preparación de la organización.
- Mayor parte de las empresas se recuperan en menos de 24 horas; algunas pueden tardar más.
- Importancia de restaurar sistemas y aprender del incidente para fortalecer defensas y prevenir futuras brechas.

### Análisis forense digital
- Comprender cómo ocurrió el incidente e identificar sus causas.
- Puede implicar contratación de consultores externos o capacitación del personal de TI en procedimientos de investigación digital.
    
### Protocolo de ciberseguridad
- Implementación crucial para mejorar la respuesta y recuperación ante incidentes.
- Construido a partir de publicaciones académicas, normas técnicas, y guías prácticas.
- Diseñado para ser económico, efectivo y accesible, especialmente para pequeñas y medianas empresas.

### Gestión eficaz de incidentes
- Requiere detección y respuesta rápidas, recuperación bien planificada y análisis post-incidente exhaustivo.
- Implementación de un protocolo de ciberseguridad y capacitación en análisis forense digital fundamentales para mejorar la resiliencia organizacional.

###  TTP (Tácticas, Técnicas y Procedimientos)
- Son los métodos que usan los ciberdelincuentes para atacar.
- **Tácticas**: Son los objetivos generales que buscan los ciberdelincuentes, como el reconocimiento, la exfiltración de datos o la interrupción del servicio.
- **Técnicas**: Son los métodos específicos que utilizan los ciberdelincuentes para lograr sus tácticas, como el phishing, el malware o el ataque de fuerza bruta.
- **Procedimientos**: Son los pasos concretos que siguen los ciberdelincuentes para llevar a cabo una técnica, como la creación de un correo electrónico de phishing o la explotación de una vulnerabilidad.

### Caso de estudio: Ataque WannaCry
- Un ataque de ransomware que afectó a más de 200.000 sistemas en 150 países en mayo de 2017.
- El ransomware cifraba los archivos de las víctimas y exigía un pago en Bitcoin para descifrarlos.
- El ataque causó un gran impacto económico en las empresas y organizaciones afectadas.
- El ransomware se propagó a través de una vulnerabilidad conocida en el sistema operativo Windows, llamada EternalBlue.
- Esta vulnerabilidad fue robada a la Agencia de Seguridad Nacional (NSA) de Estados Unidos y filtrada al público.
- El ransomware utilizaba el protocolo SMB para propagarse a través de las redes locales.
- Se cree que el grupo cibernético WannaCry, vinculado a Corea del Norte, fue responsable del ataque.
- Se estima que el costo total del ataque fue de miles de millones de dólares.
- El ataque también generó un gran temor y preocupación por la seguridad cibernética.

### Caso de estudio: Ataque Colonial Pipeline
- **Víctima**: Colonial Pipeline, la empresa privada que opera el oleoducto más grande de Estados Unidos, transportando el 45% del combustible de la costa este del país.
- **Atacantes**: DarkSide, un grupo cibercriminal con sede en Rusia, conocido por realizar ataques de ransomware a grandes empresas.
- **Infiltración**: Los atacantes ingresaron a la red de Colonial Pipeline a través de una contraseña robada de un empleado, utilizando la técnica de acceso remoto (RDP).
- **Movimiento lateral**: Una vez dentro, se movieron sigilosamente por la red, buscando sistemas críticos.
- **Escalada de privilegios**: Obtuvieron privilegios de administrador de dominio, lo que les dio control total sobre los sistemas de TI de Colonial Pipeline.
- **Instalación de ransomware**: Implementaron el ransomware Maze para cifrar los datos de la empresa, incluyendo sistemas de control operacional (OT) del oleoducto.
- **Demanda de rescate**: Exigieron un pago de 4,4 millones de dólares en Bitcoin a cambio de la clave de descifrado, amenazando con publicar los datos robados y mantener el oleoducto inoperativo.
- **Cierre del oleoducto**: Colonial Pipeline se vio obligada a cerrar su sistema de oleoductos principal, lo que provocó: escasez de combustible, aumento de precios y declaración de estado de emergencia. Adicionalmente, daño reputacional y perjuicios económicos.

### Procedimiento de Gestión de Incidentes de Seguridad Digital en Colombia

<p align="center">
  <img src="https://i.imgur.com/wEN4hZD.png"/>
</p>

## Análisis Forense y Recopilación de Evidencias
- El Análisis Forense Digital es una disciplina crucial para investigar y documentar incidentes cibernéticos.
- Se centra en la identificación, recolección, examen y análisis de datos digitales, preservando su integridad y cadena de custodia.
- La evidencia digital se diferencia de la física por ser secuencias de bits que requieren herramientas específicas para su interpretación.
- Las herramientas permiten obtener copias exactas de la información, incluyendo llamadas, correos electrónicos, documentos e información eliminada.

### Recopilación evidencia digital
- Es un proceso complejo que requiere herramientas forenses especializadas para garantizar su admisibilidad en un proceso judicial.
- Estas herramientas deben cumplir con criterios de admisibilidad, autenticidad, integridad, fiabilidad, claridad y credibilidad.
- Es fundamental preservar la integridad del medio original, etiquetar, controlar y transmitir adecuadamente las copias de datos.

### Etapas del análisis forense
- **Incautación**: asegurar y preservar la escena del crimen digital.
- **Adquisición forense**: obtener una copia exacta del dispositivo en cuestión.
- **Análisis**: examinar los datos recopilados para identificar evidencia relevante.
- **Producción de informes**: documentar los hallazgos de manera clara y concisa.

### Importancia del análisis forense digital
- Asiste en investigaciones criminales.
- Fortalece la seguridad de la información en entidades.
- Previene futuros incidentes.
- Complementa políticas de seguridad, educación digital y sistemas de prevención y monitoreo.

### Retos del análisis forense digital
- Adaptarse a la evolución tecnológica y a las nuevas formas de ciberdelincuencia.
- Requiere desarrollo y actualización constantes de herramientas y técnicas forenses.
- Colaboración entre especialistas, entidades judiciales y organismos de seguridad para mejorar las prácticas y garantizar la seguridad digital.
