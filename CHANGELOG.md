# Changelog

All notable changes to this project will be documented here.
The format follows [Keep a Changelog](https://keepachangelog.com/en/1.1.0/).

## [Unreleased]

### Added

- **Python libraries**: `vietfin`, `pyvietstock`, `vntickers`, `Vietnam_Stock`, `vnstock-data-python`
- **APIs & SDKs**: iTick API (REST/WebSocket, 99.99% uptime), EODHD VN Exchange, Vietstock DataFeed, FiinGroup API, Algotrade API Guide
- **Market Data Vendors**: iTick, EODHD, Algotrade
- **Exchanges & Regulators**: VSD (Vietnam Securities Depository), MOF (Ministry of Finance)
- **Open Data**: HNX Market Data downloads, HNX Bond Market, Yahoo Finance VNINDEX, ICE/HNX Fixed Income, Trading Economics
- **Macro / Economic Data**: MOF Bond Auctions, ADB Vietnam Statistics, Trading Economics Vietnam
- **Crypto & Digital Assets** section covering Vietnam's 2026 digital asset regulations and licensing
- **Backtesting & Quant Tools** section with vnquant, Algotrade Hub, Tidy Finance
- **News & Media** section: VnExpress Business, Vietnam Investment Review, Nhip Cau Dau Tu, NDH Money
- **Books & Courses**: Algotrade Lab entry
- **Communities**: vnstock Discussions (GitHub)
- CI/CD: `links.yml` GitHub Actions workflow using lychee for automated link checking on push, PR, and weekly schedule
- `lychee.toml` configuration with smart accept rules (403/429 tolerated), retry logic, and bot-friendly User-Agent
- `.lycheeignore` for whitelisting known bot-blocked sites
- CI badge in README header

### Fixed

- Removed broken link: `github.com/DataCore-VietNam/datacore-mcp-server` (404)

## [0.1.0] - 2026-05-29

Initial release. Curated list across exchanges, regulators, vendors, open data, Python/R libraries, alternative data, macro, ESG, research, communities.

[0.1.0]: https://github.com/DataCore-VietNam/awesome-vietnam-finance-data/releases/tag/v0.1.0
