# 👋 Hello, welcome to my code hub.

I'm Vinícius, a senior data engineer (5+ years) who builds scalable, fault-tolerant pipelines for large companies and startups. I turn complex business requirements into high-performance data architectures, with clear trade-off analysis: build vs. buy, cost, ROI. Lately I spend my time on real-time data, medallion architectures and Web3 data.

**Highlights:**

- A real-time pipeline ingesting orders from Binance, Coinbase and Bybit plus on-chain data (Etherscan, Helius, The Graph), detecting whale moves, MEV and stablecoin depegs.
- An open-source digital asset supply chain (Talos) with classification and telemetry, built as an alternative to enterprise DAM platforms.
- Microsoft Applied Skills work across Azure Data Platform, Azure SQL, security and governance.
- Developing two high-level projects for capturing telemetric data, to be used as input for driving improvements for Counter-Strike and Rainbow Six Siege teams across various tiers.
- 5 articles published on [Medium](https://medium.com/@vinifborgess).

---

## What I'm building right now?

**[data-engineering-portfolio](https://github.com/vinifborgess/data-engineering-portfolio)**: showcase of my data engineering projects.

- [digital-asset-supply-chain (Talos)](https://github.com/vinifborgess/digital-asset-supply-chain), an open-source, self-hosted system to store, classify and track digital assets, modeled as a supply chain: ingestion, transport, storage, automated classification and distribution. It covers the same problem as commercial DAM platforms like Adobe AEM and Bynder, without the enterprise license, and ships telemetry on throughput, latency and failure rate.

- [siege-lens](https://github.com/vinifborgess/siege-lens), Rainbow Six Siege analytics for professional analysts and coaches. It goes beyond the scoreboard metrics (K/D, KOST, headshot rate) that most stats tools stop at.

- [cs2-de](https://github.com/vinifborgess/cs2-de), a tactical intelligence pipeline that turns Counter-Strike 2 `.dem` replays into prescriptive insight for coaches and in-game leaders. Medallion architecture with Parquet, pandas and awpy.

---

## Other projects

- **[real-time-assets](https://github.com/vinifborgess/real-time-assets)**: real-time orders over WebSocket from Binance, Coinbase and Bybit, plus on-chain data and X/Reddit sentiment. Detects whale movements, liquidation cascades, MEV, funding-rate anomalies and stablecoin depegs, with an alerts dashboard.
- **[azure-guardian](https://github.com/vinifborgess/azure-guardian)**: real-time content moderation for online games, using Azure NLP, Speech and Cosmos DB to catch toxic text and voice chat.
- **[orchestration-hub](https://github.com/vinifborgess/orchestration-hub)**: central hub for my projects, pipelines and automations.
- **[applied-skills](https://github.com/vinifborgess/applied-skills)**: hands-on implementations and architecture notes from Microsoft Applied Skills.

---

## Open source

Contributions to [google-maps-scraper](https://github.com/gosom/google-maps-scraper) and [scrapemate](https://github.com/gosom/scrapemate), the Go scraping framework behind it:

- [google-maps-scraper#322](https://github.com/gosom/google-maps-scraper/issues/322#issuecomment-6906769082): independently confirmed the root cause of Windows jobs failing with `unexpected page type`: Chromium flags `--single-process` and `--no-zygote` in scrapemate's `jshttp` fetcher.
- Credited for that diagnosis in [scrapemate#32](https://github.com/gosom/scrapemate/issues/32) and cited in [google-maps-scraper#340](https://github.com/gosom/google-maps-scraper/pull/340).

Forks I work from: [scrapemate](https://github.com/vinifborgess/scrapemate), [awpy-fork](https://github.com/vinifborgess/awpy-fork) and [n8n-templates](https://github.com/vinifborgess/n8n-templates).


---

## 🏅 Certificates & Scores
<img alt="Certificate" src="https://templates.images.credential.net/16875328858623774637935876095299.png" width="150" />

## Tech stack

<h3>Cloud</h3> <p> <img alt="Microsoft Azure" src="https://custom-icon-badges.demolab.com/badge/Microsoft%20Azure-0089D6?logo=msazure&logoColor=white" /> <img alt="Google Cloud Platform" src="https://img.shields.io/badge/-Google_Cloud_Platform-1a73e8?style=flat-square&logo=google-cloud&logoColor=white" /> <img alt="Docker" src="https://img.shields.io/badge/-Docker-46a2f1?style=flat-square&logo=docker&logoColor=white" /> </p> <h3>Modern data stack</h3> <p> <img alt="Power BI" src="https://custom-icon-badges.demolab.com/badge/Power%20BI-F1C912?logo=power-bi&logoColor=fff" /> <img alt="Python" src="https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=fff" /> <img alt="Snowflake" src="https://img.shields.io/badge/Snowflake-29B5E8?logo=snowflake&logoColor=fff" /> <img alt="Apache Spark" src="https://img.shields.io/badge/Apache%20Spark-E25A1C?logo=apachespark&logoColor=fff" /> <img alt="GraphQL" src="https://img.shields.io/badge/-GraphQL-E10098?style=flat-square&logo=graphql&logoColor=white" /> </p> <h3>Databases</h3> <p> <img alt="SAP" src="https://img.shields.io/badge/SAP-0FAAFF?logo=sap&logoColor=fff" /> <img alt="SQLite" src="https://img.shields.io/badge/SQLite-%2307405e.svg?logo=sqlite&logoColor=white" /> <img alt="PostgreSQL" src="https://img.shields.io/badge/Postgres-%23316192.svg?logo=postgresql&logoColor=white" /> <img alt="MySQL" src="https://img.shields.io/badge/MySQL-4479A1?logo=mysql&logoColor=fff" /> <img alt="MS SQL Server" src="https://custom-icon-badges.demolab.com/badge/Microsoft%20SQL%20Server-CC2927?logo=mssqlserver-white&logoColor=white" /> </p> <h3>Engineering in Web3</h3> <p> <img alt="Ethereum" src="https://img.shields.io/badge/Ethereum-3C3C3D?logo=ethereum&logoColor=white" /> <img alt="Solana" src="https://img.shields.io/badge/Solana-9945FF?logo=solana&logoColor=fff" /> <img alt="Chainlink" src="https://img.shields.io/badge/Chainlink-2A5ADA?logo=chainlink&logoColor=white" /> </p> <h3>Management and DevTools</h3> <p> <img alt="Figma" src="https://img.shields.io/badge/Figma-F24E1E?logo=figma&logoColor=white" /> <img alt="Trello" src="https://img.shields.io/badge/Trello-0052CC?logo=trello&logoColor=fff" /> <img alt="Jira" src="https://img.shields.io/badge/Jira-0052CC?logo=jira&logoColor=fff" /> <img alt="Asana" src="https://img.shields.io/badge/Asana-F06A6A?logo=asana&logoColor=fff" /> <img alt="Obsidian" src="https://img.shields.io/badge/Obsidian-%23483699.svg?&logo=obsidian&logoColor=white" /> <img alt="Git" src="https://img.shields.io/badge/-Git-F05032?style=flat-square&logo=git&logoColor=white" /> </p>

---

## Stats

[![Streak](https://streak-stats.demolab.com/?user=vinifborgess&theme=vue-dark&hide_border=true)](https://git.io/streak-stats)

---

## Contact

Brazil (UTC-3), remote

Email: [vinicius.ferreiraborges@outlook.com](mailto:vinicius.ferreiraborges@outlook.com)

LinkedIn: [linkedin.com/in/viniciusfborges](https://www.linkedin.com/in/viniciusfborges/)

X: [@brgx_1](https://x.com/brgx_1)
