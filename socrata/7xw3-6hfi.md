# WAT OWNER/DRIVERS TRIP REIMBURSEMENT 11/12/14-12/31/15

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/wat-owner-drivers-trip-reimbursement-11-12-14-12-31-15) |
| Metadata | [Link](https://data.seattle.gov/api/views/7xw3-6hfi) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/7xw3-6hfi/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/7xw3-6hfi/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | 7xw3-6hfi |
| Name | WAT OWNER/DRIVERS TRIP REIMBURSEMENT 11/12/14-12/31/15 |
| Category | Transportation |
| Tags | taxi, wheelchair |
| Created | 2016-07-15T23:37:22Z |
| Publication Date | 2016-07-15T23:51:27Z |

## Description

Data set provides the total amount of money paid to wheelchair accessible taxi drivers for the period 11/12/14-12/31/15. Drivers were paid $20/wheelchair passenger trip from the City of Seattle Wheelchair Accessible Services Fund.

## Columns

```ls
| Included | Schema Type    | Field Name  | Name       | Data Type | Render Type |
| ======== | ============== | =========== | ========== | ========= | =========== |
| No       | time           | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag     | forhire     | FORHIRE #  | text      | text        |
| Yes      | numeric metric | total       | TOTAL      | money     | money       |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:7xw3-6hfi d:2016-07-15T16:37:25.000Z t:forhire=4995 m:total=220

series e:7xw3-6hfi d:2016-07-15T16:37:25.000Z t:forhire=6936 m:total=1100

series e:7xw3-6hfi d:2016-07-15T16:37:25.000Z t:forhire=7351 m:total=1040
```

## Meta Commands

```ls
metric m:total p:double l:TOTAL t:dataTypeName=money

entity e:7xw3-6hfi l:"WAT OWNER/DRIVERS TRIP REIMBURSEMENT 11/12/14-12/31/15" t:url=https://data.seattle.gov/api/views/7xw3-6hfi

property e:7xw3-6hfi t:meta.view v:id=7xw3-6hfi v:category=Transportation v:averageRating=0 v:name="WAT OWNER/DRIVERS TRIP REIMBURSEMENT 11/12/14-12/31/15"

property e:7xw3-6hfi t:meta.view.owner v:id=a62b-aawc v:screenName="Consumer Protection Unit, FAS" v:displayName="Consumer Protection Unit, FAS"

property e:7xw3-6hfi t:meta.view.tableauthor v:id=a62b-aawc v:screenName="Consumer Protection Unit, FAS" v:roleName=publisher v:displayName="Consumer Protection Unit, FAS"
```

## Top Records

```ls
| :updated_at | forhire | total   | 
| =========== | ======= | ======= | 
| 1468600645  | 4995    | 220     | 
| 1468600645  | 6936    | 1100.00 | 
| 1468600645  | 7351    | 1040.00 | 
| 1468600645  | 7980    | 740.00  | 
| 1468600645  | 7997    | 2460.00 | 
| 1468600645  | 7998    | 860     | 
| 1468600645  | 8587    | 1080.00 | 
| 1468600645  | 8707    | 720.00  | 
| 1468600645  | 8797    | 3040.00 | 
| 1468600645  | 8822    | 2500.00 | 
```