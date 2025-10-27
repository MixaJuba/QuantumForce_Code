---
title: "Docs Monitoring"
version: "0.1.0"
date: "2025-10-27"
category: "how-to"
tags: ["monitoring", "ci", "quality"]
safety_level: "QM"
emission_compliance: false
---

# Моніторинг документації

## Якітні ворота (CI)
- markdownlint (MD013 ≤ 120, MD041 оф)
- Vale (правопис і стиль)
- Codespell (помилки)
- Lychee (биті лінки)
- Mermaid CLI (валідація діаграм)

## Показники
- Broken links = 0
- Lint pass rate = 100%
- Review SLA < 24h

## Локальний запуск
```bash
markdownlint '**/*.md'
lychee --verbose './**/*.md'
```

## Інциденти
- Відкривайте `Documentation task` з міткою `docs` і додавайте журнал інциденту.
