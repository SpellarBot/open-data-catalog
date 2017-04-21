# Missouri First Reports of Injury by Gender and Age

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/missouri-first-reports-of-injury-by-gender-and-age-1f0f3) |
| Metadata | [Link](https://data.mo.gov/api/views/mcuk-295r) |
| Data: JSON | [100 Rows](https://data.mo.gov/api/views/mcuk-295r/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.mo.gov/api/views/mcuk-295r/rows.csv?max_rows=100) |
| Host | data.mo.gov |
| Id | mcuk-295r |
| Name | Missouri First Reports of Injury by Gender and Age |
| Category | Labor |
| Tags | labor, injury, employment, froi |
| Created | 2012-10-02T20:08:42Z |
| Publication Date | 2013-01-03T20:52:04Z |

## Description

First reports of injury filed by gender and age.

## Columns

```ls
| Included | Schema Type    | Field Name | Name     | Data Type | Render Type |
| ======== | ============== | ========== | ======== | ========= | =========== |
| Yes      | series tag     | recordid   | recordid | text      | text        |
| No       |                | year       | year     | number    | number      |
| No       |                | month      | month    | number    | number      |
| Yes      | series tag     | gender     | gender   | text      | text        |
| Yes      | numeric metric | missing    | missing  | number    | number      |
| No       |                | _2         | 10-15    | number    | number      |
| No       |                | _7         | 16-19    | number    | number      |
| Yes      | numeric metric | 2_1        | 20-29    | number    | number      |
| No       |                | _6         | 30-39    | number    | number      |
| No       |                | _3         | 40-49    | number    | number      |
| No       |                | _5         | 50-59    | number    | number      |
| Yes      | numeric metric | 2_2        | 60-69    | number    | number      |
| No       |                | _4         | 70-79    | number    | number      |
| Yes      | numeric metric | 1_1_1      | 80-89    | number    | number      |
```

## Time Field

```ls
Value = year-month
Format & Zone = yyyy-MM
```

## Series Fields

```ls
Excluded Fields = _2,_7,_6,_3,_5,_4,year,month
```

## Data Commands

```ls
series e:mcuk-295r d:2002-07-01T00:00:00.000Z t:gender=FEMALE t:recordid=72002-FEMALE m:2_1=1096 m:missing=62 m:2_2=228 m:1_1_1=6

series e:mcuk-295r d:2008-06-01T00:00:00.000Z t:gender=MALE t:recordid=62008-MALE m:2_1=1527 m:missing=67 m:2_2=347 m:1_1_1=5

series e:mcuk-295r d:2001-07-01T00:00:00.000Z t:gender=MALE t:recordid=72001-MALE m:2_1=2182 m:missing=136 m:2_2=303 m:1_1_1=5
```

## Meta Commands

```ls
metric m:missing p:integer l:missing t:dataTypeName=number

metric m:2_1 p:integer l:20-29 t:dataTypeName=number

metric m:2_2 p:integer l:60-69 t:dataTypeName=number

metric m:1_1_1 p:integer l:80-89 t:dataTypeName=number

entity e:mcuk-295r l:"Missouri First Reports of Injury by Gender and Age" t:url=https://data.mo.gov/api/views/mcuk-295r

property e:mcuk-295r t:meta.view v:id=mcuk-295r v:category=Labor v:averageRating=0 v:name="Missouri First Reports of Injury by Gender and Age"

property e:mcuk-295r t:meta.view.owner v:id=fq9d-b9a3 v:screenName=Jolene v:displayName=Jolene

property e:mcuk-295r t:meta.view.tableauthor v:id=fq9d-b9a3 v:screenName=Jolene v:roleName=editor v:displayName=Jolene
```

## Top Records

```ls
| recordid      | year | month | gender  | missing | _2 | _7  | 2_1  | _6   | _3   | _5   | 2_2 | _4 | 1_1_1 | 
| ============= | ==== | ===== | ======= | ======= | == | === | ==== | ==== | ==== | ==== | === | == | ===== | 
| 72002-FEMALE  | 2002 | 7     | FEMALE  | 62      | 6  | 269 | 1096 | 1224 | 1336 | 815  | 228 | 31 | 6     | 
| 62008-MALE    | 2008 | 6     | MALE    | 67      | 2  | 232 | 1527 | 1404 | 1514 | 1101 | 347 | 40 | 5     | 
| 72001-MALE    | 2001 | 7     | MALE    | 136     | 13 | 460 | 2182 | 2267 | 2032 | 1087 | 303 | 38 | 5     | 
| 42003-MISSING | 2003 | 4     | MISSING |         |    |     | 5    | 4    | 6    | 4    |     |    |       | 
| 42002-MISSING | 2002 | 4     | MISSING |         |    |     | 2    | 7    | 4    | 2    | 1   |    |       | 
| 112002-MALE   | 2002 | 11    | MALE    | 82      |    | 233 | 1634 | 1753 | 1645 | 1030 | 310 | 38 | 3     | 
| 72003-MISSING | 2003 | 7     | MISSING |         |    | 1   | 8    | 12   | 6    | 3    | 1   |    |       | 
| 62009-FEMALE  | 2009 | 6     | FEMALE  | 50      | 1  | 117 | 911  | 840  | 966  | 922  | 338 | 48 | 7     | 
| 22008-FEMALE  | 2008 | 2     | FEMALE  | 56      | 1  | 117 | 896  | 876  | 1129 | 1082 | 343 | 49 | 3     | 
| 72001-MISSING | 2001 | 7     | MISSING |         |    | 1   | 5    | 13   | 7    | 3    | 3   |    |       | 
```