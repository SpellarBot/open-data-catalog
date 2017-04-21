# Ofm April1 Population Change And Rank

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ofm-april1-population-change-and-rank) |
| Metadata | [Link](https://data.wa.gov/api/views/9aqx-raft) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/9aqx-raft/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/9aqx-raft/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | 9aqx-raft |
| Name | Ofm April1 Population Change And Rank |
| Category | Natural Resources & Environment |
| Tags | state of salmon |
| Created | 2016-11-29T21:46:01Z |
| Publication Date | 2016-11-29T22:06:28Z |

## Description

+++++++++++++++++++

## Columns

```ls
| Included | Schema Type    | Field Name               | Name                     | Data Type | Render Type |
| ======== | ============== | ======================== | ======================== | ========= | =========== |
| No       | time           | :updated_at              | updated_at               | meta_data | meta_data   |
| Yes      | series tag     | county                   | County                   | text      | text        |
| Yes      | numeric metric | 2011_population_estimate | 2011 Population Estimate | number    | number      |
| Yes      | numeric metric | 2012_population_estimate | 2012 Population Estimate | number    | number      |
| Yes      | numeric metric | 2013_population_estimate | 2013 Population Estimate | number    | number      |
| Yes      | numeric metric | 2014_population_estimate | 2014 Population Estimate | number    | number      |
| Yes      | numeric metric | 2015_population_estimate | 2015 Population Estimate | number    | number      |
| Yes      | numeric metric | 2016_population_estimate | 2016 Population Estimate | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:9aqx-raft d:2016-11-29T22:03:47.000Z t:county=Adams m:2012_population_estimate=0 m:2011_population_estimate=0 m:2015_population_estimate=0 m:2016_population_estimate=0 m:2013_population_estimate=0 m:2014_population_estimate=0

series e:9aqx-raft d:2016-11-29T22:03:47.000Z t:county=Asotin m:2012_population_estimate=0 m:2011_population_estimate=0 m:2015_population_estimate=0 m:2016_population_estimate=0 m:2013_population_estimate=0 m:2014_population_estimate=0

series e:9aqx-raft d:2016-11-29T22:03:47.000Z t:county=Benton m:2012_population_estimate=0 m:2011_population_estimate=0 m:2015_population_estimate=0 m:2016_population_estimate=0 m:2013_population_estimate=0 m:2014_population_estimate=0
```

## Meta Commands

```ls
metric m:2011_population_estimate p:integer l:"2011 Population Estimate" t:dataTypeName=number

metric m:2012_population_estimate p:integer l:"2012 Population Estimate" t:dataTypeName=number

metric m:2013_population_estimate p:integer l:"2013 Population Estimate" t:dataTypeName=number

metric m:2014_population_estimate p:integer l:"2014 Population Estimate" t:dataTypeName=number

metric m:2015_population_estimate p:integer l:"2015 Population Estimate" t:dataTypeName=number

metric m:2016_population_estimate p:integer l:"2016 Population Estimate" t:dataTypeName=number

entity e:9aqx-raft l:"Ofm April1 Population Change And Rank" t:url=https://data.wa.gov/api/views/9aqx-raft

property e:9aqx-raft t:meta.view v:id=9aqx-raft v:category="Natural Resources & Environment" v:averageRating=0 v:name="Ofm April1 Population Change And Rank"

property e:9aqx-raft t:meta.view.owner v:id=fuyk-waw8 v:screenName="Jennifer Johnson" v:displayName="Jennifer Johnson"

property e:9aqx-raft t:meta.view.tableauthor v:id=fuyk-waw8 v:screenName="Jennifer Johnson" v:roleName=publisher v:displayName="Jennifer Johnson"
```

## Top Records

```ls
| :updated_at | county   | 2011_population_estimate | 2012_population_estimate | 2013_population_estimate | 2014_population_estimate | 2015_population_estimate | 2016_population_estimate | 
| =========== | ======== | ======================== | ======================== | ======================== | ======================== | ======================== | ======================== | 
| 1480457027  | Adams    | 0                        | 0                        | 0                        | 0                        | 0                        | 0                        | 
| 1480457027  | Asotin   | 0                        | 0                        | 0                        | 0                        | 0                        | 0                        | 
| 1480457027  | Benton   | 0                        | 0                        | 0                        | 0                        | 0                        | 0                        | 
| 1480457027  | Chelan   | 0                        | 0                        | 0                        | 0                        | 0                        | 0                        | 
| 1480457027  | Clallam  | 0                        | 0                        | 0                        | 0                        | 0                        | 0                        | 
| 1480457027  | Clark    | 0                        | 0                        | 0                        | 0                        | 0                        | 0                        | 
| 1480457027  | Columbia | 4100                     | 4100                     | 4100                     | 4080                     | 4090                     | 4050                     | 
| 1480457027  | Cowlitz  | 102700                   | 103050                   | 103300                   | 103700                   | 104280                   | 104850                   | 
| 1480457027  | Douglas  | 38650                    | 38900                    | 39280                    | 39700                    | 39990                    | 40720                    | 
| 1480457027  | Ferry    | 7600                     | 7650                     | 7650                     | 7660                     | 7710                     | 7700                     | 
```