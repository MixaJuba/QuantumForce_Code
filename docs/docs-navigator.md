---
title: "Docs Navigator"
version: "0.1.0"
date: "2025-10-27"
category: "how-to"
tags: ["navigation", "ai-agents"]
safety_level: "QM"
emission_compliance: false
---

# Docs Navigator

Карти розділів і швидкі маршрути для людей і ШІ-агентів.

## Карта сайтмапу
```mermaid
graph TD
  A[Home] --> B[Getting Started]
  A --> C[Reference]
  A --> D[Architecture]
  A --> E[Compliance]
  A --> F[Development]
  C --> C1[Protocols]
  C --> C2[DTC Codes]
  C --> C3[API]
```

## Шаблони пошуку
- "PID timing site:reference/protocols"
- "ASIL-D safety site:safety"
- "GDPR site:compliance"

## Перехресні посилання
- Глосарій: `glossary.md`
- ADR: `architecture/decisions/`
- Безпека: `compliance/iso-26262.md`
