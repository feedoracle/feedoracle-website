---
title: Documentation
description: FeedOracle API Documentation
---

# Documentation

## Quick Start
```bash
curl https://api.feedoracle.io/v1/rwa/health \
  -H "X-API-Key: your_key"
```

---

## Success Response
```json
{
  "meta": {
    "feed_name": "rwa_health",
    "feed_version": "3.0.0",
    "schema_version": "1.0.0",
    "as_of": "2026-01-15T12:00:00Z",
    "data_sources": ["ankr_rpc", "defillama"],
    "units": {"tvl_usd": "USD", "health_score": "0-100"},
    "request_id": "550e8400-e29b-41d4-a716-446655440000"
  },
  "summary": {"total": 20, "healthy": 14},
  "assets": [...]
}
```

---

## Error Response
```json
{
  "error": {
    "code": "NOT_FOUND",
    "message": "Resource not found"
  },
  "meta": {
    "feed_name": "energy_country",
    "feed_version": "3.0.0",
    "schema_version": "1.0.0",
    "as_of": "2026-01-15T12:00:00Z",
    "data_sources": ["ourworldindata.org"],
    "units": {"electricity": "TWh", "share": "percent"},
    "request_id": "550e8400-e29b-41d4-a716-446655440001"
  }
}
```

---

## Global Response Standard

Every response includes:
- `meta.feed_name` — Feed identifier
- `meta.feed_version` — API version
- `meta.schema_version` — Schema version
- `meta.as_of` — ISO8601 UTC timestamp
- `meta.data_sources` — Data provenance array
- `meta.units` — Unit documentation
- `meta.request_id` — Correlation ID

---

## DAP Protocol

Delivery receipts for data feeds:
- Anchors snapshot receipts on Polygon Mainnet
- Proves WHAT was reported WHEN
- Does not verify underlying accuracy
- Immutable receipt for audit trails

---

## Memory Layer

Historical data verification:
- Query past snapshots by date
- Verify historical data states
- Generate audit trails
- Cryptographic receipt of past deliveries
