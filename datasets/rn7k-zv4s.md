# IDPH Deaths, by County, by Demographics, 2008

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/idph-deaths-by-county-by-demographics-2008-697b8) |
| Metadata | [Link](https://data.illinois.gov/api/views/rn7k-zv4s) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/rn7k-zv4s/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/rn7k-zv4s/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | rn7k-zv4s |
| Name | IDPH Deaths, by County, by Demographics, 2008 |
| Attribution | Illinois Center for Health Statistics |
| Category | Public Health |
| Tags | death |
| Created | 2012-01-17T19:18:52Z |
| Publication Date | 2013-08-26T18:35:36Z |

## Description

Illinois Demographics of Deaths, 2008 Note: The sum of certain variables may not equal the total due to unknown geography and/or demographics.

## Columns

```ls
| Included | Schema Type    | Field Name      | Name            | Data Type | Render Type |
| ======== | ============== | =============== | =============== | ========= | =========== |
| Yes      | series tag     | resident_county | Resident County | text      | text        |
| Yes      | numeric metric | total_deaths    | Total Deaths    | number    | number      |
| Yes      | numeric metric | male            | Male            | number    | number      |
| Yes      | numeric metric | female          | Female          | number    | number      |
| Yes      | numeric metric | white           | White           | number    | number      |
| Yes      | numeric metric | black           | Black           | number    | number      |
| Yes      | numeric metric | other           | Other           | number    | number      |
| Yes      | numeric metric | hispanic        | Hispanic        | number    | number      |
| Yes      | numeric metric | _yr             | < 1 yr          | number    | number      |
| No       |                | _1              | 1 - 14          | number    | number      |
| No       |                | _2              | 15 - 24         | number    | number      |
| No       |                | _3              | 25 - 44         | number    | number      |
| No       |                | _4              | 45 - 64         | number    | number      |
| No       |                | _5              | 65 - 84         | number    | number      |
| No       |                | _6              | 85 +            | number    | number      |
```

## Time Field

```ls
Value = 2008
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = _1,_2,_3,_4,_5,_6
```

## Data Commands

```ls
series e:rn7k-zv4s d:2008-01-01T00:00:00.000Z t:resident_county=Adams m:_yr=6 m:other=4 m:female=391 m:male=452 m:white=823 m:total_deaths=843 m:hispanic=3 m:black=16

series e:rn7k-zv4s d:2008-01-01T00:00:00.000Z t:resident_county=Alexander m:_yr=1 m:other=1 m:female=51 m:male=60 m:white=74 m:total_deaths=111 m:hispanic=1 m:black=36

series e:rn7k-zv4s d:2008-01-01T00:00:00.000Z t:resident_county=Bond m:_yr=1 m:other=0 m:female=70 m:male=86 m:white=150 m:total_deaths=156 m:hispanic=0 m:black=6
```

## Meta Commands

```ls
metric m:total_deaths p:integer l:"Total Deaths" t:dataTypeName=number

metric m:male p:integer l:Male t:dataTypeName=number

metric m:female p:integer l:Female t:dataTypeName=number

metric m:white p:integer l:White t:dataTypeName=number

metric m:black p:integer l:Black t:dataTypeName=number

metric m:other p:integer l:Other t:dataTypeName=number

metric m:hispanic p:integer l:Hispanic t:dataTypeName=number

metric m:_yr p:integer l:"< 1 yr" t:dataTypeName=number

entity e:rn7k-zv4s l:"IDPH Deaths, by County, by Demographics, 2008" t:attribution="Illinois Center for Health Statistics" t:url=https://data.illinois.gov/api/views/rn7k-zv4s

property e:rn7k-zv4s t:meta.view v:id=rn7k-zv4s v:category="Public Health" v:attributionLink=http://www.idph.state.il.us/health/statshome.htm v:averageRating=0 v:name="IDPH Deaths, by County, by Demographics, 2008" v:attribution="Illinois Center for Health Statistics"

property e:rn7k-zv4s t:meta.view.owner v:id=e75b-y6hv v:screenName=Jenny v:displayName=Jenny

property e:rn7k-zv4s t:meta.view.tableauthor v:id=e75b-y6hv v:screenName=Jenny v:roleName=publisher v:displayName=Jenny
```

## Top Records

```ls
| resident_county | total_deaths | male | female | white | black | other | hispanic | _yr | _1 | _2 | _3 | _4  | _5  | _6  | 
| =============== | ============ | ==== | ====== | ===== | ===== | ===== | ======== | === | == | == | == | === | === | === | 
| Adams           | 843          | 452  | 391    | 823   | 16    | 4     | 3        | 6   | 2  | 4  | 21 | 114 | 362 | 334 | 
| Alexander       | 111          | 60   | 51     | 74    | 36    | 1     | 1        | 1   | 0  | 0  | 6  | 21  | 55  | 28  | 
| Bond            | 156          | 86   | 70     | 150   | 6     | 0     | 0        | 1   | 1  | 0  | 6  | 28  | 75  | 45  | 
| Boone           | 365          | 181  | 184    | 358   | 4     | 3     | 14       | 5   | 3  | 3  | 16 | 65  | 181 | 92  | 
| Brown           | 56           | 28   | 28     | 55    | 1     | 0     | 0        | 0   | 0  | 1  | 2  | 10  | 25  | 18  | 
| Bureau          | 397          | 185  | 212    | 394   | 1     | 2     | 3        | 0   | 3  | 3  | 12 | 60  | 168 | 151 | 
| Calhoun         | 71           | 30   | 41     | 71    | 0     | 0     | 0        | 0   | 0  | 1  | 1  | 6   | 34  | 29  | 
| Carroll         | 195          | 106  | 89     | 192   | 3     | 0     | 1        | 2   | 0  | 3  | 5  | 30  | 89  | 66  | 
| Cass            | 166          | 78   | 88     | 166   | 0     | 0     | 1        | 1   | 0  | 1  | 7  | 24  | 70  | 63  | 
| Champaign       | 1147         | 554  | 593    | 980   | 154   | 13    | 7        | 15  | 4  | 20 | 52 | 199 | 468 | 389 | 
```