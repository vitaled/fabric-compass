# FabCon Europe + SQLCon Europe 2026 — Detailed Recap

**Event:** European Microsoft Fabric + SQL Community Conference  
**Where / when:** Centre de Convencions Internacional de Barcelona (CCIB), 28 September – 1 October 2026  
**Scale:** nearly 5,000 attendees · 130+ sessions · 10+ hands-on tutorials · community meetups and roundtables  
**Keynote:** "The Data Foundation for AI: What's Next in Microsoft Fabric" — Arun Ulag, Amir Netz, Shireesh Thota (Tue 29 Sept, 08:45–10:45)  
**Momentum numbers:** Microsoft Fabric 40,000+ customers · Power BI 425,000+ customers · 22M+ Power BI semantic models in use  
**Big theme:** the data foundation you build in Fabric now reaches Microsoft Copilot and agents directly (Fabric IQ).

> Status tags below are Microsoft's own wording: **GA** = generally available, **Preview**, **Coming soon**.

---

## Start here — official hub posts

| Post | Author | Link |
|---|---|---|
| Keynote hero blog — *FabCon and SQLCon 2026 in Barcelona: Building the data foundation for Microsoft Copilot and agents* | Arun Ulag (EVP, Azure Data) | https://azure.microsoft.com/en-us/blog/fabcon-and-sqlcon-2026-in-barcelona-building-the-data-foundation-for-microsoft-copilot-and-agents/ |
| Fabric September 2026 Feature Summary (full itemised list) | Katie Murray | https://community.fabric.microsoft.com/blog/fbc_fabricupdatesblogs/fabric-september-2026-feature-summary/5325825 |
| Power BI September 2026 Feature Summary | Katie Murray | https://community.fabric.microsoft.com/blog/fbc_pbiupdatesblog/power-bi-september-2026-feature-summary/5325831 |
| Fabric Update — September 2026 (video, ~22 min) | Microsoft Fabric (YouTube) | https://www.youtube.com/watch?v=aQLyguIg1Qk |
| Conference programme (sessions, tutorials, keynote agenda) | ESPC | https://espc.tech/conference/fabcon-europe-2026/programme/ |
| Pre-event session picks — *The sessions we're most excited to bring to Barcelona* | Kim Manis | https://www.microsoft.com/en-us/microsoft-fabric/blog/2026/06/25/fabcon-europe-2026-the-sessions-were-most-excited-to-bring-to-barcelona/ |

---

## 1. Fabric IQ, Copilot & agents

**Deep dives**
- *Bringing governed analytics into the flow of work: Fabric Analytics at FabCon Europe 2026* — Bogdan Crivat  
  https://community.fabric.microsoft.com/blog/fbc_fabricupdatesblogs/bringing-governed-analytics-into-the-flow-of-work-fabric-analytics-at-fabcon-eur/5368918
- *Trusted AI starts with Microsoft Fabric, Real-Time Intelligence, and IQ* — Yitzhak Kesselman  
  https://community.fabric.microsoft.com/blog/fbc_fabricupdatesblogs/trusted-ai-starts-with-microsoft-fabric-real-time-intelligence-and-iq/5369528
- Video: *Trusted AI starts with Microsoft Fabric, Real-Time Intelligence, and IQ*  
  https://www.youtube.com/watch?v=0Zqvi5HbxWs

