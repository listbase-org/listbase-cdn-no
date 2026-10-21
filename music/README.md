# Musikk (Music)

1 datasets — 451 records

> Browse at [listbase.org/no/music/](https://listbase.org/no/music/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Named rock formations in Norway](no-osm-natural-rock.json) | 451 | 47 KB | [CSV](no-osm-natural-rock_NO.csv) | [Excel](no-osm-natural-rock_NO.xlsx) | [View](https://listbase.org/no/music/no-osm-natural-rock/) |

## Quick Start

```bash
# List all music datasets
curl https://cdn.no.listbase.org/index.json | jq '.datasets[] | select(.category=="music") | .id'

# Fetch a dataset
curl https://cdn.no.listbase.org/music/no-osm-natural-rock.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/no/music/)
