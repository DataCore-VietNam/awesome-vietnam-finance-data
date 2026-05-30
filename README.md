# Awesome Vietnam Finance Data [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) [![Links](https://github.com/DataCore-VietNam/awesome-vietnam-finance-data/actions/workflows/links.yml/badge.svg)](https://github.com/DataCore-VietNam/awesome-vietnam-finance-data/actions/workflows/links.yml)

> A curated list of data sources, libraries, tools, and communities for Vietnamese financial markets.

Maintained by [DataCore Vietnam](https://datacore.vn). Contributions welcome — see [CONTRIBUTING.md](CONTRIBUTING.md).

## Contents

- [Exchanges & Regulators](#exchanges--regulators)
- [Market Data Vendors](#market-data-vendors)
- [Open Data](#open-data)
- [Python Libraries](#python-libraries)
- [R Packages](#r-packages)
- [APIs & SDKs](#apis--sdks)
- [Alternative Data](#alternative-data)
- [Macro / Economic Data](#macro--economic-data)
- [ESG Data](#esg-data)
- [Crypto & Digital Assets](#crypto--digital-assets)
- [Backtesting & Quant Tools](#backtesting--quant-tools)
- [Research & Academic](#research--academic)
- [News & Media](#news--media)
- [Books & Courses](#books--courses)
- [Communities](#communities)

## Exchanges & Regulators

- [HOSE](https://www.hsx.vn/) — Ho Chi Minh Stock Exchange; primary equity venue.
- [HNX](https://www.hnx.vn/) — Hanoi Stock Exchange; equities, bonds, and derivatives.
- [UPCOM](https://www.hnx.vn/) — Unlisted Public Company Market, operated by HNX.
- [VSD](https://www.vsd.vn/) — Vietnam Securities Depository and Clearing Corporation.
- [SSC](https://www.ssc.gov.vn/) — State Securities Commission of Vietnam; securities regulator.
- [SBV](https://www.sbv.gov.vn/) — State Bank of Vietnam; central bank, FX policy, and banking supervision.
- [MOF](https://www.mof.gov.vn/) — Ministry of Finance; fiscal policy, bond auctions, and insurance oversight.
- [GSO](https://www.gso.gov.vn/) — General Statistics Office; official national statistics.

## Market Data Vendors

- [DataCore](https://datacore.vn) — Vietnamese financial and alternative data via REST API and MCP server.
- [FiinGroup](https://fiingroup.vn/) — Premium financial information, analytics, and professional API data feed.
- [VietstockFinance](https://finance.vietstock.vn/) — Aggregated market data, charting, and news platform.
- [CafeF](https://cafef.vn/) — Financial news and market data aggregator with free ticker pages.
- [iTick](https://itick.io/en) — Real-time and historical market data API; covers VN stocks via REST and WebSocket.
- [EODHD](https://eodhd.com/exchange/VN) — Historical OHLCV and fundamental data for Vietnam Exchange tickers.
- [Algotrade](https://www.algotrade.vn/) — Algorithmic trading platform and knowledge hub focused on VN markets.

## Open Data

- [SSI iBoard](https://iboard.ssi.com.vn/) — Free real-time quotes from SSI Securities; widely used by open-source libraries.
- [VnDirect Charts](https://dchart.vndirect.com.vn/) — Free chart and market data portal.
- [HNX Market Data](https://hnx.vn/en-gb/co-phieu-etfs/du-lieu-thi-truong-ny.html) — Official HNX daily trading data downloads.
- [HNX Bond Market](https://www.hnx.vn/en-gb/trai-phieu-chinh-phu.html) — Government bond auction results and yield data.
- [Yahoo Finance — VNINDEX](https://finance.yahoo.com/quote/%5EVNINDEX.VN/) — Free VNINDEX historical price download.
- [World Bank Open Data — Vietnam](https://data.worldbank.org/country/vietnam) — Development and economic indicators.
- [Trading Economics Vietnam](https://tradingeconomics.com/vietnam/indicators) — 20M+ macro indicators with Vietnam coverage and forecasts.
- [ICE / HNX Fixed Income](https://developer.ice.com/fixed-income-data-services/catalog/hanoi-stock-exchange-hnx) — HNX bond data via ICE Developer Portal.

## Python Libraries

- [vnstock](https://github.com/thinh-vu/vnstock) — Beginner-friendly toolkit for financial analysis and automation; actively maintained, v3+ on PyPI.
- [vietfin](https://github.com/vietfin/vietfin) — Standardized wrapper around public APIs from multiple Vietnamese brokerages.
- [vnquant](https://github.com/phamdinhkhanh/vnquant) — Quantitative analysis with historical prices, financial statements, and visualization.
- [pyvietstock](https://github.com/kimnt93/pyvietstock) — Python client for Vietstock Finance data retrieval and analysis.
- [vntickers](https://github.com/gahoccode/vntickers) — Lightweight package retrieving closing price data from multiple VN market sources.
- [Vietnam_Stock](https://github.com/Hnam29/Vietnam_Stock) — Efficient library for comprehensive VN stock data using public broker APIs.
- [vnstock-data-python](https://github.com/vuthanhdatt/vnstock-data-python) — Alternative Python package for accessing Vietnam stock data.
- [datacore](https://github.com/DataCore-VietNam/datacore-python) — Official DataCore Python SDK.

## R Packages

- [datacore-r](https://github.com/DataCore-VietNam/datacore-r) — Official DataCore R client.
- Add your package — see [CONTRIBUTING.md](CONTRIBUTING.md).

## APIs & SDKs

- [DataCore API](https://docs.datacore.vn) — REST and MCP server for Vietnamese financial and alternative data.
- [iTick API](https://docs.itick.io/en) — Real-time quotes, order book, and historical candlestick API; 99.99% uptime; free tier available.
- [iTick VN Stock Guide](https://blog.itick.io/en/stock-api/2026-vietnam-stock-exchange-api-python-tutorial) — Python tutorial for HOSE/VN30 API integration.
- [EODHD VN Exchange API](https://eodhd.com/exchange/VN) — Ticker list, historical OHLCV, and fundamental data for VN-listed securities.
- [Vietstock DataFeed](https://dichvu.vietstock.vn/du-lieu-tai-chinh/datafeed---du-lieu-tai-chinh-tich-hop-chuyen-nghiep) — Professional price feed, corporate actions, and financial statements.
- [FiinGroup API](https://fiingroup.vn/ApiDataFeed) — Price feed, corporate reference data, financials, and corporate actions data feed.
- [SSI iBoard API](https://iboard.ssi.com.vn/) — Unofficial real-time quote endpoint widely used by open-source VN libraries.
- [Algotrade API Guide](https://hub.algotrade.vn/knowledge-hub/api-in-vietnam-stock-market/) — Overview of VN broker APIs (SSI, BSC, DNSE) with algorithmic trading context.

## Alternative Data

- E-commerce signals — Transaction and GMV trends from Shopee, Tiki, and Lazada platforms.
- Satellite imagery — Port throughput proxies for Saigon Port and Hai Phong; useful for trade and industrial indicators.
- Social sentiment — Vietnamese-language ticker sentiment from Facebook groups, F319, and Reddit.
- On-chain flows — Vietnam ranked 4th globally in Chainalysis 2025 Crypto Adoption Index; on-chain volume proxies consumer activity.
- [DataCore](https://datacore.vn) — Structured alternative data feeds for VN markets via API.
- Add your source — see [CONTRIBUTING.md](CONTRIBUTING.md).

## Macro / Economic Data

- [GSO Statistical Yearbook](https://www.gso.gov.vn/en/statistical-yearbook/) — Official annual national statistics publication.
- [SBV Monetary Statistics](https://www.sbv.gov.vn/) — Central bank rates, FX reserves, and banking sector data.
- [MOF Bond Auctions](https://www.mof.gov.vn/) — Government bond issuance schedules and auction results.
- [World Bank Open Data — Vietnam](https://data.worldbank.org/country/vietnam) — Long-run development and economic indicators.
- [IMF — Vietnam](https://www.imf.org/en/Countries/VNM) — Article IV reports, balance of payments, and fiscal data.
- [ADB Vietnam Statistics](https://data.adb.org/country/viet-nam) — Asian Development Bank country data and key indicators.
- [Trading Economics Vietnam](https://tradingeconomics.com/vietnam/indicators) — Aggregated macro dashboard with historical data and forecasts.

## ESG Data

- [VNSI](https://www.hsx.vn/Modules/VNSI/Default.aspx) — Vietnam Sustainability Index on HOSE; constituent list and methodology.
- [HNX Green Bonds](https://www.hnx.vn/en-gb/trai-phieu-xanh.html) — Green bond listings and disclosure data on HNX.
- Add your source — see [CONTRIBUTING.md](CONTRIBUTING.md).

## Crypto & Digital Assets

Vietnam's Law on Digital Technology Industry (effective 1 Jan 2026) formally brought digital assets under government oversight. Licensed domestic exchanges are expected to launch in 2026.

- [Chainalysis Crypto Adoption Index](https://www.chainalysis.com/blog/2025-global-crypto-adoption-index/) — Vietnam ranked 4th globally in 2025; strong DeFi and P2P usage.
- [VN Crypto Licensing — Fintech Singapore](https://fintechnews.sg/127795/crypto/vietnam-crypto-exchanges/) — Overview of applicants for the first VN crypto exchange licenses.
- [VN Crypto Licensing — Yahoo Finance](https://finance.yahoo.com/news/vietnam-opens-crypto-exchange-licensing-163712299.html) — Coverage of regulatory developments.
- Add your exchange API — see [CONTRIBUTING.md](CONTRIBUTING.md).

## Backtesting & Quant Tools

- [vnquant](https://github.com/phamdinhkhanh/vnquant) — Includes portfolio construction and basic backtest utilities for VN stocks.
- [Algotrade Knowledge Hub](https://hub.algotrade.vn/) — 60+ articles on algo trading theory, backtesting, and optimization for VN markets.
- Add your tool — see [CONTRIBUTING.md](CONTRIBUTING.md).

## Research & Academic

- [SSRN — Vietnam Markets](https://www.ssrn.com/) — Academic papers on Vietnamese capital markets and financial economics.
- [KPMG Vietnam 2026 Outlook](https://assets.kpmg.com/content/dam/kpmgsites/vn/pdf/2025/10/vietnam-2026-outlook.pdf) — Annual macro and capital market outlook report.
- [Tidy Finance Vietnam](https://tidy-finance.org/) — Open-source quant finance teaching materials and replicable research for VN markets.

## News & Media

- [CafeF](https://cafef.vn/) — Leading Vietnamese financial news portal.
- [VnExpress Business](https://e.vnexpress.net/business) — English-language business and market news.
- [Vietnam Investment Review](https://vir.com.vn/) — English-language investment and business news.
- [Nhip Cau Dau Tu](https://nhipcaudautu.vn/) — Investor-focused Vietnamese financial magazine.
- [NDH Money](https://ndh.vn/) — Vietnamese financial news and analysis.

## Books & Courses

- [Algotrade Lab](https://hub.algotrade.vn/knowledge-hub/algotrade-lab-overview/) — Hands-on algorithmic trading course for VN markets; covers API setup and live strategy testing.
- Add your resource — see [CONTRIBUTING.md](CONTRIBUTING.md).

## Communities

- [r/VietNamFinance](https://www.reddit.com/r/VietNamFinance) — Reddit community for Vietnamese finance discussion.
- [F319](https://f319.com/) — Largest Vietnamese stock market forum; active trading signals and news.
- [vnstock Discussions](https://github.com/thinh-vu/vnstock/discussions) — GitHub Discussions for vnstock users and contributors.
- Add your community — see [CONTRIBUTING.md](CONTRIBUTING.md).

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)
