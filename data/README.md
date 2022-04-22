I selected these variables based on some background research that I believe that the variables will have a high correlation with life expectancy in general. The initial regression model contains life expectancy at birth as the response variable while the predictor variables include smoking, alcohol consumption, and happiness.

Life expectancy at birth, denoted as life_expectancy_at_birth reflects the overall mortality level of a population. This represents the average number of years that a newborn is expected to live based on current mortality rates. This data is collected from https://data.worldbank.org/indicator/SP.DYN.LE00.IN

Smoking rates by country, denoted as smokepercentage, is defined as the proportion of
population over the minimum smoking age that smokes regularly in the country is one of the
well-known causes of reduction in life expectancy (Manuel, D. G., 2012, p.1 and Janssen et al.,
2021). This data is collected from https://worldpopulationreview.com/country-rankings/smoking-rates-by-country

Alcohol consumption per capita, denoted as alcohol consumption, is defined as number of
pure alcohol litres consumed every year per capita over legal drinking age also increases
mortality and cancer risk in older adults (Kunzmann et al., 2018). This data is collected from https://data.worldbank.org/indicator/SH.ALC.PCAP.LI

World happiness index, denoted as happiness, is defined by average answers to the main life evaluation question known as Cantril ladder, which asks respondents to think of a ladder with the best possible life for them being a 10 and worst possible life for them being a 0 and rate themselves. This data is collected from https://www.kaggle.com/datasets/unsdsn/world-happiness

Each of these datasets are taken from year 2018 for consistency. We will also use a Country-Continent Dataset to group each of the countries based on their continents.
