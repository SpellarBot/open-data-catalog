# Projected Population 2010-2040 - Males By Age Groups

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/projected-population-2010-2040-males-by-age-groups-4ae57) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/z4hj-p6bi) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/z4hj-p6bi/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/z4hj-p6bi/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | z4hj-p6bi |
| Name | Projected Population 2010-2040 - Males By Age Groups |
| Attribution | Department of City Planning (DCP) |
| Category | City Government |
| Tags | projected population 2010-2040 - males by age groups, dcp, 2010, 2040 |
| Created | 2011-10-25T18:03:11Z |
| Publication Date | 2014-04-22T20:30:11Z |

## Description

Projected male New York City population for five intervals from 2010 through 2040 by borough, broken down by 18 age cohorts. (Age groups may not add up to the total due to rounding.)

## Columns

```ls
| Included | Schema Type | Field Name | Name | Data Type | Render Type |
| ======== | =========== | ========== | ==== | ========= | =========== |
| Yes      | series tag  | boro       | Boro | text      | text        |
| Yes      | series tag  | age        | Age  | text      | text        |
| No       |             | _1         | 2010 | number    | number      |
| No       |             | _2         | 2015 | number    | number      |
| No       |             | _3         | 2020 | number    | number      |
| No       |             | _4         | 2025 | number    | number      |
| No       |             | _5         | 2030 | number    | number      |
| No       |             | _6         | 2035 | number    | number      |
| No       |             | _7         | 2040 | number    | number      |
```

## Time Field

```ls
Value = 2010
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = _1,_2,_3,_4,_5,_6,_7
```

## Data Commands

```ls
series e:z4hj-p6bi d:2010-01-01T00:00:00.000Z t:boro="NYC Total" t:age=0-4 m:row_number.z4hj-p6bi=1

series e:z4hj-p6bi d:2010-01-01T00:00:00.000Z t:boro="NYC Total" t:age=15-19 m:row_number.z4hj-p6bi=2

series e:z4hj-p6bi d:2010-01-01T00:00:00.000Z t:boro="NYC Total" t:age=20-24 m:row_number.z4hj-p6bi=3
```

## Meta Commands

```ls
metric m:row_number.z4hj-p6bi p:long l:"Row Number"

entity e:z4hj-p6bi l:"Projected Population 2010-2040 - Males By Age Groups" t:attribution="Department of City Planning (DCP)" t:url=https://data.cityofnewyork.us/api/views/z4hj-p6bi

property e:z4hj-p6bi t:meta.view v:id=z4hj-p6bi v:category="City Government" v:averageRating=0 v:name="Projected Population 2010-2040 - Males By Age Groups" v:attribution="Department of City Planning (DCP)"

property e:z4hj-p6bi t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:z4hj-p6bi t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| boro      | age   | _1     | _2     | _3     | _4     | _5     | _6     | _7     | 
| ========= | ===== | ====== | ====== | ====== | ====== | ====== | ====== | ====== | 
| NYC Total | 0-4   | 266620 | 273866 | 279271 | 280079 | 277569 | 276607 | 279627 | 
| NYC Total | 15-19 | 273907 | 256773 | 250227 | 263895 | 272209 | 277720 | 278013 | 
| NYC Total | 20-24 | 315485 | 315676 | 296613 | 289880 | 306091 | 315252 | 321586 | 
| NYC Total | 25-29 | 350994 | 371517 | 369892 | 347023 | 339052 | 359228 | 370020 | 
| NYC Total | 30-34 | 323227 | 340094 | 361303 | 360248 | 337983 | 329679 | 348946 | 
| NYC Total | 35-39 | 288181 | 294794 | 311051 | 331189 | 330845 | 310038 | 302069 | 
| NYC Total | 40-44 | 276953 | 264822 | 271603 | 286890 | 305492 | 305302 | 285997 | 
| NYC Total | 45-49 | 273136 | 256691 | 246329 | 253111 | 267292 | 284304 | 284129 | 
| NYC Total | 50-54 | 256915 | 259971 | 245016 | 235719 | 242232 | 255605 | 271631 | 
| NYC Total | 55-59 | 220408 | 227629 | 231153 | 218510 | 210206 | 215873 | 227539 | 
```