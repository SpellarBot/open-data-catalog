# Projected Population 2010-2040 - Total By Age Groups

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/projected-population-2010-2040-total-by-age-groups-1f46d) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/97pn-acdf) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/97pn-acdf/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/97pn-acdf/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 97pn-acdf |
| Name | Projected Population 2010-2040 - Total By Age Groups |
| Attribution | Department of City Planning (DCP) |
| Category | City Government |
| Tags | projected population 2000-2040 - total by age groups, dcp, 2010, 2040 |
| Created | 2011-10-25T18:11:21Z |
| Publication Date | 2014-04-22T20:29:48Z |

## Description

Projected total New York City population for five intervals from 2010 through 2040 by Borough, broken down by 18 age cohorts. (Age groups may not add up to the total due to rounding.)

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
series e:97pn-acdf d:2010-01-01T00:00:00.000Z t:age=0-4 t:borough="NYC Total" m:row_number.97pn-acdf=1

series e:97pn-acdf d:2010-01-01T00:00:00.000Z t:age=15-19 t:borough="NYC Total" m:row_number.97pn-acdf=2

series e:97pn-acdf d:2010-01-01T00:00:00.000Z t:age=20-24 t:borough="NYC Total" m:row_number.97pn-acdf=3
```

## Meta Commands

```ls
metric m:row_number.97pn-acdf p:long l:"Row Number"

entity e:97pn-acdf l:"Projected Population 2010-2040 - Total By Age Groups" t:attribution="Department of City Planning (DCP)" t:url=https://data.cityofnewyork.us/api/views/97pn-acdf

property e:97pn-acdf t:meta.view v:id=97pn-acdf v:category="City Government" v:averageRating=0 v:name="Projected Population 2010-2040 - Total By Age Groups" v:attribution="Department of City Planning (DCP)"

property e:97pn-acdf t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:97pn-acdf t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| borough   | age   | _1     | _2     | _3     | _4     | _5     | _6     | _7     | 
| ========= | ===== | ====== | ====== | ====== | ====== | ====== | ====== | ====== | 
| NYC Total | 0-4   | 521990 | 535209 | 545778 | 547336 | 542426 | 540523 | 546426 | 
| NYC Total | 15-19 | 539844 | 505783 | 492532 | 519298 | 535024 | 546062 | 546750 | 
| NYC Total | 20-24 | 647483 | 646075 | 606203 | 591683 | 625253 | 643728 | 657403 | 
| NYC Total | 25-29 | 736105 | 770396 | 763956 | 715824 | 698195 | 740437 | 762757 | 
| NYC Total | 30-34 | 667657 | 707726 | 743916 | 740268 | 693684 | 675497 | 715486 | 
| NYC Total | 35-39 | 592299 | 611239 | 649594 | 684249 | 682964 | 639237 | 621899 | 
| NYC Total | 40-44 | 571825 | 550097 | 569628 | 606185 | 638148 | 637517 | 596493 | 
| NYC Total | 45-49 | 570273 | 535998 | 517668 | 537516 | 571723 | 600792 | 600514 | 
| NYC Total | 50-54 | 546204 | 552074 | 520597 | 504322 | 523815 | 556586 | 584164 | 
| NYC Total | 55-59 | 479661 | 493997 | 501239 | 474319 | 459574 | 477052 | 506390 | 
```