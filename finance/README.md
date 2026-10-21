# Finans og handel (Finance & Trade)

11 datasets — 4,199 records

> Browse at [listbase.org/no/finance/](https://listbase.org/no/finance/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Kafeer i Norge](no-kafeer.json) | 2,231 | 225 KB | [CSV](no-kafeer_NO.csv) | [Excel](no-kafeer_NO.xlsx) | [View](https://listbase.org/no/finance/no-kafeer/) |
| [SWIFT/BIC-koder — Norge](no-swift-koder.json) | 731 | 104 KB | [CSV](no-swift-koder_NO.csv) | [Excel](no-swift-koder_NO.xlsx) | [View](https://listbase.org/no/finance/no-swift-koder/) |
| [Named trade/builders merchants in Norway](no-osm-shop-trade.json) | 646 | 70 KB | [CSV](no-osm-shop-trade_NO.csv) | [Excel](no-osm-shop-trade_NO.xlsx) | [View](https://listbase.org/no/finance/no-osm-shop-trade/) |
| [Banker i Oslo — SWIFT/BIC-koder](no-oslo-banker.json) | 544 | 89 KB | [CSV](no-oslo-banker_NO.csv) | [Excel](no-oslo-banker_NO.xlsx) | [View](https://listbase.org/no/finance/no-oslo-banker/) |
| [Banker i Bergen — SWIFT/BIC-koder](no-bergen-banker.json) | 15 | 4 KB | [CSV](no-bergen-banker_NO.csv) | [Excel](no-bergen-banker_NO.xlsx) | [View](https://listbase.org/no/finance/no-bergen-banker/) |
| [Banker i Stavanger — SWIFT/BIC-koder](no-stavanger-banker.json) | 10 | 3 KB | [CSV](no-stavanger-banker_NO.csv) | [Excel](no-stavanger-banker_NO.xlsx) | [View](https://listbase.org/no/finance/no-stavanger-banker/) |
| [Banker i Trondheim — SWIFT/BIC-koder](no-trondheim-banker.json) | 8 | 3 KB | [CSV](no-trondheim-banker_NO.csv) | [Excel](no-trondheim-banker_NO.xlsx) | [View](https://listbase.org/no/finance/no-trondheim-banker/) |
| [Banker i Kristiansand S — SWIFT/BIC-koder](no-kristiansand-s-banker.json) | 4 | 2 KB | [CSV](no-kristiansand-s-banker_NO.csv) | [Excel](no-kristiansand-s-banker_NO.xlsx) | [View](https://listbase.org/no/finance/no-kristiansand-s-banker/) |
| [Banker i Lysaker — SWIFT/BIC-koder](no-lysaker-banker.json) | 4 | 2 KB | [CSV](no-lysaker-banker_NO.csv) | [Excel](no-lysaker-banker_NO.xlsx) | [View](https://listbase.org/no/finance/no-lysaker-banker/) |
| [Banker i Bryne — SWIFT/BIC-koder](no-bryne-banker.json) | 3 | 2 KB | [CSV](no-bryne-banker_NO.csv) | [Excel](no-bryne-banker_NO.xlsx) | [View](https://listbase.org/no/finance/no-bryne-banker/) |
| [Banker i Tromsoe — SWIFT/BIC-koder](no-tromsoe-banker.json) | 3 | 2 KB | [CSV](no-tromsoe-banker_NO.csv) | [Excel](no-tromsoe-banker_NO.xlsx) | [View](https://listbase.org/no/finance/no-tromsoe-banker/) |

## Quick Start

```bash
# List all finance & trade datasets
curl https://cdn.no.listbase.org/index.json | jq '.datasets[] | select(.category=="finance") | .id'

# Fetch a dataset
curl https://cdn.no.listbase.org/finance/no-kafeer.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/no/finance/)
