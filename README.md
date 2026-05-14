# SLSA Supply Chain Levels MCP

[![PyPI](https://img.shields.io/pypi/v/slsa-supply-chain-mcp)](https://pypi.org/project/slsa-supply-chain-mcp/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![MEOK AI Labs](https://img.shields.io/badge/MEOK_AI_Labs-governance--mcp-purple)](https://meok.ai)

SLSA (Supply chain Levels for Software Artifacts) v1.0 framework. Compute SLSA level + remediation roadmap for software releases.

## Install

```bash
pip install slsa-supply-chain-mcp
```

## Tools

| Tool | Purpose |
|------|---------|
| `compute_slsa_level` | Compute SLSA level (Build L1-L3, Source L1-L3) from CI/CD config |
| `validate_provenance` | Validate SLSA provenance attestation |
| `remediation_to_l3` | Roadmap to reach SLSA Build L3 |
| `list_requirements` | SLSA requirements per level + track |
| `verify_signed_artefact` | Verify Sigstore-signed artefact + attestation chain |

## Pairs with

- `meok-attestation-api` — POST results to https://meok-attestation-api.vercel.app/sign for cryptographically signed compliance certs
- `meok-attestation-verify` — public verification of any MEOK-signed cert
- Other MEOK governance MCPs via SOV3 `mcp_bridge_call`

## Pricing

- **Free**: 10 calls/day. No API key required.
- **Pro** £79/mo: unlimited + signed attestations. [Subscribe](https://buy.stripe.com/14A4gB3K4eUWgYR56o8k836)
- **Enterprise** £1,499/mo: white-label + on-premise + SLA. hello@meok.ai

## Status

Scaffold v1.0.0 ships the MCP framework + 5 tool stubs. v1.1.0 will add real regulation data ingestion.

If your team needs this MCP fully-loaded faster, ping hello@meok.ai for sponsored development.

## License

MIT © MEOK AI Labs
