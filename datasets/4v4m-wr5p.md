# Log Prices

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/log-prices) |
| Metadata | [Link](https://data.oregon.gov/api/views/4v4m-wr5p) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/4v4m-wr5p/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/4v4m-wr5p/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | 4v4m-wr5p |
| Name | Log Prices |
| Attribution | Oregon Department of Forestry |
| Category | Natural Resources |
| Tags | logging, logs, forestry |
| Created | 2015-06-26T22:45:55Z |
| Publication Date | 2016-07-08T19:56:58Z |

## Description

Log prices by species and grade from 2015-2000

## Columns

```ls
| Included | Schema Type    | Field Name       | Name             | Data Type | Render Type |
| ======== | ============== | ================ | ================ | ========= | =========== |
| No       |                | year             | Year             | number    | text        |
| No       |                | quarter          | Quarter          | number    | number      |
| Yes      | series tag     | region           | Region           | text      | text        |
| Yes      | series tag     | species          | Species          | text      | text        |
| Yes      | series tag     | grade            | Grade            | text      | text        |
| Yes      | numeric metric | pond_value       | Pond Value       | money     | money       |
| Yes      | series tag     | number_of_quotes | Number of Quotes | text      | text        |
```

## Time Field

```ls
Value = year-quarter
Format & Zone = yyyy-q
```

## Series Fields

```ls
Excluded Fields = year,quarter
```

## Data Commands

```ls
series e:4v4m-wr5p d:2010-10-01T00:00:00.000Z t:region="5 - Klamath Unit" t:number_of_quotes=6 t:species=Douglas-fir t:grade="6""-8""" m:pond_value=305

series e:4v4m-wr5p d:2005-10-01T00:00:00.000Z t:region="4 - Grants Pass Unit" t:number_of_quotes="5 or less" t:species="Sugar Pine" t:grade=3S m:pond_value=650

series e:4v4m-wr5p d:2004-01-01T00:00:00.000Z t:region="4 - Grants Pass Unit" t:number_of_quotes="5 or less" t:species=Douglas-fir t:grade=1P m:pond_value=935
```

## Meta Commands

```ls
metric m:pond_value p:integer l:"Pond Value" t:dataTypeName=money

entity e:4v4m-wr5p l:"Log Prices" t:attribution="Oregon Department of Forestry" t:url=https://data.oregon.gov/api/views/4v4m-wr5p

property e:4v4m-wr5p t:meta.view v:id=4v4m-wr5p v:category="Natural Resources" v:attributionLink=http://oregon.gov/ODF v:averageRating=0 v:name="Log Prices" v:attribution="Oregon Department of Forestry"

property e:4v4m-wr5p t:meta.view.license v:name="Public Domain"

property e:4v4m-wr5p t:meta.view.owner v:id=d6zp-7ggp v:screenName=JeriChase v:displayName=JeriChase

property e:4v4m-wr5p t:meta.view.tableauthor v:id=d6zp-7ggp v:screenName=JeriChase v:roleName=editor v:displayName=JeriChase
```

## Top Records

```ls
| year | quarter | region                            | species        | grade     | pond_value | number_of_quotes | 
| ==== | ======= | ================================= | ============== | ========= | ========== | ================ | 
| 2010 | 4       | 5 - Klamath Unit                  | Douglas-fir    | 6"-8"     | 305        | 6                | 
| 2005 | 4       | 4 - Grants Pass Unit              | Sugar Pine     | 3S        | 650        | 5 or less        | 
| 2004 | 1       | 4 - Grants Pass Unit              | Douglas-fir    | 1P        | 935        | 5 or less        | 
| 2002 | 3       | 5 - Klamath Unit                  | Ponderosa Pine | 8"-14"    | 395        | 5 or less        | 
| 2002 | 1       | 4 - Grants Pass Unit              | Hemlock        | CR (+12") | 400        | 5 or less        | 
| 2000 | 2       | 5 - Klamath Unit                  | True Fir       | SC        | 75         | 5 or less        | 
| 2015 | 1       | 1 - Northwest Oregon & Willamette | Douglas-fir    | 1P        | 615        | 12               | 
| 2015 | 1       | 1 - Northwest Oregon & Willamette | Douglas-fir    | 2P        | 615        | 12               | 
| 2015 | 1       | 1 - Northwest Oregon & Willamette | Douglas-fir    | 3P &Btr   | 615        | 12               | 
| 2015 | 1       | 1 - Northwest Oregon & Willamette | Douglas-fir    | SM        | 610        | 12               | 
```