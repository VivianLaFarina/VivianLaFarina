<h1 align="center">Vivian La Farina 👋</h1>

<p align="center">
  <strong>IT Data Project Lead</strong><br>
  Global Supply Chain · Portfolio Governance · Data Architecture
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/vivianlafarina/"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge" /></a>
  <a href="https://vivianlf.netlify.app/"><img alt="Portfolio" src="https://img.shields.io/badge/Portfolio-7046B3?style=for-the-badge" /></a>
</p>

## 🌍 Global data delivery at a glance

| 🌐 Global reach | 📊 Planisware governance | 🤝 Onboarding |
| :--- | :--- | :--- |
| **Americas · EMEA · APAC** | **15 data professionals** | **50 professionals** |
| Regional teams impacted by the data projects I lead | I oversee updates to their projects in Planisware | I’ve led their onboarding across disciplines |

I lead enterprise data projects for global supply chain operations, bringing regional business teams and global engineering teams together to improve SAP master data, data quality, and governance. I’m based in Bogotá, Colombia, and travel as part of my work.

---

## 🧪 Architecture lab: Supplier Master Data Platform

> **Two ERP systems. Different supplier IDs. How do we tell which records belong to the same supplier?**

This portfolio project uses **synthetic data** to explore how to reconcile supplier records without merging the wrong companies.

```mermaid
flowchart LR
    A["ERP A"] --> C["Standardize records"]
    B["ERP B"] --> C
    C --> D{"Usable tax ID?"}
    D -->|Yes| E["Group by tax ID"]
    E --> F["Supplier master + source links"]
    D -->|No| G["Manual review queue"]
```

**My design decision:** In this demo, group records by tax ID, not by similar names. Preserve each source record ID so every consolidation can be traced back.

**Status:** In development · **Planned stack:** Python, SQL, DuckDB  
**First test:** Reload the same file and check that no supplier records, source links, or review entries are duplicated.

---

<details>
<summary><strong>🛠 Tools and platforms</strong></summary>

| Area | Tools |
| :--- | :--- |
| Portfolio delivery | Planisware, Jira, Confluence |
| Enterprise data & analytics | SAP/MDG, SQL, Power BI |
| Cloud data platforms | Azure, Snowflake, Microsoft Fabric |

</details>
