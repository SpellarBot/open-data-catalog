# Asthma Hospitalization and ED Visit (Primary Diagnosis) Crude and Age-Adjusted Rates by Town, 5-year period, 2005 to 2009

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/asthma-hospitalization-and-ed-visit-primary-diagnosis-crude-and-age-adjusted-rates-by-town) |
| Metadata | [Link](https://data.ct.gov/api/views/bimu-2gpn) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/bimu-2gpn/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/bimu-2gpn/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | bimu-2gpn |
| Name | Asthma Hospitalization and ED Visit (Primary Diagnosis) Crude and Age-Adjusted Rates by Town, 5-year period, 2005 to 2009 |
| Attribution | CT DPH: Community Health and Prevention Section |
| Category | Health and Human Services |
| Tags | asthma, hospitalization, emergency department visits |
| Created | 2014-04-08T15:02:00Z |
| Publication Date | 2014-04-08T15:07:16Z |

## Description

This tables provides the crude and age-adjusted rates for hospitalization and emergency department visits due to asthma as a primary diagnosis.  The information is a five-year aggregate data from 2005 to 2009 and it is provided at the Connecticut town level.

## Columns

```ls
| Included | Schema Type    | Field Name                                   | Name                                           | Data Type | Render Type |
| ======== | ============== | ============================================ | ============================================== | ========= | =========== |
| Yes      | series tag     | town                                         | Town                                           | text      | text        |
| Yes      | numeric metric | number_of_hospitalization                    | Number of Hospitalization                      | number    | number      |
| Yes      | numeric metric | hospitalization_crude_rate_per_10_000        | Hospitalization Crude Rate (Per 10,000)        | number    | number      |
| Yes      | numeric metric | hospitalization_age_adjusted_rate_per_10_000 | Hospitalization Age-Adjusted Rate (Per 10,000) | number    | number      |
| Yes      | numeric metric | number_of_ed_visits                          | Number of ED Visits                            | number    | number      |
| Yes      | numeric metric | ed_visit_crude_rate_per_10_000               | ED Visit Crude Rate (Per 10,000)               | number    | number      |
| Yes      | numeric metric | ed_visit_age_adjusted_rate_per_10_000        | ED Visit Age-Adjusted Rate (Per 10,000)        | number    | number      |
```

## Time Field

```ls
Value = 2005
Format & Zone = yyyy
```

## Data Commands

```ls
series e:bimu-2gpn d:2005-01-01T00:00:00.000Z t:town=Andover m:hospitalization_crude_rate_per_10_000=6.1 m:ed_visit_crude_rate_per_10_000=33 m:hospitalization_age_adjusted_rate_per_10_000=7.1 m:ed_visit_age_adjusted_rate_per_10_000=40.2 m:number_of_hospitalization=10 m:number_of_ed_visits=54

series e:bimu-2gpn d:2005-01-01T00:00:00.000Z t:town=Ansonia m:hospitalization_crude_rate_per_10_000=16.4 m:ed_visit_crude_rate_per_10_000=116.1 m:hospitalization_age_adjusted_rate_per_10_000=16.9 m:ed_visit_age_adjusted_rate_per_10_000=120.7 m:number_of_hospitalization=152 m:number_of_ed_visits=1076

series e:bimu-2gpn d:2005-01-01T00:00:00.000Z t:town=Ashford m:hospitalization_crude_rate_per_10_000=12.2 m:ed_visit_crude_rate_per_10_000=35.6 m:hospitalization_age_adjusted_rate_per_10_000=11 m:ed_visit_age_adjusted_rate_per_10_000=36 m:number_of_hospitalization=27 m:number_of_ed_visits=79
```

## Meta Commands

```ls
metric m:number_of_hospitalization p:integer l:"Number of Hospitalization" t:dataTypeName=number

metric m:hospitalization_crude_rate_per_10_000 p:float l:"Hospitalization Crude Rate (Per 10,000)" t:dataTypeName=number

metric m:hospitalization_age_adjusted_rate_per_10_000 p:float l:"Hospitalization Age-Adjusted Rate (Per 10,000)" t:dataTypeName=number

metric m:number_of_ed_visits p:integer l:"Number of ED Visits" t:dataTypeName=number

metric m:ed_visit_crude_rate_per_10_000 p:float l:"ED Visit Crude Rate (Per 10,000)" t:dataTypeName=number

metric m:ed_visit_age_adjusted_rate_per_10_000 p:float l:"ED Visit Age-Adjusted Rate (Per 10,000)" t:dataTypeName=number

entity e:bimu-2gpn l:"Asthma Hospitalization and ED Visit (Primary Diagnosis) Crude and Age-Adjusted Rates by Town, 5-year period, 2005 to 2009" t:attribution="CT DPH: Community Health and Prevention Section" t:url=https://data.ct.gov/api/views/bimu-2gpn

property e:bimu-2gpn t:meta.view v:id=bimu-2gpn v:category="Health and Human Services" v:attributionLink=http://www.ct.gov/dph/asthma v:averageRating=0 v:name="Asthma Hospitalization and ED Visit (Primary Diagnosis) Crude and Age-Adjusted Rates by Town, 5-year period, 2005 to 2009" v:attribution="CT DPH: Community Health and Prevention Section"

property e:bimu-2gpn t:meta.view.license v:name="Public Domain"

property e:bimu-2gpn t:meta.view.owner v:id=dby8-627v v:screenName="Gary Archambault" v:displayName="Gary Archambault"

property e:bimu-2gpn t:meta.view.tableauthor v:id=dby8-627v v:screenName="Gary Archambault" v:roleName=editor v:displayName="Gary Archambault"
```

## Top Records

```ls
| town         | number_of_hospitalization | hospitalization_crude_rate_per_10_000 | hospitalization_age_adjusted_rate_per_10_000 | number_of_ed_visits | ed_visit_crude_rate_per_10_000 | ed_visit_age_adjusted_rate_per_10_000 | 
| ============ | ========================= | ===================================== | ============================================ | =================== | ============================== | ===================================== | 
| Andover      | 10                        | 6.1                                   | 7.1                                          | 54                  | 33                             | 40.200000000000003                    | 
| Ansonia      | 152                       | 16.399999999999999                    | 16.899999999999999                           | 1076                | 116.1                          | 120.7                                 | 
| Ashford      | 27                        | 12.2                                  | 11                                           | 79                  | 35.6                           | 36                                    | 
| Avon         | 35                        | 4.0999999999999996                    | 3.3                                          | 92                  | 10.7                           | 12.5                                  | 
| Barkhamsted  | 11                        | 6                                     | 6.3                                          | 76                  | 41.4                           | 45.2                                  | 
| Beacon Falls | 18                        | 6.3                                   | 6.3                                          | 122                 | 42.6                           | 46.7                                  | 
| Berlin       | 71                        | 7.1                                   | 6.7                                          | 217                 | 21.6                           | 26                                    | 
| Bethany      | 14                        | 5.0999999999999996                    | 6                                            | 56                  | 20.3                           | 28.7                                  | 
| Bethel       | 45                        | 4.9000000000000004                    | 4.8                                          | 266                 | 28.8                           | 32                                    | 
| Bethlehem    |                           |                                       |                                              | 32                  | 17.899999999999999             | 21.4                                  | 
```