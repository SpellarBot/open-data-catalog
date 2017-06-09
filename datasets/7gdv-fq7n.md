# State Nature Centers

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/state-nature-centers) |
| Metadata | [Link](https://data.ny.gov/api/views/7gdv-fq7n) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/7gdv-fq7n/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/7gdv-fq7n/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | 7gdv-fq7n |
| Name | State Nature Centers |
| Attribution | New York State Office of Parks, Recreation and Historic Preservation |
| Category | Recreation |
| Tags | parks, recreation, environment, nature centers |
| Created | 2013-02-15T17:37:06Z |
| Publication Date | 2015-01-14T16:47:13Z |

## Description

The New York State Office of Parks, Recreation and Historic Preservation (OPRHP) oversees more than 214 state parks and historic sites, encompassing nearly 335,000 acres, that are visited by 60 million people annually. These facilities contribute to the economic vitality and quality of life of local communities and directly support New York’s tourism industry. Parks also provide a place for families and children to be active and exercise, promoting healthy lifestyles. The agency is responsible for the operation and stewardship of the state park system as well as advancing a statewide parks, historic preservation, and open space mission.The New York State Office of Parks, Recreation and Historic Preservation operates several nature centers throughout the state. Visitors to our nature centers learn about the abundance of natural resources to be found in state parks. Our state parks and historic sites are hosts to scenic viewsheds, geologic features and both common and rare flora and fauna. For more information, visit http://nysparks.com/environment/nature-centers/default.aspx

## Columns

```ls
| Included | Schema Type | Field Name          | Name                | Data Type | Render Type |
| ======== | =========== | =================== | =================== | ========= | =========== |
| No       | time        | :updated_at         | updated_at          | meta_data | meta_data   |
| Yes      | series tag  | state_park_facility | State Park Facility | text      | text        |
| Yes      | series tag  | nature_center       | Nature Center       | text      | text        |
| Yes      | series tag  | region              | Region              | text      | number      |
| Yes      | series tag  | county              | County              | text      | text        |
| Yes      | series tag  | facility_url        | Facility URL        | url       | url         |
| Yes      | series tag  | nature_center_url   | Nature Center URL   | url       | url         |
| No       |             | x                   | Longitude           | number    | number      |
| No       |             | y                   | Latitude            | number    | number      |
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
series e:7gdv-fq7n d:2013-02-20T18:49:41.000Z t:region=2 t:facility_url=http://nysparks.com/parks/136/details.aspx t:county=Cattaraugus t:nature_center="Red House Natural History Museum" t:state_park_facility="Allegany State Park" t:nature_center_url=http://www.nysparks.com/environment/nature-centers/12/details.aspx m:row_number.7gdv-fq7n=1

series e:7gdv-fq7n d:2013-02-20T18:49:41.000Z t:region=1 t:facility_url=http://nysparks.com/parks/56/details.aspx t:county=Erie t:nature_center="Beaver Island Nature Center" t:state_park_facility="Beaver Island State Park" t:nature_center_url=http://www.nysparks.com/environment/nature-centers/11/details.aspx m:row_number.7gdv-fq7n=2

series e:7gdv-fq7n d:2013-02-20T18:49:41.000Z t:region=9 t:facility_url=http://nysparks.com/parks/124/details.aspx t:county=Suffolk t:nature_center="Caleb Smith Park Preserve Nature Museum" t:state_park_facility="Caleb Smith Park Preserve" t:nature_center_url=http://www.nysparks.com/environment/nature-centers/9/details.aspx m:row_number.7gdv-fq7n=3
```

## Meta Commands

```ls
metric m:row_number.7gdv-fq7n p:long l:"Row Number"

entity e:7gdv-fq7n l:"State Nature Centers" t:attribution="New York State Office of Parks, Recreation and Historic Preservation" t:url=https://data.ny.gov/api/views/7gdv-fq7n

property e:7gdv-fq7n t:meta.view d:2017-06-09T13:53:36.715Z v:id=7gdv-fq7n v:category=Recreation v:attributionLink=http://nysparks.com/environment/nature-centers/default.aspx v:averageRating=0 v:name="State Nature Centers" v:attribution="New York State Office of Parks, Recreation and Historic Preservation"

property e:7gdv-fq7n t:meta.view.owner d:2017-06-09T13:53:36.715Z v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:7gdv-fq7n t:meta.view.tableauthor d:2017-06-09T13:53:36.715Z v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:7gdv-fq7n t:meta.view.metadata.custom_fields.common_core d:2017-06-09T13:53:36.715Z v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| :updated_at | state_park_facility                  | nature_center                                  | region | county       | facility_url                                       | nature_center_url                                                          | x              | y             | 
| =========== | ==================================== | ============================================== | ====== | ============ | ================================================== | ========================================================================== | ============== | ============= | 
| 1361386181  | Allegany State Park                  | Red House Natural History Museum               | 2      | Cattaraugus  | [http://nysparks.com/parks/136/details.aspx, null] | [http://www.nysparks.com/environment/nature-centers/12/details.aspx, null] | -78.7685586473 | 42.0547575211 | 
| 1361386181  | Beaver Island State Park             | Beaver Island Nature Center                    | 1      | Erie         | [http://nysparks.com/parks/56/details.aspx, null]  | [http://www.nysparks.com/environment/nature-centers/11/details.aspx, null] | -78.9531063633 | 42.9657659397 | 
| 1361386181  | Caleb Smith Park Preserve            | Caleb Smith Park Preserve Nature Museum        | 9      | Suffolk      | [http://nysparks.com/parks/124/details.aspx, null] | [http://www.nysparks.com/environment/nature-centers/9/details.aspx, null]  | -73.2260164473 | 40.8530379808 | 
| 1361386181  | Clarence Fahnestock State Park       | Taconic Outdoor Education Center               | 7      | Putnam       | [http://nysparks.com/parks/133/details.aspx, null] | [http://www.nysparks.com/environment/nature-centers/3/details.aspx, null]  | -73.8476473928 | 41.4527563307 | 
| 1361386181  | Clay Pit Ponds State Park Preserve   | Clay Pit Ponds Park Preserve Nature Museum     | 12     | Richmond     | [http://nysparks.com/parks/166/details.aspx, null] | [http://www.nysparks.com/environment/nature-centers/14/details.aspx, null] | -74.2290460884 | 40.5405635456 | 
| 1361386181  | Connetquot River State Park Preserve | Long Island Environmental Interpretrive Center | 9      | Suffolk      | [http://nysparks.com/parks/8/details.aspx, null]   | [http://www.nysparks.com/environment/nature-centers/6/details.aspx, null]  | -73.1492496889 | 40.7694292476 | 
| 1361386181  | John Boyd Thacher State Park         | Emma Treadwell Thacher Nature Center           | 11     | Albany       | [http://nysparks.com/parks/128/details.aspx, null] | [http://www.nysparks.com/environment/nature-centers/8/details.aspx, null]  | -74.0147061578 | 42.655465525  | 
| 1361386181  | Jones Beach State Park               | Theodore Roosevelt Nature Center               | 9      | Nassau       | [http://nysparks.com/parks/10/details.aspx, null]  | [http://www.nysparks.com/environment/nature-centers/4/details.aspx, null]  | -73.5164273182 | 40.596010848  | 
| 1361386181  | Moreau Lake State Park               | Moreau Lake Nature Center                      | 11     | Saratoga     | [http://nysparks.com/parks/150/details.aspx, null] | [http://www.nysparks.com/environment/nature-centers/7/details.aspx, null]  | -73.7337768981 | 43.2332136686 | 
| 1361386181  | Robert Moses State Park              | Robert Moses State Park Nature Center          | 10     | St. Lawrence | [http://nysparks.com/parks/51/details.aspx, null]  | [http://www.nysparks.com/environment/nature-centers/5/details.aspx, null]  | -74.8273503481 | 45.0006401225 | 
```