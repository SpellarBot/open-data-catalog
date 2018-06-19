# Motor Vehicle Crashes - Violation Information: Three Year Window

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/motor-vehicle-crashes-violation-information-beginning-2009) |
| Metadata | [Link](https://data.ny.gov/api/views/abfj-y7uq) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/abfj-y7uq/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/abfj-y7uq/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | abfj-y7uq |
| Name | Motor Vehicle Crashes - Violation Information: Three Year Window |
| Attribution | NYS Department of Motor Vehicles |
| Category | Transportation |
| Tags | crash, accident, fatalities, vehicle, driver, owner, ticket, violation |
| Created | 2013-05-28T19:25:14Z |
| Publication Date | 2015-08-10T20:01:26Z |

## Description

Attributes about each violation citation issued at the scene of the motor vehicle crash reported to NYS DMV

## Columns

```ls
| Included | Schema Type | Field Name            | Name                  | Data Type | Render Type |
| ======== | =========== | ===================== | ===================== | ========= | =========== |
| Yes      | time        | year                  | Year                  | number    | number      |
| Yes      | series tag  | violation_description | Violation Description | text      | text        |
| Yes      | series tag  | violation_code        | Violation Code        | text      | text        |
| Yes      | series tag  | case_individual_id    | Case Individual ID    | text      | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
```

## Meta Commands

```ls
entity e:abfj-y7uq l:"Motor Vehicle Crashes - Violation Information: Three Year Window" t:attribution="NYS Department of Motor Vehicles" t:url=https://data.ny.gov/api/views/abfj-y7uq

property e:abfj-y7uq t:meta.view v:id=abfj-y7uq v:category=Transportation v:attributionLink=http://www.dmv.ny.gov/stats.htm v:averageRating=0 v:name="Motor Vehicle Crashes - Violation Information: Three Year Window" v:attribution="NYS Department of Motor Vehicles"

property e:abfj-y7uq t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:abfj-y7uq t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:abfj-y7uq t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| year | violation_description                              | violation_code | case_individual_id | 
| ==== | ================================================== | ============== | ================== | 
| 2012 | UNLICENSED OPERATOR                                | 5091           | 12958468           | 
| 2012 | AGG UNLIC OPER 3 PLUS SUSPENSION                   | 5112A4         | 12958468           | 
| 2012 | FAILED TO USE DESIGNATED LANE                      | 1128C          | 12958509           | 
| 2012 | AGGRAVATED UNLIC OP 3RD MISD                       | 5111A          | 12958512           | 
| 2012 | LEAVING/SCENE PROPERTY DAMAGE ACC.                 | 6001A          | 12958558           | 
| 2012 | MOVED FROM LANE UNSAFELY                           | 1128A          | 12958558           | 
| 2012 | DRIVING WHILE INTOXICATED                          | 11923          | 12958582           | 
| 2012 | FLD TO YLD RT-OF-WAY ON LEFT TURN                  | 1141           | 12958582           | 
| 2012 | AGGRAVATED DWI - BLOOD ALCOHOL CONTENT .18 OR HIGH | 11922AA        | 12958582           | 
| 2012 | UNLICENSED OPERATOR                                | 5091           | 12958588           | 
```