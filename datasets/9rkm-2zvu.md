# Statewide Energy Star Buildings

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/statewide-leed-certified-buildings-54340) |
| Metadata | [Link](https://data.hawaii.gov/api/views/9rkm-2zvu) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/9rkm-2zvu/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/9rkm-2zvu/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | 9rkm-2zvu |
| Name | Statewide Energy Star Buildings |
| Created | 2013-08-02T20:16:17Z |
| Publication Date | 2017-02-22T23:33:46Z |

## Columns

```ls
| Included | Schema Type    | Field Name     | Name                                | Data Type | Render Type |
| ======== | ============== | ============== | =================================== | ========= | =========== |
| Yes      | time           | year_certified | Year Certified                      | number    | text        |
| Yes      | numeric metric | certified      | DBEDT State Energy Star Program     | number    | number      |
| Yes      | numeric metric | silver         | Non-State Energy Star Buildings     | number    | number      |
| Yes      | numeric metric | gold           | DBEDT Non-State Energy Star Program | number    | number      |
| Yes      | numeric metric | platinum       | State Energy Star Buildings         | number    | number      |
```

## Time Field

```ls
Value = year_certified
Format & Zone = yyyy
```

## Data Commands

```ls
series e:9rkm-2zvu d:2009-01-01T00:00:00.000Z m:certified=7 m:platinum=4 m:silver=26 m:gold=0

series e:9rkm-2zvu d:2010-01-01T00:00:00.000Z m:certified=9 m:platinum=6 m:silver=26 m:gold=3

series e:9rkm-2zvu d:2011-01-01T00:00:00.000Z m:certified=8 m:platinum=10 m:silver=25 m:gold=9
```

## Meta Commands

```ls
metric m:certified p:integer l:"DBEDT State Energy Star Program" t:dataTypeName=number

metric m:silver p:integer l:"Non-State Energy Star Buildings" t:dataTypeName=number

metric m:gold p:integer l:"DBEDT Non-State Energy Star Program" t:dataTypeName=number

metric m:platinum p:integer l:"State Energy Star Buildings" t:dataTypeName=number

entity e:9rkm-2zvu l:"Statewide Energy Star Buildings" t:url=https://data.hawaii.gov/api/views/9rkm-2zvu

property e:9rkm-2zvu t:meta.view v:id=9rkm-2zvu v:averageRating=0 v:name="Statewide Energy Star Buildings"

property e:9rkm-2zvu t:meta.view.owner v:id=vf6n-ptiq v:screenName=Kathy v:displayName=Kathy

property e:9rkm-2zvu t:meta.view.tableauthor v:id=vf6n-ptiq v:screenName=Kathy v:roleName=publisher v:displayName=Kathy
```

## Top Records

```ls
| year_certified | certified | silver | gold | platinum | 
| ============== | ========= | ====== | ==== | ======== | 
| 2009           | 7         | 26     | 0    | 4        | 
| 2010           | 9         | 26     | 3    | 6        | 
| 2011           | 8         | 25     | 9    | 10       | 
| 2012           | 11        | 39     | 6    | 10       | 
| 2013           | 0         | 50     | 0    | 21       | 
| 2014           | 7         | 52     | 0    | 15       | 
| 2015           | 67        | 59     | 0    | 16       | 
| 2016           | 24        | 60     | 0    | 83       | 
```