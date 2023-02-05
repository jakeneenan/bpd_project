# Analyzing Boston Police Department discipline records

I looked at BPD disciplinary records and Boston payroll data from 2010-2020 to get a sense of how the Department handled allegations and how likely it was to promote offending officers later in their careers.

## Findings

Being accused or being found guilty of misconduct had no effect on an officer's likelihood of being promoted. Essentially, about 4% of all officers in the Department got promoted every year. Whether they were never accused once or found guilty time and time again, this rate remained constant.

## Data collection

- I sourced BPD disciplinary records from the Boston Globe.
- Boston payroll data is posted by the city here.

## Data analysis process

I did some pandas magic to add a counter of the number of accusations, guilty findings, and promotions for each officer in the database, plus another metric that kept track of whether or not they were known to have offened when they received a promotion. Then, it was a matter of getting some stats on the data and making visualizations.

## New skills

I tried to think out of the box with visualizations here! A lot of energy was spent on conveying the information visually in addition to laying out in words. The pandas work was more complex than I had done in the past, so that was a good exercise too.

## Further work

There is just so much to look at here. How specific offenses are treated, what ranks officers offend at, which races and genders do suffer consequences of offending, any of these could be projects on their own. It's no secret the BPD had accountability issues during the timeframe covered by the data, but looking through these records is a good exercise in using data to illustrate institutional problems
