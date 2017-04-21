# On Time Performance

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/on-time-performance) |
| Metadata | [Link](https://data.maryland.gov/api/views/s7x9-aarw) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/s7x9-aarw/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/s7x9-aarw/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | s7x9-aarw |
| Name | On Time Performance |
| Attribution | Maryland Transit Administration |
| Category | Transportation |
| Tags | mta, maryland transit administration, performance, transportation |
| Created | 2016-06-08T18:28:39Z |
| Publication Date | 2016-09-07T17:54:23Z |

## Description

On Time Performance on a fiscal year basis for Maryland Transit Administration services; Local Bus, Light Rail, Metro Rail, Mobility, and MARC

## Columns

```ls
| Included | Schema Type    | Field Name           | Name                 | Data Type     | Render Type   |
| ======== | ============== | ==================== | ==================== | ============= | ============= |
| Yes      | time           | date                 | Date                 | calendar_date | calendar_date |
| Yes      | series tag     | fiscal_year          | Fiscal Year          | text          | text          |
| Yes      | numeric metric | core_bus             | Core Bus             | percent       | percent       |
| Yes      | numeric metric | metro                | Metro                | percent       | percent       |
| Yes      | numeric metric | light_rail           | Light Rail           | percent       | percent       |
| Yes      | numeric metric | marc                 | MARC                 | percent       | percent       |
| Yes      | numeric metric | mobility_taxi_access | Mobility/Taxi Access | percent       | percent       |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:s7x9-aarw d:2010-07-01T00:00:00.000Z t:fiscal_year="FY 2011" m:core_bus=85 m:mobility_taxi_access=89 m:marc=89 m:metro=97 m:light_rail=98

series e:s7x9-aarw d:2011-07-01T00:00:00.000Z t:fiscal_year="FY 2012" m:core_bus=83 m:mobility_taxi_access=90 m:marc=93 m:metro=96 m:light_rail=96

series e:s7x9-aarw d:2012-07-01T00:00:00.000Z t:fiscal_year="FY 2013" m:core_bus=82 m:mobility_taxi_access=89 m:marc=93 m:metro=97 m:light_rail=97
```

## Meta Commands

```ls
metric m:core_bus p:float l:"Core Bus" t:dataTypeName=percent

metric m:metro p:float l:Metro t:dataTypeName=percent

metric m:light_rail p:float l:"Light Rail" t:dataTypeName=percent

metric m:marc p:float l:MARC t:dataTypeName=percent

metric m:mobility_taxi_access p:float l:"Mobility/Taxi Access" t:dataTypeName=percent

entity e:s7x9-aarw l:"On Time Performance" t:attribution="Maryland Transit Administration" t:url=https://data.maryland.gov/api/views/s7x9-aarw

property e:s7x9-aarw t:meta.view v:id=s7x9-aarw v:category=Transportation v:attributionLink=https://mta.maryland.gov/ v:averageRating=0 v:name="On Time Performance" v:attribution="Maryland Transit Administration"

property e:s7x9-aarw t:meta.view.license v:name="Public Domain"

property e:s7x9-aarw t:meta.view.owner v:id=28y5-7nmz v:screenName=bsmalls1 v:displayName=bsmalls1

property e:s7x9-aarw t:meta.view.tableauthor v:id=28y5-7nmz v:screenName=bsmalls1 v:roleName=editor v:displayName=bsmalls1
```

## Top Records

```ls
| date                | fiscal_year | core_bus | metro | light_rail | marc  | mobility_taxi_access | 
| =================== | =========== | ======== | ===== | ========== | ===== | ==================== | 
| 2010-07-01T00:00:00 | FY 2011     | 85.00    | 97.00 | 98.00      | 89.00 | 89.00                | 
| 2011-07-01T00:00:00 | FY 2012     | 83.00    | 96.00 | 96.00      | 93.00 | 90.00                | 
| 2012-07-01T00:00:00 | FY 2013     | 82.00    | 97.00 | 97.00      | 93.00 | 89.00                | 
| 2013-07-01T00:00:00 | FY 2014     | 81.00    | 96.00 | 96.00      | 92.00 | 91.00                | 
| 2014-07-01T00:00:00 | FY 2015     | 81.00    | 95.00 | 97.00      | 92.00 | 88.00                | 
```