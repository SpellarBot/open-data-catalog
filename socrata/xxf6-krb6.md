# Projected Population 2010-2040 - Females By Age Groups

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/projected-population-2010-2040-females-by-age-groups-6d2bd) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/xxf6-krb6) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/xxf6-krb6/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/xxf6-krb6/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | xxf6-krb6 |
| Name | Projected Population 2010-2040 - Females By Age Groups |
| Attribution | Department of City Planning (DCP) |
| Category | City Government |
| Tags | projected population 2010-2040 - females by age groups, dcp, 2010, 2040 |
| Created | 2011-10-25T17:57:17Z |
| Publication Date | 2014-04-22T20:30:32Z |

## Description

Projected female New York City population for five intervals from 2010 through 2040 by borough, broken down by 18 age cohorts. (Age groups may not add up to the total due to rounding.)

## Columns

```ls
| Included | Schema Type | Field Name | Name    | Data Type | Render Type |
| ======== | =========== | ========== | ======= | ========= | =========== |
| Yes      | series tag  | borough    | Borough | text      | text        |
| Yes      | series tag  | age        | Age     | text      | text        |
| No       |             | _1         | 2010    | number    | number      |
| No       |             | _2         | 2015    | number    | number      |
| No       |             | _3         | 2020    | number    | number      |
| No       |             | _4         | 2025    | number    | number      |
| No       |             | _5         | 2030    | number    | number      |
| No       |             | _6         | 2035    | number    | number      |
| No       |             | _7         | 2040    | number    | number      |
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
series e:xxf6-krb6 d:2010-01-01T00:00:00.000Z t:age=0-4 t:borough="NYC Total" m:row_number.xxf6-krb6=1

series e:xxf6-krb6 d:2010-01-01T00:00:00.000Z t:age=15-19 t:borough="NYC Total" m:row_number.xxf6-krb6=2

series e:xxf6-krb6 d:2010-01-01T00:00:00.000Z t:age=20-24 t:borough="NYC Total" m:row_number.xxf6-krb6=3
```

## Meta Commands

```ls
metric m:row_number.xxf6-krb6 p:long l:"Row Number"

entity e:xxf6-krb6 l:"Projected Population 2010-2040 - Females By Age Groups" t:attribution="Department of City Planning (DCP)" t:url=https://data.cityofnewyork.us/api/views/xxf6-krb6

property e:xxf6-krb6 t:meta.view v:id=xxf6-krb6 v:category="City Government" v:averageRating=0 v:name="Projected Population 2010-2040 - Females By Age Groups" v:attribution="Department of City Planning (DCP)"

property e:xxf6-krb6 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:xxf6-krb6 t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| borough   | age   | _1     | _2     | _3     | _4     | _5     | _6     | _7     | 
| ========= | ===== | ====== | ====== | ====== | ====== | ====== | ====== | ====== | 
| NYC Total | 0-4   | 255370 | 261343 | 266507 | 267257 | 264857 | 263916 | 266799 | 
| NYC Total | 15-19 | 265937 | 249010 | 242305 | 255403 | 262815 | 268342 | 268737 | 
| NYC Total | 20-24 | 331998 | 330399 | 309590 | 301803 | 319162 | 328476 | 335817 | 
| NYC Total | 25-29 | 385111 | 398879 | 394064 | 368801 | 359143 | 381209 | 392737 | 
| NYC Total | 30-34 | 344430 | 367632 | 382613 | 380020 | 355701 | 345818 | 366540 | 
| NYC Total | 35-39 | 304118 | 316445 | 338543 | 353060 | 352119 | 329199 | 319830 | 
| NYC Total | 40-44 | 294872 | 285275 | 298025 | 319295 | 332656 | 332215 | 310496 | 
| NYC Total | 45-49 | 297137 | 279307 | 271339 | 284405 | 304431 | 316488 | 316385 | 
| NYC Total | 50-54 | 289289 | 292103 | 275581 | 268603 | 281583 | 300981 | 312533 | 
| NYC Total | 55-59 | 259253 | 266368 | 270086 | 255809 | 249368 | 261179 | 278851 | 
```