# Community Development Block Grant Awards (CDBG)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/community-development-block-grant-awards-cdbg-fy10-de2a5) |
| Metadata | [Link](https://data.maryland.gov/api/views/qubt-bv3h) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/qubt-bv3h/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/qubt-bv3h/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | qubt-bv3h |
| Name | Community Development Block Grant Awards (CDBG) |
| Attribution | Department of Housing and Community Development |
| Category | Housing |
| Tags | dhcd, housing, community development block grant, awards, cdbg, department of housing & community development, neighborhood revitalization, hud, us department of housing and urban development, grant |
| Created | 2014-11-05T14:38:08Z |
| Publication Date | 2015-04-21T14:39:31Z |

## Description

Community Development Block Grant Program funds help strengthen Maryland?s communities by expanding affordable housing opportunities, creating jobs, stabilizing neighborhoods and improving overall quality of life.?

Congress created the Community Development Block Grant Program under Title I of the Housing and Community Development Act of 1974. The primary objective is to develop viable communities, provide decent housing and a suitable living environment, and to expand economic opportunities, principally for persons of low and moderate income. The U.S. Department of Housing and Urban Development (HUD) oversees the Program.

The Program is comprised of two parts. The Entitlement Program is directly administered by HUD and provides Federal funds to large metropolitan entitlement communities. The States and Small Cities Program provides Federal funds to the States and Puerto Rico (with the exception of Hawaii) who then distribute funds to non-entitlement counties, small cities and towns. Congress? allocates funds to the program annually. The Entitlement Program receives approximately 70% of the allocation and the remaining 30% is distributed to the States and Small Cities Program.

Maryland's Community Development Block Grant Program is administered by the Maryland Department of Housing and Community Development. The State receives an allocation from the Department of Housing and Urban Development each July.

DISCLAIMER: Some of the information may be tied to the Department?s bond funded loan programs and should not be relied upon in making an investment decision. The Department provides comprehensive quarterly and annual financial information and operating data regarding its bonds and bond funded loan programs, all of which is posted on the publicly-accessible Electronic Municipal Market Access system website (commonly known as EMMA) that is maintained by the Municipal Securities Rulemaking Board, and on the Department?s website under Investor Information. 

More information accessible here: http://dhcd.maryland.gov/Investors/Pages/default.aspx

## Columns

```ls
| Included | Schema Type    | Field Name   | Name         | Data Type | Render Type |
| ======== | ============== | ============ | ============ | ========= | =========== |
| Yes      | time           | fiscal_year  | Fiscal Year  | number    | text        |
| Yes      | series tag     | awardee      | Awardee      | text      | text        |
| Yes      | series tag     | project_name | Project Name | text      | text        |
| Yes      | numeric metric | award        | Award        | money     | money       |
| Yes      | series tag     | city         | City         | text      | text        |
| Yes      | series tag     | county       | County       | text      | text        |
```

## Time Field

```ls
Value = fiscal_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:qubt-bv3h d:2010-01-01T00:00:00.000Z t:project_name="ADA Curb Cuts" t:county=Frederick t:awardee="Brunswick. City of" t:city=Brunswick m:award=104250

series e:qubt-bv3h d:2010-01-01T00:00:00.000Z t:project_name="Banner Building Renovations" t:county=Dorchester t:awardee="Cambridge, City of" t:city=Cambridge m:award=439500

series e:qubt-bv3h d:2010-01-01T00:00:00.000Z t:project_name="Christ Water and Sewer" t:county=Dorchester t:awardee="Cambridge, City of" t:city=Cambridge m:award=154000
```

## Meta Commands

```ls
metric m:award p:double l:Award t:dataTypeName=money

entity e:qubt-bv3h l:"Community Development Block Grant Awards (CDBG)" t:attribution="Department of Housing and Community Development" t:url=https://data.maryland.gov/api/views/qubt-bv3h

property e:qubt-bv3h t:meta.view v:id=qubt-bv3h v:category=Housing v:attributionLink=http://www.dhcd.maryland.gov/Pages/Default.aspx v:averageRating=0 v:name="Community Development Block Grant Awards (CDBG)" v:attribution="Department of Housing and Community Development"

property e:qubt-bv3h t:meta.view.license v:name="Public Domain"

property e:qubt-bv3h t:meta.view.owner v:id=pugw-9r35 v:screenName="Jessica Handy" v:lastNotificationSeenAt=1491917263 v:displayName="Jessica Handy"

property e:qubt-bv3h t:meta.view.tableauthor v:id=pugw-9r35 v:screenName="Jessica Handy" v:roleName=editor v:lastNotificationSeenAt=1491917263 v:displayName="Jessica Handy"
```

## Top Records

```ls
| fiscal_year | awardee               | project_name                   | award     | city         | county     | 
| =========== | ===================== | ============================== | ========= | ============ | ========== | 
| 2010        | Brunswick. City of    | ADA Curb Cuts                  | 104250.00 | Brunswick    | Frederick  | 
| 2010        | Cambridge, City of    | Banner Building Renovations    | 439500.00 | Cambridge    | Dorchester | 
| 2010        | Cambridge, City of    | Christ Water and Sewer         | 154000.00 | Cambridge    | Dorchester | 
| 2010        | Cambridge, City of    | Housing Rehabilitation Program | 250000.00 | Cambridge    | Dorchester | 
| 2010        | Cambridge, City of    | Christ Water and Sewer         | 500000.00 | Cambridge    | Dorchester | 
| 2010        | Church Creek, Town of | Boys and Girls Club            | 15000.00  | Church Creek | Dorchester | 
| 2010        | Crisfield             | Sherwin Williams               | 710000.00 | Crisfield    | Somerset   | 
| 2010        | Delmar, Town of       | Housing Rehabilitation Program | 167500.00 | Delmar       | Wicomico   | 
| 2010        | Worcester County      | Housing Rehabilitation Program | 300000.00 | County wide  | Worcester  | 
| 2011        | Frostburg, City of    | Fire Station Retrofit          | 300000.00 | Frostburg    | Allegany   | 
```