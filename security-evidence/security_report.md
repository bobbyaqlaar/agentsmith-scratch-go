# Security harness report

Mode: `smoke`  — **a smoke run examines three controls; the rest were not attempted, not passed.**

| Control ID | Title | Registry | Owner | Result | Message |
|---|---|---|---|---|---|
| `SEC-PII-001` | PII pre-call scrub | partial | shared | pass | scrubbed 3 probe cases |
| `SEC-PII-002` | Trace redaction | met | framework | pass | verify_system --check-redaction passed |
| `SEC-AUDIT-001` | HMAC audit log | met | framework | fail | missing portal files: auditSignature.test.ts, auditSignature.ts |

## Summary

- **fail**: 1
- **pass**: 2
