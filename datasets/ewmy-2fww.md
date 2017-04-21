# Procurements by Size

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/procurements-by-size-fd786) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/ewmy-2fww) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/ewmy-2fww/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/ewmy-2fww/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | ewmy-2fww |
| Name | Procurements by Size |
| Attribution | Office of the Mayor (OTM) |
| Category | City Government |
| Tags | otm, procurement, size, fiscal year |
| Created | 2014-10-23T21:02:19Z |
| Publication Date | 2014-10-23T21:06:07Z |

## Description

Summary table of procurements in the fiscal year grouped by agency and size

## Columns

```ls
| Included | Schema Type    | Field Name    | Name          | Data Type | Render Type |
| ======== | ============== | ============= | ============= | ========= | =========== |
| No       | time           | :updated_at   | updated_at    | meta_data | meta_data   |
| Yes      | series tag     | agency        | Agency        | text      | text        |
| Yes      | series tag     | budget_size   | Budget Size   | text      | text        |
| Yes      | numeric metric | 2014_fycount  | 2014 FYCount  | number    | number      |
| Yes      | numeric metric | 2014_fyvalue  | 2014 FYValue  | money     | money       |
| Yes      | numeric metric | 2013_fycount  | 2013 FYCount  | number    | number      |
| Yes      | numeric metric | 2013_fy_value | 2013 FY Value | money     | money       |
| Yes      | numeric metric | 2012_fycount  | 2012 FYCount  | number    | number      |
| Yes      | numeric metric | 2012_fy_value | 2012 FY Value | money     | money       |
| Yes      | numeric metric | 2011_fycount  | 2011 FYCount  | number    | number      |
| Yes      | numeric metric | 2011_fy_value | 2011 FY Value | money     | money       |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:ewmy-2fww d:2014-10-23T14:02:22.000Z t:budget_size="Greater than $25,000,000" t:agency=ACS m:2012_fy_value=73624372 m:2011_fy_value=1705575236 m:2014_fycount=7 m:2014_fyvalue=722943551 m:2013_fy_value=1331957906 m:2013_fycount=22 m:2012_fycount=1 m:2011_fycount=34

series e:ewmy-2fww d:2014-10-23T14:02:22.000Z t:budget_size="Greater than $25,000,000" t:agency=DCAS m:2012_fy_value=412588787 m:2011_fy_value=1117214510 m:2014_fycount=12 m:2014_fyvalue=769282720 m:2013_fy_value=1565457220 m:2013_fycount=11 m:2012_fycount=7 m:2011_fycount=13

series e:ewmy-2fww d:2014-10-23T14:02:22.000Z t:budget_size="Greater than $25,000,000" t:agency=DDC m:2012_fy_value=364983441 m:2011_fy_value=201351183 m:2014_fycount=7 m:2014_fyvalue=348325822 m:2013_fy_value=614405043 m:2013_fycount=9 m:2012_fycount=4 m:2011_fycount=5
```

## Meta Commands

```ls
metric m:2014_fycount p:integer l:"2014 FYCount" t:dataTypeName=number

metric m:2014_fyvalue p:long l:"2014 FYValue" t:dataTypeName=money

metric m:2013_fycount p:integer l:"2013 FYCount" t:dataTypeName=number

metric m:2013_fy_value p:integer l:"2013 FY Value" t:dataTypeName=money

metric m:2012_fycount p:integer l:"2012 FYCount" t:dataTypeName=number

metric m:2012_fy_value p:integer l:"2012 FY Value" t:dataTypeName=money

metric m:2011_fycount p:integer l:"2011 FYCount" t:dataTypeName=number

metric m:2011_fy_value p:integer l:"2011 FY Value" t:dataTypeName=money

entity e:ewmy-2fww l:"Procurements by Size" t:attribution="Office of the Mayor (OTM)" t:url=https://data.cityofnewyork.us/api/views/ewmy-2fww

property e:ewmy-2fww t:meta.view v:id=ewmy-2fww v:category="City Government" v:averageRating=0 v:name="Procurements by Size" v:attribution="Office of the Mayor (OTM)"

property e:ewmy-2fww t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:ewmy-2fww t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | agency | budget_size              | 2014_fycount | 2014_fyvalue | 2013_fycount | 2013_fy_value | 2012_fycount | 2012_fy_value | 2011_fycount | 2011_fy_value | 
| =========== | ====== | ======================== | ============ | ============ | ============ | ============= | ============ | ============= | ============ | ============= | 
| 1414072942  | ACS    | Greater than $25,000,000 | 7            | 722943551    | 22           | 1331957906    | 1            | 73624372      | 34           | 1705575236    | 
| 1414072942  | DCAS   | Greater than $25,000,000 | 12           | 769282720    | 11           | 1565457220    | 7            | 412588787     | 13           | 1117214510    | 
| 1414072942  | DDC    | Greater than $25,000,000 | 7            | 348325822    | 9            | 614405043     | 4            | 364983441     | 5            | 201351183     | 
| 1414072942  | DEP    | Greater than $25,000,000 | 25           | 1194288423   | 12           | 631905036     | 5            | 193595326     | 2            | 152458561     | 
| 1414072942  | DHS    | Greater than $25,000,000 | 4            | 208880150    | 8            | 381962397     | 11           | 642647030     | 7            | 390700405     | 
| 1414072942  | DOC    | Greater than $25,000,000 | 1            | 27015856     | 0            | 0             | 0            | 0             | 0            | 0             | 
| 1414072942  | DOF    | Greater than $25,000,000 | 1            | 36800000     | 0            | 0             | 1            | 31785717      | 0            | 0             | 
| 1414072942  | DOHMH  | Greater than $25,000,000 | 3            | 546930326    | 5            | 1466091049    | 1            | 30835596      | 5            | 785759470     | 
| 1414072942  | DOITT  | Greater than $25,000,000 | 9            | 697121059    | 1            | 56236831      | 4            | 185987476     | 5            | 553372269     | 
| 1414072942  | DOT    | Greater than $25,000,000 | 2            | 176862713    | 2            | 269745850     | 2            | 135765169     | 0            | 0             | 
```