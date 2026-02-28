---
layout: default
title: Docs Home
permalink: /
---
<!-- NYXERA_BRANDING_HEADER_START -->
<p align="center">
  <img src="/assets/img/product-logo.png" alt="SpectraStrike" width="220" />
</p>

<p align="center">
  <a href="https://docs.nyxera.cloud">Docs</a> |
  <a href="https://spectrastrike.nyxera.cloud">SpectraStrike</a> |
  <a href="https://nexus.nyxera.cloud">Nexus</a> |
  <a href="https://nyxera.cloud">Nyxera Labs</a>
</p>
<!-- NYXERA_BRANDING_HEADER_END -->


# SpectraStrike Documentation

## SpectraStrike — Operational Fabric for Attested Offensive Validation

SpectraStrike orchestrates deterministic offensive validation workflows with cryptographic attestation, policy-first execution controls, and telemetry artifacts ready for enterprise assurance pipelines.

## Problem Statement

Traditional offensive simulation workflows produce execution logs without strong provenance, repeatability guarantees, or evidence chains that survive audit and governance scrutiny. SpectraStrike closes that gap by enforcing policy, wrapper integrity, and signed execution telemetry.

## Architecture Overview

```mermaid
flowchart LR
Operator --> PolicyEngine
PolicyEngine --> ExecutionEngine
ExecutionEngine --> Wrapper
Wrapper --> TelemetryEmitter
TelemetryEmitter --> VectorVue
```

## Core Sections

- [Getting Started]({{ '/getting-started/' | relative_url }})
- [Architecture]({{ '/architecture/' | relative_url }})
- [Execution Engine]({{ '/execution-engine/' | relative_url }})
- [Wrapper Framework]({{ '/wrapper-framework/' | relative_url }})
- [Attestation & Signing]({{ '/attestation-signing/' | relative_url }})
- [Telemetry Model]({{ '/telemetry-model/' | relative_url }})
- [Policy Enforcement]({{ '/policy-enforcement/' | relative_url }})
- [CLI Reference]({{ '/cli-reference/' | relative_url }})
- [API Reference]({{ '/api-reference/' | relative_url }})
- [Enterprise Deployment]({{ '/enterprise-deployment/' | relative_url }})
- [Diagrams]({{ '/diagrams/' | relative_url }})

## Cross Product Links

- [VectorVue Docs](https://docs.vectorvue.nyxera.cloud)
- [Nyxera Nexus Docs](https://docs.nexus.nyxera.cloud)
- [Nyxera Cloud](https://nyxera.cloud)

<!-- NYXERA_BRANDING_FOOTER_START -->

---

<p align="center">
  <img src="/assets/img/nyxera-logo.png" alt="Nyxera Labs" width="110" />
</p>

<p align="center">
  2026 SpectraStrike by Nyxera Labs. All rights reserved.
</p>

<p align="center">
  <a href="https://docs.nyxera.cloud">Docs</a> |
  <a href="https://spectrastrike.nyxera.cloud">SpectraStrike</a> |
  <a href="https://nexus.nyxera.cloud">Nexus</a> |
  <a href="https://nyxera.cloud">Nyxera Labs</a>
</p>
<!-- NYXERA_BRANDING_FOOTER_END -->
