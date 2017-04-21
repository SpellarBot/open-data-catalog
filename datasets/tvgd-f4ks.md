# Missouri First Reports of Injury by Body Part - Head

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/missouri-first-reports-of-injury-by-body-part-head-49517) |
| Metadata | [Link](https://data.mo.gov/api/views/tvgd-f4ks) |
| Data: JSON | [100 Rows](https://data.mo.gov/api/views/tvgd-f4ks/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.mo.gov/api/views/tvgd-f4ks/rows.csv?max_rows=100) |
| Host | data.mo.gov |
| Id | tvgd-f4ks |
| Name | Missouri First Reports of Injury by Body Part - Head |
| Category | Labor |
| Tags | labor, injury, employment, froi |
| Created | 2012-10-03T12:36:08Z |
| Publication Date | 2013-01-03T20:54:27Z |

## Description

First reports of injury filed reporting an injury to the head.

## Columns

```ls
| Included | Schema Type    | Field Name           | Name                 | Data Type | Render Type |
| ======== | ============== | ==================== | ==================== | ========= | =========== |
| Yes      | series tag     | recordid             | recordid             | text      | text        |
| No       |                | year                 | year                 | number    | number      |
| No       |                | month                | month                | number    | number      |
| Yes      | numeric metric | head_soft_tissue     | head soft tissue     | number    | number      |
| Yes      | numeric metric | nose                 | nose                 | number    | number      |
| Yes      | numeric metric | mouth                | mouth                | number    | number      |
| Yes      | numeric metric | multiple_head_injury | multiple head injury | number    | number      |
| Yes      | numeric metric | ear_s                | ear(s)               | number    | number      |
| Yes      | numeric metric | teeth                | teeth                | number    | number      |
| Yes      | numeric metric | skull                | skull                | number    | number      |
| Yes      | numeric metric | eye_s                | eye(s)               | number    | number      |
| Yes      | numeric metric | brain                | brain                | number    | number      |
| Yes      | numeric metric | facial_bones         | facial bones         | number    | number      |
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
series e:tvgd-f4ks d:2005-04-01T00:00:00.000Z t:recordid=42005 m:skull=88 m:multiple_head_injury=115 m:mouth=32 m:facial_bones=18 m:ear_s=48 m:head_soft_tissue=194 m:eye_s=497 m:teeth=30 m:brain=7 m:nose=33

series e:tvgd-f4ks d:2004-04-01T00:00:00.000Z t:recordid=42004 m:skull=108 m:multiple_head_injury=129 m:mouth=35 m:facial_bones=22 m:ear_s=36 m:head_soft_tissue=223 m:eye_s=543 m:teeth=30 m:brain=8 m:nose=49

series e:tvgd-f4ks d:2007-04-01T00:00:00.000Z t:recordid=42007 m:skull=87 m:multiple_head_injury=136 m:mouth=24 m:facial_bones=29 m:ear_s=47 m:head_soft_tissue=217 m:eye_s=495 m:teeth=21 m:brain=3 m:nose=36
```

## Meta Commands

```ls
metric m:head_soft_tissue p:integer l:"head soft tissue" t:dataTypeName=number

metric m:nose p:integer l:nose t:dataTypeName=number

metric m:mouth p:integer l:mouth t:dataTypeName=number

metric m:multiple_head_injury p:integer l:"multiple head injury" t:dataTypeName=number

metric m:ear_s p:integer l:ear(s) t:dataTypeName=number

metric m:teeth p:integer l:teeth t:dataTypeName=number

metric m:skull p:integer l:skull t:dataTypeName=number

metric m:eye_s p:integer l:eye(s) t:dataTypeName=number

metric m:brain p:integer l:brain t:dataTypeName=number

metric m:facial_bones p:integer l:"facial bones" t:dataTypeName=number

entity e:tvgd-f4ks l:"Missouri First Reports of Injury by Body Part - Head" t:url=https://data.mo.gov/api/views/tvgd-f4ks

property e:tvgd-f4ks t:meta.view v:id=tvgd-f4ks v:category=Labor v:averageRating=0 v:name="Missouri First Reports of Injury by Body Part - Head"

property e:tvgd-f4ks t:meta.view.owner v:id=fq9d-b9a3 v:screenName=Jolene v:displayName=Jolene

property e:tvgd-f4ks t:meta.view.tableauthor v:id=fq9d-b9a3 v:screenName=Jolene v:roleName=editor v:displayName=Jolene
```

## Top Records

```ls
| recordid | year | month | head_soft_tissue | nose | mouth | multiple_head_injury | ear_s | teeth | skull | eye_s | brain | facial_bones | 
| ======== | ==== | ===== | ================ | ==== | ===== | ==================== | ===== | ===== | ===== | ===== | ===== | ============ | 
| 42005    | 2005 | 4     | 194              | 33   | 32    | 115                  | 48    | 30    | 88    | 497   | 7     | 18           | 
| 42004    | 2004 | 4     | 223              | 49   | 35    | 129                  | 36    | 30    | 108   | 543   | 8     | 22           | 
| 42007    | 2007 | 4     | 217              | 36   | 24    | 136                  | 47    | 21    | 87    | 495   | 3     | 29           | 
| 42006    | 2006 | 4     | 233              | 38   | 35    | 132                  | 27    | 23    | 81    | 489   | 14    | 19           | 
| 42009    | 2009 | 4     | 208              | 30   | 43    | 159                  | 26    | 19    | 81    | 346   | 4     | 22           | 
| 42008    | 2008 | 4     | 213              | 35   | 43    | 159                  | 56    | 24    | 73    | 420   | 5     | 26           | 
| 42001    | 2001 | 4     | 238              | 45   | 55    | 132                  | 51    | 44    | 101   | 719   | 8     | 29           | 
| 42003    | 2003 | 4     | 217              | 29   | 45    | 118                  | 39    | 30    | 77    | 566   | 9     | 23           | 
| 42002    | 2002 | 4     | 227              | 43   | 56    | 132                  | 48    | 46    | 107   | 637   | 9     | 28           | 
| 102009   | 2009 | 10    | 237              | 37   | 39    | 159                  | 24    | 18    | 62    | 333   | 5     | 20           | 
```