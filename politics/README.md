# Politikk (Politics)

2 datasets — 833 records

> Browse at [listbase.org/no/politics/](https://listbase.org/no/politics/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Named government offices in Norway](no-osm-office-government.json) | 556 | 59 KB | [CSV](no-osm-office-government_NO.csv) | [Excel](no-osm-office-government_NO.xlsx) | [View](https://listbase.org/no/politics/no-osm-office-government/) |
| [Named surveillance installations in Norway](no-osm-man-made-surveillance.json) | 277 | 30 KB | [CSV](no-osm-man-made-surveillance_NO.csv) | [Excel](no-osm-man-made-surveillance_NO.xlsx) | [View](https://listbase.org/no/politics/no-osm-man-made-surveillance/) |

## Quick Start

```bash
# List all politics datasets
curl https://cdn.no.listbase.org/index.json | jq '.datasets[] | select(.category=="politics") | .id'

# Fetch a dataset
curl https://cdn.no.listbase.org/politics/no-osm-office-government.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/no/politics/)
