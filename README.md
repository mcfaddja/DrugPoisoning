# Drug Poisoning Data Analysis

## Plan(s)

* Conduct some time-series analysis to see how this data is playing out over time
* Split data by year, age, sex, race, and state, then scatter plot
* Do the same splits and rerun Decision Trees and Random Forest models
* Hunt for outliers
* See if individual studies can be extracted

## Impressions

* It appears to affect men more than women
* Whites are more affected than the general population
* It gets worse as time progresses
* It affects the age groups 25-54 the most, not sure the ranking within that though

## Model Results/Information

* Using 'Deaths' :
  * Age > Sex > Race > Year > State = 1 / 5
  * Age > Sex > Year > Race > State = 2 / 5
  * Age >> Year > Sex > Race > State = 2 / 5
* Using 'Rate' :
  * Age >> Year > Race > Sex > State = 3 / 5
  * Age > Year >> State > Race > Sex = 2 / 5

# TO-DO

* Trim high value data to drill down on "clump" at low end of death/population range
* Determine ordinality for affect on races
* Determine ordinality for affect on age groups
* Split datasets
  * AGE: Drop ALL-AGES
  * STATE: Drop ALL-STATES and also NOT ALL-STATES
  * SEX: Drop BOTH-SEXES
  * RACE: Drop ALL-RACES
* ANOVA stuff
* Alternative to ANOVA

