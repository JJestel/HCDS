## Group members
- Jascha Jestel 5547158
- Mustafa Suman 5564676

## Research Topic
Investigate recent bicycle thefts in berlin and gain interesting insights.

Foundation: https://daten.berlin.de/datensaetze/fahrraddiebstahl-berlin

On the basis of the police history statistics (data warehouse management information), data on bicycle theft crimes are made available on a daily basis at the level of planning areas. Included are the data of the current year up to the day before the update as well as the data of the entire previous year, provided that the time of the crime (for crime periods) can be narrowed down to a maximum of three days.

## Target Audience
Fellow students in our course (who life in Berlin and have a bike or are thinking about getting one). Perhaps more generally: cyclists (& those who are thinking about becoming one) living in Berlin or even Police departments. But since it is a commonly known topic which occurs in every days life, a lot of people can relate to it. No prior knowledge is necessary to engage with the topic.

Fellow students are mostly Data Science or Computer Science students from FU Berlin. This means they have a great background in data driven projects and at least know the city of Berlin by some extend.

## Questions
- In which district/area are most of the bikes stolen?
- What is the total damage amount?
- How many bikes are stolen across the year? Are there some seasonal trends which can be discovered?
- How are the thefts distributed throughout the day?

## Plan
- Where are the most bikes stolen?

Aggregate data by LOR & visualize as choropleth map (would need LOR GeoJSON)

- Total damage amount?

Sum up SCHADENSHOEHE & visualize it with appropiate plots

- What daytime?

First investigate TATZEIT data; how reliable? what range? then aggregate per TATZEIT STUNDE; visualize as barplot (thefts per hour)

- What time of the year? / Seasonal trends?

First investigate TATZEIT data, aggregate by month/week, visualize as barplot or graph (thefts per month/week)
