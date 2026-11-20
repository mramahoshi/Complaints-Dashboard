# Customer Complaints Dashboard (Power BI)

An interactive Power BI dashboard analysing customer complaints data from **January to July 2026**. It was my first dashboard built end to end: data import, cleaning in Power Query, DAX measures and report visuals.

![Dashboard overview](screenshots/dashboard-overview.png)

## Business questions
- How many complaints are received each month, and is the trend rising or falling?
- Which complaint categories drive the most volume?
- How quickly are complaints resolved?
- *(add your own questions)*

## Key insights
- *(add insight 1, e.g. "Category X accounts for N% of all complaints")*
- *(add insight 2)*
- *(add insight 3)*

## Tools
Power BI Desktop · Power Query (M) · DAX · Excel (source data)

## Workflow
1. **Import**: Excel source file loaded into Power BI
2. **Clean**: Power Query steps (data types, nulls, duplicates, standardised text)
3. **Model**: tables and relationships (see [data dictionary](docs/data-dictionary.md))
4. **Measure**: DAX measures (see [DAX measures](docs/dax-measures.md))
5. **Visualise**: report pages and visuals (see [report guide](docs/report-guide.md))

## Repository structure
```
complaints-dashboard/
├── README.md
├── pbix/            # Power BI file (.pbix)
├── data/            # Sample or anonymised data only
├── docs/            # Data dictionary, DAX measures, report guide
└── screenshots/     # Dashboard images used in docs
```

## Data and privacy
The data in this repo is **sample/anonymised**. Do not upload real customer or employer data.

## How to use
1. Download the `.pbix` file from `/pbix`
2. Open in Power BI Desktop
3. If prompted, point the data source to `/data/complaints-sample.xlsx`

## Author
**Eunice** · Data analyst and cloud administrator in training
