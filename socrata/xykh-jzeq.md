# Coast Complete Metrics

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/coast-complete-metrics-86cde) |
| Metadata | [Link](https://data.wa.gov/api/views/xykh-jzeq) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/xykh-jzeq/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/xykh-jzeq/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | xykh-jzeq |
| Name | Coast Complete Metrics |
| Tags | state-of-the-salmon |
| Created | 2015-01-02T17:44:29Z |
| Publication Date | 2015-02-13T21:09:19Z |

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
series e:xykh-jzeq d:2005-01-01T00:00:00.000Z t:region=Coast m:barriers_removed_altered=84 m:estuary_acres_treated=35 m:riparian_acre_projects=0 m:riparian_acres_treated=0 m:riparian_miles_treated=0 m:stream_miles_opened=19.07 m:stream_mile_projects=6 m:riparian_mile_projects=0 m:estuary_projects=1 m:barrier_projects=6

series e:xykh-jzeq d:2006-01-01T00:00:00.000Z t:region=Coast m:barriers_removed_altered=108 m:estuary_acres_treated=0 m:riparian_acre_projects=1 m:riparian_acres_treated=30 m:riparian_miles_treated=1.57 m:stream_miles_opened=17 m:stream_mile_projects=3 m:riparian_mile_projects=1 m:estuary_projects=0 m:barrier_projects=3

series e:xykh-jzeq d:2007-01-01T00:00:00.000Z t:region=Coast m:barriers_removed_altered=189 m:estuary_acres_treated=0 m:riparian_acre_projects=0 m:riparian_acres_treated=0 m:riparian_miles_treated=0 m:stream_miles_opened=24.55 m:stream_mile_projects=6 m:riparian_mile_projects=0 m:estuary_projects=0 m:barrier_projects=6
```

## Meta Commands

```ls
metric m:estuary_acres_treated p:integer l:"Estuary Acres Treated" t:dataTypeName=number

metric m:estuary_projects p:integer l:"Estuary Projects" t:dataTypeName=number

metric m:riparian_acres_treated p:integer l:"Riparian Acres Treated" t:dataTypeName=number

metric m:riparian_acre_projects p:integer l:"Riparian Acre Projects" t:dataTypeName=number

metric m:riparian_miles_treated p:float l:"Riparian Miles Treated" t:dataTypeName=number

metric m:riparian_mile_projects p:integer l:"Riparian Mile Projects" t:dataTypeName=number

metric m:stream_miles_opened p:float l:"Stream Miles Opened" t:dataTypeName=number

metric m:stream_mile_projects p:integer l:"Stream Mile Projects" t:dataTypeName=number

metric m:barriers_removed_altered p:integer l:"Barriers Removed/Altered" t:dataTypeName=number

metric m:barrier_projects p:integer l:"Barrier Projects" t:dataTypeName=number

entity e:xykh-jzeq l:"Coast Complete Metrics" t:url=https://data.wa.gov/api/views/xykh-jzeq

property e:xykh-jzeq t:meta.view v:id=xykh-jzeq v:averageRating=0 v:name="Coast Complete Metrics"

property e:xykh-jzeq t:meta.view.owner v:id=fuyk-waw8 v:screenName="Jennifer Johnson" v:displayName="Jennifer Johnson"

property e:xykh-jzeq t:meta.view.tableauthor v:id=fuyk-waw8 v:screenName="Jennifer Johnson" v:roleName=publisher v:displayName="Jennifer Johnson"
```

## Top Records

```ls
| region | year | estuary_acres_treated | estuary_projects | riparian_acres_treated | riparian_acre_projects | riparian_miles_treated | riparian_mile_projects | stream_miles_opened | stream_mile_projects | barriers_removed_altered | barrier_projects | 
| ====== | ==== | ===================== | ================ | ====================== | ====================== | ====================== | ====================== | =================== | ==================== | ======================== | ================ | 
| Coast  | 2005 | 35                    | 1                | 0                      | 0                      | 0                      | 0                      | 19.07               | 6                    | 84                       | 6                | 
| Coast  | 2006 | 0                     | 0                | 30                     | 1                      | 1.57                   | 1                      | 17                  | 3                    | 108                      | 3                | 
| Coast  | 2007 | 0                     | 0                | 0                      | 0                      | 0                      | 0                      | 24.55               | 6                    | 189                      | 6                | 
| Coast  | 2008 | 0                     | 0                | 0                      | 0                      | 0                      | 0                      | 4.32                | 3                    | 211                      | 2                | 
| Coast  | 2009 | 0                     | 0                | 0                      | 0                      | 0                      | 0                      | 80.4                | 0                    | 120                      | 0                | 
| Coast  | 2010 | 0                     | 0                | 0                      | 0                      | 0                      | 0                      | 105                 | 0                    | 158                      | 1                | 
| Coast  | 2011 | 0                     | 0                | 10                     | 1                      | 1.08                   | 1                      | 126.33              | 1                    | 217                      | 0                | 
| Coast  | 2012 | 0                     | 0                | 0                      | 0                      | 0                      | 0                      | 133.2               | 1                    | 229                      | 2                | 
```