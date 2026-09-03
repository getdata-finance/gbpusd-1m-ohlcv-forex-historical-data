# GBPUSD 1m OHLCV Forex Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-9_194_075_rows-blue)](https://getdata.finance/datasets/gbpusd) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/gbpusd)

### -> [**Download the full GBPUSD dataset on getdata.finance**](https://getdata.finance/datasets/gbpusd)

**GBPUSD 1m OHLCV forex historical data** — ultra high-quality 1m OHLCV for **British Pound / US Dollar**. Clean `datetime, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

## Table of contents

- [Why this dataset?](#why-this-dataset)
- [Download sample CSV](#download-sample)
- [GitHub Pages preview](#github-pages)
- [Sample vs full dataset](#sample-vs-full-dataset)
- [Timeframes on GetData](#timeframes-on-getdata)
- [Weekly updates](#weekly-updates)
- [Data preview](#data-preview)
- [Schema](#schema)
- [Code examples](#code-examples)
- [Download full data on getdata.finance](#download-full-data-on-getdata)

## Why this dataset?

- **Ultra high-quality 1m OHLCV** for **British Pound / US Dollar** (Forex)
- **Clean CSV schema** — `datetime, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`1m`) · **11 timeframes** on [getdata.finance](https://getdata.finance/datasets/gbpusd) · **9,194,075** `1m` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `1m` sample updated in sync

> **Sample on GitHub** · `GBPUSD_1m.csv` (55,440 rows, `2026-07-09` -> `2026-09-02`, 5.18 MB). **Full archive on [getdata.finance](https://getdata.finance/datasets/gbpusd)** — **9,194,075** `1m` rows (full `1m`: 9,194,075), **11 timeframes**, `2001-11-28` -> `2026-09-02`.

## Download sample

**[GBPUSD_1m.csv](https://github.com/getdata-finance/gbpusd-1m-ohlcv-forex-historical-data/blob/main/GBPUSD_1m.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/getdata-finance/gbpusd-1m-ohlcv-forex-historical-data/main/GBPUSD_1m.csv)) · [GitHub Releases](https://github.com/getdata-finance/gbpusd-1m-ohlcv-forex-historical-data/releases)

## GitHub Pages

Interactive chart & stats: **[https://getdata-finance.github.io/gbpusd-1m-ohlcv-forex-historical-data/](https://getdata-finance.github.io/gbpusd-1m-ohlcv-forex-historical-data/)**

Full archive & live chart on getdata.finance: **[https://getdata.finance/datasets/gbpusd](https://getdata.finance/datasets/gbpusd)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([getdata.finance](https://getdata.finance/datasets/gbpusd))** |
|---|--:|---|
| Instrument | British Pound / US Dollar · Forex | British Pound / US Dollar · Forex |
| Timeframes | `1m` (sample) | **11** — 1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W |
| 1m rows | 55,440 | **9,194,075** |
| Size | 5.18 MB | full ZIP on [getdata.finance](https://getdata.finance/datasets/gbpusd) |
| Period | `2026-07-09` -> `2026-09-02` | `2001-11-28` -> `2026-09-02` |
| File | `GBPUSD_1m.csv` | ZIP on [getdata.finance](https://getdata.finance/datasets/gbpusd) |
| Coverage report | — | [GBPUSD coverage](https://getdata.finance/coverage/gbpusd) |
| Updates | Weekly (Saturday, 8am UTC+0) — GitHub sample | Weekly (Saturday, 8am UTC+0) — all timeframes |

## Timeframes on GetData

This GitHub repository ships a **`1m` evaluation sample** only. On **[getdata.finance](https://getdata.finance/datasets/gbpusd)**, each full asset archive is delivered as a ZIP with **11 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W**

GitHub = `1m` sample · [getdata.finance](https://getdata.finance/datasets/gbpusd) = all **11** timeframes above for the same instrument.

## Weekly updates

- **[getdata.finance](https://getdata.finance)** — Full datasets are updated every Saturday, 8am UTC+0.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Saturday, 8am UTC+0), in sync with getdata.finance.

When a new `1m` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`GBPUSD_1m.csv`**:

**First rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-07-09T13:41:00+00:00 | 1.34264 | 1.34268 | 1.34245 | 1.34266 | 269 |
| 2026-07-09T13:42:00+00:00 | 1.34266 | 1.34309 | 1.34266 | 1.34309 | 261 |
| 2026-07-09T13:43:00+00:00 | 1.34309 | 1.34309 | 1.34265 | 1.34266 | 400 |
| 2026-07-09T13:44:00+00:00 | 1.34266 | 1.34269 | 1.3424 | 1.34266 | 309 |
| 2026-07-09T13:45:00+00:00 | 1.34266 | 1.34277 | 1.34265 | 1.34267 | 256 |

**Last rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-09-02T01:56:00+00:00 | 1.35036 | 1.35036 | 1.35027 | 1.35028 | 106 |
| 2026-09-02T01:57:00+00:00 | 1.35028 | 1.35039 | 1.35027 | 1.35037 | 79 |
| 2026-09-02T01:58:00+00:00 | 1.35037 | 1.35038 | 1.35031 | 1.35038 | 82 |
| 2026-09-02T01:59:00+00:00 | 1.35038 | 1.35053 | 1.35036 | 1.3505 | 134 |
| 2026-09-02T02:00:00+00:00 | 1.3505 | 1.35051 | 1.35026 | 1.35026 | 132 |

## Schema

| Column | Description |
| --- | --- |
| `datetime` | Bar open timestamp (UTC, ISO-8601). |
| `open` | Opening price of the candlestick bar. |
| `high` | Highest price during the bar. |
| `low` | Lowest price during the bar. |
| `close` | Closing price of the candlestick bar. |
| `volume` | Tick volume (number of price updates) during the bar. |

```text
datetime,open,high,low,close,volume
```

## Code examples

### pandas

```python
import pandas as pd

df = pd.read_csv('GBPUSD_1m.csv', parse_dates=['datetime'])
df.set_index('datetime', inplace=True)
print(df.describe())
```

### backtrader

```python
import backtrader as bt
import pandas as pd

df = pd.read_csv('GBPUSD_1m.csv', parse_dates=['datetime'])
df.set_index('datetime', inplace=True)

class PandasData(bt.feeds.PandasData):
    params = (('datetime', None), ('open', 'open'), ('high', 'high'),
              ('low', 'low'), ('close', 'close'), ('volume', 'volume'))

cerebro = bt.Cerebro()
cerebro.adddata(PandasData(dataname=df))
# cerebro.addstrategy(YourStrategy)
# cerebro.run()
```

### vectorbt

```python
import pandas as pd
import vectorbt as vbt

df = pd.read_csv('GBPUSD_1m.csv', parse_dates=['datetime'])
close = df.set_index('datetime')['close']
fast, slow = vbt.MA.run(close, 10), vbt.MA.run(close, 50)
entries = fast.ma_crossed_above(slow)
exits = fast.ma_crossed_below(slow)
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='1min')
print(pf.stats())
```

## Download full data

The complete **GBPUSD** archive on **[getdata.finance](https://getdata.finance/datasets/gbpusd)** includes **11 OHLCV timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W) — **9,194,075** rows at `1m`, plus all other timeframes in the same ZIP.

**[-> Get the full GBPUSD dataset on getdata.finance](https://getdata.finance/datasets/gbpusd)**

---
*GetData · GBPUSD 1m OHLCV sample on GitHub · Full historical data on [getdata.finance](https://getdata.finance/datasets/gbpusd)*
