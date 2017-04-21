# Austin Water - Gallons of Wastewater Treated

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/austin-water-gallons-of-wastewater-treated) |
| Metadata | [Link](https://data.austintexas.gov/api/views/vuwy-s6qv) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/vuwy-s6qv/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/vuwy-s6qv/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | vuwy-s6qv |
| Name | Austin Water - Gallons of Wastewater Treated |
| Attribution | Austin Water |
| Category | Utility |
| Tags | aw, wastewater, treated |
| Created | 2015-08-31T22:30:29Z |
| Publication Date | 2016-11-21T15:23:19Z |

## Description

Millions of gallons of wastewater treated by year, month and plant.

## Columns

```ls
| Included | Schema Type    | Field Name    | Name          | Data Type | Render Type |
| ======== | ============== | ============= | ============= | ========= | =========== |
| No       |                | year          | Year          | number    | text        |
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
series e:vuwy-s6qv d:2011-10-01T00:00:00.000Z t:plant="SAR Plant" t:type_of_water=Wastewater m:mg_treated=1282.78

series e:vuwy-s6qv d:2011-10-01T00:00:00.000Z t:plant="Walnut Creek Plant" t:type_of_water=Wastewater m:mg_treated=1570.83

series e:vuwy-s6qv d:2011-11-01T00:00:00.000Z t:plant="SAR Plant" t:type_of_water=Wastewater m:mg_treated=1211.05
```

## Meta Commands

```ls
metric m:mg_treated p:float l:"MG Treated" t:dataTypeName=number

entity e:vuwy-s6qv l:"Austin Water - Gallons of Wastewater Treated" t:attribution="Austin Water" t:url=https://data.austintexas.gov/api/views/vuwy-s6qv

property e:vuwy-s6qv t:meta.view v:id=vuwy-s6qv v:category=Utility v:attributionLink=http://www.austintexas.gov/department/water v:averageRating=0 v:name="Austin Water - Gallons of Wastewater Treated" v:attribution="Austin Water"

property e:vuwy-s6qv t:meta.view.license v:name="Public Domain"

property e:vuwy-s6qv t:meta.view.owner v:id=4786-56ku v:screenName="Patricia Genty Andrade" v:displayName="Patricia Genty Andrade"

property e:vuwy-s6qv t:meta.view.tableauthor v:id=4786-56ku v:screenName="Patricia Genty Andrade" v:roleName=editor v:displayName="Patricia Genty Andrade"
```

## Top Records

```ls
| year | month | plant              | type_of_water | mg_treated | 
| ==== | ===== | ================== | ============= | ========== | 
| 2011 | Oct   | SAR Plant          | Wastewater    | 1282.78    | 
| 2011 | Oct   | Walnut Creek Plant | Wastewater    | 1570.83    | 
| 2011 | Nov   | SAR Plant          | Wastewater    | 1211.05    | 
| 2011 | Nov   | Walnut Creek Plant | Wastewater    | 1603.26    | 
| 2011 | Dec   | SAR Plant          | Wastewater    | 1315.69    | 
| 2011 | Dec   | Walnut Creek Plant | Wastewater    | 1880.30    | 
| 2012 | Jan   | SAR Plant          | Wastewater    | 1386.29    | 
| 2012 | Jan   | Walnut Creek Plant | Wastewater    | 1806.68    | 
| 2012 | Feb   | SAR Plant          | Wastewater    | 1455.53    | 
| 2012 | Feb   | Walnut Creek Plant | Wastewater    | 1726.62    | 
```