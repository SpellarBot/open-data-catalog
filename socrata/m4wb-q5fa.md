# Austin Water - Gallons of Water and Wastewater Treated

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/austin-water-gallons-of-water-and-wastewater-treated) |
| Metadata | [Link](https://data.austintexas.gov/api/views/m4wb-q5fa) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/m4wb-q5fa/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/m4wb-q5fa/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | m4wb-q5fa |
| Name | Austin Water - Gallons of Water and Wastewater Treated |
| Attribution | Austin Water |
| Category | Utility |
| Tags | aw, water, wastewater, treated |
| Created | 2015-08-13T18:43:37Z |
| Publication Date | 2015-08-13T18:53:40Z |

## Description

Millions of gallons of water treated grouped by year, month, plant and water type.

## Columns

```ls
| Included | Schema Type    | Field Name    | Name          | Data Type | Render Type |
| ======== | ============== | ============= | ============= | ========= | =========== |
| No       |                | year          | Year          | number    | number      |
| No       |                | month         | Month         | text      | text        |
| Yes      | series tag     | plant         | Plant         | text      | text        |
| Yes      | series tag     | type_of_water | Type of Water | text      | text        |
| Yes      | numeric metric | mg_treated    | MG Treated    | number    | number      |
```

## Time Field

```ls
Value = year-month
Format & Zone = yyyy-MMM
```

## Series Fields

```ls
Excluded Fields = year,month
```

## Data Commands

```ls
series e:m4wb-q5fa d:2012-01-01T00:00:00.000Z t:plant=Davis t:type_of_water=Water m:mg_treated=1480.63

series e:m4wb-q5fa d:2012-01-01T00:00:00.000Z t:plant=Ullrich t:type_of_water=Water m:mg_treated=1880.21

series e:m4wb-q5fa d:2012-01-01T00:00:00.000Z t:plant="SAR Plant" t:type_of_water=Wastewater m:mg_treated=1386.29
```

## Meta Commands

```ls
metric m:mg_treated p:float l:"MG Treated" t:dataTypeName=number

entity e:m4wb-q5fa l:"Austin Water - Gallons of Water and Wastewater Treated" t:attribution="Austin Water" t:url=https://data.austintexas.gov/api/views/m4wb-q5fa

property e:m4wb-q5fa t:meta.view v:id=m4wb-q5fa v:category=Utility v:attributionLink=http://www.austintexas.gov/department/water v:averageRating=0 v:name="Austin Water - Gallons of Water and Wastewater Treated" v:attribution="Austin Water"

property e:m4wb-q5fa t:meta.view.license v:name="Public Domain"

property e:m4wb-q5fa t:meta.view.owner v:id=4786-56ku v:screenName="Patricia Genty Andrade" v:displayName="Patricia Genty Andrade"

property e:m4wb-q5fa t:meta.view.tableauthor v:id=4786-56ku v:screenName="Patricia Genty Andrade" v:roleName=editor v:displayName="Patricia Genty Andrade"
```

## Top Records

```ls
| year | month | plant              | type_of_water | mg_treated | 
| ==== | ===== | ================== | ============= | ========== | 
| 2012 | Jan   | Davis              | Water         | 1480.63    | 
| 2012 | Jan   | Ullrich            | Water         | 1880.21    | 
| 2012 | Jan   | SAR Plant          | Wastewater    | 1386.29    | 
| 2012 | Jan   | Walnut Creek Plant | Wastewater    | 1806.68    | 
| 2012 | Feb   | Davis              | Water         | 1095.4     | 
| 2012 | Feb   | Ullrich            | Water         | 1913.29    | 
| 2012 | Feb   | SAR Plant          | Wastewater    | 1455.53    | 
| 2012 | Feb   | Walnut Creek Plant | Wastewater    | 1726.62    | 
| 2012 | Mar   | Davis              | Water         | 1476       | 
| 2012 | Mar   | Ullrich            | Water         | 1866.38    | 
```