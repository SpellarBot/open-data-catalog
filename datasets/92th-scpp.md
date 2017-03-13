# SCLR LASARStations Grab Sites

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/sclr-lasarstations-grab-sites-b37fd) |
| Metadata | [Link](https://data.oregon.gov/api/views/92th-scpp) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/92th-scpp/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/92th-scpp/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | 92th-scpp |
| Name | SCLR LASARStations Grab Sites |
| Attribution | Oregon DEQ Volunteer Program and South Coast Lower Rogue Watershed Councils |
| Category | Natural Resources |
| Tags | south coast, lower rogue, volunteer, water quality monitoring |
| Created | 2011-07-20T22:48:39Z |
| Publication Date | 2011-07-20T22:48:39Z |
| Rows Updated | 2011-08-23T16:19:09Z |

## Description

South Coast/Lower Rogue Watershed Councils grab water quality monitoring sites associated with DEQ LASAR numbers

## Columns

```ls
| Included | Schema Type    | Field Name                 | Name                       | Data Type | Render Type |
| ======== | ============== | ========================== | ========================== | ========= | =========== |
| No       | time           | :updated_at                | updated_at                 | meta_data | meta_data   |
| Yes      | series tag     | lasar_id                   | LASAR_ID                   | text      | text        |
| Yes      | series tag     | sclr_id                    | SCLR_ID                    | text      | text        |
| Yes      | series tag     | lasar_location_description | LASAR_LOCATION_DESCRIPTION | text      | text        |
| Yes      | series tag     | lasar_location_memo        | LASAR_LOCATION_MEMO        | text      | text        |
| Yes      | numeric metric | lasar_elevation            | LASAR_ELEVATION            | number    | number      |
| Yes      | numeric metric | lasar_river_distance       | LASAR_RIVER_DISTANCE       | number    | number      |
| Yes      | series tag     | lasar_data_source          | LASAR_DATA_SOURCE          | text      | text        |
| No       |                | sclr_lat                   | SCLR_LAT                   | number    | number      |
| No       |                | sclr_long                  | SCLR_LONG                  | number    | number      |
| Yes      | series tag     | sclr_description           | SCLR_DESCRIPTION           | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = sclr_lat,sclr_long
```

## Data Commands

```ls
series e:92th-scpp d:2011-07-20T15:48:40.000Z t:lasar_location_description="Floras Lake tributary - Boulder Creek" t:lasar_id=31811 t:sclr_description="Floras Lake: Swanson Creek at 101" t:sclr_id=2 t:lasar_data_source="ODEQ Staff: Dave Gilbey  10/5/2004 11:12:44 AM" m:lasar_river_distance=0

series e:92th-scpp d:2011-07-20T15:48:40.000Z t:lasar_location_description="Floras Lake, unnamed tributary #3" t:lasar_id=31844 t:sclr_description="Floras Lake: Boulder at 101" t:sclr_id=3 t:lasar_data_source="ODEQ Staff: Bob McCoy  10/14/2004 1:34:58 PM" m:lasar_river_distance=0

series e:92th-scpp d:2011-07-20T15:48:40.000Z t:lasar_location_description="Floras Lake at SE-E finger" t:lasar_id=25770 t:sclr_description="Floras Lake: @ SE-E finger" t:sclr_id=8 m:lasar_river_distance=0
```

## Meta Commands

```ls
metric m:lasar_elevation p:integer l:LASAR_ELEVATION t:dataTypeName=number

metric m:lasar_river_distance l:LASAR_RIVER_DISTANCE t:dataTypeName=number

entity e:92th-scpp l:"SCLR LASARStations Grab Sites" t:attribution="Oregon DEQ Volunteer Program and South Coast Lower Rogue Watershed Councils" t:url=https://data.oregon.gov/api/views/92th-scpp

property e:92th-scpp t:meta.view v:id=92th-scpp v:category="Natural Resources" v:averageRating=0 v:name="SCLR LASARStations Grab Sites" v:attribution="Oregon DEQ Volunteer Program and South Coast Lower Rogue Watershed Councils"

property e:92th-scpp t:meta.view.owner v:id=mgnq-77dc v:screenName="Steve Hanson" v:roleName=editor v:displayName="Steve Hanson"

property e:92th-scpp t:meta.view.tableauthor v:id=mgnq-77dc v:screenName="Steve Hanson" v:roleName=editor v:displayName="Steve Hanson"
```