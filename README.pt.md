Analista de Infraestrutura na [Pontotel](https://www.pontotel.com.br/). Radioamador licenciado, [PU3IAR](https://id.qsl.br/op/PU3IAR). Brasil.

[isaklab.com](https://isaklab.com) · [LinkedIn](https://www.linkedin.com/in/isakruas/) · [Email](mailto:isakruas@gmail.com) · [GitHub Sponsors](https://github.com/sponsors/isakruas)

Trabalho com infraestrutura em nuvem: Kubernetes e Helm, pipelines de CI/CD, infraestrutura como código com Terraform, administração de banco de dados e observabilidade com Sentry, Prometheus e Grafana.

Fora do trabalho, mantenho projetos open-source em criptografia, rádio digital e sistemas embarcados. Escrevo sobre eles em [isaklab.com](https://isaklab.com).

```text
Infraestrutura  Kubernetes · Helm · Terraform · GCP · CI/CD · Prometheus · Grafana · Sentry
Linguagens      Python · Rust · Go · Fortran · C · JavaScript / TypeScript
```

### Criptografia

Criptografia de curvas elípticas implementada em Python, JavaScript e Go, com uma aplicação construída sobre ela.

| Projeto | Descrição |
| :--- | :--- |
| [ecutils](https://ecutils.readthedocs.io/en/stable/) `Python` | Biblioteca de ECC: troca de chaves Diffie–Hellman e Massey–Omura, assinaturas ECDSA, codificação de mensagem-para-ponto de Koblitz. |
| [js-ecutils](https://www.npmjs.com/package/js-ecutils) `JS/TS` | Port em JavaScript/TypeScript do ecutils para o navegador e Node.js. |
| [go-ecutils](https://github.com/isakruas/go-ecutils) `Go` | Port em Go do ecutils. |
| [e2hat](https://e2hat.com) `JS` | Chat web com criptografia ponta a ponta usando curvas elípticas; a cifragem roda no cliente, então o servidor não consegue ler nem forjar mensagens. |

### Rádio e processamento de sinais

Modos digitais de radioamadorismo (`PU3IAR`), modems e ferramentas de SDR.

| Projeto | Descrição |
| :--- | :--- |
| [tern](https://github.com/isakruas/tern) `Fortran` | Modo digital de sinal fraco em HF com receptor ciente do canal: 16-FSK, suavização de canal Gauss–Markov (Kalman/RTS), codificação polar assistida por CRC e combinação entre quadros; validado contra um canal de Watterson ITU-R F.1487 e calibrado em comparação com o FT8 do WSJT-X. |
| [cdss](https://github.com/isakruas/cdss) `Fortran` | Modem digital CHIRP-DSSS-Polar com recepção por decisão suave e refinamento iterativo. |
| [radioplanbr](https://github.com/isakruas/radioplanbr) `HTML` | Planejamento de cobertura de RF com modelos Okumura-Hata, COST-231, ECC-33, Friis e Ericsson, incluindo análise de terreno e linha de visada. |
| [sdrconnect](https://github.com/isakruas/sdrconnect) `Python` | Biblioteca para conectividade com SDR e coleta de dados IQ brutos. |

### Embarcado e AVR

Toolchain para microcontroladores AVR de 8 bits: linguagem, compilador, emuladores e IDE.

| Projeto | Descrição |
| :--- | :--- |
| [ik8b](https://github.com/isakruas/ik8b) `Rust` | Compilador da linguagem `ik` para firmware Intel HEX para AVR, sem assembler, linker ou runtime de C externos. |
| [ikide](https://github.com/isakruas/ikide) `Rust` | IDE multiplataforma para o ik8b: validação de sintaxe, simulação de AVR e gravação via avrdude. |
| [ik8bvm](https://github.com/isakruas/ik8bvm) `Rust` · [avr-vm](https://github.com/isakruas/avr-vm) `C` | Emuladores de núcleo de CPU AVR de 8 bits. |
| [cyone-assembly](https://github.com/isakruas/cyone-assembly) `Go` | Linguagem assembly que tem como alvo o Cyone Kernel em microcontroladores de 8 bits. |
| [avr-modular-system](https://github.com/isakruas/avr-modular-system) `C` | Arquitetura modular de firmware para AVR. |

### IA e aprendizado de máquina

| Projeto | Descrição |
| :--- | :--- |
| [iklab](https://github.com/isakruas/iklab) `Python` | Agente de CLI que planeja primeiro, sobre o Granite 4.0-H-Tiny. |
| [llama-model-converter](https://github.com/isakruas/llama-model-converter) `Python` | Converte pesos de modelos Llama para o formato do Hugging Face. |

### Contribuições open-source

- [PeerDB #4365](https://github.com/PeerDB-io/peerdb/pull/4365) — corrigi uma falha de normalização no ClickHouse causada pelo tratamento sensível a maiúsculas da coluna `_peerdb_is_deleted`. *(merged)*
- [Mozilla bug 122752](https://bugzilla.mozilla.org/show_bug.cgi?id=122752) — implementação de autenticação SOCKS5 por usuário/senha (RFC 1929) no núcleo de rede do Firefox. *(em andamento)*

---

<sub>Base em Matemática (IFNMG – Januária, 2016–2023); atualmente cursando Tecnologia em Gestão da TI (PUCRS, 2025–2028). Se meu trabalho open-source foi útil para você, você pode apoiar sua manutenção pelo <a href="https://github.com/sponsors/isakruas">GitHub Sponsors</a>.</sub>
