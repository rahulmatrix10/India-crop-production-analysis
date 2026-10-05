# India Crop Production Analysis (1997-2021)

Excel-only analysis of 345,407 records covering 57 crops across 36 Indian states/UTs over 24 crop years, using Power Query, Pivot Tables, and Pivot Charts.

![Dashboard](dashboard.png)

## Dataset
India Agriculture Crop Production dataset (government-sourced, via Kaggle). Columns: State, District, Crop, Year, Season, Area, Production, Yield.

## Key findings
- Production is recorded in three incompatible units (Tonnes, Bales for cotton/jute, Nuts for coconut/arecanut). Any total or "average yield" figure must be split by unit first — combining them produces meaningless numbers (an early version of this analysis showed Puducherry with an inflated "top yield" purely because of mixed units).
- The dataset includes one aggregate row ("Oilseeds total") alongside individual oilseed crops, which was excluded from crop-level rankings to avoid double-counting.
- 2020-21 shows an artificial drop in total area, consistent with incomplete data collection for the final year rather than a real decline, and was excluded from the trend chart.
- [Add 1-2 more once you finalize: top crop by area, top state by yield-in-Tonnes, etc.]

## Tools
Excel (Power Query, Pivot Tables, Pivot Charts, slicers)


## Full Excel workbook available on request (not included here due to file size).

