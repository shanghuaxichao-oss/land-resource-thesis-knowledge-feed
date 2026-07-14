# Security Policy

This repository is a public, read-only distribution feed for signed knowledge candidates. It does not contain signing private keys, model API keys, user documents, or application databases.

Every published package is protected by SHA-256 and an Ed25519 signature. The desktop application imports new material as `pending/staged`; publication in this feed does not mean that a source has passed academic or domain-expert review.

Do not report suspected credentials or exploitable details in a public issue. Use GitHub's private vulnerability reporting for this repository instead:

https://github.com/shanghuaxichao-oss/land-resource-thesis-knowledge-feed/security/advisories/new

No software or update mechanism can be guaranteed absolutely secure. Releases are assessed against the documented threat model and should be verified with the published hashes and signatures.
