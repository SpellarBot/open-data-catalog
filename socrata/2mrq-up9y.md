# Fastest Growing Occupations

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/fastest-growing-occupations) |
| Metadata | [Link](https://data.ct.gov/api/views/2mrq-up9y) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/2mrq-up9y/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/2mrq-up9y/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | 2mrq-up9y |
| Name | Fastest Growing Occupations |
| Attribution | Department of Labor |
| Category | Business |
| Tags | ct, jobs, occupations |
| Created | 2014-03-11T20:15:50Z |
| Publication Date | 2014-03-11T20:17:14Z |

## Description

Fastest Growing Occupations in Connecticut All Levels

## Columns

```ls
| Included | Schema Type    | Field Name           | Name                 | Data Type | Render Type |
| ======== | ============== | ==================== | ==================== | ========= | =========== |
| No       | time           | :updated_at          | updated_at           | meta_data | meta_data   |
| Yes      | series tag     | job_title_types      | Job Title/Types      | text      | text        |
| Yes      | numeric metric | emp_projections_2010 | Emp Projections 2010 | number    | number      |
| Yes      | numeric metric | emp_projections_2020 | Emp Projections 2020 | number    | number      |
| Yes      | numeric metric | percent_change       | Percent Change       | percent   | percent     |
| Yes      | numeric metric | average_annual_wage  | Average Annual Wage  | money     | money       |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:2mrq-up9y d:2014-03-11T13:15:53.000Z t:job_title_types="Personal and Home Care Aides" m:emp_projections_2010=15794 m:average_annual_wage=25069 m:emp_projections_2020=24162 m:percent_change=53

series e:2mrq-up9y d:2014-03-11T13:15:53.000Z t:job_title_types="Veterinary Technologists and Technicians" m:emp_projections_2010=1100 m:average_annual_wage=37789 m:emp_projections_2020=1645 m:percent_change=49.5

series e:2mrq-up9y d:2014-03-11T13:15:53.000Z t:job_title_types="Meeting and Convention Planners" m:emp_projections_2010=643 m:average_annual_wage=54838 m:emp_projections_2020=945 m:percent_change=47
```

## Meta Commands

```ls
metric m:emp_projections_2010 p:integer l:"Emp Projections 2010" t:dataTypeName=number

metric m:emp_projections_2020 p:integer l:"Emp Projections 2020" t:dataTypeName=number

metric m:percent_change p:double l:"Percent Change" t:dataTypeName=percent

metric m:average_annual_wage p:integer l:"Average Annual Wage" t:dataTypeName=money

entity e:2mrq-up9y l:"Fastest Growing Occupations" t:attribution="Department of Labor" t:url=https://data.ct.gov/api/views/2mrq-up9y

property e:2mrq-up9y t:meta.view v:id=2mrq-up9y v:category=Business v:attributionLink=http://www1.ctdol.state.ct.us/lmi/hotnot_results.asp v:averageRating=0 v:name="Fastest Growing Occupations" v:attribution="Department of Labor"

property e:2mrq-up9y t:meta.view.license v:name="Public Domain"

property e:2mrq-up9y t:meta.view.owner v:id=cvy9-n6sb v:screenName="Tyler Kleykamp" v:lastNotificationSeenAt=1492608796 v:displayName="Tyler Kleykamp"

property e:2mrq-up9y t:meta.view.tableauthor v:id=cvy9-n6sb v:screenName="Tyler Kleykamp" v:roleName=administrator v:lastNotificationSeenAt=1492608796 v:displayName="Tyler Kleykamp"
```

## Top Records

```ls
| :updated_at | job_title_types                                                             | emp_projections_2010 | emp_projections_2020 | percent_change | average_annual_wage | 
| =========== | =========================================================================== | ==================== | ==================== | ============== | =================== | 
| 1394543753  | Personal and Home Care Aides                                                | 15794                | 24162                | 53             | 25069               | 
| 1394543753  | Veterinary Technologists and Technicians                                    | 1100                 | 1645                 | 49.50          | 37789               | 
| 1394543753  | Meeting and Convention Planners                                             | 643                  | 945                  | 47             | 54838               | 
| 1394543753  | Helpers--Brickmasons, Blockmasons, Stonemasons, and Tile and Marble Setters | 355                  | 505                  | 42.30          | 36160               | 
| 1394543753  | Helpers--Carpenters                                                         | 354                  | 502                  | 41.80          | 32849               | 
| 1394543753  | Hazardous Materials Removal Workers                                         | 564                  | 799                  | 41.70          | 40046               | 
| 1394543753  | Interpreters and Translators                                                | 383                  | 541                  | 41.30          | 55670               | 
| 1394543753  | Diagnostic Medical Sonographers                                             | 826                  | 1164                 | 40.90          | 79501               | 
| 1394543753  | Home Health Aides                                                           | 10533                | 14343                | 36.20          | 29300               | 
| 1394543753  | Veterinarians                                                               | 757                  | 1014                 | 33.90          | 123138              | 
```