# ListBase CDN — Norsk (no)

Open dataset collection for **Norsk** (Norwegian).
413 datasets across 20 categories with 1,195,129 total records.

> Browse and download at [https://listbase.org/no/](https://listbase.org/no/)

## Categories

| Category | Datasets |
|----------|----------|
| [Kultur og religion (Culture & Religion)](culture/) | 25 |
| [Utdanning (Education)](education/) | 3 |
| [Underholdning (Entertainment)](entertainment/) | 6 |
| [Miljø (Environment)](environment/) | 24 |
| [Finans og handel (Finance & Trade)](finance/) | 11 |
| [Mat (Food & Nutrition)](food/) | 3 |
| [Geografi (Geography)](geography/) | 41 |
| [Helse (Health)](health/) | 2 |
| [Språk (Language)](language/) | 1 |
| [Musikk (Music)](music/) | 1 |
| [Politikk (Politics)](politics/) | 2 |
| [Referanse (Reference)](reference/) | 229 |
| [Vitenskap (Science)](science/) | 8 |
| [Samfunn (Society)](society/) | 2 |
| [Sport (Sports)](sports/) | 3 |
| [Teknologi (Technology)](tech/) | 1 |
| [Tid og kalender (Time & Calendar)](time/) | 2 |
| [Turisme (Tourism)](tourism/) | 3 |
| [Transport](transport/) | 25 |
| [Enheter og mål (Units & Measurements)](units/) | 21 |

## Usage

### Browse on the web
Visit [listbase.org/no/](https://listbase.org/no/) to search, preview, and download in Excel, CSV, or PDF.

### Fetch via CDN
```bash
# Dataset index (metadata only)
curl https://cdn.no.listbase.org/index.json

# Full dataset (JSON)
curl https://cdn.no.listbase.org/geography/th-central-provinces.json

# Download as Excel or CSV
curl -O https://cdn.no.listbase.org/geography/th-central-provinces_NO.xlsx
curl -O https://cdn.no.listbase.org/geography/th-central-provinces_NO.csv

# Build dump (metadata + sample rows, gzipped)
curl https://cdn.no.listbase.org/dump.json.gz | gunzip
```

### Use in JavaScript
```js
const res = await fetch('https://cdn.no.listbase.org/geography/th-central-provinces.json');
const data = await res.json();
console.log(data.name);    // "ภาคกลาง — จังหวัดในภาคกลาง"
console.log(data.rows);    // [{ ... }, ...]
```

## File Structure

```
├── index.json              # Dataset index (metadata + file info)
├── dump.json.gz            # Build dump (metadata + 20 sample rows per dataset)
├── {category}/
│   ├── README.md           # Category overview
│   ├── {dataset}.json      # Full dataset with rows
│   ├── {dataset}_NO.csv   # CSV download
│   └── {dataset}_NO.xlsx  # Excel download
```

## Dataset JSON Format

Each `.json` file contains:

| Field | Description |
|-------|-------------|
| `id` | Unique dataset identifier |
| `name` | Dataset name |
| `description` | What this dataset contains |
| `category` | Category (e.g. geography, finance) |
| `source` | Data source attribution |
| `updated` | Last updated date |
| `record_count` | Number of records |
| `columns` | Column definitions (key, label, type) |
| `rows` | Array of data records |

## License

Data is provided under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).
See individual dataset `source` fields for original data attribution.

---

Part of [ListBase](https://listbase.org) — Free Reference Tables & Lists
