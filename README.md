# European Commission (InforEuro) Exchange Rates API — inforeuro-exchange-rate

[![npm version](https://img.shields.io/npm/v/inforeuro-exchange-rate.svg)](https://www.npmjs.com/package/inforeuro-exchange-rate)
[![license](https://img.shields.io/npm/l/inforeuro-exchange-rate.svg)](https://github.com/AllRates-Today/inforeuro-exchange-rate/blob/main/LICENSE)
[![zero dependencies](https://img.shields.io/badge/dependencies-0-brightgreen.svg)](https://www.npmjs.com/package/inforeuro-exchange-rate)
[![TypeScript](https://img.shields.io/badge/TypeScript-types%20included-3178C6.svg)](https://www.typescriptlang.org/)
[![EUR/USD today](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fallratestoday.com%2Fapi%2Fopen%2Fcentral-bank%2Finforeuro%3Fsource%3DEUR%26target%3DUSD&query=%24.rate&label=EUR%2FUSD%20official%2C%20European%20Commission%20(InforEuro)&color=0A7E8C&cacheSeconds=3600)](https://allratestoday.com/tax-authority-rates-api/inforeuro/)
[![rate date](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fallratestoday.com%2Fapi%2Fopen%2Fcentral-bank%2Finforeuro%3Fsource%3DEUR%26target%3DUSD&query=%24.rate_date&label=rate%20date&color=555&cacheSeconds=3600)](https://allratestoday.com/tax-authority-rates-api/inforeuro/)

**Official European Commission (InforEuro) (the European Union) monthly exchange rates for Node.js and TypeScript. The published tax authority rates behind tax filings, customs valuations, audits, and compliant invoicing — not market estimates, but the numbers European Commission (InforEuro) itself prints, every month.**

## 🚀 Why this client?

- 🏛️ **Official rates** — European Commission (InforEuro)'s own table, with the publisher's own `rate_date` on every response
- 📅 **History back to 1994** — point-in-time tables and daily series for any past date
- 🔀 **Official vs derived, always flagged** — computed inverse/cross pairs carry `derived: true`, never mixed with official prints
- ⚡ **Zero dependencies** — pure ESM + CJS over global `fetch`; Node 18+, Bun, Deno, and edge runtimes
- 🔷 **Type-safe** — full TypeScript definitions shipped with the package
- 🧾 **Compliance-grade metadata** — `rate_type`, publication date, and source disclaimer on every response

> **Official rate, not mid-market:** every value here is a number European Commission (InforEuro) itself published, fixed once printed and carrying the tax authority's own `rate_date` — what filings and audits require. Need the live mid-market rate for pricing or display instead? Use the [mid-market API](https://allratestoday.com/docs/) or [`@allratestoday/sdk`](https://www.npmjs.com/package/@allratestoday/sdk). The two can diverge by several percent.

## 🔑 Get your API key

Get a free API key at [allratestoday.com/register](https://allratestoday.com/register) — no credit card required. Latest rates are on every plan, including free.

## 📈 Latest official table

[![Latest European Commission (InforEuro) table](https://allratestoday.com/api/open/central-bank/inforeuro/table.svg)](https://allratestoday.com/tax-authority-rates-api/inforeuro/)

The image is rendered live from the keyless endpoint, so it follows the tax authority's publications on npm and on GitHub alike without a new release. The same table as text is folded below for search and copy-paste: on GitHub [a daily Action](.github/workflows/daily-table.yml) refreshes it whenever the tax authority publishes a new table; on npm it is as of the package's publish date.

<!-- daily-table:start -->
<details>
<summary>Table as text: published 2026-11-01 by European Commission (InforEuro) — 151 rates, first 60 shown. Updated 2026-11-25.</summary>

| Base | Quote | Type | Rate |
| --- | --- | --- | ---: |
| EUR | AED | monthly | 4.09675 |
| EUR | AFN | monthly | 72.535 |
| EUR | ALL | monthly | 90.85 |
| EUR | AMD | monthly | 398.7 |
| EUR | AOA | monthly | 1025.835 |
| EUR | ARS | monthly | 1715.96775 |
| EUR | AUD | monthly | 1.5842 |
| EUR | AWG | monthly | 2.01453 |
| EUR | AZN | monthly | 1.8921 |
| EUR | BAM | monthly | 1.95583 |
| EUR | BBD | monthly | 2.24169 |
| EUR | BDT | monthly | 138.2346 |
| EUR | BHD | monthly | 0.41999 |
| EUR | BIF | monthly | 3346.872 |
| EUR | BMD | monthly | 1.113 |
| EUR | BND | monthly | 1.4292 |
| EUR | BOB | monthly | 13.35044 |
| EUR | BRL | monthly | 5.9563 |
| EUR | BSD | monthly | 1.113 |
| EUR | BTN | monthly | 106.0345 |
| EUR | BWP | monthly | 15.37409 |
| EUR | BYN | monthly | 3.28295 |
| EUR | BZD | monthly | 2.23847 |
| EUR | CAD | monthly | 1.5577 |
| EUR | CDF | monthly | 2581.595 |
| EUR | CHF | monthly | 0.9222 |
| EUR | CLP | monthly | 1099.46036 |
| EUR | CNY | monthly | 7.4144 |
| EUR | COP | monthly | 3518.71611 |
| EUR | CRC | monthly | 506.12006 |
| EUR | CUP | monthly | 26.7696 |
| EUR | CVE | monthly | 110.265 |
| EUR | CZK | monthly | 24.336 |
| EUR | DJF | monthly | 198.19748 |
| EUR | DKK | monthly | 7.4736 |
| EUR | DOP | monthly | 67.281 |
| EUR | DZD | monthly | 150.8035 |
| EUR | EGP | monthly | 62.48472 |
| EUR | ERN | monthly | 16.77848 |
| EUR | ETB | monthly | 180.133 |
| EUR | FJD | monthly | 2.49895 |
| EUR | FKP | monthly | 0.83578 |
| EUR | GBP | monthly | 0.83578 |
| EUR | GEL | monthly | 2.8908 |
| EUR | GHS | monthly | 12.98325 |
| EUR | GIP | monthly | 0.83578 |
| EUR | GMD | monthly | 83.265 |
| EUR | GNF | monthly | 9872.415 |
| EUR | GTQ | monthly | 8.50889 |
| EUR | GYD | monthly | 233.8 |
| EUR | HKD | monthly | 8.733 |
| EUR | HNL | monthly | 29.87993 |
| EUR | HTG | monthly | 145.9143 |
| EUR | HUF | monthly | 365.95 |
| EUR | IDR | monthly | 20193.16 |
| EUR | ILS | monthly | 3.468 |
| EUR | INR | monthly | 106.0345 |
| EUR | IQD | monthly | 1458.03 |
| EUR | IRR | monthly | 2075355.45 |
| EUR | ISK | monthly | 135.8 |

</details>

[Full table on the European Commission (InforEuro) rates page](https://allratestoday.com/tax-authority-rates-api/inforeuro/) · Source: [Official rates published by INFOREURO, served by AllRatesToday](https://allratestoday.com/tax-authority-rates-api/inforeuro/). Rates are as printed by the tax authority; AllRatesToday is not affiliated with it.
<!-- daily-table:end -->

## 📦 Installation

```bash
npm install inforeuro-exchange-rate
```

```bash
yarn add inforeuro-exchange-rate
```

```bash
pnpm add inforeuro-exchange-rate
```

Requires Node 18+ (global `fetch`); also runs on Bun, Deno and edge runtimes. Also published under the org scope as [`@allratestoday/inforeuro-exchange-rate`](https://www.npmjs.com/package/@allratestoday/inforeuro-exchange-rate) — same code, same versions.

## 🏁 Quick start

```js
import { getRate } from 'inforeuro-exchange-rate';

const pair = await getRate('USD', 'EUR', { apiKey: 'art_live_...' });
console.log(pair.rate, pair.rate_date); // the official European Commission (InforEuro) rate, on the tax authority's own date
```

## 📚 API reference

- [Latest pair rate](#latest-pair-rate) — one pair from the latest official table
- [Full official table](#full-official-table) — everything the tax authority printed, in one call
- [Table for a date](#table-for-a-date) — the official table for an invoice or filing date
- [Daily time series](#daily-time-series) — one pair across a date range

---

### Latest pair rate

Free plan and up. Pairs the tax authority does not print directly are resolved from its table and flagged (see *Official vs derived rates* below).

```js
const pair = await getRate('USD', 'EUR', { apiKey: 'art_live_...' });
```

**Response:**

```javascript
{
  bank: 'inforeuro',
  name: 'European Commission (InforEuro)',
  rate_date: '2026-11-01',   // European Commission (InforEuro)'s own publication date
  source: 'USD',
  target: 'EUR',
  rate: 0.898473,
  rate_type: 'monthly',
  derived: true,
  method: 'inverse',  // computed from the published EUR/USD print
  disclaimer: 'Official rates as published by the named central bank. On weekends/holidays the most recent published rate_date is returned.'
}
```

### Full official table

Free plan and up. The complete table for the latest publication date.

```js
import { getLatestRates } from 'inforeuro-exchange-rate';

const table = await getLatestRates({ apiKey: 'art_live_...' });
console.log(table.rate_date, table.rates.length);
```

**Response:**

```javascript
{
  bank: 'inforeuro',
  name: 'European Commission (InforEuro)',
  rate_date: '2026-11-01',
  rates: [
    { "base": "EUR", "quote": "USD", "type": "monthly", "value": 1.113 },
    // … the rest of the official table (152 currencies vs EUR)
  ],
  disclaimer: '…'
}
```

### Table for a date

Paid plans. The official table for any date since 1994 — weekends and holidays return the most recent published date, flagged via `published_on_requested_date`, which is exactly the in-force rate a filing needs.

```js
import { getRatesForDate } from 'inforeuro-exchange-rate';

const day = await getRatesForDate('2026-06-30', { apiKey: 'art_live_...' });
// Optionally narrow to one pair:
const one = await getRatesForDate('2026-06-30', { apiKey: 'art_live_...', source: 'USD', target: 'EUR' });
```

**Response:**

```javascript
{
  bank: 'inforeuro',
  requested_date: '2026-06-30',
  rate_date: '2026-06-30',                // the date actually published
  published_on_requested_date: true,      // false when a weekend/holiday fell back
  rates: [ /* the full table for that date */ ],
  disclaimer: '…'
}
```

### Daily time series

Paid plans. One resolved rate per publication date — ready for charting, revaluation runs, or audit workpapers.

```js
import { getHistory } from 'inforeuro-exchange-rate';

const series = await getHistory(
  { source: 'USD', target: 'EUR', from: '2026-01-01', to: '2026-11-01' },
  { apiKey: 'art_live_...' }
);
```

**Response:**

```javascript
{
  bank: 'inforeuro',
  source: 'USD',
  target: 'EUR',
  from: '2026-01-01',
  to: '2026-11-01',
  count: 152,
  rates: [
    // one entry per publication date
    { date: '2026-11-01', rate: 0.898473, rate_type: 'monthly', derived: true, method: 'inverse' },
    // …
  ],
  disclaimer: '…'
}
```

Pass `{ symbol: 'USD' }` instead of `source`/`target` to get the raw published rows for one currency (all rate types, no pair resolution).

---

## 🗺️ Currencies covered

European Commission (InforEuro) currently publishes rates covering **152 currencies** against the EUR (as of the latest table):

🇦🇪 `AED` · 🇦🇫 `AFN` · 🇦🇱 `ALL` · 🇦🇲 `AMD` · 🇦🇴 `AOA` · 🇦🇷 `ARS` · 🇦🇺 `AUD` · 🇦🇼 `AWG` · 🇦🇿 `AZN` · 🇧🇦 `BAM` · 🇧🇧 `BBD` · 🇧🇩 `BDT` · 🇧🇬 `BGN` · 🇧🇭 `BHD` · 🇧🇮 `BIF` · 🇧🇲 `BMD` · 🇧🇳 `BND` · 🇧🇴 `BOB` · 🇧🇷 `BRL` · 🇧🇸 `BSD` · 🇧🇹 `BTN` · 🇧🇼 `BWP` · 🇧🇾 `BYN` · 🇧🇿 `BZD` · 🇨🇦 `CAD` · 🇨🇩 `CDF` · 🇨🇭 `CHF` · 🇨🇱 `CLP` · 🇨🇳 `CNY` · 🇨🇴 `COP` · 🇨🇷 `CRC` · 🇨🇺 `CUP` · 🇨🇻 `CVE` · 🇨🇿 `CZK` · 🇩🇯 `DJF` · 🇩🇰 `DKK` · 🇩🇴 `DOP` · 🇩🇿 `DZD` · 🇪🇬 `EGP` · 🇪🇷 `ERN` · 🇪🇹 `ETB` · 🇫🇯 `FJD` · 🇫🇰 `FKP` · 🇬🇧 `GBP` · 🇬🇪 `GEL` · 🇬🇭 `GHS` · 🇬🇮 `GIP` · 🇬🇲 `GMD` · 🇬🇳 `GNF` · 🇬🇹 `GTQ` · 🇬🇾 `GYD` · 🇭🇰 `HKD` · 🇭🇳 `HNL` · 🇭🇹 `HTG` · 🇭🇺 `HUF` · 🇮🇩 `IDR` · 🇮🇱 `ILS` · 🇮🇳 `INR` · 🇮🇶 `IQD` · 🇮🇷 `IRR` · 🇮🇸 `ISK` · 🇯🇲 `JMD` · 🇯🇴 `JOD` · 🇯🇵 `JPY` · 🇰🇪 `KES` · 🇰🇬 `KGS` · 🇰🇭 `KHR` · 🇰🇲 `KMF` · 🇰🇷 `KRW` · 🇰🇼 `KWD` · 🇰🇾 `KYD` · 🇰🇿 `KZT` · 🇱🇦 `LAK` · 🇱🇧 `LBP` · 🇱🇰 `LKR` · 🇱🇷 `LRD` · 🇱🇸 `LSL` · 🇱🇾 `LYD` · 🇲🇦 `MAD` · 🇲🇩 `MDL` · 🇲🇬 `MGA` · 🇲🇰 `MKD` · 🇲🇲 `MMK` · 🇲🇳 `MNT` · 🇲🇴 `MOP` · 🇲🇷 `MRU` · 🇲🇺 `MUR` · 🇲🇻 `MVR` · 🇲🇼 `MWK` · 🇲🇽 `MXN` · 🇲🇾 `MYR` · 🇲🇿 `MZN` · 🇳🇦 `NAD` · 🇳🇬 `NGN` · 🇳🇮 `NIO` · 🇳🇴 `NOK` · 🇳🇵 `NPR` · 🇳🇿 `NZD` · 🇴🇲 `OMR` · 🇵🇦 `PAB` · 🇵🇪 `PEN` · 🇵🇬 `PGK` · 🇵🇭 `PHP` · 🇵🇰 `PKR` · 🇵🇱 `PLN` · 🇵🇾 `PYG` · 🇶🇦 `QAR` · 🇷🇴 `RON` · 🇷🇸 `RSD` · 🇷🇺 `RUB` · 🇷🇼 `RWF` · 🇸🇦 `SAR` · 🇸🇧 `SBD` · 🇸🇨 `SCR` · 🇸🇩 `SDG` · 🇸🇪 `SEK` · 🇸🇬 `SGD` · 🇸🇭 `SHP` · 🇸🇱 `SLE` · 🇸🇴 `SOS` · 🇸🇷 `SRD` · 🇸🇸 `SSP` · 🇸🇹 `STN` · 🇸🇾 `SYP` · 🇸🇿 `SZL` · 🇹🇭 `THB` · 🇹🇯 `TJS` · 🇹🇲 `TMT` · 🇹🇳 `TND` · 🇹🇴 `TOP` · 🇹🇷 `TRY` · 🇹🇹 `TTD` · 🇹🇼 `TWD` · 🇹🇿 `TZS` · 🇺🇦 `UAH` · 🇺🇬 `UGX` · 🇺🇸 `USD` · 🇺🇾 `UYU` · 🇺🇿 `UZS` · 🇻🇪 `VES` · 🇻🇳 `VND` · 🇻🇺 `VUV` · 🇼🇸 `WST` · `XAF` · `XCD` · `XCG` · `XOF` · `XPF` · 🇾🇪 `YER` · 🇿🇦 `ZAR` · 🇿🇮 `ZIG` · 🇿🇲 `ZMW`

## 🏛️ Source

The European Commission's official monthly accounting rate of the euro, set by DG Budget and distributed through InforEuro. It is used to convert amounts for the EU budget, grants, procurement contracts and staff payments. Each rate is fixed for the whole calendar month and is stated as units of foreign currency per 1 euro.

- Publisher's own page: [Monthly exchange rates for customs and tax](https://commission.europa.eu/funding-tenders/procedures-guidelines-tenders/information-contractors-and-beneficiaries/exchange-rate-inforeuro_en) · [commission.europa.eu](https://commission.europa.eu/)
- Publication: every month; the exact schedule, freshness status and any current delay are on the [European Commission (InforEuro) rates page](https://allratestoday.com/tax-authority-rates-api/inforeuro/)
- Values are stored unmodified, with the publisher's own `rate_date` on every row — see the [methodology](https://allratestoday.com/official-rates-methodology/)

## 🧭 Reading the numbers

- `value` is always **quote currency per 1 unit of base currency** (`base: "EUR", quote: "USD", value: 1.15` means 1 EUR = 1.15 USD).
- European Commission (InforEuro) quotes **foreign currency per 1 EUR** (e.g. `base: "EUR", quote: "USD"` means USD per one EUR).
- Need the other way round? Ask `getRate(target, source)` and the API inverts or crosses for you, flagged `derived: true` — never divide a published rate yourself in a compliance workflow.
- `rate_type` tells you which of the tax authority's series a row belongs to (`monthly` here); some publishers print buy/sell or several fixings for the same pair.

## 🧩 ERP & accounting systems

Loading the official European Commission (InforEuro) rate into an accounting system is a supported workflow, not a hack. Step-by-step guides with the direction each system expects:

- [Dynamics 365 Business Central](https://allratestoday.com/docs/integrations/business-central/) — built-in Currency Exchange Rate Service, no code
- [Xero](https://allratestoday.com/docs/integrations/xero/) · [QuickBooks Online](https://allratestoday.com/docs/integrations/quickbooks/) · [SAP S/4HANA and ECC](https://allratestoday.com/docs/integrations/sap/) · [Odoo](https://allratestoday.com/docs/integrations/odoo/)

The same keyed endpoints return `?format=csv`, `?format=xml` and `?format=xlsx`, and accept the key as `?api_key=` on the URL for importers that cannot send headers:

```bash
curl "https://allratestoday.com/api/v1/central-bank/inforeuro/latest?format=xml&api_key=art_live_..."
```

## 🤖 AI agents

- MCP server: `npx -y @allratestoday/central-bank-mcp` (stdio) or the hosted endpoint `https://allratestoday.com/api/mcp` — tools for official rates, history, cross-bank comparison and publication calendars
- Already using the general SDK or MCP server? Since 2026-10-01 [`@allratestoday/sdk`](https://www.npmjs.com/package/@allratestoday/sdk) 1.4+ has `officialRates('inforeuro')` and [`@allratestoday/mcp-server`](https://www.npmjs.com/package/@allratestoday/mcp-server) 0.6+ has a `get_official_rates` tool — both return this source's latest table with no key, so you can add it without a second dependency
- Claude Code plugin (no key): `/plugin marketplace add AllRates-Today/claude-code-plugin` then `/plugin install allratestoday@allratestoday` — bundles both MCP servers plus an `/official-rate inforeuro ...` command
- Evaluating? Agents can self-issue a trial key with no signup: `POST https://allratestoday.com/api/agent/keys` (send `Content-Type: application/json`) returns a 100-call key valid 7 days that covers the free-plan methods (latest table, pairs); dated tables and history need a [paid plan](https://allratestoday.com/pricing/). The MCP servers expose it as `request_trial_key`
- Machine-readable site guide: [llms.txt](https://allratestoday.com/llms.txt) · [for-ai-agents](https://allratestoday.com/for-ai-agents/)

## ⚖️ Official vs derived rates

If European Commission (InforEuro) does not print a pair directly, the API resolves it from the tax authority's own table and says so — official and computed values are never confused:

| `method` | `derived` | Meaning |
| --- | --- | --- |
| `published` | `false` | The tax authority printed this pair directly |
| `inverse` | `true` | Computed as 1 ÷ the published opposite direction |
| `cross` | `true` | Computed via EUR from two published rates |

## 🛡️ Error handling

Errors are thrown as `Error` with `status` (HTTP code) and `body` (the API's JSON error) attached:

```js
try {
  const pair = await getRate('USD', 'XXX', { apiKey: 'art_live_...' });
} catch (err) {
  console.log(err.message); // human-readable reason
  console.log(err.status);  // e.g. 404
}
```

| Status | Meaning |
| ------ | ------- |
| — | Missing `apiKey` (thrown before any request) |
| `400` | Malformed date or parameters |
| `401` | Invalid API key |
| `403` | Endpoint needs a [paid plan](https://allratestoday.com/pricing/) (historical dates & series) |
| `404` | Pair or date range not covered by European Commission (InforEuro) |
| `429` | Monthly quota exceeded |

## 🔷 TypeScript

Full definitions ship with the package — no `@types` install:

```ts
import type { LatestRates, PairRate, DatedRates, RateEntry, HistoryQuery, RequestOptions } from 'inforeuro-exchange-rate';
```

## 📦 CommonJS

```javascript
const { getRate } = require('inforeuro-exchange-rate');

getRate('USD', 'EUR', { apiKey: 'art_live_...' }).then((pair) => console.log(pair.rate));
```

## 💡 Quota tips

- Rates change once a month — cache the official table locally and a small monthly quota goes a long way.
- Every request counts toward your AllRatesToday quota, shared across all AllRatesToday endpoints on your key.

## 📖 Methods reference

| Method | Plan | Description |
| ------ | ---- | ----------- |
| `getRate(source, target, { apiKey })` | Free | Latest rate for one pair, resolved from the official table |
| `getLatestRates({ apiKey })` | Free | The tax authority's full latest official table |
| `getRatesForDate(date, { apiKey, source?, target? })` | Paid | The official table (or one pair) for a YYYY-MM-DD date |
| `getHistory({ symbol \| source+target, from?, to? }, { apiKey })` | Paid | Daily series since 1994 |

## 📥 Bulk data (no key)

Need the whole archive rather than an API call? The same official tables are mirrored daily as open data:

- Hugging Face: [AllRatesToday/central-bank-exchange-rates](https://huggingface.co/datasets/AllRatesToday/central-bank-exchange-rates) — one CSV per institution (`rates/inforeuro.csv`)
- Kaggle: [allratestoday/central-bank-exchange-rates](https://www.kaggle.com/datasets/allratestoday/central-bank-exchange-rates)
- Raw JSON on GitHub: `https://raw.githubusercontent.com/AllRates-Today/central-bank-exchange-rates/main/data/inforeuro/latest.json`

## 🔗 Links

- **Website:** [allratestoday.com](https://allratestoday.com)
- [European Commission (InforEuro) rates page](https://allratestoday.com/tax-authority-rates-api/inforeuro/) — live table, publication cadence, FAQ
- [All tax authority sources](https://allratestoday.com/tax-authority-rates-api/) · [Full list of 120+ central banks and 50+ tax authorities](https://allratestoday.com/central-bank-rates-api/institutions/) — one API, the same response shape for every source
- [Download central bank rates](https://allratestoday.com/download-central-bank-rates/) — every bank's latest table and history as Excel, CSV or JSON
- [Bank Exchange Rate API](https://allratestoday.com/bank-exchange-rate-api/) — live buy and sell rates from 1,200+ commercial banks in 120+ countries · [npm](https://www.npmjs.com/package/bank-exchange-rates) · [GitHub](https://github.com/AllRates-Today/bank-exchange-rates)
- [Package docs on the site](https://allratestoday.com/docs/sdk/inforeuro-exchange-rate/) · [ERP integration guides](https://allratestoday.com/docs/integrations/)
- [API documentation](https://allratestoday.com/docs/#central-bank) · [Interactive reference](https://allratestoday.com/api-reference/) · [Methodology](https://allratestoday.com/official-rates-methodology/)
- [Register (Free)](https://allratestoday.com/register) · [Dashboard](https://allratestoday.com/profile) · [Pricing](https://allratestoday.com/pricing/)
- [Status](https://allratestoday.com/status)
- [Postman collection](https://allratestoday.com/postman/)
- [ChatGPT app](https://chatgpt.com/plugins/plugin_asdk_app_6ae1e76098f48191a285ac3f5ab7a83b) — ask ChatGPT for live and official central bank rates
- [OpenAPI reference on Bump.sh](https://bump.sh/allratestoday/doc/allratestoday-api) — also on [SwaggerHub](https://app.swaggerhub.com/apis-docs/allratestoday/allratestoday-exchange-rate-central-bank-rates-api/2.2.0)
- [GitHub](https://github.com/AllRates-Today/inforeuro-exchange-rate)

## 📜 License

MIT
