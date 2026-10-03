# Canadian Procurement Data Tools

Open tools and datasets for analyzing Canadian public-sector procurement. Competition statistics, award analytics, and tender intelligence computed from compiled public contracting records.

## What's here

| Tool | Description | Data source |
|---|---|---|
| Competition Index | Average bidders and single-bid rates by category and province | Compiled tender records, 2021–2026 |
| Award Analytics | Federal contract distribution by vendor, department, province, and value band | Compiled award records, 2004–2026 |
| Bid Challenge Registry | Procurement complaint filings and outcomes, 1990–2026 | Public tribunal registry |
| Re-tender Forecast | Category renewal timing from contract durations and re-award cadence | Compiled contract history |

## Key findings

- **67.4% of Quebec public tenders receive exactly one bid** (405,956 tenders, 2021–2026)
- **87.2% of federal contracts go to companies outside the top 100 vendors** (1.3M awards, 2004–2026)
- **29.3% of federal awards are non-competitive** (871K labeled records)
- **Construction averages 3.1 bidders per tender; services average 1.8** — competition varies 2× by category

## Usage

Each tool directory contains a self-contained Python script that computes statistics from the compiled corpus. Outputs are JSON with stable URLs for citation.

## License

Data compiled from public sources under Open Government Licence – Canada and provincial open licences. Code is MIT.

## Statistics of record

For the authoritative versions of these statistics with methodology notes and release versioning, see the [Public Service Index](https://publicserviceindex.org).
