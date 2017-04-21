# DOF Parking Violation Codes

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dof-parking-violation-codes-63051) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/ncbg-6agr) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/ncbg-6agr/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/ncbg-6agr/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | ncbg-6agr |
| Name | DOF Parking Violation Codes |
| Attribution | Department of Finance (DOF) |
| Category | Transportation |
| Tags | dof, parking, violation, code, fine |
| Created | 2013-01-16T14:56:58Z |
| Publication Date | 2013-01-16T17:10:35Z |

## Description

This dataset defines the parking violation codes in New York City and lists the fines. Each fine amount includes a $15 New York State Criminal Justice surcharge.

## Columns

```ls
| Included | Schema Type | Field Name              | Name                        | Data Type | Render Type |
| ======== | =========== | ======================= | =========================== | ========= | =========== |
| No       | time        | :updated_at             | updated_at                  | meta_data | meta_data   |
| Yes      | series tag  | code                    | CODE                        | text      | text        |
| Yes      | series tag  | definition              | DEFINITION                  | text      | text        |
| Yes      | series tag  | manhattan_96th_st_below | Manhattan  96th St. & below | text      | text        |
| Yes      | series tag  | all_other_areas         | All Other Areas             | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:ncbg-6agr d:2013-01-16T06:57:00.000Z t:all_other_areas=$115 t:manhattan_96th_st_below=$115 t:definition="Stopping, standing or parking where a sign, street marking, or traffic control device does not allow stopping." t:code=10 m:row_number.ncbg-6agr=1

series e:ncbg-6agr d:2013-01-16T06:57:00.000Z t:all_other_areas=$115 t:manhattan_96th_st_below=$115 t:definition="Hotel Loading/Unloading: Standing or parking where standing is not allowed by sign, street marking or; traffic control device." t:code=11 m:row_number.ncbg-6agr=2

series e:ncbg-6agr d:2013-01-16T06:57:00.000Z t:all_other_areas=$95 t:manhattan_96th_st_below=$95 t:definition="Snow Emergency: Standing or parking where standing is not allowed by sign, street marking or; traffic control device." t:code=12 m:row_number.ncbg-6agr=3
```

## Meta Commands

```ls
metric m:row_number.ncbg-6agr p:long l:"Row Number"

entity e:ncbg-6agr l:"DOF Parking Violation Codes" t:attribution="Department of Finance (DOF)" t:url=https://data.cityofnewyork.us/api/views/ncbg-6agr

property e:ncbg-6agr t:meta.view v:id=ncbg-6agr v:category=Transportation v:attributionLink=http://www.nyc.gov/html/dof/html/parking/violation_codes.shtml v:averageRating=0 v:name="DOF Parking Violation Codes" v:attribution="Department of Finance (DOF)"

property e:ncbg-6agr t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:ncbg-6agr t:meta.view.tableauthor v:id=8b43-zkvh v:screenName="Ram S." v:displayName="Ram S."
```

## Top Records

```ls
| :updated_at | code | definition                                                                                                                      | manhattan_96th_st_below | all_other_areas | 
| =========== | ==== | =============================================================================================================================== | ======================= | =============== | 
| 1358319420  | 10   | Stopping, standing or parking where a sign, street marking, or traffic control device does not allow stopping.                  | $115                    | $115            | 
| 1358319420  | 11   | Hotel Loading/Unloading: Standing or parking where standing is not allowed by sign, street marking or; traffic control device.  | $115                    | $115            | 
| 1358319420  | 12   | Snow Emergency: Standing or parking where standing is not allowed by sign, street marking or; traffic control device.           | $95                     | $95             | 
| 1358319420  | 13   | Taxi Stand: Standing or parking where standing is not allowed by sign, street marking or; traffic control device.               | $115                    | $115            | 
| 1358319420  | 14   | General No Standing: Standing or parking where standing is not allowed by sign, street marking or; traffic control device.      | $115                    | $115            | 
| 1358319420  | 16   | Truck Loading/Unloading: Standing or parking where standing is not allowed by sign, street marking or; traffic control device.  | $95                     | $95             | 
| 1358319420  | 17   | Authorized Vehicles Only: Standing or parking where standing is not allowed by sign, street marking or; traffic control device. | $95                     | $95             | 
| 1358319420  | 18   | Bus Lane: Standing or parking where standing is not allowed by sign, street marking or; traffic control device.                 | $115                    | $115            | 
| 1358319420  | 19   | Bus Stop: Standing or parking where standing is not allowed by sign, street marking or; traffic control device.                 | $115                    | $115            | 
| 1358319420  | 20   | General No Parking: No parking where parking is not allowed by sign, street marking or traffic control device.                  | $65                     | $60             | 
```