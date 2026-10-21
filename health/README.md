# Helse (Health)

2 datasets — 1,177 records

> Browse at [listbase.org/no/health/](https://listbase.org/no/health/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Apotek i Norge](no-apotek.json) | 1,038 | 109 KB | [CSV](no-apotek_NO.csv) | [Excel](no-apotek_NO.xlsx) | [View](https://listbase.org/no/health/no-apotek/) |
| [Sykehus i Norge](no-sykehus.json) | 139 | 16 KB | [CSV](no-sykehus_NO.csv) | [Excel](no-sykehus_NO.xlsx) | [View](https://listbase.org/no/health/no-sykehus/) |

## Quick Start

```bash
# List all health datasets
curl https://cdn.no.listbase.org/index.json | jq '.datasets[] | select(.category=="health") | .id'

# Fetch a dataset
curl https://cdn.no.listbase.org/health/no-apotek.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/no/health/)
