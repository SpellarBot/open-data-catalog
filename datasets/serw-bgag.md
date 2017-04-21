# Maryland Housing Rehab Special Loans Program

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/maryland-housing-rehab-special-loans-program) |
| Metadata | [Link](https://data.maryland.gov/api/views/serw-bgag) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/serw-bgag/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/serw-bgag/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | serw-bgag |
| Name | Maryland Housing Rehab Special Loans Program |
| Attribution | Department of Housing and Community Development |
| Category | Housing |
| Tags | dhcd, maryland, housing, rehab, special, loans |
| Created | 2014-10-01T20:49:47Z |
| Publication Date | 2014-10-01T20:53:11Z |

## Description

The Special Loans Program rehabilitates homes of moderate income maryland homeowners across the state in cooperation with the Local Government agencies Types of rehabilitation include accessibility modifications for senior and disabled occupants, bringing electrical and/or plumbing systems to state and local codes, making roof and structural repairs, and in exceptional cases replacing an uninhabitable dwelling with a modest living structure.

DISCLAIMER: Some of the information may be tied to the Department?s bond funded loan programs and should not be relied upon in making an investment decision. The Department provides comprehensive quarterly and annual financial information and operating data regarding its bonds and bond funded loan programs, all of which is posted on the publicly-accessible Electronic Municipal Market Access system website (commonly known as EMMA) that is maintained by the Municipal Securities Rulemaking Board, and on the Department?s website under Investor Information. 

More information accessible here: http://dhcd.maryland.gov/Investors/Pages/default.aspx

## Columns

```ls
| Included | Schema Type    | Field Name         | Name               | Data Type | Render Type |
| ======== | ============== | ================== | ================== | ========= | =========== |
| No       | time           | :updated_at        | updated_at         | meta_data | meta_data   |
| Yes      | series tag     | county             | COUNTY             | text      | text        |
| Yes      | series tag     | fy10               | FY10               | text      | text        |
| Yes      | numeric metric | fy10_units         | FY10 UNITS         | number    | number      |
| Yes      | numeric metric | fy10_amt_of_funds  | FY10 AMT OF FUNDS  | money     | money       |
| Yes      | numeric metric | fy10_grants        | FY10 GRANTS        | number    | number      |
| Yes      | numeric metric | fy10_loans         | FY10 LOANS         | number    | number      |
| Yes      | series tag     | fy11               | FY11               | text      | text        |
| Yes      | numeric metric | fy11_units         | FY11 UNITS         | number    | number      |
| Yes      | numeric metric | fy11_amt_of_funds  | FY11 AMT OF FUNDS  | money     | money       |
| Yes      | numeric metric | fy11_grants        | FY11 GRANTS        | number    | number      |
| Yes      | numeric metric | fy11_loans         | FY11 LOANS         | number    | number      |
| Yes      | series tag     | fy12               | FY12               | text      | text        |
| Yes      | numeric metric | fy12_units         | FY12 UNITS         | number    | number      |
| Yes      | numeric metric | fy12_amt_of_funds  | FY12 AMT OF FUNDS  | money     | money       |
| Yes      | numeric metric | fy12_grants        | FY12 GRANTS        | number    | number      |
| Yes      | numeric metric | fy12_loans         | FY12 LOANS         | number    | number      |
| Yes      | series tag     | fy13               | FY13               | text      | text        |
| Yes      | numeric metric | fy13_units         | FY13 UNITS         | number    | number      |
| Yes      | numeric metric | fy_13_amt_of_funds | FY 13 AMT OF FUNDS | money     | money       |
| Yes      | numeric metric | fy13_grants        | FY13 GRANTS        | number    | number      |
| Yes      | numeric metric | fy13_loans         | FY13 LOANS         | number    | number      |
| Yes      | series tag     | fy14               | FY14               | text      | text        |
| Yes      | numeric metric | fy14_units         | FY14 UNITS         | number    | number      |
| Yes      | numeric metric | fy14_amt_of_funds  | FY14 AMT OF FUNDS  | money     | money       |
| Yes      | numeric metric | fy14_grants        | FY14 GRANTS        | number    | number      |
| Yes      | numeric metric | fy14_loans         | FY14 LOANS         | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:serw-bgag d:2014-10-01T13:49:53.000Z t:fy10=FY10 t:fy11=FY11 t:fy12=FY12 t:county=Allegany t:fy13=FY13 t:fy14=FY14 m:fy10_loans=3 m:fy14_loans=4 m:fy14_amt_of_funds=116296 m:fy12_units=2 m:fy11_amt_of_funds=73299 m:fy11_loans=4 m:fy13_units=0 m:fy13_grants=0 m:fy12_loans=2 m:fy14_grants=0 m:fy11_grants=0 m:fy10_amt_of_funds=41421 m:fy_13_amt_of_funds=0 m:fy13_loans=0 m:fy12_amt_of_funds=33323 m:fy14_units=4 m:fy11_units=4 m:fy10_units=3 m:fy10_grants=0 m:fy12_grants=0

series e:serw-bgag d:2014-10-01T13:49:53.000Z t:fy10=FY10 t:fy11=FY11 t:fy12=FY12 t:county="Anne Arundel" t:fy13=FY13 t:fy14=FY14 m:fy10_loans=13 m:fy14_loans=19 m:fy14_amt_of_funds=830950 m:fy12_units=19 m:fy11_amt_of_funds=450459 m:fy11_loans=12 m:fy13_units=17 m:fy13_grants=0 m:fy12_loans=18 m:fy14_grants=0 m:fy11_grants=0 m:fy10_amt_of_funds=550968 m:fy_13_amt_of_funds=1201966 m:fy13_loans=17 m:fy12_amt_of_funds=1292850 m:fy14_units=19 m:fy11_units=13 m:fy10_units=13 m:fy10_grants=0 m:fy12_grants=0

series e:serw-bgag d:2014-10-01T13:49:53.000Z t:fy10=FY10 t:fy11=FY11 t:fy12=FY12 t:county=Baltimore t:fy13=FY13 t:fy14=FY14 m:fy10_loans=7 m:fy14_loans=4 m:fy14_amt_of_funds=126709 m:fy12_units=14 m:fy11_amt_of_funds=237189 m:fy11_loans=4 m:fy13_units=20 m:fy13_grants=0 m:fy12_loans=14 m:fy14_grants=0 m:fy11_grants=0 m:fy10_amt_of_funds=393975 m:fy_13_amt_of_funds=842453 m:fy13_loans=20 m:fy12_amt_of_funds=570852 m:fy14_units=4 m:fy11_units=4 m:fy10_units=7 m:fy10_grants=0 m:fy12_grants=0
```

## Meta Commands

```ls
metric m:fy10_units p:integer l:"FY10 UNITS" t:dataTypeName=number

metric m:fy10_amt_of_funds p:integer l:"FY10 AMT OF FUNDS" t:dataTypeName=money

metric m:fy10_grants p:integer l:"FY10 GRANTS" t:dataTypeName=number

metric m:fy10_loans p:integer l:"FY10 LOANS" t:dataTypeName=number

metric m:fy11_units p:integer l:"FY11 UNITS" t:dataTypeName=number

metric m:fy11_amt_of_funds p:integer l:"FY11 AMT OF FUNDS" t:dataTypeName=money

metric m:fy11_grants p:integer l:"FY11 GRANTS" t:dataTypeName=number

metric m:fy11_loans p:integer l:"FY11 LOANS" t:dataTypeName=number

metric m:fy12_units p:integer l:"FY12 UNITS" t:dataTypeName=number

metric m:fy12_amt_of_funds p:integer l:"FY12 AMT OF FUNDS" t:dataTypeName=money

metric m:fy12_grants p:integer l:"FY12 GRANTS" t:dataTypeName=number

metric m:fy12_loans p:integer l:"FY12 LOANS" t:dataTypeName=number

metric m:fy13_units p:integer l:"FY13 UNITS" t:dataTypeName=number

metric m:fy_13_amt_of_funds p:integer l:"FY 13 AMT OF FUNDS" t:dataTypeName=money

metric m:fy13_grants p:integer l:"FY13 GRANTS" t:dataTypeName=number

metric m:fy13_loans p:integer l:"FY13 LOANS" t:dataTypeName=number

metric m:fy14_units p:integer l:"FY14 UNITS" t:dataTypeName=number

metric m:fy14_amt_of_funds p:integer l:"FY14 AMT OF FUNDS" t:dataTypeName=money

metric m:fy14_grants p:integer l:"FY14 GRANTS" t:dataTypeName=number

metric m:fy14_loans p:integer l:"FY14 LOANS" t:dataTypeName=number

entity e:serw-bgag l:"Maryland Housing Rehab Special Loans Program" t:attribution="Department of Housing and Community Development" t:url=https://data.maryland.gov/api/views/serw-bgag

property e:serw-bgag t:meta.view v:id=serw-bgag v:category=Housing v:attributionLink=http://www.dhcd.maryland.gov/Pages/Default.aspx v:averageRating=0 v:name="Maryland Housing Rehab Special Loans Program" v:attribution="Department of Housing and Community Development"

property e:serw-bgag t:meta.view.license v:name="Public Domain"

property e:serw-bgag t:meta.view.owner v:id=pugw-9r35 v:screenName="Jessica Handy" v:lastNotificationSeenAt=1491917263 v:displayName="Jessica Handy"

property e:serw-bgag t:meta.view.tableauthor v:id=pugw-9r35 v:screenName="Jessica Handy" v:roleName=editor v:lastNotificationSeenAt=1491917263 v:displayName="Jessica Handy"
```

## Top Records

```ls
| :updated_at | county         | fy10 | fy10_units | fy10_amt_of_funds | fy10_grants | fy10_loans | fy11 | fy11_units | fy11_amt_of_funds | fy11_grants | fy11_loans | fy12 | fy12_units | fy12_amt_of_funds | fy12_grants | fy12_loans | fy13 | fy13_units | fy_13_amt_of_funds | fy13_grants | fy13_loans | fy14 | fy14_units | fy14_amt_of_funds | fy14_grants | fy14_loans | 
| =========== | ============== | ==== | ========== | ================= | =========== | ========== | ==== | ========== | ================= | =========== | ========== | ==== | ========== | ================= | =========== | ========== | ==== | ========== | ================== | =========== | ========== | ==== | ========== | ================= | =========== | ========== | 
| 1412171393  | Allegany       | FY10 | 3          | 41421             | 0           | 3          | FY11 | 4          | 73299             | 0           | 4          | FY12 | 2          | 33323             | 0           | 2          | FY13 | 0          | 0                  | 0           | 0          | FY14 | 4          | 116296            | 0           | 4          | 
| 1412171393  | Anne Arundel   | FY10 | 13         | 550968            | 0           | 13         | FY11 | 13         | 450459            | 0           | 12         | FY12 | 19         | 1292850           | 0           | 18         | FY13 | 17         | 1201966            | 0           | 17         | FY14 | 19         | 830950            | 0           | 19         | 
| 1412171393  | Baltimore      | FY10 | 7          | 393975            | 0           | 7          | FY11 | 4          | 237189            | 0           | 4          | FY12 | 14         | 570852            | 0           | 14         | FY13 | 20         | 842453             | 0           | 20         | FY14 | 4          | 126709            | 0           | 4          | 
| 1412171393  | Baltimore City | FY10 | 23         | 895055            | 0           | 23         | FY11 | 8          | 334723            | 0           | 8          | FY12 | 17         | 666983            | 0           | 17         | FY13 | 13         | 337633             | 0           | 13         | FY14 | 11         | 296739            | 0           | 11         | 
| 1412171393  | Calvert        | FY10 | 1          | 35114             | 0           | 1          | FY11 | 1          | 26096             | 0           | 1          | FY12 | 0          | 0                 | 0           | 0          | FY13 | 1          | 35768              | 0           | 1          | FY14 | 0          | 0                 | 0           | 0          | 
| 1412171393  | Caroline       | FY10 | 3          | 168613            | 0           | 3          | FY11 | 7          | 243723            | 0           | 7          | FY12 | 4          | 126564            | 0           | 4          | FY13 | 3          | 66112              | 0           | 3          | FY14 | 2          | 67486             | 0           | 2          | 
| 1412171393  | Carroll        | FY10 | 2          | 97977             | 0           | 2          | FY11 | 1          | 53155             | 0           | 1          | FY12 | 2          | 58489             | 0           | 2          | FY13 | 2          | 181529             | 0           | 2          | FY14 | 1          | 54408             | 0           | 1          | 
| 1412171393  | Cecil          | FY10 | 1          | 27955             | 0           | 1          | FY11 | 0          | 0                 | 0           | 0          | FY12 | 0          | 0                 | 0           | 0          | FY13 | 0          | 0                  | 0           | 0          | FY14 | 1          | 32465             | 0           | 1          | 
| 1412171393  | Charles        | FY10 | 5          | 219776            | 0           | 5          | FY11 | 4          | 120567            | 0           | 4          | FY12 | 3          | 76735             | 0           | 3          | FY13 | 0          | 0                  | 0           | 0          | FY14 | 1          | 95995             | 0           | 1          | 
| 1412171393  | Dorchester     | FY10 | 2          | 96992             | 0           | 2          | FY11 | 8          | 235547            | 0           | 8          | FY12 | 2          | 60264             | 0           | 2          | FY13 | 1          | 14539              | 0           | 1          | FY14 | 3          | 120981            | 0           | 3          | 
```