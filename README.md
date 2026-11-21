<h1 align="center">Hi, I’m Vivian La Farina 👋</h1>

<p align="center">
  <strong>IT Data Project Lead · Global Supply Chain Data Programs</strong>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/vivianlafarina/"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge" /></a>
  <a href="https://vivianlf.netlify.app/"><img alt="Portfolio" src="https://img.shields.io/badge/Portfolio-6940A5?style=for-the-badge" /></a>
</p>

> I lead enterprise data projects that impact supply chain operations across the Americas, EMEA, and APAC. I bring regional business teams and global engineering teams together to deliver SAP master data, data quality, and governance initiatives, adapting global standards to regional needs.

## 🌎 What I lead

| Global program delivery | Supply chain data | Architecture & governance |
| :--- | :--- | :--- |
| Cross-regional workstreams, dependencies, and delivery risks | Supplier and purchasing master data, standardization, and data quality | Architecture reviews, integration planning, and data governance |

## 🚧 Now building: Supplier Master Data Platform

**The problem:** Two ERP systems can list the same supplier under different names and IDs. How do we consolidate those records without merging the wrong companies?

**The design decision:** Group records by a valid tax ID in the demo dataset. When a tax ID is missing or invalid, send the record for manual review instead of guessing from the supplier name. Keep the original source and ID so the result can be traced back.

```mermaid
flowchart LR
    A["ERP A"] --> C["Standardize records"]
    B["ERP B"] --> C
    C --> D{"Tax ID present and valid?"}
    D -->|Yes| E["Group by tax ID"]
    E --> F["Supplier master"]
    D -->|No| G["Manual review queue"]
```

**Status:** In development · Synthetic data only  
**Planned stack:** Python · SQL · DuckDB  
**First test:** Reload the same file and verify that no new supplier records are created.

<details>
<summary><strong>🛠 Tools and platforms</strong></summary>

- **Enterprise data and analytics:** SAP/MDG, SQL, Power BI
- **Cloud data platforms:** Azure, Snowflake, Microsoft Fabric
- **Program delivery:** Planisware, Jira, Confluence

</details>
