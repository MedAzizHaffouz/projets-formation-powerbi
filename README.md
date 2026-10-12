# Power BI Training Projects

A collection of four end-to-end Power BI dashboards built during a Power BI training course. Each project goes from raw data (Excel / CSV) to an interactive, multi-visual report: data import and cleaning in Power Query, a relational data model, DAX measures, and a designed report layout with slicers and navigation.

## Projects

| # | Project | Domain | Data | Highlights |
|---|---------|--------|------|------------|
| 1 | [COVID Dashboard](./COVID%20dashboard) | Public health | Our World in Data COVID-19 dataset (72k+ rows, 59 columns) | World vs. Tunisia view, mortality and test-positivity KPIs, continent and country rankings, Tunisia vs. Belgium/Greece comparison |
| 2 | [Energy Consumption Dashboard](./Energy%20Consumptions) | Facilities / utilities | Monthly water, electricity and gas consumption for 11 US buildings (2016–2019) | 4 navigable pages, cost modelling from yearly unit rates, map, smart narrative, waterfall and treemap visuals |
| 3 | [HR Dashboard](./HR%20Analytics%20Data) | Human resources | IBM HR Analytics dataset (1,470 employees, 35 attributes) | Promotion and retrenchment flags, workforce demographics, custom side-panel navigation (Home / Detail / Action) |
| 4 | [Sales Dashboard](./Sales%20dashboard) | Sales | Daily sales transactions (6,490 rows) with product and employee master tables | Star-schema model, revenue by product / employee / supervisor, cross-filtering slicers, scrolling KPI ticker |

## Previews

| COVID | Energy |
|-------|--------|
| ![COVID](./COVID%20dashboard/Capture%20d'%C3%A9cran%202026-10-10%20233815.png) | ![Energy](./Energy%20Consumptions/Screenshot1.png) |

| HR | Sales |
|----|-------|
| ![HR](./HR%20Analytics%20Data/Screenshot1.png) | ![Sales](./Sales%20dashboard/Capture%20d'%C3%A9cran%202026-10-12%20171729.png) |

## Skills Covered

- **Power Query (M):** importing Excel/CSV sources, fixing data types, cleaning and reshaping tables
- **Data modelling:** fact and dimension tables, one-to-many relationships, star schema
- **DAX:** KPIs (totals, ratios, percentages), calculated columns for business rules, cost calculations joining usage to rate tables
- **Visualization:** cards, line/area/combo charts, donut and pie charts, maps, treemaps, waterfall charts, matrices, smart narratives
- **Report design:** custom backgrounds and layouts, page navigation with buttons and bookmarks, slicers and cross-filtering

## Repository Structure

```
projets-formation-powerbi/
├── COVID dashboard/        # OWID COVID-19 data, world + Tunisia report
├── Energy Consumptions/    # Building utility consumption & cost report
├── HR Analytics Data/      # Employee promotion / retrenchment report
└── Sales dashboard/        # Product & employee sales performance report
```

Each folder contains the `.pbix` report, its source dataset, screenshots, and a dedicated README.

## How to Open

1. Install [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free, Windows).
2. Clone the repository:
   ```bash
   git clone https://github.com/MedAzizHaffouz/projets-formation-powerbi.git
   ```
3. Open the `.pbix` file of any project.
4. If Power BI cannot find the data source, go to **Transform data → Data source settings → Change source** and point it to the dataset file in the same folder, then **Refresh**.

## Author

**Mohamed Aziz Haffouz** — [GitHub](https://github.com/MedAzizHaffouz)
