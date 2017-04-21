# Missouri First Reports of Injury by Body Part - Neck

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/missouri-first-reports-of-injury-by-body-part-neck-8e38c) |
| Metadata | [Link](https://data.mo.gov/api/views/v2fi-tjym) |
| Data: JSON | [100 Rows](https://data.mo.gov/api/views/v2fi-tjym/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.mo.gov/api/views/v2fi-tjym/rows.csv?max_rows=100) |
| Host | data.mo.gov |
| Id | v2fi-tjym |
| Name | Missouri First Reports of Injury by Body Part - Neck |
| Category | Labor |
| Tags | labor, injury, employment, froi |
| Created | 2012-10-03T12:35:39Z |
| Publication Date | 2013-01-03T20:53:14Z |

## Description

First reports of injury filed reporting an injury to the neck.

## Columns

```ls
| Included | Schema Type    | Field Name           | Name                 | Data Type | Render Type |
| ======== | ============== | ==================== | ==================== | ========= | =========== |
| Yes      | series tag     | recordid             | recordid             | text      | text        |
| No       |                | year                 | year                 | number    | number      |
| No       |                | month                | month                | number    | number      |
| Yes      | numeric metric | disc                 | disc                 | number    | number      |
| Yes      | numeric metric | vertebrae            | vertebrae            | number    | number      |
| Yes      | numeric metric | larynx               | larynx               | number    | number      |
| Yes      | numeric metric | multiple_neck_injury | multiple neck injury | number    | number      |
| Yes      | numeric metric | neck_soft_tissue     | neck soft tissue     | number    | number      |
| Yes      | numeric metric | spinal_cord          | spinal cord          | number    | number      |
| Yes      | numeric metric | trachea              | trachea              | number    | number      |
```

## Time Field

```ls
Value = year-month
Format & Zone = yyyy-MM
```

## Series Fields

```ls
Excluded Fields = year,month
```

## Data Commands

```ls
series e:v2fi-tjym d:2005-04-01T00:00:00.000Z t:recordid=42005 m:multiple_neck_injury=37 m:trachea=2 m:vertebrae=10 m:neck_soft_tissue=73 m:spinal_cord=9 m:disc=34

series e:v2fi-tjym d:2004-04-01T00:00:00.000Z t:recordid=42004 m:multiple_neck_injury=64 m:trachea=1 m:vertebrae=12 m:neck_soft_tissue=65 m:spinal_cord=9 m:disc=10

series e:v2fi-tjym d:2007-04-01T00:00:00.000Z t:recordid=42007 m:multiple_neck_injury=41 m:trachea=2 m:larynx=3 m:vertebrae=8 m:neck_soft_tissue=81 m:spinal_cord=6 m:disc=30
```

## Meta Commands

```ls
metric m:disc p:integer l:disc t:dataTypeName=number

metric m:vertebrae p:integer l:vertebrae t:dataTypeName=number

metric m:larynx p:integer l:larynx t:dataTypeName=number

metric m:multiple_neck_injury p:integer l:"multiple neck injury" t:dataTypeName=number

metric m:neck_soft_tissue p:integer l:"neck soft tissue" t:dataTypeName=number

metric m:spinal_cord p:integer l:"spinal cord" t:dataTypeName=number

metric m:trachea p:integer l:trachea t:dataTypeName=number

entity e:v2fi-tjym l:"Missouri First Reports of Injury by Body Part - Neck" t:url=https://data.mo.gov/api/views/v2fi-tjym

property e:v2fi-tjym t:meta.view v:id=v2fi-tjym v:category=Labor v:averageRating=0 v:name="Missouri First Reports of Injury by Body Part - Neck"

property e:v2fi-tjym t:meta.view.owner v:id=fq9d-b9a3 v:screenName=Jolene v:displayName=Jolene

property e:v2fi-tjym t:meta.view.tableauthor v:id=fq9d-b9a3 v:screenName=Jolene v:roleName=editor v:displayName=Jolene
```

## Top Records

```ls
| recordid | year | month | disc | vertebrae | larynx | multiple_neck_injury | neck_soft_tissue | spinal_cord | trachea | 
| ======== | ==== | ===== | ==== | ========= | ====== | ==================== | ================ | =========== | ======= | 
| 42005    | 2005 | 4     | 34   | 10        |        | 37                   | 73               | 9           | 2       | 
| 42004    | 2004 | 4     | 10   | 12        |        | 64                   | 65               | 9           | 1       | 
| 42007    | 2007 | 4     | 30   | 8         | 3      | 41                   | 81               | 6           | 2       | 
| 42006    | 2006 | 4     | 26   | 13        | 4      | 45                   | 74               | 6           | 3       | 
| 42009    | 2009 | 4     | 7    | 5         |        | 37                   | 70               | 11          | 1       | 
| 42008    | 2008 | 4     | 8    | 5         |        | 43                   | 73               | 20          | 2       | 
| 42001    | 2001 | 4     | 7    | 12        | 4      | 66                   | 98               | 1           | 2       | 
| 42003    | 2003 | 4     | 8    | 9         |        | 64                   | 74               | 3           |         | 
| 42002    | 2002 | 4     | 12   | 13        | 6      | 61                   | 95               | 2           | 4       | 
| 102009   | 2009 | 10    | 11   | 3         | 2      | 59                   | 83               | 8           | 1       | 
```