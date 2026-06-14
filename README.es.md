[English](README.md) · [Português](README.pt.md) · **Español**

Analista de Infraestructura en [Pontotel](https://www.pontotel.com.br/). Radioaficionado licenciado, [PU3IAR](https://id.qsl.br/op/PU3IAR). Brasil.

[isaklab.com](https://isaklab.com) · [LinkedIn](https://www.linkedin.com/in/isakruas/) · [Email](mailto:isakruas@gmail.com) · [GitHub Sponsors](https://github.com/sponsors/isakruas)

Trabajo con infraestructura en la nube: Kubernetes y Helm, pipelines de CI/CD, infraestructura como código con Terraform, administración de bases de datos y observabilidad con Sentry, Prometheus y Grafana.

Fuera del trabajo, mantengo proyectos de código abierto en criptografía, radio digital y sistemas embebidos. Escribo sobre ellos en [isaklab.com](https://isaklab.com).

```text
Infraestructura  Kubernetes · Helm · Terraform · GCP · CI/CD · Prometheus · Grafana · Sentry
Lenguajes        Python · Rust · Go · Fortran · C · JavaScript / TypeScript
```

### Criptografía

Criptografía de curva elíptica implementada en Python, JavaScript y Go, con una aplicación construida sobre ella.

| Proyecto | Descripción |
| :--- | :--- |
| [ecutils](https://ecutils.readthedocs.io/en/stable/) `Python` | Biblioteca de ECC: intercambio de claves Diffie–Hellman y Massey–Omura, firmas ECDSA, codificación de mensaje-a-punto de Koblitz. |
| [js-ecutils](https://www.npmjs.com/package/js-ecutils) `JS/TS` | Port en JavaScript/TypeScript de ecutils para el navegador y Node.js. |
| [go-ecutils](https://github.com/isakruas/go-ecutils) `Go` | Port en Go de ecutils. |
| [e2hat](https://e2hat.com) `JS` | Chat web cifrado de extremo a extremo usando curva elíptica; el cifrado corre en el cliente, así que el servidor no puede leer ni falsificar mensajes. |

### Radio y procesamiento de señales

Modos digitales de radioafición (`PU3IAR`), módems y herramientas de SDR.

| Proyecto | Descripción |
| :--- | :--- |
| [tern](https://github.com/isakruas/tern) `Fortran` | Modo digital de señal débil en HF con receptor consciente del canal: 16-FSK, suavizado de canal Gauss–Markov (Kalman/RTS), codificación polar asistida por CRC y combinación entre tramas; validado contra un canal de Watterson ITU-R F.1487 y calibrado en comparación con el FT8 de WSJT-X. |
| [cdss](https://github.com/isakruas/cdss) `Fortran` | Módem digital CHIRP-DSSS-Polar con recepción por decisión suave y refinamiento iterativo. |
| [radioplanbr](https://github.com/isakruas/radioplanbr) `HTML` | Planificación de cobertura de RF con modelos Okumura-Hata, COST-231, ECC-33, Friis y Ericsson, incluyendo análisis de terreno y línea de vista. |
| [sdrconnect](https://github.com/isakruas/sdrconnect) `Python` | Biblioteca para conectividad con SDR y recolección de datos IQ en crudo. |

### Embebido y AVR

Toolchain para microcontroladores AVR de 8 bits: lenguaje, compilador, emuladores e IDE.

| Proyecto | Descripción |
| :--- | :--- |
| [ik8b](https://github.com/isakruas/ik8b) `Rust` | Compilador del lenguaje `ik` a firmware Intel HEX para AVR, sin ensamblador, enlazador ni runtime de C externos. |
| [ikide](https://github.com/isakruas/ikide) `Rust` | IDE multiplataforma para ik8b: validación de sintaxis, simulación de AVR y grabación vía avrdude. |
| [ik8bvm](https://github.com/isakruas/ik8bvm) `Rust` · [avr-vm](https://github.com/isakruas/avr-vm) `C` | Emuladores de núcleo de CPU AVR de 8 bits. |
| [cyone-assembly](https://github.com/isakruas/cyone-assembly) `Go` | Lenguaje ensamblador que apunta al Cyone Kernel en microcontroladores de 8 bits. |
| [avr-modular-system](https://github.com/isakruas/avr-modular-system) `C` | Arquitectura modular de firmware para AVR. |

### IA y aprendizaje automático

| Proyecto | Descripción |
| :--- | :--- |
| [iklab](https://github.com/isakruas/iklab) `Python` | Agente de CLI que planifica primero, sobre Granite 4.0-H-Tiny. |
| [llama-model-converter](https://github.com/isakruas/llama-model-converter) `Python` | Convierte pesos de modelos Llama al formato de Hugging Face. |

### Contribuciones de código abierto

- [PeerDB #4365](https://github.com/PeerDB-io/peerdb/pull/4365) — corregí una falla de normalización en ClickHouse causada por el manejo sensible a mayúsculas de la columna `_peerdb_is_deleted`. *(merged)*
- [Mozilla bug 122752](https://bugzilla.mozilla.org/show_bug.cgi?id=122752) — implementación de autenticación SOCKS5 por usuario/contraseña (RFC 1929) en el núcleo de red de Firefox. *(en progreso)*

---

<sub>Base en Matemáticas (IFNMG – Januária, 2016–2023); actualmente cursando Tecnología en Gestión de TI (PUCRS, 2025–2028). Si mi trabajo de código abierto te ha sido útil, puedes apoyar su mantenimiento mediante <a href="https://github.com/sponsors/isakruas">GitHub Sponsors</a>.</sub>
