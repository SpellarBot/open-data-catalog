# Population Health Measures: Age-Adjusted Mortality Rates

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/population-health-measures-age-adjusted-mortality-rates-6a2e8) |
| Metadata | [Link](https://data.montgomerycountymd.gov/api/views/j55i-sqj8) |
| Data: JSON | [100 Rows](https://data.montgomerycountymd.gov/api/views/j55i-sqj8/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.montgomerycountymd.gov/api/views/j55i-sqj8/rows.csv?max_rows=100) |
| Host | data.montgomerycountymd.gov |
| Id | j55i-sqj8 |
| Name | Population Health Measures: Age-Adjusted Mortality Rates |
| Category | Health and Human Services |
| Tags | population health, measures, age, adjusted, mortality, rates |
| Created | 2014-12-23T19:33:23Z |
| Publication Date | 2015-01-05T14:59:24Z |

## Description

Age-adjustment mortality rates are rates of deaths that are computed using a statistical method to create a metric based on the true death rate so that it can be compared over time for a single population (i.e. comparing 2006-2008 to 2010-2012), as well as enable comparisons across different populations with possibly different age distributions in their populations (i.e. comparing Hispanic residents to Asian residents).  
Age adjustment methods applied to Montgomery County rates are consistent with US Centers for Disease Control and Prevention (CDC), National Center for Health Statistics (NCHS) as well as Maryland Department of Health and Mental Hygiene?s Vital Statistics Administration (DHMH VSA).
PHS Planning and Epidemiology receives an annual data file of Montgomery County resident deaths registered with Maryland Department of Health and Mental Hygiene?s Vital Statistics Administration (DHMH VSA).  
Using SAS analytic software, MCDHHS standardizes, aggregates, and calculates age-adjusted rates for each of the leading causes of death category consistent with state and national methods and by subgroups based on age, gender, race, and ethnicity combinations. Data are released in compliance with Data Use Agreements between DHMH VSA and MCDHHS. This dataset will be updated Annually.

## Columns

```ls
| Included | Schema Type    | Field Name                               | Name                                     | Data Type | Render Type |
| ======== | ============== | ======================================== | ======================================== | ========= | =========== |
| No       | time           | :updated_at                              | updated_at                               | meta_data | meta_data   |
| Yes      | series tag     | unique_id                                | Unique ID                                | text      | text        |
| Yes      | series tag     | year_range                               | 3-Year Period                            | text      | text        |
| Yes      | series tag     | cause_of_death                           | Cause of Death                           | text      | text        |
| Yes      | series tag     | race                                     | Race                                     | text      | text        |
| Yes      | series tag     | hispanic_origin                          | Hispanic or Latino Origin                | text      | text        |
| Yes      | series tag     | gender                                   | Gender                                   | text      | text        |
| Yes      | numeric metric | age_adjusted_rate_per_100_000_population | Age-Adjusted Rate per 100,000 Population | number    | number      |
| Yes      | numeric metric | lower_95_confidence_interval             | Lower 95% Confidence Interval            | number    | number      |
| Yes      | numeric metric | upper_95_confidence_interval             | Upper 95% Confidence Interval            | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:j55i-sqj8 d:2015-01-07T22:20:29.000Z t:hispanic_origin=Hispanic t:unique_id=A2006200804120 t:cause_of_death="Whooping cough" t:year_range=2006-2008 t:gender=Total t:race=White m:age_adjusted_rate_per_100_000_population=0 m:upper_95_confidence_interval=0.8 m:lower_95_confidence_interval=0

series e:j55i-sqj8 d:2015-01-07T22:20:40.000Z t:hispanic_origin=Total t:unique_id=A2007200914000 t:cause_of_death=Malaria t:year_range=2007-2009 t:gender=Total t:race=Total m:age_adjusted_rate_per_100_000_population=0 m:upper_95_confidence_interval=0.1 m:lower_95_confidence_interval=0

series e:j55i-sqj8 d:2015-01-07T22:20:40.000Z t:hispanic_origin=Hispanic t:unique_id=A2007200914220 t:cause_of_death=Malaria t:year_range=2007-2009 t:gender=Total t:race=Black m:age_adjusted_rate_per_100_000_population=0 m:upper_95_confidence_interval=15.5 m:lower_95_confidence_interval=0
```

## Meta Commands

```ls
metric m:age_adjusted_rate_per_100_000_population p:float l:"Age-Adjusted Rate per 100,000 Population" d:"Age-Adjusted Rate Per 100,000 Population based on the U.S. 2000 Standard Population. (Point Estimate)" t:dataTypeName=number

metric m:lower_95_confidence_interval p:float l:"Lower 95% Confidence Interval" d:"Lower boundary of 95th Percentile Confidence Interval Range of the Age-Adjusted Rate (true rate estimate falls within the upper and lower boundaries)" t:dataTypeName=number

metric m:upper_95_confidence_interval p:float l:"Upper 95% Confidence Interval" d:"Upper boundary of 95th Percentile Confidence Interval Range of the Age-Adjusted Rate (true rate estimate falls within the upper and lower boundaries)" t:dataTypeName=number

entity e:j55i-sqj8 l:"Population Health Measures: Age-Adjusted Mortality Rates" t:url=https://data.montgomerycountymd.gov/api/views/j55i-sqj8

property e:j55i-sqj8 t:meta.view v:id=j55i-sqj8 v:category="Health and Human Services" v:averageRating=0 v:name="Population Health Measures: Age-Adjusted Mortality Rates"

property e:j55i-sqj8 t:meta.view.owner v:id=ajn4-zy65 v:screenName="MCG ESB Service" v:lastNotificationSeenAt=1491401045 v:displayName="MCG ESB Service"

property e:j55i-sqj8 t:meta.view.tableauthor v:id=ajn4-zy65 v:screenName="MCG ESB Service" v:roleName=administrator v:lastNotificationSeenAt=1491401045 v:displayName="MCG ESB Service"
```

## Top Records

```ls
| :updated_at | unique_id      | year_range | cause_of_death      | race                   | hispanic_origin | gender | age_adjusted_rate_per_100_000_population | lower_95_confidence_interval | upper_95_confidence_interval | 
| =========== | ============== | ========== | =================== | ====================== | =============== | ====== | ======================================== | ============================ | ============================ | 
| 1420669229  | A2006200803000 | 2006-2008  | Tuberculosis        | Total                  | Total           | Total  |                                          |                              |                              | 
| 1420669229  | A2006200804120 | 2006-2008  | Whooping cough      | White                  | Hispanic        | Total  | 0                                        | 0                            | 0.8                          | 
| 1420669231  | A2006200820400 | 2006-2008  | Meningitis          | Asian/Pacific Islander | Total           | Total  |                                          |                              |                              | 
| 1420669237  | A2007200907221 | 2007-2009  | Septicemia          | Black                  | Hispanic        | Male   |                                          |                              |                              | 
| 1420669240  | A2007200914000 | 2007-2009  | Malaria             | Total                  | Total           | Total  | 0                                        | 0                            | 0.1                          | 
| 1420669240  | A2007200914220 | 2007-2009  | Malaria             | Black                  | Hispanic        | Total  | 0                                        | 0                            | 15.5                         | 
| 1420669241  | A2007200918021 | 2007-2009  | Diabetes mellitus   | Total                  | Hispanic        | Male   |                                          |                              |                              | 
| 1420669241  | A2007200920000 | 2007-2009  | Meningitis          | Total                  | Total           | Total  |                                          |                              |                              | 
| 1420669243  | A2007200922021 | 2007-2009  | Alzheimer's disease | Total                  | Hispanic        | Male   |                                          |                              |                              | 
| 1420669246  | A2007200933000 | 2007-2009  | Peptic ulcer        | Total                  | Total           | Total  |                                          |                              |                              | 
```