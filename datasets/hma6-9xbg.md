# Agricultural Commoditites Grown By Farmer

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/agricultural-commoditites-grown-by-farmer) |
| Metadata | [Link](https://data.ct.gov/api/views/hma6-9xbg) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/hma6-9xbg/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/hma6-9xbg/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | hma6-9xbg |
| Name | Agricultural Commoditites Grown By Farmer |
| Attribution | Department of Agriculture |
| Category | Environment and Natural Resources |
| Tags | agriculture, farming, commodities |
| Created | 2014-09-04T15:01:44Z |
| Publication Date | 2014-09-04T16:57:09Z |

## Description

Listing of individual commodities grown by licensed farmers in Connecticut

## Columns

```ls
| Included | Schema Type | Field Name  | Name       | Data Type | Render Type |
| ======== | =========== | =========== | ========== | ========= | =========== |
| No       | time        | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag  | farm_name   | Farm Name  | text      | text        |
| Yes      | series tag  | category    | Category   | text      | text        |
| Yes      | series tag  | item        | Item       | text      | text        |
| Yes      | series tag  | farmer_id   | Farmer ID  | text      | number      |
| Yes      | series tag  | website     | Website    | url       | url         |
| Yes      | series tag  | suite       | Suite      | text      | text        |
| Yes      | series tag  | zipcode     | Zipcode    | text      | text        |
| Yes      | series tag  | phone1      | Phone1     | text      | text        |
| Yes      | series tag  | business    | Business   | text      | text        |
| No       |             | l           | l          | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = l
```

## Data Commands

```ls
series e:hma6-9xbg d:2014-09-04T08:03:28.000Z t:category="Livestock Products" t:zipcode=06268 t:item=goat t:farmer_id=5377 t:business="John Wolfe" m:row_number.hma6-9xbg=1

series e:hma6-9xbg d:2014-09-04T08:03:59.000Z t:category=honey t:zipcode=06756 t:item=honey t:farmer_id=2186 t:phone1=860-491-2338 t:business="Charles Howe" m:row_number.hma6-9xbg=2

series e:hma6-9xbg d:2014-09-04T08:04:02.000Z t:category=vegetables t:zipcode=06247 t:item=Potatoes t:farmer_id=16722 t:phone1=860-455-1351 m:row_number.hma6-9xbg=3
```

## Meta Commands

```ls
metric m:row_number.hma6-9xbg p:long l:"Row Number"

entity e:hma6-9xbg l:"Agricultural Commoditites Grown By Farmer" t:attribution="Department of Agriculture" t:url=https://data.ct.gov/api/views/hma6-9xbg

property e:hma6-9xbg t:meta.view v:id=hma6-9xbg v:category="Environment and Natural Resources" v:attributionLink="http://www.ct.gov/doag/cwp/view.asp?a=1367&q=259096" v:averageRating=0 v:name="Agricultural Commoditites Grown By Farmer" v:attribution="Department of Agriculture"

property e:hma6-9xbg t:meta.view.license v:name="Public Domain"

property e:hma6-9xbg t:meta.view.owner v:id=cvy9-n6sb v:screenName="Tyler Kleykamp" v:lastNotificationSeenAt=1492608796 v:displayName="Tyler Kleykamp"

property e:hma6-9xbg t:meta.view.tableauthor v:id=cvy9-n6sb v:screenName="Tyler Kleykamp" v:roleName=administrator v:lastNotificationSeenAt=1492608796 v:displayName="Tyler Kleykamp"
```

## Top Records

```ls
| :updated_at | farm_name | category           | item         | farmer_id | website      | suite | zipcode    | phone1       | business                    | l | 
| =========== | ========= | ================== | ============ | ========= | ============ | ===== | ========== | ============ | =========================== | = | 
| 1409817808  |           | Livestock Products | goat         | 5377      | [null, null] |       | 06268      |              | John Wolfe                  | 0 | 
| 1409817839  |           | honey              | honey        | 2186      | [null, null] |       | 06756      | 860-491-2338 | Charles Howe                | 0 | 
| 1409817842  |           | vegetables         | Potatoes     | 16722     | [null, null] |       | 06247      | 860-455-1351 |                             |   | 
| 1409817854  |           | Farm Products      | pasture      | 1340      | [null, null] |       | 06351      | 860-376-2306 | Lawrence Dudek              | 0 | 
| 1409817856  |           | Vegetables         | Corn         | 4087      | [null, null] |       | 06795      |              | Albinas Rickevicius         | 0 | 
| 1409817858  |           | vegetables         | Broccoli     | 584       | [null, null] |       | 06247      |              | Richard D. & Irene Q. Brown | 0 | 
| 1409817867  |           | vegetables         | Peppers      | 1318      | [null, null] |       | 06078      | 860-668-1763 | Brian & Karne Doyon         | 0 | 
| 1409817869  |           | vegetables         | Garlic       | 15350     | [null, null] |       | 06259-1128 | 860-928-4554 |                             |   | 
| 1409817879  |           | Farm Products      | Hay          | 1976      | [null, null] |       | 06483      |              | Jeffrey Haney               | 0 | 
| 1409817879  |           | fruit              | Strawberries | 16722     | [null, null] |       | 06247      | 860-455-1351 |                             |   | 
```