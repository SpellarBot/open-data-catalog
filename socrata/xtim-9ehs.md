# Austin Water - Gallons of Water Treated

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/austin-water-gallons-of-water-treated) |
| Metadata | [Link](https://data.austintexas.gov/api/views/xtim-9ehs) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/xtim-9ehs/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/xtim-9ehs/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | xtim-9ehs |
| Name | Austin Water - Gallons of Water Treated |
| Attribution | Austin Water |
| Category | Utility |
| Tags | aw, water, treated |
| Created | 2015-08-31T22:26:57Z |
| Publication Date | 2016-11-21T15:20:40Z |

## Description

Millions of gallons of water treated by year, month and Plant.

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
series e:xtim-9ehs d:2011-10-01T00:00:00.000Z t:plant=Davis t:type_of_water=Water m:mg_treated=2512.94

series e:xtim-9ehs d:2011-10-01T00:00:00.000Z t:plant=Ullrich t:type_of_water=Water m:mg_treated=2129.12

series e:xtim-9ehs d:2011-11-01T00:00:00.000Z t:plant=Davis t:type_of_water=Water m:mg_treated=2405.53
```

## Meta Commands

```ls
metric m:mg_treated p:float l:"MG Treated" t:dataTypeName=number

entity e:xtim-9ehs l:"Austin Water - Gallons of Water Treated" t:attribution="Austin Water" t:url=https://data.austintexas.gov/api/views/xtim-9ehs

property e:xtim-9ehs t:meta.view v:id=xtim-9ehs v:category=Utility v:attributionLink=http://www.austintexas.gov/department/water v:averageRating=0 v:name="Austin Water - Gallons of Water Treated" v:attribution="Austin Water"

property e:xtim-9ehs t:meta.view.license v:name="Public Domain"

property e:xtim-9ehs t:meta.view.owner v:id=4786-56ku v:screenName="Patricia Genty Andrade" v:displayName="Patricia Genty Andrade"

property e:xtim-9ehs t:meta.view.tableauthor v:id=4786-56ku v:screenName="Patricia Genty Andrade" v:roleName=editor v:displayName="Patricia Genty Andrade"
```

## Top Records

```ls
| year | month | plant                   | type_of_water | mg_treated | 
| ==== | ===== | ======================= | ============= | ========== | 
| 2011 | Oct   | Davis                   | Water         | 2512.94    | 
| 2011 | Oct   | Ullrich                 | Water         | 2129.12    | 
| 2011 | Oct   | Water Treatment Plant 4 | Water         |            | 
| 2011 | Nov   | Davis                   | Water         | 2405.53    | 
| 2011 | Nov   | Ullrich                 | Water         | 1387.45    | 
| 2011 | Nov   | Water Treatment Plant 4 | Water         |            | 
| 2011 | Dec   | Davis                   | Water         | 1646.50    | 
| 2011 | Dec   | Ullrich                 | Water         | 1558.34    | 
| 2011 | Dec   | Water Treatment Plant 4 | Water         |            | 
| 2012 | Jan   | Davis                   | Water         | 1480.63    | 
```