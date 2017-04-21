# Ready NY Events

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ready-ny-events-d9877) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/hyur-qpyf) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/hyur-qpyf/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/hyur-qpyf/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | hyur-qpyf |
| Name | Ready NY Events |
| Attribution | Office of Emergency Management (OEM) |
| Category | Public Safety |
| Tags | ready ny events, oem, preparedness |
| Created | 2014-03-05T22:32:47Z |
| Publication Date | 2016-08-01T17:00:55Z |

## Description

Events held to increase public preparedness

## Columns

```ls
| Included | Schema Type | Field Name  | Name       | Data Type | Render Type |
| ======== | =========== | =========== | ========== | ========= | =========== |
| Yes      | time        | date        | Event Date | text      | text        |
| Yes      | series tag  | description | Event      | text      | text        |
| Yes      | series tag  | time        | Location   | text      | text        |
| No       |             | location    | Address    | text      | text        |
| Yes      | series tag  | borough     | Borough    | text      | text        |
```

## Time Field

```ls
Value = date
Format & Zone = MM/dd/yy
```

## Series Fields

```ls
Excluded Fields = location
```

## Data Commands

```ls
series e:hyur-qpyf d:2016-06-30T00:00:00.000Z t:time="Christian Heritage Church" t:description="Citizen Preparedness Training" t:borough=Brooklyn m:row_number.hyur-qpyf=1

series e:hyur-qpyf d:2016-06-29T00:00:00.000Z t:time="10 Gregg Place" t:description="RNY General Presentation" t:borough="Staten Island" m:row_number.hyur-qpyf=2

series e:hyur-qpyf d:2016-06-29T00:00:00.000Z t:time="Governor's Office of Storm Recovery" t:description="Bring Your Kids to Work Day" t:borough=Manhattan m:row_number.hyur-qpyf=3
```

## Meta Commands

```ls
metric m:row_number.hyur-qpyf p:long l:"Row Number"

entity e:hyur-qpyf l:"Ready NY Events" t:attribution="Office of Emergency Management (OEM)" t:url=https://data.cityofnewyork.us/api/views/hyur-qpyf

property e:hyur-qpyf t:meta.view v:id=hyur-qpyf v:category="Public Safety" v:averageRating=0 v:name="Ready NY Events" v:attribution="Office of Emergency Management (OEM)"

property e:hyur-qpyf t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:hyur-qpyf t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| date    | description                         | time                                | location                    | borough       | 
| ======= | =================================== | =================================== | =========================== | ============= | 
| 6/30/16 | Citizen Preparedness Training       | Christian Heritage Church           | 4121 Avenue J               | Brooklyn      | 
| 6/29/16 | RNY General Presentation            | 10 Gregg Place                      | 10 Gregg Place              | Staten Island | 
| 6/29/16 | Bring Your Kids to Work Day         | Governor's Office of Storm Recovery | 25 Beaver Street, 5th Floor | Manhattan     | 
| 6/29/16 | Emergency Preparedness Presentation | The Axis Project                    | 1325 Fifth Ave              | Manhattan     | 
| 6/29/16 | Ready NY for Nursing Students       | NYC EM Situation Room               | 165 Cadman Plaza East       | Brooklyn      | 
| 6/29/16 | Caribbean American Heritage Fair    | Brooklyn Borough Hall               | 209 Joralemon St.           | Brooklyn      | 
| 6/28/16 | Hurricane Prep                      | RAIN Eastchester Senior Center      | 1246 Burke Avenue           | Bronx         | 
| 6/28/16 | National Safety Month               | Coney Island Hospital               | 2601 OCean Parkway          | Brooklyn      | 
| 6/27/16 | Emergency Preparedness for Staff    | IncludeNYC                          | 116 E 16 St, 5 Fl           | Manhattan     | 
| 6/27/16 | Citizen Preparedness Training       | Restoration Temple                  | 4610 Church Ave             | Brooklyn      | 
```