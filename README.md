**English** · [Português](README.pt.md) · [Español](README.es.md)

Infrastructure Analyst at [Pontotel](https://www.pontotel.com.br/). Licensed radio amateur, [PU3IAR](https://id.qsl.br/op/PU3IAR). Brazil.

[isaklab.com](https://isaklab.com) · [LinkedIn](https://www.linkedin.com/in/isakruas/) · [Email](mailto:isakruas@gmail.com) · [GitHub Sponsors](https://github.com/sponsors/isakruas)

I work on cloud infrastructure: Kubernetes and Helm, CI/CD pipelines, infrastructure as code with Terraform, database administration, and observability with Sentry, Prometheus, and Grafana.

Outside of work I maintain open-source projects in cryptography, digital radio, and embedded systems. I write about them at [isaklab.com](https://isaklab.com).

```text
Infrastructure  Kubernetes · Helm · Terraform · GCP · CI/CD · Prometheus · Grafana · Sentry
Languages       Python · Rust · Go · Fortran · C · JavaScript / TypeScript
```

### Cryptography

Elliptic-curve cryptography implemented across Python, JavaScript, and Go, with an application built on it.

| Project | Description |
| :--- | :--- |
| [ecutils](https://ecutils.readthedocs.io/en/stable/) `Python` | ECC library: Diffie–Hellman and Massey–Omura key exchange, ECDSA signatures, Koblitz message-to-point encoding. |
| [js-ecutils](https://www.npmjs.com/package/js-ecutils) `JS/TS` | JavaScript/TypeScript port of ecutils for the browser and Node.js. |
| [go-ecutils](https://github.com/isakruas/go-ecutils) `Go` | Go port of ecutils. |
| [e2hat](https://e2hat.com) `JS` | End-to-end encrypted web chat using elliptic-curve cryptography; encryption runs client-side, so the server cannot read or forge messages. |

### Radio and signal processing

Amateur-radio (`PU3IAR`) digital modes, modems, and SDR tooling.

| Project | Description |
| :--- | :--- |
| [tern](https://github.com/isakruas/tern) `Fortran` | HF weak-signal digital mode with a channel-aware receiver: 16-FSK, Gauss–Markov (Kalman/RTS) channel smoothing, CRC-aided polar coding, and cross-frame combining; validated against an ITU-R F.1487 Watterson channel and cross-calibrated with WSJT-X FT8. |
| [cdss](https://github.com/isakruas/cdss) `Fortran` | CHIRP-DSSS-Polar digital modem with soft-decision reception and iterative refinement. |
| [radioplanbr](https://github.com/isakruas/radioplanbr) `HTML` | RF coverage planning with Okumura-Hata, COST-231, ECC-33, Friis, and Ericsson models, including terrain and line-of-sight analysis. |
| [sdrconnect](https://github.com/isakruas/sdrconnect) `Python` | Library for SDR connectivity and raw IQ data collection. |

### Embedded and AVR

Toolchain for 8-bit AVR microcontrollers: language, compiler, emulators, and IDE.

| Project | Description |
| :--- | :--- |
| [ik8b](https://github.com/isakruas/ik8b) `Rust` | Compiler from the `ik` language to Intel HEX firmware for AVR, with no external assembler, linker, or C runtime. |
| [ikide](https://github.com/isakruas/ikide) `Rust` | Cross-platform IDE for ik8b: syntax validation, AVR simulation, and avrdude flashing. |
| [ik8bvm](https://github.com/isakruas/ik8bvm) `Rust` · [avr-vm](https://github.com/isakruas/avr-vm) `C` | 8-bit AVR CPU core emulators. |
| [cyone-assembly](https://github.com/isakruas/cyone-assembly) `Go` | Assembly language targeting the Cyone Kernel on 8-bit microcontrollers. |
| [avr-modular-system](https://github.com/isakruas/avr-modular-system) `C` | Modular firmware architecture for AVR. |

### AI and machine learning

| Project | Description |
| :--- | :--- |
| [iklab](https://github.com/isakruas/iklab) `Python` | Planning-first CLI agent powered by Granite 4.0-H-Tiny. |
| [llama-model-converter](https://github.com/isakruas/llama-model-converter) `Python` | Converts Llama model weights to the Hugging Face format. |

### Open-source contributions

- [PeerDB #4365](https://github.com/PeerDB-io/peerdb/pull/4365) — fixed a ClickHouse normalization failure caused by case-sensitive handling of the `_peerdb_is_deleted` column. *(merged)*
- [Mozilla bug 122752](https://bugzilla.mozilla.org/show_bug.cgi?id=122752) — implementing SOCKS5 username/password authentication (RFC 1929) in Firefox's networking core. *(in progress)*

---

<sub>Background in Mathematics (IFNMG – Januária, 2016–2023); currently studying IT Management (PUCRS, 2025–2028). If my open-source work has been useful to you, you can support its maintenance through <a href="https://github.com/sponsors/isakruas">GitHub Sponsors</a>.</sub>
