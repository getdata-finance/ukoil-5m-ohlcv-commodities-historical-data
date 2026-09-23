# UKOIL 5m OHLCV Commodities Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-1_070_208_rows-blue)](https://getdata.finance/datasets/ukoil) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/ukoil)

### -> [**Download the full UKOIL dataset on getdata.finance**](https://getdata.finance/datasets/ukoil)

**UKOIL 5m OHLCV commodities historical data** — ultra high-quality 5m OHLCV for **Brent Crude Oil**. Clean `datetime, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

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

- **Ultra high-quality 5m OHLCV** for **Brent Crude Oil** (Commodities)
- **Clean CSV schema** — `datetime, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`5m`) · **11 timeframes** on [getdata.finance](https://getdata.finance/datasets/ukoil) · **1,070,208** `5m` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `5m` sample updated in sync

> **Sample on GitHub** · `UKOIL_5m.csv` (32,771 rows, `2026-03-23` -> `2026-09-23`, 2.79 MB). **Full archive on [getdata.finance](https://getdata.finance/datasets/ukoil)** — **1,070,208** `5m` rows (full `1m`: 5,228,763), **11 timeframes**, `2010-02-01` -> `2026-09-23`.

## Download sample

**[UKOIL_5m.csv](https://github.com/getdata-finance/ukoil-5m-ohlcv-commodities-historical-data/blob/main/UKOIL_5m.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/getdata-finance/ukoil-5m-ohlcv-commodities-historical-data/main/UKOIL_5m.csv)) · [GitHub Releases](https://github.com/getdata-finance/ukoil-5m-ohlcv-commodities-historical-data/releases)

## GitHub Pages

Interactive chart & stats: **[https://getdata-finance.github.io/ukoil-5m-ohlcv-commodities-historical-data/](https://getdata-finance.github.io/ukoil-5m-ohlcv-commodities-historical-data/)**

Full archive & live chart on getdata.finance: **[https://getdata.finance/datasets/ukoil](https://getdata.finance/datasets/ukoil)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([getdata.finance](https://getdata.finance/datasets/ukoil))** |
|---|--:|---|
| Instrument | Brent Crude Oil · Commodities | Brent Crude Oil · Commodities |
| Timeframes | `5m` (sample) | **11** — 1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W |
| 5m rows | 32,771 | **1,070,208** |
| Size | 2.79 MB | full ZIP on [getdata.finance](https://getdata.finance/datasets/ukoil) |
| Period | `2026-03-23` -> `2026-09-23` | `2010-02-01` -> `2026-09-23` |
| File | `UKOIL_5m.csv` | ZIP on [getdata.finance](https://getdata.finance/datasets/ukoil) |
| Coverage report | — | [UKOIL coverage](https://getdata.finance/coverage/ukoil) |
| Updates | Weekly (Saturday, 8am UTC+0) — GitHub sample | Weekly (Saturday, 8am UTC+0) — all timeframes |

## Timeframes on GetData

This GitHub repository ships a **`5m` evaluation sample** only. On **[getdata.finance](https://getdata.finance/datasets/ukoil)**, each full asset archive is delivered as a ZIP with **11 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W**

GitHub = `5m` sample · [getdata.finance](https://getdata.finance/datasets/ukoil) = all **11** timeframes above for the same instrument.

## Weekly updates

- **[getdata.finance](https://getdata.finance)** — Full datasets are updated every Saturday, 8am UTC+0.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Saturday, 8am UTC+0), in sync with getdata.finance.

When a new `5m` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`UKOIL_5m.csv`**:

**First rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-03-23T02:30:00+00:00 | 112.498 | 112.62 | 112.338 | 112.429 | 1024 |
| 2026-03-23T02:35:00+00:00 | 112.429 | 112.83 | 112.31 | 112.8 | 978 |
| 2026-03-23T02:40:00+00:00 | 112.8 | 112.863 | 112.529 | 112.639 | 979 |
| 2026-03-23T02:45:00+00:00 | 112.639 | 112.76 | 112.464 | 112.76 | 866 |
| 2026-03-23T02:50:00+00:00 | 112.76 | 112.78 | 112.509 | 112.6 | 829 |

**Last rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-09-23T01:40:00+00:00 | 99.066 | 99.221 | 99.054 | 99.185 | 706 |
| 2026-09-23T01:45:00+00:00 | 99.185 | 99.281 | 99.041 | 99.041 | 635 |
| 2026-09-23T01:50:00+00:00 | 99.041 | 99.076 | 98.89 | 98.941 | 681 |
| 2026-09-23T01:55:00+00:00 | 98.941 | 98.951 | 98.859 | 98.88 | 576 |
| 2026-09-23T02:00:00+00:00 | 98.88 | 98.89 | 98.696 | 98.744 | 347 |

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
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='5min')
print(pf.stats())
```

## Download full data

The complete **UKOIL** archive on **[getdata.finance](https://getdata.finance/datasets/ukoil)** includes **11 OHLCV timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W) — **1,070,208** rows at `5m`, plus all other timeframes in the same ZIP.

**[-> Get the full UKOIL dataset on getdata.finance](https://getdata.finance/datasets/ukoil)**

---
*GetData · UKOIL 5m OHLCV sample on GitHub · Full historical data on [getdata.finance](https://getdata.finance/datasets/ukoil)*
