# Concrete/Hardware Weekly Repair Schedule

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/concrete-hardware-weekly-repair-schedule-be31f) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/78sp-6jhj) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/78sp-6jhj/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/78sp-6jhj/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 78sp-6jhj |
| Name | Concrete/Hardware Weekly Repair Schedule |
| Attribution | Department of Transportation (DOT) |
| Category | Transportation |
| Tags | dot, concrete, hardware, repair schedule |
| Created | 2014-10-23T14:40:24Z |
| Publication Date | 2014-10-23T14:42:07Z |

## Description

Concrete schedule for installation maintenance or repair of concrete structures (center medians, curbs, sidewalks and other concrete infrastructures)

## Columns

```ls
| Included | Schema Type | Field Name  | Name       | Data Type | Render Type |
| ======== | =========== | =========== | ========== | ========= | =========== |
| No       | time        | :updated_at | updated_at | meta_data | meta_data   |
| No       |             | day_date    | Day & Date | text      | text        |
| Yes      | series tag  | borough     | Borough    | text      | text        |
| Yes      | series tag  | location    | Location   | text      | text        |
| Yes      | series tag  | details     | Details    | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = day_date
```

## Data Commands

```ls
series e:78sp-6jhj d:2014-10-23T07:40:27.000Z t:location="No Work" m:row_number.78sp-6jhj=1

series e:78sp-6jhj d:2014-10-23T07:40:27.000Z t:details="Neckdowns, Refuge Island & Median Ext" t:location="Houston St / 6 Ave" t:borough=Manhattan m:row_number.78sp-6jhj=2

series e:78sp-6jhj d:2014-10-23T07:40:27.000Z t:details="Median Refuge Islands" t:location="West End Ave @ W 95 St & @ W 97 St" t:borough=Manhattan m:row_number.78sp-6jhj=3
```

## Meta Commands

```ls
metric m:row_number.78sp-6jhj p:long l:"Row Number"

entity e:78sp-6jhj l:"Concrete/Hardware Weekly Repair Schedule" t:attribution="Department of Transportation (DOT)" t:url=https://data.cityofnewyork.us/api/views/78sp-6jhj

property e:78sp-6jhj t:meta.view v:id=78sp-6jhj v:category=Transportation v:attributionLink=http://www.nyc.gov/html/dot/downloads/pdf/concretesch.pdf v:averageRating=0 v:name="Concrete/Hardware Weekly Repair Schedule" v:attribution="Department of Transportation (DOT)"

property e:78sp-6jhj t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:78sp-6jhj t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | day_date           | borough   | location                                   | details                                 | 
| =========== | ================== | ========= | ========================================== | ======================================= | 
| 1414050027  | Sunday, 10/19/2014 |           | No Work                                    |                                         | 
| 1414050027  | Monday, 10/20/2014 | Manhattan | Houston St / 6 Ave                         | Neckdowns, Refuge Island & Median Ext   | 
| 1414050027  | Monday, 10/20/2014 | Manhattan | West End Ave @ W 95 St & @ W 97 St         | Median Refuge Islands                   | 
| 1414050027  | Monday, 10/20/2014 | Manhattan | A C Powell Jr Blvd b/t W 151 St & W 133 St | Median Tip Extensions                   | 
| 1414050027  | Monday, 10/20/2014 | Manhattan | IFO 42 Bond St                             | Cobblestone Roadway Repair              | 
| 1414050027  | Monday, 10/20/2014 | Bronx     | E L Grant Hwy / University Ave             | Islands, Neckdowns & Bus Pad            | 
| 1414050027  | Monday, 10/20/2014 | Bronx     | Mt Eden Ave / Walton Ave                   | Medians & Neckdown                      | 
| 1414050027  | Monday, 10/20/2014 | Bronx     | Gun Hill Rd b/t Jerome Ave & Olinville Ave | Bus Boarding Island, Neckdowns & Island | 
| 1414050027  | Monday, 10/20/2014 | Queens    | Northern Blvd b/t 102 St and 62 St         | Median Refuge Islands                   | 
| 1414050027  | Monday, 10/20/2014 | Queens    | Woodhaven Blvd/Queens Blvd                 | Neck-down & Medians Tips                | 
```