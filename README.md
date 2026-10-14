<h1 align="center">Nexara</h1>

<p align="center">
  <b>Automated SSR/128T, SRX &amp; EdgeConnect Diagnostic Analyser</b><br/>
  Turn a support bundle into answers in seconds.
</p>

<p align="center">
  <a href="https://yambati-jnpr.github.io/nexara-site/"><b>🌐 Website</b></a> ·
  <a href="https://github.com/yambati-JNPR/nexara-site/releases/latest"><b>⬇️ Download</b></a>
</p>

---

Nexara is a browser-based diagnostic tool for Juniper **SSR/128T** routers — with dedicated analysis modes for **SRX** firewalls and **EdgeConnect** SD-WAN appliances. Upload a Tech Support Info (TSI) bundle, RSI output or EdgeConnect sysdump and Nexara automatically analyses the data, runs a full suite of indicators, and surfaces actionable findings across a structured set of views. It runs entirely on your machine — no external dependencies, and bundles never leave your computer.

This repository hosts the **official website and installer downloads**. The application source lives in a separate private repository.

## Download

| Platform | Installer |
|----------|-----------|
| 🍎 macOS | [Nexara-v3.4.0-macOS.dmg](https://github.com/yambati-JNPR/nexara-site/releases/download/v3.4.0/Nexara-v3.4.0-macOS.dmg) |
| 🪟 Windows | [Nexara-v3.4.0-Windows-Setup.exe](https://github.com/yambati-JNPR/nexara-site/releases/download/v3.4.0/Nexara-v3.4.0-Windows-Setup.exe) |

See the [Releases](https://github.com/yambati-JNPR/nexara-site/releases) page for all versions and checksums.

## What it does

- **Automated indicators** — 55+ system, traffic, and network checks with detection logic, evidence, and corrective actions.
- **Critical &amp; Deep Insights** — a dashboard of what matters first, then every finding sorted by severity.
- **Debug &amp; RCA** — pattern-based log + PCAP analysis, deterministic crash stack-trace RCA, and optional LLM-powered root-cause analysis.
- **Performance metrics** — CPU, memory, and packet-processing charts over time with per-node filters for HA.
- **Parsed views** — Sessions, Interfaces, Services, Alarms, Events, FIB, Routing, and BGP rendered as clean tables.
- **EdgeConnect workspace** — sysdump analysis with an alarms timeline (severity, action and category filters), tunnel/interface/traffic-class telemetry in bps/Kbps/Mbps, key log indicators, hardware sensors and power-supply events, SAR history, and HTML/JSON/CSV exports.
- **Three pipelines** — SSR/128T (TSI bundle), SRX (RSI output) and EdgeConnect (sysdump `.tgz`), auto-detected and fully separated.

## How it works

1. **Install &amp; launch** Nexara, then open `http://localhost:8443` in your browser.
2. **Drop your bundle** — a `.zip` TSI or RSI archive, or an EdgeConnect sysdump `.tgz` (upload both HA node bundles together for side-by-side analysis).
3. **Read the findings** — critical insights, evidence, charts, and corrective actions across structured views.

## Website

The site is served via GitHub Pages from the `main` branch root (`index.html`).
To publish: **Settings → Pages → Source: Deploy from a branch → `main` / `/ (root)`**.

## Authors

- **Bhaskar Gaddam** — [LinkedIn](https://www.linkedin.com/in/bhaskar-reddy-gaddam-a4118a53/)
- **Yeshwanth Ambati** — [LinkedIn](https://www.linkedin.com/in/yeshwanth-ambati/)
