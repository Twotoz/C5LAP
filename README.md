<div align="center">
  <img src="assets/c5lap-logo.jpg" alt="C5LAP logo" width="760" />

  <p><strong>ESP32-C5 FPV Lap Timer</strong></p>
  <p>Building an FPV lap timer on the ESP32-C5, using the RF knowledge gained from C5VRX.</p>

  <p>
    <img src="https://img.shields.io/badge/status-early%20research-orange" alt="Early research" />
    <img src="https://img.shields.io/badge/chip-ESP32--C5-111111" alt="ESP32-C5" />
    <a href="https://github.com/Twotoz/C5VRX"><img src="https://img.shields.io/badge/based%20on-C5VRX-1f6feb" alt="Based on C5VRX knowledge" /></a>
  </p>
</div>

---

## What is C5LAP?

**C5LAP** is an early-stage project exploring an ESP32-C5-based lap timer for analog 5.8 GHz FPV racing. It builds on the experience and RF research from [C5VRX](https://github.com/Twotoz/C5VRX), applying that knowledge to detecting passes and measuring lap times.

## Planned setup

Connect C5LAP to a laptop via **USB-C** and control it through a **web UI**. The goal is to manage receiver settings, race sessions, and live lap times from one browser interface. The USB communication and browser integration will be researched before implementation.

## Research first, then build

This repository starts as a home for research, experiments, and design notes. The RF hardware, detection method, and firmware architecture are still to be determined.

1. **Research:** Explore the ESP32-C5 RF capabilities, signal measurements, reliable pass detection, and USB-to-browser communication.
2. **Prototype:** Build and test the hardware, firmware, and web UI based on the findings.
3. **Validate:** Test timing accuracy, repeatability, and behavior in real racing conditions.

**Current status: research phase.** There is no working lap timer or ready-to-flash firmware yet.

## Community

Ideas, findings, and contributions are welcome through [issues](https://github.com/Twotoz/C5LAP/issues). For the shared community and Discord link, visit the [C5VRX website](https://twotoz.github.io/C5VRX/).
