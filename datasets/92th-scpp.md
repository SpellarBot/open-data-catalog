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

metric m:lasar_river_distance p:float l:LASAR_RIVER_DISTANCE t:dataTypeName=number

entity e:92th-scpp l:"SCLR LASARStations Grab Sites" t:attribution="Oregon DEQ Volunteer Program and South Coast Lower Rogue Watershed Councils" t:url=https://data.oregon.gov/api/views/92th-scpp

property e:92th-scpp t:meta.view v:id=92th-scpp v:category="Natural Resources" v:averageRating=0 v:name="SCLR LASARStations Grab Sites" v:attribution="Oregon DEQ Volunteer Program and South Coast Lower Rogue Watershed Councils"

property e:92th-scpp t:meta.view.owner v:id=mgnq-77dc v:screenName="Steve Hanson" v:displayName="Steve Hanson"

property e:92th-scpp t:meta.view.tableauthor v:id=mgnq-77dc v:screenName="Steve Hanson" v:roleName=editor v:displayName="Steve Hanson"
```

## Top Records

```ls
| :updated_at | lasar_id | sclr_id | lasar_location_description            | lasar_location_memo | lasar_elevation | lasar_river_distance | lasar_data_source                             | sclr_lat | sclr_long  | sclr_description                  | 
| =========== | ======== | ======= | ===================================== | =================== | =============== | ==================== | ============================================= | ======== | ========== | ================================= | 
| 1311176920  | LASAR_ID | SCLR_ID | LASAR_LOCATION_DESCRIPTION            | LASAR_LOCATION_MEMO |                 |                      | LASAR_DATA_SOURCE                             |          |            | SCLR_DESCRIPTION                  | 
| 1311176920  | 31811    | 2       | Floras Lake tributary - Boulder Creek |                     |                 | 0                    | ODEQ Staff: Dave Gilbey 10/5/2004 11:12:44 AM | 42.87904 | -124.46786 | Floras Lake: Swanson Creek at 101 | 
| 1311176920  | 31844    | 3       | Floras Lake, unnamed tributary #3     |                     |                 | 0                    | ODEQ Staff: Bob McCoy 10/14/2004 1:34:58 PM   | 42.85929 | -124.47025 | Floras Lake: Boulder at 101       | 
| 1311176920  | 25770    | 8       | Floras Lake at SE-E finger            |                     |                 | 0                    |                                               | 42.89312 | -124.49561 | Floras Lake: @ SE-E finger        | 
| 1311176920  | 25768    | 9       | Floras Lake at wetland                |                     |                 | 0                    |                                               | 42.8903  | -124.49979 | Floras Lake: @ wetland            | 
| 1311176920  | 31812    | 10      | Floras Lake at SW-E finger            |                     |                 | 0                    | ODEQ Staff: Dave Gilbey 10/5/2004 11:17:38 AM | 42.88456 | -124.50324 | Floras Lake: @ SW-E finger        | 
| 1311176920  | 25764    | 11      | Floras Lake SW-W finger               |                     |                 | 0                    |                                               | 42.88472 | -124.50721 | Floras Lake: @ SW-W finger        | 
| 1311176920  | 25765    | 11.5    | Floras Lake at southeast peninsula    |                     |                 | 0                    |                                               | 42.89412 | -124.50201 | Floras Lake: at SE Peninsula      | 
| 1311176920  | 31847    | 12      | Floras Lake at south end of lake      |                     |                 | 0                    | ODEQ Staff: Bob McCoy 10/15/2004 2:46:57 PM   | 42.89345 | -124.5063  | Floras Lake: @ South end of lake  | 
| 1311176920  | 13782    | 13      | Floras Lake at center                 | /TYPA/AMBNT/LAKE    |                 | 0                    |                                               | 42.89813 | -124.50546 | Floras Lake: at Center            | 
```