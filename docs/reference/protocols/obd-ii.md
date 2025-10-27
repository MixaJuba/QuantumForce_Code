---
title: "OBD-II Reference (SAE J1979)"
version: "0.1.0"
date: "2025-10-27"
category: "reference"
tags: ["obd-ii", "sae-j1979", "pids"]
safety_level: "QM"
emission_compliance: true
---

# OBD-II (SAE J1979)

> Стандартні PID, DTC, freeze frame. Сумісність з ELM327.

## Підтримувані служби (Mode 01/02/03/04/05/06/07/09)
- 01: Поточні дані (PIDs)
- 03: DTC
- 04: Скидання MIL
- 09: VIN, Calibration IDs

## Таймінги
- Init latency: 50–250 ms
- PID polling: ≥ 50 ms між запитами

## Приклад кадру
```text
> 010C
< 41 0C 1A F8   # RPM = 1726 rpm
```

## Посилання
- SAE J1979, SAE J2012
