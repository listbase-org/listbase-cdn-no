# Turisme (Tourism)

3 datasets — 3,327 records

> Browse at [listbase.org/no/tourism/](https://listbase.org/no/tourism/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Named museums in Norway](no-osm-tourism-museum.json) | 1,161 | 123 KB | [CSV](no-osm-tourism-museum_NO.csv) | [Excel](no-osm-tourism-museum_NO.xlsx) | [View](https://listbase.org/no/tourism/no-osm-tourism-museum/) |
| [Norway Viewpoints](no-utsiktspunkter.json) | 1,107 | 109 KB | [CSV](no-utsiktspunkter_NO.csv) | [Excel](no-utsiktspunkter_NO.xlsx) | [View](https://listbase.org/no/tourism/no-utsiktspunkter/) |
| [Hoteller i Norge](no-hoteller.json) | 1,059 | 112 KB | [CSV](no-hoteller_NO.csv) | [Excel](no-hoteller_NO.xlsx) | [View](https://listbase.org/no/tourism/no-hoteller/) |

## Quick Start

```bash
# List all tourism datasets
curl https://cdn.no.listbase.org/index.json | jq '.datasets[] | select(.category=="tourism") | .id'

# Fetch a dataset
curl https://cdn.no.listbase.org/tourism/no-osm-tourism-museum.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/no/tourism/)
