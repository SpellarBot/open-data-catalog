# Work Orders Completed: El Pueblo Historical Monument

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/work-orders-completed-el-pueblo-historical-monument) |
| Metadata | [Link](https://data.lacity.org/api/views/nsdh-74d5) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/nsdh-74d5/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/nsdh-74d5/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | nsdh-74d5 |
| Name | Work Orders Completed: El Pueblo Historical Monument |
| Attribution | El Pueblo Historical Monument |
| Category | A Livable and Sustainable City |
| Tags | historic buildings |
| Created | 2014-05-30T23:29:38Z |
| Publication Date | 2017-03-20T22:28:55Z |

## Description

Work orders are maintenance and repair items in and around the El Pueblo Historical Monument historic monument.

## Columns

```ls
| Included | Schema Type    | Field Name            | Name                  | Data Type     | Render Type   |
| ======== | ============== | ===================== | ===================== | ============= | ============= |
| Yes      | time           | month                 | Month                 | calendar_date | calendar_date |
| Yes      | numeric metric | work_order_submitted  | Work Order Submitted  | number        | number        |
| Yes      | numeric metric | work_orders_completed | Work Orders Completed | number        | number        |
```

## Time Field

```ls
Value = month
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:nsdh-74d5 d:2014-01-01T00:00:00.000Z m:work_orders_completed=35 m:work_order_submitted=35

series e:nsdh-74d5 d:2014-02-01T00:00:00.000Z m:work_orders_completed=38 m:work_order_submitted=46

series e:nsdh-74d5 d:2014-03-01T00:00:00.000Z m:work_orders_completed=42 m:work_order_submitted=56
```

## Meta Commands

```ls
metric m:work_order_submitted p:integer l:"Work Order Submitted" t:dataTypeName=number

metric m:work_orders_completed p:integer l:"Work Orders Completed" t:dataTypeName=number

entity e:nsdh-74d5 l:"Work Orders Completed: El Pueblo Historical Monument" t:attribution="El Pueblo Historical Monument" t:url=https://data.lacity.org/api/views/nsdh-74d5

property e:nsdh-74d5 t:meta.view v:id=nsdh-74d5 v:category="A Livable and Sustainable City" v:attributionLink=http://elpueblo.lacity.org/index.htm v:averageRating=0 v:name="Work Orders Completed: El Pueblo Historical Monument" v:attribution="El Pueblo Historical Monument"

property e:nsdh-74d5 t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:nsdh-74d5 t:meta.view.owner v:id=rz8e-rup2 v:profileImageUrlMedium=/api/users/rz8e-rup2/profile_images/THUMB v:profileImageUrlLarge=/api/users/rz8e-rup2/profile_images/LARGE v:screenName="El Pueblo OpenData" v:profileImageUrlSmall=/api/users/rz8e-rup2/profile_images/TINY v:displayName="El Pueblo OpenData"

property e:nsdh-74d5 t:meta.view.tableauthor v:id=rz8e-rup2 v:profileImageUrlMedium=/api/users/rz8e-rup2/profile_images/THUMB v:profileImageUrlLarge=/api/users/rz8e-rup2/profile_images/LARGE v:screenName="El Pueblo OpenData" v:profileImageUrlSmall=/api/users/rz8e-rup2/profile_images/TINY v:roleName=publisher v:displayName="El Pueblo OpenData"
```

## Top Records

```ls
| month               | work_order_submitted | work_orders_completed | 
| =================== | ==================== | ===================== | 
| 2014-01-01T00:00:00 | 35                   | 35                    | 
| 2014-02-01T00:00:00 | 46                   | 38                    | 
| 2014-03-01T00:00:00 | 56                   | 42                    | 
| 2014-04-01T00:00:00 | 45                   | 24                    | 
| 2014-05-01T00:00:00 | 50                   | 36                    | 
| 2014-06-01T00:00:00 | 41                   | 22                    | 
| 2014-07-01T00:00:00 | 55                   | 31                    | 
| 2014-08-01T00:00:00 | 24                   | 19                    | 
| 2014-09-01T00:00:00 | 45                   | 36                    | 
| 2014-10-01T00:00:00 | 84                   | 52                    | 
```