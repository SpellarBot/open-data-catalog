# Northeast Complete

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/northeast-complete-cd436) |
| Metadata | [Link](https://data.wa.gov/api/views/t8dk-esb7) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/t8dk-esb7/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/t8dk-esb7/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | t8dk-esb7 |
| Name | Northeast Complete |
| Tags | state-of-the-salmon |
| Created | 2015-01-02T20:10:53Z |
| Publication Date | 2015-02-13T21:08:10Z |

## Columns

```ls
| Included | Schema Type    | Field Name               | Name                     | Data Type | Render Type |
| ======== | ============== | ======================== | ======================== | ========= | =========== |
| Yes      | series tag     | region                   | Region                   | text      | text        |
| Yes      | time           | year                     | Year                     | number    | number      |
| Yes      | numeric metric | estuary_acres_treated    | Estuary Acres Treated    | number    | number      |
| Yes      | numeric metric | estuary_projects         | Estuary Projects         | number    | number      |
| Yes      | numeric metric | riparian_acres_treated   | Riparian Acres Treated   | number    | number      |
| Yes      | numeric metric | riparian_acre_projects   | Riparian Acre Projects   | number    | number      |
| Yes      | numeric metric | riparian_miles_treated   | Riparian Miles Treated   | number    | number      |
| Yes      | numeric metric | riparian_mile_projects   | Riparian Mile Projects   | number    | number      |
| Yes      | numeric metric | stream_miles_opened      | Stream Miles Opened      | number    | number      |
| Yes      | numeric metric | stream_mile_projects     | Stream Mile Projects     | number    | number      |
| Yes      | numeric metric | barriers_removed_altered | Barriers Removed/Altered | number    | number      |
| Yes      | numeric metric | barrier_projects         | Barrier Projects         | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:t8dk-esb7 d:2005-01-01T00:00:00.000Z t:region=Northeast m:barriers_removed_altered=23 m:estuary_acres_treated=0 m:riparian_acre_projects=1 m:riparian_acres_treated=6 m:riparian_miles_treated=0 m:stream_miles_opened=9 m:stream_mile_projects=1 m:riparian_mile_projects=0 m:estuary_projects=0 m:barrier_projects=1

series e:t8dk-esb7 d:2006-01-01T00:00:00.000Z t:region=Northeast m:barriers_removed_altered=29 m:estuary_acres_treated=0 m:riparian_acre_projects=0 m:riparian_acres_treated=0 m:riparian_miles_treated=0 m:stream_miles_opened=0 m:stream_mile_projects=0 m:riparian_mile_projects=0 m:estuary_projects=0 m:barrier_projects=0

series e:t8dk-esb7 d:2007-01-01T00:00:00.000Z t:region=Northeast m:barriers_removed_altered=20 m:estuary_acres_treated=0 m:riparian_acre_projects=0 m:riparian_acres_treated=0 m:riparian_miles_treated=0 m:stream_miles_opened=0 m:stream_mile_projects=0 m:riparian_mile_projects=0 m:estuary_projects=0 m:barrier_projects=0
```

## Meta Commands

```ls
metric m:estuary_acres_treated p:integer l:"Estuary Acres Treated" t:dataTypeName=number

metric m:estuary_projects p:integer l:"Estuary Projects" t:dataTypeName=number

metric m:riparian_acres_treated p:float l:"Riparian Acres Treated" t:dataTypeName=number

metric m:riparian_acre_projects p:integer l:"Riparian Acre Projects" t:dataTypeName=number

metric m:riparian_miles_treated p:float l:"Riparian Miles Treated" t:dataTypeName=number

metric m:riparian_mile_projects p:integer l:"Riparian Mile Projects" t:dataTypeName=number

metric m:stream_miles_opened p:float l:"Stream Miles Opened" t:dataTypeName=number

metric m:stream_mile_projects p:integer l:"Stream Mile Projects" t:dataTypeName=number

metric m:barriers_removed_altered p:integer l:"Barriers Removed/Altered" t:dataTypeName=number

metric m:barrier_projects p:integer l:"Barrier Projects" t:dataTypeName=number

entity e:t8dk-esb7 l:"Northeast Complete" t:url=https://data.wa.gov/api/views/t8dk-esb7

property e:t8dk-esb7 t:meta.view v:id=t8dk-esb7 v:averageRating=0 v:name="Northeast Complete"

property e:t8dk-esb7 t:meta.view.owner v:id=fuyk-waw8 v:screenName="Jennifer Johnson" v:displayName="Jennifer Johnson"

property e:t8dk-esb7 t:meta.view.tableauthor v:id=fuyk-waw8 v:screenName="Jennifer Johnson" v:roleName=publisher v:displayName="Jennifer Johnson"
```