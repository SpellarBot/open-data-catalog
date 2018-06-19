# Appropriations - Proprietary Departments

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/proprietary-budgets-fiscal-years-2013-2017) |
| Metadata | [Link](https://data.lacity.org/api/views/jauz-q9v3) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/jauz-q9v3/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/jauz-q9v3/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | jauz-q9v3 |
| Name | Appropriations - Proprietary Departments |
| Attribution | LA City Chief Administrative Office |
| Category | A Prosperous City |
| Tags | budget, proprietary, dwp, pension, pensions, fiscal |
| Created | 2016-04-15T23:57:59Z |
| Publication Date | 2016-04-18T22:22:19Z |

## Description

The departments in this file - Airports, Harbor, Water and Power, and the city's two pension funds - operate independently from LA's city government. Their budgets are approved by independent boards of commissioners and appear in the back of the city budget document only for information purposes. Data covers fiscal years 2013-2017.

## Columns

```ls
| Included | Schema Type    | Field Name     | Name          | Data Type | Render Type |
| ======== | ============== | ============== | ============= | ========= | =========== |
| Yes      | series tag     | department_sub | Department    | text      | text        |
| Yes      | series tag     | account_code   | Account_Code  | text      | text        |
| Yes      | series tag     | account_name   | Account_Name  | text      | text        |
| Yes      | numeric metric | appropriation  | Appropriation | money     | money       |
| Yes      | time           | fiscal_year    | Fiscal_Year   | number    | number      |
```

## Time Field

```ls
Value = fiscal_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:jauz-q9v3 d:2013-01-01T00:00:00.000Z t:department_sub=DWP t:account_code=0000A t:account_name="Purchase of land and buildings" m:appropriation=3165100

series e:jauz-q9v3 d:2013-01-01T00:00:00.000Z t:department_sub=DWP t:account_code=2000 t:account_name="Transportation, lodging and employee mileage reimbursements in connection with construction, operation and maintenance work" m:appropriation=4390200

series e:jauz-q9v3 d:2013-01-01T00:00:00.000Z t:department_sub=DWP t:account_code=2000 t:account_name="Rentals and leases" m:appropriation=5806400
```

## Meta Commands

```ls
metric m:appropriation p:integer l:Appropriation t:dataTypeName=money

entity e:jauz-q9v3 l:"Appropriations - Proprietary Departments" t:attribution="LA City Chief Administrative Office" t:url=https://data.lacity.org/api/views/jauz-q9v3

property e:jauz-q9v3 t:meta.view v:id=jauz-q9v3 v:category="A Prosperous City" v:attributionLink=http://cao.lacity.org/budget/ v:averageRating=0 v:name="Appropriations - Proprietary Departments" v:attribution="LA City Chief Administrative Office"

property e:jauz-q9v3 t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:jauz-q9v3 t:meta.view.owner v:id=95pg-i79k v:profileImageUrlMedium=/api/users/95pg-i79k/profile_images/THUMB v:profileImageUrlLarge=/api/users/95pg-i79k/profile_images/LARGE v:screenName=ChelseaU v:profileImageUrlSmall=/api/users/95pg-i79k/profile_images/TINY v:displayName=ChelseaU

property e:jauz-q9v3 t:meta.view.tableauthor v:id=95pg-i79k v:profileImageUrlMedium=/api/users/95pg-i79k/profile_images/THUMB v:profileImageUrlLarge=/api/users/95pg-i79k/profile_images/LARGE v:screenName=ChelseaU v:profileImageUrlSmall=/api/users/95pg-i79k/profile_images/TINY v:roleName=administrator v:displayName=ChelseaU
```

## Top Records

```ls
| department_sub | account_code | account_name                                                                                                                | appropriation | fiscal_year | 
| ============== | ============ | =========================================================================================================================== | ============= | =========== | 
| DWP            | 0000A        | Purchase of land and buildings                                                                                              | 3165100       | 2013        | 
| DWP            | 2000         | Transportation, lodging and employee mileage reimbursements in connection with construction, operation and maintenance work | 4390200       | 2013        | 
| DWP            | 2000         | Rentals and leases                                                                                                          | 5806400       | 2013        | 
| DWP            | 2000         | Contracts - Operation and maintenance work                                                                                  | 7626400       | 2013        | 
| DWP            | 0000A        | Utility services for telecommunications and water                                                                           | 8359500       | 2013        | 
| DWP            | 0000A        | Energy Efficiency Loans to customers                                                                                        | 9594500       | 2013        | 
| DWP            | 2000         | Postal services                                                                                                             | 9600300       | 2013        | 
| DWP            | 0000A        | Refunds of customers' deposits                                                                                              | 11284478      | 2013        | 
| DWP            | 0000A        | Property taxes                                                                                                              | 13823400      | 2013        | 
| DWP            | 0000A        | Adjustments (Accrual, etc.)                                                                                                 | 16508222      | 2013        | 
```