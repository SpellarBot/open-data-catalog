# Golf Courses

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/golf-courses) |
| Metadata | [Link](https://data.ny.gov/api/views/cgck-srxx) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/cgck-srxx/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/cgck-srxx/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | cgck-srxx |
| Name | Golf Courses |
| Attribution | New York State Office of Parks, Recreation and Historic Preservation |
| Category | Recreation |
| Tags | parks, recreation, golf |
| Created | 2013-02-15T17:48:43Z |
| Publication Date | 2015-01-14T17:20:06Z |

## Description

The New York State Office of Parks, Recreation and Historic Preservation (OPRHP) oversees more than 214 state parks and historic sites, encompassing nearly 335,000 acres, that are visited by 60 million people annually. These facilities contribute to the economic vitality and quality of life of local communities and directly support New York?s tourism industry. Parks also provide a place for families and children to be active and exercise, promoting healthy lifestyles. The agency is responsible for the operation and stewardship of the state park system as well as advancing a statewide parks, historic preservation, and open space mission.From the famed Bethpage Black, to the rolling terrain of the Robert Trent Jones' designed 18-hole course at Green Lakes State Park, New York's state park golf courses rank among the best public courses in the world. For more information, visit http://nysparks.com/golf-courses/

## Columns

```ls
| Included | Schema Type | Field Name   | Name         | Data Type | Render Type |
| ======== | =========== | ============ | ============ | ========= | =========== |
| No       | time        | :updated_at  | updated_at   | meta_data | meta_data   |
| Yes      | series tag  | state_park   | State Park   | text      | text        |
| Yes      | series tag  | course_name  | Course Name  | text      | text        |
| Yes      | series tag  | region       | Region       | text      | number      |
| Yes      | series tag  | county       | County       | text      | text        |
| Yes      | series tag  | facility_url | Facility URL | url       | url         |
| Yes      | series tag  | golf_url     | Golf URL     | url       | url         |
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
series e:cgck-srxx d:2013-02-20T18:38:21.000Z t:golf_url=http://nysparks.com/golf-courses/13/details.aspx t:region=9 t:state_park="Alfred E. Smith/Sunken Meadow" t:facility_url=http://nysparks.com/parks/37/details.aspx t:county=Suffolk t:course_name=Blue m:row_number.cgck-srxx=1

series e:cgck-srxx d:2013-02-20T18:38:21.000Z t:golf_url=http://nysparks.com/golf-courses/13/details.aspx t:region=9 t:state_park="Alfred E. Smith/Sunken Meadow" t:facility_url=http://nysparks.com/parks/37/details.aspx t:county=Suffolk t:course_name=Green m:row_number.cgck-srxx=2

series e:cgck-srxx d:2013-02-20T18:38:21.000Z t:golf_url=http://nysparks.com/golf-courses/13/details.aspx t:region=9 t:state_park="Alfred E. Smith/Sunken Meadow" t:facility_url=http://nysparks.com/parks/37/details.aspx t:county=Suffolk t:course_name=Red m:row_number.cgck-srxx=3
```

## Meta Commands

```ls
metric m:row_number.cgck-srxx p:long l:"Row Number"

entity e:cgck-srxx l:"Golf Courses" t:attribution="New York State Office of Parks, Recreation and Historic Preservation" t:url=https://data.ny.gov/api/views/cgck-srxx

property e:cgck-srxx t:meta.view v:id=cgck-srxx v:category=Recreation v:attributionLink=http://nysparks.com/golf-courses/ v:averageRating=0 v:name="Golf Courses" v:attribution="New York State Office of Parks, Recreation and Historic Preservation"

property e:cgck-srxx t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:cgck-srxx t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:cgck-srxx t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| :updated_at | state_park                    | course_name | region | county  | facility_url                                       | golf_url                                                 | x              | y             | 
| =========== | ============================= | =========== | ====== | ======= | ================================================== | ======================================================== | ============== | ============= | 
| 1361385501  | Alfred E. Smith/Sunken Meadow | Blue        | 9      | Suffolk | [http://nysparks.com/parks/37/details.aspx, null]  | [http://nysparks.com/golf-courses/13/details.aspx, null] | -73.2632063245 | 40.9099922695 | 
| 1361385501  | Alfred E. Smith/Sunken Meadow | Green       | 9      | Suffolk | [http://nysparks.com/parks/37/details.aspx, null]  | [http://nysparks.com/golf-courses/13/details.aspx, null] | -73.2632063245 | 40.9099922695 | 
| 1361385501  | Alfred E. Smith/Sunken Meadow | Red         | 9      | Suffolk | [http://nysparks.com/parks/37/details.aspx, null]  | [http://nysparks.com/golf-courses/13/details.aspx, null] | -73.2632063245 | 40.9099922695 | 
| 1361385501  | Battle Island                 |             | 5      | Oswego  | [http://nysparks.com/parks/44/details.aspx, null]  | [http://nysparks.com/golf-courses/5/details.aspx, null]  | -76.4360441829 | 43.3616709338 | 
| 1361385501  | Beaver Island                 |             | 1      | Erie    | [http://nysparks.com/parks/56/details.aspx, null]  | [http://nysparks.com/golf-courses/4/details.aspx, null]  | -78.9531063633 | 42.9657659397 | 
| 1361385501  | Bethpage                      | Black       | 9      | Nassau  | [http://nysparks.com/parks/108/details.aspx, null] | [http://nysparks.com/golf-courses/11/details.aspx, null] | -73.4568035403 | 40.7475174105 | 
| 1361385501  | Bethpage                      | Blue        | 9      | Nassau  | [http://nysparks.com/parks/108/details.aspx, null] | [http://nysparks.com/golf-courses/11/details.aspx, null] | -73.4568035403 | 40.7475174105 | 
| 1361385501  | Bethpage                      | Green       | 9      | Nassau  | [http://nysparks.com/parks/108/details.aspx, null] | [http://nysparks.com/golf-courses/11/details.aspx, null] | -73.4568035403 | 40.7475174105 | 
| 1361385501  | Bethpage                      | Red         | 9      | Nassau  | [http://nysparks.com/parks/108/details.aspx, null] | [http://nysparks.com/golf-courses/11/details.aspx, null] | -73.4568035403 | 40.7475174105 | 
| 1361385501  | Bethpage                      | Yellow      | 9      | Nassau  | [http://nysparks.com/parks/108/details.aspx, null] | [http://nysparks.com/golf-courses/11/details.aspx, null] | -73.4568035403 | 40.7475174105 | 
```