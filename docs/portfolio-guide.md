# Portfolio Guide

[Back to portfolio](../README.md)

## Repository layout

```
Power-BI-Reports/
├── README.md                              Portfolio landing page
├── dashboards/
│   ├── business-performance-tracking/     Business Updates Snapshot V1 and V2
│   ├── operational-performance/           Executive KPI report (3 pages)
│   └── loan-collections-analytics/        Individual Loan Dashboard
└── docs/
    ├── portfolio-guide.md                 This file
    └── technical-skills.md                What the dashboards evidence
```

Each project folder has its own README and an `images/` folder.

## Assets available

| Project | Screenshots | PDF export | PBIX | Source data |
|---|---|---|---|---|
| Business Updates Snapshot | Yes (V1 PNG, V2 JPG) | No | No | No |
| Operational Performance Dashboard | Yes (3 pages, rendered from the PDF) | Yes | No | No |
| Individual Loan Dashboard | Yes (rendered from the PDF) | Yes | No | No |

The PNG previews for the two PDF-based projects were rendered directly from the PDF pages without editing. The dashboards are not available as interactive online reports.

## Viewing the dashboards

- Click any preview image in a README to open it at full size.
- Open the PDF exports from the project folders; GitHub displays them in the browser.

## Naming conventions

Lowercase, hyphen-separated, descriptive: `<project>-<page-or-version>.<ext>`.

## Adding a new dashboard

1. Create `dashboards/<domain>/` with an `images/` subfolder, reusing an existing domain folder if it fits.
2. Add the image with a descriptive lowercase filename.
3. Copy an existing project README and update it using only what is visible or confirmed.
4. Add the project to the root README (table and gallery section).

## Terms on the dashboards

Standard terms: AUM (assets under management), NPA (non-performing asset), SMA (special mention account), DPD (days past due), NACH (National Automated Clearing House), UPI (Unified Payments Interface), EMI (equated monthly instalment), POS (principal outstanding), O/s (outstanding).

Other abbreviations, such as HM, ATS, CE %, RO, IGL and IL, are shown as labelled on the original dashboards.
