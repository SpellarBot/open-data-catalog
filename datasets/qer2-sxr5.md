# BSS Pavement Preservation Annual Data

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/bss-pavement-preservation-annual-data-e229d) |
| Metadata | [Link](https://data.lacity.org/api/views/qer2-sxr5) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/qer2-sxr5/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/qer2-sxr5/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | qer2-sxr5 |
| Name | BSS Pavement Preservation Annual Data |
| Created | 2014-05-30T21:24:30Z |
| Publication Date | 2014-05-30T21:27:48Z |

## Description

Annual Data FY 10 to FY 13 for street resurfacing, resealing, small asphalt repairs (potholes), slurry seal

## Columns

```ls
| Included | Schema Type    | Field Name                  | Name                        | Data Type     | Render Type   |
| ======== | ============== | =========================== | =========================== | ============= | ============= |
| Yes      | time           | date                        | Date                        | calendar_date | calendar_date |
| No       |                | date_name                   | Date Name                   | text          | text          |
| Yes      | numeric metric | resurfacing                 | Resurfacing                 | number        | number        |
| Yes      | numeric metric | reconstruction              | Reconstruction              | number        | number        |
| Yes      | numeric metric | pavement_preservation_total | Pavement Preservation Total | number        | number        |
| Yes      | numeric metric | slurry_seal                 | Slurry Seal                 | number        | number        |
| Yes      | numeric metric | total_centerline_miles      | Total Centerline Miles      | number        | number        |
| Yes      | numeric metric | small_asphalt_repairs       | Small Asphalt Repairs       | number        | number        |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = date_name
```

## Data Commands

```ls
series e:qer2-sxr5 d:2010-06-30T00:00:00.000Z m:slurry_seal=401 m:resurfacing=137 m:pavement_preservation_total=149 m:reconstruction=12 m:total_centerline_miles=550 m:small_asphalt_repairs=362205

series e:qer2-sxr5 d:2011-06-30T00:00:00.000Z m:slurry_seal=401 m:resurfacing=158 m:pavement_preservation_total=174.45 m:reconstruction=17 m:total_centerline_miles=575 m:small_asphalt_repairs=297561

series e:qer2-sxr5 d:2012-06-30T00:00:00.000Z m:slurry_seal=401 m:resurfacing=223 m:pavement_preservation_total=236.01 m:reconstruction=13 m:total_centerline_miles=637 m:small_asphalt_repairs=301653
```

## Meta Commands

```ls
metric m:resurfacing p:float l:Resurfacing d:"centerline mile" t:dataTypeName=number

metric m:reconstruction p:integer l:Reconstruction d:"centerline mile" t:dataTypeName=number

metric m:pavement_preservation_total p:float l:"Pavement Preservation Total" d:"centerline mile" t:dataTypeName=number

metric m:slurry_seal p:integer l:"Slurry Seal" t:dataTypeName=number

metric m:total_centerline_miles p:integer l:"Total Centerline Miles" t:dataTypeName=number

metric m:small_asphalt_repairs p:integer l:"Small Asphalt Repairs" t:dataTypeName=number

entity e:qer2-sxr5 l:"BSS Pavement Preservation Annual Data" t:url=https://data.lacity.org/api/views/qer2-sxr5

property e:qer2-sxr5 t:meta.view v:id=qer2-sxr5 v:averageRating=0 v:name="BSS Pavement Preservation Annual Data"

property e:qer2-sxr5 t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:qer2-sxr5 t:meta.view.owner v:id=df4s-jhab v:profileImageUrlMedium=/api/users/df4s-jhab/profile_images/THUMB v:profileImageUrlLarge=/api/users/df4s-jhab/profile_images/LARGE v:screenName="Public Works: Street Services OpenData" v:profileImageUrlSmall=/api/users/df4s-jhab/profile_images/TINY v:displayName="Public Works: Street Services OpenData"

property e:qer2-sxr5 t:meta.view.tableauthor v:id=df4s-jhab v:profileImageUrlMedium=/api/users/df4s-jhab/profile_images/THUMB v:profileImageUrlLarge=/api/users/df4s-jhab/profile_images/LARGE v:screenName="Public Works: Street Services OpenData" v:profileImageUrlSmall=/api/users/df4s-jhab/profile_images/TINY v:roleName=publisher v:displayName="Public Works: Street Services OpenData"
```

## Top Records

```ls
| date                | date_name | resurfacing | reconstruction | pavement_preservation_total | slurry_seal | total_centerline_miles | small_asphalt_repairs | 
| =================== | ========= | =========== | ============== | =========================== | =========== | ====================== | ===================== | 
| 2010-06-30T00:00:00 | FY 2010   | 137         | 12             | 149                         | 401         | 550                    | 362205                | 
| 2011-06-30T00:00:00 | FY 2011   | 158         | 17             | 174.45                      | 401         | 575                    | 297561                | 
| 2012-06-30T00:00:00 | FY 2012   | 223         | 13             | 236.01                      | 401         | 637                    | 301653                | 
| 2013-06-30T00:00:00 | FY 2013   | 235.49      | 10             | 245.64                      | 455         | 701                    | 354125                | 
```