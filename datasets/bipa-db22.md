# 2015 Public Bonds Data As of June 30, 2015

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2015-public-bonds-data-as-of-june-30-2015) |
| Metadata | [Link](https://data.mo.gov/api/views/bipa-db22) |
| Data: JSON | [100 Rows](https://data.mo.gov/api/views/bipa-db22/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.mo.gov/api/views/bipa-db22/rows.csv?max_rows=100) |
| Host | data.mo.gov |
| Id | bipa-db22 |
| Name | 2015 Public Bonds Data As of June 30, 2015 |
| Category | Government Administration |
| Created | 2015-07-02T15:22:20Z |
| Publication Date | 2015-07-02T15:24:03Z |

## Description

The data provided here details the State of Missouri's Public Bonds Data as of June 30, 2015.

## Columns

```ls
| Included | Schema Type    | Field Name                    | Name                          | Data Type     | Render Type   |
| ======== | ============== | ============================= | ============================= | ============= | ============= |
| Yes      | series tag     | political_subdivision_name    | Political Subdivision Name    | text          | text          |
| Yes      | time           | date_of_issuance              | Date of Issuance              | calendar_date | calendar_date |
| Yes      | series tag     | bond_name                     | Bond Name                     | text          | text          |
| Yes      | series tag     | description_of_revenue_stream | Description of Revenue Stream | text          | text          |
| Yes      | numeric metric | face_amount                   | Face Amount                   | number        | number        |
| Yes      | series tag     | outstanding_balance           | Outstanding Balance           | text          | text          |
| Yes      | series tag     | description_of_project        | Description of Project        | text          | text          |
| Yes      | series tag     | interest_rate                 | Interest Rate                 | text          | text          |
```

## Time Field

```ls
Value = date_of_issuance
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:bipa-db22 d:2012-04-26T00:00:00.000Z t:outstanding_balance="NOT PROVIDED" t:description_of_revenue_stream=N/A t:bond_name="RELATING TO -$39,470,000 SUBORDINATE TRANSPORTATION REVENUE NOTE, SERIES 2011" t:political_subdivision_name="370/MISSOURI BOTTOM ROAD/TAUSSIG ROAD TRANSPORTATION DEVELOPMENT" t:interest_rate="NOT PROVIDED" t:description_of_project="NOT PROVIDED" m:face_amount=1258265

series e:bipa-db22 d:2012-07-26T00:00:00.000Z t:outstanding_balance="NOT PROVIDED" t:description_of_revenue_stream=N/A t:bond_name="RELATING TO -$2,845,502.23 JUNIOR SUBORDINATE TRANSPORTATION REVENUE NOTE, SERIES 2012" t:political_subdivision_name="370/MISSOURI BOTTOM ROAD/TAUSSIG ROAD TRANSPORTATION DEVELOPMENT" t:interest_rate="NOT PROVIDED" t:description_of_project="NOT PROVIDED" m:face_amount=2845502

series e:bipa-db22 d:2009-08-31T00:00:00.000Z t:outstanding_balance="NOT PROVIDED" t:description_of_revenue_stream=N/A t:bond_name="RELATING TO -$39,470,000 SUBORDINATE TRANSPORTATION REVENUE NOTE, SERIES 2009" t:political_subdivision_name="370/MISSOURI BOTTOM ROAD/TAUSSIG ROAD TRANSPORTATION DEVELOPMENT" t:interest_rate="NOT PROVIDED" t:description_of_project="NOT PROVIDED" m:face_amount=942682
```

## Meta Commands

```ls
metric m:face_amount p:long l:"Face Amount" t:dataTypeName=number

entity e:bipa-db22 l:"2015 Public Bonds Data As of June 30, 2015" t:url=https://data.mo.gov/api/views/bipa-db22

property e:bipa-db22 t:meta.view v:id=bipa-db22 v:category="Government Administration" v:averageRating=0 v:name="2015 Public Bonds Data As of June 30, 2015"

property e:bipa-db22 t:meta.view.license v:name="Public Domain"

property e:bipa-db22 t:meta.view.owner v:id=4cdh-4my4 v:screenName=Dwight v:displayName=Dwight

property e:bipa-db22 t:meta.view.tableauthor v:id=4cdh-4my4 v:screenName=Dwight v:roleName=editor v:displayName=Dwight
```

## Top Records

```ls
| political_subdivision_name                                       | date_of_issuance    | bond_name                                                                              | description_of_revenue_stream | face_amount | outstanding_balance | description_of_project | interest_rate | 
| ================================================================ | =================== | ====================================================================================== | ============================= | =========== | =================== | ====================== | ============= | 
| 370/MISSOURI BOTTOM ROAD/TAUSSIG ROAD TRANSPORTATION DEVELOPMENT | 2012-04-26T00:00:00 | RELATING TO -$39,470,000 SUBORDINATE TRANSPORTATION REVENUE NOTE, SERIES 2011          | N/A                           | 1258265     | NOT PROVIDED        | NOT PROVIDED           | NOT PROVIDED  | 
| 370/MISSOURI BOTTOM ROAD/TAUSSIG ROAD TRANSPORTATION DEVELOPMENT | 2012-07-26T00:00:00 | RELATING TO -$2,845,502.23 JUNIOR SUBORDINATE TRANSPORTATION REVENUE NOTE, SERIES 2012 | N/A                           | 2845502     | NOT PROVIDED        | NOT PROVIDED           | NOT PROVIDED  | 
| 370/MISSOURI BOTTOM ROAD/TAUSSIG ROAD TRANSPORTATION DEVELOPMENT | 2009-08-31T00:00:00 | RELATING TO -$39,470,000 SUBORDINATE TRANSPORTATION REVENUE NOTE, SERIES 2009          | N/A                           | 942682      | NOT PROVIDED        | NOT PROVIDED           | NOT PROVIDED  | 
| 370/MISSOURI BOTTOM ROAD/TAUSSIG ROAD TRANSPORTATION DEVELOPMENT | 2010-08-31T00:00:00 | RELATING TO -$39,470,000 SUBORDINATE TRANSPORTATION REVENUE NOTE, SERIES 2010          | N/A                           | 1455471     | NOT PROVIDED        | NOT PROVIDED           | NOT PROVIDED  | 
| 370/MISSOURI BOTTOM ROAD/TAUSSIG ROAD TRANSPORTATION DEVELOPMENT | 2005-09-01T00:00:00 | RELATING TO -$791,506.62 SUBORDINATE TRANSPORTATION REVENUE NOTE, SERIES 2005          | N/A                           | 791506      | NOT PROVIDED        | NOT PROVIDED           | NOT PROVIDED  | 
| 370/MISSOURI BOTTOM ROAD/TAUSSIG ROAD TRANSPORTATION DEVELOPMENT | 2002-11-05T00:00:00 | RELATING TO -$39,470,000 TRANSPORTATION REVENUE BONDS, SERIES 2002                     | N/A                           | 3947000     | NOT PROVIDED        | NOT PROVIDED           | NOT PROVIDED  | 
| 370/MISSOURI BOTTOM ROAD/TAUSSIG ROAD TRANSPORTATION DEVELOPMENT | 2007-12-01T00:00:00 | RELATING TO -$39,470,000 SUBORDINATE TRANSPORTATION REVENUE NOTE, SERIES 2006          | N/A                           | 1831687     | NOT PROVIDED        | NOT PROVIDED           | NOT PROVIDED  | 
| 370/MISSOURI BOTTOM ROAD/TAUSSIG ROAD TRANSPORTATION DEVELOPMENT | 2007-12-01T00:00:00 | RELATING TO -$39,470,000 SUBORDINATE TRANSPORTATION REVENUE NOTE, SERIES 2007          | N/A                           | 1943543     | NOT PROVIDED        | NOT PROVIDED           | NOT PROVIDED  | 
| 370/MISSOURI BOTTOM ROAD/TAUSSIG ROAD TRANSPORTATION DEVELOPMENT | 2008-12-01T00:00:00 | RELATING TO -$39,470,000 SUBORDINATE TRANSPORTATION REVENUE BONDS, SERIES 2008         | N/A                           | 896781      | NOT PROVIDED        | NOT PROVIDED           | NOT PROVIDED  | 
| ACADEMIE LAFAYETTE                                               | 2004-02-01T00:00:00 | BOA                                                                                    | STATE AND LOCAL FUNDS         | 2310000     | 0.00                | OAK PURCHASE           | 1.63          | 
```