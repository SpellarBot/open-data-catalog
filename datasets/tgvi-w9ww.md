# Damage By Sandy By Land Use

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/damage-by-sandy-by-land-use-f5920) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/tgvi-w9ww) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/tgvi-w9ww/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/tgvi-w9ww/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | tgvi-w9ww |
| Name | Damage By Sandy By Land Use |
| Attribution | Department of City Planning (DCP) |
| Category | Housing & Development |
| Tags | dcp, city, planning, hurricane, sandy, damage |
| Created | 2013-02-13T19:42:34Z |
| Publication Date | 2013-06-21T20:41:54Z |

## Description

Details about damage by Storm Sandy to various types of buildings

## Columns

```ls
| Included | Schema Type | Field Name                  | Name                          | Data Type | Render Type |
| ======== | =========== | =========================== | ============================= | ========= | =========== |
| No       | time        | :updated_at                 | updated_at                    | meta_data | meta_data   |
| Yes      | series tag  | land_use                    | Land Use                      | text      | text        |
| Yes      | series tag  | of_total_destroyed_by_storm | % of Total Destroyed by Storm | text      | text        |
| Yes      | series tag  | of_total_red_tags           | % of Total Red Tags           | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:tgvi-w9ww d:2013-02-13T11:42:35.000Z t:of_total_red_tags=90% t:land_use="One & Two Family" t:of_total_destroyed_by_storm=88% m:row_number.tgvi-w9ww=1

series e:tgvi-w9ww d:2013-02-13T11:42:35.000Z t:of_total_red_tags=4% t:land_use="Multi-Family Walk Up" t:of_total_destroyed_by_storm=1% m:row_number.tgvi-w9ww=2

series e:tgvi-w9ww d:2013-02-13T11:42:35.000Z t:of_total_red_tags=1% t:land_use="Mixed Residential & Commercial" t:of_total_destroyed_by_storm=6% m:row_number.tgvi-w9ww=3
```

## Meta Commands

```ls
metric m:row_number.tgvi-w9ww p:long l:"Row Number"

entity e:tgvi-w9ww l:"Damage By Sandy By Land Use" t:attribution="Department of City Planning (DCP)" t:url=https://data.cityofnewyork.us/api/views/tgvi-w9ww

property e:tgvi-w9ww t:meta.view v:id=tgvi-w9ww v:category="Housing & Development" v:attributionLink=http://www.nyc.gov/html/dcp/pdf/climate_resilience/presentation_sandy.pdf v:averageRating=0 v:name="Damage By Sandy By Land Use" v:attribution="Department of City Planning (DCP)"

property e:tgvi-w9ww t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:tgvi-w9ww t:meta.view.tableauthor v:id=8b43-zkvh v:screenName="Ram S." v:displayName="Ram S."
```

## Top Records

```ls
| :updated_at | land_use                       | of_total_destroyed_by_storm | of_total_red_tags | 
| =========== | ============================== | =========================== | ================= | 
| 1360755755  | One & Two Family               | 88%                         | 90%               | 
| 1360755755  | Multi-Family Walk Up           | 1%                          | 4%                | 
| 1360755755  | Mixed Residential & Commercial | 6%                          | 1%                | 
| 1360755755  | Commercial & Office            | 2%                          | 1%                | 
| 1360755755  | Public Facility & Institution  | < 1%                        | 1%                | 
| 1360755755  | Vacant                         | 1%                          | 1%                | 
| 1360755755  | Open Space & Recreation        | 1%                          | 1%                | 
| 1360755755  | Industrial & Manufacturing     | < 1%                        | 1%                | 
| 1360755755  | Multi-Family Elevator          | < 1%                        | < 1%              | 
| 1360755755  | Transportation & Utility       | < 1%                        | < 1%              | 
```