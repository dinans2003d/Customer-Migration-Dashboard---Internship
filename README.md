# Customer Migration Status – Power BI Dashboard (2023–2025)

## Business Impact
I built an enterprise migration tracking dashboard for Kaiser Permanente to monitor the progress, readiness, and data completeness of analytics application migrations across multiple business units. Leadership needed end-to-end visibility into:
- Which applications were successfully migrating
- Where delays and data gaps were occurring
- Which accountable owners required follow-up
- Readiness across target migration years (2023–2025)

By surfacing real-time data completeness, migration status, ownership, and risk conditions, the dashboard enables:
- Faster escalation to business owners
- Earlier detection of data blockers
- Reduction in failed or delayed migrations
- Efficient portfolio-level planning and resource allocation

The dashboard replaces static spreadsheets and manual reporting and now centralizes migration health signals in a single, filterable view.  

## Project Objective
Track and visualize application migration progress by:
- Migration status (not started, in progress, completed, decommissioned)
- Migrating platform (Tableau, Business Objects, Cognos)
- Data completeness
- Target rationalization year
- Ownership and accountable entities
- Migration risk/readiness levels

## Data Sources
The dashboard analyzes the full migration inventory provided by Kaiser leadership. Each row represents an application/site and includes:
- Platform being migrated from
- Field completion percentage
- Migration readiness status
- Size (T-shirt sizing)
- Owning entity and contact details
- Target migration year

(See dashboard visuals on pages 1–3 of the project PDF) :contentReference[oaicite:0]{index=0}  

## Power BI + DAX Work
I modeled the dataset and built custom DAX measures to:
- Calculate missing field counts
- Compute missing field percentage across groups
- Aggregate readiness levels dynamically by slicer selection
- Count total migration groups by platform
- Track migration completion vs. target timelines

Examples of calculated KPIs represented in DAX:
- Missing Data Count
- Missing Data Percent
- Migration Readiness Count by T-shirt sizing
- Total Groups by Completion Bucket
- Completion % by entity and source platform

## Key Visuals
The dashboard contains multiple linked report pages:
- Migration Status Overview (page 1)
- Migration Group Details (page 2)
- Full Inventory Table (page 3)

Displayed metrics and visuals include:
- Total Groups + Missing Data KPI tiles
- Migration funnel by status
- Group counts by platform
- Ownership by year
- Field completion progress bars
- Missing data by accountable contact
- Readiness level segmentation
- Inventory table with conditional formatting

## Key Insights Delivered
- Majority of missing-data risk concentrated in Tableau migrations  
- Large migrations had disproportionately lower readiness scores  
- >80% missing field rate surfaced across multiple groups  
- Field completion correlated with delayed timelines  
- Readiness blockers traceable to specific owning entities and contacts  

## Outcome
This dashboard gives executives and migration leads a centralized system to:
- Prioritize highest-risk migrations
- Validate ownership and accountability
- Monitor readiness trends over time
- Accelerate planning and execution

The work demonstrates end-to-end experience in:
- Power BI data modeling
- DAX calculations for KPI design
- Executive-level dashboard development
- Enterprise migration use cases
- Operational analytics for large organizations
