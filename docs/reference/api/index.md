---
title: "Diagnostic API"
version: "0.1.0"
date: "2025-10-27"
category: "reference"
tags: ["api"]
safety_level: "QM"
emission_compliance: true
---

# API

## Read PID
```yaml
request:
  pid: "0C"
  timeoutMs: 200
response:
  value: 1726
  unit: rpm
```

## ReadDataByIdentifier (UDS)
```yaml
request:
  did: "F190" # VIN
  timeoutMs: 500
response:
  dataHex: "313233..."
```
