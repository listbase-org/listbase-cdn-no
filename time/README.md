# Tid og kalender (Time & Calendar)

2 datasets — 1,037 records

> Browse at [listbase.org/no/time/](https://listbase.org/no/time/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Norske helligdager – fullstendig flerspråklig (1947–2030)](no-helligdager-completos.json) | 1,000 | 507 KB | [CSV](no-helligdager-completos_NO.csv) | [Excel](no-helligdager-completos_NO.xlsx) | [View](https://listbase.org/no/time/no-helligdager-completos/) |
| [Helligdager og merkedager i Norge](no-helligdager.json) | 37 | 13 KB | [CSV](no-helligdager_NO.csv) | [Excel](no-helligdager_NO.xlsx) | [View](https://listbase.org/no/time/no-helligdager/) |

## Quick Start

```bash
# List all time & calendar datasets
curl https://cdn.no.listbase.org/index.json | jq '.datasets[] | select(.category=="time") | .id'

# Fetch a dataset
curl https://cdn.no.listbase.org/time/no-helligdager-completos.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/no/time/)
