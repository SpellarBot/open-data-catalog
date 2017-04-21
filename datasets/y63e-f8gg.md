# IDOL Illinois Minimum Wage

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/idol-illinois-minimum-wage-3c2b7) |
| Metadata | [Link](https://data.illinois.gov/api/views/y63e-f8gg) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/y63e-f8gg/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/y63e-f8gg/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | y63e-f8gg |
| Name | IDOL Illinois Minimum Wage |
| Attribution | Illinois Department of Labor |
| Category | Labor |
| Tags | labor, minimum wage, 820 ilcs 105, fair labor standards |
| Created | 2014-03-07T19:56:41Z |
| Publication Date | 2015-06-08T20:43:01Z |

## Description

Guarantees a minimum wage per hour for workers 18 years of age and older.

## Columns

```ls
| Included | Schema Type    | Field Name | Name | Data Type | Render Type |
| ======== | ============== | ========== | ==== | ========= | =========== |
| Yes      | time           | year       | Year | number    | text        |
| Yes      | numeric metric | rate       | Wage | money     | money       |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:y63e-f8gg d:1972-01-01T00:00:00.000Z m:rate=1.4

series e:y63e-f8gg d:1973-01-01T00:00:00.000Z m:rate=1.4

series e:y63e-f8gg d:1974-01-01T00:00:00.000Z m:rate=1.4
```

## Meta Commands

```ls
metric m:rate p:double l:Wage t:dataTypeName=money

entity e:y63e-f8gg l:"IDOL Illinois Minimum Wage" t:attribution="Illinois Department of Labor" t:url=https://data.illinois.gov/api/views/y63e-f8gg

property e:y63e-f8gg t:meta.view v:id=y63e-f8gg v:category=Labor v:attributionLink=http://labor.illinois.gov/ v:averageRating=0 v:name="IDOL Illinois Minimum Wage" v:attribution="Illinois Department of Labor"

property e:y63e-f8gg t:meta.view.license v:name="Public Domain"

property e:y63e-f8gg t:meta.view.owner v:id=qz2n-kjc9 v:screenName="IL Department of Labor" v:displayName="IL Department of Labor"

property e:y63e-f8gg t:meta.view.tableauthor v:id=qz2n-kjc9 v:screenName="IL Department of Labor" v:roleName=publisher v:displayName="IL Department of Labor"
```

## Top Records

```ls
| year | rate | 
| ==== | ==== | 
| 1972 | 1.40 | 
| 1973 | 1.40 | 
| 1974 | 1.40 | 
| 1975 | 1.40 | 
| 1976 | 2.10 | 
| 1977 | 2.10 | 
| 1978 | 2.10 | 
| 1979 | 2.30 | 
| 1980 | 2.30 | 
| 1981 | 2.30 | 
```