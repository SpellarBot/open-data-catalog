# Lower Columbia Complete

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/lower-columbia-complete-34288) |
| Metadata | [Link](https://data.wa.gov/api/views/25xk-8tku) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/25xk-8tku/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/25xk-8tku/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | 25xk-8tku |
| Name | Lower Columbia Complete |
| Tags | state-of-the-salmon |
| Created | 2015-01-02T20:39:21Z |
| Publication Date | 2015-02-13T20:56:19Z |

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
series e:25xk-8tku d:2005-01-01T00:00:00.000Z t:region="Lower Columbia" m:barriers_removed_altered=84 m:estuary_acres_treated=0 m:riparian_acre_projects=4 m:riparian_acres_treated=0.3 m:riparian_miles_treated=1.8 m:stream_miles_opened=1.8 m:stream_mile_projects=4 m:riparian_mile_projects=4 m:estuary_projects=0 m:barrier_projects=148

series e:25xk-8tku d:2006-01-01T00:00:00.000Z t:region="Lower Columbia" m:barriers_removed_altered=107 m:estuary_acres_treated=0 m:riparian_acre_projects=3 m:riparian_acres_treated=0.5 m:riparian_miles_treated=2.6 m:stream_miles_opened=2.6 m:stream_mile_projects=3 m:riparian_mile_projects=3 m:estuary_projects=0 m:barrier_projects=143

series e:25xk-8tku d:2007-01-01T00:00:00.000Z t:region="Lower Columbia" m:barriers_removed_altered=92 m:estuary_acres_treated=0 m:riparian_acre_projects=6 m:riparian_acres_treated=0.9 m:riparian_miles_treated=3.7 m:stream_miles_opened=3.7 m:stream_mile_projects=6 m:riparian_mile_projects=6 m:estuary_projects=0 m:barrier_projects=97
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

entity e:25xk-8tku l:"Lower Columbia Complete" t:url=https://data.wa.gov/api/views/25xk-8tku

property e:25xk-8tku t:meta.view v:id=25xk-8tku v:averageRating=0 v:name="Lower Columbia Complete"

property e:25xk-8tku t:meta.view.owner v:id=fuyk-waw8 v:screenName="Jennifer Johnson" v:displayName="Jennifer Johnson"

property e:25xk-8tku t:meta.view.tableauthor v:id=fuyk-waw8 v:screenName="Jennifer Johnson" v:roleName=publisher v:displayName="Jennifer Johnson"
```

## Top Records

```ls
| region         | year | estuary_acres_treated | estuary_projects | riparian_acres_treated | riparian_acre_projects | riparian_miles_treated | riparian_mile_projects | stream_miles_opened | stream_mile_projects | barriers_removed_altered | barrier_projects | 
| ============== | ==== | ===================== | ================ | ====================== | ====================== | ====================== | ====================== | =================== | ==================== | ======================== | ================ | 
| Lower Columbia | 2005 | 0                     | 0                | 0.3                    | 4                      | 1.8                    | 4                      | 1.8                 | 4                    | 84                       | 148              | 
| Lower Columbia | 2006 | 0                     | 0                | 0.5                    | 3                      | 2.6                    | 3                      | 2.6                 | 3                    | 107                      | 143              | 
| Lower Columbia | 2007 | 0                     | 0                | 0.9                    | 6                      | 3.7                    | 6                      | 3.7                 | 6                    | 92                       | 97               | 
| Lower Columbia | 2008 | 0                     | 0                | 0.9                    | 4                      | 4.1                    | 4                      | 4.1                 | 4                    | 109                      | 97               | 
| Lower Columbia | 2009 | 0                     | 0                | 2.1                    | 7                      | 4.9                    | 7                      | 66.5                | 7                    | 101                      | 95               | 
| Lower Columbia | 2010 | 0                     | 0                | 0.8                    | 12                     | 3.7                    | 12                     | 68.400000000000006  | 12                   | 114                      | 98               | 
| Lower Columbia | 2011 | 0                     | 0                | 1.7                    | 5                      | 7.7                    | 5                      | 92.86               | 5                    | 107                      | 95               | 
| Lower Columbia | 2012 | 0                     | 0                | 28.0                   | 10                     | 112.1                  | 10                     | 51.52               | 10                   | 80                       | 99               | 
```