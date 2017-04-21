# Public Health Statistics- Life Expectancy By Race Ethnicity

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/public-health-statistics-life-expectancy-by-race-ethnicity-79ff0) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/3qdj-cqb8) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/3qdj-cqb8/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/3qdj-cqb8/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | 3qdj-cqb8 |
| Name | Public Health Statistics- Life Expectancy By Race Ethnicity |
| Attribution | Vital statistics files produced by the Illinois Department of Public Health (IDPH) |
| Category | Health & Human Services |
| Tags | health, life, death, race, ethnicity |
| Created | 2014-06-16T21:01:51Z |
| Publication Date | 2014-08-27T15:14:53Z |

## Description

This dataset gives the average life expectancy and corresponding confidence intervals for sex and racial-ethnic groups in Chicago for the years 1990, 2000 and 2010.  See the full description at: 
https://data.cityofchicago.org/api/views/3qdj-cqb8/files/pJ3PVVyubnsS2SpGO5P5IOPtNgCJZTE3LNOeLagC3mw?download=true&filename=P:\EPI\OEPHI\MATERIALS\REFERENCES\Life Expectancy\Dataset description_LE_ Sex_Race_Ethnicity.pdf

## Columns

```ls
| Included | Schema Type    | Field Name           | Name                 | Data Type | Render Type |
| ======== | ============== | ==================== | ==================== | ========= | =========== |
| No       | time           | :updated_at          | updated_at           | meta_data | meta_data   |
| Yes      | series tag     | race_ethnicity       | Race-ethnicity       | text      | text        |
| Yes      | series tag     | sex                  | Sex                  | text      | text        |
| Yes      | numeric metric | 1990_life_expectancy | 1990 Life Expectancy | number    | number      |
| Yes      | numeric metric | 1990_lower_95_ci     | 1990 Lower 95% CI    | number    | number      |
| Yes      | numeric metric | 1990_upper_95_ci     | 1990 Upper 95% CI    | number    | number      |
| Yes      | numeric metric | 2000_life_expectancy | 2000 Life Expectancy | number    | number      |
| Yes      | numeric metric | 2000_lower_95_ci     | 2000 Lower 95% CI    | number    | number      |
| Yes      | numeric metric | 2000_upper_95_ci     | 2000 Upper 95% CI    | number    | number      |
| Yes      | numeric metric | 2010_life_expectancy | 2010 Life Expectancy | number    | number      |
| Yes      | numeric metric | 2010_lower_95_ci     | 2010 Lower 95% CI    | number    | number      |
| Yes      | numeric metric | 2010_upper_95_ci     | 2010 Upper 95% CI    | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:3qdj-cqb8 d:2014-06-16T14:01:55.000Z t:sex=All t:race_ethnicity=All m:1990_lower_95_ci=70.3 m:2010_lower_95_ci=77.6 m:2000_upper_95_ci=74.1 m:2000_lower_95_ci=73.8 m:2010_upper_95_ci=78 m:1990_life_expectancy=70.5 m:2010_life_expectancy=77.8 m:1990_upper_95_ci=70.7 m:2000_life_expectancy=73.9

series e:3qdj-cqb8 d:2014-06-16T14:01:55.000Z t:sex=All t:race_ethnicity=Hispanic m:1990_lower_95_ci=82 m:2010_lower_95_ci=84.4 m:2000_upper_95_ci=81.9 m:2000_lower_95_ci=81 m:2010_upper_95_ci=85.1 m:1990_life_expectancy=82.6 m:2010_life_expectancy=84.7 m:1990_upper_95_ci=83.1 m:2000_life_expectancy=81.4

series e:3qdj-cqb8 d:2014-06-16T14:01:55.000Z t:sex=All t:race_ethnicity="Non-Hispanic Black" m:1990_lower_95_ci=65.7 m:2010_lower_95_ci=72.1 m:2000_upper_95_ci=68.9 m:2000_lower_95_ci=68.4 m:2010_upper_95_ci=72.7 m:1990_life_expectancy=65.9 m:2010_life_expectancy=72.4 m:1990_upper_95_ci=66.2 m:2000_life_expectancy=68.7
```

## Meta Commands

