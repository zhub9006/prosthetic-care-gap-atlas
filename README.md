# Prosthetic Care Gap Atlas

An open-access resource mapping prosthetic and orthotic care access across underserved regions of the United States, combined with ClinicalTrials.gov research trends.

> **Note:** The originally requested repository name `prosthetic-access-atlas` was already taken on this account. This repo (`prosthetic-care-gap-atlas`) contains the full compiled analysis.

## Mission

Identify coverage gaps in prosthetic and orthotic care by cross-referencing:
1. **Clinical trial landscape** — current and historical prosthetic/orthotic research from ClinicalTrials.gov
2. **Provider mapping** — geospatial analysis of specialist providers in three historically underserved regions
3. **Coverage gap analysis** — quantitative assessment of accessibility deficits

## Regions Under Analysis

| Region | Center Coordinates | Key Cities | Bounding Box |
|--------|-------------------|------------|--------------|
| Rural West Virginia | 38.48°N, 80.84°W | Charleston, Huntington, Parkersburg | 37.2–40.6°N, 82.6–77.7°W |
| Appalachian Kentucky | 37.25°N, 83.20°W | Hazard, Pikeville, Middlesboro | 36.9–38.0°N, 84.5–82.2°W |
| Mississippi Delta | 33.41°N, 91.06°W | Greenville, Clarksdale, Jackson | 33.0–35.0°N, 92.0–88.0°W |

## Key Findings (Preliminary)

- **2,169 prosthetic-related clinical trials** identified on ClinicalTrials.gov
- **Zero prosthetist/orthotist specialists** found via OpenStreetMap in any of the three target regions
- Healthcare infrastructure in all three regions is dominated by **pharmacies and general clinics**, with no dedicated prosthetic/orthotic providers
- The United States accounts for the vast majority of global prosthetic trials (2,383 of 4,500+ total), yet access within underserved US regions remains critically low
- **Rehabilitation services are extremely sparse**: only 2-3 general clinics per region, no dedicated amputee rehabilitation centers

## Data Sources

- [ClinicalTrials.gov API](https://clinicaltrials.gov/) — trial listings and trend analysis
- [OpenStreetMap](https://www.openstreetmap.org/) — provider and facility geodata

## Repository Structure

```
├── README.md                  # This file
├── clinical-trials/
│   ├── trend-analysis.md      # Status and country trend breakdowns
│   ├── recent-trials.md       # Sample recent prosthetic trials
│   └── trial-data.json        # Raw clinical trial trend data
├── coverage-gaps/
│   ├── gap-analysis.md        # Detailed coverage gap report
│   ├── provider-maps/         # Per-region provider inventories
│   │   ├── west-virginia.md
│   │   ├── appalachian-kentucky.md
│   │   └── mississippi-delta.md
│   └── gap-data.json          # Raw geospatial gap data
└── recommendations.md         # Actionable recommendations
```

## Contributing

This is an open-access project. Pull requests welcome for:
- Expanded provider searches (DMLO, prosthetist, orthotist directories)
- Additional underserved regions
- Updated trial data
- Visualizations and interactive maps

## License

Open Data — see LICENSE file.
