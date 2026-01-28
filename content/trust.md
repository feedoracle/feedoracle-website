---
title: Trust & Controls
description: DORA-supporting controls for ICT third-party risk assessments
---

# Operational Resilience & Controls

DORA-supporting controls for ICT third-party risk assessments

---

## Incident Management
- Severity classification (SEV0–SEV3)
- Documented response procedures
- Postmortem and RCA process

## Monitoring & Logging
- Structured audit logging
- Request correlation (request_id)
- Daily SLO evidence snapshots

## Backup & Recovery
- RPO Target: ≤1 hour
- RTO Target: ≤2 hours
- Regular restore testing with evidence

## Third-Party Management
- Documented subprocessor register
- Data source inventory
- Regional classification

## Change Management
- Semantic versioning
- 90-day deprecation policy

---

## What We Don't Do

- We do not provide legal or compliance advice
- We do not certify underlying truth of third-party data
- Customers remain responsible for compliance decisions
- We provide infrastructure and delivery evidence — not compliance decisions

---

## Evidence Package

DORA Support Pack available for Enterprise customers.
Sanitized documentation, no internal infrastructure details.

[Request DORA Support Pack](mailto:enterprise@feedoracle.io?subject=DORA%20Support%20Pack%20Request)

---

## Security Contact

Vulnerability disclosure: security@feedoracle.io

---

## Disclaimer

FeedOracle provides DORA-supporting controls for ICT third-party risk assessments under DORA.

We do not claim regulatory compliance or certification. Customers remain responsible for their own compliance.

---

## On-Chain Provenance

Cryptographic proof of FeedOracle's existence and first-mover status.

### Genesis Proof

| | |
|---|---|
| **Chain** | Polygon Mainnet |
| **Transaction** | `0xcdfad8b21a5254c615f53c56fb073153135fe47950749bbaaae8baf2f797b713` |
| **Genesis Hash** | `201b37305ae82da4eeea978c48dae1fb41d03a097a617c9a66562c7cba0a0446` |
| **Date** | January 14, 2026 |

[View Genesis TX on Polygonscan →](https://polygonscan.com/tx/0xcdfad8b21a5254c615f53c56fb073153135fe47950749bbaaae8baf2f797b713)

---

## Smart Contract (Verified)

DAPAnchor - Disclosure Attestation Protocol for Merkle root anchoring.

| | |
|---|---|
| **Address** | `0xE1eAC4435716B1B8F358D280ab87FB04FEa7b93C` |
| **Status** | ✅ Source Code Verified |
| **Compiler** | Solidity 0.8.19 |
| **License** | MIT |

[View Verified Contract →](https://polygonscan.com/address/0xE1eAC4435716B1B8F358D280ab87FB04FEa7b93C#code)

**Functions:**
- `anchorMerkleRoot()` - Anchor data hash on-chain
- `verifyMerkleRoot()` - Verify hash exists
- `getAnchor()` - Get anchor details

---

## Public Release Timeline

| Date | Release |
|------|---------|
| Jan 14, 2026 | Genesis Proof anchored on Polygon |
| Jan 14, 2026 | Evidence Envelope Spec v1.0 |
| Jan 21, 2026 | OpenAPI 3.1 specification |
| Jan 28, 2026 | DAPAnchor contract verified |

---

## Source Code

| | |
|---|---|
| **GitHub** | [github.com/feedoracle/feedoracle-docs](https://github.com/feedoracle/feedoracle-docs) |
| **Version** | `v1.0.0` |
| **Status** | Public |

---

## How to Verify

1. Check [Genesis TX](https://polygonscan.com/tx/0xcdfad8b21a5254c615f53c56fb073153135fe47950749bbaaae8baf2f797b713) - decode input data
2. View [Verified Contract Source](https://polygonscan.com/address/0xE1eAC4435716B1B8F358D280ab87FB04FEa7b93C#code)
3. Clone repo: `git clone https://github.com/feedoracle/feedoracle-docs`
4. Check tag `v1.0.0` for timestamped proof

---

> *"You can't retroactively establish verifiable data history — unless it was preserved when it happened."*
