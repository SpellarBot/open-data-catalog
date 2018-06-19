# Violent Crime Statistics For Champaign 2007-2011

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/violent-crime-statistics-for-champaign-2007-2011-b4e0d) |
| Metadata | [Link](https://data.illinois.gov/api/views/akb5-n6v7) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/akb5-n6v7/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/akb5-n6v7/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | akb5-n6v7 |
| Name | Violent Crime Statistics For Champaign 2007-2011 |
| Attribution | City of Champaign |
| Category | Municipality |
| Tags | champaign |
| Created | 2012-12-05T17:56:31Z |
| Publication Date | 2012-12-05T17:58:07Z |

## Columns

```ls
| Included | Schema Type | Field Name | Name    | Data Type | Render Type |
| ======== | =========== | ========== | ======= | ========= | =========== |
| Yes      | series tag  | offense    | Offense | text      | text        |
| No       |             | _1         | 2007    | number    | number      |
| No       |             | _2         | 2008    | number    | number      |
| No       |             | _3         | 2009    | number    | number      |
| No       |             | _4         | 2010    | number    | number      |
| No       |             | _5         | 2011    | number    | number      |
```

## Time Field

```ls
Value = 2007
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = _1,_2,_3,_4,_5
```

## Data Commands

```ls
series e:akb5-n6v7 d:2007-01-01T00:00:00.000Z t:offense="Murder - 1st Degree" m:row_number.akb5-n6v7=1

series e:akb5-n6v7 d:2007-01-01T00:00:00.000Z t:offense="Murder - 2nd Degree" m:row_number.akb5-n6v7=2

series e:akb5-n6v7 d:2007-01-01T00:00:00.000Z t:offense="Solicitation for Murder" m:row_number.akb5-n6v7=3
```

## Meta Commands

```ls
metric m:row_number.akb5-n6v7 p:long l:"Row Number"

entity e:akb5-n6v7 l:"Violent Crime Statistics For Champaign 2007-2011" t:attribution="City of Champaign" t:url=https://data.illinois.gov/api/views/akb5-n6v7

property e:akb5-n6v7 t:meta.view v:id=akb5-n6v7 v:category=Municipality v:averageRating=0 v:name="Violent Crime Statistics For Champaign 2007-2011" v:attribution="City of Champaign"

property e:akb5-n6v7 t:meta.view.license v:name="Public Domain"

property e:akb5-n6v7 t:meta.view.owner v:id=v5dz-wzd9 v:screenName="Patrick East" v:displayName="Patrick East"

property e:akb5-n6v7 t:meta.view.tableauthor v:id=v5dz-wzd9 v:screenName="Patrick East" v:displayName="Patrick East"
```

## Top Records

```ls
| offense                           | _1 | _2 | _3 | _4 | _5 | 
| ================================= | == | == | == | == | == | 
| Murder - 1st Degree               | 16 | 9  | 8  | 8  | 6  | 
| Murder - 2nd Degree               | 1  | 0  | 0  | 0  | 0  | 
| Solicitation for Murder           | 1  | 0  | 0  | 0  | 0  | 
| Manslaughter - Inv/Rec Home/Veh   | 1  | 0  | 0  | 0  | 0  | 
| Sexual Assault - Criminal         | 58 | 53 | 37 | 54 | 38 | 
| Sexual Assault - Agg. Criminal    | 12 | 0  | 9  | 9  | 6  | 
| Predatory Criminal Sexual Assault | 2  | 6  | 0  | 1  | 1  | 
| Sodomy - Forcible                 | 0  | 0  | 2  | 1  | 3  | 
| Robbery - Armed                   | 42 | 41 | 41 | 46 | 35 | 
| Robbery                           | 50 | 42 | 56 | 82 | 54 | 
```