# rti-live

Public daily output of Regime Trade Insider, a Discord trading bot, read by
the case study on [beckportfolio.com](https://beckportfolio.com/work/regime-trader/).

The bot's GitHub Actions jobs update two files every weekday after the US close:

- `live.json`: the market regime from the bot's hidden Markov model (SPY), the
  last 60 trading days, and the screener's top picks. Rules-based, no AI.
- `brief.json`: the day's research report (overview, short- and long-term
  picks, avoid / watch, quant screen top 10). The notes are written by Claude
  from the screen and the week's headlines.

Market data only: nothing about any brokerage account, balance or position.
Automated research, not financial advice; nothing is traded automatically.
