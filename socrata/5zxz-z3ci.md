# Campgrounds by County Outside Adirondack & Catskill Forest Preserve

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/campgrounds-by-county-outside-adirondack-catskill-forest-preserve) |
| Metadata | [Link](https://data.ny.gov/api/views/5zxz-z3ci) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/5zxz-z3ci/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/5zxz-z3ci/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | 5zxz-z3ci |
| Name | Campgrounds by County Outside Adirondack & Catskill Forest Preserve |
| Attribution | New York State Office of Parks, Recreation and Historic Preservation |
| Category | Recreation |
| Tags | parks, recreation, camping |
| Created | 2013-02-15T18:01:23Z |
| Publication Date | 2015-01-14T17:11:52Z |

## Description

The New York State Office of Parks, Recreation and Historic Preservation (OPRHP) oversees more than 214 state parks and historic sites, encompassing nearly 335,000 acres, that are visited by 60 million people annually. These facilities contribute to the economic vitality and quality of life of local communities and directly support New York?s tourism industry. Parks also provide a place for families and children to be active and exercise, promoting healthy lifestyles. The agency is responsible for the operation and stewardship of the state park system as well as advancing a statewide parks, historic preservation, and open space mission.The New York State Office of Parks and Recreation operates campgrounds in 65 state parks across New York (outside the Adirondack and Catskill Forest Preserves) offering more than 9,000 campsites, cabins and cottages. For more information about camping in New York State Parks, visit http://nysparks.com/camping/

## Columns

```ls
| Included | Schema Type | Field Name   | Name         | Data Type | Render Type |
| ======== | =========== | ============ | ============ | ========= | =========== |
| No       | time        | :updated_at  | updated_at   | meta_data | meta_data   |
| Yes      | series tag  | name         | Name         | text      | text        |
| Yes      | series tag  | category     | Category     | text      | text        |
| Yes      | series tag  | region       | Region       | text      | number      |
| Yes      | series tag  | county       | County       | text      | text        |
| Yes      | series tag  | facility_url | Facility URL | url       | url         |
| No       |             | x            | Longitude    | number    | number      |
| No       |             | y            | Latitude     | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = x,y
```

## Data Commands

```ls
series e:5zxz-z3ci d:2013-02-20T18:34:56.000Z t:region=2 t:category="State Park" t:facility_url=http://nysparks.com/parks/136/details.aspx t:county=Cattaraugus t:name=Allegany m:row_number.5zxz-z3ci=1

series e:5zxz-z3ci d:2013-02-20T18:34:56.000Z t:region=5 t:category="State Park" t:facility_url=http://nysparks.com/parks/76/details.aspx t:county=Chenango t:name="Bowman Lake" m:row_number.5zxz-z3ci=2

series e:5zxz-z3ci d:2013-02-20T18:34:56.000Z t:region=10 t:category="State Park" t:facility_url=http://nysparks.com/parks/57/details.aspx t:county=Jefferson t:name="Burnham Point" m:row_number.5zxz-z3ci=3
```

## Meta Commands

```ls
metric m:row_number.5zxz-z3ci p:long l:"Row Number"

entity e:5zxz-z3ci l:"Campgrounds by County Outside Adirondack & Catskill Forest Preserve" t:attribution="New York State Office of Parks, Recreation and Historic Preservation" t:url=https://data.ny.gov/api/views/5zxz-z3ci

property e:5zxz-z3ci t:meta.view v:id=5zxz-z3ci v:category=Recreation v:attributionLink=http://nysparks.com/camping/ v:averageRating=0 v:name="Campgrounds by County Outside Adirondack & Catskill Forest Preserve" v:attribution="New York State Office of Parks, Recreation and Historic Preservation"

property e:5zxz-z3ci t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:5zxz-z3ci t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:5zxz-z3ci t:meta.view.metadata.custom_fields.common_core v:Contact_Email=opendata@its.ny.gov v:Publisher="State of New York" v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| :updated_at | name               | category   | region | county       | facility_url                                       | x              | y             | 
| =========== | ================== | ========== | ====== | ============ | ================================================== | ============== | ============= | 
| 1361385296  | Allegany           | State Park | 2      | Cattaraugus  | [http://nysparks.com/parks/136/details.aspx, null] | -78.7685586473 | 42.0547575211 | 
| 1361385296  | Bowman Lake        | State Park | 5      | Chenango     | [http://nysparks.com/parks/76/details.aspx, null]  | -75.6806338029 | 42.519984738  | 
| 1361385296  | Burnham Point      | State Park | 10     | Jefferson    | [http://nysparks.com/parks/57/details.aspx, null]  | -76.2644442667 | 44.1625024865 | 
| 1361385296  | Buttermilk Falls   | State Park | 4      | Tompkins     | [http://nysparks.com/parks/151/details.aspx, null] | -76.5122566369 | 42.4040259595 | 
| 1361385296  | Canoe Picnic Point | State Park | 10     | Jefferson    | [http://nysparks.com/parks/64/details.aspx, null]  | -76.0747121606 | 44.304171386  | 
| 1361385296  | Cayuga Lake        | State Park | 4      | Seneca       | [http://nysparks.com/parks/123/details.aspx, null] | -76.7553118502 | 42.8979519073 | 
| 1361385296  | Cedar Island       | State Park | 10     | St. Lawrence | [http://nysparks.com/parks/25/details.aspx, null]  | -75.7905288637 | 44.449679332  | 
| 1361385296  | Cedar Point        | State Park | 10     | Jefferson    | [http://nysparks.com/parks/21/details.aspx, null]  | -76.19613394   | 44.2034891967 | 
| 1361385296  | Chenango Valley    | State Park | 5      | Broome       | [http://nysparks.com/parks/41/details.aspx, null]  | -75.8362368401 | 42.2155402507 | 
| 1361385296  | Cherry Plain       | State Park | 11     | Rensselaer   | [http://nysparks.com/parks/173/details.aspx, null] | -73.412215266  | 42.6178677896 | 
```