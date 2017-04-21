# Emissions Stations by Town

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/emissions-stations-by-town) |
| Metadata | [Link](https://data.ct.gov/api/views/q8eg-b88c) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/q8eg-b88c/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/q8eg-b88c/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | q8eg-b88c |
| Name | Emissions Stations by Town |
| Attribution | Department of Motor Vehicles |
| Category | Transportation |
| Tags | emissions, testing, stations, dmv |
| Created | 2014-03-28T12:39:17Z |
| Publication Date | 2014-10-02T19:40:30Z |

## Description

List of Active Emissions testing stations as of Oct,2,2014

## Columns

```ls
| Included | Schema Type | Field Name   | Name         | Data Type | Render Type |
| ======== | =========== | ============ | ============ | ========= | =========== |
| No       | time        | :updated_at  | updated_at   | meta_data | meta_data   |
| Yes      | series tag  | station_name | Station Name | text      | text        |
| Yes      | series tag  | phone        | Phone        | text      | text        |
| Yes      | series tag  | station_type | Station Type | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:q8eg-b88c d:2014-10-02T12:26:24.000Z t:station_name="Frenchys Auto Repair Inc." t:phone="(203) 265-0889" t:station_type="OBD Plus" m:row_number.q8eg-b88c=1

series e:q8eg-b88c d:2014-10-02T12:26:47.000Z t:station_name="Thompson Auto Care LLC" t:phone=860-923-2520 t:station_type="Full Service" m:row_number.q8eg-b88c=2

series e:q8eg-b88c d:2014-10-02T12:26:47.000Z t:station_name="Amaral Motors Inc." t:phone="(203) 426-4427" t:station_type="OBD Plus" m:row_number.q8eg-b88c=3
```

## Meta Commands

```ls
metric m:row_number.q8eg-b88c p:long l:"Row Number"

entity e:q8eg-b88c l:"Emissions Stations by Town" t:attribution="Department of Motor Vehicles" t:url=https://data.ct.gov/api/views/q8eg-b88c

property e:q8eg-b88c t:meta.view v:id=q8eg-b88c v:category=Transportation v:attributionLink=http://www.ct.gov/dmv v:averageRating=0 v:name="Emissions Stations by Town" v:attribution="Department of Motor Vehicles"

property e:q8eg-b88c t:meta.view.license v:name="Public Domain"

property e:q8eg-b88c t:meta.view.owner v:id=fd5k-6njr v:screenName=APatel v:displayName=APatel

property e:q8eg-b88c t:meta.view.tableauthor v:id=fd5k-6njr v:screenName=APatel v:roleName=editor v:displayName=APatel
```

## Top Records

```ls
| :updated_at | station_name                           | phone          | station_type | 
| =========== | ====================================== | ============== | ============ | 
| 1412252784  | Frenchys Auto Repair Inc.              | (203) 265-0889 | OBD Plus     | 
| 1412252807  | Thompson Auto Care LLC                 | 860-923-2520   | Full Service | 
| 1412252807  | Amaral Motors Inc.                     | (203) 426-4427 | OBD Plus     | 
| 1412252807  | O'Neill's Chevrolet Buick Inc          | (860) 677-1666 | Full Service | 
| 1412252807  | Long Ridge Service                     | (203) 322-3900 | OBD Plus     | 
| 1412252807  | General Muffler & Automotive Supply    | (203) 735-6406 | OBD Plus     | 
| 1412252807  | Nova Automotive                        | (203) 865-6174 | OBD Plus     | 
| 1412252807  | T and B Motor Sales and Service Inc.   | (860) 423-1187 | Full Service | 
| 1412252807  | West High Service Station Inc.         | (203) 324-0288 | OBD Plus     | 
| 1412252807  | Modern Tire & Auto Service - Newington | (860) 666-2404 | OBD Plus     | 
```