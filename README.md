# netflix-king-of-streaming-dataviz
Comparative analysis of Netflix vs. Disney+, Prime Video, and Hulu. Used Power BI (Power Query) to clean/join four Kaggle catalogs into a snowflake model; built Power BI/Tableau dashboards with DAX and KPI reporting; final deliverable: one-page infographic with trend &amp; competitive insights.

# Netflix vs. Competitors — Data Visualization (Power BI & Tableau)

**Purpose.** Explain *how Netflix became the “king of streaming”* using comparative, business-facing visuals. The project merges and models four streaming catalogs, then visualizes KPIs across subscribers, catalog/genres, geography, and awards to tell a clear story for decision-makers.

---

## Business questions
1) Who leads by **subscribers** and how fast is that changing?  
2) How do platforms compare by **catalog size**, **genre breadth**, and **geographic coverage**?  
3) Do **awards** (Emmys/Globes/Oscars) correlate with leadership?  
4) Where are the **growth opportunities** (audience segments, regions, content types)?

---

## Data sources (public)
- Kaggle title catalogs for **Netflix, Disney+, Prime Video, Hulu** (same schema).  
- External reference stats for **subscribers, time spent, demographics, awards** (cited in the infographic/slides).  
  *(See “Report/Slides” for full citations.)*

---

## Preparation (Power BI – Power Query)
- Imported 4 CSV catalogs → **standardized** column names/types.  
- **Merged & deduplicated** titles; normalized **genres**; derived counts by service/genre/country.  
- Built a **snowflake model** (fact + dimensions) to support flexible slicing.  
- Created calculated fields for KPI reporting (titles by service, genres/service, countries/service).

---

## Tools
- **Power BI** (Power Query, DAX) for modeling & dashboards  
- **Tableau** for comparative visuals and final layout options

---

## KPIs / Metrics
Subscribers • Titles (catalog size) • **Genres** (breadth) • **Countries** (coverage) • Major **awards** (wins/nominations)

---

## Visuals included
Bar/line trends • Bubble & radar comparisons • Gauges/KPI cards • Geographic coverage maps (where supported)

---

## Key findings (examples)
- Netflix holds the **largest subscriber base (~260M)** vs. Prime (~200M), Disney+ (~150M), Hulu (~48M). :contentReference[oaicite:0]{index=0}  
- Netflix shows the **largest library (~8,000 titles)**, **~115 genres**, and content from **~119 countries**. :contentReference[oaicite:1]{index=1}  
- Awards leadership: hundreds of major nominations/wins (Emmys, Globes, Oscars), supporting its premium slate strategy. :contentReference[oaicite:2]{index=2}

*(Numbers reflect the sources summarized in the submitted infographic and slides.)*

---

## Recommendations
- **Youth expansion:** increase targeted youth/teen slates to balance adult-skewed catalog. :contentReference[oaicite:3]{index=3}  
- **Regional growth:** invest in under-represented regions (e.g., Africa/Middle East) to extend country coverage. :contentReference[oaicite:4]{index=4}  
- **Originals & awards:** continue outsized investment in originals that drive awards and brand prestige. :contentReference[oaicite:5]{index=5}

---
