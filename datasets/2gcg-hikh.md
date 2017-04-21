# Boat Launch Sites by State Parks or Marine Facility

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/boat-launch-sites-by-state-parks-or-marine-facility) |
| Metadata | [Link](https://data.ny.gov/api/views/2gcg-hikh) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/2gcg-hikh/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/2gcg-hikh/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | 2gcg-hikh |
| Name | Boat Launch Sites by State Parks or Marine Facility |
| Attribution | New York State Office of Parks, Recreation and Historic Preservation |
| Category | Recreation |
| Tags | parks, recreation, boat launch sites |
| Created | 2013-02-15T18:06:49Z |
| Publication Date | 2015-01-14T17:23:23Z |

## Description

The New York State Office of Parks, Recreation and Historic Preservation (OPRHP) oversees more than 214 state parks and historic sites, encompassing nearly 335,000 acres, that are visited by 60 million people annually. These facilities contribute to the economic vitality and quality of life of local communities and directly support New York?s tourism industry. Parks also provide a place for families and children to be active and exercise, promoting healthy lifestyles. The agency is responsible for the operation and stewardship of the state park system as well as advancing a statewide parks, historic preservation, and open space mission.The New York State Office of Parks, Recreation, and Historic Preservation operates marinas and boat launching sites across the state. For more information about boating in New York State parks, visit http://nysparks.com/recreation/boating/

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
series e:2gcg-hikh d:2013-02-20T18:28:51.000Z t:region=4 t:category="Marine Facility" t:facility_url=http://nysparks.com/parks/35/details.aspx t:county=Tompkins t:name="Allan H. Treman" m:row_number.2gcg-hikh=1

series e:2gcg-hikh d:2013-02-20T18:28:51.000Z t:region=2 t:category="State Park" t:facility_url=http://nysparks.com/parks/136/details.aspx t:county=Cattaraugus t:name=Allegany m:row_number.2gcg-hikh=2

series e:2gcg-hikh d:2013-02-20T18:28:51.000Z t:region=1 t:category="State Park" t:facility_url=http://nysparks.com/parks/56/details.aspx t:county=Erie t:name="Beaver Island" m:row_number.2gcg-hikh=3
```

## Meta Commands

```ls
metric m:row_number.2gcg-hikh p:long l:"Row Number"

entity e:2gcg-hikh l:"Boat Launch Sites by State Parks or Marine Facility" t:attribution="New York State Office of Parks, Recreation and Historic Preservation" t:url=https://data.ny.gov/api/views/2gcg-hikh

property e:2gcg-hikh t:meta.view v:id=2gcg-hikh v:category=Recreation v:attributionLink=http://nysparks.com/recreation/boating/ v:averageRating=0 v:name="Boat Launch Sites by State Parks or Marine Facility" v:attribution="New York State Office of Parks, Recreation and Historic Preservation"

property e:2gcg-hikh t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:2gcg-hikh t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:2gcg-hikh t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| :updated_at | name                         | category        | region | county      | facility_url                                       | x              | y             | 
| =========== | ============================ | =============== | ====== | =========== | ================================================== | ============== | ============= | 
| 1361384931  | Allan H. Treman              | Marine Facility | 4      | Tompkins    | [http://nysparks.com/parks/35/details.aspx, null]  | -76.517568174  | 42.4613966817 | 
| 1361384931  | Allegany                     | State Park      | 2      | Cattaraugus | [http://nysparks.com/parks/136/details.aspx, null] | -78.7685586473 | 42.0547575211 | 
| 1361384931  | Beaver Island                | State Park      | 1      | Erie        | [http://nysparks.com/parks/56/details.aspx, null]  | -78.9531063633 | 42.9657659397 | 
| 1361384931  | Big Six Mile Creek Marina    | Marine Facility | 1      | Erie        | [http://nysparks.com/parks/50/details.aspx, null]  | -79.0109877003 | 43.0231951575 | 
| 1361384931  | Bowman Lake                  | State Park      | 5      | Chenango    | [http://nysparks.com/parks/76/details.aspx, null]  | -75.6806338029 | 42.519984738  | 
| 1361384931  | Burnham Point                | State Park      | 10     | Jefferson   | [http://nysparks.com/parks/57/details.aspx, null]  | -76.2644442667 | 44.1625024865 | 
| 1361384931  | Canandaigua Lake Marine Park | Marine Facility | 4      | Ontario     | [http://nysparks.com/parks/3/details.aspx, null]   | -77.275682797  | 42.8766685939 | 
| 1361384931  | Captree                      | State Park      | 9      | Suffolk     | [http://nysparks.com/parks/65/details.aspx, null]  | -73.2612735859 | 40.6388521833 | 
| 1361384931  | Cayuga Lake                  | State Park      | 4      | Seneca      | [http://nysparks.com/parks/123/details.aspx, null] | -76.7553118502 | 42.8979519073 | 
| 1361384931  | Cedar Point                  | State Park      | 10     | Jefferson   | [http://nysparks.com/parks/21/details.aspx, null]  | -76.19613394   | 44.2034891967 | 
```