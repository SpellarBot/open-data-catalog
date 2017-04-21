# Bird Conservation Areas

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/bird-conservation-areas) |
| Metadata | [Link](https://data.ny.gov/api/views/9yjx-h3yi) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/9yjx-h3yi/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/9yjx-h3yi/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | 9yjx-h3yi |
| Name | Bird Conservation Areas |
| Attribution | New York State Department of Environmental Conservation |
| Category | Recreation |
| Tags | birds, environmental education, conservation, bird conservation areas |
| Created | 2013-02-14T03:17:42Z |
| Publication Date | 2013-03-01T18:52:53Z |

## Description

This data set shows point locations of Bird Conservation Areas. Bird Conservation Areas are New York State lands that have been officially designated for their value to bird conservation. Points are approximate locations and may represent large areas.

## Columns

```ls
| Included | Schema Type    | Field Name | Name                        | Data Type     | Render Type   |
| ======== | ============== | ========== | =========================== | ============= | ============= |
| Yes      | series tag     | bcaname    | Bird Conservation Area Name | text          | text          |
| Yes      | time           | designated | Designated                  | calendar_date | calendar_date |
| Yes      | series tag     | picurl     | Picture URL                 | url           | url           |
| Yes      | numeric metric | gewidth    | GEWIDTH                     | number        | number        |
| Yes      | numeric metric | gmwidth    | GMWIDTH                     | number        | number        |
| Yes      | numeric metric | gmheight   | GMHEIGHT                    | number        | number        |
| Yes      | series tag     | url        | URL                         | url           | url           |
| No       |                | point_x    | POINT_X                     | number        | number        |
| No       |                | point_y    | POINT_Y                     | number        | number        |
```

## Time Field

```ls
Value = designated
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = point_x,point_y
```

## Data Commands

```ls
series e:9yjx-h3yi d:1998-08-31T00:00:00.000Z t:bcaname="Buckhorn Island" t:url=http://www.dec.ny.gov/animals/27685.html m:gewidth=0 m:gmheight=0 m:gmwidth=0

series e:9yjx-h3yi d:2000-05-05T00:00:00.000Z t:bcaname="Braddock Bay" t:picurl=http://www.dec.ny.gov/images/environmentdec_images/BB17.jpg t:url=http://www.dec.ny.gov/animals/27691.html m:gewidth=250 m:gmheight=117 m:gmwidth=175

series e:9yjx-h3yi d:2000-05-05T00:00:00.000Z t:bcaname="Montezuma Wetlands Complex" t:picurl=http://www.dec.ny.gov/images/environmentdec_images/montezuma41006.jpg t:url=http://www.dec.ny.gov/animals/27124.html m:gewidth=250 m:gmheight=115 m:gmwidth=175
```

## Meta Commands

```ls
metric m:gewidth p:integer l:GEWIDTH t:dataTypeName=number

metric m:gmwidth p:integer l:GMWIDTH t:dataTypeName=number

metric m:gmheight p:integer l:GMHEIGHT t:dataTypeName=number

entity e:9yjx-h3yi l:"Bird Conservation Areas" t:attribution="New York State Department of Environmental Conservation" t:url=https://data.ny.gov/api/views/9yjx-h3yi

property e:9yjx-h3yi t:meta.view v:id=9yjx-h3yi v:category=Recreation v:attributionLink=http://www.dec.ny.gov/animals/30935.html v:averageRating=0 v:name="Bird Conservation Areas" v:attribution="New York State Department of Environmental Conservation"

property e:9yjx-h3yi t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:9yjx-h3yi t:meta.view.tableauthor v:id=mwxm-zess v:profileImageUrlMedium=/api/users/mwxm-zess/profile_images/THUMB v:profileImageUrlLarge=/api/users/mwxm-zess/profile_images/LARGE v:screenName="Lindsey Krough" v:profileImageUrlSmall=/api/users/mwxm-zess/profile_images/TINY v:roleName=administrator v:displayName="Lindsey Krough"

property e:9yjx-h3yi t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| bcaname                      | designated          | picurl                                                                        | gewidth | gmwidth | gmheight | url                                              | point_x        | point_y       | 
| ============================ | =================== | ============================================================================= | ======= | ======= | ======== | ================================================ | ============== | ============= | 
| Buckhorn Island              | 1998-08-31T00:00:00 | [null, null]                                                                  | 0       | 0       | 0        | [http://www.dec.ny.gov/animals/27685.html, null] | -78.9880816874 | 43.0618647012 | 
| Braddock Bay                 | 2000-05-05T00:00:00 | [http://www.dec.ny.gov/images/environmentdec_images/BB17.jpg, null]           | 250     | 175     | 117      | [http://www.dec.ny.gov/animals/27691.html, null] | -77.6942944027 | 43.274059525  | 
| Montezuma Wetlands Complex   | 2000-05-05T00:00:00 | [http://www.dec.ny.gov/images/environmentdec_images/montezuma41006.jpg, null] | 250     | 175     | 115      | [http://www.dec.ny.gov/animals/27124.html, null] | -76.7429666225 | 43.0811176528 | 
| Eastern Lake Ontario Marshes | 1998-08-31T00:00:00 | [http://www.dec.ny.gov/images/regions_images/blackpd3.jpg, null]              | 300     | 160     | 120      | [http://www.dec.ny.gov/animals/27256.html, null] | -76.1943013089 | 43.7290997409 | 
| Joseph Davis                 | 2005-03-14T00:00:00 | [null, null]                                                                  | 0       | 0       | 0        | [http://www.dec.ny.gov/animals/27159.html, null] | -79.0405395637 | 43.2134654291 | 
| Minnewaska                   | 2006-09-25T00:00:00 | [null, null]                                                                  | 0       | 0       | 0        | [http://www.dec.ny.gov/animals/32008.html, null] | -74.2767302695 | 41.7141447628 | 
| Caumsett                     | 2006-09-25T00:00:00 | [null, null]                                                                  | 0       | 0       | 0        | [http://www.dec.ny.gov/animals/31830.html, null] | -73.4681342882 | 40.9273220738 | 
| Valcour Island               | 2006-09-25T00:00:00 | [null, null]                                                                  | 0       | 0       | 0        | [http://www.dec.ny.gov/animals/32055.html, null] | -73.4165568527 | 44.6213662824 | 
| Point Peninsula              | 2006-09-25T00:00:00 | [http://www.dec.ny.gov/images/regions_images/ppfield.jpg, null]               | 300     | 160     | 120      | [http://www.dec.ny.gov/animals/32025.html, null] | -76.253481376  | 43.9992040708 | 
| Lake Shore Marshes           | 2006-09-25T00:00:00 | [null, null]                                                                  | 0       | 0       | 0        | [http://www.dec.ny.gov/animals/32004.html, null] | -76.8490563365 | 43.2888792622 | 
```