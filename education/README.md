# Utdanning (Education)

3 datasets — 9,171 records

> Browse at [listbase.org/no/education/](https://listbase.org/no/education/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Barnehager i Norge](no-barnehager.json) | 5,616 | 4672 KB | [CSV](no-barnehager_NO.csv) | [Excel](no-barnehager_NO.xlsx) | [View](https://listbase.org/no/education/no-barnehager/) |
| [Skoler i Norge](no-skoler.json) | 3,531 | 373 KB | [CSV](no-skoler_NO.csv) | [Excel](no-skoler_NO.xlsx) | [View](https://listbase.org/no/education/no-skoler/) |
| [Norway — Universiteter & høgskoler (Universities)](no-universiteter.json) | 24 | 9 KB | [CSV](no-universiteter_NO.csv) | [Excel](no-universiteter_NO.xlsx) | [View](https://listbase.org/no/education/no-universiteter/) |

## Quick Start

```bash
# List all education datasets
curl https://cdn.no.listbase.org/index.json | jq '.datasets[] | select(.category=="education") | .id'

# Fetch a dataset
curl https://cdn.no.listbase.org/education/no-barnehager.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/no/education/)
