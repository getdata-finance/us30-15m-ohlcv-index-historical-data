# US30 15m OHLCV Index Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-411_094_rows-blue)](https://getdata.finance/datasets/us30) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/us30)

### -> [**Download the full US30 dataset on getdata.finance**](https://getdata.finance/datasets/us30)

**US30 15m OHLCV index historical data** — ultra high-quality 15m OHLCV for **Dow Jones 30**. Clean `datetime, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

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

- **Ultra high-quality 15m OHLCV** for **Dow Jones 30** (Index)
- **Clean CSV schema** — `datetime, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`15m`) · **11 timeframes** on [getdata.finance](https://getdata.finance/datasets/us30) · **411,094** `15m` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `15m` sample updated in sync

> **Sample on GitHub** · `US30_15m.csv` (12,046 rows, `2026-03-26` -> `2026-09-25`, 920.93 KB). **Full archive on [getdata.finance](https://getdata.finance/datasets/us30)** — **411,094** `15m` rows (full `1m`: 5,980,529), **11 timeframes**, `2009-03-11` -> `2026-09-25`.

## Download sample

**[US30_15m.csv](https://github.com/getdata-finance/us30-15m-ohlcv-index-historical-data/blob/main/US30_15m.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/getdata-finance/us30-15m-ohlcv-index-historical-data/main/US30_15m.csv)) · [GitHub Releases](https://github.com/getdata-finance/us30-15m-ohlcv-index-historical-data/releases)

## GitHub Pages

Interactive chart & stats: **[https://getdata-finance.github.io/us30-15m-ohlcv-index-historical-data/](https://getdata-finance.github.io/us30-15m-ohlcv-index-historical-data/)**

Full archive & live chart on getdata.finance: **[https://getdata.finance/datasets/us30](https://getdata.finance/datasets/us30)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([getdata.finance](https://getdata.finance/datasets/us30))** |
|---|--:|---|
| Instrument | Dow Jones 30 · Index | Dow Jones 30 · Index |
| Timeframes | `15m` (sample) | **11** — 1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W |
| 15m rows | 12,046 | **411,094** |
| Size | 920.93 KB | full ZIP on [getdata.finance](https://getdata.finance/datasets/us30) |
| Period | `2026-03-26` -> `2026-09-25` | `2009-03-11` -> `2026-09-25` |
| File | `US30_15m.csv` | ZIP on [getdata.finance](https://getdata.finance/datasets/us30) |
| Coverage report | — | [US30 coverage](https://getdata.finance/coverage/us30) |
| Updates | Weekly (Saturday, 8am UTC+0) — GitHub sample | Weekly (Saturday, 8am UTC+0) — all timeframes |

## Timeframes on GetData

This GitHub repository ships a **`15m` evaluation sample** only. On **[getdata.finance](https://getdata.finance/datasets/us30)**, each full asset archive is delivered as a ZIP with **11 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W**

GitHub = `15m` sample · [getdata.finance](https://getdata.finance/datasets/us30) = all **11** timeframes above for the same instrument.

## Weekly updates

- **[getdata.finance](https://getdata.finance)** — Full datasets are updated every Saturday, 8am UTC+0.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Saturday, 8am UTC+0), in sync with getdata.finance.

When a new `15m` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`US30_15m.csv`**:

**First rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-03-26T02:30:00+00:00 | 46344.58 | 46352.58 | 46240.58 | 46292.58 | 5256 |
| 2026-03-26T02:45:00+00:00 | 46292.58 | 46313.08 | 46280.08 | 46284.58 | 2803 |
| 2026-03-26T03:00:00+00:00 | 46284.58 | 46313.58 | 46273.58 | 46310.58 | 2048 |
| 2026-03-26T03:15:00+00:00 | 46310.58 | 46337.08 | 46297.58 | 46330.58 | 2099 |
| 2026-03-26T03:30:00+00:00 | 46330.58 | 46437.58 | 46328.58 | 46427.58 | 3935 |

**Last rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-09-25T19:30:00+00:00 | 51708.01 | 51785.01 | 51702.01 | 51773.01 | 4508 |
| 2026-09-25T19:45:00+00:00 | 51773.01 | 51826.01 | 51755.01 | 51774.51 | 8668 |
| 2026-09-25T20:00:00+00:00 | 51774.51 | 51798.66 | 51767.66 | 51775.66 | 2107 |
| 2026-09-25T20:15:00+00:00 | 51775.66 | 51780.16 | 51764.66 | 51768.16 | 878 |
| 2026-09-25T20:30:00+00:00 | 51768.16 | 51786.16 | 51765.66 | 51784.66 | 598 |

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

df = pd.read_csv('US30_15m.csv', parse_dates=['datetime'])
df.set_index('datetime', inplace=True)
print(df.describe())
```

### backtrader

```python
import backtrader as bt
import pandas as pd

df = pd.read_csv('US30_15m.csv', parse_dates=['datetime'])
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

df = pd.read_csv('US30_15m.csv', parse_dates=['datetime'])
close = df.set_index('datetime')['close']
fast, slow = vbt.MA.run(close, 10), vbt.MA.run(close, 50)
entries = fast.ma_crossed_above(slow)
exits = fast.ma_crossed_below(slow)
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='15min')
print(pf.stats())
```

## Download full data

The complete **US30** archive on **[getdata.finance](https://getdata.finance/datasets/us30)** includes **11 OHLCV timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W) — **411,094** rows at `15m`, plus all other timeframes in the same ZIP.

**[-> Get the full US30 dataset on getdata.finance](https://getdata.finance/datasets/us30)**

---
*GetData · US30 15m OHLCV sample on GitHub · Full historical data on [getdata.finance](https://getdata.finance/datasets/us30)*
