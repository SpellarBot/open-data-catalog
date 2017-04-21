# Hybrid Electric Vehicles, Registered 2015 (Source: 2016 US Clean Tech Leadership Index)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ninth-in-nation-2013-leed-green-building-source-u-s-green-building-council-7d442) |
| Metadata | [Link](https://data.hawaii.gov/api/views/rk4m-bf9e) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/rk4m-bf9e/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/rk4m-bf9e/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | rk4m-bf9e |
| Name | Hybrid Electric Vehicles, Registered 2015 (Source: 2016 US Clean Tech Leadership Index) |
| Created | 2014-02-18T22:43:23Z |
| Publication Date | 2016-11-28T23:57:24Z |

## Columns

```ls
| Included | Schema Type    | Field Name         | Name               | Data Type | Render Type |
| ======== | ============== | ================== | ================== | ========= | =========== |
| Yes      | series tag     | state              | State              | text      | text        |
| Yes      | numeric metric | rank               | Rank               | number    | number      |
| Yes      | numeric metric | hevs_per_1m_people | HEVs per 1M People | number    | number      |
| Yes      | numeric metric | total_hevs         | Total HEVs         | number    | number      |
```

## Time Field

```ls
Value = 2015
Format & Zone = yyyy
```

## Data Commands

```ls
series e:rk4m-bf9e d:2015-01-01T00:00:00.000Z t:state=California m:rank=1 m:hevs_per_1m_people=22940 m:total_hevs=897988

series e:rk4m-bf9e d:2015-01-01T00:00:00.000Z t:state=Washington m:rank=2 m:hevs_per_1m_people=18840 m:total_hevs=135093

series e:rk4m-bf9e d:2015-01-01T00:00:00.000Z t:state=Oregon m:rank=3 m:hevs_per_1m_people=18575 m:total_hevs=74837
```

## Meta Commands

```ls
metric m:rank p:integer l:Rank t:dataTypeName=number

metric m:hevs_per_1m_people p:integer l:"HEVs per 1M People" t:dataTypeName=number

metric m:total_hevs p:integer l:"Total HEVs" t:dataTypeName=number

entity e:rk4m-bf9e l:"Hybrid Electric Vehicles, Registered 2015 (Source: 2016 US Clean Tech Leadership Index)" t:url=https://data.hawaii.gov/api/views/rk4m-bf9e

property e:rk4m-bf9e t:meta.view v:id=rk4m-bf9e v:averageRating=0 v:name="Hybrid Electric Vehicles, Registered 2015 (Source: 2016 US Clean Tech Leadership Index)"

property e:rk4m-bf9e t:meta.view.owner v:id=vf6n-ptiq v:screenName=Kathy v:displayName=Kathy

property e:rk4m-bf9e t:meta.view.tableauthor v:id=vf6n-ptiq v:screenName=Kathy v:roleName=publisher v:displayName=Kathy
```

## Top Records

```ls
| state      | rank | hevs_per_1m_people | total_hevs | 
| ========== | ==== | ================== | ========== | 
| California | 1    | 22940              | 897988     | 
| Washington | 2    | 18840              | 135093     | 
| Oregon     | 3    | 18575              | 74837      | 
| Vermont    | 4    | 17168              | 10748      | 
| Hawaii     | 5    | 14776              | 21154      | 
```