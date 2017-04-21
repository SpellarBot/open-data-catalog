# Local Development Corporations Grants Dataset

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/local-development-corporations-grants-dataset) |
| Metadata | [Link](https://data.ny.gov/api/views/j5ab-5nj2) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/j5ab-5nj2/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/j5ab-5nj2/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | j5ab-5nj2 |
| Name | Local Development Corporations Grants Dataset |
| Attribution | Individual Local Development Corporations submitted to Authorities Budget Office |
| Category | Transparency |
| Tags | ldc grants |
| Created | 2015-03-16T17:14:02Z |
| Publication Date | 2016-10-06T16:40:06Z |

## Description

Public authorities are required by Section 2800 of Public Authorities Law to submit annual reports to the Authorities Budget Office that include grants data. Local development corporations are required to report information on the projects they support and how those approved projects are financed (either through grants, loans, or bonds). The dataset consists of grants data reported by Local Development Corporations beginning with fiscal years ending in 2011.

## Columns

```ls
| Included | Schema Type    | Field Name            | Name                  | Data Type     | Render Type   |
| ======== | ============== | ===================== | ===================== | ============= | ============= |
| Yes      | series tag     | authority_name        | Authority Name        | text          | text          |
| Yes      | time           | fiscal_year_end_date  | Fiscal Year End Date  | calendar_date | calendar_date |
| Yes      | series tag     | awarded_grants        | Awarded Grants        | text          | text          |
| Yes      | series tag     | grant_fund_sources    | Grant Fund Sources    | text          | text          |
| Yes      | series tag     | recipient_name        | Recipient Name        | text          | text          |
| Yes      | series tag     | recipient_city        | Recipient City        | text          | text          |
| Yes      | series tag     | recipient_state       | Recipient State       | text          | text          |
| Yes      | series tag     | recipient_postal_code | Recipient Postal Code | text          | text          |
| Yes      | numeric metric | grant_amount          | Grant Amount          | money         | money         |
| No       |                | date_grant_awarded    | Date Grant Awarded    | calendar_date | calendar_date |
| Yes      | series tag     | grant_purpose         | Grant Purpose         | text          | text          |
| Yes      | series tag     | new_jobs              | New Jobs              | text          | text          |
| Yes      | numeric metric | jobs_planned          | Jobs Planned          | number        | number        |
| Yes      | numeric metric | jobs_created          | Jobs Created          | number        | number        |
```

## Time Field

```ls
Value = fiscal_year_end_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = date_grant_awarded
```

## Data Commands

```ls
series e:j5ab-5nj2 d:2011-03-31T00:00:00.000Z t:authority_name="Salamanca Area Development Corporation" t:recipient_city=SALAMANCA t:recipient_postal_code=14779 t:new_jobs=Yes t:recipient_state=NY t:grant_purpose="Business Expansion/Startup" t:grant_fund_sources=State t:recipient_name="Snyder Manufacturing" m:grant_amount=97359 m:jobs_created=5 m:jobs_planned=5

series e:j5ab-5nj2 d:2011-12-31T00:00:00.000Z t:authority_name="St. Lawrence County Local Development Corporation" t:recipient_city=GOUVERNEUR t:recipient_postal_code=13642 t:new_jobs=Yes t:recipient_state=NY t:grant_purpose="Business Expansion/Startup" t:grant_fund_sources=Federal t:recipient_name="Ablan's Business Center, Inc." m:grant_amount=15750 m:jobs_created=2 m:jobs_planned=1

series e:j5ab-5nj2 d:2011-12-31T00:00:00.000Z t:authority_name="St. Lawrence County Local Development Corporation" t:recipient_city=LISBON t:recipient_postal_code=13658 t:new_jobs=Yes t:recipient_state=NY t:grant_purpose="Business Expansion/Startup" t:grant_fund_sources=Federal t:recipient_name="New Horizons Wireless" m:grant_amount=35000 m:jobs_created=1 m:jobs_planned=1
```

## Meta Commands

```ls
metric m:grant_amount p:double l:"Grant Amount" d:"Amount of the grant awarded" t:dataTypeName=money

metric m:jobs_planned p:integer l:"Jobs Planned" d:"Number of jobs planned to be created as a result of the grant. This field is blank if the authority indicated that the grant was not expected to result in new jobs being created or there were no grants." t:dataTypeName=number

metric m:jobs_created p:integer l:"Jobs Created" d:"Number of jobs created as a result of the grant. This field is blank if the authority indicated that the grant was not expected to result in new jobs being created or if there were no grants." t:dataTypeName=number

entity e:j5ab-5nj2 l:"Local Development Corporations Grants Dataset" t:attribution="Individual Local Development Corporations submitted to Authorities Budget Office" t:url=https://data.ny.gov/api/views/j5ab-5nj2

property e:j5ab-5nj2 t:meta.view v:id=j5ab-5nj2 v:category=Transparency v:attributionLink=http://www.abo.ny.gov/ v:averageRating=0 v:name="Local Development Corporations Grants Dataset" v:attribution="Individual Local Development Corporations submitted to Authorities Budget Office"

property e:j5ab-5nj2 t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:j5ab-5nj2 t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:j5ab-5nj2 t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| authority_name                                    | fiscal_year_end_date | awarded_grants | grant_fund_sources | recipient_name                | recipient_city | recipient_state | recipient_postal_code | grant_amount | date_grant_awarded  | grant_purpose                                                            | new_jobs | jobs_planned | jobs_created | 
| ================================================= | ==================== | ============== | ================== | ============================= | ============== | =============== | ===================== | ============ | =================== | ======================================================================== | ======== | ============ | ============ | 
| Salamanca Area Development Corporation            | 2011-03-31T00:00:00  |                | State              | Snyder Manufacturing          | SALAMANCA      | NY              | 14779                 | 97359.00     | 2010-02-02T00:00:00 | Business Expansion/Startup                                               | Yes      | 5            | 5            | 
| St. Lawrence County Local Development Corporation | 2011-12-31T00:00:00  |                | Federal            | Ablan's Business Center, Inc. | GOUVERNEUR     | NY              | 13642                 | 15750.00     | 2011-02-09T00:00:00 | Business Expansion/Startup                                               | Yes      | 1            | 2            | 
| St. Lawrence County Local Development Corporation | 2011-12-31T00:00:00  |                | Federal            | New Horizons Wireless         | LISBON         | NY              | 13658                 | 35000.00     | 2011-01-12T00:00:00 | Business Expansion/Startup                                               | Yes      | 1            | 1            | 
| Livingston County Development Corporation         | 2011-12-31T00:00:00  |                | Municipal          | Barbara Baldwin               | NUNDA          | NY              | 14517                 | 5750.00      | 2011-09-09T00:00:00 | Commercial Property Construction/Acquisition/Revitalization/Improvement  | No       |              |              | 
| Cohoes Local Development Corporation              | 2011-12-31T00:00:00  |                | Federal            | Commerecial Investigations    | COHOES         | NY              | 12047                 | 10000.00     | 2011-08-08T00:00:00 | Business Expansion/Startup                                               | Yes      | 5            | 3            | 
| Cohoes Local Development Corporation              | 2011-12-31T00:00:00  |                | State              | Mike Flatley                  | COHOES         | NY              | 12047                 | 1000.00      | 2011-05-13T00:00:00 | Residential Property Construction/Acquisition/Rehabilitation/Improvement | No       |              |              | 
| Cohoes Local Development Corporation              | 2011-12-31T00:00:00  |                | Private            | The Foundry                   | COHOES         | NY              | 12047                 | 25000.00     | 2011-06-29T00:00:00 | Commercial Property Construction/Acquisition/Revitalization/Improvement  | Yes      | 2            | 2            | 
| Cohoes Local Development Corporation              | 2011-12-31T00:00:00  |                | State              | Chlandra Lee                  | COHOES         | NY              | 12047                 | 7225.00      | 2011-03-01T00:00:00 | Commercial Property Construction/Acquisition/Revitalization/Improvement  | No       |              |              | 
| Cohoes Local Development Corporation              | 2011-12-31T00:00:00  |                | Federal            | Linda Russell                 | COHOES         | NY              | 12047                 | 275.00       | 2011-04-28T00:00:00 | Residential Property Construction/Acquisition/Rehabilitation/Improvement | No       |              |              | 
| Cohoes Local Development Corporation              | 2011-12-31T00:00:00  |                | Federal            | City of Cohoes                | COHOES         | NY              | 12047                 | 11600.00     | 2011-03-31T00:00:00 | Residential Property Construction/Acquisition/Rehabilitation/Improvement | No       |              |              | 
```