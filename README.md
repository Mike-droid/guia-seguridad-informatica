# Guía para Aprender Seguridad Informática

## Introducción a la seguridad informática

### ¿Qué es la seguridad informática?

> Todo lo que implica proteger acceso o uso no autorizado de datos (electróincos o digitales)

Prerequisitos:

- Redes computacionales
  - Protocolos de red, modelos OSI, TCP/IP
  - Arquitectura de redes
- Desarrollo de software/lenguajes de programación
- Sistemas computacionales
  - Sistemas operativos
  - Arquitectura de sistemas
- Normativa y legislación: ISO 27001
- Inglés (esencial)
- Experimentar y no perder la curiosidad

### Retos: define tu rol en seguridad informática

[Guía de retos](https://drive.google.com/file/d/1gnn4huictpqOk5FwE08pm4yJVMu0O18P/view?usp=sharing)

### Roles y oportunidades laborales de la ciberseguridad

- Seguridad de la información: Normativas (27001) y protección de datos
- Código seguro: Autenticación, Buenas práctias, OWASP, arquitectura de seguridad en aplicaciones
- Seguridad aplicativa: Web, Mobile & Network
- Criptogafía: Esteganografía (ocultar datos), Criptografía (cifrar datos)
- Redes: Hardware, Software, Seguridad en Redes
- Ingeniería Social: Phishing, Vishing (voz)
- Ciberinteligencia: OSINT
- Ingeniería Forense: Encontrar las causas que llevaron al fallo
- Ética: Hacktivismo, Ethical Hacking
- Scripting: Bash, Payloading, Exploits
- Malware: Análisis de malware, Protección de Malware, IA + Malware

### Glosario de seguridad informática

**Ciberseguridad**: todo lo que implica proteger el acceso o uso no autorizado de datos electrónicos.

**Seguridad de la información**: medidas para resguardar y proteger la información buscando mantener la confidencialidad, la disponibilidad e integridad de datos.

**Código seguro**: es una área de la ciberseguridad que se dedica a asegurar que el desarrollo de software cumpla con requisitos funcionales de ciberseguridad y normativas según el caso de uso.

**Seguridad aplicativa**: en este segmento encuentras el pentesting, que se dedica a realizar pruebas de penetración y análisis de vulnerabilidades. Es decir, se simula el “hackeo” o ataque informático de manera ética/legal sobre un aplicativo web, móvil o la red para encontrar vulnerabilidades, reportarlas a los desarrolladores o administradores del sistema y protegerse de ataques reales.

**Criptografía**: es un área que estudia el cifrado de información, busca que un mensaje solo pueda ser leído por personas autorizadas.

**Esteganografía**: es una técnica que consiste en insertar un mensaje secreto dentro de una información aparentemente inocua.

**Redes computacionales**: es el área de la informática que estudia la comunicación o interconexión entre dos computadoras mediante una tecnología.

**Ingeniería social**: consiste en técnicas de manipulación que tienen el objetivo de obtener información de interés para el atacante, ciertos accesos o permisos en un sistema. Dicha manipulación se realiza sobre usuarios legítimos, sin que ellos se den cuenta. Por ejemplo, el empleado de un banco.

**Ciberinteligencia**: adquisición y análisis de información para identificar, rastrear y predecir las capacidades, intenciones y actividades cibernéticas que ayuden a identificar amenazas.

**Ingeniería forense**: la ingeniería forense consiste en identificar la causa en el fallo de un sistema ya sea para mejorarlo o encontrar a los responsables.

**Scripting**: es un área de especialización que automatiza tareas y herramientas de hacking como exploits, para facilitar las auditorías de ciberseguridad o la búsqueda de vulnerabilidades.

**Malware**: esta es simple, significa Software Malicioso. Es decir, es una pieza de software que tiene la intención de obtener, alterar o afectar alguna pieza de información digital. Hay de varios tipos:

- **Spyware**: es una clase de malware espía que puede capturar todo lo que sucede en el equipo infectado e incluso controlarlo. Normalmente detrás de esto hay una persona con otro software que controla el spyware, llamado “Comando y Control”.
- **Virus**: cualquier código que puede infectar tu computadora.
- **Troyanos**: virus que aparenta hacer otra cosa mientras en realidad tiene intenciones maliciosas.
- **Ransomware**: es un software que secuestra tu computador, tomando control de este hasta que pagues una suma de rescate.
- **Rootkits**: es un malware que tiene como objetivo ganar privilegios administrativos tratando de llegar al kernel.
- **Backdoors**: Su nombre en inglés significa “puerta trasera”, ya que permite el acceso de terceros al sistema informático, evadiendo los usuales controles y protocolos de comunicación.
- **Drive-by downloads**: Piezas maliciosas de software que son descargados automáticamente por ciertas páginas Web sin pedir autorización al usuario ni permitirle detenerlo a tiempo, y le abren la puerta a otras formas de invasión virtual.
- **Adware**: Una aplicación en la frontera del malware, porque no siempre es dañino para el ordenador. Su única misión es la de meterse en tu ordenador y empezar a mostrarte publicidad, ya sea mientras estás navegando por internet, a forma de popup en momentos aleatorios o durante la ejecución de un programa.

## Ramas de la ciberseguridad

### InfoSec o seguridad de la información

> Medidas para resguardar y proteger la información buscando mantener la **confidencialidad**, la **disponibilidad** e **integridad de datos**.

[Ataques hacker casi imposibles de detener: 0-day exploits](https://www.youtube.com/watch?v=gjV6wbEipW4)

Consiste en un fallo en la tecnología, como es nuevo no existe un parche de seguridad.

### Ciberinteligencia

> Adquisición y análisis de información para identificar, rastrear y predecir las capacidades, intenciones y actividades cibernéticas que ayudan a identificar amenazas.

[Informe: Hacking Team - Malware para la vigilance en américa latina](https://www.derechosdigitales.org/wp-content/uploads/malware-para-la-vigilancia.pdf)

Remote control system:

- Modo captura: Toma toda la información de tu teléfono / PC

### Malware

**Busca no dañar a otros**. Cruzar la línea de lo ilegal es muy fácil. 💻 El malware es un software malicioso, donde podemos tener diversas áreas tales como:

- 🔒 El análisis de malware.
- 🔒 Ingeniería forense.
- 🔒 ingeniería reversa.

### Criptografía y esteganografía

Criptografía = cifrar datos 🔐
Esteganografía = ocultar datos 🐱‍👤

Combinar ambas técnicas es mucho mejor.

Película recomendada: Código enigma. Disponible en Netflix 😎.

- 🚚 Capacidad: cantidad de bits incrustados.
- 💪 Robustez: ¿cuántos ataques puede soportar un algoritmo? ¿qué tan bueno es el algoritmo?
- 🐱‍👤 Transparencia o imperceptibilidad: ¿qué tanto se verá afectado lo que ya tenía?
- 🔒 Seguridad: ¿qué tan seguro son los algoritmos?

### Código seguro

Ciclo de vida del desarrollo de software

1. Requerimientos
2. Diseño
3. Desarrollo
4. Pruebas
5. Despliegue
6. operaciones

¡La ciberseguridad entra en todas! Y *los programadores deben conocer buenas prácticas de ciberseguridad*.

Es importante tener feedback de los usuarios para ver si existe algún detalle que no habíamos tomado en cuenta.

**OWASP**: biblia de la ciberseguridad.

[OWASP - Open Web Application Security Project](https://owasp.org/)

### Pentesting

- Inyección de código 💉: Insertar código malicioso dentro de código normal.
- Backdoor 🚪: Dejar un punto de acceso para los atacantes pero sin que se note que existe este punto de acceso.
- Vector de ataque 💣: Medio por el cual se realiza un ciberataque. Algunos ejemplos:
  - Inyección de código
  - Pérdida de autenticación
  - Pérdida de controles de acceso
  - Uso de componentes con vulnerabilidades conocidas
  - Registros y monitoreos insuficientes
  - Deserialización insegura

Pentesting:
> Las pruebas de seguridad o pentest consisten en realizar ataques informáticas a aplicaciones con el objetivo de encontrar vulnerabilidades existentes.

[5 ejemplos de vectores de ataque](https://www.optical.pe/blog/vectores-de-ataque-ciberseguridad/#5_Vectores_de_ataque)

🐱‍👤 Pentesting o pruebas de seguridad son pruebas de penetración para evaluar la seguridad de los sistemas. Consisten en realizar ataques informáticos a aplicaciones con el objetivo de encontrar vulnerabilidades existentes.

-- Para qué --

- Reducir el gasto de seguridad de TI y mejorar el ROSI (Retorno de Inversión en Seguridad).

- Enfocarse en vulnerabilidades de alta severidad y aumentar la consciencia de seguridad.

- Adoptar las mejores prácticas.

⚠ Qué se va a evaluar.

- Seguridad en la Red (interna, externa, inalámbrica)

- Aplicaciones.- ver los diferentes módulos de una ap. Ej. Si usan xml o Json, evaluar que envían la info de forma cifrada.

- Seguridad Física .- Si tienen, por ejemplo Data Center. Preguntarse cómo está el acceso a dicho Data Center.

- Ingeniería Social.- la manera de engañar a las personas para sacarles información Tomar en cuenta aspecto como ¿Se destruye bien la información que desechamos? Cualquier persona revisando la basura podría tomar datos importantes para la empresa.

☢ Tipos de Pruebas

- Caja Negra.- Simula un ataque como en el mundo real.

- Caja Blanca.- Aquí el persona de la empresa nos dará acceso a toda la información, la infraestructura, qué implementaciones de seguridad tiene, qué políticas utiliza. Se dividen en pruebas anunciadas y pruebas no anunciadas.

- Grey-Box.- Combinación de las anteriores.

🛑 Fases del Pentesting

- Pre Ataque.- se realiza una planeación, se definen los objetivos. se prepara el ataque con un papel llamado Reglas de Compromiso.

- Ataque.- Recolección de información a través de fuentes pasivas o activos. Escaneo de vulnerabilidad.

- Post Ataque.- Reporte técnico para el equipo de TI y no técnico para el equipo de toma de decisiones.

### Seguridad forense

> La ingeniería forense consiste en identificar la causa en el fallo de un sistema ya sea para mejorarlo o encontrar a los responsables.

### Seguridad en redes

Lecturas recomendadas:

- [Computer Networks](https://www.amazon.com/dp/0132126958)
- [Zero Trust Networks](https://www.amazon.com/Zero-Trust-Networks-Building-Untrusted/dp/1491962194)

Hoy en día se usa una estructura de 0 confianza.

### Certificaciones internacionales de ciberseguridad

Empleos para acercarte a roles de ciberseguridad

- Desarrollo Web
- Ingeniería de redes
- Analista de sistemas
- Bases de datos
- Soporte técnico
- Ingeniería de software
- Administración de sistemas, bases de datos, redes, seguridad
- Testing / Ingeniería de pruebas
- Campo normativo / legal

Certificaciones: es un requisito

| Comptia   | Offense Security | EC-Council | ISC^2       | Otras |
| --------- | ---------------- | ---------- | ----------- | ----- |
| Network+  | OSCP             | CND        |             | ITIL  |
| Security+ |                  | CEH        |             | ISACA |
|           |                  | ESCA       | ISSC2 CCSP  | SANS  |
|           |                  | LPT        | ISSC2 CISSP |       |

Dificultad aumenta de arriba hacía abajo.

La de más prestigio es ISC^2 pero también la más difícil.

## Define tu ruta de aprendizaje en seguridad informática

### Cómo hacer una carrera de seguridad informática

Roles en la industria, empleos más demandados en 2020:

- Ingeniero en ciberseguridad -> tener un nivel técnico y de alto nivel para saber qué podemos sugerir para una organización para que esta sea más segura.
- Analista de ciberseguridad -> A nivel de red; Entender el tráfico de red. Ser capaz de detectar posibles ataques y en caso de suceder encontrar el origen de dicho ataque.
- Arquitecto de redes/ciberseguridad -> Es una persona que a un alto nivel es capaz de proponer la manera de estructura una red para evitar exponer los datos de una empresa
- Consultor de ciberseguridad -> Personas que está actualizada en tendencias de tecnología, cuáles son los ataques vigentes hoy en día. Tiene ese nivel humano para interactuar con personas de una organización y sugerir el camino que deberían tomar para mejorar el nivel en el que están.
- Gerente de ciberseguridad -> Persona encargada de todos los temas y todas las estrategias de ciberseguridad.

Para principiantes:

- Pentester Jr
- Analista Jr
- Técnico de redes
- Respuesta a incidentes
- Consultor Jr

Intermedios:

- Ingeniero de preventa
- Ethical hacker => Bug bounties
- Ingeniero Forense / Análisis forense
- Consultor en Seguridad de la información

Avanzado:

- Análisis de malware / Malware reversing
- Ingeniería reversa
- Líder de Red Team (atacan) / Blue Team (defienden)
- Experto en nube
- CISO, CSO, DPO
- Especialista en incidencias

### Continúa aprendiendo seguridad informática

Participa en [Capture the Flag](https://github.com/apsdehal/awesome-ctf)

Haz los [Bug Bounties](https://drive.google.com/file/d/1RfMyIo6kzjcWh-tX3ThoM1x28mCjeR1A/view) ¡te pagan mucho dinero por las más difíciles!

¡Toma cursos! Tanto en Platzi como los especializados

Usa laboratorios, son entornos controlados en tu computadora
