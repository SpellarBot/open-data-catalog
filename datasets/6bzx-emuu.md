# Times Square Signage

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/times-square-signage-fcb49) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/6bzx-emuu) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/6bzx-emuu/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/6bzx-emuu/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 6bzx-emuu |
| Name | Times Square Signage |
| Attribution | Times Square Alliance (TSA) |
| Category | Business |
| Tags | times square alliance, times square, crossroads, crossroads of the world, nyc, new york city, new york, manhattan, theater, food, screens, pedestrian, entertainment, tourism, signage |
| Created | 2011-10-31T17:19:31Z |
| Publication Date | 2011-10-31T17:42:29Z |

## Description

Information on signage in the Times Square area

## Columns

```ls
| Included | Schema Type    | Field Name                   | Name                            | Data Type | Render Type |
| ======== | ============== | ============================ | =============================== | ========= | =========== |
| No       | time           | :updated_at                  | updated_at                      | meta_data | meta_data   |
| Yes      | series tag     | screen_name_led_vinyl_signs_ | Screen Name (LED + Vinyl Signs) | text      | text        |
| No       |                | building_address             | Building Address                | text      | text        |
| Yes      | series tag     | location_description         | Location Description            | text      | text        |
| Yes      | series tag     | location                     | Location                        | text      | text        |
| Yes      | series tag     | height                       | Height                          | text      | text        |
| Yes      | series tag     | type                         | Type                            | text      | text        |
| No       |                | _1                           | #                               | number    | number      |
| Yes      | numeric metric | width                        | Width                           | number    | number      |
| Yes      | numeric metric | height_1                     | __Height                        | number    | number      |
| No       |                | sf                           | SF                              | number    | number      |
| Yes      | series tag     | note_photo                   | Note/Photo                      | text      | text        |
| No       |                | _2                           | _#                              | number    | number      |
| Yes      | numeric metric | width                        | _Width                          | number    | number      |
| Yes      | numeric metric | height_2                     | _Height                         | number    | number      |
| Yes      | numeric metric | _sf                          | _SF                             | number    | number      |
| Yes      | numeric metric | total                        | TOTAL                           | number    | number      |
| Yes      | numeric metric | total_sf                     | TOTAL SF                        | number    | number      |
| Yes      | series tag     | total_by_type                | TOTAL BY TYPE                   | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = building_address,_1,sf,_2
```

## Data Commands

```ls
series e:6bzx-emuu d:2011-10-31T10:19:34.000Z t:height=Marquee t:note_photo=IMG_8993 t:screen_name_led_vinyl_signs_=Modell's t:location=42nd/Below t:type=LED m:total=1 m:total_sf=300 m:height_1=10 m:_sf=0

series e:6bzx-emuu d:2011-10-31T10:19:34.000Z t:height=Marquee t:screen_name_led_vinyl_signs_="Ripley's Odditorium Screen (3 LED Screens)" t:location=42nd/Below t:location_description="Marquee Level" t:type=LED m:total=3 m:total_sf=44 m:_sf=0

series e:6bzx-emuu d:2011-10-31T10:19:34.000Z t:height="Under 65 Ft" t:note_photo=IMG_8998 t:screen_name_led_vinyl_signs_="Above Chevys corner (1/9 LED center)" t:location=42nd/Below t:location_description="NE corner of 42nd St and 8th Ave" t:type=LED m:total=1 m:total_sf=121 m:height_1=11 m:_sf=0
```

## Meta Commands

```ls
metric m:width p:integer l:Width t:dataTypeName=number

metric m:height_1 p:integer l:__Height t:dataTypeName=number

metric m:width p:integer l:_Width t:dataTypeName=number

metric m:height_2 p:integer l:_Height t:dataTypeName=number

metric m:_sf p:integer l:_SF t:dataTypeName=number

metric m:total p:integer l:TOTAL t:dataTypeName=number

metric m:total_sf p:integer l:"TOTAL SF" t:dataTypeName=number

entity e:6bzx-emuu l:"Times Square Signage" t:attribution="Times Square Alliance (TSA)" t:url=https://data.cityofnewyork.us/api/views/6bzx-emuu

property e:6bzx-emuu t:meta.view v:id=6bzx-emuu v:category=Business v:averageRating=0 v:name="Times Square Signage" v:attribution="Times Square Alliance (TSA)"

property e:6bzx-emuu t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:6bzx-emuu t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | screen_name_led_vinyl_signs_               | building_address | location_description             | location   | height      | type | _1 | width | height_1 | sf   | note_photo | _2 | width | height_2 | _sf | total | total_sf | total_by_type | 
| =========== | ========================================== | ================ | ================================ | ========== | =========== | ==== | == | ===== | ======== | ==== | ========== | == | ===== | ======== | === | ===== | ======== | ============= | 
| 1320056374  | Modell's                                   | 234 W 42nd St    |                                  | 42nd/Below | Marquee     | LED  | 1  | 30    | 10       | 300  | IMG_8993   |    |       |          | 0   | 1     | 300      |               | 
| 1320056374  | Ripley's Odditorium Screen (3 LED Screens) | 234 W 42nd St    | Marquee Level                    | 42nd/Below | Marquee     | LED  | 3  |       |          | 44   |            |    |       |          | 0   | 3     | 44       |               | 
| 1320056374  | Above Chevys corner (1/9 LED center)       | 243 W 42nd St    | NE corner of 42nd St and 8th Ave | 42nd/Below | Under 65 Ft | LED  | 1  | 11    | 11       | 121  | IMG_8998   |    |       |          | 0   | 1     | 121      |               | 
| 1320056374  | CBS/Panasonic                              | 253 W 42nd       | Above Cold Stone                 | 42nd/Below | Under 65 Ft | LED  | 1  | 24    | 18       | 432  | IMG_8994   |    |       |          |     | 1     | 432      |               | 
| 1320056374  | Skechers                                   | 3 Times Sq       | Above 42nd/7th subway entrance   | 42nd/Below | Under 65 Ft | LED  | 1  | 4     | 10       | 40   | IMG_8985   |    |       |          | 0   | 1     | 40       |               | 
| 1320056374  | NBC Screen                                 | 5 Times Sq       | Above Champs Sports              | 42nd/Below | Above 65 Ft | LED  | 1  | 18    | 13       | 234  | IMG_8979   |    |       |          | 0   | 1     | 234      |               | 
| 1320056374  | Toshiba Below Highest Toshba Screen        | 1 Times Sq       | Below Highest Toshiba Screen     | Bowtie     | Above 65 Ft | LED  | 1  | 51    | 53       | 2703 |            |    |       |          | 0   | 1     | 2703     |               | 
| 1320056374  | Toshiba (Highest Screen)                   | 1 Times Sq       | Tallest Point on 1 Times Sq.     | Bowtie     | Above 65 Ft | LED  | 1  | 40    | 53       | 2120 |            |    |       |          | 0   | 1     | 2120     |               | 
| 1320056374  | Anheuser-Busch Budlight Screen             | 1 Times Sq       | High Level- Above Sony News Corp | Bowtie     | Above 65 Ft | LED  | 1  | 35    | 50       | 1750 | IMG_8953   |    |       |          | 0   | 1     | 1750     |               | 
| 1320056374  | Sony News Corp Screen                      | 1 Times Sq       | Below the Budlight Screen        | Bowtie     | Under 65 Ft | LED  | 1  | 35    | 40       | 1400 |            |    |       |          | 0   | 1     | 1400     |               | 
```