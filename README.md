# Final-Project-Tableau

## Project/Goals
In this project, I will examine data from the Canadian Open Data portal related to housing and income (option 1 from the assignment page). I will create visualizations to depict trends and relationships between the data over the past 40 years. Specifically, I'll be looking at the following:
- The overall trend of the HPI across Canada over the past 40 years
- How this trend compares to other metrics such as CPI, benchmark prices and the office price index
- How housing prices have changed in different regions of the country
- What impact large economic crises have had on these metrics
- How trends in housing prices compares to trends in individual earnings and housing construciton

## Process
I first examined all the data to understand what types of information I was working with. This involved some minor data cleaning mostly to ensure Tableu could accurately read dates and create relationships between the tables.

Once I had my data all loaded into Tableau, I started creating various visualizations to understand better the trends and relationships I was interested in. Next, I thought about what story this data was telling and how to best to present this data to narrate that story.

## Results
What I saw in this data was a crisi in housing affordability. Generally over the past 40 years, there has been a drastic increase in Canadian Housing prices, as shown by both HPI and benchmark prices. This increase can also been seen in the CPI and Office Price Index. I found trendlines between CPI and HPI to be nearly parallel, suggesting a strong correlation between the two. This makes sense given CPI includes housing as part of its basket of goods and service.

The recession in the early 1990s and well as the 2008 Financial Crisis both had depressing effects on all the metrics I examined. The impact of Black Monday in 1987 and the Dot Com Bubble bursting in the early 2000s had a less clear effect.

The increase in housing costs is not uniform across the country. The data I had for regional changes was only from 2005-2021, the Vancouver and Toronto metro areas have seen the most severe increases in prices in that time period. In 2005, prices in all reported regions were clustered between $100,000 and $400,000. By the end of 2020 however, that cluster spread out to be between $200,000 and over $1.1 million, with the Vancouver and Toronto metro areas well above the rest of the data. 

I further broke this down to look at the prices of different types of housing in BC, Ontario, Quebec and the Prairies. Here, I could see more clearly the differences in detached houses vs townhouses and apartments and when different regions experiences spikes and dips in prices.

It becomes clear that these rising house prices are a crisis when I compare the trend of prices to the trend of annual earnings over the same period of time. Since 2005, national house prices have increased nearly 75%. Over that same period of time, average national annual earnings have only increased 32%. As costs increases continue to outpace income increases, people need to spend a larger and larger percentage of their earnings on housing. This means people get priced out of housing markets and are forced to either give up on home ownership, or move to areas further from their work and social lives. 

I also compared population growth and new housing construction over time. This helps frame the housing prices in terms of supply and demand, as the population increases, there is a need for more houses to be built. This graph shows the trend over the past 50 years. There does not appear to be a strong relationship between the two. Spikes in population growth do not always correspond to spikes in housing construction, suggesting it is not a major factor in construction.


## Challenges 
One of the challenges of this project was that the different data sets did not all span the same periods of time. Also, for indexed measures like CPI and HPI, the year the indeces were tied to was not consistent between data sets and sometimes changed within a single data set. This made direct comparisons between these indeces difficult. To compensate, I tried to focus on overall shapes and rates of change as oppose to specific values.
The regional data also contained many more data points for Ontario then any other area. There were 22 districts in Ontario, 5 in BC and only 1 or 2 for every other province (and no data from the territories). This means comparisons between different provinces are sometimes based off of just one or two cities in that province.


## Future Goals
The next steps in this project would be to look for some other data that could show the impacts of rising housing costs such as percentages of renters vs owners, counts of homeless or shelter populations, numbers related to social and subsidized housing projects, and average commute times.

I could also look into various policy decisions federal and provincial goverments have made and how they may or may not impact housing costs.