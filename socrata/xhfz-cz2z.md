# Neighborhood Business Works (NBW) FY 2011 - 2016

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/neighborhood-business-works-nbw-fy-2011-2015) |
| Metadata | [Link](https://data.maryland.gov/api/views/xhfz-cz2z) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/xhfz-cz2z/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/xhfz-cz2z/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | xhfz-cz2z |
| Name | Neighborhood Business Works (NBW) FY 2011 - 2016 |
| Attribution | Department of Housing and Community Development |
| Category | Housing |
| Tags | nbw, neighborhood business works, dhcd, department of housing & community development, business loans, business lending, maryland, small business lending, neighborhood businessworks, open for busi... |
| Created | 2016-07-01T14:58:58Z |
| Publication Date | 2017-02-27T21:14:37Z |

## Description

Neighborhood Business Work's loan progr?am provi?des gap financing, i.e. subordinate financing, to new or expanding small businesses and nonprofit organizations in Sustainable Communities throughout the State.

DISCLAIMER: Some of the information may be tied to the Department?s bond funded loan programs and should not be relied upon in making an investment decision. The Department provides comprehensive quarterly and annual financial information and operating data regarding its bonds and bond funded loan programs, all of which is posted on the publicly-accessible Electronic Municipal Market Access system website (commonly known as EMMA) that is maintained by the Municipal Securities Rulemaking Board, and on the Department?s website under Investor Information. 

More information accessible here: http://dhcd.maryland.gov/Investors/Pages/default.aspx

## Columns

```ls
| Included | Schema Type    | Field Name             | Name                   | Data Type | Render Type |
| ======== | ============== | ====================== | ====================== | ========= | =========== |
| Yes      | series tag     | project_name           | Project Name           | text      | text        |
| No       |                | project_address        | Project Address        | text      | text        |
| Yes      | series tag     | project_city           | Project City           | text      | text        |
| Yes      | series tag     | projectcounty          | ProjectCounty          | text      | text        |
| Yes      | series tag     | project_zip            | Project Zip            | text      | text        |
| Yes      | series tag     | awardee_name           | Awardee Name           | text      | text        |
| Yes      | numeric metric | amount_of_funds        | Amount of Funds        | money     | money       |
| Yes      | numeric metric | number_of_jobs_created | Number of Jobs Created | number    | number      |
| No       |                | fy                     | FY                     | number    | text        |
```

## Time Field

```ls
Value = 2011
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = project_address,fy
```

## Data Commands

```ls
series e:xhfz-cz2z d:2011-01-01T00:00:00.000Z t:project_name="C & A, Inc." t:awardee_name="Constantin Rodousakis" t:project_city=Bladensburg t:projectcounty="Prince George's" t:project_zip=20710 m:amount_of_funds=243500 m:number_of_jobs_created=3

series e:xhfz-cz2z d:2011-01-01T00:00:00.000Z t:project_name="Fire Station 1 Restaurant & Brewing Company" t:awardee_name="Jeremy Gruber" t:project_city="Silver Spring" t:projectcounty=Montgomery t:project_zip=20910 m:amount_of_funds=150000 m:number_of_jobs_created=125

series e:xhfz-cz2z d:2011-01-01T00:00:00.000Z t:project_name="Babe (A Boutique)" t:awardee_name="Lisa Ponzoli" t:project_city=Baltimore t:projectcounty="Baltimore City" t:project_zip=21230 m:amount_of_funds=35000 m:number_of_jobs_created=0
```

## Meta Commands

```ls
metric m:amount_of_funds p:double l:"Amount of Funds" t:dataTypeName=money

metric m:number_of_jobs_created p:integer l:"Number of Jobs Created" t:dataTypeName=number

entity e:xhfz-cz2z l:"Neighborhood Business Works (NBW) FY 2011 - 2016" t:attribution="Department of Housing and Community Development" t:url=https://data.maryland.gov/api/views/xhfz-cz2z

property e:xhfz-cz2z t:meta.view v:id=xhfz-cz2z v:category=Housing v:attributionLink=http://dhcd.maryland.gov/Pages/default.aspx v:averageRating=0 v:name="Neighborhood Business Works (NBW) FY 2011 - 2016" v:attribution="Department of Housing and Community Development"

property e:xhfz-cz2z t:meta.view.owner v:id=pugw-9r35 v:screenName="Jessica Handy" v:lastNotificationSeenAt=1491917263 v:displayName="Jessica Handy"

property e:xhfz-cz2z t:meta.view.tableauthor v:id=pugw-9r35 v:screenName="Jessica Handy" v:roleName=editor v:lastNotificationSeenAt=1491917263 v:displayName="Jessica Handy"
```

## Top Records

```ls
| project_name                                | project_address            | project_city  | projectcounty   | project_zip | awardee_name             | amount_of_funds | number_of_jobs_created | fy   | 
| =========================================== | ========================== | ============= | =============== | =========== | ======================== | =============== | ====================== | ==== | 
| C & A, Inc.                                 | 4208 48th Street           | Bladensburg   | Prince George's | 20710       | Constantin Rodousakis    | 243500.00       | 3                      | 2011 | 
| Fire Station 1 Restaurant & Brewing Company | 8131 Georgia Avenue        | Silver Spring | Montgomery      | 20910       | Jeremy Gruber            | 150000.00       | 125                    | 2011 | 
| Babe (A Boutique)                           | 910 S. Charles St          | Baltimore     | Baltimore City  | 21230       | Lisa Ponzoli             | 35000.00        | 0                      | 2011 | 
| Pemberton Caf?                              | 1100 Pemberton Drive       | Salisbury     | Wicomico        | 21801       | Avraham and Erin Failaev | 37476.00        | 3                      | 2011 | 
| Joie De Vivre Studios                       | 408 Race St                | Cambridge     | Dorchester      | 21613       | Joy Staniforth           | 90000.00        | 1                      | 2011 | 
| Limerick Pub                                | 11301 Elkin Street         | Wheaton       | Montgomery      | 20902       | Thomas Stanton           | 335000.00       | 20                     | 2011 | 
| Big Bad Woof                                | 5501 Baltimore Ave #501    | Hyattsville   | Prince George's | 20781       | Pennye Jones-Napier      | 134500.00       | 12                     | 2011 | 
| DeQuan's Construction LLC                   | 11 East Mount Royal Avenue | Baltimore     | Baltimore City  | 21202       | Claretta Rideout         | 250000.00       | 2                      | 2011 | 
| Tooney Town Early Learning Center           | 2221 Wheatley Drive        | Baltimore     | Baltimore City  | 21207       | Glenesa D Swann          | 100000.00       | 12                     | 2011 | 
| Riverside Country Inn                       | 204 N Main Street          | Greensboro    | Caroline        | 21639       | John Douglas Mutolo      | 148450.00       | 20                     | 2011 | 
```