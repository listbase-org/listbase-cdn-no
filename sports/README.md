# Sport (Sports)

3 datasets — 2,534 records

> Browse at [listbase.org/no/sports/](https://listbase.org/no/sports/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [UEFA Mesterligaen — alle kamper i hovedturneringen 2011/12–2025/26 (1997)](no-uefa-mesterligaen-kamper.json) | 1,997 | 1136 KB | [CSV](no-uefa-mesterligaen-kamper_NO.csv) | [Excel](no-uefa-mesterligaen-kamper_NO.xlsx) | [View](https://listbase.org/no/sports/no-uefa-mesterligaen-kamper/) |
| [Sports shops in Norway](no-sportsbutikker.json) | 401 | 41 KB | [CSV](no-sportsbutikker_NO.csv) | [Excel](no-sportsbutikker_NO.xlsx) | [View](https://listbase.org/no/sports/no-sportsbutikker/) |
| [Norske klubber i UEFAs europacuper — kamper 2020/21–2025/26 (136)](no-norske-klubber-i-europacupene-kamper.json) | 136 | 82 KB | [CSV](no-norske-klubber-i-europacupene-kamper_NO.csv) | [Excel](no-norske-klubber-i-europacupene-kamper_NO.xlsx) | [View](https://listbase.org/no/sports/no-norske-klubber-i-europacupene-kamper/) |

## Quick Start

```bash
# List all sports datasets
curl https://cdn.no.listbase.org/index.json | jq '.datasets[] | select(.category=="sports") | .id'

# Fetch a dataset
curl https://cdn.no.listbase.org/sports/no-uefa-mesterligaen-kamper.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/no/sports/)
