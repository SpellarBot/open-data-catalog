# Performance Metrics - Chicago Park District - Facilities Work Order Management

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/performance-metrics-chicago-park-district-facilities-work-order-management-9a082) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/sya9-5zxj) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/sya9-5zxj/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/sya9-5zxj/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | sya9-5zxj |
| Name | Performance Metrics - Chicago Park District - Facilities Work Order Management |
| Attribution | Chicago Park District |
| Category | Administration & Finance |
| Tags | performance metrics, parks |
| Created | 2011-11-09T15:52:53Z |
| Publication Date | 2012-08-03T19:15:34Z |

## Description

The Facility Management Department works to ensure safe, clean and high quality parkland and facilities throughout the City of Chicago by utilizing the highest effective maintenance standards/procedures and management practices. This department is responsible for the maintenance, repair, renovation and general upkeep of all Park District property such as field houses, swimming pools, comfort stations, park amenities, etc. The data displayed represents the weekly number of work orders completed compared to the number open by the Facilities Department. 

Please note that the number is cumulative, the previous weeks open work orders roll into the current week, which during seasonal fluctuations may cause the number completed to outpace the number opened.

## Columns

```ls
| Included | Schema Type    | Field Name                                 | Name                         | Data Type | Render Type |
| ======== | ============== | ========================================== | ============================ | ========= | =========== |
| No       | time           | :updated_at                                | updated_at                   | meta_data | meta_data   |
| No       |                | date                                       | Date                         | text      | text        |
| Yes      | numeric metric | open_w_o_s_completed_1                     | # Open Work Orders Completed | number    | number      |
| Yes      | numeric metric | open                                       | # Open                       | number    | number      |
| Yes      | numeric metric | open_w_o_s_completed_2                     | % Open Work Orders Completed | percent   | percent     |
| Yes      | numeric metric | complete_target_based_on_previous_results_ | % Complete Target            | percent   | percent     |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = date
```

## Data Commands

```ls
series e:sya9-5zxj d:2012-07-02T12:22:43.000Z m:open=1055 m:open_w_o_s_completed_1=788 m:open_w_o_s_completed_2=75 m:complete_target_based_on_previous_results_=85

series e:sya9-5zxj d:2012-07-02T12:22:43.000Z m:open=1027 m:open_w_o_s_completed_1=745 m:open_w_o_s_completed_2=73 m:complete_target_based_on_previous_results_=85

series e:sya9-5zxj d:2012-07-02T12:22:43.000Z m:open=1082 m:open_w_o_s_completed_1=684 m:open_w_o_s_completed_2=63 m:complete_target_based_on_previous_results_=85
```

## Meta Commands

```ls
metric m:open_w_o_s_completed_1 p:integer l:"# Open Work Orders Completed" t:dataTypeName=number

metric m:open p:integer l:"# Open" t:dataTypeName=number

metric m:open_w_o_s_completed_2 p:integer l:"% Open Work Orders Completed" t:dataTypeName=percent

metric m:complete_target_based_on_previous_results_ p:integer l:"% Complete Target" t:dataTypeName=percent

entity e:sya9-5zxj l:"Performance Metrics - Chicago Park District - Facilities Work Order Management" t:attribution="Chicago Park District" t:url=https://data.cityofchicago.org/api/views/sya9-5zxj

property e:sya9-5zxj t:meta.view v:id=sya9-5zxj v:category="Administration & Finance" v:attributionLink=http://www.chicagoparkdistrict.com/ v:averageRating=0 v:name="Performance Metrics - Chicago Park District - Facilities Work Order Management" v:attribution="Chicago Park District"

property e:sya9-5zxj t:meta.view.owner v:id=7jj6-h75i v:screenName=Eve v:displayName=Eve

property e:sya9-5zxj t:meta.view.tableauthor v:id=7jj6-h75i v:screenName=Eve v:displayName=Eve
```

## Top Records

```ls
| :updated_at | date    | open_w_o_s_completed_1 | open | open_w_o_s_completed_2 | complete_target_based_on_previous_results_ | 
| =========== | ======= | ====================== | ==== | ====================== | ========================================== | 
| 1341231763  | Date    |                        |      |                        |                                            | 
| 1341231763  | 6/29/11 | 788                    | 1055 | 75                     | 85                                         | 
| 1341231763  | 7/6/11  | 745                    | 1027 | 73                     | 85                                         | 
| 1341231763  | 7/13/11 | 684                    | 1082 | 63                     | 85                                         | 
| 1341231763  | 7/20/11 | 767                    | 1067 | 72                     | 85                                         | 
| 1341231763  | 7/27/11 | 834                    | 1102 | 76                     | 85                                         | 
| 1341231763  | 8/3/11  | 829                    | 1122 | 74                     | 85                                         | 
| 1341231763  | 8/10/11 | 827                    | 1105 | 75                     | 85                                         | 
| 1341231763  | 8/17/11 | 808                    | 1028 | 79                     | 85                                         | 
| 1341231763  | 8/24/11 | 784                    | 1074 | 73                     | 85                                         | 
```