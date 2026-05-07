<picture>
  <source media="(prefers-color-scheme: dark)" srcset=".github/banner-dark.svg">
  <img alt="Carlos Jimenez — Software engineer building public-safety tools and self-hosted infrastructure in San Diego." src=".github/banner-light.svg" width="100%">
</picture>

I build tools that work in the real world — from **mission-critical desktop apps for the San Diego Fire Department** to internal developer tooling, automation systems, and self-hosted infrastructure. I care about reliability, clean architecture, and shipping things that actually get used.

**Currently** — Flutter, Python, C#, and RabbitMQ on public-safety software. Personal work spans Rust desktop apps, Python automation, and data tooling.

- Shipping CADSOS enhancements — paging, incident map layers, ArcGIS integrations
- Built **TorchDocTool** — browser-based schema documentation via SQL Server extended properties
- Exploring desktop development with **Rust + Tauri** — see *Junbi* below
- Self-hosted infrastructure on a Raspberry Pi 5 — WireGuard, Nginx, no cloud preferred
- B.S. Computer Science, Cal State San Marcos · AWS Certified Cloud Practitioner · Oracle Certified Associate, Java SE Programmer

---

## Notable Work

*All projects below are closed-source / internal — descriptions only.*

| Project | Stack | What it does |
|---|---|---|
| **CADSOS** | Flutter · Dart · RabbitMQ · SQL Server · Riverpod | Live incident-tracking app for SDFD with ArcGIS map layers. RPC-style messaging over RabbitMQ, real-time streams, built for restricted offline networks. |
| **Special Status Queue** | Flutter · Dart · Python · C# · RabbitMQ · SQL Server | Out-of-service unit tracking for SDFD dispatchers and field crews. RPC messaging, real-time streams, same offline-first constraints as CADSOS. |
| **TorchDocTool** | React · JavaScript · SQL Server | Browser-based schema documentation. Attaches structured metadata to SQL Server tables and columns via extended properties — the docs live inside the database itself. |
| **Aircraft Order** | Flutter · Python · C# / .NET · SQL Server | Cross-language ordering workflow demonstrating a multi-tier RPC chain: Flutter UI → Python service → C# / .NET data layer, fully logged to SQL Server. |
| **Interface Restart Automation** | Python · PsExec · schtasks | Maps logical interface names to their host servers and triggers remote scheduled-task restarts — turns a cross-host restart into one command. |

## Personal Projects

| Project | Stack | What it does |
|---|---|---|
| **Junbi** | Rust · Tauri · JavaScript | Cross-platform desktop app built on Tauri — Rust backend, web-tech frontend, native binary output. |
| **swingscanner** | Python · PowerShell · HTML | Swing-trade screener: scans market data and surfaces candidate setups, with HTML reports and Windows-side automation. |

## Toolbox

**Languages**
![Dart](https://img.shields.io/badge/Dart-0175C2?style=flat-square&logo=dart&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C#](https://img.shields.io/badge/C%23-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![Swift](https://img.shields.io/badge/Swift-F05138?style=flat-square&logo=swift&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)

**Frameworks**
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![.NET](https://img.shields.io/badge/.NET-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![Tauri](https://img.shields.io/badge/Tauri-24C8DB?style=flat-square&logo=tauri&logoColor=black)

**Data & messaging**
![SQL Server](https://img.shields.io/badge/SQL_Server-CC2927?style=flat-square&logo=microsoftsqlserver&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=flat-square&logo=rabbitmq&logoColor=white)

**Infrastructure & automation**
![Linux](https://img.shields.io/badge/Linux-1A1A1A?style=flat-square&logo=linux&logoColor=FCC624)
![Raspberry Pi](https://img.shields.io/badge/Raspberry_Pi-A22846?style=flat-square&logo=raspberrypi&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=flat-square&logo=powershell&logoColor=white)

---

## Get in Touch

I'm open to conversations about public-safety software, self-hosted infrastructure, or anything in the Flutter / .NET / RabbitMQ orbit.

[**LinkedIn**](https://www.linkedin.com/in/jimenezcarlos-/) · [**Email**](mailto:carlosjimenez.eng@gmail.com)

<!--
ca-jimen/ca-jimen is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
-->