```ls
metric m:1990_life_expectancy p:float l:"1990 Life Expectancy" d:"Life expectancy by race/ethnicity for the year of 1990" t:dataTypeName=number

metric m:1990_lower_95_ci p:float l:"1990 Lower 95% CI" d:"Life expectancy lower confidence interval for the year of 1990" t:dataTypeName=number

metric m:1990_upper_95_ci p:float l:"1990 Upper 95% CI" d:"Life expectancy upper confidence interval for the year of 1990" t:dataTypeName=number

metric m:2000_life_expectancy p:float l:"2000 Life Expectancy" d:"Life expectancy by race/ethnicity for the year of 2000" t:dataTypeName=number

metric m:2000_lower_95_ci p:float l:"2000 Lower 95% CI" d:"Life expectancy lower confidence interval for the year of 2000" t:dataTypeName=number

metric m:2000_upper_95_ci p:float l:"2000 Upper 95% CI" d:"Life expectancy upper confidence interval for the year of 2000" t:dataTypeName=number

metric m:2010_life_expectancy p:float l:"2010 Life Expectancy" d:"Life expectancy by race/ethnicity for the year of 2010" t:dataTypeName=number

metric m:2010_lower_95_ci p:float l:"2010 Lower 95% CI" d:"Life expectancy lower confidence interval for the year of 2010" t:dataTypeName=number

metric m:2010_upper_95_ci p:float l:"2010 Upper 95% CI" d:"Life expectancy upper confidence interval for the year of 2010" t:dataTypeName=number

entity e:3qdj-cqb8 l:"Public Health Statistics- Life Expectancy By Race Ethnicity" t:attribution="Vital statistics files produced by the Illinois Department of Public Health (IDPH)" t:url=https://data.cityofchicago.org/api/views/3qdj-cqb8

property e:3qdj-cqb8 t:meta.view v:id=3qdj-cqb8 v:category="Health & Human Services" v:averageRating=0 v:name="Public Health Statistics- Life Expectancy By Race Ethnicity" v:attribution="Vital statistics files produced by the Illinois Department of Public Health (IDPH)"

property e:3qdj-cqb8 t:meta.view.owner v:id=is6y-5c5n v:screenName=Jamyia v:displayName=Jamyia

property e:3qdj-cqb8 t:meta.view.tableauthor v:id=is6y-5c5n v:screenName=Jamyia v:displayName=Jamyia
```

## Top Records

```ls
| :updated_at | race_ethnicity     | sex    | 1990_life_expectancy | 1990_lower_95_ci | 1990_upper_95_ci | 2000_life_expectancy | 2000_lower_95_ci | 2000_upper_95_ci | 2010_life_expectancy | 2010_lower_95_ci | 2010_upper_95_ci | 
| =========== | ================== | ====== | ==================== | ================ | ================ | ==================== | ================ | ================ | ==================== | ================ | ================ | 
| 1402927315  | All                | All    | 70.5                 | 70.3             | 70.7             | 73.9                 | 73.8             | 74.1             | 77.8                 | 77.6             | 78.0             | 
| 1402927315  | Hispanic           | All    | 82.6                 | 82.0             | 83.1             | 81.4                 | 81.0             | 81.9             | 84.7                 | 84.4             | 85.1             | 
| 1402927315  | Non-Hispanic Black | All    | 65.9                 | 65.7             | 66.2             | 68.7                 | 68.4             | 68.9             | 72.4                 | 72.1             | 72.7             | 
| 1402927315  | Non-Hispanic White | All    | 73.2                 | 72.9             | 73.4             | 76.0                 | 75.8             | 76.3             | 79.2                 | 78.9             | 79.4             | 
| 1402927315  | All                | Female | 75.1                 | 74.9             | 75.4             | 77.5                 | 77.3             | 77.7             | 79.8                 | 79.6             | 80.0             | 
| 1402927315  | Hispanic           | Female | 87.6                 | 86.9             | 88.4             | 84.3                 | 83.8             | 84.9             | 87.6                 | 87.1             | 88.0             | 
| 1402927315  | Non-Hispanic Black | Female | 71.4                 | 71.1             | 71.8             | 73.2                 | 72.9             | 73.6             | 76.6                 | 76.2             | 76.9             | 
| 1402927315  | Non-Hispanic White | Female | 77.5                 | 77.1             | 77.8             | 79.3                 | 79.0             | 79.6             | 81.8                 | 81.5             | 82.1             | 
| 1402927315  | All                | Male   | 65.9                 | 65.6             | 66.1             | 70.3                 | 70.0             | 70.5             | 73.6                 | 73.4             | 73.8             | 
| 1402927315  | Hispanic           | Male   | 77.9                 | 77.2             | 78.7             | 78.8                 | 78.2             | 79.4             | 82.0                 | 81.4             | 82.4             | 
```