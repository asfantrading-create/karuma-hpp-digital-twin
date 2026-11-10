<p align="center"><img src="docs/img/asfan-logo.png" alt="ASFAN" height="70"></p>

<h1 align="center">Karuma HPP Digital Twin</h1>
<p align="center"><b>Power System Training Simulator & SCADA</b><br>
Generation · Transmission · Distribution · Protection · 3D Training Lab<br>
<i>Software designed &amp; developed by ASFAN</i></p>

---

## Downloads (Windows 10 / 11, 64-bit)

| File | Description | Link |
|---|---|---|
| **Setup installer** | Installs the app with Start-menu and desktop shortcuts | [Karuma-HPP-Digital-Twin-1.0.0-Setup.exe](https://github.com/asfantrading-create/karuma-hpp-digital-twin/releases/latest/download/Karuma-HPP-Digital-Twin-1.0.0-Setup.exe) |
| **Portable** | Single EXE, no installation needed | [Karuma-HPP-Digital-Twin-1.0.0-Portable.exe](https://github.com/asfantrading-create/karuma-hpp-digital-twin/releases/latest/download/Karuma-HPP-Digital-Twin-1.0.0-Portable.exe) |
| **Datasheet (PDF)** | Full technical datasheet in English | [Karuma-HPP-Digital-Twin-Datasheet.pdf](https://github.com/asfantrading-create/karuma-hpp-digital-twin/releases/latest/download/Karuma-HPP-Digital-Twin-Datasheet.pdf) · [view in repo](docs/Karuma-HPP-Digital-Twin-Datasheet.pdf) |

All releases: <https://github.com/asfantrading-create/karuma-hpp-digital-twin/releases>

> Windows SmartScreen may show "Windows protected your PC" for a new publisher. Choose **More info → Run anyway**.

## What it does

A real-time digital twin of the Karuma HPP power-system training laboratory:

- **Generation**: 2 × 75 MVA hydro units with turbine, governor, excitation/AVR, start-up sequence, synchroscope and P-Q capability chart.
- **Transmission**: 2 × 80 MVA step-up transformers, a 220 kV double-circuit line (2 × 85 km) and a grid interconnector with synchro-check.
- **Distribution**: a 150 MVA 220/33 kV transformer with OLTC, four 33 kV feeders, distribution transformers with voltage regulation, a capacitor bank and voltage- and frequency-dependent loads.
- **SCADA**: Overview, Generation, Transmission, Distribution, Alarms & Events, Reports and Trends pages.
- **Monitoring and control**:
  - live voltage, current, MW, MVAr and Hz;
  - breaker control with interlocking;
  - load and generation control;
  - Newton-Raphson power-flow analysis.
- **Protection**:
  - 65 relay functions (87G, 87T, 87B, 21, 67N, 51/51N, 81, 59, 27, 79 and more);
  - R-X diagram;
  - time-current coordination;
  - disturbance recorder.
- **Faults and training**:
  - 3-phase, L-G, L-L and L-L-G faults;
  - malfunctions and breaker failure;
  - guided training scenarios with automatic assessment.
- **Workstations**: an instructor station plus trainee workstations over the classroom network.
- **3D training lab**: an interactive 3D model of the whole laboratory, linked to live data.
  - Each of the 14 desk monitors shows its own live page: hydro units 1 and 2, step-up transformers, 220 kV lines, grid interconnector, substation and OLTC, feeders 1–4, protection, power balance and AGC, plus the instructor's alarms and energy-flow pages.
  - Click a monitor to zoom in and read it.

## Screenshots

![Trainee workstations in the 3D lab](docs/img/desks.jpg)
*Trainee workstations in the 3D lab: every monitor shows a different part of the power system.*

| | |
|---|---|
| ![Overview](docs/img/overview.jpg) | ![3D lab](docs/img/lab.jpg) |
| SCADA overview | 3D training lab |
| ![Generation](docs/img/generation.jpg) | ![Transmission](docs/img/transmission.jpg) |
| Generator control & AVR | Transmission |
| ![Distribution](docs/img/distribution.jpg) | ![Protection](docs/img/protection.jpg) |
| Distribution | Protection relays |
| ![Recorder](docs/img/recorder.jpg) | ![Trends](docs/img/trends.jpg) |
| Disturbance recorder | Trends |
| ![Instructor](docs/img/instructor.jpg) | ![Reports](docs/img/reports.jpg) |
| Instructor station | Reports |

## Developer

**ASFAN**: software design and development
info@asfanco.com · WhatsApp +962 7 7614 0404

© ASFAN. All rights reserved. This repository contains release binaries and documentation only.
