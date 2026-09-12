# NIST AI RMF

| Control ID | NIST | Registry | Result | Message |
|---|---|---|---|---|
| `SEC-PII-001` | MAP 2.6, MANAGE 2.4 | partial | pass | scrubbed 3 probe cases |
| `SEC-PII-002` | MANAGE 2.4 | met | pass | verify_system --check-redaction passed |
| `SEC-AUDIT-001` | GOVERN 1.2 | met | fail | missing portal files: auditSignature.test.ts, auditSignature.ts |
