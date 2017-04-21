# Campgrounds by County Within Adirondack & Catskill Forest Preserve

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/campgrounds-by-county-within-adirondack-catskill-forest-preserve) |
| Metadata | [Link](https://data.ny.gov/api/views/tnqf-vydw) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/tnqf-vydw/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/tnqf-vydw/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | tnqf-vydw |
| Name | Campgrounds by County Within Adirondack & Catskill Forest Preserve |
| Attribution | New York State Department of Environmental Conservation |
| Category | Recreation |
| Tags | campground, camping, hiking, tents |
| Created | 2013-02-14T03:50:44Z |
| Publication Date | 2014-09-19T17:24:58Z |

## Description

The Department of Environmental Conservation operates 51 campgrounds located in the Adirondack and Catskill Parks. The campgrounds provide a wide variety of experiences, including island camping, tent and trailer camping, boat launching facilities, hiking trails, beaches and day use areas with picnic tables and grills. Fishing licenses are no longer being sold at any of our campground facilities. This data set provides a listing of the campgrounds, with direct links to individual web pages containing additional information for each campground.

## Columns

```ls
| Included | Schema Type | Field Name  | Name       | Data Type | Render Type |
| ======== | =========== | =========== | ========== | ========= | =========== |
| No       | time        | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag  | campground  | Campground | text      | text        |
| Yes      | series tag  | county      | County     | text      | text        |
| Yes      | series tag  | url         | URL        | url       | url         |
| No       |             | y           | Y          | number    | number      |
| No       |             | x           | X          | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = y,x
```

## Data Commands

```ls
series e:tnqf-vydw d:2014-09-19T10:24:27.000Z t:county=HERKIMER t:campground="Alger Island Campground" t:url=http://www.dec.ny.gov/outdoor/24451.html m:row_number.tnqf-vydw=1

series e:tnqf-vydw d:2014-09-19T10:24:27.000Z t:county=CLINTON t:campground="Ausable Point Campground" t:url=http://www.dec.ny.gov/outdoor/24452.html m:row_number.tnqf-vydw=2

series e:tnqf-vydw d:2014-09-19T10:24:27.000Z t:county=SULLIVAN t:campground="Beaverkill Campground" t:url=http://www.dec.ny.gov/outdoor/24455.html m:row_number.tnqf-vydw=3
```

## Meta Commands

```ls
metric m:row_number.tnqf-vydw p:long l:"Row Number"

entity e:tnqf-vydw l:"Campgrounds by County Within Adirondack & Catskill Forest Preserve" t:attribution="New York State Department of Environmental Conservation" t:url=https://data.ny.gov/api/views/tnqf-vydw

property e:tnqf-vydw t:meta.view v:id=tnqf-vydw v:category=Recreation v:attributionLink=http://www.dec.ny.gov/outdoor/camping.html v:averageRating=0 v:name="Campgrounds by County Within Adirondack & Catskill Forest Preserve" v:attribution="New York State Department of Environmental Conservation"

property e:tnqf-vydw t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:tnqf-vydw t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:tnqf-vydw t:meta.view.metadata.custom_fields.common_core v:Contact_Email=opendata@its.ny.gov v:Publisher="State of New York" v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| :updated_at | campground                   | county      | url                                              | y         | x          | 
| =========== | ============================ | =========== | ================================================ | ========= | ========== | 
| 1411122267  | Alger Island Campground      | HERKIMER    | [http://www.dec.ny.gov/outdoor/24451.html, null] | 43.745784 | -74.874585 | 
| 1411122267  | Ausable Point Campground     | CLINTON     | [http://www.dec.ny.gov/outdoor/24452.html, null] | 44.570662 | -73.430416 | 
| 1411122267  | Beaverkill Campground        | SULLIVAN    | [http://www.dec.ny.gov/outdoor/24455.html, null] | 41.977219 | -74.839592 | 
| 1411122267  | Brown Tract Pond Campground  | HAMILTON    | [http://www.dec.ny.gov/outdoor/24456.html, null] | 43.809152 | -74.701188 | 
| 1411122267  | Buck Pond Campground         | FRANKLIN    | [http://www.dec.ny.gov/outdoor/24457.html, null] | 44.501034 | -74.112157 | 
| 1411122267  | Caroga Lake Campground       | FULTON      | [http://www.dec.ny.gov/outdoor/24458.html, null] | 43.124012 | -74.471252 | 
| 1411122267  | Cranberry Lake Campground    | ST LAWRENCE | [http://www.dec.ny.gov/outdoor/24460.html, null] | 44.195805 | -74.82649  | 
| 1411122267  | Crown Point Campground       | ESSEX       | [http://www.dec.ny.gov/outdoor/24461.html, null] | 44.02605  | -73.421172 | 
| 1411122267  | Devil'S Tombstone Campground | GREENE      | [http://www.dec.ny.gov/outdoor/24462.html, null] | 42.152974 | -74.206624 | 
| 1411122267  | Eagle Point Campground       | WARREN      | [http://www.dec.ny.gov/outdoor/24463.html, null] | 43.747823 | -73.795196 | 
```