**Announcements**
- **Fabric IQ in Microsoft Copilot Chat — GA.** Ask business questions and get answers grounded in governed Power BI reports and semantic models; Copilot infers which report/model fits the question. No additional AI token costs.
- **Fabric IQ in Microsoft Copilot Cowork — GA.** Power BI content participates directly in long-running and asynchronous tasks.
- **Fabric IQ in the new Copilot "Code" experience — Coming soon** via the Frontier program.
- **Fabric IQ MCP server — GA.** Same conversational analytics from development tools and external MCP clients.
- **Microsoft 365 Copilot in Power BI — Preview.** Fabric IQ + Work IQ context + Cowork actions in one conversation. Off by default behind a new Fabric admin portal setting (independent of the standalone Power BI Copilot setting); initially for Microsoft 365 Copilot licence holders.
- **Fabric data agents in Copilot Studio — GA.** Visualisations in data agents — GA; topics in data agents — Preview.
- **Fabric IQ expanded to answer from data agents and ontologies — Preview.**
- **Ontologies:** new agentic experience to create ontologies from semantic models, OneLake data and context documents; define rules in natural language and connect them to entities/properties/relationships; bring Power BI DAX measures into an ontology.
- **Build agent with AI mode** can use semantic models, documentation, glossaries and data dictionaries to generate richer data agents with less manual configuration.
- **Operations agents:** pre-approved actions and root-cause analysis — Preview.
- **Microsoft IQ framing:** Web IQ + Work IQ + Foundry IQ + Fabric IQ as the four complementary intelligence sources; Fabric IQ contributes governed business meaning across data, models, operational signals, entities, relationships, history and actions.
- **Trust travels with the data:** sensitivity labels, DLP enforcement and admin controls follow data across product boundaries; new "Restrict from Copilot" control lets model owners block read-only users from querying a model via Copilot/MCP (access allowed by default).
- **Planning in Fabric IQ:** new Native Planning Engine — Preview (up to 10x performance/scale); planners connect to a semantic model directly with their signed-in identity; deeper Fabric IQ integration.
- **Customer proof points:** Hilti (25,000 users across 700 Fabric workspaces, eight business domains), Mohawk Industries (Copilot Chat on Power BI semantic models).

## 2. Power BI

**Deep dive**
- *Power BI's next chapter: The evolution of business intelligence* — Mohammad Ali  
  https://community.fabric.microsoft.com/blog/fbc_pbiupdatesblog/power-bi%E2%80%99s-next-chapter-the-evolution-of-business-intelligence/5369131

**Announcements**
- **Agentic app creation in Power BI Desktop** (arriving "in the coming months"): start from a trusted semantic model, describe the application in natural language, preview and edit in real time, publish to Fabric. Apps accept inputs, write back data, preserve shared state and support operational workflows; each app gets a SQL database in Fabric, authentication and security via Fabric Apps.
- **Licensing headline:** Apps in Power BI in **Preview in the coming weeks for Power BI Pro and Premium Per User** as well as Fabric capacity customers — **at no additional cost**, including Fabric Apps and Fabric Database capabilities **up to 1 GB per app**.
- **Semantic views — early look:** governed business metrics and semantics defined directly where data lives in OneLake, reusable across and beyond Fabric.
- **Apache Ossie (incubating):** Microsoft + Snowflake commitment to a vendor-neutral standard for exchanging semantic metadata; open-source converter turns an Ossie document into a Snowflake Semantic View and a Power BI semantic model; plan to establish DAX as an Ossie-recognised query language and extend support to ontologies.
- From the **Power BI September 2026 Feature Summary:**
  - Power BI Agentic Experiences — GA
  - Power BI Projects (PBIP) — GA; PBIR becomes the default report format (legacy reports converted on edit — check scripts that parse the old format)
  - Remote Power BI Authoring MCP Server — Preview
  - Create and edit DirectQuery semantic models in the service
  - APPROXIMATEDISTINCTCOUNT for Import and Direct Lake — Preview (~1.6% standard error)
  - String indexing & full-text search in semantic models — Preview
  - New Power Query editor in Desktop — Preview
  - Outlook Mail connector — Preview; new Report Ribbon on the web — Preview; Live Visual Sharing in Outlook on the web — Preview
  - Increased Export to Excel row limits — GA
- **Admin notes:** from October, Power BI Desktop versions from March 2026 or earlier can no longer save to OneDrive/SharePoint. Power BI Q&A retirement timeline moved to February 2027.

## 3. Fabric Apps (Rayfin)

**Deep dive**
- *From prompt to production: What's new in Fabric Apps* — Sachin Patney  
  https://community.fabric.microsoft.com/blog/fbc_fabricupdatesblogs/from-prompt-to-production-whats-new-in-fabric-apps/5369134

