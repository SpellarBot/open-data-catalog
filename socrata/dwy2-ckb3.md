# Neighborhood and Rural Preservation Companies Directory

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/neighborhood-and-rural-preservation-companies-directory) |
| Metadata | [Link](https://data.ny.gov/api/views/dwy2-ckb3) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/dwy2-ckb3/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/dwy2-ckb3/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | dwy2-ckb3 |
| Name | Neighborhood and Rural Preservation Companies Directory |
| Attribution | New York State Homes and Community Renewal |
| Category | Economic Development |
| Tags | npc, rpc, community-based housing, community development |
| Created | 2014-08-13T17:41:26Z |
| Publication Date | 2015-10-15T14:46:58Z |

## Description

List of Neighborhood and Rural Preservation Program companies including the organization name and service area description.  New York State Homes and Community Renewal (HCR) provides financial support for these community-based housing organizations to perform housing and community renewal activities statewide. These organizations provide assistance including, but not limited to, housing rehabilitation, home buyer counseling, tenant counseling, landlord/tenant mediation, community rehabilitation and renewal, crime watch programs, employment programs, legal assistance, and Main Street Development.

## Columns

```ls
| Included | Schema Type | Field Name              | Name              | Data Type | Render Type |
| ======== | =========== | ======================= | ================= | ========= | =========== |
| No       | time        | :updated_at             | updated_at        | meta_data | meta_data   |
| Yes      | series tag  | organization_name       | Organization Name | text      | text        |
| Yes      | series tag  | area_served             | Area Served       | text      | text        |
| Yes      | series tag  | county                  | County            | text      | text        |
| Yes      | series tag  | street_address          | Street Address    | text      | text        |
| Yes      | series tag  | room_or_suite           | Room or Suite     | text      | text        |
| Yes      | series tag  | municipality            | Municipality      | text      | text        |
| Yes      | series tag  | state                   | State             | text      | text        |
| Yes      | series tag  | zip                     | Zip               | text      | text        |
| Yes      | series tag  | website                 | Program Type      | text      | text        |
| Yes      | series tag  | description_of_services | Web Site          | url       | url         |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:dwy2-ckb3 d:2015-10-15T07:42:40.000Z t:zip=11230 t:area_served=Midwood t:website=NPP t:county=Kings t:state=NY t:municipality=Brooklyn t:street_address="1416 Avenue M" t:organization_name="Midwood Development Corp" m:row_number.dwy2-ckb3=1

series e:dwy2-ckb3 d:2015-10-15T07:42:09.000Z t:zip=11722 t:area_served="Central Islip" t:website=NPP t:county=Suffolk t:state=NY t:municipality="Central Islip" t:street_address="P.O. Box 219" t:organization_name="Central Islip Civic Council Inc" m:row_number.dwy2-ckb3=2

series e:dwy2-ckb3 d:2015-10-15T07:42:09.000Z t:zip=14739 t:area_served="Towns of Belfast, Clarksville, Cuba, Friendship, New Hudson" t:website=RPP t:county=Allegany t:state=NY t:municipality=Friendship t:street_address="P.O. Box 194" t:organization_name="Cuba Community Development Corporation" m:row_number.dwy2-ckb3=3
```

## Meta Commands

```ls
metric m:row_number.dwy2-ckb3 p:long l:"Row Number"

entity e:dwy2-ckb3 l:"Neighborhood and Rural Preservation Companies Directory" t:attribution="New York State Homes and Community Renewal" t:url=https://data.ny.gov/api/views/dwy2-ckb3

property e:dwy2-ckb3 t:meta.view v:id=dwy2-ckb3 v:category="Economic Development" v:attributionLink=http://www.nyshcr.org/Programs/NPP/HousingOrgs.htm v:averageRating=0 v:name="Neighborhood and Rural Preservation Companies Directory" v:attribution="New York State Homes and Community Renewal"

property e:dwy2-ckb3 t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:dwy2-ckb3 t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:dwy2-ckb3 t:meta.view.metadata.custom_fields.common_core v:Contact_Email=opendata@its.ny.gov v:Publisher="State of New York" v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| :updated_at | organization_name                           | area_served                                                         | county     | street_address         | room_or_suite        | municipality  | state | zip   | website | description_of_services       | 
| =========== | =========================================== | =================================================================== | ========== | ====================== | ==================== | ============= | ===== | ===== | ======= | ============================= | 
| 1444894960  | Midwood Development Corp                    | Midwood                                                             | Kings      | 1416 Avenue M          |                      | Brooklyn      | NY    | 11230 | NPP     | [null, null]                  | 
| 1444894929  | Central Islip Civic Council Inc             | Central Islip                                                       | Suffolk    | P.O. Box 219           |                      | Central Islip | NY    | 11722 | NPP     | [null, null]                  | 
| 1444894929  | Cuba Community Development Corporation      | Towns of Belfast, Clarksville, Cuba, Friendship, New Hudson         | Allegany   | P.O. Box 194           |                      | Friendship    | NY    | 14739 | RPP     | [null, null]                  | 
| 1444894929  | HomeFront Development Corp                  | Washington County Excluding Towns Of Putnam, Dresden, And Whitehall | Washington | 568 Lower Allen Street |                      | Hudson Falls  | NY    | 12839 | RPP     | [null, null]                  | 
| 1444894929  | Mohawk Indian Housing Corp                  | St Regis Indian Res/Rooseveltown/Massena                            | Franklin   | P.O. Box 402           |                      | Rooseveltown  | NY    | 13683 | RPP     | [null, null]                  | 
| 1444894929  | Mount Hope Housing Co, Inc                  | Mount Hope                                                          | Bronx      | 2003-05 Walton Avenue  |                      | Bronx         | NY    | 10453 | NPP     | [null, null]                  | 
| 1444894929  | NCS Community Development Corp              | Northwest Rochester                                                 | Monroe     | 275 Driving Park       |                      | Rochester     | NY    | 14613 | NPP     | [http://www.ncscdc.org, null] | 
| 1444894929  | North Brooklyn Development Corp             | Greenpoint                                                          | Kings      | 148-150 Huron Street   |                      | Brooklyn      | NY    | 11222 | NPP     | [null, null]                  | 
| 1444894929  | Rensselaer County Housing Resources         | Rensselaer County, Excluding Troy                                   | Rensselaer | 415 River Steet        |                      | Troy          | NY    | 12180 | RPP     | [null, null]                  | 
| 1444894929  | Rockland Community Development Council, Inc | Villages In Rockland County                                         | Rockland   | Nyack Business Center  | 99 Main St, Room 215 | Nyack         | NY    | 10960 | RPP     | [null, null]                  | 
```