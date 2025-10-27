---
title: "DoIP Reference (ISO 13400)"
version: "0.1.0"
date: "2025-10-27"
category: "reference"
tags: ["doip", "iso-13400", "tcp-ip"]
safety_level: "QM"
emission_compliance: true
---

# Diagnostics over IP (DoIP)

## Транспорт
- TCP/UDP, стандартний порт 13400 (OEM specific)
- Виявлення ECU через Vehicle Announcement/Entity Status

## Сесії
- UDS поверх DoIP, маршрутизація до target address

## Вимоги до мережі
- Low jitter, stable MTU, QoS для діагностичних потоків
