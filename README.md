# Exxon Mobil (XOM) Daily Price Data

Daily stock price data for Exxon Mobil Corporation (NYSE: XOM), covering
2024-06-04 through 2026-07-05.

## Files

- `xom_us_d.csv` — Daily Date, Close, and Volume values. The series has been
  expanded to a continuous calendar-day range: weekend and holiday dates are
  filled in by carrying forward the prior trading day's Close and Volume. The
  final 30 dates (2026-06-06 through 2026-07-05) have blank Close/Volume
  values.
- `xom_us_d.ods` — LibreOffice Calc spreadsheet generated from the CSV,
  including line charts plotting Close and Volume over time, plus calculated
  indicator columns (moving averages and VWAP bands).

## Columns

| Column   | Description                                                                 |
|----------|-----------------------------------------------------------------------------|
| Date     | Calendar date (YYYY-MM-DD)                                                  |
| Close    | Closing price for the trading day                                           |
| Volume   | Shares traded on the trading day                                            |
| Forecast | ETS forecast of Close for future dates (rows 735–763)                       |
| PI       | 95% prediction interval half-width for the forecast                         |
| Lower    | Forecast − PI                                                               |
| Upper    | Forecast + PI                                                               |
| MA21     | 21-day rolling average of Close (blank until row 22)                        |
| MA50     | 50-day rolling average of Close (blank until row 51)                        |
| MA100    | 100-day rolling average of Close (blank until row 101)                      |
| VWAP     | Cumulative volume-weighted average price from the first trading day         |
| VWAP+2SD | VWAP + 2 × volume-weighted standard deviation of price around VWAP         |
| VWAP-2SD | VWAP − 2 × volume-weighted standard deviation of price around VWAP         |
