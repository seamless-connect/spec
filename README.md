# Seamless Connect specifications

**Open Infrastructure for Cross-Provider Internet Operations**

Seamless Connect is an open-source, nonprofit infrastructure project providing a neutral coordination layer between service providers, DNS providers, and registrars, initially focused on DNS configuration through Domain Connect.

A neutral home for standards-adjacent specifications and governance material supporting neutral cross-provider coordination and its provider interfaces, separate from implementation code. The existing project charter remains the governance reference.

Early industry participation includes Name.com (Identity Digital), Cloudflare, DigiCert, Datum.net, and Cloud 66.

The initial focus is DNS configuration through Domain Connect. DNSSEC, Primary / Secondary DNS, Domain Registration, and Agent Bootstrapping describe planned or developing workflows; availability depends on the operation and participating provider integrations. Industry participation does not imply implemented integrations.

[Use Cases & Protocols](https://seamlessconnect.org/use-cases/) · [Canonical project description](https://github.com/seamless-connect/.github/blob/main/PROJECT-DESCRIPTION.md)

## Messaging reference and review

The current [`PROJECT-DESCRIPTION.md` on `.github/main`](https://github.com/seamless-connect/.github/blob/main/PROJECT-DESCRIPTION.md) is the canonical public messaging source. Review that source before changing project positioning. Interfaces (including APIs, CLIs, and authorized software agents) support the coordination service. They do not define the project. Messaging changes do not change the charter, technical specifications, provider support, or capability statuses.

Run `python3 -m unittest discover -s tests -p "test_messaging.py"` to check this README for positioning drift. The checks run offline and do not copy or modify the canonical description. They are guardrails for recurring errors, not a substitute for reviewing the canonical source.
