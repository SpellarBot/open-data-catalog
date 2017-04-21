# Middle Columbia Complete

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/middle-columbia-complete-70036) |
| Metadata | [Link](https://data.wa.gov/api/views/xkff-xt2h) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/xkff-xt2h/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/xkff-xt2h/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | xkff-xt2h |
| Name | Middle Columbia Complete |
| Tags | state-of-the-salmon |
| Created | 2015-01-02T22:04:48Z |
| Publication Date | 2015-02-13T21:04:09Z |

## Columns

```ls
| Included | Schema Type    | Field Name                  | Name                        | Data Type | Render Type |
| ======== | ============== | =========================== | =========================== | ========= | =========== |
| Yes      | series tag     | region                      | Region                      | text      | text        |
| Yes      | time           | year                        | Year                        | number    | number      |
| Yes      | numeric metric | est_acres                   | Est Acres                   | number    | number      |
| Yes      | numeric metric | projects                    | # Projects                  | number    | number      |
| Yes      | numeric metric | riparian_acres_treated      | Riparian Acres Treated      | number    | number      |
| Yes      | numeric metric | riparian_acre_projects      | Riparian Acre Projects      | number    | number      |
| Yes      | numeric metric | riparian_miles_treated      | Riparian Miles Treated      | number    | number      |
| Yes      | numeric metric | riparian_mile_projects      | Riparian Mile Projects      | number    | number      |
| Yes      | numeric metric | stream_miles_opened         | Stream Miles Opened         | number    | number      |
| Yes      | numeric metric | stream_mile_projects        | Stream Mile Projects        | number    | number      |
| Yes      | numeric metric | barriers_removed_or_altered | Barriers Removed or Altered | number    | number      |
| Yes      | numeric metric | barrier_projects            | Barrier Projects            | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:xkff-xt2h d:2005-01-01T00:00:00.000Z t:region="Mid Columbia" m:projects=0 m:riparian_acre_projects=0 m:riparian_acres_treated=0 m:riparian_miles_treated=14.41 m:barriers_removed_or_altered=14 m:est_acres=0 m:stream_miles_opened=10.92 m:stream_mile_projects=3 m:riparian_mile_projects=3 m:barrier_projects=3

series e:xkff-xt2h d:2006-01-01T00:00:00.000Z t:region="Mid Columbia" m:projects=0 m:riparian_acre_projects=0 m:riparian_acres_treated=0 m:riparian_miles_treated=0 m:barriers_removed_or_altered=17 m:est_acres=0 m:stream_miles_opened=27.75 m:stream_mile_projects=2 m:riparian_mile_projects=0 m:barrier_projects=2

series e:xkff-xt2h d:2007-01-01T00:00:00.000Z t:region="Mid Columbia" m:projects=0 m:riparian_acre_projects=0 m:riparian_acres_treated=0 m:riparian_miles_treated=4.45 m:barriers_removed_or_altered=12 m:est_acres=0 m:stream_miles_opened=0 m:stream_mile_projects=0 m:riparian_mile_projects=1 m:barrier_projects=1
```

## Meta Commands

```ls
metric m:est_acres p:integer l:"Est Acres" t:dataTypeName=number

metric m:projects p:integer l:"# Projects" t:dataTypeName=number

metric m:riparian_acres_treated p:float l:"Riparian Acres Treated" t:dataTypeName=number

metric m:riparian_acre_projects p:integer l:"Riparian Acre Projects" t:dataTypeName=number

metric m:riparian_miles_treated p:float l:"Riparian Miles Treated" t:dataTypeName=number

metric m:riparian_mile_projects p:integer l:"Riparian Mile Projects" t:dataTypeName=number

metric m:stream_miles_opened p:float l:"Stream Miles Opened" t:dataTypeName=number

metric m:stream_mile_projects p:integer l:"Stream Mile Projects" t:dataTypeName=number

metric m:barriers_removed_or_altered p:integer l:"Barriers Removed or Altered" t:dataTypeName=number

metric m:barrier_projects p:integer l:"Barrier Projects" t:dataTypeName=number

entity e:xkff-xt2h l:"Middle Columbia Complete" t:url=https://data.wa.gov/api/views/xkff-xt2h

property e:xkff-xt2h t:meta.view v:id=xkff-xt2h v:averageRating=0 v:name="Middle Columbia Complete"

property e:xkff-xt2h t:meta.view.owner v:id=fuyk-waw8 v:screenName="Jennifer Johnson" v:displayName="Jennifer Johnson"

property e:xkff-xt2h t:meta.view.tableauthor v:id=fuyk-waw8 v:screenName="Jennifer Johnson" v:roleName=publisher v:displayName="Jennifer Johnson"
```

## Top Records

```ls
| region       | year | est_acres | projects | riparian_acres_treated | riparian_acre_projects | riparian_miles_treated | riparian_mile_projects | stream_miles_opened | stream_mile_projects | barriers_removed_or_altered | barrier_projects | 
| ============ | ==== | ========= | ======== | ====================== | ====================== | ====================== | ====================== | =================== | ==================== | =========================== | ================ | 
| Mid Columbia | 2005 | 0         | 0        | 0                      | 0                      | 14.41                  | 3                      | 10.92               | 3                    | 14                          | 3                | 
| Mid Columbia | 2006 | 0         | 0        | 0                      | 0                      | 0                      | 0                      | 27.75               | 2                    | 17                          | 2                | 
| Mid Columbia | 2007 | 0         | 0        | 0                      | 0                      | 4.45                   | 1                      | 0                   | 0                    | 12                          | 1                | 
| Mid Columbia | 2008 | 0         | 0        | 0                      | 0                      | 0                      | 0                      | 1                   | 1                    | 15                          | 1                | 
| Mid Columbia | 2009 | 0         | 0        | 0                      | 0                      | 0.82                   | 2                      | 21.1                | 2                    | 21                          | 2                | 
| Mid Columbia | 2010 | 0         | 0        | 0                      | 0                      | 1.4                    | 2                      | 11.2                | 2                    | 13                          | 2                | 
| Mid Columbia | 2011 | 0         | 0        | 113.8                  | 2                      | 1.58                   | 2                      | 4.74                | 3                    | 6                           | 3                | 
| Mid Columbia | 2012 | 0         | 0        | 12.2                   | 2                      | 1.47                   | 2                      | 5.85                | 2                    | 7                           | 2                | 
```