**Announcements**
- 15,000+ developers have built a Fabric App since the June 2026 launch.
- **Fabric data connectors:** direct connections to Fabric SQL Databases and Warehouses (read/write), Lakehouse SQL analytics endpoints and Power BI semantic models (read-only, DAX queries) — no data copies, existing permissions preserved, schemas discovered automatically.
- **New backend services:** TypeScript backend functions, Secret Store, built-in storage, PostgreSQL support, private-by-default access, built-in usage and performance metrics.
- **Rayfin** open-source SDK + CLI: describe the app in TypeScript (you or your coding agent), generate typed APIs/clients, run locally, deploy as a Fabric App with database, storage, connectors, functions and auth governed for you.
- Build Fabric Apps in the GitHub Copilot App — Preview; support for Fabric Apps in Org apps — Coming soon.
- Fabric Apps gallery with Microsoft and community examples.

## 4. OneLake & ecosystem

**Deep dive**
- *FabCon and SQLCon Barcelona 2026: What's new in Microsoft OneLake and its rapidly growing ecosystem* — Dipti Borkar  
  https://community.fabric.microsoft.com/blog/fbc_fabricupdatesblogs/fabcon-and-sqlcon-barcelona-2026-what%E2%80%99s-new-in-microsoft-onelake-and-its-rapidly/5369146

**Announcements**
- **IQ sharing — Preview.** Securely share governed data and business context across teams, customers, partners and ecosystems. At launch: governed tables and files plus Markdown agent instructions and RDF ontologies; native support for Fabric IQ ontologies and Power BI semantic models on the roadmap. Early partners: EY, S&P Global, TomTom (geospatial/transportation data products discoverable in the OneLake catalog), Financial Fabric, xMentium.
- **Salesforce Data Cloud 360 bidirectional integration — Preview.** Salesforce data joins the unified estate without moving/duplicating it, available as business context for Fabric data agents.
- **Google BigQuery mirroring — GA.**
- **Dynamics 365 Business Central mirroring — Coming soon** (selected tables and companies into OneLake).
- **Ecosystem additions:** Atlan, dbt, ClickHouse, lakeFS.
- **OneLake Table Read API — Preview** (Iceberg/Delta access for external engines).
- **Catalog federation** (Salesforce, AWS Glue, GCP catalogs), **Policy Engine**, **OneLake Catalog lineage — Private preview** (OpenLineage-based).
- OneLake Outbound Access Protection with external shortcuts — GA; new OneLake security UX — GA.

## 5. Data Factory

**Deep dives**
- *FabCon/SQLCon Barcelona 2026: What's new in Fabric Data Factory* — Faisal Mohamood  
  https://community.fabric.microsoft.com/blog/fbc_fabricupdatesblogs/fabconsqlcon-barcelona-2026-what%E2%80%99s-new-in-fabric-data-factory/5369551
