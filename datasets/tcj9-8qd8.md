# Bureau of Sanitation - Unscheduled Absences by Day of Week for Refuse Truck Drivers

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/bureau-of-sanitation-unscheduled-absences-by-day-of-week-for-refuse-truck-drivers-da1b6) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/tcj9-8qd8) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/tcj9-8qd8/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/tcj9-8qd8/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | tcj9-8qd8 |
| Name | Bureau of Sanitation - Unscheduled Absences by Day of Week for Refuse Truck Drivers |
| Category | Sanitation |
| Created | 2011-09-27T21:51:11Z |
| Publication Date | 2011-09-27T21:52:12Z |

## Description

Number of call outs by day of the week from August 2010 - August 2011 for truck drivers in Streets & Sanitation Department

## Columns

```ls
| Included | Schema Type    | Field Name                                                            | Name                                                                 | Data Type | Render Type |
| ======== | ============== | ===================================================================== | ==================================================================== | ========= | =========== |
| No       | time           | :updated_at                                                           | updated_at                                                           | meta_data | meta_data   |
| No       |                | day_of_the_week                                                       | Day of the Week                                                      | text      | text        |
| Yes      | numeric metric | average_unscheduled_absences_by_day_of_week_for_refuse_truck_drivers_ | Average Unscheduled Absences by Day of Week for Refuse Truck Drivers | number    | number      |
| Yes      | numeric metric | unscheduled_absence                                                   | Unscheduled Absences (Yearly Total)                                  | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = day_of_the_week
```

## Data Commands

```ls
series e:tcj9-8qd8 d:2011-09-26T19:30:07.000Z m:unscheduled_absence=932 m:average_unscheduled_absences_by_day_of_week_for_refuse_truck_drivers_=19

series e:tcj9-8qd8 d:2011-09-26T19:30:08.000Z m:unscheduled_absence=741 m:average_unscheduled_absences_by_day_of_week_for_refuse_truck_drivers_=13

series e:tcj9-8qd8 d:2011-09-26T19:30:10.000Z m:unscheduled_absence=759 m:average_unscheduled_absences_by_day_of_week_for_refuse_truck_drivers_=13
```

## Meta Commands

```ls
metric m:average_unscheduled_absences_by_day_of_week_for_refuse_truck_drivers_ p:integer l:"Average Unscheduled Absences by Day of Week for Refuse Truck Drivers" t:dataTypeName=number

metric m:unscheduled_absence p:integer l:"Unscheduled Absences (Yearly Total)" t:dataTypeName=number

entity e:tcj9-8qd8 l:"Bureau of Sanitation - Unscheduled Absences by Day of Week for Refuse Truck Drivers" t:url=https://data.cityofchicago.org/api/views/tcj9-8qd8

property e:tcj9-8qd8 t:meta.view v:id=tcj9-8qd8 v:category=Sanitation v:averageRating=0 v:name="Bureau of Sanitation - Unscheduled Absences by Day of Week for Refuse Truck Drivers"

property e:tcj9-8qd8 t:meta.view.owner v:id=7jj6-h75i v:screenName=Eve v:displayName=Eve

property e:tcj9-8qd8 t:meta.view.tableauthor v:id=7jj6-h75i v:screenName=Eve v:displayName=Eve
```

## Top Records

```ls
| :updated_at | day_of_the_week | average_unscheduled_absences_by_day_of_week_for_refuse_truck_drivers_ | unscheduled_absence | 
| =========== | =============== | ===================================================================== | =================== | 
| 1317065407  | Monday          | 19                                                                    | 932                 | 
| 1317065408  | Tuesday         | 13                                                                    | 741                 | 
| 1317065410  | Wednesday       | 13                                                                    | 759                 | 
| 1317065413  | Thursday        | 14                                                                    | 775                 | 
| 1317135081  | Friday          | 18                                                                    | 950                 | 
```