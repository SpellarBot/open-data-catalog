# Contracts: Lottery: Fiscal Year 2012

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/contracts-lottery-fiscal-year-2012-7ed14) |
| Metadata | [Link](https://data.oregon.gov/api/views/i3ri-n6hq) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/i3ri-n6hq/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/i3ri-n6hq/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | i3ri-n6hq |
| Name | Contracts: Lottery: Fiscal Year 2012 |
| Category | Revenue & Expense |
| Created | 2012-12-18T16:02:35Z |
| Publication Date | 2012-12-28T23:45:31Z |

## Columns

```ls
| Included | Schema Type    | Field Name                 | Name                       | Data Type | Render Type |
| ======== | ============== | ========================== | ========================== | ========= | =========== |
| Yes      | series tag     | award_numberw_amendments   | Award Numberw/Amendments   | text      | text        |
| Yes      | series tag     | award_title                | Award Title                | text      | text        |
| Yes      | series tag     | award_type                 | Award Type                 | text      | text        |
| Yes      | series tag     | contractor_information     | Contractor Information     | text      | text        |
| Yes      | series tag     | street_address             | Street Address             | text      | text        |
| Yes      | series tag     | zip_code                   | Zip Code                   | text      | text        |
| Yes      | time           | start_date                 | Start Date                 | text      | text        |
| No       |                | expirationdate             | ExpirationDate             | text      | text        |
| Yes      | numeric metric | contract_amendmentvalue    | Contract/AmendmentValue    | money     | money       |
| Yes      | numeric metric | total_contractw_amendments | Total Contractw/Amendments | money     | money       |
```

## Time Field

```ls
Value = start_date
Format & Zone = MM/dd/yy
```

## Series Fields

```ls
Excluded Fields = expirationdate
```

## Data Commands

```ls
series e:i3ri-n6hq d:2011-10-04T00:00:00.000Z t:zip_code=97223 t:award_numberw_amendments=000016 t:award_type="PURCHASE ORDER" t:award_title="Ticket Scratchers for give-aways to Retailers and Players" t:street_address="13815 SW 114TH AVENUE" t:contractor_information="CUSTOM IMPRINT" m:contract_amendmentvalue=24300 m:total_contractw_amendments=24300

series e:i3ri-n6hq d:2011-10-05T00:00:00.000Z t:zip_code=89119 t:award_numberw_amendments=000022 t:award_type="PURCHASE ORDER" t:award_title="Shock, Bolster, Bally? C9" t:street_address="6601 S. BERMUDA ROAD" t:contractor_information="BALLY GAMING & SYSTEMS" m:contract_amendmentvalue=17292 m:total_contractw_amendments=17292

series e:i3ri-n6hq d:2011-10-06T00:00:00.000Z t:zip_code=97220 t:award_numberw_amendments=000038 t:award_type="PURCHASE ORDER" t:award_title="Tripplite  Isobar 4 Ultra" t:street_address="9440 NE HALSEY" t:contractor_information="DOUBLE O ELECTRONIC DISTRIBUTORS IN" m:contract_amendmentvalue=5342.4 m:total_contractw_amendments=5342.4
```

## Meta Commands

```ls
metric m:contract_amendmentvalue p:double l:Contract/AmendmentValue t:dataTypeName=money

metric m:total_contractw_amendments p:double l:"Total Contractw/Amendments" t:dataTypeName=money

entity e:i3ri-n6hq l:"Contracts: Lottery: Fiscal Year 2012" t:url=https://data.oregon.gov/api/views/i3ri-n6hq

property e:i3ri-n6hq t:meta.view v:id=i3ri-n6hq v:category="Revenue & Expense" v:averageRating=0 v:name="Contracts: Lottery: Fiscal Year 2012"

property e:i3ri-n6hq t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:i3ri-n6hq t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| award_numberw_amendments | award_title                                                                                                              | award_type              | contractor_information              | street_address           | zip_code | start_date | expirationdate | contract_amendmentvalue | total_contractw_amendments | 
| ======================== | ======================================================================================================================== | ======================= | =================================== | ======================== | ======== | ========== | ============== | ======================= | ========================== | 
| 000016                   | Ticket Scratchers for give-aways to Retailers and Players                                                                | PURCHASE ORDER          | CUSTOM IMPRINT                      | 13815 SW 114TH AVENUE    | 97223    | 10/4/11    |                | 24300.00                | 24300.00                   | 
| 000022                   | Shock, Bolster, Bally? C9                                                                                                | PURCHASE ORDER          | BALLY GAMING & SYSTEMS              | 6601 S. BERMUDA ROAD     | 89119    | 10/5/11    |                | 17292.00                | 17292.00                   | 
| 000038                   | Tripplite Isobar 4 Ultra                                                                                                 | PURCHASE ORDER          | DOUBLE O ELECTRONIC DISTRIBUTORS IN | 9440 NE HALSEY           | 97220    | 10/6/11    |                | 5342.40                 | 5342.40                    | 
| 000054                   | Oregon State Police Security Services Interagency Agreement #145-2011                                                    | INTER AGENCY AGREEMENT  | OREGON STATE POLICE                 | 400 PUBLIC SERVICE BLDG  | 97310    | 7/1/11     | 6/30/2013      | 6147792.00              | 6147792.00                 | 
| 000055                   | Cisco? Secure Access Control System (ACS), centralized identity and access policy solution. ACS Large Deployment License | PRICE AGREEMENT (STATE) | SIRIUS COMPUTER SOLUTIONS INC       | 613 NW LOOP 410 STE 1000 | 78216    | 10/11/11   |                | 10197.00                | 10197.00                   | 
| 000059                   | Blanket Order for Janitorial Supplies                                                                                    | PURCHASE ORDER          | COASTWIDE LABORATORIES              | 10000 SW COMMERCE CIRCLE | 97070    | 10/11/11   | 6/30/2013      | 10000.00                | 10000.00                   | 
| 000063                   | Advertising Services for Oregon Wins Campaign #1                                                                         | WORK ORDER CONTRACT     | BORDERS PERRIN NORRANDER            | 118 SW 1ST AVE           | 97204    | 7/1/11     | 6/30/12        | 110013.53               | 110013.53                  | 
| 000064                   | Advertising Services for Annual Strategic Planning and Consulting                                                        | WORK ORDER CONTRACT     | BORDERS PERRIN NORRANDER            | 118 SW 1ST AVE           | 97204    | 7/1/11     | 6/30/12        | 64000.00                | 64000.00                   | 
| 000068                   | Advertising Services for Keno To Go Campaign                                                                             | WORK ORDER CONTRACT     | BORDERS PERRIN NORRANDER            | 118 SW 1ST AVE           | 97204    | 8/1/11     | 6/30/12        | 210480.00               | 210480.00                  | 
| 000069                   | Advertising Services for Strategic Planning for Loyalty Prize Acquisition                                                | WORK ORDER CONTRACT     | BORDERS PERRIN NORRANDER            | 118 SW 1ST AVE           | 97204    | 7/29/11    | 6/30/2012      | 70000.00                | 70000.00                   | 
```