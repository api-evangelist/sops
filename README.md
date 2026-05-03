# SOPS

SOPS (Secrets OPerationS) is a CNCF Sandbox encrypted file editor that supports YAML, JSON, ENV, INI, and binary formats. SOPS encrypts file values while leaving keys in cleartext, enabling secure storage of secrets in version control systems. Supports AWS KMS, GCP KMS, Azure Key Vault, HuaweiCloud KMS, age, and PGP for key management. Originally created at Mozilla and donated to the CNCF in 2023.

**URL:** [https://github.com/getsops/sops](https://github.com/getsops/sops)

## Tags

Secrets Management, Encryption, Configuration Management, DevOps, Security, Kubernetes, CNCF

## Timestamps

- **Created:** 2025
- **Modified:** 2026-05-02

## APIs

### SOPS Go Library

The SOPS decrypt Go package provides programmatic access to SOPS-encrypted files from Go applications. Supports decryption of YAML, JSON, ENV, INI, and binary formats using configured key management services.

**Human URL:** [https://getsops.io/docs/](https://getsops.io/docs/)

#### Properties

- [Documentation](https://getsops.io/docs/)
- [GitHub](https://github.com/getsops/sops)
- [Releases](https://github.com/getsops/sops/releases)

## Features

- Encrypts file values while keeping keys in cleartext
- Supports AWS KMS, GCP KMS, Azure Key Vault, HuaweiCloud KMS, age, PGP
- Works with YAML, JSON, ENV, INI, and binary file formats
- Key groups using Shamir Secret Sharing for multi-factor access control
- Audit logging via PostgreSQL integration
- Git integration for transparent decryption in diffs
- Configuration file (.sops.yaml) for creation and destination rules
- exec-env and exec-file commands to avoid secret exposure to disk
- In-place encryption/decryption for workflow integration

## Integrations

AWS KMS, GCP KMS, Azure Key Vault, HuaweiCloud KMS, age encryption, PGP/GPG, Kubernetes Secrets, Flux CD, ArgoCD, Helm

## Artifacts

### JSON Schemas

| Schema | File |
|--------|------|
| Encrypted File | [json-schema/sops-encrypted-file-schema.json](json-schema/sops-encrypted-file-schema.json) |

### JSON Structures

| Structure | File |
|-----------|------|
| Configuration | [json-structure/sops-config-structure.json](json-structure/sops-config-structure.json) |

### JSON-LD Contexts

| Context | File |
|---------|------|
| SOPS | [json-ld/sops-context.jsonld](json-ld/sops-context.jsonld) |

### Examples

| Example | File |
|---------|------|
| Encrypt File | [examples/sops-encrypt-file-example.json](examples/sops-encrypt-file-example.json) |

### Vocabulary

| Vocabulary | File |
|------------|------|
| SOPS | [vocabulary/sops-vocabulary.yml](vocabulary/sops-vocabulary.yml) |

## Common Properties

- [Website](https://getsops.io/)
- [Documentation](https://getsops.io/docs/)
- [GitHub Org](https://github.com/getsops)
- [GitHub Repository](https://github.com/getsops/sops)
- [Releases](https://github.com/getsops/sops/releases)
- [CNCF Sandbox](https://www.cncf.io/projects/sops/)
- [Flux Integration](https://fluxcd.io/flux/guides/mozilla-sops/)
- [Security](https://github.com/getsops/sops/blob/main/SECURITY.md)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
