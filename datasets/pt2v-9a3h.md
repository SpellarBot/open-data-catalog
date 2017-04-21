# Accessible Outdoor Recreation Destinations

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/accessible-outdoor-recreation-destinations) |
| Metadata | [Link](https://data.ny.gov/api/views/pt2v-9a3h) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/pt2v-9a3h/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/pt2v-9a3h/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | pt2v-9a3h |
| Name | Accessible Outdoor Recreation Destinations |
| Attribution | New York State Department of Environmental Conservation |
| Category | Recreation |
| Tags | access, disabled, handicap, mobility impaired |
| Created | 2013-02-14T03:56:51Z |
| Publication Date | 2014-03-14T18:58:48Z |

## Description

This data set displays the locations of accessible recreation sites throughout New York State that are owned, maintained or jointly managed by the Department of Environmental Conservation.

## Columns

```ls
| Included | Schema Type    | Field Name | Name                      | Data Type     | Render Type   |
| ======== | ============== | ========== | ========================= | ============= | ============= |
| Yes      | numeric metric | reg        | Region                    | number        | number        |
| Yes      | series tag     | county     | County                    | text          | text          |
| Yes      | series tag     | name       | Name                      | text          | text          |
| Yes      | series tag     | feature    | Feature                   | text          | text          |
| Yes      | series tag     | descriptn  | Description               | text          | text          |
| Yes      | series tag     | primtveset | Primitive Setting         | text          | text          |
| Yes      | series tag     | tentsite_s | Tent Site                 | text          | text          |
| Yes      | series tag     | leanto     | Lean-to                   | text          | text          |
| Yes      | series tag     | picnctbl_s | Picnic Tables             | text          | text          |
| Yes      | series tag     | privy      | Privy                     | text          | text          |
| Yes      | series tag     | trail_s    | Trails                    | text          | text          |
| Yes      | series tag     | equestr    | Equestrian                | text          | text          |
| Yes      | series tag     | scenicovlk | Scenic Overlook           | text          | text          |
| Yes      | series tag     | interpmtrl | Interpretive Materials    | text          | text          |
| Yes      | series tag     | wlviewplat | Wildlife Viewing Platform | text          | text          |
| Yes      | series tag     | huntgblind | Hunting Blind             | text          | text          |
| Yes      | series tag     | fshpieretc | Fishing Pier              | text          | text          |
| Yes      | series tag     | boatlaunch | Boat Launch               | text          | text          |
| Yes      | series tag     | loadngdock | Loading Dock              | text          | text          |
| Yes      | series tag     | handlaunch | Hand Launch               | text          | text          |
| Yes      | series tag     | beach      | Beach                     | text          | text          |
| Yes      | series tag     | flshtoilet | Flush Toilet              | text          | text          |
| Yes      | series tag     | shower     | Shower                    | text          | text          |
| Yes      | series tag     | url        | URL                       | url           | url           |
| Yes      | series tag     | data_type  | Data_Type                 | text          | text          |
| Yes      | series tag     | land_unit  | Land_Unit                 | text          | text          |
| Yes      | series tag     | facility   | Facility                  | text          | text          |
| Yes      | series tag     | status     | Status                    | text          | text          |
| Yes      | series tag     | setlmt     | Setlmt                    | text          | text          |
| Yes      | series tag     | inspected  | Inspected                 | text          | text          |
| Yes      | series tag     | inspectdby | Inspected By              | text          | text          |
| Yes      | time           | dateinspc  | Date Inspected            | calendar_date | calendar_date |
| Yes      | series tag     | passinspc  | Pass Inspection           | text          | text          |
| Yes      | series tag     | accessible | Accessible                | text          | text          |
| Yes      | series tag     | notes      | Notes                     | text          | text          |
| Yes      | series tag     | directions | Directions                | text          | text          |
| Yes      | series tag     | kmlnotes   | KMLNOTES                  | text          | text          |
| No       |                | point_x    | POINT_X                   | number        | number        |
| No       |                | point_y    | POINT_Y                   | number        | number        |
```

## Time Field

```ls
Value = dateinspc
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = point_x,point_y
```

## Data Commands

```ls
series e:pt2v-9a3h d:2013-02-20T18:21:25.000Z t:flshtoilet=N t:handlaunch=N t:beach=N t:scenicovlk=Y t:facility="SALMON RIVER FALLS UNIQUE AREA" t:fshpieretc=N t:data_type="Destination Point" t:primtveset=Y t:name="Salmon River Falls Trail" t:accessible=Y t:feature="HIKING TRAIL" t:trail_s=Y t:interpmtrl=N t:wlviewplat=N t:boatlaunch=N t:tentsite_s=N t:status=Existing/Compl t:loadngdock=N t:inspectdby="Carole Fraser" t:url=http://www.dec.ny.gov/lands/63578.html#Access t:inspected=Y t:picnctbl_s=N t:county=OSWEGO t:leanto=N t:huntgblind=N t:passinspc=Y t:equestr=N t:shower=N t:privy=N t:setlmt=N m:reg=7

series e:pt2v-9a3h d:2013-02-20T18:21:25.000Z t:flshtoilet=Y t:handlaunch=N t:beach=Y t:directions="entrance from Rte. 9" t:scenicovlk=N t:facility="SCAROON MANOR PUBLIC CAMPGROUND" t:fshpieretc=Y t:data_type="Destination Point" t:primtveset=N t:name="Scaroon Manor Campground" t:kmlnotes="Directions: Entrance on Rte. 9." t:accessible=Y t:feature=CAMPGROUND t:trail_s=N t:interpmtrl=Y t:wlviewplat=Y t:boatlaunch=N t:tentsite_s=Y t:status=Existing/Incmpl t:loadngdock=Y t:inspectdby="Carole Fraser" t:url=http://www.dec.ny.gov/outdoor/72082.html#Access t:inspected=Y t:land_unit=AFP t:picnctbl_s=Y t:county=WARREN t:leanto=N t:huntgblind=N t:passinspc=Y t:equestr=N t:shower=Y t:privy=N t:setlmt=N m:reg=5

series e:pt2v-9a3h d:2013-02-20T18:21:25.000Z t:flshtoilet=Y t:handlaunch=Y t:beach=N t:scenicovlk=N t:facility="LITTLE TUPPER LAKE HQ ADMINISTRATIVE USE AREA" t:fshpieretc=N t:data_type="Destination Point" t:primtveset=Y t:name="William C Whitney Wilderness" t:accessible=Y t:feature=CANOEING t:trail_s=N t:interpmtrl=N t:wlviewplat=N t:boatlaunch=N t:tentsite_s=N t:status=Complete t:loadngdock=Y t:inspectdby="Doug Fitzgerald" t:url=http://www.dec.ny.gov/outdoor/9165.html#access t:inspected=Y t:picnctbl_s=N t:land_unit=AFP t:county=HAMILTON t:leanto=N t:huntgblind=N t:passinspc=Y t:equestr=N t:shower=N t:privy=N t:setlmt=Y m:reg=5
```

## Meta Commands

```ls
metric m:reg p:integer l:Region t:dataTypeName=number

entity e:pt2v-9a3h l:"Accessible Outdoor Recreation Destinations" t:attribution="New York State Department of Environmental Conservation" t:url=https://data.ny.gov/api/views/pt2v-9a3h

property e:pt2v-9a3h t:meta.view v:id=pt2v-9a3h v:category=Recreation v:attributionLink=http://www.dec.ny.gov/outdoor/34038.html v:averageRating=0 v:name="Accessible Outdoor Recreation Destinations" v:attribution="New York State Department of Environmental Conservation"

property e:pt2v-9a3h t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:pt2v-9a3h t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:pt2v-9a3h t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| reg | county      | name                                              | feature            | descriptn | primtveset | tentsite_s | leanto | picnctbl_s | privy | trail_s | equestr | scenicovlk | interpmtrl | wlviewplat | huntgblind | fshpieretc | boatlaunch | loadngdock | handlaunch | beach | flshtoilet | shower | url                                                                               | data_type         | land_unit | facility                                       | status          | setlmt | inspected | inspectdby      | dateinspc           | passinspc | accessible | notes | directions                                       | kmlnotes                                                      | point_x        | point_y       | 
| === | =========== | ================================================= | ================== | ========= | ========== | ========== | ====== | ========== | ===== | ======= | ======= | ========== | ========== | ========== | ========== | ========== | ========== | ========== | ========== | ===== | ========== | ====== | ================================================================================= | ================= | ========= | ============================================== | =============== | ====== | ========= | =============== | =================== | ========= | ========== | ===== | ================================================ | ============================================================= | ============== | ============= | 
| 7   | OSWEGO      | Salmon River Falls Trail                          | HIKING TRAIL       |           | Y          | N          | N      | N          | N     | Y       | N       | Y          | N          | N          | N          | N          | N          | N          | N          | N     | N          | N      | [http://www.dec.ny.gov/lands/63578.html#Access, null]                             | Destination Point |           | SALMON RIVER FALLS UNIQUE AREA                 | Existing/Compl  | N      | Y         | Carole Fraser   |                     | Y         | Y          |       |                                                  |                                                               | -75.9429914838 | 43.5491134979 | 
| 5   | WARREN      | Scaroon Manor Campground                          | CAMPGROUND         |           | N          | Y          | N      | Y          | N     | N       | N       | N          | Y          | Y          | N          | Y          | N          | Y          | N          | Y     | Y          | Y      | [http://www.dec.ny.gov/outdoor/72082.html#Access, null]                           | Destination Point | AFP       | SCAROON MANOR PUBLIC CAMPGROUND                | Existing/Incmpl | N      | Y         | Carole Fraser   |                     | Y         | Y          |       | entrance from Rte. 9                             | Directions: Entrance on Rte. 9.                               | -73.7913352398 | 43.767624959  | 
| 5   | HAMILTON    | William C Whitney Wilderness                      | CANOEING           |           | Y          | N          | N      | N          | N     | N       | N       | N          | N          | N          | N          | N          | N          | Y          | Y          | N     | Y          | N      | [http://www.dec.ny.gov/outdoor/9165.html#access, null]                            | Destination Point | AFP       | LITTLE TUPPER LAKE HQ ADMINISTRATIVE USE AREA  | Complete        | Y      | Y         | Doug Fitzgerald |                     | Y         | Y          |       |                                                  |                                                               | -74.5828973497 | 44.0492365537 | 
| 6   | ST LAWRENCE | Streeter Lake Campsites                           | PRIMITIVE CAMPSITE |           | Y          | Y          | N      | N          | Y     | N       | N       | N          | N          | N          | N          | N          | N          | N          | N          | N     | N          | N      | [http://www.dec.ny.gov/lands/75315.html#Access, null]                             | Destination Point | AFP       | ALDRICH POND WILD FOREST                       | Complete        | Y      | Y         | Blanche Town    |                     | Y         | Y          |       | along Streeter Lake Rd.                          | Directions: Along Streeter Lake Rd.                           | -75.0695199769 | 44.1110869122 | 
| 3   | ULSTER      | Alder Lake Picnic Site at Balsam Lake Mtn WF      | PICNIC SITE        |           | Y          | N          | N      | Y          | Y     | N       | N       | Y          | N          | N          | N          | N          | N          | N          | N          | N     | N          | N      | [http://www.dec.ny.gov/outdoor/9152.html#Alder_Lake_Accessible_Picnic_Area, null] | Destination Point | CFP       | BALSAM LAKE MOUNTAIN WILD FOREST               | Complete        | Y      | Y         | Dylan - Carole  | 2007-07-01T00:00:00 | Y         | Y          |       |                                                  |                                                               | -74.6807115737 | 42.0499793343 | 
| 3   | ULSTER      | Onteora Lake                                      | FISHING            |           | Y          | N          | N      | Y          | Y     | Y       | N       | N          | N          | N          | N          | Y          | N          | N          | N          | N     | N          | N      | [http://www.dec.ny.gov/lands/75323.html#Access, null]                             | Destination Point | CFP       | BLUESTONE WILD FOREST                          | Complete        | Y      | Y         | Carole Fraser   |                     | Y         | Y          |       |                                                  |                                                               | -74.0827107764 | 41.9839899847 | 
| 3   | SULLIVAN    | Mongaup Pond Campground                           | CAMPGROUND         |           | N          | Y          | N      | Y          | N     | Y       | N       | N          | N          | N          | N          | Y          | N          | N          | N          | Y     | Y          | Y      | [http://www.dec.ny.gov/outdoor/24484.html#access, null]                           | Destination Point | CFP       | MONGAUP POND CAMPGROUND                        | Complete        | Y      | Y         | Carole Fraser   |                     | Y         | Y          |       |                                                  |                                                               | -74.6911214656 | 41.9583932738 | 
| 3   | DUTCHESS    | Stony Kill Farm Environmental Education Center    | INTERPRETIVE SITE  |           | N          | N          | N      | Y          | N     | Y       | N       | N          | Y          | Y          | N          | N          | N          | N          | N          | N     | Y          | N      | [http://www.dec.ny.gov/education/1833.html#Accessibility, null]                   | Destination Point |           | STONY KILL FARM ENVIRONMENTAL EDUCATION CENTER | Existing/Compl  | N      | Y         | Carole Fraser   |                     | Y         | Y          |       |                                                  |                                                               | -73.9516692348 | 41.5429725187 | 
| 3   | ULSTER      | Lower Birch Creek Road Picnic Site @ Shandaken WF | PICNIC SITE        |           | N          | N          | N      | Y          | Y     | Y       | N       | N          | N          | N          | N          | Y          | N          | N          | N          | N     | N          | N      | [http://www.dec.ny.gov/lands/75328.html#Access, null]                             | Destination Point | CFP       | HALCOTT MOUNTAIN WILD FOREST                   | Complete        | Y      | Y         | Carole Fraser   |                     | Y         | Y          |       | at end of Lower Birch Creek Rd. (Reisser Estate) | Directions: At end of Lower Birch Creek Rd. (Reisser Estate). | -74.4444479286 | 42.1592753697 | 
| 3   | ULSTER      | Allaben Campsites at Shandaken Wild Forest        | PRIMITIVE CAMPSITE |           | Y          | Y          | N      | Y          | Y     | N       | N       | N          | N          | N          | N          | Y          | N          | N          | N          | N     | N          | N      | [http://www.dec.ny.gov/lands/75328.html#Access, null]                             | Destination Point | CFP       | SHANDAKEN WILD FOREST                          | Complete        | Y      | Y         | Carole Fraser   |                     | Y         | Y          |       | on Matyas Rd                                     | Directions: On Matyas Rd.                                     | -74.4519098856 | 42.1173227848 | 
```