# Film and Television Oregon Production Investment Fund - Fiscal Year 2012

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/film-and-television-oregon-production-investment-fund-fiscal-year-2012-ecc3e) |
| Metadata | [Link](https://data.oregon.gov/api/views/gq9r-bjuu) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/gq9r-bjuu/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/gq9r-bjuu/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | gq9r-bjuu |
| Name | Film and Television Oregon Production Investment Fund - Fiscal Year 2012 |
| Category | Revenue & Expense |
| Created | 2013-02-07T18:23:21Z |
| Publication Date | 2013-02-07T18:24:37Z |

## Columns

```ls
| Included | Schema Type    | Field Name           | Name                 | Data Type | Render Type |
| ======== | ============== | ==================== | ==================== | ========= | =========== |
| Yes      | series tag     | first_name           | First Name           | text      | text        |
| Yes      | series tag     | last_name            | Last Name            | text      | text        |
| No       |                | address_line_1       | Address Line 1       | text      | text        |
| Yes      | series tag     | city                 | City                 | text      | text        |
| Yes      | series tag     | state                | State                | text      | text        |
| Yes      | series tag     | zip                  | Zip                  | text      | text        |
| Yes      | numeric metric | 2011_amt_paid        | 2011 Amt Paid        | money     | money       |
| Yes      | numeric metric | 2011_credit_amt      | 2011 Credit Amt      | money     | money       |
| Yes      | series tag     | outcomes             | Outcomes             | text      | text        |
| Yes      | series tag     | taxpayer_requirement | Taxpayer Requirement | text      | text        |
```

## Time Field

```ls
Value = 2012
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = address_line_1
```

## Data Commands

```ls
series e:gq9r-bjuu d:2012-01-01T00:00:00.000Z t:outcomes="Taxpayer received a credit and enough money was raised in OPIF to recruit a record amount of film and television production.  See addendum for a more detailed description of outcome." t:zip=97401- t:first_name=Richard t:taxpayer_requirement="Taxpayer filled out application and submitted application for credit." t:state=OR t:last_name=Abraham t:city=Eugene m:2011_credit_amt=22222.22 m:2011_amt_paid=20000

series e:gq9r-bjuu d:2012-01-01T00:00:00.000Z t:outcomes="Taxpayer received a credit and enough money was raised in OPIF to recruit a record amount of film and television production.  See addendum for a more detailed description of outcome." t:zip=97223- t:first_name="Richard & Vesna" t:taxpayer_requirement="Taxpayer filled out application and submitted application for credit." t:state=OR t:last_name=Ader t:city=Portland m:2011_credit_amt=15789.47 m:2011_amt_paid=15000

series e:gq9r-bjuu d:2012-01-01T00:00:00.000Z t:outcomes="Taxpayer received a credit and enough money was raised in OPIF to recruit a record amount of film and television production.  See addendum for a more detailed description of outcome." t:zip=97068- t:first_name=Douglas t:taxpayer_requirement="Taxpayer filled out application and submitted application for credit." t:state=OR t:last_name=Ainslie t:city="West Linn" m:2011_credit_amt=31578.95 m:2011_amt_paid=30000
```

## Meta Commands

```ls
metric m:2011_amt_paid p:double l:"2011 Amt Paid" t:dataTypeName=money

metric m:2011_credit_amt p:double l:"2011 Credit Amt" t:dataTypeName=money

entity e:gq9r-bjuu l:"Film and Television Oregon Production Investment Fund - Fiscal Year 2012" t:url=https://data.oregon.gov/api/views/gq9r-bjuu

property e:gq9r-bjuu t:meta.view v:id=gq9r-bjuu v:category="Revenue & Expense" v:averageRating=0 v:name="Film and Television Oregon Production Investment Fund - Fiscal Year 2012"

property e:gq9r-bjuu t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:gq9r-bjuu t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| first_name          | last_name | address_line_1               | city         | state | zip    | 2011_amt_paid | 2011_credit_amt | outcomes                                                                                                                                                                              | taxpayer_requirement                                                  | 
| =================== | ========= | ============================ | ============ | ===== | ====== | ============= | =============== | ===================================================================================================================================================================================== | ===================================================================== | 
| Richard             | Abraham   | 2136 Prestwich Place         | Eugene       | OR    | 97401- | 20000.00      | 22222.22        | Taxpayer received a credit and enough money was raised in OPIF to recruit a record amount of film and television production. See addendum for a more detailed description of outcome. | Taxpayer filled out application and submitted application for credit. | 
| Richard & Vesna     | Ader      | 11501 SW Pacific Hwy Ste 203 | Portland     | OR    | 97223- | 15000.00      | 15789.47        | Taxpayer received a credit and enough money was raised in OPIF to recruit a record amount of film and television production. See addendum for a more detailed description of outcome. | Taxpayer filled out application and submitted application for credit. | 
| Douglas             | Ainslie   | 2951 Beacon Drive            | West Linn    | OR    | 97068- | 30000.00      | 31578.95        | Taxpayer received a credit and enough money was raised in OPIF to recruit a record amount of film and television production. See addendum for a more detailed description of outcome. | Taxpayer filled out application and submitted application for credit. | 
| Roy                 | Aldritt   | 19460 Tam Lake Ct.           | Bend         | OR    | 97702- | 13500.00      | 15000.00        | Taxpayer received a credit and enough money was raised in OPIF to recruit a record amount of film and television production. See addendum for a more detailed description of outcome. | Taxpayer filled out application and submitted application for credit. | 
| Aad & Rachelle      | Alkemade  | 34276 Country View Drive     | Eugene       | OR    | 97408- | 45000.00      | 50000.00        | Taxpayer received a credit and enough money was raised in OPIF to recruit a record amount of film and television production. See addendum for a more detailed description of outcome. | Taxpayer filled out application and submitted application for credit. | 
| Finlay              | Anderson  | 4022 NE 8th Ave.             | Portland     | OR    | 97212- | 8500.00       | 8947.37         | Taxpayer received a credit and enough money was raised in OPIF to recruit a record amount of film and television production. See addendum for a more detailed description of outcome. | Taxpayer filled out application and submitted application for credit. | 
| Christie & Lawrence | Anderson  | 11501 SW Pacific Hwy Ste 203 | Portland     | OR    | 97223- | 4000.00       | 4210.53         | Taxpayer received a credit and enough money was raised in OPIF to recruit a record amount of film and television production. See addendum for a more detailed description of outcome. | Taxpayer filled out application and submitted application for credit. | 
| William & Susan     | Anderson  | 11501 SW Pacific Hwy Ste 203 | Portland     | OR    | 97223- | 1000.00       | 1052.63         | Taxpayer received a credit and enough money was raised in OPIF to recruit a record amount of film and television production. See addendum for a more detailed description of outcome. | Taxpayer filled out application and submitted application for credit. | 
| Ana                 | Andueza   | 2231 NE Halsey               | Portland     | OR    | 97232- | 13000.00      | 13684.21        | Taxpayer received a credit and enough money was raised in OPIF to recruit a record amount of film and television production. See addendum for a more detailed description of outcome. | Taxpayer filled out application and submitted application for credit. | 
| Doug & Laura        | Baker     | 10936 SE Valley View Terrace | Happy Valley | OR    | 97086- | 75000.00      | 78947.37        | Taxpayer received a credit and enough money was raised in OPIF to recruit a record amount of film and television production. See addendum for a more detailed description of outcome. | Taxpayer filled out application and submitted application for credit. | 
```