# September 2014 FMU Monthly Report WQ EX data

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/september-2014-fmu-monthly-report-wq-ex-data-c3e7d) |
| Metadata | [Link](https://data.wa.gov/api/views/mcjf-t2vf) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/mcjf-t2vf/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/mcjf-t2vf/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | mcjf-t2vf |
| Name | September 2014 FMU Monthly Report WQ EX data |
| Created | 2014-11-07T19:19:21Z |
| Publication Date | 2015-03-17T18:55:39Z |

## Columns

```ls
| Included | Schema Type    | Field Name | Name      | Data Type | Render Type |
| ======== | ============== | ========== | ========= | ========= | =========== |
| Yes      | series tag     | parameter  | Parameter | text      | text        |
| Yes      | numeric metric | centeral   | Centeral  | percent   | percent     |
| Yes      | numeric metric | eastern    | Eastern   | percent   | percent     |
| Yes      | numeric metric | northwest  | Northwest | percent   | percent     |
| Yes      | numeric metric | southwest  | Southwest | percent   | percent     |
```

## Time Field

```ls
Value = 2014
Format & Zone = yyyy
```

## Data Commands

```ls
series e:mcjf-t2vf d:2014-01-01T00:00:00.000Z t:parameter="5 Yr September Average" m:southwest=20 m:northwest=27 m:eastern=45 m:centeral=49

series e:mcjf-t2vf d:2014-01-01T00:00:00.000Z t:parameter="Monthly Average" m:southwest=37 m:northwest=36 m:eastern=91 m:centeral=38
```

## Meta Commands

```ls
metric m:centeral p:integer l:Centeral t:dataTypeName=percent

metric m:eastern p:integer l:Eastern t:dataTypeName=percent

metric m:northwest p:integer l:Northwest t:dataTypeName=percent

metric m:southwest p:integer l:Southwest t:dataTypeName=percent

entity e:mcjf-t2vf l:"September 2014 FMU Monthly Report WQ EX data" t:url=https://data.wa.gov/api/views/mcjf-t2vf

property e:mcjf-t2vf t:meta.view d:2017-06-09T13:51:36.021Z v:id=mcjf-t2vf v:averageRating=0 v:name="September 2014 FMU Monthly Report WQ EX data"

property e:mcjf-t2vf t:meta.view.owner d:2017-06-09T13:51:36.021Z v:id=q8y9-svx9 v:profileImageUrlMedium=/api/users/q8y9-svx9/profile_images/THUMB v:profileImageUrlLarge=/api/users/q8y9-svx9/profile_images/LARGE v:screenName="Markus.Von Prause@ecy.wa.gov" v:profileImageUrlSmall=/api/users/q8y9-svx9/profile_images/TINY v:displayName="Markus.Von Prause@ecy.wa.gov"

property e:mcjf-t2vf t:meta.view.tableauthor d:2017-06-09T13:51:36.021Z v:id=q8y9-svx9 v:profileImageUrlMedium=/api/users/q8y9-svx9/profile_images/THUMB v:profileImageUrlLarge=/api/users/q8y9-svx9/profile_images/LARGE v:screenName="Markus.Von Prause@ecy.wa.gov" v:profileImageUrlSmall=/api/users/q8y9-svx9/profile_images/TINY v:roleName=publisher v:displayName="Markus.Von Prause@ecy.wa.gov"
```

## Top Records

```ls
| parameter              | centeral | eastern | northwest | southwest | 
| ====================== | ======== | ======= | ========= | ========= | 
| 5 Yr September Average | 49       | 45      | 27        | 20        | 
| Monthly Average        | 38       | 91      | 36        | 37        | 
```