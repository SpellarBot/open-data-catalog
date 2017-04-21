# Hood Canal Complete

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/hood-canal-complete-29127) |
| Metadata | [Link](https://data.wa.gov/api/views/u5is-fgut) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/u5is-fgut/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/u5is-fgut/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | u5is-fgut |
| Name | Hood Canal Complete |
| Tags | state-of-the-salmon |
| Created | 2015-01-02T19:06:22Z |
| Publication Date | 2015-01-05T16:54:36Z |

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
series e:u5is-fgut d:2005-01-01T00:00:00.000Z t:region=HCCC m:barriers_removed_altered=14 m:estuary_acres_treated=76.51 m:riparian_acre_projects=6 m:riparian_acres_treated=75.9 m:riparian_miles_treated=4.41 m:stream_miles_opened=0 m:stream_mile_projects=0 m:riparian_mile_projects=5 m:estuary_projects=3 m:barrier_projects=2

series e:u5is-fgut d:2006-01-01T00:00:00.000Z t:region=HCCC m:barriers_removed_altered=15 m:estuary_acres_treated=4.68 m:riparian_acre_projects=7 m:riparian_acres_treated=68.34 m:riparian_miles_treated=4.39 m:stream_miles_opened=0 m:stream_mile_projects=0 m:riparian_mile_projects=7 m:estuary_projects=1 m:barrier_projects=0

series e:u5is-fgut d:2007-01-01T00:00:00.000Z t:region=HCCC m:barriers_removed_altered=13 m:estuary_acres_treated=147.3 m:riparian_acre_projects=3 m:riparian_acres_treated=14.48 m:riparian_miles_treated=0 m:stream_miles_opened=0 m:stream_mile_projects=0 m:riparian_mile_projects=0 m:estuary_projects=4 m:barrier_projects=0
```

## Meta Commands

```ls
metric m:estuary_acres_treated p:float l:"Estuary Acres Treated" t:dataTypeName=number

metric m:estuary_projects p:integer l:"Estuary Projects" t:dataTypeName=number

metric m:riparian_acres_treated p:float l:"Riparian Acres Treated" t:dataTypeName=number

metric m:riparian_acre_projects p:integer l:"Riparian Acre Projects" t:dataTypeName=number

metric m:riparian_miles_treated p:float l:"Riparian Miles Treated" t:dataTypeName=number

metric m:riparian_mile_projects p:integer l:"Riparian Mile Projects" t:dataTypeName=number

metric m:stream_miles_opened p:float l:"Stream Miles Opened" t:dataTypeName=number

metric m:stream_mile_projects p:integer l:"Stream Mile Projects" t:dataTypeName=number

metric m:barriers_removed_altered p:integer l:"Barriers Removed/Altered" t:dataTypeName=number

metric m:barrier_projects p:integer l:"Barrier Projects" t:dataTypeName=number

entity e:u5is-fgut l:"Hood Canal Complete" t:url=https://data.wa.gov/api/views/u5is-fgut

property e:u5is-fgut t:meta.view v:id=u5is-fgut v:averageRating=0 v:name="Hood Canal Complete"

property e:u5is-fgut t:meta.view.owner v:id=fuyk-waw8 v:screenName="Jennifer Johnson" v:displayName="Jennifer Johnson"

property e:u5is-fgut t:meta.view.tableauthor v:id=fuyk-waw8 v:screenName="Jennifer Johnson" v:roleName=publisher v:displayName="Jennifer Johnson"
```

## Top Records

```ls
| region | year | estuary_acres_treated | estuary_projects | riparian_acres_treated | riparian_acre_projects | riparian_miles_treated | riparian_mile_projects | stream_miles_opened | stream_mile_projects | barriers_removed_altered | barrier_projects | 
| ====== | ==== | ===================== | ================ | ====================== | ====================== | ====================== | ====================== | =================== | ==================== | ======================== | ================ | 
| HCCC   | 2005 | 76.510000000000005    | 3                | 75.900000000000006     | 6                      | 4.41                   | 5                      | 0                   | 0                    | 14                       | 2                | 
| HCCC   | 2006 | 4.68                  | 1                | 68.34                  | 7                      | 4.3899999999999997     | 7                      | 0                   | 0                    | 15                       | 0                | 
| HCCC   | 2007 | 147.30000000000001    | 4                | 14.48                  | 3                      | 0                      | 0                      | 0                   | 0                    | 13                       | 0                | 
| HCCC   | 2013 | 56.31                 | 2                | 46.71                  | 6                      | 1.35                   | 3                      | 0                   | 0                    | 0                        | 0                | 
| HCCC   | 2009 | 7.01                  | 1                | 24.47                  | 6                      | 12.51                  | 4                      | 10.5                | 0                    | 13                       | 2                | 
| HCCC   | 2010 | 247.85                | 3                | 193.88                 | 15                     | 35.92                  | 13                     | 9.6                 | 0                    | 12                       | 0                | 
| HCCC   | 2011 | 0                     | 0                | 46.44                  | 13                     | 3.02                   | 8                      | 8.53                | 0                    | 14                       | 0                | 
| HCCC   | 2012 | 45.1                  | 3                | 127.74                 | 6                      | 3.67                   | 6                      | 25.76               | 0                    | 26                       | 0                | 
| HCCC   | 2008 | 26.05                 | 5                | 10.24                  | 4                      | 1.37                   | 4                      | 0                   | 0                    | 16                       | 0                | 
```