# NYC Fire Department Building Vacate List

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/nyc-fire-department-building-vacate-list-8d27f) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/n5xc-7jfa) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/n5xc-7jfa/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/n5xc-7jfa/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | n5xc-7jfa |
| Name | NYC Fire Department Building Vacate List |
| Attribution | Fire Department of New York City (FDNY) |
| Category | Public Safety |
| Tags | fdny, fire department, safety, fire safety, unsafe, vacate |
| Created | 2013-01-31T20:31:39Z |
| Publication Date | 2013-02-04T19:22:11Z |

## Description

List of Buildings declared unsafe and off-limits

## Columns

```ls
| Included | Schema Type    | Field Name  | Name        | Data Type | Render Type |
| ======== | ============== | =========== | =========== | ========= | =========== |
| Yes      | time           | vac_date    | vac_date    | text      | text        |
| Yes      | series tag     | num         | num         | text      | text        |
| No       |                | pf          | pf          | text      | text        |
| Yes      | series tag     | location_1  | street      | text      | text        |
| Yes      | series tag     | typ         | typ         | text      | text        |
| No       |                | sf          | sf          | text      | text        |
| Yes      | series tag     | bor         | bor         | text      | text        |
| No       |                | date_of_lif | date_of_lif | text      | text        |
| Yes      | series tag     | area_vac    | area_vac    | text      | text        |
| Yes      | numeric metric | div         | div         | number    | text        |
```

## Time Field

```ls
Value = vac_date
Format & Zone = MM/dd/yyyy
```

## Series Fields

```ls
Excluded Fields = pf,sf,date_of_lif
```

## Data Commands

```ls
series e:n5xc-7jfa d:2008-05-19T00:00:00.000Z t:num=1234 t:bor=BX t:typ=AVE t:area_vac="ENTIRE BLDG" t:location_1=INTERVALE m:div=6

series e:n5xc-7jfa d:2008-05-31T00:00:00.000Z t:num=1556 t:bor=BX t:typ=ST t:area_vac=BASEMENT t:location_1=PARKER m:div=6

series e:n5xc-7jfa d:2009-03-17T00:00:00.000Z t:num=1420 t:bor=BX t:typ=AVE t:area_vac="ENTIRE BUILDING" t:location_1=CROTONA m:div=6
```

## Meta Commands

```ls
metric m:div p:integer l:div t:dataTypeName=number

entity e:n5xc-7jfa l:"NYC Fire Department Building Vacate List" t:attribution="Fire Department of New York City (FDNY)" t:url=https://data.cityofnewyork.us/api/views/n5xc-7jfa

property e:n5xc-7jfa t:meta.view v:id=n5xc-7jfa v:category="Public Safety" v:attributionLink=http://www.nyc.gov/html/fdny/pdf/fire_prevention/vacate_status_list.pdf v:averageRating=0 v:name="NYC Fire Department Building Vacate List" v:attribution="Fire Department of New York City (FDNY)"

property e:n5xc-7jfa t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:n5xc-7jfa t:meta.view.tableauthor v:id=syvn-4vgv v:screenName="Sudhir Vasudeva" v:displayName="Sudhir Vasudeva"
```

## Top Records

```ls
| vac_date   | num  | pf | location_1 | typ | sf | bor | date_of_lif | area_vac                         | div | 
| ========== | ==== | == | ========== | === | == | === | =========== | ================================ | === | 
| 05/19/2008 | 1234 |    | INTERVALE  | AVE |    | BX  |             | ENTIRE BLDG                      | 6   | 
| 05/31/2008 | 1556 |    | PARKER     | ST  |    | BX  |             | BASEMENT                         | 6   | 
| 03/17/2009 | 1420 |    | CROTONA    | AVE |    | BX  |             | ENTIRE BUILDING                  | 6   | 
| 07/03/2009 | 414  | E  | 140        | ST  |    | BX  |             | 3rd floor and one room 2nd floor | 6   | 
| 01/27/2010 | 1698 |    | DAVIDSON   | AVE |    | BX  |             | 2ND FLOOR REAR                   | 7   | 
| 02/12/2010 | 366  |    | BRONX PARK | AVE |    | BX  |             | ENTIRE BUILDING                  | 7   | 
| 02/23/2010 | 1312 |    | BUSHWICK   | AVE |    | BR  |             | 2ND & 3RD FLOOR                  | 15  | 
| 03/16/2010 | 1233 |    | BOYNTON    | AVE |    | BX  |             | BASEMENT                         | 6   | 
| 04/23/2010 | 838  |    | MONROE     | ST  |    | BR  |             | 3RD FLOOR AND 8&10 ON 4TH        | 15  | 
| 06/21/2010 | 685  |    | GREENE     | AVE |    | BR  |             | 4TH FLOOR FRONT & REAR           | 11  | 
```