# Supplemental Nutrition Assistance Program (SNAP) Caseloads and Expenditures: Beginning 2002

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/supplemental-nutrition-assistance-program-snap-caseloads-and-expenditures-beginning-2002) |
| Metadata | [Link](https://data.ny.gov/api/views/dq6j-8u8z) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/dq6j-8u8z/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/dq6j-8u8z/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | dq6j-8u8z |
| Name | Supplemental Nutrition Assistance Program (SNAP) Caseloads and Expenditures: Beginning 2002 |
| Attribution | New York State Office of Temporary and Disability Assistance |
| Category | Human Services |
| Tags | welfare, food stamps, supplemental nutrition assistance program, public assistance |
| Created | 2013-02-28T21:56:42Z |
| Publication Date | 2017-03-31T22:04:11Z |

## Description

These data are monthly listings of households, recipients and expenditures for the Supplemental Nutrition Assistance Program.

## Columns

```ls
| Included | Schema Type    | Field Name                               | Name                                     | Data Type | Render Type |
| ======== | ============== | ======================================== | ======================================== | ========= | =========== |
| No       |                | year                                     | Year                                     | number    | number      |
| No       |                | month                                    | Month                                    | text      | text        |
| Yes      | series tag     | month_code                               | Month Code                               | text      | number      |
| Yes      | series tag     | district_code                            | District Code                            | text      | text        |
| Yes      | series tag     | district                                 | District                                 | text      | text        |
| Yes      | numeric metric | total_snap_households                    | Total SNAP Households                    | number    | number      |
| Yes      | numeric metric | total_snap_persons                       | Total SNAP Persons                       | number    | number      |
| Yes      | numeric metric | total_snap_benefits                      | Total SNAP Benefits                      | money     | money       |
| Yes      | numeric metric | temporary_assistance_snap_households     | Temporary Assistance SNAP Households     | number    | number      |
| Yes      | numeric metric | temporary_assistance_snap_persons        | Temporary Assistance SNAP Persons        | number    | number      |
| Yes      | numeric metric | temporary_assistance_snap_benefits       | Temporary Assistance SNAP Benefits       | money     | money       |
| Yes      | numeric metric | non_temporary_assistance_snap_households | Non-Temporary Assistance SNAP Households | number    | number      |
| Yes      | numeric metric | non_temporary_assistance_snap_persons    | Non-Temporary Assistance SNAP Persons    | number    | number      |
| Yes      | numeric metric | non_temporary_assistance_snap_benefits   | Non-Temporary Assistance SNAP Benefits   | money     | money       |
```

## Time Field

```ls
Value = year-month
Format & Zone = yyyy-MMMM
```

## Series Fields

```ls
Excluded Fields = year,month
```

## Data Commands

```ls
series e:dq6j-8u8z d:2002-01-01T00:00:00.000Z t:district_code=1 t:month_code=1 t:district=Albany m:temporary_assistance_snap_households=4885 m:total_snap_households=8598 m:temporary_assistance_snap_persons=8301 m:non_temporary_assistance_snap_households=3713 m:total_snap_benefits=1451349 m:total_snap_persons=17533 m:non_temporary_assistance_snap_benefits=668657 m:non_temporary_assistance_snap_persons=9232 m:temporary_assistance_snap_benefits=782692

series e:dq6j-8u8z d:2002-01-01T00:00:00.000Z t:district_code=2 t:month_code=1 t:district=Allegany m:temporary_assistance_snap_households=842 m:total_snap_households=1812 m:temporary_assistance_snap_persons=1330 m:non_temporary_assistance_snap_households=970 m:total_snap_benefits=277998 m:total_snap_persons=3783 m:non_temporary_assistance_snap_benefits=169513 m:non_temporary_assistance_snap_persons=2453 m:temporary_assistance_snap_benefits=108485

series e:dq6j-8u8z d:2002-01-01T00:00:00.000Z t:district_code=3 t:month_code=1 t:district=Broome m:temporary_assistance_snap_households=3010 m:total_snap_households=6000 m:temporary_assistance_snap_persons=4694 m:non_temporary_assistance_snap_households=2990 m:total_snap_benefits=938534 m:total_snap_persons=11905 m:non_temporary_assistance_snap_benefits=517807 m:non_temporary_assistance_snap_persons=7211 m:temporary_assistance_snap_benefits=420727
```

## Meta Commands

```ls
metric m:total_snap_households p:integer l:"Total SNAP Households" d:"Table 16 Supplemental Nutrition Assistance Program Total Households." t:dataTypeName=number

metric m:total_snap_persons p:integer l:"Total SNAP Persons" d:"Table 16 Supplemental Nutrition Assistance Program Total Persons." t:dataTypeName=number

metric m:total_snap_benefits p:integer l:"Total SNAP Benefits" d:"Table 16 Supplemental Nutrition Assistance Program Total Benefits." t:dataTypeName=money

metric m:temporary_assistance_snap_households p:integer l:"Temporary Assistance SNAP Households" d:"Table 16 Supplemental Nutrition Assistance Program, Temporary Assistance Households." t:dataTypeName=number

metric m:temporary_assistance_snap_persons p:integer l:"Temporary Assistance SNAP Persons" d:"Table 16 Supplemental Nutrition Assistance Program, Temporary Assistance Persons." t:dataTypeName=number

metric m:temporary_assistance_snap_benefits p:integer l:"Temporary Assistance SNAP Benefits" d:"Table 16 Supplemental Nutrition Assistance Program, Temporary Assistance Benefits." t:dataTypeName=money

metric m:non_temporary_assistance_snap_households p:integer l:"Non-Temporary Assistance SNAP Households" d:"Table 16 Supplemental Nutrition Assistance Program, Non?Temporary Assistance Households." t:dataTypeName=number

metric m:non_temporary_assistance_snap_persons p:integer l:"Non-Temporary Assistance SNAP Persons" d:"Table 16 Supplemental Nutrition Assistance Program, Non-Temporary Assistance Persons." t:dataTypeName=number

metric m:non_temporary_assistance_snap_benefits p:integer l:"Non-Temporary Assistance SNAP Benefits" d:"Table 16 Supplemental Nutrition Assistance Program, Non-Temporary Assistance Benefits." t:dataTypeName=money

entity e:dq6j-8u8z l:"Supplemental Nutrition Assistance Program (SNAP) Caseloads and Expenditures: Beginning 2002" t:attribution="New York State Office of Temporary and Disability Assistance" t:url=https://data.ny.gov/api/views/dq6j-8u8z

property e:dq6j-8u8z t:meta.view v:id=dq6j-8u8z v:category="Human Services" v:attributionLink=http://otda.ny.gov/resources/caseload/ v:averageRating=0 v:name="Supplemental Nutrition Assistance Program (SNAP) Caseloads and Expenditures: Beginning 2002" v:attribution="New York State Office of Temporary and Disability Assistance"

property e:dq6j-8u8z t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:dq6j-8u8z t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:dq6j-8u8z t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| year | month   | month_code | district_code | district    | total_snap_households | total_snap_persons | total_snap_benefits | temporary_assistance_snap_households | temporary_assistance_snap_persons | temporary_assistance_snap_benefits | non_temporary_assistance_snap_households | non_temporary_assistance_snap_persons | non_temporary_assistance_snap_benefits | 
| ==== | ======= | ========== | ============= | =========== | ===================== | ================== | =================== | ==================================== | ================================= | ================================== | ======================================== | ===================================== | ====================================== | 
| 2002 | January | 1          | 1             | Albany      | 8598                  | 17533              | 1451349             | 4885                                 | 8301                              | 782692                             | 3713                                     | 9232                                  | 668657                                 | 
| 2002 | January | 1          | 2             | Allegany    | 1812                  | 3783               | 277998              | 842                                  | 1330                              | 108485                             | 970                                      | 2453                                  | 169513                                 | 
| 2002 | January | 1          | 3             | Broome      | 6000                  | 11905              | 938534              | 3010                                 | 4694                              | 420727                             | 2990                                     | 7211                                  | 517807                                 | 
| 2002 | January | 1          | 4             | Cattaraugus | 3041                  | 6164               | 432312              | 1225                                 | 1713                              | 140490                             | 1816                                     | 4451                                  | 291822                                 | 
| 2002 | January | 1          | 5             | Cayuga      | 2159                  | 4830               | 376009              | 754                                  | 1068                              | 90769                              | 1405                                     | 3762                                  | 285240                                 | 
| 2002 | January | 1          | 6             | Chautauqua  | 5523                  | 11755              | 964526              | 2892                                 | 4867                              | 464529                             | 2631                                     | 6888                                  | 499997                                 | 
| 2002 | January | 1          | 7             | Chemung     | 2702                  | 5869               | 450645              | 1355                                 | 2191                              | 190543                             | 1347                                     | 3678                                  | 260102                                 | 
| 2002 | January | 1          | 8             | Chenango    | 1704                  | 3758               | 286522              | 483                                  | 666                               | 57186                              | 1221                                     | 3092                                  | 229336                                 | 
| 2002 | January | 1          | 9             | Clinton     | 2945                  | 5581               | 421385              | 1348                                 | 1706                              | 140938                             | 1597                                     | 3875                                  | 280447                                 | 
| 2002 | January | 1          | 10            | Columbia    | 1365                  | 2521               | 196052              | 584                                  | 815                               | 72726                              | 781                                      | 1706                                  | 123326                                 | 
```