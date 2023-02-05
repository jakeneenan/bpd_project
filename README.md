# Analyzing Boston Police Department discipline records

I looked at BPD disciplinary records and Boston payroll data from 2010-2020 to get a sense of how the Department handled allegations and how likely it was to promote offending officers later in their careers.

## Findings

Being accused or being found guilty of misconduct had no effect on an officer's likelihood of being promoted. Essentially, about 4% of all officers in the Department got promoted every year. Whether they were never accused once or found guilty time and time again, this rate remained constant.

## Data collection

- I sourced BPD disciplinary records from the [Boston Globe](https://www.bostonglobe.com/2020/11/24/metro/heres-searchable-database-boston-police-department-internal-investigations-disciplinary-actions-more/).
- Boston payroll data is posted on the city's [Analyze Boston](https://data.boston.gov/dataset/employee-earnings-report) website.

## Data analysis process

I did some pandas magic to add a counter of the number of accusations, guilty findings, and promotions for each officer in the database, plus another metric that kept track of whether or not they were known to have offened when they received a promotion. Then, it was a matter of getting some stats on the data and making visualizations.

## New skills

I tried to think out of the box with visualizations here! Developing an intuition for visual language is an area I need to grow in, so this was valuable. The pandas work was a good refresher as well.

## Further work

There is just so much to look at here. How specific offenses are treated, what ranks officers offend at, which races and genders do suffer consequences of offending, any of these could be projects on their own. It's no secret the BPD had accountability issues during the timeframe covered by the data, but looking through these records is a good exercise in using data to illustrate institutional problems
