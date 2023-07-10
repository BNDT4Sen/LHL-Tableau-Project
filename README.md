# Final-Project-Tableau

Link to Tableau Story:

https://public.tableau.com/views/LHLTableauAssignment/CausesofDeath1990to2019?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link

## Project/Goals
For this project I chose dataset 5 of option 2 (Causes of Death). The dataset is made up of dozens of causes of death broken down by country and year. My goal for this project was to thoroughly examine the data and explore interesting trends with Tableau Visualizations.

## Process
### Collection of Data
Aside from the original causes of death csv file, I also grabbed population information from the World Bank database. This information is almost necessary when attempting to identify trends in causes of death. The two files were joined on the standardized country codes. 
https://databank.worldbank.org/reports.aspx?source=2&series=SP.POP.TOTL&country=#
### Focusing on the Data
I decided to focus on a few broad sections of the data: 
  Death by contagion, including HIV, Tuberculosis, Malaria, and Hepatitis. 
  Deaths resulting from war, genocide, and terrorism.
  Deaths related to alcohol and drugs.
The more specific questions related to each are:
  How has death as a result of contagion changed over the time period?
  What are the most dramatic outliers in terms of conflict related deaths? 
  Where are deaths from alcohol and drugs forecasted to be in the future?
### Visualization of the Data
Most of the visualizations that I used in order to get a feel for the data couldn't make it into the final dashboard due to lack of space. As a result, only visualizations which more or less directly answer the questions will be included. Those that made the cut were combined into the final result.

## Results
The four diseases measured all showed similar behavior in their gradual decline over the last several decades. The primary outlier here was HIV/AIDS. There was a dramatic peak in 2004, during which time it even overtook Tuberculosis in yearly deaths. Since then however, there has been a steady decline across the board.

Conflict was used as a general term in the data source, defined as including both war and terrorism. This measure was visualized over time and by country, with one huge point of data standing out. 1994 saw a huge spike in conflict related deaths due to the Rwandan Genocide. When visualized on a tree map counting conflict deaths cumulatively over almost 30 years, Rwanda is still the nation with by far the greatest number of deaths. Years long conflicts in Iraq, Afghanistan, and Syria still fall short of the brutality that Rwanda saw in just a few months.

Deaths from drug use have remained lower than deaths from alcohol use throughout the entire timespan of the data set, although the gap is shrinking. Alcohol related deaths peaked in 2005, and declined for several years afterwards. Since 2013 this number has been growing once more, however. Deaths from drug use have steadily and dramatically increased over time. In fact, deaths from drugs were projected to surpass deaths from alcohol within the next years. Out of all countries in the data, Russia suffered the most from substance abuse both in terms of raw numbers and per capita.

## Challenges 
Collecting and connecting the information that I collected from the World Bank to the rest of the data was tricky, and I tried a few methods with both Pandas and Tableau before figuring it out directly through the source website.
I found myself making visualizations with certain graphs that I later found did not really make sense. For instance, representing the proportionality of many categories is much more intuitive with treemaps than with bar charts.

## Future Goals
I found that essentially everything I wanted to do with Tableau I could do, if I spent enough time figuring it out. Next time I would spend more effort on learning how to make my visualizations more visually appealing. When it comes to this particular dataset, exploring some of the other causes of death would be interesting. I focused moreso on a few limited segments, but there are still many more where interesting trends can be identified.
