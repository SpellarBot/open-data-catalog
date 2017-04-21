# WSeattle Winter2012

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/wseattle-winter2012-edae7) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/4wxe-trr7) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/4wxe-trr7/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/4wxe-trr7/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | 4wxe-trr7 |
| Name | WSeattle Winter2012 |
| Attribution | King County Ferry District |
| Category | Transportation |
| Tags | water taxi, sailing, schedule, west seattle |
| Created | 2012-08-30T22:21:41Z |
| Publication Date | 2012-08-30T23:17:30Z |

## Description

Water Taxi West Seattle Route schedule, winter 2012

## Columns

```ls
| Included | Schema Type | Field Name                 | Name                       | Data Type | Render Type |
| ======== | =========== | ========================== | ========================== | ========= | =========== |
| Yes      | series tag  | west_seattle_seacrest_park | West Seattle-Seacrest Park | text      | text        |
| Yes      | series tag  | seattle_waterfront_pier_50 | Seattle waterfront Pier 50 | text      | text        |
```

## Time Field

```ls
Value = 2012
Format & Zone = yyyy
```

## Data Commands

```ls
series e:4wxe-trr7 d:2012-01-01T00:00:00.000Z t:west_seattle_seacrest_park=--- t:seattle_waterfront_pier_50="6:00  a.m." m:row_number.4wxe-trr7=1

series e:4wxe-trr7 d:2012-01-01T00:00:00.000Z t:west_seattle_seacrest_park=--- t:seattle_waterfront_pier_50="3:45  p.m." m:row_number.4wxe-trr7=2

series e:4wxe-trr7 d:2012-01-01T00:00:00.000Z t:west_seattle_seacrest_park="8:45 a.m." t:seattle_waterfront_pier_50=--- m:row_number.4wxe-trr7=3
```

## Meta Commands

```ls
metric m:row_number.4wxe-trr7 p:long l:"Row Number"

entity e:4wxe-trr7 l:"WSeattle Winter2012" t:attribution="King County Ferry District" t:url=https://data.kingcounty.gov/api/views/4wxe-trr7

property e:4wxe-trr7 t:meta.view v:id=4wxe-trr7 v:category=Transportation v:attributionLink=http://www.kingcounty.gov/watertaxi/ v:averageRating=0 v:name="WSeattle Winter2012" v:attribution="King County Ferry District"

property e:4wxe-trr7 t:meta.view.license v:name="Public Domain"

property e:4wxe-trr7 t:meta.view.owner v:id=x8p2-hzee v:screenName=Lernerg v:displayName=Lernerg

property e:4wxe-trr7 t:meta.view.tableauthor v:id=x8p2-hzee v:screenName=Lernerg v:roleName=publisher v:displayName=Lernerg
```

## Top Records

```ls
| west_seattle_seacrest_park | seattle_waterfront_pier_50 | 
| ========================== | ========================== | 
| ---                        | 6:00 a.m.                  | 
| ---                        | 3:45 p.m.                  | 
| 8:45 a.m.                  | ---                        | 
| 6:15 a.m.                  | 6:30 a.m.                  | 
| 6:45 a.m.                  | 7:00 a.m.                  | 
| 7:15 a.m.                  | 7:30 a.m.                  | 
| 7:45 a.m.                  | 8:00 a.m.                  | 
| 8:15 a.m.                  | 8:30 a.m.                  | 
| 4:00 p.m.                  | 4:15 p.m.                  | 
| 4:30 p.m.                  | 4:45 p.m.                  | 
```