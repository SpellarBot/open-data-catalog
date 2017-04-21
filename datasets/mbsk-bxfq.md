# Banking Institution History: Beginning 1784

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/banking-institution-history-beginning-1784) |
| Metadata | [Link](https://data.ny.gov/api/views/mbsk-bxfq) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/mbsk-bxfq/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/mbsk-bxfq/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | mbsk-bxfq |
| Name | Banking Institution History: Beginning 1784 |
| Attribution | New York State Department of Financial Services |
| Category | Government & Finance |
| Tags | banking, institution, history |
| Created | 2013-03-05T22:19:53Z |
| Publication Date | 2017-04-05T22:20:02Z |

## Description

This file contains a history of banking institutions that are, or were, state chartered, as well as most federally chartered institutions that have operated in the state of New York.  Events in the life cycle of institutions are listed by date.

## Columns

```ls
| Included | Schema Type | Field Name                      | Name                              | Data Type | Render Type |
| ======== | =========== | =============================== | ================================= | ========= | =========== |
| Yes      | series tag  | institution_name_primary        | Institution Name Primary          | text      | text        |
| Yes      | series tag  | identification_number_primary   | Identification Number Primary     | text      | text        |
| Yes      | series tag  | type                            | Type                              | text      | text        |
| Yes      | time        | event_date                      | Event Date                        | text      | text        |
| Yes      | series tag  | event_type                      | Event Type                        | text      | text        |
| Yes      | series tag  | institution_name_secondary      | Institution Name (Secondary)      | text      | text        |
| Yes      | series tag  | identification_number_secondary | Identification Number (Secondary) | text      | text        |
```

## Time Field

```ls
Value = event_date
Format & Zone = yyyyMMdd
```

## Data Commands

```ls
series e:mbsk-bxfq d:1992-06-25T00:00:00.000Z t:identification_number_primary=0460101 t:event_type="Merge To State" t:institution_name_primary="A. T. & M. Corp. Employees Credit Union" t:identification_number_secondary=0460507 t:institution_name_secondary="Erie County Employees Credit Union" t:type="Credit Unions" m:row_number.mbsk-bxfq=1

series e:mbsk-bxfq d:1940-06-17T00:00:00.000Z t:identification_number_primary=8300046 t:event_type="NYS Chartered" t:institution_name_primary="A.P.W. Employees Credit Union" t:institution_name_secondary="A.P.W. Employees Credit Union" t:type="Former Credit Union" m:row_number.mbsk-bxfq=2

series e:mbsk-bxfq d:1956-02-14T00:00:00.000Z t:identification_number_primary=8300046 t:event_type=Liquidated t:institution_name_primary="A.P.W. Employees Credit Union" t:type="Former Credit Union" m:row_number.mbsk-bxfq=3
```

## Meta Commands

```ls
metric m:row_number.mbsk-bxfq p:long l:"Row Number"

entity e:mbsk-bxfq l:"Banking Institution History: Beginning 1784" t:attribution="New York State Department of Financial Services" t:url=https://data.ny.gov/api/views/mbsk-bxfq

property e:mbsk-bxfq t:meta.view v:id=mbsk-bxfq v:category="Government & Finance" v:attributionLink=http://www.dfs.ny.gov/about/auhistory.htm v:averageRating=0 v:name="Banking Institution History: Beginning 1784" v:attribution="New York State Department of Financial Services"

property e:mbsk-bxfq t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:mbsk-bxfq t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:mbsk-bxfq t:meta.view.metadata.custom_fields.common_core v:Contact_Email=opendata@its.ny.gov v:Publisher="State of New York" v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| institution_name_primary                | identification_number_primary | type                           | event_date | event_type     | institution_name_secondary               | identification_number_secondary | 
| ======================================= | ============================= | ============================== | ========== | ============== | ======================================== | =============================== | 
| A. T. & M. Corp. Employees Credit Union | 0460101                       | Credit Unions                  | 19920625   | Merge To State | Erie County Employees Credit Union       | 0460507                         | 
| A.P.W. Employees Credit Union           | 8300046                       | Former Credit Union            | 19400617   | NYS Chartered  | A.P.W. Employees Credit Union            |                                 | 
| A.P.W. Employees Credit Union           | 8300046                       | Former Credit Union            | 19560214   | Liquidated     |                                          |                                 | 
| Aareal Bank AG                          | 2270181                       | Foreign Representative Offices | 20011123   | Licensed       | DePfa Bank AG                            |                                 | 
| Aareal Bank AG                          | 2270181                       | Foreign Representative Offices | 20020807   | Name Change To | Aareal Bank AG                           |                                 | 
| Aareal Bank AG                          | 2270181                       | Foreign Representative Offices | 20080314   | Closed         |                                          |                                 | 
| Abingdon Square Savings Bank            | 8100092                       | Former Savings Bank            | 18690000   | Established    | Abingdon Square Savings Bank             |                                 | 
| Abingdon Square Savings Bank            | 8100092                       | Former Savings Bank            | 18760801   | Failed         |                                          |                                 | 
| Adam, Meldrum & Anderson State Bank     | 0000099                       | Bank                           | 19230000   | Established    | Adam, Meldrum & Anderson State Bank, The |                                 | 
| Adam, Meldrum & Anderson State Bank     | 0000099                       | Bank                           | 19560307   | Merge To State | Manufacturers and Traders Trust Company  | 0113003                         | 
```