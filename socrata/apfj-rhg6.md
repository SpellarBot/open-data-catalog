# IHDA - Illinois Housing Dev Auth - FY2010 Governor's Report - Closings.SF Trust Fund

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ihda-illinois-housing-dev-auth-fy2010-governors-report-closings-sf-trust-fund-bf75d) |
| Metadata | [Link](https://data.illinois.gov/api/views/apfj-rhg6) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/apfj-rhg6/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/apfj-rhg6/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | apfj-rhg6 |
| Name | IHDA - Illinois Housing Dev Auth - FY2010 Governor's Report - Closings.SF Trust Fund |
| Category | Housing |
| Tags | ihda, illinois housing development authority |
| Created | 2012-01-24T22:45:31Z |
| Publication Date | 2012-01-25T22:02:13Z |

## Description

FY2010 Governor's Report - Closings.SF Trust Fund

## Columns

```ls
| Included | Schema Type    | Field Name             | Name                   | Data Type     | Render Type   |
| ======== | ============== | ====================== | ====================== | ============= | ============= |
| No       |                | fiscal_year            | FISCAL YEAR            | number        | text          |
| Yes      | series tag     | project_name           | PROJECT NAME           | text          | text          |
| No       |                | project_address        | PROJECT ADDRESS        | text          | text          |
| Yes      | series tag     | project_city           | PROJECT CITY           | text          | text          |
| Yes      | series tag     | project_sponsor        | PROJECT SPONSOR        | text          | text          |
| Yes      | series tag     | loan_or_grant          | LOAN OR GRANT          | text          | text          |
| Yes      | time           | closing_date           | CLOSING DATE           | calendar_date | calendar_date |
| Yes      | numeric metric | total_trust_fund_award | TOTAL TRUST FUND AWARD | money         | money         |
| Yes      | numeric metric | loan_funds             | LOAN FUNDS             | money         | money         |
| Yes      | numeric metric | grant_funds            | GRANT FUNDS            | money         | money         |
| Yes      | numeric metric | of_units               | # OF UNITS             | number        | number        |
| Yes      | series tag     | ihda_                  | IHDA#                  | text          | text          |
```

## Time Field

```ls
Value = closing_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = project_address,fiscal_year
```

## Data Commands

```ls
series e:apfj-rhg6 d:2009-07-15T00:00:00.000Z t:project_sponsor="Rogers Park Coumunity Dev. Corp" t:project_name="RPCDC Downpayment Assistance Program" t:ihda_=50102 t:project_city=Chicago t:loan_or_grant=Both m:loan_funds=440000 m:grant_funds=60000 m:total_trust_fund_award=500000 m:of_units=18

series e:apfj-rhg6 d:2009-07-16T00:00:00.000Z t:project_sponsor="Latin United Community Housing Association" t:project_name=LUCHA t:ihda_=50103 t:project_city=Chicago t:loan_or_grant=Both m:loan_funds=390000 m:grant_funds=110000 m:total_trust_fund_award=500000 m:of_units=30

series e:apfj-rhg6 d:2009-07-31T00:00:00.000Z t:project_sponsor="Spanish Coalition for Housing" t:project_name="Spanish Coalition for Housing Initiative" t:ihda_=50095 t:project_city=Chicago t:loan_or_grant=Both m:loan_funds=420000 m:grant_funds=80000 m:total_trust_fund_award=500000 m:of_units=35
```

## Meta Commands

```ls
metric m:total_trust_fund_award p:integer l:"TOTAL TRUST FUND AWARD" t:dataTypeName=money

metric m:loan_funds p:integer l:"LOAN FUNDS" t:dataTypeName=money

metric m:grant_funds p:integer l:"GRANT FUNDS" t:dataTypeName=money

metric m:of_units p:integer l:"# OF UNITS" t:dataTypeName=number

entity e:apfj-rhg6 l:"IHDA - Illinois Housing Dev Auth - FY2010 Governor's Report - Closings.SF Trust Fund" t:url=https://data.illinois.gov/api/views/apfj-rhg6

property e:apfj-rhg6 t:meta.view v:id=apfj-rhg6 v:category=Housing v:averageRating=0 v:name="IHDA - Illinois Housing Dev Auth - FY2010 Governor's Report - Closings.SF Trust Fund"

property e:apfj-rhg6 t:meta.view.owner v:id=i46z-zq8e v:screenName="Larry Michalski" v:displayName="Larry Michalski"

property e:apfj-rhg6 t:meta.view.tableauthor v:id=i46z-zq8e v:screenName="Larry Michalski" v:roleName=publisher v:displayName="Larry Michalski"
```

## Top Records

```ls
| fiscal_year | project_name                                                                           | project_address | project_city | project_sponsor                                    | loan_or_grant | closing_date        | total_trust_fund_award | loan_funds | grant_funds | of_units | ihda_ | 
| =========== | ====================================================================================== | =============== | ============ | ================================================== | ============= | =================== | ====================== | ========== | =========== | ======== | ===== | 
| 2010        | RPCDC Downpayment Assistance Program                                                   | Various         | Chicago      | Rogers Park Coumunity Dev. Corp                    | Both          | 2009-07-15T00:00:00 | 500000                 | 440000     | 60000       | 18       | 50102 | 
| 2010        | LUCHA                                                                                  | Various         | Chicago      | Latin United Community Housing Association         | Both          | 2009-07-16T00:00:00 | 500000                 | 390000     | 110000      | 30       | 50103 | 
| 2010        | Spanish Coalition for Housing Initiative                                               | Various         | Chicago      | Spanish Coalition for Housing                      | Both          | 2009-07-31T00:00:00 | 500000                 | 420000     | 80000       | 35       | 50095 | 
| 2010        | St. Clair County Homebuyer Program                                                     | Various         | Belleville   | St. Clair County Intergovernmental Grants          | Grant         | 2009-08-11T00:00:00 | 200000                 | 0          | 200000      | 80       | 50100 | 
| 2010        | City of Alton Homeownership Program                                                    | Various         | Alton        | City of Alton                                      | Grant         | 2009-08-11T00:00:00 | 120000                 | 0          | 120000      | 35       | 50108 | 
| 2010        | CDAP City of Shelbyville                                                               | Various         | Shelbyville  | City of Shelbyville                                | Loan          | 2009-08-20T00:00:00 | 36000                  | 36000      | 0           | 12       | 50132 | 
| 2010        | Housing Action Illinois Technical Assistance & Training to Housing Counseling Agencies | Various         | Chicago      | Housing Action Illinois                            | Grant         | 2009-08-28T00:00:00 | 125000                 | 0          | 125000      |          | 50125 | 
| 2010        | Home Options                                                                           | Various         | Chicago      | Commmunity Service Options, Inc.                   | Both          | 2009-09-09T00:00:00 | 300000                 | 260000     | 40000       | 10       | 50101 | 
| 2010        | Housing McHenry County                                                                 | Various         | Various      | Corporation for Affordable Homes of McHenry County | Both          | 2009-09-22T00:00:00 | 360000                 | 300000     | 60000       | 22       | 2997  | 
| 2010        | CDAP City of Johnston City                                                             | Various         | Johnston     | City of Johnston City                              | Loan          | 2009-10-13T00:00:00 | 39000                  | 39000      | 0           | 13       | 50128 | 
```