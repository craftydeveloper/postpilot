# Security review

## Product risks

A draft can be mistaken for a published post. Keep draft, approved, and published states distinct.

## Baseline

Treat imported text as untrusted, bound input sizes, avoid unsafe HTML insertion, keep credentials out of client code, and verify external links. This checklist is not a security certification.