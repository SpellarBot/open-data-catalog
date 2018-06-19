# Contracts: ESD: Jefferson County: FY 2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/contracts-esd-jefferson-county-fy-2013-f0649) |
| Metadata | [Link](https://data.oregon.gov/api/views/yh3r-bunr) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/yh3r-bunr/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/yh3r-bunr/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | yh3r-bunr |
| Name | Contracts: ESD: Jefferson County: FY 2013 |
| Category | Revenue & Expense |
| Tags | jefferson county esd contracts, esd contracts, contracts, esd, education service district contracts, contract |
| Created | 2013-11-19T19:40:47Z |
| Publication Date | 2013-11-19T19:42:49Z |

## Columns

```ls
| Included | Schema Type    | Field Name           | Name                 | Data Type | Render Type |
| ======== | ============== | ==================== | ==================== | ========= | =========== |
| Yes      | numeric metric | esd                  | ESD#                 | number    | number      |
| Yes      | series tag     | esd_name             | ESD Name             | text      | text        |
| Yes      | series tag     | award                | Award #              | text      | text        |
| Yes      | series tag     | award_title          | Award Title          | text      | text        |
| Yes      | series tag     | award_type           | Award Type           | text      | text        |
| Yes      | series tag     | contractor           | Contractor           | text      | text        |
| No       |                | contractor_address   | Contractor Address   | text      | text        |
| Yes      | series tag     | contractor_city      | Contractor City      | text      | text        |
| Yes      | series tag     | contractor_state     | Contractor State     | text      | text        |
| Yes      | series tag     | contractor_zip       | Contractor Zip       | text      | text        |
| No       |                | start_amend_exp_date | Start/Amend/Exp Date | text      | text        |
| Yes      | numeric metric | original_value       | Original Value       | money     | money       |
| Yes      | series tag     | amendment_value      | Amendment Value      | text      | text        |
| Yes      | numeric metric | total_value          | Total Value          | money     | money       |
```

## Time Field

```ls
Value = 2013
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = contractor_address,start_amend_exp_date
```

## Data Commands

```ls
series e:yh3r-bunr d:2013-01-01T00:00:00.000Z t:esd_name="Jefferson Co. Ed. Svc. District" t:contractor_state=PA t:contractor="Pitney Bowes" t:contractor_city=Pittsburgh t:award=N/A t:award_type="Lease Agreement" t:award_title="Postage Meter Rental" t:contractor_zip=15250-7874 m:esd=2049 m:original_value=600 m:total_value=600

series e:yh3r-bunr d:2013-01-01T00:00:00.000Z t:esd_name="Jefferson Co. Ed. Svc. District" t:contractor_state=MO t:contractor="Associated Business Machines" t:contractor_city="St Louis" t:award=N/A t:award_type="Lease Agreement" t:award_title="Copy Machine Rental" t:contractor_zip=63179-0448 m:esd=2049 m:original_value=1788 m:total_value=1788

series e:yh3r-bunr d:2013-01-01T00:00:00.000Z t:esd_name="Jefferson Co. Ed. Svc. District" t:contractor_state=OR t:contractor="Keila Monroy" t:contractor_city=Madras t:award=N/A t:award_type="Professional Services" t:award_title="Translation Services" t:contractor_zip=97741-0000 m:esd=2049 m:original_value=1967.95 m:total_value=630.66
```

## Meta Commands

```ls
metric m:esd p:integer l:ESD# t:dataTypeName=number

metric m:original_value p:double l:"Original Value" t:dataTypeName=money

metric m:total_value p:double l:"Total Value" t:dataTypeName=money

entity e:yh3r-bunr l:"Contracts: ESD: Jefferson County: FY 2013" t:url=https://data.oregon.gov/api/views/yh3r-bunr

property e:yh3r-bunr t:meta.view v:id=yh3r-bunr v:category="Revenue & Expense" v:averageRating=0 v:name="Contracts: ESD: Jefferson County: FY 2013"

property e:yh3r-bunr t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:yh3r-bunr t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| esd  | esd_name                        | award | award_title           | award_type            | contractor                   | contractor_address             | contractor_city | contractor_state | contractor_zip | start_amend_exp_date | original_value | amendment_value | total_value | 
| ==== | =============================== | ===== | ===================== | ===================== | ============================ | ============================== | =============== | ================ | ============== | ==================== | ============== | =============== | =========== | 
| 2049 | Jefferson Co. Ed. Svc. District | N/A   | Postage Meter Rental  | Lease Agreement       | Pitney Bowes                 | PO Box 371874                  | Pittsburgh      | PA               | 15250-7874     | 7/1/2012-6/30/2013   | 600.00         |                 | 600.00      | 
| 2049 | Jefferson Co. Ed. Svc. District | N/A   | Copy Machine Rental   | Lease Agreement       | Associated Business Machines | PO Box 790448                  | St Louis        | MO               | 63179-0448     | 7/1/2012-6/30/2013   | 1788.00        |                 | 1788.00     | 
| 2049 | Jefferson Co. Ed. Svc. District | N/A   | Translation Services  | Professional Services | Keila Monroy                 | 126 NW B St SPC #6             | Madras          | OR               | 97741-0000     | 7/1/2012-6/30/2013   | 1967.95        |                 | 630.66      | 
| 2049 | Jefferson Co. Ed. Svc. District | N/A   | Interpreting Services | Professional Services | Suedy Borja                  | PO Box 528                     | Madras          | OR               | 97741-0000     | 7/1/2012-6/30/2013   | 1760.00        |                 | 4676.25     | 
| 2049 | Jefferson Co. Ed. Svc. District | N/A   | Landscaping Services  | Professional Services | Jesse Rodriguez              | 451 SW J Street                | Madras          | OR               | 97741-0000     | 7/1/2012-6/30/2013   | 270.00         |                 | 270.00      | 
| 2049 | Jefferson Co. Ed. Svc. District | N/A   | Audit Preparation     | Professional Services | Casey Terada                 | PO Box 9388                    | Bend            | OR               | 97708-9388     | 7/1/2012-6/30/2013   | 3000.00        |                 | 3000.00     | 
| 2049 | Jefferson Co. Ed. Svc. District | N/A   | Audit Services        | Professional Services | Greer, Mahr & Assoc.         | 499 SW Upper Terrace Dr. Ste A | Bend            | OR               | 97708-0000     | 7/1/2012-6/30/2013   | 8750.00        |                 | 8750.00     | 
```