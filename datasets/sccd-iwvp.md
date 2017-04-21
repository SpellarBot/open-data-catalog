# Clearance Heights for Large Vehicle Circulation

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/clearance-heights-for-large-vehicle-circulation) |
| Metadata | [Link](https://data.sfgov.org/api/views/sccd-iwvp) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/sccd-iwvp/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/sccd-iwvp/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | sccd-iwvp |
| Name | Clearance Heights for Large Vehicle Circulation |
| Attribution | City and County of San Francisco |
| Category | Transportation |
| Tags | vehicle clearance heights |
| Created | 2016-08-18T20:50:30Z |
| Publication Date | 2016-10-12T00:58:45Z |

## Description

To identify the location and clearance heights for large vehicle circulation in the City.

## Columns

```ls
| Included | Schema Type | Field Name       | Name             | Data Type | Render Type |
| ======== | =========== | ================ | ================ | ========= | =========== |
| No       | time        | :updated_at      | updated_at       | meta_data | meta_data   |
| Yes      | series tag  | object_id        | Object ID        | text      | number      |
| Yes      | series tag  | type             | Type             | text      | text        |
| Yes      | series tag  | location         | Location         | text      | text        |
| Yes      | series tag  | height           | Height           | text      | text        |
| No       |             | last_edited_date | Last Edited Date | date      | date        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = last_edited_date
```

## Data Commands

```ls
series e:sccd-iwvp d:2017-04-15T16:41:33.000Z t:height=22' t:location="HWY 1 & KOBBE" t:object_id=1 t:type=OVERPASS m:row_number.sccd-iwvp=1

series e:sccd-iwvp d:2017-04-15T16:41:33.000Z t:height=15.9' t:location="HWY 101 & 18TH ST(BTWN SAN BRUNO & UTAH)" t:object_id=2 t:type=OVERPASS m:row_number.sccd-iwvp=2

series e:sccd-iwvp d:2017-04-15T16:41:33.000Z t:height=20' t:location="HWY 101 & HARRISON(BTWN 13TH ST & 14TH ST)" t:object_id=3 t:type=OVERPASS m:row_number.sccd-iwvp=3
```

## Meta Commands

```ls
metric m:row_number.sccd-iwvp p:long l:"Row Number"

entity e:sccd-iwvp l:"Clearance Heights for Large Vehicle Circulation" t:attribution="City and County of San Francisco" t:url=https://data.sfgov.org/api/views/sccd-iwvp

property e:sccd-iwvp t:meta.view v:id=sccd-iwvp v:category=Transportation v:attributionLink=http://sfgov.org/ v:averageRating=0 v:name="Clearance Heights for Large Vehicle Circulation" v:attribution="City and County of San Francisco"

property e:sccd-iwvp t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:sccd-iwvp t:meta.view.owner v:id=dbag-6qd9 v:screenName=OpenData v:displayName=OpenData

property e:sccd-iwvp t:meta.view.tableauthor v:id=dbag-6qd9 v:screenName=OpenData v:roleName=publisher v:displayName=OpenData
```

## Top Records

```ls
| :updated_at | object_id | type     | location                                     | height | last_edited_date | 
| =========== | ========= | ======== | ============================================ | ====== | ================ | 
| 1492274493  | 1         | OVERPASS | HWY 1 & KOBBE                                | 22'    |                  | 
| 1492274493  | 2         | OVERPASS | HWY 101 & 18TH ST(BTWN SAN BRUNO & UTAH)     | 15.9'  |                  | 
| 1492274493  | 3         | OVERPASS | HWY 101 & HARRISON(BTWN 13TH ST & 14TH ST)   | 20'    |                  | 
| 1492274493  | 4         | OVERPASS | HWY 101 & VALENCIA ST(BTWN DUBOCE & MCCOPPIN | 15'3"  |                  | 
| 1492274493  | 5         | OVERPASS | I-280 & ALEMANY BLVD(BTWN ORIZABA AVE & PALM | 16'2"  |                  | 
| 1492274493  | 6         | OVERPASS | I-80 & 7TH ST(BTWN BRYANT & HARRISON)        | 14'9"  |                  | 
| 1492274493  | 7         | OVERPASS | I-80 E ON RAMP & 4TH ST(BTWN BRYANT & HARRIS | 12'6"  |                  | 
| 1492274493  | 8         | OVERPASS | 3RD ST & TERRY A FRANCOIS                    | 18'8"  |                  | 
| 1492274493  | 9         | TUNNEL   | BROADWAY & HYDE                              | 20'    |                  | 
| 1492274493  | 10        | TUNNEL   | BROADWAY & LEAVENWORTH                       | 18'    |                  | 
```