# Missouri Monthly Unemployment Claims By Age

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/missouri-monthly-unemployment-claims-by-age-d20a7) |
| Metadata | [Link](https://data.mo.gov/api/views/5tqh-2x4m) |
| Data: JSON | [100 Rows](https://data.mo.gov/api/views/5tqh-2x4m/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.mo.gov/api/views/5tqh-2x4m/rows.csv?max_rows=100) |
| Host | data.mo.gov |
| Id | 5tqh-2x4m |
| Name | Missouri Monthly Unemployment Claims By Age |
| Category | Labor |
| Tags | unemployment, labor, employment |
| Created | 2012-08-30T14:34:49Z |
| Publication Date | 2017-04-10T13:01:40Z |

## Description

Demographic data of Missouri Unemployment claims by age

## Columns

```ls
| Included | Schema Type    | Field Name | Name      | Data Type     | Render Type   |
| ======== | ============== | ========== | ========= | ============= | ============= |
| Yes      | series tag     | record_id  | Record ID | text          | text          |
| Yes      | time           | date       | Date      | calendar_date | calendar_date |
| Yes      | numeric metric | ina        | INA       | number        | number        |
| No       |                | _6         | <22       | number        | number        |
| Yes      | numeric metric | 2_1        | 22-24     | number        | number        |
| No       |                | _4         | 25-34     | number        | number        |
| No       |                | _2         | 35-44     | number        | number        |
| Yes      | numeric metric | 1_1_1      | 45-54     | number        | number        |
| No       |                | _3         | 55-59     | number        | number        |
| Yes      | numeric metric | 2_2        | 60-64     | number        | number        |
| No       |                | _5         | >=65      | number        | number        |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = _6,_4,_2,_3,_5
```

## Data Commands

```ls
series e:5tqh-2x4m d:2011-08-01T00:00:00.000Z t:record_id=08012011 m:2_1=3558 m:2_2=3879 m:1_1_1=15232 m:ina=56

series e:5tqh-2x4m d:2011-07-01T00:00:00.000Z t:record_id=07012011 m:2_1=3768 m:2_2=4291 m:1_1_1=16600 m:ina=58

series e:5tqh-2x4m d:2011-09-01T00:00:00.000Z t:record_id=09012011 m:2_1=3170 m:2_2=3158 m:1_1_1=13051 m:ina=51
```

## Meta Commands

```ls
metric m:ina p:integer l:INA d:"Information Not Available" t:dataTypeName=number

metric m:2_1 p:integer l:22-24 t:dataTypeName=number

metric m:1_1_1 p:integer l:45-54 t:dataTypeName=number

metric m:2_2 p:integer l:60-64 t:dataTypeName=number

entity e:5tqh-2x4m l:"Missouri Monthly Unemployment Claims By Age" t:url=https://data.mo.gov/api/views/5tqh-2x4m

property e:5tqh-2x4m t:meta.view v:id=5tqh-2x4m v:category=Labor v:averageRating=0 v:name="Missouri Monthly Unemployment Claims By Age"

property e:5tqh-2x4m t:meta.view.owner v:id=eb88-upz2 v:screenName=DOLIR v:displayName=DOLIR

property e:5tqh-2x4m t:meta.view.tableauthor v:id=eb88-upz2 v:screenName=DOLIR v:roleName=editor v:displayName=DOLIR
```

## Top Records

```ls
| record_id | date                | ina | _6   | 2_1  | _4    | _2    | 1_1_1 | _3   | 2_2  | _5   | 
| ========= | =================== | === | ==== | ==== | ===== | ===== | ===== | ==== | ==== | ==== | 
| 08012011  | 2011-08-01T00:00:00 | 56  | 1665 | 3558 | 15074 | 13835 | 15232 | 5859 | 3879 | 2906 | 
| 07012011  | 2011-07-01T00:00:00 | 58  | 1609 | 3768 | 15999 | 14954 | 16600 | 6318 | 4291 | 3224 | 
| 09012011  | 2011-09-01T00:00:00 | 51  | 1639 | 3170 | 13500 | 11949 | 13051 | 4987 | 3158 | 1976 | 
| 02012012  | 2012-02-01T00:00:00 | 51  | 1400 | 3702 | 15728 | 14101 | 15917 | 6131 | 3843 | 3092 | 
| 10012011  | 2011-10-01T00:00:00 | 58  | 1578 | 3120 | 12590 | 11166 | 12481 | 4681 | 2862 | 1818 | 
| 11012011  | 2011-11-01T00:00:00 | 53  | 2142 | 3799 | 14715 | 12926 | 14104 | 5313 | 3175 | 2109 | 
| 12012011  | 2011-12-01T00:00:00 | 64  | 2036 | 3662 | 14487 | 12946 | 14113 | 5310 | 3119 | 2188 | 
| 01012012  | 2012-01-01T00:00:00 | 50  | 1466 | 3836 | 16666 | 15051 | 16808 | 6483 | 4152 | 3469 | 
| 03012012  | 2012-03-01T00:00:00 | 47  | 1178 | 3084 | 13401 | 12476 | 14052 | 5370 | 3390 | 2647 | 
| 06012012  | 2012-06-01T00:00:00 | 39  | 1119 | 2569 | 11380 | 11266 | 12841 | 5115 | 3220 | 2611 | 
```