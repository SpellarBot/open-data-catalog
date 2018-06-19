# WAT Owners Shift Reimbursement 2015

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/wat-owners-shift-reimbursement-2015) |
| Metadata | [Link](https://data.seattle.gov/api/views/a44h-qn3y) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/a44h-qn3y/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/a44h-qn3y/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | a44h-qn3y |
| Name | WAT Owners Shift Reimbursement 2015 |
| Category | Transportation |
| Tags | taxi |
| Created | 2016-07-15T23:52:04Z |
| Publication Date | 2016-07-18T15:57:35Z |

## Description

Data set provides the total amount of money paid to wheelchair accessible taxi owners for the period 6/1/15-12/31/15. Owners were paid $15/shift operated from the City of Seattle Wheelchair Accessible Services Fund.

## Columns

```ls
| Included | Schema Type    | Field Name | Name  | Data Type | Render Type |
| ======== | ============== | ========== | ===== | ========= | =========== |
| Yes      | numeric metric | cab        | CAB#  | number    | number      |
| Yes      | numeric metric | total      | TOTAL | money     | money       |
```

## Time Field

```ls
Value = 2015
Format & Zone = yyyy
```

## Data Commands

```ls
series e:a44h-qn3y d:2015-01-01T00:00:00.000Z m:total=3375 m:cab=220

series e:a44h-qn3y d:2015-01-01T00:00:00.000Z m:total=2610 m:cab=222

series e:a44h-qn3y d:2015-01-01T00:00:00.000Z m:total=3465 m:cab=237
```

## Meta Commands

```ls
metric m:cab p:integer l:CAB# t:dataTypeName=number

metric m:total p:integer l:TOTAL t:dataTypeName=money

entity e:a44h-qn3y l:"WAT Owners Shift Reimbursement 2015" t:url=https://data.seattle.gov/api/views/a44h-qn3y

property e:a44h-qn3y t:meta.view v:id=a44h-qn3y v:category=Transportation v:averageRating=0 v:name="WAT Owners Shift Reimbursement 2015"

property e:a44h-qn3y t:meta.view.owner v:id=a62b-aawc v:screenName="Consumer Protection Unit, FAS" v:displayName="Consumer Protection Unit, FAS"

property e:a44h-qn3y t:meta.view.tableauthor v:id=a62b-aawc v:screenName="Consumer Protection Unit, FAS" v:roleName=publisher v:displayName="Consumer Protection Unit, FAS"
```

## Top Records

```ls
| cab | total | 
| === | ===== | 
| 220 | 3375  | 
| 222 | 2610  | 
| 237 | 3465  | 
| 253 | 2880  | 
| 255 | 4020  | 
| 257 | 2175  | 
| 258 | 2055  | 
| 259 | 2280  | 
| 260 | 1785  | 
| 262 | 2235  | 
```