# Architecture

## High-level architecture
- Classification: CORE HEALTHCARE / CLINICAL AI
- Category: clinical-ai
- Confidence: HIGH
- Exposure risk: HIGH

```mermaid
    flowchart LR
        A[Web client]
    B[Access gate]
    C[Hybrid processing layer]
    D[Structured job control]
    E[Result delivery surface]
        A --> B
    B --> C
    C --> D
    D --> E
```

## Public-safe component view
- Web client
- Access gate
- Hybrid processing layer
- Structured job control
- Result delivery surface

## Boundary notes
- This diagram is intentionally high level.
- No internal routes, private services, live storage names, or deployment details are published.
- The public-safe view is limited to product layers that can be discussed without weakening security.
