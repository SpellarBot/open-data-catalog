# Lobbyist Data - Historical - Lobbyist Categorized Expenditures Report - 2010

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/lobbyist-data-lobbyist-categorized-expenditures-report-2010-b739a) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/zugr-hsc5) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/zugr-hsc5/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/zugr-hsc5/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | zugr-hsc5 |
| Name | Lobbyist Data - Historical - Lobbyist Categorized Expenditures Report - 2010 |
| Attribution | City of Chicago |
| Category | Ethics |
| Tags | lobbyists, historical |
| Created | 2011-08-30T20:25:08Z |
| Publication Date | 2011-08-30T20:25:08Z |

## Description

The lobbyist categorized expenditures report is part of the Lobbyist Activity Report, a notarized disclosure that lobbyists were required to file twice during 2010 (January 20th and July 20th). Lobbyists were required to report  the total amount of lobbying-related expenditures paid by the lobbyist or charged to the client in each of the categories listed on Form C, Part 3 of 3, Section H, Question 3 (http://bit.ly/q2lRTh). Data for the 2010 reporting period is limited because previous policy did not require the Board of Ethics to prioritize the reporting of all data available from paper filings. / Data Owner: Board of Ethics [http://j.mp/mbH9BN] / Time Period: 2010/ Frequency: Data is updated daily / Related Applications: Registered Lobbyist List http://j.mp/l8LwAq

## Columns

```ls
| Included | Schema Type    | Field Name             | Name                   | Data Type | Render Type |
| ======== | ============== | ====================== | ====================== | ========= | =========== |
| Yes      | series tag     | last_name              | LAST NAME              | text      | text        |
| Yes      | series tag     | first_name             | FIRST NAME             | text      | text        |
| Yes      | series tag     | middle_initial         | MIDDLE INITIAL         | text      | text        |
| Yes      | series tag     | client_name            | CLIENT NAME            | text      | text        |
| Yes      | numeric metric | office_expenses        | OFFICE EXPENSES        | number    | number      |
| Yes      | numeric metric | compensation_to_others | COMPENSATION TO OTHERS | number    | number      |
| Yes      | numeric metric | public_education       | PUBLIC EDUCATION       | number    | number      |
| Yes      | numeric metric | personal_sustenance    | PERSONAL SUSTENANCE    | number    | number      |
| Yes      | numeric metric | other_expenses         | OTHER EXPENSES         | number    | number      |
| Yes      | numeric metric | total_expenses         | TOTAL EXPENSES         | number    | number      |
```

## Time Field

```ls
Value = 2010
Format & Zone = yyyy
```

## Data Commands

```ls
series e:zugr-hsc5 d:2010-01-01T00:00:00.000Z t:first_name=Anthony t:middle_initial=B t:last_name=Abbinante t:client_name="Diageo NA" m:office_expenses=0 m:other_expenses=0 m:compensation_to_others=0 m:personal_sustenance=0 m:public_education=0 m:total_expenses=0

series e:zugr-hsc5 d:2010-01-01T00:00:00.000Z t:first_name=Anthony t:middle_initial=B t:last_name=Abbinante t:client_name="Diageo NA" m:office_expenses=0 m:other_expenses=0 m:compensation_to_others=0 m:personal_sustenance=0 m:public_education=0 m:total_expenses=0

series e:zugr-hsc5 d:2010-01-01T00:00:00.000Z t:first_name=Anthony t:middle_initial=L t:last_name=Abboud t:client_name="108 West Germania Place, LLC" m:office_expenses=0 m:other_expenses=0 m:compensation_to_others=0 m:personal_sustenance=0 m:public_education=0 m:total_expenses=0
```

## Meta Commands

```ls
metric m:office_expenses p:double l:"OFFICE EXPENSES" t:dataTypeName=number

metric m:compensation_to_others p:integer l:"COMPENSATION TO OTHERS" t:dataTypeName=number

metric m:public_education p:float l:"PUBLIC EDUCATION" t:dataTypeName=number

metric m:personal_sustenance p:float l:"PERSONAL SUSTENANCE" t:dataTypeName=number

metric m:other_expenses p:double l:"OTHER EXPENSES" t:dataTypeName=number

metric m:total_expenses p:double l:"TOTAL EXPENSES" t:dataTypeName=number

entity e:zugr-hsc5 l:"Lobbyist Data - Historical - Lobbyist Categorized Expenditures Report - 2010" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/zugr-hsc5

property e:zugr-hsc5 t:meta.view v:id=zugr-hsc5 v:category=Ethics v:attributionLink=http://www.cityofchicago.org/city/en/depts/ethics/provdrs/lobby.html v:averageRating=0 v:name="Lobbyist Data - Historical - Lobbyist Categorized Expenditures Report - 2010" v:attribution="City of Chicago"

property e:zugr-hsc5 t:meta.view.owner v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:displayName=cocadmin v:privilegesDisabled=false

property e:zugr-hsc5 t:meta.view.tableauthor v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:roleName=administrator v:displayName=cocadmin v:privilegesDisabled=false
```

## Top Records

```ls
| last_name | first_name | middle_initial | client_name                  | office_expenses | compensation_to_others | public_education | personal_sustenance | other_expenses | total_expenses | 
| ========= | ========== | ============== | ============================ | =============== | ====================== | ================ | =================== | ============== | ============== | 
| Abbinante | Anthony    | B              | Diageo NA                    | 0               | 0                      | 0                | 0                   | 0              | 0              | 
| Abbinante | Anthony    | B              | Diageo NA                    | 0               | 0                      | 0                | 0                   | 0              | 0              | 
| Abboud    | Anthony    | L              | 108 West Germania Place, LLC | 0               | 0                      | 0                | 0                   | 0              | 0              | 
| Abboud    | Anthony    | L              | 108 West Germania Place, LLC | 0               | 0                      | 0                | 0                   | 0              | 0              | 
| Abboud    | Anthony    | L              | Tracfone Wireless, Inc       | 0               | 0                      | 0                | 0                   | 0              | 0              | 
| Abboud    | Anthony    | L              | 108 West Germania Place, LLC | 0               | 0                      | 0                | 0                   | 0              | 0              | 
| Acosta    | Rolando    | R              | Logan Square Kitchen         | 0               | 0                      | 0                | 0                   | 0              | 0              | 
| Acosta    | Rolando    | R              | East Lake/West End, LLC      | 0               | 0                      | 0                | 0                   | 0              | 0              | 
| Acosta    | Rolando    | R              | East Lake/West End, LLC      | 0               | 0                      | 0                | 0                   | 0              | 0              | 
| Acosta    | Rolando    | R              | Lazo's Tacos Inc             | 0               | 0                      | 0                | 0                   | 0              | 0              | 
```