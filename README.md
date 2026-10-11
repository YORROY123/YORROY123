### Hi, I'm 林子揚 (Roy) 👋

🏢 Industrial Technology Research Institute (ITRI) · 工研院

**Hardware × software.** I design PCBs with AI agents and scripts, build IoT / embedded systems (ESP32, nRF, Raspberry Pi), and fix the open-source EDA tools I run into along the way.

我用 AI agent 與程式畫電路板,做 ESP32 / nRF / 樹莓派的嵌入式與 IoT 系統,順手修好路上踩到的開源 EDA 工具。

---

#### 🔧 Featured

| Project | What it is |
|---|---|
| [**kicad-scripted-pcb**](https://github.com/YORROY123/kicad-scripted-pcb) | Three KiCad 10 boards written entirely as Python: schematic → ERC → netlist check → datasheet design review → placement → freerouting → DRC → Gerber/BOM/CPL. Byte-for-byte reproducible builds, ngspice simulations, a 2-D field solver for trace impedance. |
| [**easyeda-pro-extension-notes**](https://github.com/YORROY123/easyeda-pro-extension-notes) | Field notes on EasyEDA Pro's extension host: why side-loaded extensions never activate after a restart, and how to get evidence when they don't. 中英雙語。 |
| [**usbc-5v-to-3v3-ldo**](https://github.com/YORROY123/usbc-5v-to-3v3-ldo) | A USB-C 5 V → 3.3 V board designed end-to-end by an AI agent. |
| [**selfhosted-llm-toolkit**](https://github.com/YORROY123/selfhosted-llm-toolkit) | Connect a self-hosted OpenAI-compatible LLM (vLLM / LiteLLM / Ollama) to coding agents, a web UI and a terminal chat. |
| [**iot-energy-cloud**](https://github.com/YORROY123/iot-energy-cloud) | Multi-tenant IoT energy-management platform (EMQX + InfluxDB + FastAPI). |

#### 🌍 Open-source contributions

- **[freerouting](https://github.com/freerouting/freerouting)**: CLI `-l` flag read as both language and log path ([#963](https://github.com/freerouting/freerouting/pull/963)); LLM scaffolding leaking into locale files ([#964](https://github.com/freerouting/freerouting/pull/964))
- **[FluidNC](https://github.com/bdring/FluidNC)**: swapped MISO/MOSI arguments for SPI Ethernet PHYs ([#1835](https://github.com/bdring/FluidNC/pull/1835))
- **[easyeda-agent](https://github.com/zhoushoujianwork/easyeda-agent)**: 14 merged PRs, including the schematic-frame y-sign bug ([#238](https://github.com/zhoushoujianwork/easyeda-agent/pull/238)), a native Windows installer ([#229](https://github.com/zhoushoujianwork/easyeda-agent/pull/229)) and fixes for CI on dev versions ([#232](https://github.com/zhoushoujianwork/easyeda-agent/pull/232))
- Bug reports to **Espressif** ([esp-eth-drivers#178](https://github.com/espressif/esp-eth-drivers/issues/178), W5500 reset timing) and **EasyEDA** ([easyeda-api-skill#18](https://github.com/easyeda/easyeda-api-skill/issues/18), extension activation)

#### 🛠 Tools

KiCad · EasyEDA Pro · ngspice · freerouting · Python · Go · ESP-IDF / Arduino · Zephyr (nRF) · FastAPI · MQTT · Flutter

---

<sub>Every board here passes ERC/DRC, but none has been manufactured yet. Checks are scripted; the final review is human.</sub>
