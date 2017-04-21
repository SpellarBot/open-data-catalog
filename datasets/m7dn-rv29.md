# Facilities

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/facilities) |
| Metadata | [Link](https://data.mo.gov/api/views/m7dn-rv29) |
| Data: JSON | [100 Rows](https://data.mo.gov/api/views/m7dn-rv29/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.mo.gov/api/views/m7dn-rv29/rows.csv?max_rows=100) |
| Host | data.mo.gov |
| Id | m7dn-rv29 |
| Name | Facilities |
| Attribution | Department of Natural Resources |
| Category | Natural Resources |
| Created | 2015-07-02T17:59:57Z |
| Publication Date | 2017-02-22T22:52:30Z |

## Description

Hazardous Waste Treatment, Storage and Disposal Facilities in Missouri

## Columns

```ls
| Included | Schema Type    | Field Name       | Name             | Data Type | Render Type |
| ======== | ============== | ================ | ================ | ========= | =========== |
| No       | time           | :updated_at      | updated_at       | meta_data | meta_data   |
| Yes      | series tag     | facility_name    | Facility_Name    | text      | text        |
| Yes      | series tag     | epa_id           | EPA_ID           | text      | text        |
| Yes      | numeric metric | tsduniverse      | TSDUniverse      | number    | number      |
| Yes      | numeric metric | rruniverse       | RRUniverse       | number    | number      |
| Yes      | series tag     | code_descq       | Code_Descq       | text      | text        |
| Yes      | series tag     | class            | CLASS            | text      | text        |
| Yes      | series tag     | class_short      | CLASS_Short      | text      | text        |
| Yes      | series tag     | process          | PROCESS          | text      | text        |
| Yes      | series tag     | facilitystatus   | FacilityStatus   | text      | text        |
| Yes      | numeric metric | morepdist1       | MOREPDIST1       | number    | number      |
| Yes      | numeric metric | mosenatedist1    | MOSENATEDIST1    | number    | number      |
| Yes      | numeric metric | usrep            | USREP            | number    | number      |
| Yes      | series tag     | countyname       | CountyName       | text      | text        |
| No       |                | facility_address | Facility_Address | text      | text        |
| Yes      | series tag     | region           | Region           | text      | text        |
| Yes      | series tag     | facility_city    | Facility_City    | text      | text        |
| Yes      | series tag     | facility_state   | Facility_State   | text      | text        |
| Yes      | series tag     | facility_zipcode | Facility_Zipcode | text      | number      |
| Yes      | series tag     | facility_phone   | Facility_Phone   | text      | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = facility_address
```

## Data Commands

```ls
series e:m7dn-rv29 d:2017-02-22T22:51:59.000Z t:facility_city=COLUMBIA t:region=NORTHEAST t:facility_zipcode=652029348 t:countyname=BOONE t:facility_name="3M CO COLUMBIA" t:epa_id=MOD054950670 t:facility_phone=5734748521 t:facilitystatus="INTERIM STATUS" t:facility_state=MO t:code_descq="TSD FACILITY" m:tsduniverse=1 m:morepdist1=44 m:usrep=4 m:rruniverse=0 m:mosenatedist1=19

series e:m7dn-rv29 d:2017-02-22T22:51:59.000Z t:facility_city=NEVADA t:process="DISTILLS SPENT SOLVENTS" t:region=SOUTHWEST t:facility_zipcode=647724211 t:countyname=VERNON t:facility_name="3M CO NEVADA" t:epa_id=MOD057894321 t:facility_phone=4176677851 t:facilitystatus="INTERIM STATUS" t:class="Recycles Hazardous Wastes Generated On-Site Only" t:facility_state=MO t:class_short=U t:code_descq="TSD AND RR FACILITY" m:tsduniverse=1 m:morepdist1=126 m:usrep=4 m:rruniverse=1 m:mosenatedist1=31

series e:m7dn-rv29 d:2017-02-22T22:51:59.000Z t:facility_city="FORT LEONARD WOOD" t:region=SOUTHEAST t:facility_zipcode=654738944 t:countyname=PULASKI t:facility_name="FORT LEONARD WOOD" t:epa_id=MO3213720979 t:facility_phone=5735960882 t:facilitystatus="INTERIM STATUS" t:facility_state=MO t:code_descq="TSD FACILITY" m:tsduniverse=1 m:morepdist1=122 m:usrep=4 m:rruniverse=0 m:mosenatedist1=16
```

## Meta Commands

```ls
metric m:tsduniverse p:integer l:TSDUniverse t:dataTypeName=number

metric m:rruniverse p:integer l:RRUniverse t:dataTypeName=number

metric m:morepdist1 p:integer l:MOREPDIST1 t:dataTypeName=number

metric m:mosenatedist1 p:integer l:MOSENATEDIST1 t:dataTypeName=number

metric m:usrep p:integer l:USREP t:dataTypeName=number

entity e:m7dn-rv29 l:Facilities t:attribution="Department of Natural Resources" t:url=https://data.mo.gov/api/views/m7dn-rv29

property e:m7dn-rv29 t:meta.view v:id=m7dn-rv29 v:category="Natural Resources" v:attributionLink=http://dnr.mo.gov v:averageRating=0 v:name=Facilities v:attribution="Department of Natural Resources"

property e:m7dn-rv29 t:meta.view.license v:name="Public Domain"

property e:m7dn-rv29 t:meta.view.owner v:id=wwxh-sgxy v:profileImageUrlMedium=/api/users/wwxh-sgxy/profile_images/THUMB v:profileImageUrlLarge=/api/users/wwxh-sgxy/profile_images/LARGE v:screenName="Renee Wright" v:profileImageUrlSmall=/api/users/wwxh-sgxy/profile_images/TINY v:displayName="Renee Wright"

property e:m7dn-rv29 t:meta.view.tableauthor v:id=wwxh-sgxy v:profileImageUrlMedium=/api/users/wwxh-sgxy/profile_images/THUMB v:profileImageUrlLarge=/api/users/wwxh-sgxy/profile_images/LARGE v:screenName="Renee Wright" v:profileImageUrlSmall=/api/users/wwxh-sgxy/profile_images/TINY v:roleName=editor v:displayName="Renee Wright"
```

## Top Records

```ls
| :updated_at | facility_name                        | epa_id       | tsduniverse | rruniverse | code_descq          | class                                            | class_short | process                 | facilitystatus | morepdist1 | mosenatedist1 | usrep | countyname    | facility_address               | region      | facility_city     | facility_state | facility_zipcode | facility_phone | 
| =========== | ==================================== | ============ | =========== | ========== | =================== | ================================================ | =========== | ======================= | ============== | ========== | ============= | ===== | ============= | ============================== | =========== | ================= | ============== | ================ | ============== | 
| 1487803919  | 3M CO COLUMBIA                       | MOD054950670 | 1           | 0          | TSD FACILITY        |                                                  |             |                         | INTERIM STATUS | 44         | 19            | 4     | BOONE         | 5400 RT B                      | NORTHEAST   | COLUMBIA          | MO             | 652029348        | 5734748521     | 
| 1487803919  | 3M CO NEVADA                         | MOD057894321 | 1           | 1          | TSD AND RR FACILITY | Recycles Hazardous Wastes Generated On-Site Only | U           | DISTILLS SPENT SOLVENTS | INTERIM STATUS | 126        | 31            | 4     | VERNON        | 2120 E AUSTIN                  | SOUTHWEST   | NEVADA            | MO             | 647724211        | 4176677851     | 
| 1487803919  | FORT LEONARD WOOD                    | MO3213720979 | 1           | 0          | TSD FACILITY        |                                                  |             |                         | INTERIM STATUS | 122        | 16            | 4     | PULASKI       | 1334 FIRST ST BLDG 2229        | SOUTHEAST   | FORT LEONARD WOOD | MO             | 654738944        | 5735960882     | 
| 1487803919  | BOEING (MD-ST. CHARLES)              | MOD075888487 | 1           | 0          | TSD FACILITY        |                                                  |             |                         | PERMITTED      | 65         | 23            | 3     | ST CHARLES    | 2600 N THIRD ST                | ST. LOUIS   | ST CHARLES        | MO             | 633010060        | 3142323319     | 
| 1487803919  | MISSOURI PRESSED METALS INC          | MOD073029936 | 1           | 0          | TSD FACILITY        |                                                  |             |                         | PERMITTED      | 52         | 28            | 4     | PETTIS        | 1200 E. BOONVILLE RD.          | KANSAS CITY | SEDALIA           | MO             | 653013322        | 6608273460     | 
| 1487803919  | MODINE HEAT TRANSFER INC - CAMDENTON | MOD062439351 | 1           | 0          | TSD FACILITY        |                                                  |             |                         | INTERIM STATUS | 123        | 16            | 3     | CAMDEN        | 179 SUNSET DR                  | SOUTHWEST   | CAMDENTON         | MO             | 650209691        | 5733465693     | 
| 1487803919  | MODINE - JOPLIN                      | MOD087775920 | 1           | 0          | TSD FACILITY        |                                                  |             |                         | INTERIM STATUS | 161        | 32            | 7     | JASPER        | 3300 W SEVENTH                 | SOUTHWEST   | JOPLIN            | MO             | 648013499        | 4177819500     | 
| 1487803919  | SIGMA/DEKALB STREET                  | MOD006273726 | 1           | 0          | TSD FACILITY        |                                                  |             |                         | OTHER          | 81         | 5             | 1     | ST LOUIS CITY | 3500 DEKALB ST                 | ST. LOUIS   | ST LOUIS CITY     | MO             | 631184103        | 3142867931     | 
| 1487803919  | SIGMA/SECOND STREET                  | MOD980962773 | 1           | 0          | TSD FACILITY        |                                                  |             |                         | OTHER          | 81         | 5             | 1     | ST LOUIS CITY | 3300 S SECOND ST               | ST. LOUIS   | ST LOUIS          | MO             | 631183306        | 3142867931     | 
| 1487803919  | UNIVERSITY OF MISSOURI - COLUMBIA    | MOD006326904 | 1           | 0          | TSD FACILITY        |                                                  |             |                         | PERMITTED      | 45         | 19            | 4     | BOONE         | UNIVERSITY OF MISSOURI COLUMBI | NORTHEAST   | COLUMBIA          | MO             | 65211            | 5738827018     | 
```