# OIMT Spending Report to Legislature FY13-FY14

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/oimt-spending-report-to-legislature-fy13-fy14-7c1c7) |
| Metadata | [Link](https://data.hawaii.gov/api/views/fh6a-3v4q) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/fh6a-3v4q/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/fh6a-3v4q/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | fh6a-3v4q |
| Name | OIMT Spending Report to Legislature FY13-FY14 |
| Attribution | Office of Information Management and Technology |
| Category | Other |
| Tags | oimt, procurements, spending, acquisitions |
| Created | 2014-01-28T19:43:27Z |
| Publication Date | 2014-01-28T20:01:54Z |

## Description

OIMNT Spending Report to Legislature

## Columns

```ls
| Included | Schema Type    | Field Name       | Name             | Data Type | Render Type |
| ======== | ============== | ================ | ================ | ========= | =========== |
| No       | time           | :updated_at      | updated_at       | meta_data | meta_data   |
| Yes      | series tag     | reporting_period | Reporting Period | text      | text        |
| Yes      | series tag     | description      | Description      | text      | text        |
| Yes      | series tag     | entity           | Entity           | text      | text        |
| Yes      | series tag     | special          | Special          | text      | text        |
| Yes      | numeric metric | project_phase    | Project Phase /  | money     | money       |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:fh6a-3v4q d:2014-01-28T11:43:29.000Z t:description="01 - GovernanceOrganizational Change Management Facilitation and Specialized Training" t:entity=OIMT t:special=NO t:reporting_period="FY13 Launched" m:project_phase=250000

series e:fh6a-3v4q d:2014-01-28T11:43:29.000Z t:description="04 - ERP RFP for Program Management Consulting Support (OceanIt)" t:entity=OIMT t:special=Requested t:reporting_period="FY13 Launched" m:project_phase=3139742.2

series e:fh6a-3v4q d:2014-01-28T11:43:29.000Z t:description="04 - ERP RFP for ERP Enterprise Architecture Consulting Support (SAIC)" t:entity=OIMT t:special=Requested t:reporting_period="FY13 Launched" m:project_phase=2229955.27
```

## Meta Commands

```ls
metric m:project_phase p:double l:"Project Phase /" t:dataTypeName=money

entity e:fh6a-3v4q l:"OIMT Spending Report to Legislature FY13-FY14" t:attribution="Office of Information Management and Technology" t:url=https://data.hawaii.gov/api/views/fh6a-3v4q

property e:fh6a-3v4q t:meta.view v:id=fh6a-3v4q v:category=Other v:attributionLink=http://hawaii.gov/oimt v:averageRating=0 v:name="OIMT Spending Report to Legislature FY13-FY14" v:attribution="Office of Information Management and Technology"

property e:fh6a-3v4q t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:fh6a-3v4q t:meta.view.owner v:id=a5cm-ukuw v:profileImageUrlMedium=/api/users/a5cm-ukuw/profile_images/THUMB v:profileImageUrlLarge=/api/users/a5cm-ukuw/profile_images/LARGE v:screenName="OIMT Open Data Coordinator" v:profileImageUrlSmall=/api/users/a5cm-ukuw/profile_images/TINY v:displayName="OIMT Open Data Coordinator"

property e:fh6a-3v4q t:meta.view.tableauthor v:id=a5cm-ukuw v:profileImageUrlMedium=/api/users/a5cm-ukuw/profile_images/THUMB v:profileImageUrlLarge=/api/users/a5cm-ukuw/profile_images/LARGE v:screenName="OIMT Open Data Coordinator" v:profileImageUrlSmall=/api/users/a5cm-ukuw/profile_images/TINY v:roleName=publisher v:displayName="OIMT Open Data Coordinator"
```

## Top Records

```ls
| :updated_at | reporting_period | description                                                                           | entity | special   | project_phase | 
| =========== | ================ | ===================================================================================== | ====== | ========= | ============= | 
| 1390909409  |                  |                                                                                       |        |           |               | 
| 1390909409  | FY13 Launched    | 01 - GovernanceOrganizational Change Management Facilitation and Specialized Training | OIMT   | NO        | 250000        | 
| 1390909409  | FY13 Launched    | 04 - ERP RFP for Program Management Consulting Support (OceanIt)                      | OIMT   | Requested | 3139742.20    | 
| 1390909409  | FY13 Launched    | 04 - ERP RFP for ERP Enterprise Architecture Consulting Support (SAIC)                | OIMT   | Requested | 2229955.27    | 
| 1390909409  | FY13 Launched    | 04 - ERP ERP UCOA RFP                                                                 | OIMT   | No        | 585000        | 
| 1390909409  | FY13 Launched    | 04 - ERP Interim Budget Solution                                                      | OIMT   | No        | 1000000       | 
| 1390909409  | FY13 Launched    | 04 - ERP Assistance                                                                   | OIMT   | No        | 488951.25     | 
| 1390909409  | FY13 Launched    | 06 - Triage State Enterprise Server Version Compliance - zOS/CICS                     | ICSD   | No        | 310000.00     | 
| 1390909409  | FY13 Launched    | 06 - Triage State Datacenter Consolidated Server Storage                              | ICSD   | No        |               | 
| 1390909409  | FY13 Launched    | 06 - Triage Add Redundancy to Consolidated Enterprise Server (p-Series)               | ICSD   | No        |               | 
```