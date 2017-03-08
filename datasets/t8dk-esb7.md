# Northeast Complete

## Dataset

* [Dataset URL](https://data.wa.gov/api/views/t8dk-esb7/rows.json?max_rows=100)
* [Catalog URL](https://catalog.data.gov/dataset/northeast-complete-cd436)
* [Metadata URL](https://data.wa.gov/api/views/t8dk-esb7)
* Id = t8dk-esb7
* Name = Northeast Complete
* Tags = [state-of-the-salmon]
* Created = 2015-01-02T20:10:53Z
* Publication Date = 2015-02-13T21:08:10Z
* Rows Updated = 2015-02-13T21:08:07Z

## Description



## Columns

```ls
| Name                     | Field Name               | Data Type | Render Type | Schema Type    | Included | 
| ======================== | ======================== | ========= | =========== | ============== | ======== | 
| Region                   | region                   | text      | text        | series tag     | Yes      | 
| Year                     | year                     | number    | number      | time           | Yes      | 
| Estuary Acres Treated    | estuary_acres_treated    | number    | number      | numeric metric | Yes      | 
| Estuary Projects         | estuary_projects         | number    | number      | numeric metric | Yes      | 
| Riparian Acres Treated   | riparian_acres_treated   | number    | number      | numeric metric | Yes      | 
| Riparian Acre Projects   | riparian_acre_projects   | number    | number      | numeric metric | Yes      | 
| Riparian Miles Treated   | riparian_miles_treated   | number    | number      | numeric metric | Yes      | 
| Riparian Mile Projects   | riparian_mile_projects   | number    | number      | numeric metric | Yes      | 
| Stream Miles Opened      | stream_miles_opened      | number    | number      | numeric metric | Yes      | 
| Stream Mile Projects     | stream_mile_projects     | number    | number      | numeric metric | Yes      | 
| Barriers Removed/Altered | barriers_removed_altered | number    | number      | numeric metric | Yes      | 
| Barrier Projects         | barrier_projects         | number    | number      | numeric metric | Yes      | 
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Series Fields

```ls
Metric Prefix = 
Included Fields = *
Excluded Fields = 
Annotation Fields = 
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

metric m:riparian_acres_treated l:"Riparian Acres Treated" t:dataTypeName=number

metric m:riparian_acre_projects p:integer l:"Riparian Acre Projects" t:dataTypeName=number

metric m:riparian_miles_treated l:"Riparian Miles Treated" t:dataTypeName=number

metric m:riparian_mile_projects p:integer l:"Riparian Mile Projects" t:dataTypeName=number

metric m:stream_miles_opened l:"Stream Miles Opened" t:dataTypeName=number

metric m:stream_mile_projects p:integer l:"Stream Mile Projects" t:dataTypeName=number

metric m:barriers_removed_altered p:integer l:"Barriers Removed/Altered" t:dataTypeName=number

metric m:barrier_projects p:integer l:"Barrier Projects" t:dataTypeName=number

entity e:t8dk-esb7 l:"Northeast Complete" t:url=https://data.wa.gov/api/views/t8dk-esb7

property e:t8dk-esb7 t:meta.view d:2017-03-08T01:37:37.035Z v:id=t8dk-esb7 v:averageRating=0 v:name="Northeast Complete"

property e:t8dk-esb7 t:meta.view.owner d:2017-03-08T01:37:37.035Z v:id=fuyk-waw8 v:screenName="Jennifer Johnson" v:roleName=publisher v:displayName="Jennifer Johnson"

property e:t8dk-esb7 t:meta.view.tableauthor d:2017-03-08T01:37:37.035Z v:id=fuyk-waw8 v:screenName="Jennifer Johnson" v:roleName=publisher v:displayName="Jennifer Johnson"
```