
# EV Fault Code Dataset

Public dataset entry point: https://evfaultcode.com/en/dataset/ev-fault-codes/

## Files

| File | Description |
| --- | --- |
| data/ev-fault-code-dataset.json | Dataset manifest with counts, URLs, citation, and metadata |
| data/obd-ii-codes.csv | Flat English OBD-II export for tools and spreadsheets |
| data/obd-ii-codes.json | Full OBD-II export with structured fields and translations |
| data/tesla-alerts.csv | Flat English Tesla alert export |
| data/tesla-alerts.json | Full Tesla alert export with systems and translations |

## Coverage

- Generic OBD-II diagnostic trouble codes
- EV-specific OBD-II codes
- Manufacturer-specific OBD-II ranges where available
- Tesla proprietary alert codes grouped by subsystem
- English CSV exports and multilingual JSON translation objects

## Methodology

See https://evfaultcode.com/en/methodology/ for source, validation, translation, review cadence, and limitation notes.
