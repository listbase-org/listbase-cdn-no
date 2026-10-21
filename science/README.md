# Vitenskap (Science)

8 datasets — 94,323 records

> Browse at [listbase.org/no/science/](https://listbase.org/no/science/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Norwegian Species Taxonomy (Artsdatabanken)](no-arter.json) | 73,299 | 29587 KB | [CSV](no-arter_NO.csv) | [Excel](no-arter_NO.xlsx) | [View](https://listbase.org/no/science/no-arter/) |
| [Norwegian Red List Species — Livskraftig (Least Concern)](no-arter-livskraftige.json) | 16,583 | 6931 KB | [CSV](no-arter-livskraftige_NO.csv) | [Excel](no-arter-livskraftige_NO.xlsx) | [View](https://listbase.org/no/science/no-arter-livskraftige/) |
| [Norwegian Red List Species — Nær truet (Near Threatened)](no-arter-naer-truede.json) | 1,248 | 531 KB | [CSV](no-arter-naer-truede_NO.csv) | [Excel](no-arter-naer-truede_NO.xlsx) | [View](https://listbase.org/no/science/no-arter-naer-truede/) |
| [Norwegian Red List Species — Sårbar (Vulnerable)](no-arter-sarbare.json) | 1,243 | 529 KB | [CSV](no-arter-sarbare_NO.csv) | [Excel](no-arter-sarbare_NO.xlsx) | [View](https://listbase.org/no/science/no-arter-sarbare/) |
| [Norwegian Red List Species — Sterkt truet (Endangered)](no-arter-sterkt-truede.json) | 882 | 377 KB | [CSV](no-arter-sterkt-truede_NO.csv) | [Excel](no-arter-sterkt-truede_NO.xlsx) | [View](https://listbase.org/no/science/no-arter-sterkt-truede/) |
| [Norwegian Red List Species — Datamangel (Data Deficient)](no-arter-datamangel.json) | 707 | 297 KB | [CSV](no-arter-datamangel_NO.csv) | [Excel](no-arter-datamangel_NO.xlsx) | [View](https://listbase.org/no/science/no-arter-datamangel/) |
| [Norwegian Red List Species — Kritisk truet (Critically Endangered)](no-arter-kritisk-truede.json) | 245 | 106 KB | [CSV](no-arter-kritisk-truede_NO.csv) | [Excel](no-arter-kritisk-truede_NO.xlsx) | [View](https://listbase.org/no/science/no-arter-kritisk-truede/) |
| [Norwegian Red List Species — Regionalt utdødd (Regionally Extinct)](no-arter-regionalt-utdodde.json) | 116 | 52 KB | [CSV](no-arter-regionalt-utdodde_NO.csv) | [Excel](no-arter-regionalt-utdodde_NO.xlsx) | [View](https://listbase.org/no/science/no-arter-regionalt-utdodde/) |

## Quick Start

```bash
# List all science datasets
curl https://cdn.no.listbase.org/index.json | jq '.datasets[] | select(.category=="science") | .id'

# Fetch a dataset
curl https://cdn.no.listbase.org/science/no-arter.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/no/science/)
