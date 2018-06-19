# Public Housing Sites Managed HACLA 2014

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/public-housing-sites-managed-hacla-2014) |
| Metadata | [Link](https://data.lacity.org/api/views/vxhy-r447) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/vxhy-r447/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/vxhy-r447/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | vxhy-r447 |
| Name | Public Housing Sites Managed HACLA 2014 |
| Category | A Livable and Sustainable City |
| Tags | housing authority for the city of los angeles, hacla, locations, public housing, housing, sites |
| Created | 2014-12-06T22:02:51Z |
| Publication Date | 2015-01-12T21:51:43Z |

## Description

Public Housing Sites Managed HACLA 2014

## Columns

```ls
| Included | Schema Type    | Field Name                        | Name                              | Data Type | Render Type |
| ======== | ============== | ================================= | ================================= | ========= | =========== |
| Yes      | series tag     | site_name                         | Site Name                         | text      | text        |
| Yes      | series tag     | property_no                       | Property No.                      | text      | text        |
| Yes      | numeric metric | acres                             | Acres                             | number    | number      |
| Yes      | numeric metric | actual_units                      | Actual Units                      | number    | number      |
| Yes      | numeric metric | occupied_units                    | Occupied Units                    | number    | number      |
| Yes      | numeric metric | rate_of_occupied_units            | Rate of Occupied Units            | percent   | percent     |
| Yes      | series tag     | no_of_resident                    | No. of Resident                   | text      | text        |
| Yes      | numeric metric | average_rent_per_month            | Average Rent Per Month            | money     | money       |
| Yes      | numeric metric | average_monthly_income_per_family | Average Monthly Income Per Family | money     | money       |
```

## Time Field

```ls
Value = 2014
Format & Zone = yyyy
```

## Data Commands

```ls
series e:vxhy-r447 d:2014-01-01T00:00:00.000Z t:property_no=4013 t:site_name="Nickerson Gardens" t:no_of_resident="* 3,217" m:occupied_units=1029 m:average_rent_per_month=286 m:average_monthly_income_per_family=1194 m:acres=68.6 m:rate_of_occupied_units=96.5

series e:vxhy-r447 d:2014-01-01T00:00:00.000Z t:property_no=4021 t:site_name="Mar Vista Gardens" t:no_of_resident="* 1,922" m:occupied_units=597 m:average_rent_per_month=423 m:actual_units=601 m:average_monthly_income_per_family=1863 m:acres=43.2 m:rate_of_occupied_units=99.3

series e:vxhy-r447 d:2014-01-01T00:00:00.000Z t:property_no=4009 t:site_name="Avalon Gardens" t:no_of_resident="* 443" m:occupied_units=162 m:average_rent_per_month=318 m:actual_units=164 m:average_monthly_income_per_family=1507 m:acres=14.9 m:rate_of_occupied_units=98.8
```

## Meta Commands

```ls
metric m:acres p:float l:Acres t:dataTypeName=number

metric m:actual_units p:integer l:"Actual Units" t:dataTypeName=number

metric m:occupied_units p:integer l:"Occupied Units" t:dataTypeName=number

metric m:rate_of_occupied_units p:float l:"Rate of Occupied Units" t:dataTypeName=percent

metric m:average_rent_per_month p:double l:"Average Rent Per Month" t:dataTypeName=money

metric m:average_monthly_income_per_family p:double l:"Average Monthly Income Per Family" t:dataTypeName=money

entity e:vxhy-r447 l:"Public Housing Sites Managed HACLA 2014" t:url=https://data.lacity.org/api/views/vxhy-r447

property e:vxhy-r447 t:meta.view v:id=vxhy-r447 v:category="A Livable and Sustainable City" v:averageRating=0 v:name="Public Housing Sites Managed HACLA 2014"

property e:vxhy-r447 t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:vxhy-r447 t:meta.view.owner v:id=ihg6-62bp v:screenName="Rodd Talebi" v:displayName="Rodd Talebi"

property e:vxhy-r447 t:meta.view.tableauthor v:id=ihg6-62bp v:screenName="Rodd Talebi" v:displayName="Rodd Talebi"
```

## Top Records

```ls
| site_name              | property_no | acres              | actual_units | occupied_units | rate_of_occupied_units | no_of_resident | average_rent_per_month | average_monthly_income_per_family | 
| ====================== | =========== | ================== | ============ | ============== | ====================== | ============== | ====================== | ================================= | 
| Nickerson Gardens      | 4013        | 68.599999999999994 |              | 1029           | 96.5                   | * 3,217        | 286.00                 | 1194.00                           | 
| Mar Vista Gardens      | 4021        | 43.2               | 601          | 597            | 99.3                   | * 1,922        | 423.00                 | 1863.00                           | 
| Avalon Gardens         | 4009        | 14.9               | 164          | 162            | 98.8                   | * 443          | 318.00                 | 1507.00                           | 
| Pueblo Del Sol         | 4222 & 4227 | 34.3               | 242          | 242            | 100.0                  | * 856          | 489.00                 | 1966.00                           | 
| New Pico & Las Casitas | 4223 & 4224 | 18.4               | 296          | 296            | 100.0                  | * 952          | 437.00                 | 2097.00                           | 
| San Fernando Gardens   | 4022        | 33.5               | 448          | 445            | 99.3                   | * 1,692        | 435.00                 | 1812.00                           | 
| Jordan Downs           | 4016        | 49.5               | 727          | 720            | 99.0                   | * 2,620        | 341.00                 | 1412.00                           | 
| Pueblo Del Rio         | 4003 & 4015 | 34.1               | 660          | 654            | 99.1                   | * 2,005        | 340.00                 | 1456.00                           | 
| Rancho San Pedro       | 4004 & 4017 | 21.2               | 478          | 470            | 98.3                   | * 1,367        | 365.00                 | 1621.00                           | 
| Rose Hill Courts       | 4008        | 5.2                | 100          | 94             | 94.0                   | * 242          | 325.00                 | 1675.00                           | 
```