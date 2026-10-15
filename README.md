# Fabric Compass

**A curated reference repository tracking the evolution of Microsoft Fabric** — conference recaps, monthly feature summaries, roadmap snapshots, blogs, documentation and per-workload deep dives, all in one place.

> ⚠️ **Disclaimer:** This is a personal, unofficial reference maintained by Daniele Vitale (Cloud Solution Architect, Microsoft). Content links to public Microsoft sources and community material. Opinions and notes are my own and do not represent official Microsoft positions. Always check the official [Fabric Roadmap](https://aka.ms/FabricRoadmap) and [Microsoft Learn](https://learn.microsoft.com/fabric/) for current status.

---

## Why this repo

Microsoft Fabric evolves fast: two FabCons a year, Build and Ignite, monthly feature summaries, a public roadmap and dozens of product blogs. This repository keeps a **chronological and thematic record** of that evolution so it's easy to:

- see **what was announced, when, and with what status** (GA / Preview / Coming soon)
- find the **authoritative source** (blog, docs, roadmap entry) for any capability
- track how a workload or feature **changed over time**
- prepare **customer conversations** with up-to-date, linked material

## Repository structure

```
fabric-compass/
├── README.md                 # this file — index and how to navigate
├── CHANGELOG.md              # what was added to the repo and when
├── conferences/              # event recaps: FabCon, SQLCon, Build, Ignite
│   └── YYYY-MM-event-city.md
├── monthly-updates/          # Fabric & Power BI monthly feature summaries (notes + links)
│   └── YYYY-MM-fabric.md / YYYY-MM-powerbi.md
├── roadmap/                  # dated snapshots of the official roadmap + commentary
│   └── YYYY-MM-roadmap-snapshot.md
├── blogs/                    # curated blog posts, organised by workload
│   ├── fabric-iq-and-agents.md
│   ├── onelake.md
│   ├── data-factory.md
│   ├── data-engineering.md
│   ├── data-warehouse.md
│   ├── real-time-intelligence.md
│   ├── power-bi.md
│   ├── fabric-apps.md
│   ├── platform-governance-admin.md
│   └── databases.md
├── docs/                     # key Microsoft Learn articles, decision guides, architecture guidance
└── workloads/                # evolution timeline per workload (what changed, release by release)
```

### Naming conventions
- Files are prefixed with `YYYY-MM` so they sort chronologically.
- Every announcement carries a status tag: **GA**, **Preview**, **Private preview**, **Coming soon**, **Retired**.
- Every item links to its primary source (Microsoft blog, Learn docs or roadmap). Community sources are marked as such.

---

## Conferences

| Date | Event | Location | Recap |
|---|---|---|---|
| 28 Sep – 1 Oct 2026 | FabCon Europe + SQLCon Europe 2026 | Barcelona | [2026-09-fabcon-europe-barcelona.md](conferences/2026-09-fabcon-europe-barcelona.md) |
| Mar 2026 | FabCon + SQLCon 2026 | Atlanta | _to add_ — [Microsoft highlights post](https://www.microsoft.com/en-us/microsoft-fabric/blog/2026/03/30/highlights-from-fabcon-and-sqlcon-2026-where-databases-and-fabric-come-together/) |
| Sep 2025 | FabCon Europe 2025 | Vienna | _to add_ |
| Sep 2024 | FabCon Europe 2024 | Stockholm | _to add_ — [Official recap](https://community.fabric.microsoft.com/t5/Fabric-Updates-Blog/Fabric-Community-Conference-Europe-Recap/ba-p/5173066) |

Upcoming: **Microsoft Ignite** — San Francisco, 17–20 November 2026.

## Monthly updates

| Month | Fabric | Power BI |
|---|---|---|
| September 2026 | [Feature Summary](https://community.fabric.microsoft.com/blog/fbc_fabricupdatesblogs/fabric-september-2026-feature-summary/5325825) | [Feature Summary](https://community.fabric.microsoft.com/blog/fbc_pbiupdatesblog/power-bi-september-2026-feature-summary/5325831) |
| August 2026 | [Feature Summary](https://community.fabric.microsoft.com/category/fabricupdatesblogs/blog/fbc_fabricupdatesblogs) | [Feature Summary](https://community.fabric.microsoft.com/category/fabricupdatesblogs/blog/fbc_pbiupdatesblog) |

_Notes per month go in `monthly-updates/`._

## Roadmap

- Official Fabric Roadmap: https://aka.ms/FabricRoadmap
- Fabric "What's new" (rolling list): https://learn.microsoft.com/fabric/fundamentals/whats-new
- Snapshots with commentary go in `roadmap/`.

## Essential links

**Official**
- Microsoft Fabric Blog: https://www.microsoft.com/en-us/microsoft-fabric/blog/
- Fabric Updates Blog (Community): https://community.fabric.microsoft.com/category/fabricupdatesblogs/blog/fbc_fabricupdatesblogs
- Power BI Updates Blog (Community): https://community.fabric.microsoft.com/category/fabricupdatesblogs/blog/fbc_pbiupdatesblog
- Azure SQL / SQL Server Blog: https://www.microsoft.com/en-us/sql-server/blog/
- Microsoft Learn — Fabric documentation: https://learn.microsoft.com/fabric/
- Fabric Ideas: https://ideas.fabric.microsoft.com
- Fabric SKU Estimator: https://aka.ms/FabricSKUEstimator

**Community**
- Fabric Weekly newsletter: https://fabricweekly.info/
- Power BI Weekly newsletter: https://powerbiweekly.info/
- Awesome Microsoft Fabric (curated list): https://github.com/bhakthan/awesome-microsoft-fabric
- r/MicrosoftFabric: https://www.reddit.com/r/MicrosoftFabric/

## Workloads tracked

Fabric IQ & agents · OneLake · Data Factory · Data Engineering · Data Warehouse · Data Science · Real-Time Intelligence · Power BI · Fabric Apps · Platform, governance & admin · Databases (SQL database in Fabric, Azure SQL, PostgreSQL, Cosmos DB)

## Contributing / maintaining

1. Add the new file under the right folder using the `YYYY-MM-` prefix.
2. Link it from the relevant table in this README.
3. Add a line to `CHANGELOG.md`.
4. Tag every announcement with its status and primary source link.

Suggested GitHub topics: `microsoft-fabric` `power-bi` `onelake` `fabric-iq` `data-platform` `azure-data` `knowledge-base`

---

_Last updated: 5 October 2026_
