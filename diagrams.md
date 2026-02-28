---
layout: default
title: Diagrams
permalink: /diagrams/
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


# Diagrams

## System Architecture

```mermaid
flowchart LR
Operator --> PolicyEngine
PolicyEngine --> ExecutionEngine
ExecutionEngine --> Wrapper
Wrapper --> TelemetryEmitter
TelemetryEmitter --> VectorVue
```

## Data Model

```mermaid
flowchart TD
ExecutionIntent --> ExecutionFingerprint
ExecutionFingerprint --> AttestationHash
AttestationHash --> SignedEvidence
SignedEvidence --> CorrelatedRecord
```

## Wrapper Lifecycle

```mermaid
flowchart LR
SelectTool --> ValidatePolicy --> LaunchWrapper --> CaptureOutput --> Canonicalize --> Sign --> Emit
```

## Federation Model

```mermaid
flowchart TD
TenantA --> FederationGateway
TenantB --> FederationGateway
FederationGateway --> VectorVueCore
```

## Evidence Lifecycle

```mermaid
flowchart LR
WrapperOutput --> CanonicalEvent --> Signature --> Ingestion --> Correlation --> Dashboard
```

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
