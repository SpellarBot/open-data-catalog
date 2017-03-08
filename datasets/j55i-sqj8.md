# Population Health Measures: Age-Adjusted Mortality Rates

## Dataset

* [Dataset URL](https://data.montgomerycountymd.gov/api/views/j55i-sqj8/rows.json?max_rows=100)
* [Catalog URL](https://catalog.data.gov/dataset/population-health-measures-age-adjusted-mortality-rates-6a2e8)
* [Metadata URL](https://data.montgomerycountymd.gov/api/views/j55i-sqj8)
* Id = j55i-sqj8
* Name = Population Health Measures: Age-Adjusted Mortality Rates
* Category = Health and Human Services
* Tags = [population health, measures, age, adjusted, mortality, rates]
* Created = 2014-12-23T19:33:23Z
* Publication Date = 2015-01-05T14:59:24Z
* Rows Updated = 2015-01-08T06:21:19Z

## Description

Age-adjustment mortality rates are rates of deaths that are computed using a statistical method to create a metric based on the true death rate so that it can be compared over time for a single population (i.e. comparing 2006-2008 to 2010-2012), as well as enable comparisons across different populations with possibly different age distributions in their populations (i.e. comparing Hispanic residents to Asian residents).  
Age adjustment methods applied to Montgomery County rates are consistent with US Centers for Disease Control and Prevention (CDC), National Center for Health Statistics (NCHS) as well as Maryland Department of Health and Mental Hygiene?s Vital Statistics Administration (DHMH VSA).
PHS Planning and Epidemiology receives an annual data file of Montgomery County resident deaths registered with Maryland Department of Health and Mental Hygiene?s Vital Statistics Administration (DHMH VSA).  
Using SAS analytic software, MCDHHS standardizes, aggregates, and calculates age-adjusted rates for each of the leading causes of death category consistent with state and national methods and by subgroups based on age, gender, race, and ethnicity combinations. Data are released in compliance with Data Use Agreements between DHMH VSA and MCDHHS. This dataset will be updated Annually.

## Columns

```ls
| Name                                     | Field Name                               | Data Type | Render Type | Schema Type    | Included | 
| ======================================== | ======================================== | ========= | =========== | ============== | ======== | 
| updated_at                               | :updated_at                              | meta_data | meta_data   | time           | No       | 
| Unique ID                                | unique_id                                | text      | text        | series tag     | Yes      | 
| 3-Year Period                            | year_range                               | text      | text        | series tag     | Yes      | 
| Cause of Death                           | cause_of_death                           | text      | text        | series tag     | Yes      | 
| Race                                     | race                                     | text      | text        | series tag     | Yes      | 
| Hispanic or Latino Origin                | hispanic_origin                          | text      | text        | series tag     | Yes      | 
| Gender                                   | gender                                   | text      | text        | series tag     | Yes      | 
| Age-Adjusted Rate per 100,000 Population | age_adjusted_rate_per_100_000_population | number    | number      | numeric metric | Yes      | 
| Lower 95% Confidence Interval            | lower_95_confidence_interval             | number    | number      | numeric metric | Yes      | 
| Upper 95% Confidence Interval            | upper_95_confidence_interval             | number    | number      | numeric metric | Yes      | 
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Metric Prefix = 
Included Fields = *
Excluded Fields = 
Annotation Fields = 
```

## Data Commands

```ls
series e:j55i-sqj8 d:2015-01-07T22:20:29.000Z t:hispanic_origin=Hispanic t:unique_id=A2006200804120 t:cause_of_death="Whooping cough" t:year_range=2006-2008 t:gender=Total t:race=White m:age_adjusted_rate_per_100_000_population=0 m:upper_95_confidence_interval=0.8 m:lower_95_confidence_interval=0

series e:j55i-sqj8 d:2015-01-07T22:20:40.000Z t:hispanic_origin=Total t:unique_id=A2007200914000 t:cause_of_death=Malaria t:year_range=2007-2009 t:gender=Total t:race=Total m:age_adjusted_rate_per_100_000_population=0 m:upper_95_confidence_interval=0.1 m:lower_95_confidence_interval=0

series e:j55i-sqj8 d:2015-01-07T22:20:40.000Z t:hispanic_origin=Hispanic t:unique_id=A2007200914220 t:cause_of_death=Malaria t:year_range=2007-2009 t:gender=Total t:race=Black m:age_adjusted_rate_per_100_000_population=0 m:upper_95_confidence_interval=15.5 m:lower_95_confidence_interval=0
```

## Meta Commands

```ls
metric m:age_adjusted_rate_per_100_000_population l:"Age-Adjusted Rate per 100,000 Population" d:"Age-Adjusted Rate Per 100,000 Population based on the U.S. 2000 Standard Population. (Point Estimate)" t:dataTypeName=number

metric m:lower_95_confidence_interval l:"Lower 95% Confidence Interval" d:"Lower boundary of 95th Percentile Confidence Interval Range of the Age-Adjusted Rate (true rate estimate falls within the upper and lower boundaries)" t:dataTypeName=number

metric m:upper_95_confidence_interval l:"Upper 95% Confidence Interval" d:"Upper boundary of 95th Percentile Confidence Interval Range of the Age-Adjusted Rate (true rate estimate falls within the upper and lower boundaries)" t:dataTypeName=number

entity e:j55i-sqj8 l:"Population Health Measures: Age-Adjusted Mortality Rates" t:url=https://data.montgomerycountymd.gov/api/views/j55i-sqj8

property e:j55i-sqj8 t:meta.view d:2017-03-07T18:00:16.755Z v:id=j55i-sqj8 v:category="Health and Human Services" v:averageRating=0 v:name="Population Health Measures: Age-Adjusted Mortality Rates"

property e:j55i-sqj8 t:meta.view.owner d:2017-03-07T18:00:16.755Z v:id=ajn4-zy65 v:screenName="MCG ESB Service" v:roleName=administrator v:displayName="MCG ESB Service"

property e:j55i-sqj8 t:meta.view.tableauthor d:2017-03-07T18:00:16.755Z v:id=ajn4-zy65 v:screenName="MCG ESB Service" v:roleName=administrator v:displayName="MCG ESB Service"
```