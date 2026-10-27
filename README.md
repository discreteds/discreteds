# Nathaniel Ramm

**Software and data engineer · Data scientist · Melbourne, Australia**

[![Email](https://img.shields.io/badge/Email-nathaniel%40mountainash.io-red?logo=protonmail&style=flat-square)](mailto:nathaniel@mountainash.io)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-nathaniel--ramm-blue?logo=linkedin&style=flat-square)](https://linkedin.com/in/nathaniel-ramm)
[![Kaggle](https://img.shields.io/badge/Kaggle-rambeaux-20BEFF?logo=kaggle&style=flat-square)](https://kaggle.com/rambeaux)

---

## About

I'm a software and data engineer and data scientist with 20+ years in Australian financial services. Most of that time I've worked inside the business units that own the problem, building the systems they need with them rather than for them.

At NAB I led the enterprise data-science function, run as an internal consultancy across retail, business, digital and financial crime, and before that the Risk division's data-governance team. Earlier roles took me through retail credit risk: decision strategy, independent model validation, model performance monitoring and Basel II methodology.

As an independent consultant since 2014:

- **Credit stress testing:** principal engineer and architect of NAB's whole-of-bank engine. I decomposed the legacy SAS system into a traceable backlog and rebuilt it as a modular R and Spark pipeline, cutting a two-week process to two hours.
- **Home-lending pricing:** principal engineer of a rules engine that cut pricing changes from a week to an hour, then business analyst and product owner for its migration to FICO's price-optimisation platform.
- **Credit-bureau reporting:** a dbt medallion pipeline reporting to all three Australian credit bureaux under ACRDS, embedded in a non-bank lender's credit risk team.

Now I'm building Mountain Ash, an open-source Python data stack, and applying agentic engineering to regulatory data processes.

---

## Mountain Ash

**[github.com/mountainash-io](https://github.com/mountainash-io)** · docs at **[docs.mountainash.io](https://docs.mountainash.io)**

A composable Python data engineering ecosystem. Expressions, rules, validation, schema conformance and pipelines are built once against a single expression algebra, then run on Polars, pandas, DuckDB and the other backends reachable through Ibis and Narwhals.

> **Status: under active development, not production ready.** None of the packages are on PyPI yet, and APIs can change without notice.

| Package | Intent |
|---|---|
| [mountainash](https://github.com/mountainash-io/mountainash) | Cross-backend expressions and relational plans, in Polars-style syntax, compiled to the selected backend. |
| [mountainash-data](https://github.com/mountainash-io/mountainash-data) | One connection interface for analytical backends: relational databases through Ibis, Iceberg catalogs through PyIceberg. |
| [mountainash-settings](https://github.com/mountainash-io/mountainash-settings) | Typed configuration: layered YAML, TOML, JSON and environment variables, template resolution and Pydantic integration. |
| [mountainash-rules](https://github.com/mountainash-io/mountainash-rules) | Metadata-driven business rules engine: decision tables ranked by specificity, evaluated in one vectorised pass, with per-rule explainability. |
| [mountainash-rules-babel](https://github.com/mountainash-io/mountainash-rules-babel) | Translation of rule sets between formats, such as CSV and DMN. |
| [mountainash-structuremap](https://github.com/mountainash-io/mountainash-structuremap) | Declarative, bidirectional transformation between hierarchical payloads (XML, JSON) and relational tables. |
| [mountainash-transport](https://github.com/mountainash-io/mountainash-transport) | Storage abstraction with one interface across local and cloud object stores. |
| [mountainash-secrets](https://github.com/mountainash-io/mountainash-secrets) | Capability-graded secret-store protocols with pluggable stores and an injected resolver. |
| [mountainash-pipelines](https://github.com/mountainash-io/mountainash-pipelines) | Generic pipeline protocols with predicate pushdown. |
| [mountainash-resource-provider](https://github.com/mountainash-io/mountainash-resource-provider) | Neutral resource-provider contracts shared across packages. |

---

## Professional journey

| Years | Role | Organisation |
| --- | --- | --- |
| 2014 – Present | Fractional Consultant, Engineer, Data Scientist | Discrete Data Science |
| 2022 – 2023 | Head of Data Science | National Australia Bank |
| 2021 – 2022 | Head of Risk Data | National Australia Bank |
| 2020 – 2021 | Associate Director, Optimisation - Stress Testing and Models | National Australia Bank |
| 2013 – 2016 | Founder, Data Scientist, Engineer | Pulse Data Science |
| 2010 – 2013 | Senior Manager, Strategic Analytics | National Australia Bank |
| 2009 – 2010 | Senior Manager - Model Performance | National Australia Bank |
| 2008 – 2009 | Manager Retail Model Validation, Group Retail Credit | National Australia Bank |
| 2006 – 2008 | Decision Strategy Analyst, Consumer Lending | National Australia Bank |
| 2002 – 2006 | Fraud Analyst / Intranet Developer, Consumer Credit Cards | National Australia Bank |

Full history at [linkedin.com/in/nathaniel-ramm](https://linkedin.com/in/nathaniel-ramm).

---

## Technical skills

| Category | Tools |
| --- | --- |
| **Languages** | Python, R, SQL, Java |
| **AI / LLM** | Agentic coding (Claude, Codex, Cursor, open-weight models), spec-driven SDLC, MCP, CLI and API development and integrations, multi-agent workflows and automation |
| **ML / Statistics** | Logistic regression and tree-based models, credit scorecards, Monte-Carlo simulation, champion–challenger experiments and impact analysis, model performance monitoring metrics and visualisation |
| **Modern data stack** | Polars, DuckDB, Ibis, Apache Spark, dbt, Snowflake, Databricks, Redshift, Iceberg, Parquet/Arrow |
| **Domain** | Credit risk models (Basel II PD, EAD, LGD; IFRS 9; application and behavioural scorecards), home lending and credit cards, pricing engines and optimisation, credit-bureau reporting data (CCR and ACRDS), data governance and data quality |
| **Legacy / enterprise** | Teradata, SQL Server, Oracle, SAS, mainframe (SAS, JCL) |

---

## Kaggle

- **Give Me Some Credit, 1st place** (2011), with team Perfect Storm, ~1,000 teams
- **Follow the Money, winner** (2012), a data-journalism challenge
- **Peak global rank 21st** (historical), [kaggle.com/rambeaux](https://kaggle.com/rambeaux)

---

If you have a data, risk or AI problem that needs an engineer working alongside the team that owns it, get in touch on [LinkedIn](https://linkedin.com/in/nathaniel-ramm) or by [email](mailto:nathaniel@mountainash.io).
