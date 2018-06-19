# Directory of Multi-Purpose Senior Centers

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/directory-of-multi-purpose-senior-centers) |
| Metadata | [Link](https://data.ny.gov/api/views/t4ba-giyx) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/t4ba-giyx/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/t4ba-giyx/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | t4ba-giyx |
| Name | Directory of Multi-Purpose Senior Centers |
| Attribution | New York State Office for the Aging |
| Category | Human Services |
| Tags | aging, aging resources, aging offices, congregate meals, health related programing, recreation |
| Created | 2013-12-23T19:15:23Z |
| Publication Date | 2016-11-03T22:01:57Z |

## Description

This dataset is listing of Multipurpose Senior Centers across the state which provide multiple services to New York?s senior citizens.  AAAs (Area Agencies on Aging - local offices for the Aging) provide services at senior center locations either directly or through subcontract. Services may include but are not limited to congregate meals, health promotion, educational programs, recreation, etc.

## Columns

```ls
| Included | Schema Type | Field Name         | Name               | Data Type | Render Type |
| ======== | =========== | ================== | ================== | ========= | =========== |
| No       | time        | :updated_at        | updated_at         | meta_data | meta_data   |
| Yes      | series tag  | nysofa_county_code | NYSOFA County Code | text      | text        |
| Yes      | series tag  | county_name        | County Name        | text      | text        |
| Yes      | series tag  | facility_name      | Facility Name      | text      | text        |
| Yes      | series tag  | street_address     | Street Address     | text      | text        |
| Yes      | series tag  | city               | City               | text      | text        |
| Yes      | series tag  | state              | State              | text      | text        |
| Yes      | series tag  | zip                | Zip                | text      | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:t4ba-giyx d:2016-11-03T22:01:03.000Z t:zip=12059 t:facility_name="East Berne Senior Center" t:nysofa_county_code=1 t:state=NY t:street_address="1656 Helderberg Trail" t:county_name=Albany t:city="East Berne" m:row_number.t4ba-giyx=1

series e:t4ba-giyx d:2016-11-03T22:01:03.000Z t:zip=12189 t:facility_name="Watervliet Senior Citizens Center" t:nysofa_county_code=1 t:state=NY t:street_address=Broadway t:county_name=Albany t:city=Watervliet m:row_number.t4ba-giyx=2

series e:t4ba-giyx d:2016-11-03T22:01:03.000Z t:zip=12047 t:facility_name="Cohoes Multi-Service Center" t:nysofa_county_code=1 t:state=NY t:street_address="10 Cayuga Plaza" t:county_name=Albany t:city=Cohoes m:row_number.t4ba-giyx=3
```

## Meta Commands

```ls
metric m:row_number.t4ba-giyx p:long l:"Row Number"

entity e:t4ba-giyx l:"Directory of Multi-Purpose Senior Centers" t:attribution="New York State Office for the Aging" t:url=https://data.ny.gov/api/views/t4ba-giyx

property e:t4ba-giyx t:meta.view v:id=t4ba-giyx v:category="Human Services" v:attributionLink=http://aging.ny.gov v:averageRating=0 v:name="Directory of Multi-Purpose Senior Centers" v:attribution="New York State Office for the Aging"

property e:t4ba-giyx t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:t4ba-giyx t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:t4ba-giyx t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| :updated_at | nysofa_county_code | county_name | facility_name                       | street_address                       | city         | state | zip   | 
| =========== | ================== | =========== | =================================== | ==================================== | ============ | ===== | ===== | 
| 1478210463  | 1                  | Albany      | East Berne Senior Center            | 1656 Helderberg Trail                | East Berne   | NY    | 12059 | 
| 1478210463  | 1                  | Albany      | Watervliet Senior Citizens Center   | Broadway                             | Watervliet   | NY    | 12189 | 
| 1478210463  | 1                  | Albany      | Cohoes Multi-Service Center         | 10 Cayuga Plaza                      | Cohoes       | NY    | 12047 | 
| 1478210463  | 1                  | Albany      | Guilderland Senior Services Town of | P.O. Box 339                         | Guilderland  | NY    | 12084 | 
| 1478210463  | 3                  | Broome      | Johnson City Senior Center          | 30 Brocton Avenue                    | Johnson City | NY    | 13790 | 
| 1478210463  | 5                  | Cayuga      | Moravia VFW                         | Grove Street Extension               | Moravia      | NY    | 13118 | 
| 1478210463  | 5                  | Cayuga      | Fair Haven American Legion          | 14521 Lake Street                    | Fair Haven   | NY    | 13064 | 
| 1478210463  | 6                  | Chautauqua  | North Harmony Senior Center         | 5377 Stow Ferry Rd                   | Ashville     | NY    | 14710 | 
| 1478210463  | 8                  | Chenango    | Westside Park Senior Center         | First Baptist Church West Park Place | Norwich      | NY    | 13815 | 
| 1478210463  | 8                  | Chenango    | Plum Valley Forever Young Center    | Methodist Church                     | So.Otselic   | NY    | 13155 | 
```