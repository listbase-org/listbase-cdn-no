# Teknologi (Technology)

1 datasets — 1,081 records

> Browse at [listbase.org/no/tech/](https://listbase.org/no/tech/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Named ferry terminals in Norway](no-osm-amenity-ferry-terminal.json) | 1,081 | 110 KB | [CSV](no-osm-amenity-ferry-terminal_NO.csv) | [Excel](no-osm-amenity-ferry-terminal_NO.xlsx) | [View](https://listbase.org/no/tech/no-osm-amenity-ferry-terminal/) |

## Quick Start

```bash
# List all technology datasets
curl https://cdn.no.listbase.org/index.json | jq '.datasets[] | select(.category=="tech") | .id'

# Fetch a dataset
curl https://cdn.no.listbase.org/tech/no-osm-amenity-ferry-terminal.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/no/tech/)
