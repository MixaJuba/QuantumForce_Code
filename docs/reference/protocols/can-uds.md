---
title: "CAN-UDS Reference (ISO 14229)"
version: "0.1.0"
date: "2025-10-27"
category: "reference"
tags: ["uds", "iso-14229", "can"]
safety_level: "QM"
emission_compliance: true
---

# UDS over CAN (ISO 14229)

## Ключові служби
- 0x10 Diagnostic Session Control
- 0x11 ECU Reset
- 0x22 ReadDataByIdentifier
- 0x2E WriteDataByIdentifier
- 0x27 SecurityAccess (не документувати ключові алгоритми)

## Транспорт
- ISO-TP (ISO 15765-2): SF/FF/CF/FC кадри

## Таймінги
- P2 = 50–200 ms, P2* до 5000 ms

## Безпека
- Без розкриття секретів або процедур обходу імобілайзера
