# Department of Housing & Community Development Performance Metrics FY 2011 - 2016

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/department-of-housing-community-development-performance-metrics-fy-2011-2015) |
| Metadata | [Link](https://data.maryland.gov/api/views/tay4-rqsd) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/tay4-rqsd/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/tay4-rqsd/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | tay4-rqsd |
| Name | Department of Housing & Community Development Performance Metrics FY 2011 - 2016 |
| Attribution | Department of Housing and Community Development |
| Category | Housing |
| Tags | mmp, cda, maryland mortgage, maryland mortgage program, community development administration, dhcd, department of housing & community development, single family housing, down payment assistance, d... |
| Created | 2016-07-05T13:05:08Z |
| Publication Date | 2017-01-31T16:47:52Z |

## Description

The Maryland D?epartment of Housing and Community Development is proud to be at the forefront in implementing housing policy that promotes and preserves homeownership and creating innovative community development initiatives to meet the challenges of a growing Maryland.

Through the Maryland Mortgage Program, the department has empowered thousands of Maryland families to realize the American dream of homeownership and for existing homeowners.

The department?s rental housing programs increase and preserve the supply of affordable housing and provide good choices for working families, senior citizens, and individuals with special needs.

Community development and revitalization programs like Neighborhood BusinessWorks, Community Legacy, and Main Street Maryland help our cities and towns remain rich, vibrant communities.

The Maryland Department of Housing and Community Development remains committed to building on our past successes to maintain our reputation as an innovator in community revitalization and a national leader in housing finance.

DISCLAIMER: Some of the information may be tied to the Department?s bond funded loan programs and should not be relied upon in making an investment decision. The Department provides comprehensive quarterly and annual financial information and operating data regarding its bonds and bond funded loan programs, all of which is posted on the publicly-accessible Electronic Municipal Market Access system website (commonly known as EMMA) that is maintained by the Municipal Securities Rulemaking Board, and on the Department?s website under Investor Information. 

More information accessible here: http://dhcd.maryland.gov/Investors/Pages/default.aspx

## Columns

```ls
| Included | Schema Type    | Field Name                     | Name                           | Data Type     | Render Type   |
| ======== | ============== | ============================== | ============================== | ============= | ============= |
| Yes      | time           | date                           | Date                           | calendar_date | calendar_date |
| No       |                | year                           | Fiscal Year                    | number        | text          |
| Yes      | numeric metric | jobs_created                   | Jobs Created                   | number        | number        |
| Yes      | numeric metric | small_business_loans           | Small Business Loans           | number        | number        |
| Yes      | numeric metric | households_purchased           | Homes Purchased                | number        | number        |
| Yes      | numeric metric | rental_housing_produced_units  | Rental Housing Units Produced  | number        | number        |
| Yes      | numeric metric | rental_housing_preserved_units | Rental Housing Units Preserved | number        | number        |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = year
```

## Data Commands

```ls
series e:tay4-rqsd d:2011-06-30T00:00:00.000Z m:small_business_loans=17 m:rental_housing_produced_units=482 m:jobs_created=11216 m:households_purchased=1126 m:rental_housing_preserved_units=1773

series e:tay4-rqsd d:2012-06-30T00:00:00.000Z m:small_business_loans=6 m:rental_housing_produced_units=1040 m:jobs_created=12504 m:households_purchased=1450 m:rental_housing_preserved_units=197

series e:tay4-rqsd d:2013-06-30T00:00:00.000Z m:small_business_loans=14 m:rental_housing_produced_units=1048 m:jobs_created=14990 m:households_purchased=1559 m:rental_housing_preserved_units=1110
```

## Meta Commands

```ls
metric m:jobs_created p:integer l:"Jobs Created" t:dataTypeName=number

metric m:small_business_loans p:integer l:"Small Business Loans" d:"Neighborhood Business Work's loan program provides gap financing, i.e. subordinate financing, to new or expanding small businesses and nonprofit organizations in Sustainable Communities throughout the State." t:dataTypeName=number

metric m:households_purchased p:integer l:"Homes Purchased" d:"The Maryland Mortgage Program provides help in the form of Down Payment Assistance, as well as a range of Partner Match programs from employers, developers and community organizations that can help you cover these down payment and closing costs. These programs may make it possible for first-time homebuyers to afford a mortgage when they would not be able to do so the conventional way." t:dataTypeName=number

metric m:rental_housing_produced_units p:integer l:"Rental Housing Units Produced" d:"The Maryland Department of Housing and Community Development offers multifamily finance programs for the construction and rehabilitation of affordable rental housing units for low to moderate income families, senior citizens and individuals with disabilities. Our multifamily bond programs issues tax-exempt and taxable revenue mortgage bonds to finance the acquisition, preservation and creation of affordable multifamily rental housing units in priority funding areas. By advocating for increased production of rental housing units, we help create much-needed jobs and leverage opportunities to live, work and prosper for hardworking Maryland families, senior citizens, and individuals with disabilities throughout the state" t:dataTypeName=number

metric m:rental_housing_preserved_units p:integer l:"Rental Housing Units Preserved" d:"The Maryland Department of Housing and Community Development offers multifamily finance programs for the construction and rehabilitation of affordable rental housing units for low to moderate income families, senior citizens and individuals with disabilities. Our multifamily bond programs issues tax-exempt and taxable revenue mortgage bonds to finance the acquisition, preservation and creation of affordable multifamily rental housing units in priority funding areas. By advocating for increased production of rental housing units, we help create much-needed jobs and leverage opportunities to live, work and prosper for hardworking Maryland families, senior citizens, and individuals with disabilities throughout the state" t:dataTypeName=number

entity e:tay4-rqsd l:"Department of Housing & Community Development Performance Metrics FY 2011 - 2016" t:attribution="Department of Housing and Community Development" t:url=https://data.maryland.gov/api/views/tay4-rqsd

property e:tay4-rqsd t:meta.view v:id=tay4-rqsd v:category=Housing v:attributionLink=http://dhcd.maryland.gov/Pages/default.aspx v:averageRating=0 v:name="Department of Housing & Community Development Performance Metrics FY 2011 - 2016" v:attribution="Department of Housing and Community Development"

property e:tay4-rqsd t:meta.view.owner v:id=pugw-9r35 v:screenName="Jessica Handy" v:lastNotificationSeenAt=1491917263 v:displayName="Jessica Handy"

property e:tay4-rqsd t:meta.view.tableauthor v:id=pugw-9r35 v:screenName="Jessica Handy" v:roleName=editor v:lastNotificationSeenAt=1491917263 v:displayName="Jessica Handy"
```

## Top Records

```ls
| date                | year | jobs_created | small_business_loans | households_purchased | rental_housing_produced_units | rental_housing_preserved_units | 
| =================== | ==== | ============ | ==================== | ==================== | ============================= | ============================== | 
| 2011-06-30T00:00:00 | 2011 | 11216        | 17                   | 1126                 | 482                           | 1773                           | 
| 2012-06-30T00:00:00 | 2012 | 12504        | 6                    | 1450                 | 1040                          | 197                            | 
| 2013-06-30T00:00:00 | 2013 | 14990        | 14                   | 1559                 | 1048                          | 1110                           | 
| 2014-06-30T00:00:00 | 2014 | 15362        | 13                   | 1537                 | 631                           | 1776                           | 
| 2015-06-30T00:00:00 | 2015 | 16519        | 23                   | 2348                 | 1533                          | 1432                           | 
| 2016-06-30T00:00:00 | 2016 | 19024        | 54                   | 3378                 | 1131                          | 3543                           | 
```