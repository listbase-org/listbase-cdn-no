# Samfunn (Society)

2 datasets — 304 records

> Browse at [listbase.org/no/society/](https://listbase.org/no/society/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Politistasjoner i Norge](no-politistasjoner.json) | 237 | 27 KB | [CSV](no-politistasjoner_NO.csv) | [Excel](no-politistasjoner_NO.xlsx) | [View](https://listbase.org/no/society/no-politistasjoner/) |
| [Charity shops in Norway](no-veldedighetsbutikker.json) | 67 | 8 KB | [CSV](no-veldedighetsbutikker_NO.csv) | [Excel](no-veldedighetsbutikker_NO.xlsx) | [View](https://listbase.org/no/society/no-veldedighetsbutikker/) |

## Quick Start

```bash
# List all society datasets
curl https://cdn.no.listbase.org/index.json | jq '.datasets[] | select(.category=="society") | .id'

# Fetch a dataset
curl https://cdn.no.listbase.org/society/no-politistasjoner.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/no/society/)
