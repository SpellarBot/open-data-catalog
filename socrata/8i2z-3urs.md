# Special Loans Closed By County FY10- FY13

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/special-loans-closed-by-county-fy10-fy13-43508) |
| Metadata | [Link](https://data.maryland.gov/api/views/8i2z-3urs) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/8i2z-3urs/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/8i2z-3urs/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | 8i2z-3urs |
| Name | Special Loans Closed By County FY10- FY13 |
| Attribution | Maryland Department of Housing and Community Development |
| Category | Housing |
| Tags | dhcd, special, loans, closed, county, housing |
| Created | 2014-05-08T19:42:09Z |
| Publication Date | 2014-05-08T19:49:43Z |

## Description

The Special Loans Program rehabilitates homes of moderate income maryland homeowners across the state in cooperation with the Local Government agencies
Types of rehabilitation include accessibility modifications for senior and disabled occupants, bringing electrical and/or plumbing systems to state and local codes, 
making roof and structural repairs, and in exceptional cases replacing an uninhabitable dwelling with a modest living structure.

## Columns

```ls
| Included | Schema Type    | Field Name        | Name              | Data Type | Render Type |
| ======== | ============== | ================= | ================= | ========= | =========== |
| No       | time           | :updated_at       | updated_at        | meta_data | meta_data   |
| Yes      | series tag     | county_name       | County Name       | text      | text        |
| Yes      | numeric metric | fy10_loans_closed | FY10-Loans Closed | number    | number      |
| Yes      | numeric metric | fy10_amount       | FY10-Amount       | money     | money       |
| Yes      | numeric metric | fy11_loans_closed | FY11-Loans Closed | number    | number      |
| Yes      | numeric metric | fy11_amount       | FY11-Amount       | money     | money       |
| Yes      | numeric metric | fy12_loans_closed | FY12-Loans Closed | number    | number      |
| Yes      | numeric metric | fy12_amount       | FY12-Amount       | money     | money       |
| Yes      | numeric metric | fy13_loans_closed | FY13-Loans Closed | number    | number      |
| Yes      | numeric metric | fy13_amount       | FY13-Amount       | money     | money       |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:8i2z-3urs d:2014-05-08T12:42:15.000Z t:county_name=ALLEGANY m:fy11_loans_closed=6 m:fy10_amount=72124 m:fy12_amount=58323 m:fy10_loans_closed=5 m:fy11_amount=102399 m:fy13_loans_closed=1 m:fy13_amount=24413 m:fy12_loans_closed=3

series e:8i2z-3urs d:2014-05-08T12:42:15.000Z t:county_name="ANNE ARUNDEL" m:fy11_loans_closed=33 m:fy10_amount=727118 m:fy12_amount=1503495 m:fy10_loans_closed=22 m:fy11_amount=1116602 m:fy13_loans_closed=26 m:fy13_amount=1129236 m:fy12_loans_closed=29

series e:8i2z-3urs d:2014-05-08T12:42:15.000Z t:county_name="BALTIMORE CITY" m:fy11_loans_closed=91 m:fy10_amount=1801768 m:fy12_amount=1476389 m:fy10_loans_closed=119 m:fy11_amount=1012572 m:fy13_loans_closed=92 m:fy13_amount=1312730 m:fy12_loans_closed=81
```

## Meta Commands

```ls
metric m:fy10_loans_closed p:integer l:"FY10-Loans Closed" t:dataTypeName=number

metric m:fy10_amount p:integer l:FY10-Amount t:dataTypeName=money

metric m:fy11_loans_closed p:integer l:"FY11-Loans Closed" t:dataTypeName=number

metric m:fy11_amount p:integer l:FY11-Amount t:dataTypeName=money

metric m:fy12_loans_closed p:integer l:"FY12-Loans Closed" t:dataTypeName=number

metric m:fy12_amount p:integer l:FY12-Amount t:dataTypeName=money

metric m:fy13_loans_closed p:integer l:"FY13-Loans Closed" t:dataTypeName=number

metric m:fy13_amount p:integer l:FY13-Amount t:dataTypeName=money

entity e:8i2z-3urs l:"Special Loans Closed By County FY10- FY13" t:attribution="Maryland Department of Housing and Community Development" t:url=https://data.maryland.gov/api/views/8i2z-3urs

property e:8i2z-3urs t:meta.view v:id=8i2z-3urs v:category=Housing v:attributionLink=http://mdhousing.org/Website/Default v:averageRating=0 v:name="Special Loans Closed By County FY10- FY13" v:attribution="Maryland Department of Housing and Community Development"

property e:8i2z-3urs t:meta.view.license v:name="Public Domain"

property e:8i2z-3urs t:meta.view.owner v:id=3bma-cuk6 v:screenName="Linda DeLuca" v:displayName="Linda DeLuca"

property e:8i2z-3urs t:meta.view.tableauthor v:id=3bma-cuk6 v:screenName="Linda DeLuca" v:roleName=editor v:displayName="Linda DeLuca"
```

## Top Records

```ls
| :updated_at | county_name    | fy10_loans_closed | fy10_amount | fy11_loans_closed | fy11_amount | fy12_loans_closed | fy12_amount | fy13_loans_closed | fy13_amount | 
| =========== | ============== | ================= | =========== | ================= | =========== | ================= | =========== | ================= | =========== | 
| 1399552935  | ALLEGANY       | 5                 | 72124       | 6                 | 102399      | 3                 | 58323       | 1                 | 24413       | 
| 1399552935  | ANNE ARUNDEL   | 22                | 727118      | 33                | 1116602     | 29                | 1503495     | 26                | 1129236     | 
| 1399552935  | BALTIMORE CITY | 119               | 1801768     | 91                | 1012572     | 81                | 1476389     | 92                | 1312730     | 
| 1399552935  | BALTIMORE      | 11                | 444367      | 9                 | 315032      | 25                | 747259      | 21                | 844254      | 
| 1399552935  | CALVERT        | 14                | 166598      | 3                 | 144365      | 2                 | 15240       | 2                 | 86217       | 
| 1399552935  | CAROLINE       | 8                 | 333746      | 10                | 371071      | 7                 | 155968      | 6                 | 86882       | 
| 1399552935  | CARROLL        | 7                 | 245516      | 6                 | 220868      | 4                 | 130055      | 2                 | 181529      | 
| 1399552935  | CECIL          | 3                 | 54619       | 0                 | 0           | 0                 | 0           | 0                 | 0           | 
| 1399552935  | CHARLES        | 14                | 999263      | 4                 | 120567      | 4                 | 111820      | 5                 | 510824      | 
| 1399552935  | DORCHESTER     | 15                | 644530      | 18                | 676683      | 5                 | 293767      | 4                 | 175862      | 
```