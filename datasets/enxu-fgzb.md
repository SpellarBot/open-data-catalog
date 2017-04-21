# Active Fleet Complement

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/active-fleet-complement-86d1c) |
| Metadata | [Link](https://data.seattle.gov/api/views/enxu-fgzb) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/enxu-fgzb/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/enxu-fgzb/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | enxu-fgzb |
| Name | Active Fleet Complement |
| Attribution | Fleet Management Division |
| Category | City Business |
| Tags | fleet, equipment, cars, trucks |
| Created | 2014-02-04T22:36:58Z |
| Publication Date | 2017-03-30T15:51:20Z |

## Description

The City of Seattle's active fleet equipment complement is dynamic. This list is updated on a monthly basis.

## Columns

```ls
| Included | Schema Type    | Field Name                 | Name                       | Data Type | Render Type |
| ======== | ============== | ========================== | ========================== | ========= | =========== |
| Yes      | series tag     | equipid                    | EquipID                    | text      | text        |
| Yes      | series tag     | license                    | License#                   | text      | text        |
| Yes      | time           | year                       | Year                       | number    | number      |
| Yes      | series tag     | make                       | Make                       | text      | text        |
| Yes      | series tag     | model                      | Model                      | text      | text        |
| Yes      | series tag     | descrip                    | Description                | text      | text        |
| Yes      | series tag     | dept                       | Dept                       | text      | text        |
| No       |                | inservicedate              | InServiceDate              | text      | text        |
| Yes      | numeric metric | inservicecost              | InServiceCost              | money     | money       |
| Yes      | numeric metric | estimated_replacement_year | Estimated Replacement Year | number    | text        |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = inservicedate
```

## Data Commands

```ls
series e:enxu-fgzb d:2009-01-01T00:00:00.000Z t:model=CW1422-102 t:descrip="TRAILER - ENCLOSED" t:dept=SPU t:equipid=96584 t:license=49152D t:make="WELLS CARGO" m:inservicecost=7439.1 m:estimated_replacement_year=2023

series e:enxu-fgzb d:2011-01-01T00:00:00.000Z t:model=337 t:descrip="TRUCK - EDUCTOR - VAC CON" t:dept=SCL t:equipid=31623 t:license=53085D t:make=PETERBILT m:inservicecost=269756.1 m:estimated_replacement_year=2027

series e:enxu-fgzb d:2009-01-01T00:00:00.000Z t:model="INTERCEPTOR III" t:descrip="PEO SCOOTER" t:dept=SPD t:equipid=98242 t:license=2568EX t:make=GO-4 m:inservicecost=33837.18 m:estimated_replacement_year=2016
```

## Meta Commands

```ls
metric m:inservicecost p:double l:InServiceCost d:"Cost to Place in Service" t:dataTypeName=money

metric m:estimated_replacement_year p:integer l:"Estimated Replacement Year" t:dataTypeName=number

entity e:enxu-fgzb l:"Active Fleet Complement" t:attribution="Fleet Management Division" t:url=https://data.seattle.gov/api/views/enxu-fgzb

property e:enxu-fgzb t:meta.view v:id=enxu-fgzb v:category="City Business" v:attributionLink=http://www.seattle.gov v:averageRating=0 v:name="Active Fleet Complement" v:attribution="Fleet Management Division"

property e:enxu-fgzb t:meta.view.license v:name="Public Domain"

property e:enxu-fgzb t:meta.view.owner v:id=sb28-e8im v:screenName="FAS - Fleet Management" v:displayName="FAS - Fleet Management"

property e:enxu-fgzb t:meta.view.tableauthor v:id=sb28-e8im v:screenName="FAS - Fleet Management" v:roleName=publisher v:displayName="FAS - Fleet Management"
```

## Top Records

```ls
| equipid | license | year | make        | model           | descrip                         | dept | inservicedate | inservicecost | estimated_replacement_year | 
| ======= | ======= | ==== | =========== | =============== | =============================== | ==== | ============= | ============= | ========================== | 
| 96584   | 49152D  | 2009 | WELLS CARGO | CW1422-102      | TRAILER - ENCLOSED              | SPU  | 15-Sep-08     | 7439.1        | 2023                       | 
| 31623   | 53085D  | 2011 | PETERBILT   | 337             | TRUCK - EDUCTOR - VAC CON       | SCL  | 03-Oct-11     | 269756.10     | 2027                       | 
| 98242   | 2568EX  | 2009 | GO-4        | INTERCEPTOR III | PEO SCOOTER                     | SPD  | 09-Jun-09     | 33837.18      | 2016                       | 
| 79278   | 49449D  | 2009 | GMC         | WORK HORSE      | WALKIN VAN - CLASS 4            | SCL  | 15-Jul-09     | 140349.63     | 2025                       | 
| 71712   | 44395D  | 2007 | TOYOTA      | PRIUS           | SEDAN - COMPACT - HYBRID        | SFD  | 19-Jun-07     | 24886.75      | 2017                       | 
| 95966   | 49405D  | 2009 | PETERBILT   | 335             | TRUCK - REFUSE PACKER - CLASS 7 | DPR  | 12-Nov-08     | 210471.23     | 2015                       | 
| 71459   | 44397D  | 2007 | TOYOTA      | PRIUS           | SEDAN - COMPACT - HYBRID        | SFD  | 11-Jun-07     | 24572.53      | 2017                       | 
| 31598   | 54157D  | 2011 | FORD        | CROWN VICTORIA  | PATROL CAR                      | SPD  | 01-Mar-13     | 41544.53      | 2018                       | 
| 99216   | 61314D  | 2009 | TOYOTA      | HIGHLANDER      | SUV - MID SIZE - HYBRID - 4WD   | SFD  | 01-Jul-09     | 53088.39      | 2019                       | 
| 31599   | 54158D  | 2011 | FORD        | CROWN VICTORIA  | PATROL CAR                      | SPD  | 26-Sep-13     | 44830.81      | 2018                       | 
```