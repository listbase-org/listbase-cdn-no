# Mat (Food & Nutrition)

3 datasets — 14,245 records

> Browse at [listbase.org/no/food/](https://listbase.org/no/food/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Vinmonopolet — komplett vinkatalog](no-vinmonopolet-viner.json) | 10,972 | 5481 KB | [CSV](no-vinmonopolet-viner_NO.csv) | [Excel](no-vinmonopolet-viner_NO.xlsx) | [View](https://listbase.org/no/food/no-vinmonopolet-viner/) |
| [Restauranter i Norge](no-restauranter.json) | 3,222 | 323 KB | [CSV](no-restauranter_NO.csv) | [Excel](no-restauranter_NO.xlsx) | [View](https://listbase.org/no/food/no-restauranter/) |
| [Michelin-restauranter i Norge](no-michelin-restauranter.json) | 51 | 57 KB | [CSV](no-michelin-restauranter_NO.csv) | [Excel](no-michelin-restauranter_NO.xlsx) | [View](https://listbase.org/no/food/no-michelin-restauranter/) |

## Quick Start

```bash
# List all food & nutrition datasets
curl https://cdn.no.listbase.org/index.json | jq '.datasets[] | select(.category=="food") | .id'

# Fetch a dataset
curl https://cdn.no.listbase.org/food/no-vinmonopolet-viner.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/no/food/)
