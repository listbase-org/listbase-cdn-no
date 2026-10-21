# Underholdning (Entertainment)

6 datasets — 442 records

> Browse at [listbase.org/no/entertainment/](https://listbase.org/no/entertainment/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Bookshops in Norway](no-bokhandler.json) | 236 | 24 KB | [CSV](no-bokhandler_NO.csv) | [Excel](no-bokhandler_NO.xlsx) | [View](https://listbase.org/no/entertainment/no-bokhandler/) |
| [Feeder for norske TV-kanaler](no-tv-kanaler-feeder.json) | 91 | 26 KB | [CSV](no-tv-kanaler-feeder_NO.csv) | [Excel](no-tv-kanaler-feeder_NO.xlsx) | [View](https://listbase.org/no/entertainment/no-tv-kanaler-feeder/) |
| [Norske TV-kanaler](no-tv-kanaler.json) | 70 | 27 KB | [CSV](no-tv-kanaler_NO.csv) | [Excel](no-tv-kanaler_NO.xlsx) | [View](https://listbase.org/no/entertainment/no-tv-kanaler/) |
| [Norske TV-kanaler — sport](no-tv-kanaler-sport.json) | 25 | 11 KB | [CSV](no-tv-kanaler-sport_NO.csv) | [Excel](no-tv-kanaler-sport_NO.xlsx) | [View](https://listbase.org/no/entertainment/no-tv-kanaler-sport/) |
| [Norske TV-kanaler — allmennkanaler](no-tv-kanaler-allmenn.json) | 13 | 7 KB | [CSV](no-tv-kanaler-allmenn_NO.csv) | [Excel](no-tv-kanaler-allmenn_NO.xlsx) | [View](https://listbase.org/no/entertainment/no-tv-kanaler-allmenn/) |
| [Norske TV-kanaler — religiøse kanaler](no-tv-kanaler-religion.json) | 7 | 5 KB | [CSV](no-tv-kanaler-religion_NO.csv) | [Excel](no-tv-kanaler-religion_NO.xlsx) | [View](https://listbase.org/no/entertainment/no-tv-kanaler-religion/) |

## Quick Start

```bash
# List all entertainment datasets
curl https://cdn.no.listbase.org/index.json | jq '.datasets[] | select(.category=="entertainment") | .id'

# Fetch a dataset
curl https://cdn.no.listbase.org/entertainment/no-bokhandler.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/no/entertainment/)
