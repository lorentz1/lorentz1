<div align="center">

<img src="assets/banner-original.svg" alt="Lorentz — Defesa Cibernética · Eletrônica · IoT · Robótica" width="100%" />

<br>

![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![C#](https://img.shields.io/badge/C%23-512BD4?style=for-the-badge&logo=csharp&logoColor=white)
![Shell](https://img.shields.io/badge/Shell-121011?style=for-the-badge&logo=gnubash&logoColor=white)
![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=for-the-badge&logo=espressif&logoColor=white)
![Arduino](https://img.shields.io/badge/Arduino-00878F?style=for-the-badge&logo=arduino&logoColor=white)

![AI Orchestration](https://img.shields.io/badge/AI_Agent_Orchestration-D97757?style=for-the-badge&logo=anthropic&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-000000?style=for-the-badge&logo=anthropic&logoColor=white)
![Cybersecurity](https://img.shields.io/badge/Cyber_Defense-0A0A0A?style=for-the-badge&logo=hackthebox&logoColor=green)
![IoT](https://img.shields.io/badge/IoT-1BA94C?style=for-the-badge&logo=internetofthings&logoColor=white)
![RF](https://img.shields.io/badge/Sub--GHz_RF-663399?style=for-the-badge&logoColor=white)

</div>

---

## 🧭 Quem sou

Minha área é **Defesa Cibernética**, e meu diferencial está na fronteira entre **segurança, eletrônica e sistemas embarcados**.

Trabalho **orquestrando agentes de IA** para projetar e entregar soluções com muito mais velocidade — mas sempre com **desenvolvimento assistido, revisão crítica e segurança desde o design**. A IA acelera a execução; o **domínio de hardware e a engenharia** garantem que a solução esteja **certa**, não só pronta. Pra mim, saber *dirigir* bem a IA — definir arquitetura, validar, revisar e integrar — vale mais do que digitar cada linha.

- 🤖 **Orquestração de IA & MCP** — projeto, conecto e dirijo agentes (Model Context Protocol) para acelerar engenharia, com validação e revisão humana em cada etapa.
- 🔐 **Defesa Cibernética** — superfícies de ataque além do software: RF, controles de acesso, IoT, replay de código fixo.
- ⚡ **Eletrônica & Potência** — circuitos, transistores, **PWM**, **IGBTs**, drivers e acionamento. Leio **datasheets e CIs** como mapa, não como obstáculo.
- 🛰️ **IoT, Drones & Robótica** — nanodegree na área; sensores, aquisição de sinal e integração embarcada.
- 💾 **C / C++** — vetores, gestão de memória, arrays e lógica de baixo nível; **C#** para desktop/console.

---

## 🎯 Focos atuais

<div align="center">

| 🤖 **IA & MCP** | ⚡ **Eletrônica** | 🔐 **Segurança** | 🛰️ **IoT & Robótica** |
|:---:|:---:|:---:|:---:|
| Orquestração de agentes | PWM · IGBT · drivers | RF / Sub-GHz | Sensores & aquisição |
| Desenvolvimento assistido | Circuitos de potência | Replay & código fixo | ESP32 & embarcado |
| Model Context Protocol | Datasheets & CIs | Scanners & recon | Drones & robótica |

</div>

---

## 🛠️ Projeto em destaque

### 📡 [`lorentzesp`](https://github.com/lorentz1/lorentzesp) — RF Cyberdeck

Ferramenta de **auditoria de RF sub-GHz** sobre **ESP32 + CC1101**, para testar a resistência de sistemas de controle (portões, controles, alarmes) a ataques de **replay**.

`ESP32` · `CC1101` · `OOK` · `RMT` · `SSD1306/U8g2` · `NVS`

- Medição de **RSSI**, varredura de espectro (315 / 433 / 868 / 915 MHz) e detecção por limiar
- **Captura, reconhecimento e retransmissão** de sinais OOK via RMT, com armazenamento persistente versionado
- Interface *RF Cyberdeck* em OLED com encoder incremental e estados operacionais explícitos (`RX` · `SCAN` · `LOCK` · `TX`)
- Arquitetura em domínios (`radio` · `signal` · `storage` · `ui`), 100% documentada
- ⚠️ *Uso exclusivo em equipamentos próprios ou com autorização — pesquisa e educação em segurança.*

> Demonstra na prática por que **código fixo é vulnerável a replay** e por que **rolling-code** resiste.

**Outros repositórios de segurança:**
🔎 [`multipleScanner`](https://github.com/lorentz1/multipleScanner) — scanner de listas de domínios e subdomínios · `Shell` &nbsp;·&nbsp; 🔐 [`Basic-Xoring`](https://github.com/lorentz1/Basic-Xoring) — cifra/decifra XOR de chave única · `C`

---

## 🧰 Caixa de ferramentas

<div align="center">

**Embarcado & RF** &nbsp;·&nbsp; ESP32 · Arduino · CC1101 · SPI/I²C · RMT · GPIO · OOK/ASK
**Eletrônica** &nbsp;·&nbsp; PWM · IGBT · MOSFET · drivers · circuitos de potência · osciloscópio · datasheets
**Linguagens** &nbsp;·&nbsp; C · C++ · C# · Shell
**IA & Fluxo** &nbsp;·&nbsp; Orquestração de agentes · MCP · desenvolvimento assistido · Git

<br>

<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/c/c-original.svg" width="42" height="42" alt="C" />&nbsp;&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/cplusplus/cplusplus-original.svg" width="42" height="42" alt="C++" />&nbsp;&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/csharp/csharp-original.svg" width="42" height="42" alt="C#" />&nbsp;&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/arduino/arduino-original.svg" width="42" height="42" alt="Arduino" />&nbsp;&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/raspberrypi/raspberrypi-original.svg" width="42" height="42" alt="Raspberry Pi" />&nbsp;&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/bash/bash-original.svg" width="42" height="42" alt="Bash" />&nbsp;&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linux/linux-original.svg" width="42" height="42" alt="Linux" />&nbsp;&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" width="42" height="42" alt="Git" />

</div>

---

<div align="center">

*"Aprendo o hardware a fundo, dirijo a IA como alavanca, e trato segurança como engenharia — não como mágica."*

</div>
