# Tax Lien Sale Lists

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/tax-lien-sale-lists) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/9rz4-mjek) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/9rz4-mjek/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/9rz4-mjek/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 9rz4-mjek |
| Name | Tax Lien Sale Lists |
| Attribution | Department of Finance (DOF) |
| Category | City Government |
| Created | 2016-03-04T23:32:00Z |
| Publication Date | 2016-09-06T22:38:15Z |

## Description

Properties with tax and/or water liens that are potentially eligible to be included in the next lien sale.

## Columns

```ls
| Included | Schema Type    | Field Name       | Name             | Data Type     | Render Type   |
| ======== | ============== | ================ | ================ | ============= | ============= |
| Yes      | time           | month            | Month            | calendar_date | calendar_date |
| Yes      | numeric metric | borough          | Borough          | number        | number        |
| Yes      | series tag     | block            | Block            | text          | number        |
| Yes      | series tag     | lot              | Lot              | text          | number        |
| Yes      | series tag     | tax_class_code   | Tax Class Code   | text          | number        |
| Yes      | series tag     | building_class   | Building Class   | text          | text          |
| Yes      | numeric metric | community_board  | Community Board  | number        | number        |
| Yes      | series tag     | council_district | Council District | text          | number        |
| Yes      | series tag     | house_number     | House Number     | text          | text          |
| Yes      | series tag     | street_name      | Street Name      | text          | text          |
| Yes      | series tag     | zip_code         | Zip Code         | text          | text          |
| Yes      | series tag     | water_debt_only  | Water Debt Only  | text          | text          |
```

## Time Field

```ls
Value = month
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:9rz4-mjek d:2016-03-01T00:00:00.000Z t:water_debt_only=YES t:house_number=22 t:zip_code=10004 t:street_name="BEAVER STREET" t:lot=11 t:block=11 t:council_district=1 t:building_class=K4 t:tax_class_code=4 m:borough=1 m:community_board=101

series e:9rz4-mjek d:2016-03-01T00:00:00.000Z t:water_debt_only=NO t:house_number=20 t:zip_code=10004 t:street_name="WEST STREET" t:lot=1285 t:block=15 t:council_district=3 t:building_class=R4 t:tax_class_code=2 m:borough=1 m:community_board=101

series e:9rz4-mjek d:2016-03-01T00:00:00.000Z t:water_debt_only=NO t:house_number=88 t:zip_code=10006 t:street_name="GREENWICH STREET" t:lot=1003 t:block=18 t:council_district=1 t:building_class=R4 t:tax_class_code=2 m:borough=1 m:community_board=101
```

## Meta Commands

```ls
metric m:borough p:integer l:Borough t:dataTypeName=number

metric m:community_board p:integer l:"Community Board" t:dataTypeName=number

entity e:9rz4-mjek l:"Tax Lien Sale Lists" t:attribution="Department of Finance (DOF)" t:url=https://data.cityofnewyork.us/api/views/9rz4-mjek

property e:9rz4-mjek t:meta.view v:id=9rz4-mjek v:category="City Government" v:averageRating=0 v:name="Tax Lien Sale Lists" v:attribution="Department of Finance (DOF)"

property e:9rz4-mjek t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:9rz4-mjek t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| month               | borough | block | lot  | tax_class_code | building_class | community_board | council_district | house_number | street_name      | zip_code | water_debt_only | 
| =================== | ======= | ===== | ==== | ============== | ============== | =============== | ================ | ============ | ================ | ======== | =============== | 
| 2016-03-01T00:00:00 | 1       | 11    | 11   | 4              | K4             | 101             | 1                | 22           | BEAVER STREET    | 10004    | YES             | 
| 2016-03-01T00:00:00 | 1       | 15    | 1285 | 2              | R4             | 101             | 3                | 20           | WEST STREET      | 10004    | NO              | 
| 2016-03-01T00:00:00 | 1       | 18    | 1003 | 2              | R4             | 101             | 1                | 88           | GREENWICH STREET | 10006    | NO              | 
| 2016-03-01T00:00:00 | 1       | 18    | 1305 | 2              | R4             | 101             | 1                | 88           | GREENWICH STREET | 10006    | NO              | 
| 2016-03-01T00:00:00 | 1       | 18    | 1405 | 2              | R4             | 101             | 1                | 88           | GREENWICH STREET | 10006    | NO              | 
| 2016-03-01T00:00:00 | 1       | 18    | 1449 | 2              | R4             | 101             | 1                | 88           | GREENWICH STREET | 10006    | NO              | 
| 2016-03-01T00:00:00 | 1       | 24    | 1005 | 2              | R4             | 101             | 1                | 40           | BROAD STREET     | 10004    | NO              | 
| 2016-03-01T00:00:00 | 1       | 26    | 1272 | 2              | R4             | 101             | 1                | 15           | BROAD STREET     | 10005    | NO              | 
| 2016-03-01T00:00:00 | 1       | 27    | 1055 | 2              | R4             | 101             | 1                | 55           | WALL STREET      | 10005    | NO              | 
| 2016-03-01T00:00:00 | 1       | 28    | 1047 | 2              | R4             | 101             | 1                | 82           | BEAVER STREET    | 10005    | NO              | 
```