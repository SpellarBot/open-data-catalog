# Cook County Municipalities, Percent of Population Below Poverty Level, 2005-09 ACS

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/cook-county-municipalities-percent-of-population-below-poverty-level-2005-09-acs-3721c) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/8ayh-a99a) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/8ayh-a99a/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/8ayh-a99a/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | 8ayh-a99a |
| Name | Cook County Municipalities, Percent of Population Below Poverty Level, 2005-09 ACS |
| Attribution | Chicago Metropolitan Agency for Planning MetroPulse |
| Category | Economic Development |
| Created | 2012-08-30T20:41:04Z |
| Publication Date | 2014-10-09T21:37:30Z |

## Description

Courtesy of MetroPulse

## Columns

```ls
| Included | Schema Type    | Field Name                         | Name                               | Data Type | Render Type |
| ======== | ============== | ================================== | ================================== | ========= | =========== |
| Yes      | series tag     | municipality                       | Municipality                       | text      | text        |
| Yes      | numeric metric | percent_living_below_poverty_level | Percent Living Below Poverty Level | number    | number      |
| Yes      | series tag     | location                           | Location                           | text      | text        |
```

## Time Field

```ls
Value = 2005
Format & Zone = yyyy
```

## Data Commands

```ls
series e:8ayh-a99a d:2005-01-01T00:00:00.000Z t:location="Mount Prospect" t:municipality="Mount Prospect" m:percent_living_below_poverty_level=5.9

series e:8ayh-a99a d:2005-01-01T00:00:00.000Z t:location="Hoffman Estates" t:municipality="Hoffman Estates" m:percent_living_below_poverty_level=5.7

series e:8ayh-a99a d:2005-01-01T00:00:00.000Z t:location=Lansing t:municipality=Lansing m:percent_living_below_poverty_level=10.6
```

## Meta Commands

```ls
metric m:percent_living_below_poverty_level p:float l:"Percent Living Below Poverty Level" t:dataTypeName=number

entity e:8ayh-a99a l:"Cook County Municipalities, Percent of Population Below Poverty Level, 2005-09 ACS" t:attribution="Chicago Metropolitan Agency for Planning MetroPulse" t:url=https://datacatalog.cookcountyil.gov/api/views/8ayh-a99a

property e:8ayh-a99a t:meta.view v:id=8ayh-a99a v:category="Economic Development" v:attributionLink=https://www.cmap.illinois.gov/ v:averageRating=0 v:name="Cook County Municipalities, Percent of Population Below Poverty Level, 2005-09 ACS" v:attribution="Chicago Metropolitan Agency for Planning MetroPulse"

property e:8ayh-a99a t:meta.view.license v:name="Public Domain"

property e:8ayh-a99a t:meta.view.owner v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"

property e:8ayh-a99a t:meta.view.tableauthor v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"
```

## Top Records

```ls
| municipality     | percent_living_below_poverty_level | location         | 
| ================ | ================================== | ================ | 
| Mount Prospect   | 5.9                                | Mount Prospect   | 
| Hoffman Estates  | 5.7                                | Hoffman Estates  | 
| Lansing          | 10.6                               | Lansing          | 
| Barrington Hills | 2.8                                | Barrington Hills | 
| Northbrook       | 2.9                                | Northbrook       | 
| Rosemont         | 19.9                               | Rosemont         | 
| Stickney         | 9.5                                | Stickney         | 
| Calumet City     | 16.8                               | Calumet City     | 
| Chicago Heights  | 23.6                               | Chicago Heights  | 
| Phoenix          | 13.6                               | Phoenix          | 
```