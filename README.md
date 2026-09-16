# NSE Market Data Pine Scripts

This public repository contains generated TradingView Pine Script outputs from the private automation pipeline.

## Update schedule

The files are refreshed automatically every morning at **8:00 AM IST (Asia/Kolkata)** using GitHub Actions.

The daily process downloads the latest source data, regenerates the Pine Script files, and publishes the updated outputs here.

## Available outputs

- `nse_circuit_limit_static.pine` — latest NSE circuit-limit mapping for supported symbols.
- `results/nse_circuit_limit_static.pine` — same circuit-limit Pine output inside the results folder.
- `results/MS India Fund Ownership.pine` — MarketSmith India fund-ownership data embedded into the Pine indicator, including the fund tier/trend and bucket logic.

## Notes

- These files are auto-generated. Manual edits may be overwritten by the next scheduled run.
- Data availability depends on the respective upstream sources.
- The repository contains generated Pine outputs only; the private data-fetching and generation code is maintained separately.
