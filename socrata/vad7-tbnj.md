# DBEDT Energy Savings Performance Contracting Per Capita

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dbedt-energy-savings-performance-contracting-per-capita-5023a) |
| Metadata | [Link](https://data.hawaii.gov/api/views/vad7-tbnj) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/vad7-tbnj/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/vad7-tbnj/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | vad7-tbnj |
| Name | DBEDT Energy Savings Performance Contracting Per Capita |
| Attribution | Department of Economic Development and Tourism |
| Category | Economic Development |
| Tags | energy |
| Created | 2012-08-28T19:38:49Z |
| Publication Date | 2012-08-29T01:26:48Z |

## Columns

```ls
| Included | Schema Type    | Field Name                    | Name                              | Data Type | Render Type |
| ======== | ============== | ============================= | ================================= | ========= | =========== |
| Yes      | numeric metric | dollars_per_capita            | Dollars per Capita ($)            | money     | money       |
| Yes      | numeric metric | total_performance_contracting | Total Performance Contracting ($) | money     | money       |
| Yes      | time           | jobs_created_job_year         | Jobs Created (Job Year)           | number    | number      |
```

## Time Field

```ls
Value = jobs_created_job_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:vad7-tbnj d:1402-01-01T00:00:00.000Z m:dollars_per_capita=90.27 m:total_performance_contracting=129000000

series e:vad7-tbnj d:1078-01-01T00:00:00.000Z m:dollars_per_capita=77.76 m:total_performance_contracting=99161315

series e:vad7-tbnj d:4975-01-01T00:00:00.000Z m:dollars_per_capita=71.53 m:total_performance_contracting=457696106
```

## Meta Commands

```ls
metric m:dollars_per_capita p:double l:"Dollars per Capita ($)" t:dataTypeName=money

metric m:total_performance_contracting p:integer l:"Total Performance Contracting ($)" t:dataTypeName=money

entity e:vad7-tbnj l:"DBEDT Energy Savings Performance Contracting Per Capita" t:attribution="Department of Economic Development and Tourism" t:url=https://data.hawaii.gov/api/views/vad7-tbnj

property e:vad7-tbnj t:meta.view v:id=vad7-tbnj v:category="Economic Development" v:attributionLink=http://hawaii.gov/dbedt v:averageRating=0 v:name="DBEDT Energy Savings Performance Contracting Per Capita" v:attribution="Department of Economic Development and Tourism"

property e:vad7-tbnj t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:vad7-tbnj t:meta.view.owner v:id=uaqq-pakk v:screenName="Douglas Oshiro" v:displayName="Douglas Oshiro"

property e:vad7-tbnj t:meta.view.tableauthor v:id=uaqq-pakk v:screenName="Douglas Oshiro" v:displayName="Douglas Oshiro"
```

## Top Records

```ls
| dollars_per_capita | total_performance_contracting | jobs_created_job_year | 
| ================== | ============================= | ===================== | 
| 90.27              | 129000000                     | 1402                  | 
| 77.76              | 99161315                      | 1078                  | 
| 71.53              | 457696106                     | 4975                  | 
| 66.89              | 165195000                     | 1796                  | 
| 63.69              | 174796442                     | 1900                  | 
```