- *Modernize your Azure Data Estate with Microsoft Fabric: A guided path from Azure Data Factory and Azure Synapse* — Faisal Mohamood (listed on the Fabric Updates Blog: https://community.fabric.microsoft.com/category/fabricupdatesblogs/blog/fbc_fabricupdatesblogs)

**Announcements**
- **45+ new capabilities** across sources, replication governance, destinations, pipeline resilience, monitoring and AI assistance.
- **Mirroring for Google BigQuery — GA**; **Mirroring for SharePoint Lists — GA**; **Mirroring for Dynamics 365 Business Central — Coming soon**.
- **Extended capabilities in Mirroring — GA**, including Change Data Feeds.
- **Mirroring for Snowflake: replication of security policies/roles into OneLake** — governance context travels with the data.
- **Open Mirroring** partner ecosystem continues to grow.
- Multicloud, petabyte-scale data distribution (to other clouds, partners, customers' environments).
- **dbt Job — GA**; new data destinations; more resilient pipelines; richer monitoring; Copilot across the end-to-end experience.
- Upcoming changes to legacy Teams and Outlook activities in pipelines; On-premises data gateway September 2026 release.

## 6. Data Engineering, Data Warehouse & Data Science

(Details in Bogdan Crivat's post — section 1 — and the Fabric September 2026 Feature Summary.)

- **Data engineering agent (Project Osmos) — Preview.** Built on technology from Microsoft's acquisition of Osmos. Governed, autonomous execution of long-running initiatives: data platform migrations, lakehouse modernization, performance optimization, complex ETL and data preparation. Engineers set outcomes and guardrails; agents plan, execute, validate and refine. Tasks inherit workspace permissions for collaborative work. Works from Fabric, GitHub Copilot, Visual Studio Code, Codex and Claude Code.
- **GPU-accelerated query execution in Fabric Data Warehouse — Preview.**
- **Spark Runtime 2.0** (Spark 4.0, Delta 4.0); **Materialized Lake Views — GA**.
- Data Engineering: Custom Live Pools — GA; Native JSON acceleration in the Native Execution Engine — Preview; Notebook toolkit for agentic development — Preview; Codex/Claude Code integration in the VS Code extension; Spark connector for SQL databases — GA.
- Data Warehouse: Custom SQL pools — GA; Statement Type classifier — GA; Distributed Bitmap Filters — GA; Teradata Migration Assistant — Preview; pre/post deployment support — Preview; SQL DW operations skill — GA; SQL query editor enhancements — GA.
- Data Science: Spark 4.1 for ML endpoints — Preview; tensor-based models on endpoints — Preview.

## 7. Real-Time Intelligence

(Yitzhak Kesselman's post — link in section 1.)

- **Copilot creation of Real-Time Dashboards — Preview**: describe what you want to understand and Copilot builds the dashboard.
- **Copilot for eventhouse management**: creating tables, configuring policies, managing schema, inspecting cluster state.
- **Schema recommendations and optimisation** to improve performance and reduce cost; **operations agent** root-cause analysis and actionable recommendations.
- **Business Events — GA**; Fabric Event Schemaset & Schema Registry — GA; schema-aware Eventstreams — Preview; Eventstream Custom Stream Connector — Preview; workspace private link for Eventstream — Preview.
- Real-Time Dashboards with Ontology as a source — Preview; AI-native custom visual builder — Preview.
- Activator: manage rules from Real-Time hub and OneLake catalog — Preview; trigger Copy job as an action — GA; capacity alert templates — GA.

## 8. Platform, governance, observability & billing

**Deep dive**
- *Build, deploy, and govern Microsoft Fabric at scale* — Kim Manis  
  https://community.fabric.microsoft.com/blog/fbc_fabricupdatesblogs/build-deploy-and-govern-microsoft-fabric-at-scale/5369145

**Announcements**
- **Observability in Fabric — Preview.** Spans workspace monitoring, the monitor hub and operations agents for a unified view of the Fabric estate.
  - **Unified workspace monitoring:** consolidate telemetry from multiple workspaces into a single Eventhouse; custom endpoints for other destinations; control retention and caching policy.
  - **Refreshed Monitor Hub:** deeper visibility into jobs, capacities and workloads; built-in views, alerts and AI-powered insights; new capacity view for consumption and headroom.
  - **Activator-powered job alerts** for job failures and successes.
  - **Operations agents** with autonomous investigation: root causes and recommended actions.
- **On-demand billing — Coming soon.** Consumption-based billing across Fabric workloads (building on Autoscale Billing for Spark); pay only for compute used, auto-scaling up and down.
- **Fabric zero-provisioned (F0) — Coming soon.** Start with Fabric and OneLake without an upfront capacity commitment.
- **Policies in Fabric — Preview**; **DLP policies for sensitive data — GA**; **Fabric CI/CD Deployment Plan — Preview**; **Fabric Core MCP Server — GA**.
- Git integration: Branch workspace — GA; selective branching — GA; compare & commit — GA; file-level commit — Preview; bulk export/import API — GA.
- New Global Search; improved OneLake Catalog Search API — Preview; Networking Communication Policies Admin API — GA.
- **Microsoft Fabric expanding to Microsoft 365 GCC High** (US sovereign cloud).

## 9. SQLCon — databases

**Deep dives**
- *SQLCon Barcelona 2026: Advancing SQL with greater control, scale, and intelligence* — Shireesh Thota  
  https://www.microsoft.com/en-us/sql-server/blog/2026/09/28/sqlcon-barcelona-2026-advancing-sql-with-greater-control-scale-and-intelligence/
- *Connecting apps, databases, and AI on one foundation: new innovations at SQLCon and FabCon EU 2026* — Shireesh Thota (Fabric Updates Blog: https://community.fabric.microsoft.com/category/fabricupdatesblogs/blog/fbc_fabricupdatesblogs)
- Pre-event: *What's next for SQL? Performance, scale, AI and developer productivity at the European SQL Community Conference* — Priya Sathy  
  https://www.microsoft.com/en-us/sql-server/blog/2026/08/13/whats-next-for-sql-performance-scale-ai-and-developer-productivity-at-the-european-sql-community-conference/

**Announcements**
- **Database Hub in Fabric — Preview.** Centralized control plane for SQL Server, Azure SQL, PostgreSQL, Azure Cosmos DB and SQL database in Fabric: monitor health, assess risk, enforce governance, estate-wide visibility.
- **Database agents for SQL and PostgreSQL on Azure — Preview soon.** AI specialist agents in Database Hub and VS Code that observe database signals, investigate issues, find bottlenecks and optimisation opportunities.
- **Azure SQL Database Hyperscale:**
  - 160 and 192 vCore Premium-series compute — GA
  - Serverless auto-pause (scale to zero) — Preview
  - Higher-density elastic pools, up to 50 databases per pool — Preview
  - New Azure Arc migration experience — Preview
- **DiskANN vector indexes — GA** for Azure SQL Database Hyperscale, Azure SQL Managed Instance and SQL database in Fabric, with full DML support — build recommendation engines, semantic search and RAG without a separate vector store.
- **Sovereign / edge:** SQL Server on Azure Local — GA; SQL Server on Azure Local Disconnected Operations (ALDO) — GA; Foundry Local on Azure Local — Preview.
- **Customer story:** SAP Commerce Cloud — 6,000+ databases migrated to Hyperscale; $17.8B processed on Black Friday at 100% uptime.

---

## Community & third-party recaps

- Solv Systems — announcements grouped by GA / Preview / Coming soon: https://solv-systems.com/resources/fabcon-europe-2026-recap
- Fabric Weekly #12 (FabCon week round-up): https://fabricweekly.info/latest/
- Power BI Weekly #377 (2 Oct 2026): https://powerbiweekly.info/issue-377
- Awesome Microsoft Fabric — curated FabCon & SQLCon Europe 2026 section: https://github.com/bhakthan/awesome-microsoft-fabric
- Microsoft Fabric Community — Fabric Updates Blog: https://community.fabric.microsoft.com/category/fabricupdatesblogs/blog/fbc_fabricupdatesblogs
- Microsoft Fabric Community — Power BI Updates Blog: https://community.fabric.microsoft.com/category/fabricupdatesblogs/blog/fbc_pbiupdatesblog

## Partner blogs referenced in the keynote post

- Emergent Software — Microsoft IQ Explained: How Microsoft Is Building Context for AI Agents
- Acuvate — Microsoft Fabric IQ Ontology for Enterprise AI Agents; Scaling Enterprise AI: Data, Governance, Real-Time Intelligence & More
- Bismart — Fabric IQ in Microsoft Fabric: Semantic Layer for Artificial Intelligence
- Element61 — Fabric IQ: When your Data needs to speak Business

---

## What's next

- **Microsoft Ignite** — San Francisco, 17–20 November 2026.
- Fabric Roadmap, Fabric SKU Estimator and the Fabric free trial are linked from the keynote hero blog above.

*Compiled 5 October 2026 from Microsoft's public FabCon/SQLCon Europe 2026 announcements.*
