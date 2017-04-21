# neigh_zoning_summary

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/neigh-zoning-summary) |
| Metadata | [Link](https://data.austintexas.gov/api/views/sjzt-gzvd) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/sjzt-gzvd/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/sjzt-gzvd/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | sjzt-gzvd |
| Name | neigh_zoning_summary |
| Attribution | City of Austin Development Services Department |
| Created | 2016-05-27T21:08:15Z |
| Publication Date | 2016-05-27T21:08:57Z |

## Description

Shows the acreage of "general" zoning categories in each neigborhood reporting area. Neigborhood reporting areas are a combination of official and unofficial boundaries for the purpose of collecting and reporting information (data) in Austin. They are comprised of Neighborhood Planning Areas (in the central core) which are approved and can only be changed by City Council. Areas outside of neighborhood planning areas were drawn using logical boundaries such as roadways, and covering larger areas encompassing several neighborhoods. A Neighborhood Reporting Area map is available at http://www.austintexas.gov/sites/default/files/files/Planning/Demographics/Neighborhood_Reporting_Areas.pdf. The zoning data does not indicate public right-of-way (ROW) areas, such as streets and railroad ROW's, which are not typically zoned. General zoning includes major base zone district categories plus zones with vertical and mixed use overlays. Zoning maps are available at http://austintexas.gov/page/planning-maps, and http://www.arcgis.com/home/item.html?id=6803413bed5e4aa0bb13c93c71ccb41d. More information on zoning is available at http://www.austintexas.gov/department/zoning. This information is taken from the zoning layer https://data.austintexas.gov/Geodata/Zoning/5rzy-nm5e

## Columns

```ls
| Included | Schema Type    | Field Name     | Name           | Data Type | Render Type |
| ======== | ============== | ============== | ============== | ========= | =========== |
| No       | time           | :updated_at    | updated_at     | meta_data | meta_data   |
| Yes      | series tag     | objectid       | OBJECTID       | text      | number      |
| Yes      | numeric metric | frequency      | FREQUENCY      | number    | number      |
| Yes      | series tag     | neighname      | NEIGHNAME      | text      | text        |
| Yes      | series tag     | base_zone      | BASE_ZONE      | text      | text        |
| Yes      | series tag     | general_zoning | GENERAL_ZONING | text      | text        |
| Yes      | numeric metric | acres          | ACRES          | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:sjzt-gzvd d:2016-05-27T14:08:18.000Z t:neighname=ALLANDALE t:general_zoning=Commercial t:base_zone=CS t:objectid=41 m:frequency=11 m:acres=23.4307635658596

series e:sjzt-gzvd d:2016-05-27T14:08:18.000Z t:neighname=ALLANDALE t:general_zoning="Vertical Mixed Use" t:base_zone=CS t:objectid=42 m:frequency=6 m:acres=42.3724404568871

series e:sjzt-gzvd d:2016-05-27T14:08:18.000Z t:neighname=ALLANDALE t:general_zoning=Commercial t:base_zone=CS-1 t:objectid=43 m:frequency=5 m:acres=0.987334089836617
```

## Meta Commands

```ls
metric m:frequency p:integer l:FREQUENCY t:dataTypeName=number

metric m:acres p:double l:ACRES t:dataTypeName=number

entity e:sjzt-gzvd l:neigh_zoning_summary t:attribution="City of Austin Development Services Department" t:url=https://data.austintexas.gov/api/views/sjzt-gzvd

property e:sjzt-gzvd t:meta.view v:id=sjzt-gzvd v:averageRating=0 v:name=neigh_zoning_summary v:attribution="City of Austin Development Services Department"

property e:sjzt-gzvd t:meta.view.owner v:id=4y62-vmjm v:screenName="Paul Frank" v:displayName="Paul Frank"

property e:sjzt-gzvd t:meta.view.tableauthor v:id=4y62-vmjm v:screenName="Paul Frank" v:roleName=editor_stories v:displayName="Paul Frank"
```

## Top Records

```ls
| :updated_at | objectid | frequency | neighname     | base_zone | general_zoning     | acres             | 
| =========== | ======== | ========= | ============= | ========= | ================== | ================= | 
| 1464358098  | 41       | 11        | ALLANDALE     | CS        | Commercial         | 23.4307635658596  | 
| 1464358098  | 42       | 6         | ALLANDALE     | CS        | Vertical Mixed Use | 42.3724404568871  | 
| 1464358098  | 43       | 5         | ALLANDALE     | CS-1      | Commercial         | 0.987334089836617 | 
| 1464358098  | 44       | 3         | ALLANDALE     | CS-1      | Vertical Mixed Use | 0.291388005802087 | 
| 1464358098  | 45       | 1         | ALLANDALE     | GO        | Office             | 4.7720930932257   | 
| 1464358098  | 47       | 2         | ALLANDALE     | GR        | Mixed Use          | 5.37195966808127  | 
| 1470434876  | 192      | 5         | BOULDIN CREEK | CS-1      | Commercial         | 8.51116585023122  | 
| 1464358098  | 50       | 5         | ALLANDALE     | LR        | Commercial         | 8.38988975944708  | 
| 1464358098  | 51       | 1         | ALLANDALE     | LR        | Mixed Use          | 0.147077705418353 | 
| 1464358098  | 52       | 3         | ALLANDALE     | MF-3      | Multi-Family       | 4.5249841782352   | 
```