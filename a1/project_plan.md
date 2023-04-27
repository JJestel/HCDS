## Topic 
Investigate bicycle thefts in berlin.

https://daten.berlin.de/datensaetze/fahrraddiebstahl-berlin

On the basis of the police history statistics (data warehouse management information), data on bicycle theft crimes are made available on a daily basis at the level of planning areas. Included are the data of the current year up to the day before the update as well as the data of the entire previous year, provided that the time of the crime (for crime periods) can be narrowed down to a maximum of three days.

## Audience
Cyclists and fellow students. Commonly known topic, many people can relate to the topic => no proir knowledge necessary.

Fellow students are mostly Data Science or Computer Science students from FU Berlin => have a great background in data driven projects and at least know the city of Berlin by some extend.

## Questions
- Where are the most bikes stolen?
- Total damage amount?
- What daytime?
- What time of the year? / Seasonal trends?

## Plan
- Where are the most bikes stolen?

Aggregate data by LOR, maybe visualize as choropleth map (would need LOR GeoJSON)

- Total damage amount?

Sum up SCHADENSHOEHE

- What daytime?

First investigate TATZEIT data; how reliable?, what range?; then aggregate per TATZEIT STUNDE, visualize as barplot (thefts per hour)

- What time of the year? / Seasonal trends?

First investigate TATZEIT data, aggregate by month/week, visualize as barplot (thefts per month/week)