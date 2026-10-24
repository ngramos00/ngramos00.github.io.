# [Noah G. Ramos]
I'm currently studying Environmental Science at RCC and once transferred out focus on forest conservation. With GIS I get to learn and understand the mapping/layout of land throughout National Parks and how to properly track the areas I'd be covering.
---
## [Map 1 COVID-19 Cases/Rates]
 The map gives the viewer the layout of NYC and gives a description of areas within that have the highest COVID cases and rates <img width="2550" height="3300" alt="Disease Map png" src="https://github.com/user-attachments/assets/b48c56db-24ce-4c12-bafa-b17f2c06efd4" />

**Question:** [How does the spatial pattern of COVID-19 cases differ across New York City ZIP codes when you look at raw case counts versus case rates (and how does population density relate to those patterns)?]
**Data:** [COVID19_ZCTA, GGA_Admin, 2020, ArcGIS Online.]
**Method:** [I used the Portal tab to add the COVID19_ZCTA layer from ArcGIS Online, then checked the attribute table and Explore tool for case counts and rates. I symbolized the layers and built the layout with a Map Frame, Legend, North Arrow, Scale Bar, and Text.]
**A design choice I made and why:** [I used Graduated Symbols for case counts and Graduated Colors for the case rates so the two patterns could be compared side by side. Counts show raw volume with the symbol size, while rates use color to show intensity relative to population, making it easier to see that high-count areas are not always high rate areas.]
**A limitation of this map:** [The map cannot show when the cases occurred or how testing access varied across ZIP codes. A high rate could reflect either a real outbreak or simply better testing, and the map provides no information about timing or testing equity.]
## [Map 2 Enriched Redlining]
[HOLC redlining grades in Atlanta with 2024 household internet access] <img width="493" height="302" alt="Enriched map png" src="https://github.com/user-attachments/assets/e6422cec-a5e0-463f-87f3-ab83f095f43f" />
**Question:**How does the percentage of households without internet access vary across historical HOLC relining grades in Atlanta?
**Data:**Enriched Atlanta census tract data (ACS 5-Year estimates) joined to HOLC redlining grades (A-D). Key fields include 2024 HHs w/No internet Access (ACS 5-Yr) and HOLC grade.
**Method:**Created a box plot in ArcGIS pro using 2024 HH's w/NO Internet Access as the numeric field and HOLC grade as the category. Outliers were shown.
**A design choice I made and why:**I used a box plot instead of a choropleth so the distribution for each grade is visible side by side. This makes it easier to compare the spread of the internet access rates across A, B, C and D grades rather than just seeing average values on a map.
**A limitation of this map:**The data shows (2024) internet access rates overlaid on historical HOLC grades. It cannot establish whether lower access in lower grades is caused by the original redlining policies or other ongoing socioeconomic factors.
---
## Data sources
- [ACS 5-Year Estimates, U.S. Census Bureau, 2024, https://www.census.gov/programs-surveys/acs]
- [HOLC Redlining Maps, Mapping Inequality/University of Richmond, historical, https://dsl.richmond.edu/panorama/redlining/]
## Where this is going
By the end of this term, I intend to include more pieces of data that I got to personally work on. As I continue, I want my portfolio to demonstrate that I've grown and furthered my understand of mapping and how to create proper information that anyone can follow. With each passing week I want the data to show my understanding of more complex ways of gathering information for future field work and use that to build my portfolio as a reference to gain more hand to hand work.
