# IEPA Facilities Table

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/iepa-facilities-table-456d6) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/kimt-s6rh) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/kimt-s6rh/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/kimt-s6rh/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | kimt-s6rh |
| Name | IEPA Facilities Table |
| Attribution | IEPA |
| Created | 2011-12-15T18:17:44Z |
| Publication Date | 2014-10-09T21:50:33Z |

## Description

Data from December 2011

## Columns

```ls
| Included | Schema Type    | Field Name             | Name                   | Data Type | Render Type |
| ======== | ============== | ====================== | ====================== | ========= | =========== |
| No       | time           | :updated_at            | updated_at             | meta_data | meta_data   |
| Yes      | series tag     | facility               | Facility               | text      | text        |
| Yes      | series tag     | municipality           | Municipality           | text      | text        |
| Yes      | series tag     | county                 | County                 | text      | text        |
| Yes      | numeric metric | tons_in_2008           | Tons in 2008           | number    | number      |
| Yes      | series tag     | type_of_waste_accepted | Type of Waste Accepted | text      | text        |
| Yes      | series tag     | recycling_             | Recycling?             | text      | text        |
| Yes      | series tag     | c_d_                   | C&D?                   | text      | text        |
| Yes      | series tag     | lw_                    | LW?                    | text      | text        |
| Yes      | series tag     | owner                  | Owner                  | text      | text        |
| Yes      | series tag     | operator               | Operator               | text      | text        |
| Yes      | series tag     | truck_tip_fee          | Truck Tip Fee          | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:kimt-s6rh d:2011-12-15T10:18:49.000Z t:lw_=yes t:facility="C & L LSW Trans. Stn." t:county=Cook t:owner="C&L LLC" t:municipality="Chicago Heights" t:truck_tip_fee=NA t:type_of_waste_accepted=LW t:operator="Skyline Disposal" m:tons_in_2008=0

series e:kimt-s6rh d:2011-12-15T10:18:49.000Z t:lw_=yes t:facility="Harvey Transfer Station" t:county=Cook t:c_d_=yes t:owner=J&L t:municipality=Harvey t:truck_tip_fee=NA t:type_of_waste_accepted="C&D, LW" t:operator="Contractors Recycling Service" m:tons_in_2008=0

series e:kimt-s6rh d:2011-12-15T10:18:49.000Z t:lw_=yes t:facility=Homewood t:county=Cook t:owner="Star Investments" t:municipality="East Hazel Crest" t:truck_tip_fee=NA t:type_of_waste_accepted="MSW, LW" t:operator="Homewood Scavenger" m:tons_in_2008=0
```

## Meta Commands

```ls
metric m:tons_in_2008 p:integer l:"Tons in 2008" t:dataTypeName=number

entity e:kimt-s6rh l:"IEPA Facilities Table" t:attribution=IEPA t:url=https://datacatalog.cookcountyil.gov/api/views/kimt-s6rh

property e:kimt-s6rh t:meta.view v:id=kimt-s6rh v:averageRating=0 v:name="IEPA Facilities Table" v:attribution=IEPA

property e:kimt-s6rh t:meta.view.license v:name="Public Domain"

property e:kimt-s6rh t:meta.view.owner v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"

property e:kimt-s6rh t:meta.view.tableauthor v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"
```

## Top Records

```ls
| :updated_at | facility                                   | municipality     | county | tons_in_2008 | type_of_waste_accepted      | recycling_ | c_d_           | lw_  | owner                | operator                      | truck_tip_fee | 
| =========== | ========================================== | ================ | ====== | ============ | =========================== | ========== | ============== | ==== | ==================== | ============================= | ============= | 
| 1323944329  | C & L LSW Trans. Stn.                      | Chicago Heights  | Cook   | 0            | LW                          |            |                | yes  | C&L LLC              | Skyline Disposal              | NA            | 
| 1323944329  | Harvey Transfer Station                    | Harvey           | Cook   | 0            | C&D, LW                     |            | yes            | yes  | J&L                  | Contractors Recycling Service | NA            | 
| 1323944329  | Homewood                                   | East Hazel Crest | Cook   | 0            | MSW, LW                     |            |                | yes  | Star Investments     | Homewood Scavenger            | NA            | 
| 1323944329  | Prairie Lakes Recycling and Transfer 3     | Matteson         | Cook   | 0            | LW, C&D, recyclables        | yes        | yes            |      | Matteson Investments | Land and Lakes                | NA            | 
| 1323944330  | Greenwood Development                      | Maywood          | Cook   | 0            | LW                          |            |                | yes  | Greenwood            | Greenwood                     | NA            | 
| 1323944330  | Waste Management/Rockdale                  | Rockdale         | Will   | 53479        | MSW, LW, recyclables        | yes        |                | yes  | Waste Management     | Waste Management              | NA            | 
| 1323944330  | CID Transfer Station                       | Chicago          | Cook   | 40886        | MSW                         |            |                |      | Waste Management     | Waste Management              | NA            | 
| 1323944330  | ARC Disposal & Recycling                   | Mt. Prospect     | Cook   | 326227       | MSW, industrial, commercial | yes?       |                | LSW? | ARC                  | ARC                           | $51/ton       | 
| 1323944330  | Des Plaines Trans. Stn.                    | Des Plaines      | Cook   | 545          | LW, CCDD from muni          |            | CCDD from muni |      | City of Des Plaines  | City of Des Plaines           | NA            | 
| 1323944330  | Star Disposal Service LSW Transfer Station | Park Forest      | Cook   | 0            | LW                          |            |                | yes  | Star Investments     | Homewood Scavenger            | NA            | 
```