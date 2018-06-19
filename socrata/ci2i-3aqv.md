# Cook County Municipalities, by Percent of Population with at Least an Associates Degree, ACS 2005-2009

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/cook-county-municipalities-by-percent-of-population-with-at-least-an-associates-degre-2005-79734) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/ci2i-3aqv) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/ci2i-3aqv/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/ci2i-3aqv/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | ci2i-3aqv |
| Name | Cook County Municipalities, by Percent of Population with at Least an Associates Degree, ACS 2005-2009 |
| Attribution | Chicago Metropolitan Agency for Planning MetroPulse |
| Category | Economic Development |
| Created | 2012-08-30T21:08:58Z |
| Publication Date | 2014-10-09T22:08:16Z |

## Description

Courtesy of MetroPulse

## Columns

```ls
| Included | Schema Type    | Field Name                                                   | Name                                                          | Data Type | Render Type |
| ======== | ============== | ============================================================ | ============================================================= | ========= | =========== |
| Yes      | series tag     | municipality                                                 | Municipality                                                  | text      | text        |
| Yes      | numeric metric | percent_of_population_25_with_at_least_an_associate_s_degree | Percent of Population 25+ with at Least an Associate's Degree | percent   | percent     |
```

## Time Field

```ls
Value = 2005
Format & Zone = yyyy
```

## Data Commands

```ls
series e:ci2i-3aqv d:2005-01-01T00:00:00.000Z t:municipality="Mount Prospect" m:percent_of_population_25_with_at_least_an_associate_s_degree=45.6

series e:ci2i-3aqv d:2005-01-01T00:00:00.000Z t:municipality=Glenwood m:percent_of_population_25_with_at_least_an_associate_s_degree=33.1

series e:ci2i-3aqv d:2005-01-01T00:00:00.000Z t:municipality=Crestwood m:percent_of_population_25_with_at_least_an_associate_s_degree=20.8
```

## Meta Commands

```ls
metric m:percent_of_population_25_with_at_least_an_associate_s_degree p:float l:"Percent of Population 25+ with at Least an Associate's Degree" t:dataTypeName=percent

entity e:ci2i-3aqv l:"Cook County Municipalities, by Percent of Population with at Least an Associates Degree, ACS 2005-2009" t:attribution="Chicago Metropolitan Agency for Planning MetroPulse" t:url=https://datacatalog.cookcountyil.gov/api/views/ci2i-3aqv

property e:ci2i-3aqv t:meta.view v:id=ci2i-3aqv v:category="Economic Development" v:attributionLink=https://www.cmap.illinois.gov/ v:averageRating=0 v:name="Cook County Municipalities, by Percent of Population with at Least an Associates Degree, ACS 2005-2009" v:attribution="Chicago Metropolitan Agency for Planning MetroPulse"

property e:ci2i-3aqv t:meta.view.license v:name="Public Domain"

property e:ci2i-3aqv t:meta.view.owner v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"

property e:ci2i-3aqv t:meta.view.tableauthor v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"
```

## Top Records

```ls
| municipality     | percent_of_population_25_with_at_least_an_associate_s_degree | 
| ================ | ============================================================ | 
| Mount Prospect   | 45.6                                                         | 
| Glenwood         | 33.1                                                         | 
| Crestwood        | 20.8                                                         | 
| Lynwood          | 30.3                                                         | 
| Willow Springs   | 42.9                                                         | 
| Prospect Heights | 38                                                           | 
| Lemont           | 44.7                                                         | 
| Summit           | 17.1                                                         | 
| Steger           | 25.4                                                         | 
| Sauk Village     | 20.2                                                         | 
```