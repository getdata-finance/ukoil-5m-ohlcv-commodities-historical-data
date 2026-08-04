# UKOIL 5m OHLCV Commodities Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-1_060_922_rows-blue)](https://getdata.finance/datasets/ukoil) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/ukoil)

### -> [**Download the full UKOIL dataset on getdata.finance**](https://getdata.finance/datasets/ukoil)

**UKOIL 5m OHLCV commodities historical data** — ultra high-quality 5m OHLCV for **UKOIL**. Global commodity sessions — Asia, Europe and US coverage for futures-style market activity. Clean `datetime, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

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

- **Ultra high-quality 5m OHLCV** for **UKOIL** (Commodities)
- **Global commodity sessions — Asia, Europe and US coverage for futures-style market activity**
- **Clean CSV schema** — `datetime, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`5m`) · **9 timeframes** on [getdata.finance](https://getdata.finance/datasets/ukoil) · **1,060,922** `1m` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `5m` sample updated in sync

> **Sample on GitHub** · `UKOIL_5m.csv` (32,278 rows, `2026-02-02` -> `2026-07-31`). **Full archive on [getdata.finance](https://getdata.finance/datasets/ukoil)** — **1,060,922** `1m` rows (~76.09 MB), **9 timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 12H · 3D · 1W), `2010-02-01` -> `2026-07-31`.

## Download sample

**[UKOIL_5m.csv](https://github.com/getdata-finance/ukoil-5m-ohlcv-commodities-historical-data/blob/main/UKOIL_5m.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/getdata-finance/ukoil-5m-ohlcv-commodities-historical-data/main/UKOIL_5m.csv)) · [GitHub Releases](https://github.com/getdata-finance/ukoil-5m-ohlcv-commodities-historical-data/releases)

## GitHub Pages

Interactive chart & stats: **[https://getdata-finance.github.io/ukoil-5m-ohlcv-commodities-historical-data/](https://getdata-finance.github.io/ukoil-5m-ohlcv-commodities-historical-data/)**

Full archive & live chart on getdata.finance: **[https://getdata.finance/datasets/ukoil](https://getdata.finance/datasets/ukoil)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([getdata.finance](https://getdata.finance/datasets/ukoil))** |
|---|--:|---|
| Instrument | UKOIL · Commodities | UKOIL · Commodities |
| Timeframes | `5m` (sample) | **9** — 1m · 3m · 5m · 15m · 30m · 1H · 12H · 3D · 1W |
| 1m rows | 32,278 | **1,060,922** |
| Size | 2.81 MB | ~76.09 MB |
| Period | `2026-02-02` -> `2026-07-31` | `2010-02-01` -> `2026-07-31` |
| File | `UKOIL_5m.csv` | ZIP on [getdata.finance](https://getdata.finance/datasets/ukoil) |
| Coverage report | — | [UKOIL coverage](https://getdata.finance/coverage/ukoil) |
| Updates | Weekly (Saturday, 8am UTC+0) — GitHub sample | Weekly (Saturday, 8am UTC+0) — all timeframes |

## Timeframes on GetData

This GitHub repository ships a **`5m` evaluation sample** only. On **[getdata.finance](https://getdata.finance/datasets/ukoil)**, each full asset archive is delivered as a ZIP with **9 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m** · **3m** · **5m** · **15m** · **30m** · **1H** · **12H** · **3D** · **1W**

GitHub = `5m` sample · [getdata.finance](https://getdata.finance/datasets/ukoil) = all **9** timeframes above for the same instrument.

## Weekly updates

- **[getdata.finance](https://getdata.finance)** — Full datasets are updated every Saturday, 8am UTC+0.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Saturday, 8am UTC+0), in sync with getdata.finance.

When a new `5m` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`UKOIL_5m.csv`**:

**First rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-02-02T04:00:00+00:00 | 65.808 | 65.843 | 65.681 | 65.693 | 416 |
| 2026-02-02T04:05:00+00:00 | 65.693 | 65.713 | 65.631 | 65.677 | 311 |
| 2026-02-02T04:10:00+00:00 | 65.677 | 65.782 | 65.657 | 65.727 | 336 |
| 2026-02-02T04:15:00+00:00 | 65.727 | 65.788 | 65.697 | 65.763 | 278 |
| 2026-02-02T04:20:00+00:00 | 65.763 | 65.783 | 65.686 | 65.736 | 198 |

**Last rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-07-31T20:20:00+00:00 | 85.673 | 85.69 | 85.559 | 85.589 | 311 |
| 2026-07-31T20:25:00+00:00 | 85.589 | 85.72 | 85.563 | 85.72 | 243 |
| 2026-07-31T20:30:00+00:00 | 85.72 | 85.883 | 85.563 | 85.563 | 583 |
| 2026-07-31T20:35:00+00:00 | 85.563 | 85.649 | 85.539 | 85.589 | 270 |
| 2026-07-31T20:40:00+00:00 | 85.589 | 85.74 | 85.583 | 85.658 | 280 |

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

df = pd.read_csv('UKOIL_5m.csv', parse_dates=['datetime'])
df.set_index('datetime', inplace=True)
print(df.describe())
print(df.resample('1h').agg({'open': 'first', 'high': 'max',
                              'low': 'min', 'close': 'last', 'volume': 'sum'}).head())
```

### backtrader

```python
import backtrader as bt
import pandas as pd

df = pd.read_csv('UKOIL_5m.csv', parse_dates=['datetime'])
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

df = pd.read_csv('UKOIL_5m.csv', parse_dates=['datetime'])
close = df.set_index('datetime')['close']
fast, slow = vbt.MA.run(close, 10), vbt.MA.run(close, 50)
entries = fast.ma_crossed_above(slow)
exits = fast.ma_crossed_below(slow)
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='1min')
print(pf.stats())
```

## Download full data

The complete **UKOIL** archive on **[getdata.finance](https://getdata.finance/datasets/ukoil)** includes **9 OHLCV timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 12H · 3D · 1W) — **1,060,922** rows at `1m`, plus all other timeframes in the same ZIP.

**[-> Get the full UKOIL dataset on getdata.finance](https://getdata.finance/datasets/ukoil)**

---
*GetData · UKOIL 5m OHLCV sample on GitHub · Full historical data on [getdata.finance](https://getdata.finance/datasets/ukoil) · 2026-08-04 UTC*
