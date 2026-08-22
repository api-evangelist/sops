# SOPS

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
