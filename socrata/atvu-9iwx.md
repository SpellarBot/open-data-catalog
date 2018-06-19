# Maryland Mortgage (Single Family Loans) FY 2011-2016

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/maryland-mortgage-single-family-loans-fy-2011-2015) |
| Metadata | [Link](https://data.maryland.gov/api/views/atvu-9iwx) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/atvu-9iwx/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/atvu-9iwx/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | atvu-9iwx |
| Name | Maryland Mortgage (Single Family Loans) FY 2011-2016 |
| Attribution | Department of Housing and Community Development |
| Category | Housing |
| Tags | mmp, cda, maryland mortgage, maryland mortgage program, dhcd, department of housing & community development, single family housing, down payment assistance, dpa, first time home ownership, home bu... |
| Created | 2016-07-01T15:12:33Z |
| Publication Date | 2017-02-27T21:37:50Z |

## Description

The Maryland Mortgage Program provides help in the form of Down Payment Assistance, as well as a range of Partner Match programs from employers, developers and community organizations that can help you cover these down payment and closing costs.  These programs may make it possible for first-time homebuyers to afford a mortgage when they would not be able to do so the conventional way.

DISCLAIMER: Some of the information may be tied to the Department?s bond funded loan programs and should not be relied upon in making an investment decision. The Department provides comprehensive quarterly and annual financial information and operating data regarding its bonds and bond funded loan programs, all of which is posted on the publicly-accessible Electronic Municipal Market Access system website (commonly known as EMMA) that is maintained by the Municipal Securities Rulemaking Board, and on the Department?s website under Investor Information. 

More information accessible here: http://dhcd.maryland.gov/Investors/Pages/default.aspx

## Columns

```ls
| Included | Schema Type    | Field Name      | Name            | Data Type | Render Type |
| ======== | ============== | =============== | =============== | ========= | =========== |
| Yes      | numeric metric | loan_amount     | Loan Amount     | money     | money       |
| Yes      | series tag     | county          | County          | text      | text        |
| Yes      | series tag     | houseingtype    | HouseingType    | text      | text        |
| Yes      | series tag     | number_of_units | Number of Units | text      | text        |
| Yes      | numeric metric | interest_rate   | Interest Rate   | percent   | percent     |
| Yes      | numeric metric | dpaloanamt      | DPALoanAmt      | money     | money       |
| Yes      | numeric metric | purch_price     | Purch Price     | money     | money       |
| Yes      | numeric metric | dselp_amount    | DSELP AMOUNT    | money     | money       |
| No       |                | fy              | FY              | number    | text        |
```

## Time Field

```ls
Value = 2011
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = fy
```

## Data Commands

```ls
series e:atvu-9iwx d:2011-01-01T00:00:00.000Z t:houseingtype=1-Detached t:county="BALTIMORE CO." t:number_of_units="1 UNIT" m:loan_amount=204676 m:purch_price=210000 m:dselp_amount=5000 m:dpaloanamt=8500 m:interest_rate=4

series e:atvu-9iwx d:2011-01-01T00:00:00.000Z t:houseingtype=3-Townhouse t:county="SAINT MARY'S" t:number_of_units="1 UNIT" m:loan_amount=248186 m:purch_price=241935 m:dselp_amount=5000 m:dpaloanamt=7500 m:interest_rate=4

series e:atvu-9iwx d:2011-01-01T00:00:00.000Z t:houseingtype=3-Townhouse t:county=CHARLES t:number_of_units="1 UNIT" m:loan_amount=191709 m:purch_price=185000 m:dselp_amount=5000 m:dpaloanamt=5000 m:interest_rate=3.875
```

## Meta Commands

```ls
metric m:loan_amount p:integer l:"Loan Amount" t:dataTypeName=money

metric m:interest_rate p:float l:"Interest Rate" t:dataTypeName=percent

metric m:dpaloanamt p:integer l:DPALoanAmt t:dataTypeName=money

metric m:purch_price p:integer l:"Purch Price" t:dataTypeName=money

metric m:dselp_amount p:integer l:"DSELP AMOUNT" t:dataTypeName=money

entity e:atvu-9iwx l:"Maryland Mortgage (Single Family Loans) FY 2011-2016" t:attribution="Department of Housing and Community Development" t:url=https://data.maryland.gov/api/views/atvu-9iwx

property e:atvu-9iwx t:meta.view v:id=atvu-9iwx v:category=Housing v:attributionLink=http://mmp.maryland.gov/Pages/default.aspx v:averageRating=0 v:name="Maryland Mortgage (Single Family Loans) FY 2011-2016" v:attribution="Department of Housing and Community Development"

property e:atvu-9iwx t:meta.view.owner v:id=pugw-9r35 v:screenName="Jessica Handy" v:lastNotificationSeenAt=1491917263 v:displayName="Jessica Handy"

property e:atvu-9iwx t:meta.view.tableauthor v:id=pugw-9r35 v:screenName="Jessica Handy" v:roleName=editor v:lastNotificationSeenAt=1491917263 v:displayName="Jessica Handy"
```

## Top Records

```ls
| loan_amount | county          | houseingtype | number_of_units | interest_rate | dpaloanamt | purch_price | dselp_amount | fy   | 
| =========== | =============== | ============ | =============== | ============= | ========== | =========== | ============ | ==== | 
| 204676      | BALTIMORE CO.   | 1-Detached   | 1 UNIT          | 4             | 8500       | 210000      | 5000         | 2011 | 
| 248186      | SAINT MARY'S    | 3-Townhouse  | 1 UNIT          | 4             | 7500       | 241935      | 5000         | 2011 | 
| 191709      | CHARLES         | 3-Townhouse  | 1 UNIT          | 3.875         | 5000       | 185000      | 5000         | 2011 | 
| 122273      | PRINCE GEORGE'S | 1-Detached   | 1 UNIT          | 3.625         | 5000       | 119700      | 5000         | 2011 | 
| 114887      | PRINCE GEORGE'S | 1-Detached   | 1 UNIT          | 4.25          | 5000       | 117900      | 5000         | 2011 | 
| 100826      | BALTIMORE CITY  | 3-Townhouse  | 1 UNIT          | 4             | 5000       | 104900      | 5000         | 2011 | 
| 141324      | BALTIMORE CO.   | 3-Townhouse  | 1 UNIT          | 4.25          | 7500       | 145000      | 5000         | 2011 | 
| 121243      | CAROLINE        | 1-Detached   | 1 UNIT          | 3.625         | 5000       | 115000      | 5000         | 2011 | 
| 112084      | HARFORD         | 3-Townhouse  | 1 UNIT          | 4.25          | 5000       | 115000      | 5000         | 2011 | 
| 88880       | WASHINGTON      | 9-PUD        | 1 UNIT          | 4.25          | 5000       | 105000      | 5000         | 2011 | 
```