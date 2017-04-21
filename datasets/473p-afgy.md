# Wastewater Treatment Plant Data

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/wastewater-treatment-plant-data-4f1af) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/473p-afgy) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/473p-afgy/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/473p-afgy/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 473p-afgy |
| Name | Wastewater Treatment Plant Data |
| Attribution | Department of Environmental Protection (DEP) |
| Category | Environment |
| Tags | wastewater treatment plant data, dep, capacities, water |
| Created | 2014-03-05T20:54:56Z |
| Publication Date | 2014-03-05T21:01:00Z |

## Description

New York city plant locations and capacities

## Columns

```ls
| Included | Schema Type    | Field Name  | Name       | Data Type | Render Type |
| ======== | ============== | =========== | ========== | ========= | =========== |
| No       | time           | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag     | area_no     | Area No.   | text      | number      |
| Yes      | series tag     | location    | Location   | text      | text        |
| Yes      | numeric metric | capacity    | Capacity   | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:473p-afgy d:2014-03-05T12:54:59.000Z t:location="Bowery Bay" t:area_no=1 m:capacity=150

series e:473p-afgy d:2014-03-05T12:54:59.000Z t:location="Hunts Point" t:area_no=2 m:capacity=200

series e:473p-afgy d:2014-03-05T12:54:59.000Z t:location="Tallman Island" t:area_no=3 m:capacity=80
```

## Meta Commands

```ls
metric m:capacity p:integer l:Capacity t:dataTypeName=number

entity e:473p-afgy l:"Wastewater Treatment Plant Data" t:attribution="Department of Environmental Protection (DEP)" t:url=https://data.cityofnewyork.us/api/views/473p-afgy

property e:473p-afgy t:meta.view v:id=473p-afgy v:category=Environment v:averageRating=0 v:name="Wastewater Treatment Plant Data" v:attribution="Department of Environmental Protection (DEP)"

property e:473p-afgy t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:473p-afgy t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | area_no | location       | capacity | 
| =========== | ======= | ============== | ======== | 
| 1394024099  | 1       | Bowery Bay     | 150      | 
| 1394024099  | 2       | Hunts Point    | 200      | 
| 1394024099  | 3       | Tallman Island | 80       | 
| 1394024099  | 4       | Wards island   | 275      | 
| 1394024099  | 5       | Newtown Creek  | 310      | 
| 1394024099  | 6       | North River    | 170      | 
| 1394024099  | 7       | Oakwood Beach  | 40       | 
| 1394024099  | 8       | Port Richmond  | 60       | 
| 1394024099  | 9       | Red Hook       | 60       | 
| 1394024099  | 10      | 26th Ward      | 85       | 
```