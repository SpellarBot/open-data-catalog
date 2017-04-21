# Clear Channel Sign List - Times Sqaure

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/clear-channel-sign-list-times-sqaure-85353) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/wjtn-s4z7) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/wjtn-s4z7/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/wjtn-s4z7/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | wjtn-s4z7 |
| Name | Clear Channel Sign List - Times Sqaure |
| Attribution | Times Square Alliance (TSA) |
| Category | Business |
| Tags | times square alliance, times square, crossroads, crossroads of the world, nyc, new york city, new york, manhattan, theater, food, screens, pedestrian, entertainment, tourism, signs, clear channel |
| Created | 2011-10-31T17:09:10Z |
| Publication Date | 2011-10-31T17:13:53Z |

## Description

Clear Channel Spectacolor Sign Locations in Times Square

## Columns

```ls
| Included | Schema Type    | Field Name        | Name                 | Data Type | Render Type |
| ======== | ============== | ================= | ==================== | ========= | =========== |
| No       | time           | :updated_at       | updated_at           | meta_data | meta_data   |
| Yes      | series tag     | analysed_         | Analysed?            | text      | text        |
| Yes      | series tag     | description       | Description          | text      | text        |
| Yes      | series tag     | photo             | Photo                | text      | text        |
| Yes      | series tag     | note              | Note                 | text      | text        |
| Yes      | series tag     | type              | Type                 | text      | text        |
| Yes      | series tag     | height            | Height               | text      | text        |
| Yes      | series tag     | size              | Size                 | text      | text        |
| Yes      | numeric metric | of_signs_panel_a_ | # of Signs (Panel A) | number    | number      |
| Yes      | numeric metric | width_panel_a_    | Width (Panel A)      | number    | number      |
| Yes      | numeric metric | height_panel_a_   | Height (Panel A)     | number    | number      |
| Yes      | numeric metric | area_panel_a_     | Area (Panel A)       | number    | number      |
| Yes      | numeric metric | of_signs_panel_b_ | # of Signs (Panel B) | number    | number      |
| Yes      | numeric metric | width_panel_b_    | Width (Panel B)      | number    | number      |
| Yes      | numeric metric | height_panel_b_   | Height (Panel B)     | number    | number      |
| Yes      | numeric metric | area_panel_b_     | Area (Panel B)       | number    | number      |
| Yes      | numeric metric | total_of_signs    | Total # of Signs     | number    | number      |
| Yes      | numeric metric | total_area        | Total Area           | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:wjtn-s4z7 d:2011-10-31T10:09:21.000Z t:analysed_=n t:description="1560 Broadway- Colombian Coffee (Broadway@46th)" t:type=Vinyl t:size="?75' high x ?80' wide" m:area_panel_a_=6000 m:of_signs_panel_a_=1 m:total_area=6000 m:total_of_signs=1 m:area_panel_b_=0 m:height_panel_a_=80 m:width_panel_a_=75

series e:wjtn-s4z7 d:2011-10-31T10:09:21.000Z t:analysed_=n t:height="Above 65 Ft" t:description="Broadway Spire - Argent mortgage company (1567 Broadway @ 47th St)" t:type=Vinyl t:size="?160' high x ?20' wide" m:area_panel_a_=3200 m:of_signs_panel_a_=1 m:total_area=3200 m:total_of_signs=1 m:area_panel_b_=0 m:height_panel_a_=20 m:width_panel_a_=160

series e:wjtn-s4z7 d:2011-10-31T10:09:21.000Z t:analysed_=n t:description="Marriott Marquis - Column Wraps (Broadway between 45th & 46th)" t:type=Vinyl t:size="13 column wraps are ?8' high x ?4' wide; 2 column wraps are ?6' high x ?4' wide" m:area_panel_a_=416 m:of_signs_panel_a_=13 m:total_area=464 m:total_of_signs=15 m:area_panel_b_=48 m:height_panel_a_=4 m:width_panel_a_=8 m:width_panel_b_=6 m:height_panel_b_=4 m:of_signs_panel_b_=2
```

## Meta Commands

