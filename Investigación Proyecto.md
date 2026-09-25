
# Investigación: ¿esto ya existe? ¿quién lo dice?
  

> Instrucción: sustituye lo que está entre corchetes y borra las líneas que empiezan con

> "Instrucción:". Todos los enlaces deben abrir. Un enlace roto o inventado anula el

> criterio correspondiente.

  

**Autor:** [Jose Pedro Itzcoatl Macuil ]

**Fecha:** [20/09/26]

**Ideas analizadas:** ver [[Inicio de proyecto]] o [[Ideas Proyecto]]

  

---

  

## Parte 1. Un ejemplo que ya existe, por cada idea

  

> Instrucción: busca algo parecido que alguien ya haya construido: un producto, un

> proyecto de otra universidad, un repositorio, un tutorial. Encontrar que ya existe no

> arruina tu idea; te dice desde dónde empezar.

  

### Idea 1: [El Guante de Regulación Térmica Extrema]

  

- **Qué encontré:** [Un artículo de investigación científica indexado que evalúa la adición de Materiales de Cambio de Fase (PCM) en guantes industriales.]

- **Enlace:** [(s. f.). _Home_ [Página de inicio]. https://www.researchgate.net/]

- **Qué hace:** [Analiza cómo reacciona un guante al inyectarle microcápsulas de sales hidratadas y geles de parafina en su capa intermedia. Demuestra en laboratorios que el material absorbe el calor extremo cambiando de estado sólido a líquido, manteniendo el interior a una temperatura corporal segura por mucho más tiempo.]

- **Por qué no resuelve mi caso:** [Aunque valida la física del proyecto, el estudio se enfoca en la teoría térmica y química en condiciones de laboratorio. No propone un diseño textil comercial, no resuelve la pérdida de flexibilidad en la mano al usar geles densos ni dice a detalle cómo integrar materiales de última generación como el aerogel de la NASA para adelgazar el guante.]

---

  

### Idea 2: [La App de Hogar Inteligente Multimarca]

  

- **Qué encontré:** [El ecosistema de desarrollo global y libre para la unificación del hogar inteligente basado en el nuevo protocolo universal.]

- **Enlace:** [(2026, 24 de septiembre). _Connectedhomeip_ [Repositorio de GitHub]. GitHub. https://github.com/project-chip/connectedhomeip ]

- **Qué hace:** [Permite a desarrolladores conectar y comandar de forma directa dispositivos locales de iluminación, climatización y seguridad compatibles con el estándar Matter, sin importar la marca fabricante.]

- **Por qué no resuelve mi caso:** [Carece por completo de una interfaz de usuario visual (frontend), de una aplicación móvil amigable para una persona normal o de sistemas logre comprender la automatización de complejos estilos diseñados con un enfoque en privacidad local o accesibilidad.]

  ---

### Idea 3: [La Botella con Tapa Automatizada / Inteligente]

  

- **Qué encontré:** [Una guía completa de desarrollo de Internet de las Cosas (IoT) y repositorio para crear una botella de agua inteligente interactiva usando chips ESP32. ]

- **Enlace:** [(2026, 18 de enero). _Smart Hydration Made Simple: How to Build Your Own BLE Water Bottle Tracker_. DEV Community. https://dev.to/wellallytech/smart-hydration-made-simple-how-to-build-your-own-ble-water-bottle-tracker-1oen ]

- **Qué hace:** [ Explica cómo integrar un microcontrolador ESP32 con Bluetooth de Baja Energía (BLE) dentro de una botella. Utiliza sensores de nivel para medir el volumen de agua consumido en tiempo real y transmite esos datos automáticamente a una aplicación móvil desarrollada en React Native sin necesidad de registros manuales.]

- **Por qué no resuelve mi caso:** [Aunque aporta toda la arquitectura para crear la aplicación móvil y la comunicación Bluetooth con la botella, el proyecto está diseñado exclusivamente para **monitorear de forma pasiva** los mililitros que el usuario bebe. No incluye actuadores mecánicos (como servomotores), automatizaciones de apertura autónoma de la tapa, ni conectividad para controlarse mediante comandos de voz en un entorno de hogar inteligente.]

  

---

  

## Parte 2. Fuentes de la idea que elegí

  

> Instrucción: de dos a tres fuentes, solo de la idea elegida. Todavía no se pide formato

> APA; eso llega más adelante en el curso. Lo que se pide es que distingas quién publicó

> la información y por qué le crees.

  

### Fuente 1

  

| Campo                | Contenido                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |     |
| -------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --- |
| Autor u organización | Quartz Components / Plataforma Hackster.io                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |     |
| Título               | Smart Hydration Tracker Bottle Using ESP32 & VL53L0X Sensor                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |     |
| Año                  | 2026                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |     |
| Enlace               | https://www.hackster.io/quartz-components/smart-hydration-tracker-bottle-using-esp32-vl53l0x-sensor-37867b                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |     |
| Tipo                 | Documentación técnica / Blog                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |     |
| Por qué le creo      | Hackster.io es una de las comunidades globales de ingeniería de hardware y robótica más prestigiosas del mundo. El contenido está respaldado por código de programación real para microcontroladores y diagramas de circuitos electrónicos que cualquier desarrollador puede verificar y replicar. Me la recomendó un amigo que estudia ingeniería en sistemas.                                                                                                                                                                                                                                                                     |     |
| Qué dato me dio      | Me dio la arquitectura exacta de cómo meter hardware dentro de una tapa de botella pequeña usando el microcontrolador **[ESP32-C3 Super Mini](https://www.google.com/search?ibp=oshop&prds=pvt:hg,pvo:29,mid:576462548989429084,imageDocid:10421347492086157820,gpcid:14035323063556170526,headlineOfferDocid:9587323306725213820,catalogid:18353405609868270911,productDocid:11568109850234383072,rds:PC_14035323063556170526%7CPROD_PC_14035323063556170526&q=product&sa=X&ved=2ahUKEwjZyczR9v6WAxVFMNAFHR7EBqsQxa4PegYIAAgPEAk)** y cómo medir fluidos de forma inalámbrica a través de sensores láser de tiempo de vuelo (ToF). |     |

  ---

### Fuente 2

  
| Campo                | Contenido                                                                                                                                                                                                                                                        |
| -------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Autor u organización | WellAlly Tech                                                                                                                                                                                                                                                    |
| Título               | Smart Water Bottle: ESP32 + React Native BLE (Track 8)                                                                                                                                                                                                           |
| Año                  | 2025                                                                                                                                                                                                                                                             |
| Enlace               | [WellAlly - Smart Water Bottle Guide](https://www.wellally.tech/blog/build-react-native-ble-app-esp32-smart-water-bottle)                                                                                                                                        |
| Tipo                 | Blog / Documentación técnica                                                                                                                                                                                                                                     |
| Por qué le creo      | Es una plataforma de desarrollo especializada en Internet de las Cosas (IoT) aplicada a la salud. Publican guías con métricas reales de confiabilidad técnica (mencionan pruebas en más de 200 prototipos físicos) orientadas a ingenieros de software.          |
| Qué dato me dio      | Me dio el método de comunicación: demuestra que usar **Bluetooth Low Energy (BLE)** junto con el framework de aplicaciones móviles **React Native** es la forma más rápida y eficiente (con 47ms de latencia) para conectar un teléfono a un envase inteligente. |

  ---

### Fuente 3 (opcional)

| Campo                | Contenido                                                                                                                                                                                                                                                                           |
| -------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Autor u organización | Connectivity Standards Alliance (CSA)                                                                                                                                                                                                                                               |
| Título               | Matter Standard Specifications & Development Overview                                                                                                                                                                                                                               |
| Año                  | 2026                                                                                                                                                                                                                                                                                |
| Enlace               | [Build With Matter - Alliance Official]([https://csa-iot.org/all-solutions/matter/).                                                                                                                                                                                                |
| Tipo                 | Sitio institucional / Documentación técnica                                                                                                                                                                                                                                         |
| Por qué le creo      | Es el consorcio oficial internacional integrado por las empresas tecnológicas más grandes del planeta (incluyendo a Apple, Google y Amazon) encargado de dictar las reglas del hogar inteligente. Es la máxima autoridad en conectividad.                                           |
| Qué dato me dio      | Me dio el marco de compatibilidad. Explica cómo el protocolo universal **Matter** permite que cualquier hardware nuevo se conecte directamente a los asistentes de voz sin necesidad de programar integraciones individuales por marca, usando Wi-Fi o Thread como puentes locales. |




---

  

## Parte 3. Qué haría distinto

  

[Tomando en cuenta que ya existe la idea de la tapa inteligente o botellas o recipientes que se abren solas, mi enfoque podría dirigirse a igualmente la automatización de esa abrir y cerra de las tapas en otro ámbito que se necesite lo automático, cajas de zapatos, componentes electrónicos, electrodomésticos y todo tipo de cosas que necesiten comercializar o empezar a producir en masa esa opción de controlar la manera en que usas tus dispositivos o objetos diariamente, algo mas general que ya todas las marcas ya usen en todos sus productos, aunque conllevaría mucha producción en masa y limitaría el alcance al que puede llegar. Algo tan general y ya común como las cámaras en los teléfonos celulares.]

  

## Parte 4. Qué me falta averiguar

  

- [x] [Como conocer mis limites y el limite de lo que puedo hacer.]

- [ ] [No encontré en especifico la manera "fácil" de hacer o llevar acabo el proceso de fabricación del guante.] 

- [ ] [El sensor que detecta movimiento al tocar o al pasar un objeto frente a el.]

  

---

  

## Declaración de uso de IA

  

- **Herramienta utilizada:** [Google Gemini y ChatGPT]

- **Qué le pedí:** [A Gemini le pedí que verificara la seguridad y la veracidad de lo que dice la pagina que encontré, y a Chatgpt le pedí que me ayudara a encontrar los términos y ver que significan las palabras difíciles o que no sabia que significaban en la fuente de donde saqué la información. ]

- **Qué modifiqué o rechacé de su respuesta, y por qué:** [Rechacé la respuesta de el resumen de lo que dice la pagina de donde tenía la información. Porque solo pegar el copiar y pegar el resumen se salta de toda la otra información que no me dio y que me podría ayudar en otro momento.]