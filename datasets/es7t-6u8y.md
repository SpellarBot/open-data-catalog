# Litter Basket Inventory

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/litter-basket-inventory) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/es7t-6u8y) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/es7t-6u8y/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/es7t-6u8y/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | es7t-6u8y |
| Name | Litter Basket Inventory |
| Attribution | Department of Sanitation (DSNY) |
| Category | Environment |
| Created | 2015-12-11T19:50:21Z |
| Publication Date | 2015-12-14T21:43:58Z |

## Description

Locations and types of litter baskets and public space recycling baskets as of November 2015.

## Columns

```ls
| Included | Schema Type | Field Name  | Name       | Data Type | Render Type |
| ======== | =========== | =========== | ========== | ========= | =========== |
| No       | time        | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag  | baskettype  | BasketType | text      | text        |
| No       |             | x           | x          | number    | number      |
| No       |             | y           | y          | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = x,y
```

## Data Commands

```ls
series e:es7t-6u8y d:2015-12-11T12:46:32.000Z t:baskettype=S m:row_number.es7t-6u8y=1

series e:es7t-6u8y d:2015-12-11T12:46:32.000Z t:baskettype=S m:row_number.es7t-6u8y=2

series e:es7t-6u8y d:2015-12-11T12:46:32.000Z t:baskettype=S m:row_number.es7t-6u8y=3
```

## Meta Commands

```ls
metric m:row_number.es7t-6u8y p:long l:"Row Number"

entity e:es7t-6u8y l:"Litter Basket Inventory" t:attribution="Department of Sanitation (DSNY)" t:url=https://data.cityofnewyork.us/api/views/es7t-6u8y

property e:es7t-6u8y t:meta.view v:id=es7t-6u8y v:category=Environment v:averageRating=0 v:name="Litter Basket Inventory" v:attribution="Department of Sanitation (DSNY)"

property e:es7t-6u8y t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:es7t-6u8y t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | baskettype | x            | y           | 
| =========== | ========== | ============ | =========== | 
| 1449837992  | S          | -73.91681942 | 40.65465237 | 
| 1449837992  | S          | -73.95419618 | 40.73104188 | 
| 1449837992  | S          | -73.91127359 | 40.65723743 | 
| 1449837992  | S          | -73.94864898 | 40.71099129 | 
| 1449837992  | S          | -73.91730814 | 40.65466421 | 
| 1449837992  | S          | -73.94238297 | 40.71157956 | 
| 1449837992  | S          | -73.91397793 | 40.671696   | 
| 1449837992  | S          | -73.95443574 | 40.73247036 | 
| 1449837992  | S          | -73.91946448 | 40.66082169 | 
| 1449837992  | S          | -73.94355547 | 40.7081872  | 
```