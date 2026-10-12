# Dean Vallejo 
I’m working toward my bachelor’s in Emergency Management at Moreno Valley College. I want to develop the GIS skills to build my own maps independently, so I can take complex spatial data and present it in a way that’s clear and useful to the public, not just to people trained to read maps. I’m always looking for ways to make that information easier for the average person to understand, especially now that I’m learning just how much data and technical work actually goes into a single map, and how long maps have been used as a critical tool for decision-making.
## Disease Outbreak 
Covid 19 cases in the city of New York."<img width="950" height="330" alt="COVID19 PNG" src="https://github.com/user-attachments/assets/5f9f5996-f73b-4123-9be9-ca5c8b05f18f" />

**Question:** Which boroughs and neighborhoods in New York City experienced the highest concentrations of COVID-19 cases, and how did case rates differ across the city?

**Data:** COVID19 cases/New York, Dean Vallejo, 2026, ARCGIS.

**Method:** I imported the case rate data into ArcGIS Pro and joined it to a borough (or ZIP code/neighborhood) boundary shapefile. I then built a choropleth map using [classification method you used, e.g., “natural breaks” or “quantile”] to group areas by case rate, and symbolized the map using a graduated color scheme so higher case concentrations stand out visually. 

**A design choice I made and why:** I used a [color scheme,“red-to-yellow gradient”] because it intuitively signals severity to a reader, with darker or more intense colors drawing the eye to the hardest-hit areas first. I also chose to classify the data by [natural breaks because the case rate distribution showed clear clusters rather than an even spread”], which better reflects the real differences between boroughs than an evenly divided scale would.

**A limitation of this map:** This map shows case rates at a single point in time, so it can’t capture how the outbreak shifted week to week or show the underlying reasons for the disparities, like population density, access to testing, or healthcare infrastructure. It also can’t account for underreporting, which was a known issue early in the pandemic.

## Red Lining Equity

RedLining Map <img width="705" height="330" alt="redliningMap" src="https://github.com/user-attachments/assets/2f153cec-6fda-41db-a1cf-e00857b8245c" />

**Question:** Which Atlanta neighborhoods were historically redlined by the Home Owners’ Loan Corporation (HOLC) in the 1930s, and how do those boundaries compare to [what you compared it to present day income levels, racial demographics, or health outcomes in those same areas today]?

**Data:** OLC Residential Security Map for Atlanta, published by [the Mapping Inequality project, University of Richmond’s Digital Scholarship Lab], originally created in [year, likely 1938],

**Method:** I imported the historical HOLC grade boundaries for Atlanta into ArcGIS Pro and [“overlaid them with current-day census tract boundaries” or “joined them to a modern Atlanta neighborhood layer”]. I symbolized the map using the four HOLC grade categories, A through D (commonly labeled “Best,” “Still Desirable,” “Definitely Declining,” and “Hazardous”), using [color scheme you used,“the traditional green-blue-yellow-red color-coding from the original HOLC maps”] so the historical grading pattern is immediately recognizable.

**A design choice I made and why:** I imported the historical HOLC grade boundaries for Atlanta into ArcGIS Pro and [describe what you did — e.g., “overlaid them with current-day census tract boundaries” or “joined them to a modern Atlanta neighborhood layer”]. I symbolized the map using the four HOLC grade categories, A through D (commonly labeled “Best,” “Still Desirable,” “Definitely Declining,” and “Hazardous”), using [color scheme red, yellow, green “the traditional green-blue-yellow-red color-coding from the original HOLC maps”] so the historical grading pattern is immediately recognizable.

**A limitation of this map:** This map shows boundaries drawn nearly 90 years ago and does not, by itself, prove a direct causal link between historical redlining and any present-day conditions in Atlanta, that requires additional data and analysis. It also reflects the subjective judgments of HOLC assessors at the time, shaped by the racial and economic biases of that era rather than objective risk assessment, including biases that specifically affected historically Black Atlanta neighborhoods like those around Sweet Auburn and the Westside.
## Where this is going 
I plan to keep adding PNG exports of the maps I create throughout this GIS course, continuing to build out this portfolio as my skills grow. I want to keep learning the key principles behind strong map-making and understand just how powerful a well-built map can be for showing real data about specific places. By the end of the semester, I want this portfolio to reflect real, visible growth, showing not just what I’ve learned about the technology and tools behind GIS, but how much more capable and confident I’ve become at turning raw data into maps that actually mean something to the people who see them.
