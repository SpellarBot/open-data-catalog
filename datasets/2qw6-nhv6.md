# Proportion of restaurant inspections with red violations

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/proportion-of-restaurant-inspections-with-red-violations-4d85f) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/2qw6-nhv6) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/2qw6-nhv6/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/2qw6-nhv6/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | 2qw6-nhv6 |
| Name | Proportion of restaurant inspections with red violations |
| Attribution | Public Health: Seattle & King County; Environmental Health Division |
| Category | Health |
| Tags | restaurant, inspections, health |
| Created | 2013-02-13T19:27:54Z |
| Publication Date | 2013-02-13T19:40:15Z |

## Description

Five-year listing of data. Data source: https://data.kingcounty.gov/Government/Food-Establishment-Inspection-Data/f29f-zza5

## Columns

```ls
| Included | Schema Type    | Field Name | Name       | Data Type | Render Type |
| ======== | ============== | ========== | ========== | ========= | =========== |
| Yes      | time           | year       | Year       | number    | number      |
| Yes      | numeric metric | violations | Violations | percent   | percent     |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:2qw6-nhv6 d:2007-01-01T00:00:00.000Z m:violations=41

series e:2qw6-nhv6 d:2008-01-01T00:00:00.000Z m:violations=44

series e:2qw6-nhv6 d:2009-01-01T00:00:00.000Z m:violations=40
```

## Meta Commands

```ls
metric m:violations p:integer l:Violations d:"Percent of red violations" t:dataTypeName=percent

entity e:2qw6-nhv6 l:"Proportion of restaurant inspections with red violations" t:attribution="Public Health: Seattle & King County; Environmental Health Division" t:url=https://data.kingcounty.gov/api/views/2qw6-nhv6

property e:2qw6-nhv6 t:meta.view v:id=2qw6-nhv6 v:category=Health v:attributionLink=http://www.kingcounty.gov/health v:averageRating=0 v:name="Proportion of restaurant inspections with red violations" v:attribution="Public Health: Seattle & King County; Environmental Health Division"

property e:2qw6-nhv6 t:meta.view.license v:name="Public Domain"

property e:2qw6-nhv6 t:meta.view.owner v:id=7ja6-sv4x v:profileImageUrlMedium=/api/users/7ja6-sv4x/profile_images/THUMB v:profileImageUrlLarge=/api/users/7ja6-sv4x/profile_images/LARGE v:screenName="King County Open Data admin" v:profileImageUrlSmall=/api/users/7ja6-sv4x/profile_images/TINY v:lastNotificationSeenAt=1492197205 v:displayName="King County Open Data admin"

property e:2qw6-nhv6 t:meta.view.tableauthor v:id=7ja6-sv4x v:profileImageUrlMedium=/api/users/7ja6-sv4x/profile_images/THUMB v:profileImageUrlLarge=/api/users/7ja6-sv4x/profile_images/LARGE v:screenName="King County Open Data admin" v:profileImageUrlSmall=/api/users/7ja6-sv4x/profile_images/TINY v:roleName=administrator v:lastNotificationSeenAt=1492197205 v:displayName="King County Open Data admin"
```

## Top Records

```ls
| year | violations | 
| ==== | ========== | 
| 2007 | 41         | 
| 2008 | 44         | 
| 2009 | 40         | 
| 2010 | 41         | 
| 2011 | 38         | 
```