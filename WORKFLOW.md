# Workflow

## High-level functional workflow
1. Choose a document workflow
2. Provide a file
3. Apply controlled processing
4. Review high-level output
5. Export a sanitized result

```mermaid
    flowchart TD
        S1["Choose a document workflow"]
    S2["Provide a file"]
    S3["Apply controlled processing"]
    S4["Review high-level output"]
    S5["Export a sanitized result"]
    S1 --> S2
    S2 --> S3
    S3 --> S4
    S4 --> S5
```

## Publication boundary
- The workflow is intentionally simplified.
- No internal rules, private thresholds, or sensitive processing detail are described here.
