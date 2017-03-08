# State Nature Centers

## Dataset

* [Dataset URL](https://data.ny.gov/api/views/7gdv-fq7n/rows.json?max_rows=100)
* [Catalog URL](https://catalog.data.gov/dataset/state-nature-centers)
* [Metadata URL](https://data.ny.gov/api/views/7gdv-fq7n)
* Id = 7gdv-fq7n
* Name = State Nature Centers
* Attribution = New York State Office of Parks, Recreation and Historic Preservation
* [Attribution Link](http://nysparks.com/environment/nature-centers/default.aspx)
* Category = Recreation
* Tags = [parks, recreation, environment, nature centers]
* Created = 2013-02-15T17:37:06Z
* Publication Date = 2015-01-14T16:47:13Z
* Rows Updated = 2015-01-14T16:43:55Z

## Description

The New York State Office of Parks, Recreation and Historic Preservation (OPRHP) oversees more than 214 state parks and historic sites, encompassing nearly 335,000 acres, that are visited by 60 million people annually. These facilities contribute to the economic vitality and quality of life of local communities and directly support New York?s tourism industry. Parks also provide a place for families and children to be active and exercise, promoting healthy lifestyles. The agency is responsible for the operation and stewardship of the state park system as well as advancing a statewide parks, historic preservation, and open space mission.The New York State Office of Parks, Recreation and Historic Preservation operates several nature centers throughout the state. Visitors to our nature centers learn about the abundance of natural resources to be found in state parks. Our state parks and historic sites are hosts to scenic viewsheds, geologic features and both common and rare flora and fauna. For more information, visit http://nysparks.com/environment/nature-centers/default.aspx

## Columns

```ls
| Name                | Field Name          | Data Type | Render Type | Schema Type    | Included | 
| =================== | =================== | ========= | =========== | ============== | ======== | 
| updated_at          | :updated_at         | meta_data | meta_data   | time           | No       | 
| State Park Facility | state_park_facility | text      | text        | series tag     | Yes      | 
| Nature Center       | nature_center       | text      | text        | series tag     | Yes      | 
| Region              | region              | number    | number      | numeric metric | Yes      | 
| County              | county              | text      | text        | series tag     | Yes      | 
| Facility URL        | facility_url        | url       | url         | series tag     | Yes      | 
| Nature Center URL   | nature_center_url   | url       | url         | series tag     | Yes      | 
| Longitude           | x                   | number    | number      |                | No       | 
| Latitude            | y                   | number    | number      |                | No       | 
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Metric Prefix = 
Included Fields = *
Excluded Fields = y,x
Annotation Fields = 
```

## Data Commands

```ls
series e:7gdv-fq7n d:2013-02-20T18:49:41.000Z t:county=Cattaraugus t:nature_center="Red House Natural History Museum" t:state_park_facility="Allegany State Park" m:region=2

series e:7gdv-fq7n d:2013-02-20T18:49:41.000Z t:county=Erie t:nature_center="Beaver Island Nature Center" t:state_park_facility="Beaver Island State Park" m:region=1

series e:7gdv-fq7n d:2013-02-20T18:49:41.000Z t:county=Suffolk t:nature_center="Caleb Smith Park Preserve Nature Museum" t:state_park_facility="Caleb Smith Park Preserve" m:region=9
```

## Meta Commands

```ls
metric m:region p:integer l:Region d:"State Park Region" t:dataTypeName=number

entity e:7gdv-fq7n l:"State Nature Centers" t:attribution="New York State Office of Parks, Recreation and Historic Preservation" t:url=https://data.ny.gov/api/views/7gdv-fq7n

property e:7gdv-fq7n t:meta.view d:2017-03-08T00:19:02.975Z v:id=7gdv-fq7n v:category=Recreation v:attributionLink=http://nysparks.com/environment/nature-centers/default.aspx v:averageRating=0 v:name="State Nature Centers" v:attribution="New York State Office of Parks, Recreation and Historic Preservation"

property e:7gdv-fq7n t:meta.view.owner d:2017-03-08T00:19:02.975Z v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:7gdv-fq7n t:meta.view.tableauthor d:2017-03-08T00:19:02.975Z v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:7gdv-fq7n t:meta.view.metadata.custom_fields.common_core d:2017-03-08T00:19:02.975Z v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```