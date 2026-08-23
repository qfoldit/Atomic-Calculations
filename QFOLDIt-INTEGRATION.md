# qFoldIT Integration

`Atomic-Calculations` is a domain-specific atomistic/materials lineage and compute source.

Canonical qFoldIT contracts live in:

- `qfoldit/UEFN-QFOLDIT/crates/qfoldit-core`
- `qfoldit/UEFN-QFOLDIT/crates/scientific-mcp`
- `qfoldit/UEFN-QFOLDIT/crates/atomic-adapter`

Do not introduce a second mission/state/provenance authority here. Scientific calculations may remain implementation-specific; their inputs/outputs should be wrapped by qFoldIT adapter contracts.
