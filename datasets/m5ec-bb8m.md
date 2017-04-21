# LADWP Solar Interconnection Time

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ladwp-solar-interconnection-time-c3b0a) |
| Metadata | [Link](https://data.lacity.org/api/views/m5ec-bb8m) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/m5ec-bb8m/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/m5ec-bb8m/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | m5ec-bb8m |
| Name | LADWP Solar Interconnection Time |
| Attribution | LADWP |
| Category | A Livable and Sustainable City |
| Tags | solar panels, interconnection |
| Created | 2014-05-23T23:15:51Z |
| Publication Date | 2014-05-23T23:18:43Z |

## Description

The average amount of days to interconnect solar panels

## Columns

```ls
| Included | Schema Type    | Field Name                 | Name                         | Data Type | Render Type |
| ======== | ============== | ========================== | ============================ | ========= | =========== |
| Yes      | time           | quarter_year               | Quarter-Year                 | text      | text        |
| Yes      | numeric metric | avg_interconnect_time_days | Avg Interconnect Time (days) | number    | number      |
```

## Time Field

```ls
Value = quarter_year
Format & Zone = QQQ-yyyy
```

## Data Commands

```ls
series e:m5ec-bb8m d:2011-01-01T00:00:00.000Z m:avg_interconnect_time_days=52

series e:m5ec-bb8m d:2011-04-01T00:00:00.000Z m:avg_interconnect_time_days=59

series e:m5ec-bb8m d:2011-07-01T00:00:00.000Z m:avg_interconnect_time_days=33
```

## Meta Commands

```ls
metric m:avg_interconnect_time_days p:integer l:"Avg Interconnect Time (days)" t:dataTypeName=number

entity e:m5ec-bb8m l:"LADWP Solar Interconnection Time" t:attribution=LADWP t:url=https://data.lacity.org/api/views/m5ec-bb8m

property e:m5ec-bb8m t:meta.view v:id=m5ec-bb8m v:category="A Livable and Sustainable City" v:averageRating=0 v:name="LADWP Solar Interconnection Time" v:attribution=LADWP

property e:m5ec-bb8m t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:m5ec-bb8m t:meta.view.owner v:id=hb8e-gdsp v:profileImageUrlMedium=/api/users/hb8e-gdsp/profile_images/THUMB v:profileImageUrlLarge=/api/users/hb8e-gdsp/profile_images/LARGE v:screenName="LA DWP OpenData" v:profileImageUrlSmall=/api/users/hb8e-gdsp/profile_images/TINY v:displayName="LA DWP OpenData"

property e:m5ec-bb8m t:meta.view.tableauthor v:id=7q7s-tyf3 v:screenName="Steve Baule" v:roleName=publisher v:displayName="Steve Baule"
```

## Top Records

```ls
| quarter_year | avg_interconnect_time_days | 
| ============ | ========================== | 
| Q1-2011      | 52                         | 
| Q2-2011      | 59                         | 
| Q3-2011      | 33                         | 
| Q4-2011      | 33                         | 
| Q1-2012      | 23                         | 
| Q2-2012      | 24                         | 
| Q3-2012      | 20                         | 
| Q4-2012      | 51                         | 
| Q1-2013      | 40                         | 
| Q2-2013      | 25                         | 
```