<h1 align="center">Hi, I'm Xorlent</h1>

<p align="center">
  <b>Cybersecurity practitioner &amp; Electrical engineer</b><br/>
  I build low-cost, open hardware security appliances and ESP32/Arduino firmware that solve
  real-world problems.
</p>

<p align="center">
  <a href="https://xorlent.github.io/">Website</a> &nbsp;&middot;&nbsp;
  <a href="https://github.com/Xorlent?tab=repositories&sort=stargazers">Top repos</a>
</p>

<p align="center">
  <img alt="Focus" src="https://img.shields.io/badge/focus-embedded%20%2B%20blue%20team-informational"/>
  <img alt="Languages" src="https://img.shields.io/badge/languages-C%2B%2B%2C%20C%2C%20PowerShell%2C%20Go%2C%20C%23-blue"/>
  <img alt="Hardware" src="https://img.shields.io/badge/hardware-ESP32%2C%20ESP32--P4%2C%20PoE-green"/>
  <img alt="Published libraries" src="https://img.shields.io/badge/libraries-8%20published-orange"/>
</p>

---

## Focus

- **Embedded / IoT** - ESP32 & SAMD firmware, PoE-powered appliances, and Arduino libraries
- **Cybersecurity** - Honeypots/deception, network & OT/ICS monitoring, threat intelligence, endpoint and identity hygiene
- **Hardware** - Custom PCBs, 3D-printed enclosures, and full BOM-to-deployment build guides
- **Automation / Infrastructure** - PowerShell tooling, SNMP/PRTG monitoring, and serverless (Cloudflare Workers)

## Libraries

Available via Arduino Library Manager and the [PlatformIO registry](https://registry.platformio.org/search?q=xorlent):

| Library | What it does | Latest | License |
|---|---|---|---|
| **[ESP32IMDB](https://github.com/Xorlent/ESP32IMDB)** | Small, fast, thread-safe in-memory database for ESP32-Arduino | 1.1.3 | MIT |
| **[ESP32P4_ULP](https://github.com/Xorlent/ESP32P4_ULP)** | ESP32-P4 Ultra Low Power (LP-core) library for Arduino | 0.0.1 | MIT |
| **[Async_SHT4x](https://github.com/Xorlent/Async_SHT4x)** | Asynchronous Sensirion SHT4x temp/humidity library | 1.2.0 | BSD-3-Clause |
| **[SAMD_SafeFlashStorage](https://github.com/Xorlent/SAMD_SafeFlashStorage)** | Crash-safe flash storage for SAMD21/51 (checksums + validation) | 1.0.2 | LGPL-2.1 |
| **[ESP32_WS2812B](https://github.com/Xorlent/ESP32_WS2812B)** | Ultra-light WS2812B LED library (ESP32 RMT) | 1.0.5 | MIT |
| **[SAMD21_WS2812B](https://github.com/Xorlent/SAMD21_WS2812B)** | Ultra-light WS2812B LED library for SAMD21 | 1.0.5 | MIT |
| **[ESP32-EasyWolfSSL](https://github.com/Xorlent/ESP32-EasyWolfSSL)** | Simple Arduino wrapper for wolfSSL on ESP32 | 1.0.0 | GPL-3.0 |
| **[ESP32AI Voice Command](https://github.com/Xorlent/ESP32AI)** | On-device voice commands via I2S mic + Cloudflare Workers AI | 1.0.3 | MIT |

## Featured Projects

### Security appliances (open hardware, sensors)
| Project | Description |
|---|---|
| **[PoESP32-SNMP-Environmental-Monitor](https://github.com/Xorlent/PoESP32-SNMP-Environmental-Monitor)** | ~$32 PoE SNMP temperature/humidity monitor. Full build + 3D-printable mounts. |
| **[PoE-Honeypot](https://github.com/Xorlent/PoE-Honeypot)** | ~$22 PoE honeypot (ESP32-P4) listening on unlimited TCP/UDP ports, with Syslog/SMTP alerting. |
| **[The-26-Dollar-Honeypot](https://github.com/Xorlent/The-26-Dollar-Honeypot)** | The original low-cost PoE honeypot appliance. |
| **[ESP32-Watchman](https://github.com/Xorlent/ESP32-Watchman)** | Sub-$35 PoE physical + RF watchdog: BLE presence, light and motion sensing. |
| **[PoE-Passkey](https://github.com/Xorlent/PoE-Passkey)** | ESP32-P4 FIDO2/WebAuthn relying party for passkey-based client pre-authentication. |

### OT / ICS & network security
| Project | Description |
|---|---|
| **[SCADASentry](https://github.com/Xorlent/SCADASentry)** | Allen-Bradley ControlLogix PLC network & vulnerability monitor with SNMP trap / SMTP alerts. |
| **[ESP32ControlLogix](https://github.com/Xorlent/ESP32ControlLogix)** | ESP32-Arduino Ethernet/IP (CIP) protocol library for ControlLogix. |
| **[Cisco-OSPF-Monitor](https://github.com/Xorlent/Cisco-OSPF-Monitor)** | Cisco OSPF neighbor health monitoring and network visualization. |
| **[PRTG-OIDLIBS](https://github.com/Xorlent/PRTG-OIDLIBS)** | PRTG custom OID libraries (MIBs) and device templates. |

### Blue-team tools
| Project | Description |
|---|---|
| **[Falcon-Contain](https://github.com/Xorlent/Falcon-Contain)** | GUI for flexible CrowdStrike Falcon host containment. |
| **[O365-Monitor](https://github.com/Xorlent/O365-Monitor)** | Office 365 hygiene and account monitoring (Microsoft Graph). |
| **[Windows-SRP-Policy-Generator](https://github.com/Xorlent/Windows-SRP-Policy-Generator)** | Hash-based Software Restriction Policy `.pol` generator. |
| **[DNS-Data-Diode](https://github.com/Xorlent/DNS-Data-Diode)** | One-way file transfer using DNS as a data diode. |

### Handy utilities
| Project | Description |
|---|---|
| **[Vaydeer-9-Key-Programmer](https://github.com/Xorlent/Vaydeer-9-Key-Programmer)** | CLI USB-HID programmer for the Vaydeer 9-key pad (Go, cross-platform). |
| **[Easy-Cisco-Backup](https://github.com/Xorlent/Easy-Cisco-Backup)** | The simplest Cisco IOS backup tool. |
| **[ESP32-Boards](https://github.com/Xorlent/ESP32-Boards)** | ESP32-based custom PCBs. |

---

<p align="center"><i>If a project saved you time or money, a ⭐ helps others find it!</i></p>
