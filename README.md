# Exxon Mobil (XOM) Daily Price Data

Daily stock price data for Exxon Mobil Corporation (NYSE: XOM), covering
2024-06-04 through 2026-07-05.

## Files

- `xom_us_d.csv` — Daily Date, Close, and Volume values. The series has been
  expanded to a continuous calendar-day range: weekend and holiday dates are
  filled in by carrying forward the prior trading day's Close and Volume. The
  final 30 dates (2026-06-06 through 2026-07-05) have blank Close/Volume
  values.
- `xom_us_d.ods` — LibreOffice Calc spreadsheet generated from the CSV.

## Columns

| Column | Description                          |
|--------|--------------------------------------|
| Date   | Calendar date (YYYY-MM-DD)           |
| Close  | Closing price for the trading day    |
| Volume | Shares traded on the trading day     |
