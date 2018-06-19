# WAT Maintenance and Equipment Reimbursment 2015

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/wat-maintenance-and-equipment-reimbursment-2015) |
| Metadata | [Link](https://data.seattle.gov/api/views/3mzv-b4ze) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/3mzv-b4ze/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/3mzv-b4ze/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | 3mzv-b4ze |
| Name | WAT Maintenance and Equipment Reimbursment 2015 |
| Category | Transportation |
| Tags | taxi |
| Created | 2016-07-15T23:46:04Z |
| Publication Date | 2016-07-15T23:51:15Z |

## Description

Data set provides the total amount of money paid per wheelchair accessible taxi for maintenance and equipment costs for the period 1/1/13-12/31/15. Owners were reimbursed for expenses related to ramps, axles, brakes and transmissions up to $3500.

## Columns

```ls
| Included | Schema Type    | Field Name       | Name             | Data Type | Render Type |
| ======== | ============== | ================ | ================ | ========= | =========== |
| Yes      | numeric metric | cab              | CAB#             | number    | number      |
| Yes      | numeric metric | 2015_paid_amount | 2015 PAID AMOUNT | money     | money       |
```

## Time Field

```ls
Value = 2015
Format & Zone = yyyy
```

## Data Commands

```ls
series e:3mzv-b4ze d:2015-01-01T00:00:00.000Z m:cab=220 m:2015_paid_amount=3463.56

series e:3mzv-b4ze d:2015-01-01T00:00:00.000Z m:cab=222 m:2015_paid_amount=3500

series e:3mzv-b4ze d:2015-01-01T00:00:00.000Z m:cab=237 m:2015_paid_amount=2667.36
```

## Meta Commands

```ls
metric m:cab p:integer l:CAB# t:dataTypeName=number

metric m:2015_paid_amount p:double l:"2015 PAID AMOUNT" t:dataTypeName=money

entity e:3mzv-b4ze l:"WAT Maintenance and Equipment Reimbursment 2015" t:url=https://data.seattle.gov/api/views/3mzv-b4ze

property e:3mzv-b4ze t:meta.view v:id=3mzv-b4ze v:category=Transportation v:averageRating=0 v:name="WAT Maintenance and Equipment Reimbursment 2015"

property e:3mzv-b4ze t:meta.view.owner v:id=a62b-aawc v:screenName="Consumer Protection Unit, FAS" v:displayName="Consumer Protection Unit, FAS"

property e:3mzv-b4ze t:meta.view.tableauthor v:id=a62b-aawc v:screenName="Consumer Protection Unit, FAS" v:roleName=publisher v:displayName="Consumer Protection Unit, FAS"
```

## Top Records

```ls
| cab | 2015_paid_amount | 
| === | ================ | 
| 220 | 3463.56          | 
| 222 | 3500             | 
| 237 | 2667.36          | 
| 253 | 3293.22          | 
| 255 | 3500             | 
| 257 | 3119.17          | 
| 258 | 1731.19          | 
| 259 | 505              | 
| 260 | 3500             | 
| 262 | 571.59           | 
```