```ls
metric m:of_signs_panel_a_ p:integer l:"# of Signs (Panel A)" t:dataTypeName=number

metric m:width_panel_a_ p:integer l:"Width (Panel A)" t:dataTypeName=number

metric m:height_panel_a_ p:integer l:"Height (Panel A)" t:dataTypeName=number

metric m:area_panel_a_ p:integer l:"Area (Panel A)" t:dataTypeName=number

metric m:of_signs_panel_b_ p:integer l:"# of Signs (Panel B)" t:dataTypeName=number

metric m:width_panel_b_ p:integer l:"Width (Panel B)" t:dataTypeName=number

metric m:height_panel_b_ p:integer l:"Height (Panel B)" t:dataTypeName=number

metric m:area_panel_b_ p:integer l:"Area (Panel B)" t:dataTypeName=number

metric m:total_of_signs p:integer l:"Total # of Signs" t:dataTypeName=number

metric m:total_area p:integer l:"Total Area" t:dataTypeName=number

entity e:wjtn-s4z7 l:"Clear Channel Sign List - Times Sqaure" t:attribution="Times Square Alliance (TSA)" t:url=https://data.cityofnewyork.us/api/views/wjtn-s4z7

property e:wjtn-s4z7 t:meta.view v:id=wjtn-s4z7 v:category=Business v:averageRating=0 v:name="Clear Channel Sign List - Times Sqaure" v:attribution="Times Square Alliance (TSA)"

property e:wjtn-s4z7 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:wjtn-s4z7 t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | analysed_ | description                                                           | photo         | note          | type  | height      | size                                                                            | of_signs_panel_a_ | width_panel_a_ | height_panel_a_ | area_panel_a_ | of_signs_panel_b_ | width_panel_b_ | height_panel_b_ | area_panel_b_ | total_of_signs | total_area | 
| =========== | ========= | ===================================================================== | ============= | ============= | ===== | =========== | =============================================================================== | ================= | ============== | =============== | ============= | ================= | ============== | =============== | ============= | ============== | ========== | 
| 1320055761  | n         | 1560 Broadway- Colombian Coffee (Broadway@46th)                       |               |               | Vinyl |             | ?75' high x ?80' wide                                                           | 1                 | 75             | 80              | 6000          |                   |                |                 | 0             | 1              | 6000       | 
| 1320055761  | n         | Broadway Spire - Argent mortgage company (1567 Broadway @ 47th St)    |               |               | Vinyl | Above 65 Ft | ?160' high x ?20' wide                                                          | 1                 | 160            | 20              | 3200          |                   |                |                 | 0             | 1              | 3200       | 
| 1320055761  | n         | Marriott Marquis - Column Wraps (Broadway between 45th & 46th)        |               |               | Vinyl |             | 13 column wraps are ?8' high x ?4' wide; 2 column wraps are ?6' high x ?4' wide | 13                | 8              | 4               | 416           | 2                 | 6              | 4               | 48            | 15             | 464        | 
| 1320055761  | n         | 1460 Broadway (Broadway between 41st & 42nd)                          |               |               | Vinyl |             | Approx. 14' high x 96' wide                                                     | 1                 | 14             | 96              | 1344          |                   |                |                 | 0             | 1              | 1344       | 
| 1320055762  | y         | Marriott Marquis - Planters (Broadway & 45th)                         | IMG_8938      | Car ad        | Vinyl |             | ?40' high x ?50' wide                                                           | 1                 | 40             | 50              | 2000          |                   |                |                 | 0             | 1              | 2000       | 
| 1320055762  | y         | 1500 Broadway - GMC (Between 43rd & 44th)                             |               |               | LED   |             | ?35' high x ? 90' wide                                                          | 1                 | 35             | 90              | 3150          |                   |                |                 | 0             | 1              | 3150       | 
| 1320055762  | y         | Winter Garden Theatre (Broadway @ 50th)                               | IMG_8889      | Ugg           | Vinyl | Under 65 Ft | ?28' high x ?48' wide                                                           | 1                 | 28             | 48              | 1344          |                   |                |                 | 0             | 1              | 1344       | 
| 1320055762  | y         | Planet Hollwood (1540 Broadway)                                       | IMG_8934/9007 | True Crime    | Vinyl |             | Two faces: ?30' high x ?68' wide                                                | 2                 | 30             | 68              | 4080          |                   |                |                 | 0             | 2              | 4080       | 
| 1320055762  | y         | Morgan Stanley Building (1626 Broadway btw 49th & 50th)               | IMG_8872/3    | Falling skies | Vinyl | Under 65 Ft | ?29' high x ?125' wide                                                          | 1                 | 29             | 125             | 3625          |                   |                |                 | 0             | 1              | 3625       | 
| 1320055762  | n         | Winter Garden Theatre Package (7th Avenue & Broadway Btw 50th & 51st) |               |               | Vinyl |             | N/face: ?30' high x ?40' wide; S/face: ?30' high x ?29' wide                    | 1                 | 30             | 40              | 1200          | 1                 | 30             | 29              | 870           | 2              | 2070       | 
```