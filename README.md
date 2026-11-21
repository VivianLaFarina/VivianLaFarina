<p align="center">
  <picture>
    <source media="(prefers-reduced-motion: reduce)" srcset="./signal-cover-balance-static.png" />
    <img src="./signal-cover-balance.gif" width="1080" alt="Vivian La Farina | IT Data Project Lead. White waves with an orange accent break into particles that assemble the name." />
  </picture>
</p>

<table>
  <tr>
    <td width="61%" valign="middle">
      <h1>Vivian La Farina</h1>
      <p><strong>IT Data Project Lead | SAP Master Data & Global Supply Chain</strong></p>
      <p>I lead supplier and purchasing data initiatives in medtech across the <strong>Americas, EMEA, and APAC</strong>. I work with regional business teams and global engineering teams to turn data quality issues into requirements, coordinate validation, and prepare changes for release.</p>
    </td>
    <td width="39%" valign="middle" align="center">
      <picture>
        <source media="(prefers-reduced-motion: reduce)" srcset="./data-cubes-balance-static.png" />
        <img src="./data-cubes-balance.gif" width="350" alt="Scattered data cubes assemble into layers and disperse again." />
      </picture>
    </td>
  </tr>
</table>

[Selected work](#selected-work) · [Supplier data lab](#supplier-master-data-lab) · [LinkedIn](https://www.linkedin.com/in/vivianlafarina/) · [Portfolio](https://vivianlf.netlify.app/)

## Selected work

### SAP purchasing data quality | Price-date controls

I coordinate remediation of SAP purchasing data where date controls affect which price is used. My role spans regional requirements, architecture reviews, user acceptance testing, and release handoffs. The validation question is concrete: does SAP select the intended price for the relevant purchasing date?

### Portfolio governance | Global delivery

- Contributed to **40+ delivered projects** across my career, with impact in Colombia and internationally.
- Oversee Planisware project updates for **15 data professionals**, surfacing milestones, dependencies, and risks that need escalation.
- Led onboarding for **50 professionals** across disciplines, coordinating role-specific system access and helping resolve setup blockers.

Based in Bogotá, Colombia. I travel for work.

<picture>
  <source media="(prefers-reduced-motion: reduce)" srcset="./delivery-maps-balance-static.png" />
  <img src="./delivery-maps-balance.gif" width="1000" alt="An orange scan moves down three regional maps: the Americas; Europe, Middle East and Africa (EMEA); and Asia-Pacific (APAC)." />
</picture>

## Supplier Master Data Lab

**Portfolio prototype · Python, SQL, SQLite · Synthetic ERP data**

Two ERP systems can list the same supplier under different names and IDs. A false merge can be harder to unwind than a duplicate, so the prototype matches on **country + normalized tax ID**, never on name alone. It retains the source IDs for traceability and routes missing identifiers or conflicting entity types to a review queue.

<picture>
  <source media="(prefers-reduced-motion: reduce)" srcset="./supplier-ascii-balance-static.png" />
  <img src="./supplier-ascii-balance.gif" width="1000" alt="Four synthetic source rows produce two canonical suppliers and one review case, with traceability for all source rows." />
</picture>

| What the prototype checks | What the test demonstrates |
| :--- | :--- |
| **Match boundaries** | The same tax ID in two countries does not merge those suppliers. |
| **Traceability** | The sample produces two canonical suppliers and one review case; all four source rows are accounted for. |
| **Repeatability** | Rerunning the same input produces identical export files. |

## Tools & platforms

<picture>
  <source media="(prefers-reduced-motion: reduce)" srcset="./technology-stack-balance-static.png" />
  <img src="./technology-stack-balance.gif" width="1000" alt="Technologies grouped by delivery and governance, data and analytics, and cloud learning." />
</picture>

**Delivery and governance:** Planisware, Jira, Confluence · **Enterprise data and analytics:** SAP master data, SQL, Power BI · **Cloud learning:** Azure, Snowflake, Microsoft Fabric

<!-- Technology marks identify their respective products. Artwork: Simple Icons, Devicon, Planisware, and Microsoft Learn. -->

<!-- Schematic regional map artwork made with Natural Earth. -->

## Supply chain

<picture>
  <source media="(prefers-reduced-motion: reduce)" srcset="./supply-chain-flow-wide-static.png" />
  <img src="./supply-chain-flow-wide.gif" width="1060" alt="Supply chain in motion: an orange package moves from purchase order to warehouse, transit, and delivery. Each active stop lights up yellow." />
</picture>

**Purchase order** → **Warehouse** → **Transit** → **Delivery**
