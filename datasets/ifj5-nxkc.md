# Upper Columbia Complete

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/upper-columbia-complete-a2493) |
| Metadata | [Link](https://data.wa.gov/api/views/ifj5-nxkc) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/ifj5-nxkc/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/ifj5-nxkc/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | ifj5-nxkc |
| Name | Upper Columbia Complete |
| Tags | state-of-the-salmon |
| Created | 2015-01-02T21:42:18Z |
| Publication Date | 2015-02-13T21:03:00Z |

## Columns

```ls
| Included | Schema Type    | Field Name                      | Name                              | Data Type | Render Type |
| ======== | ============== | =============================== | ================================= | ========= | =========== |
| Yes      | series tag     | region                          | Region                            | text      | text        |
| Yes      | time           | year                            | Year                              | number    | number      |
| Yes      | numeric metric | estuary_nearshore_acres_treated | Estuary & Nearshore Acres Treated | number    | number      |
| Yes      | numeric metric | estuary_projects                | # Estuary Projects                | number    | number      |
| Yes      | numeric metric | riparian_acres_treated          | Riparian Acres Treated            | number    | number      |
| Yes      | numeric metric | riparian_acre_projects          | Riparian Acre Projects            | number    | number      |
| Yes      | numeric metric | riparian_miles_treated          | Riparian Miles Treated            | number    | number      |
| Yes      | numeric metric | riparian_mile_projects          | Riparian Mile Projects            | number    | number      |
| Yes      | numeric metric | miles_stream_treated            | Stream Miles Opened               | number    | number      |
| Yes      | numeric metric | stream_mile_projects            | Stream Mile Projects              | number    | number      |
| Yes      | numeric metric | barriers_removed_altered        | Barriers Removed/Altered          | number    | number      |
| Yes      | numeric metric | barrier_projects                | Barrier Projects                  | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:ifj5-nxkc d:2005-01-01T00:00:00.000Z t:region="Upper C" m:barriers_removed_altered=14 m:miles_stream_treated=8.5 m:riparian_acre_projects=0 m:riparian_acres_treated=0 m:riparian_miles_treated=0 m:stream_mile_projects=2 m:riparian_mile_projects=0 m:estuary_projects=0 m:barrier_projects=2 m:estuary_nearshore_acres_treated=0

series e:ifj5-nxkc d:2006-01-01T00:00:00.000Z t:region="Upper C" m:barriers_removed_altered=18 m:miles_stream_treated=29.8 m:riparian_acre_projects=2 m:riparian_acres_treated=0.58 m:riparian_miles_treated=0.12 m:stream_mile_projects=4 m:riparian_mile_projects=2 m:estuary_projects=0 m:barrier_projects=4 m:estuary_nearshore_acres_treated=0

series e:ifj5-nxkc d:2007-01-01T00:00:00.000Z t:region="Upper C" m:barriers_removed_altered=27 m:miles_stream_treated=16.2 m:riparian_acre_projects=7 m:riparian_acres_treated=11.59 m:riparian_miles_treated=2.67 m:stream_mile_projects=5 m:riparian_mile_projects=7 m:estuary_projects=0 m:barrier_projects=8 m:estuary_nearshore_acres_treated=0
```

## Meta Commands

```ls
metric m:estuary_nearshore_acres_treated p:integer l:"Estuary & Nearshore Acres Treated" t:dataTypeName=number

metric m:estuary_projects p:integer l:"# Estuary Projects" t:dataTypeName=number

metric m:riparian_acres_treated p:float l:"Riparian Acres Treated" t:dataTypeName=number

metric m:riparian_acre_projects p:integer l:"Riparian Acre Projects" t:dataTypeName=number

metric m:riparian_miles_treated p:float l:"Riparian Miles Treated" t:dataTypeName=number

metric m:riparian_mile_projects p:integer l:"Riparian Mile Projects" t:dataTypeName=number

metric m:miles_stream_treated p:float l:"Stream Miles Opened" t:dataTypeName=number

metric m:stream_mile_projects p:integer l:"Stream Mile Projects" t:dataTypeName=number

metric m:barriers_removed_altered p:integer l:"Barriers Removed/Altered" t:dataTypeName=number

metric m:barrier_projects p:integer l:"Barrier Projects" t:dataTypeName=number

entity e:ifj5-nxkc l:"Upper Columbia Complete" t:url=https://data.wa.gov/api/views/ifj5-nxkc

property e:ifj5-nxkc t:meta.view v:id=ifj5-nxkc v:averageRating=0 v:name="Upper Columbia Complete"

property e:ifj5-nxkc t:meta.view.owner v:id=fuyk-waw8 v:screenName="Jennifer Johnson" v:displayName="Jennifer Johnson"

property e:ifj5-nxkc t:meta.view.tableauthor v:id=fuyk-waw8 v:screenName="Jennifer Johnson" v:roleName=publisher v:displayName="Jennifer Johnson"
```

## Top Records

```ls
| region  | year | estuary_nearshore_acres_treated | estuary_projects | riparian_acres_treated | riparian_acre_projects | riparian_miles_treated | riparian_mile_projects | miles_stream_treated | stream_mile_projects | barriers_removed_altered | barrier_projects | 
| ======= | ==== | =============================== | ================ | ====================== | ====================== | ====================== | ====================== | ==================== | ==================== | ======================== | ================ | 
| Upper C | 2005 | 0                               | 0                | 0                      | 0                      | 0                      | 0                      | 8.5                  | 2                    | 14                       | 2                | 
| Upper C | 2006 | 0                               | 0                | 0.57999999999999996    | 2                      | 0.12                   | 2                      | 29.8                 | 4                    | 18                       | 4                | 
| Upper C | 2007 | 0                               | 0                | 11.59                  | 7                      | 2.67                   | 7                      | 16.2                 | 5                    | 27                       | 8                | 
| Upper C | 2008 | 0                               | 0                | 42.39                  | 6                      | 4.3099999999999996     | 6                      | 1.5                  | 2                    | 21                       | 2                | 
| Upper C | 2009 | 0                               | 0                | 5.27                   | 4                      | 3.48                   | 4                      | 44.2                 | 2                    | 17                       | 3                | 
| Upper C | 2010 | 0                               | 0                | 16.95                  | 9                      | 2.4300000000000002     | 10                     | 2                    | 6                    | 5                        | 7                | 
| Upper C | 2011 | 0                               | 0                | 5                      | 1                      | 0.35                   | 1                      | 2.2000000000000002   | 1                    | 7                        | 1                | 
| Upper C | 2012 | 0                               | 0                | 22.6                   | 6                      | 2.0499999999999998     | 5                      | 2.6                  | 1                    | 2                        | 1                | 
```