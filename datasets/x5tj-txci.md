# DPW Maintained Roadway Structures

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dpw-maintained-roadway-structures-9e89c) |
| Metadata | [Link](https://data.sfgov.org/api/views/x5tj-txci) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/x5tj-txci/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/x5tj-txci/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | x5tj-txci |
| Name | DPW Maintained Roadway Structures |
| Attribution | San Francisco Department of Public Works |
| Category | City Infrastructure |
| Tags | stairs, stairway, retaining, wall, street, roadway, structure, information, system, rsis |
| Created | 2013-10-08T23:57:17Z |
| Publication Date | 2016-08-10T22:49:55Z |

## Description

Structures in the public right of way maintained by DPW. Source: DPW'S RSIS system.

## Columns

```ls
| Included | Schema Type | Field Name   | Name         | Data Type | Render Type |
| ======== | =========== | ============ | ============ | ========= | =========== |
| No       | time        | :updated_at  | updated_at   | meta_data | meta_data   |
| Yes      | series tag  | facilitytype | FacilityType | text      | text        |
| Yes      | series tag  | assetid      | AssetID      | text      | text        |
| Yes      | series tag  | assetdesc    | AssetDesc    | text      | text        |
| Yes      | series tag  | assettype    | AssetType    | text      | text        |
| Yes      | series tag  | onstreet     | OnStreet     | text      | text        |
| Yes      | series tag  | fromstreet   | FromStreet   | text      | text        |
| Yes      | series tag  | tostreet     | ToStreet     | text      | text        |
| No       |             | latitude     | Latitude     | number    | number      |
| No       |             | longitude    | Longitude    | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = latitude,longitude
```

## Data Commands

```ls
series e:x5tj-txci d:2016-12-07T06:43:25.000Z t:onstreet="MONTEREY BLVD. ON-RAMP" t:assetdesc="MONTEREY BLVD. ON-RAMP" t:fromstreet="CIRCULAR AVE." t:facilitytype="Roadway Structures" t:tostreet=US280 t:assettype="Vehicular Bridges" t:assetid=304 m:row_number.x5tj-txci=1

series e:x5tj-txci d:2016-12-07T06:43:25.000Z t:onstreet="VERMONT ST." t:assetdesc="VERMONT ST WALL" t:fromstreet="20th ST." t:facilitytype="Roadway Structures" t:tostreet="22ND ST." t:assettype="Retaining Wall & Stair" t:assetid=136 m:row_number.x5tj-txci=2

series e:x5tj-txci d:2016-12-07T06:43:25.000Z t:onstreet="CLAYTON ST." t:assetdesc="CLAYTON ST STAIRS" t:fromstreet="CORBETT ST." t:facilitytype="Roadway Structures" t:assettype=Stair t:assetid=116 m:row_number.x5tj-txci=3
```

## Meta Commands

```ls
metric m:row_number.x5tj-txci p:long l:"Row Number"

entity e:x5tj-txci l:"DPW Maintained Roadway Structures" t:attribution="San Francisco Department of Public Works" t:url=https://data.sfgov.org/api/views/x5tj-txci

property e:x5tj-txci t:meta.view v:id=x5tj-txci v:category="City Infrastructure" v:averageRating=0 v:name="DPW Maintained Roadway Structures" v:attribution="San Francisco Department of Public Works"

property e:x5tj-txci t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:x5tj-txci t:meta.view.owner v:id=rcpp-nrjq v:profileImageUrlMedium=/api/users/rcpp-nrjq/profile_images/THUMB v:profileImageUrlLarge=/api/users/rcpp-nrjq/profile_images/LARGE v:screenName="Public Works" v:profileImageUrlSmall=/api/users/rcpp-nrjq/profile_images/TINY v:displayName="Public Works"

property e:x5tj-txci t:meta.view.tableauthor v:id=rcpp-nrjq v:profileImageUrlMedium=/api/users/rcpp-nrjq/profile_images/THUMB v:profileImageUrlLarge=/api/users/rcpp-nrjq/profile_images/LARGE v:screenName="Public Works" v:profileImageUrlSmall=/api/users/rcpp-nrjq/profile_images/TINY v:roleName=editor v:displayName="Public Works"
```

## Top Records

```ls
| :updated_at | facilitytype       | assetid | assetdesc                            | assettype              | onstreet               | fromstreet       | tostreet    | latitude        | longitude         | 
| =========== | ================== | ======= | ==================================== | ====================== | ====================== | ================ | =========== | =============== | ================= | 
| 1481093005  | Roadway Structures | 304     | MONTEREY BLVD. ON-RAMP               | Vehicular Bridges      | MONTEREY BLVD. ON-RAMP | CIRCULAR AVE.    | US280       | 37.731240910036 | -122.435618340969 | 
| 1481093005  | Roadway Structures | 136     | VERMONT ST WALL                      | Retaining Wall & Stair | VERMONT ST.            | 20th ST.         | 22ND ST.    | 37.758275       | -122.404053       | 
| 1481093005  | Roadway Structures | 116     | CLAYTON ST STAIRS                    | Stair                  | CLAYTON ST.            | CORBETT ST.      |             | 37.758915       | -122.446245       | 
| 1481093005  | Roadway Structures | 52      | HIGHLAND AVE BRIDGE                  | Vehicular Bridges      | HIGHLAND AVE.          | ARLINGTON        | MISSION     | 37.737587       | -122.425185       | 
| 1481093005  | Roadway Structures | 148     | ARMY ST PIPE RAILING                 | Guardrail              | ARMY ST.               | EVANS            | MISSISSIPPI | 37.749706       | -122.395282       | 
| 1481093005  | Roadway Structures | 213     | KENNY ALY STAIRWAY                   | Stair                  | KENNY ALLEY            | LONDON ST.       | MISSION ST. | 37.719063       | -122.438344       | 
| 1481093005  | Roadway Structures | 518     | CESAR CHAVEZ ST AND BAYSHORE FREEWAY | Guardrail              | Twin Peaks Blvd        |                  |             | 37.753776634409 | -122.447749972343 | 
| 1481093005  | Roadway Structures | 502     | 18TH STREET AT HWY280 GUARDRAIL      | Guardrail              | 18TH ST                | PENNSYLVANIA AVE | INDIANA ST  | 37.762802785675 | -122.392815649509 | 
| 1481093005  | Roadway Structures | 98      | AZTEC ST WALL AND STAIRS             | Retaining Wall & Stair | AZTEC ST.              | SHOTWELL ST.     |             | 37.745539       | -122.415177       | 
| 1481093005  | Roadway Structures | 91A-7   | 14TH AVE WALL AND STAIRS             | Retaining Wall & Stair | 14th AVE.              | ALOHA ST.        | NORIEGA ST. | 37.756693       | -122.470992       | 
```