# Contracts: ESD: Jefferson: Fiscal Year 2014

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/contracts-esd-jefferson-fiscal-year-2014-8cf93) |
| Metadata | [Link](https://data.oregon.gov/api/views/jkem-ghbt) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/jkem-ghbt/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/jkem-ghbt/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | jkem-ghbt |
| Name | Contracts: ESD: Jefferson: Fiscal Year 2014 |
| Category | Revenue & Expense |
| Tags | jefferson county esd contracts, esd contracts, contracts, esd, education service district contracts, 2014 |
| Created | 2014-12-16T21:09:32Z |
| Publication Date | 2014-12-29T06:12:34Z |

## Description

Contracts for Jefferson County ESD for Fiscal Year 2014

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
Value = 2014
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = contractor_address,start_amend_exp_date
```

## Data Commands

```ls
series e:jkem-ghbt d:2014-01-01T00:00:00.000Z t:esd_name="Jefferson Co. Ed. Svc. District" t:contractor_state=OR t:contractor="Online Accounting Services" t:contractor_city=Dufur t:award=N/A t:award_type="Professional Services" t:award_title="Interpreting Services" t:contractor_zip=97021-0000 m:esd=2049 m:original_value=12000 m:total_value=12000

series e:jkem-ghbt d:2014-01-01T00:00:00.000Z t:esd_name="Jefferson Co. Ed. Svc. District" t:contractor_state=OR t:contractor="Santa Silvia Navarro-Bonilla" t:contractor_city=Culver t:award=N/A t:award_type="Professional Services" t:award_title="Interpreting Services" t:contractor_zip=97734-0000 m:esd=2049 m:original_value=331.25 m:total_value=331.25

series e:jkem-ghbt d:2014-01-01T00:00:00.000Z t:esd_name="Jefferson Co. Ed. Svc. District" t:contractor_state=OR t:contractor="Janet Pacheco" t:contractor_city=Madras t:award=N/A t:award_type="Professional Services" t:award_title="Interpreting Services" t:contractor_zip=97741-0000 m:esd=2049 m:original_value=1040.75 m:total_value=1040.75
```

## Meta Commands

```ls
metric m:esd p:integer l:ESD# t:dataTypeName=number

metric m:original_value p:double l:"Original Value" t:dataTypeName=money

metric m:total_value p:double l:"Total Value" t:dataTypeName=money

entity e:jkem-ghbt l:"Contracts: ESD: Jefferson: Fiscal Year 2014" t:url=https://data.oregon.gov/api/views/jkem-ghbt

property e:jkem-ghbt t:meta.view v:id=jkem-ghbt v:category="Revenue & Expense" v:averageRating=0 v:name="Contracts: ESD: Jefferson: Fiscal Year 2014"

property e:jkem-ghbt t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:jkem-ghbt t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| esd  | esd_name                        | award | award_title           | award_type            | contractor                   | contractor_address             | contractor_city | contractor_state | contractor_zip | start_amend_exp_date  | original_value | amendment_value | total_value | 
| ==== | =============================== | ===== | ===================== | ===================== | ============================ | ============================== | =============== | ================ | ============== | ===================== | ============== | =============== | =========== | 
| 2049 | Jefferson Co. Ed. Svc. District | N/A   | Interpreting Services | Professional Services | Online Accounting Services   | PO Box 485                     | Dufur           | OR               | 97021-0000     | 07/01/2013-06/30/2014 | 12000.00       |                 | 12000.00    | 
| 2049 | Jefferson Co. Ed. Svc. District | N/A   | Interpreting Services | Professional Services | Santa Silvia Navarro-Bonilla | PO Box 430                     | Culver          | OR               | 97734-0000     | 07/01/2013-06/30/2014 | 331.25         |                 | 331.25      | 
| 2049 | Jefferson Co. Ed. Svc. District | N/A   | Interpreting Services | Professional Services | Janet Pacheco                | 163 NE 11TH STREET             | Madras          | OR               | 97741-0000     | 07/01/2013-06/30/2014 | 1040.75        |                 | 1040.75     | 
| 2049 | Jefferson Co. Ed. Svc. District | N/A   | Student Services      | Professional Services | Marji Siebers                | 63970 Sunset Drive             | Bend            | OR               | 97701-0000     | 07/01/2013-06/30/2014 | 9000.00        |                 | 9000.00     | 
| 2049 | Jefferson Co. Ed. Svc. District | N/A   | Translation Services  | Professional Services | Keila Monroy                 | 126 NW B St SPC #6             | Madras          | OR               | 97741-0000     | 07/01/2013-06/30/2014 | 285.50         |                 | 285.50      | 
| 2049 | Jefferson Co. Ed. Svc. District | N/A   | Interpreting Services | Professional Services | Suedy Borja                  | PO Box 528                     | Madras          | OR               | 97741-0000     | 07/01/2013-06/30/2014 | 6392.50        |                 | 6392.50     | 
| 2049 | Jefferson Co. Ed. Svc. District | N/A   | Landscaping Services  | Professional Services | Jesse Rodriguez              | 451 SW J Street                | Madras          | OR               | 97741-0000     | 07/01/2013-06/30/2014 | 820.00         |                 | 820.00      | 
| 2049 | Jefferson Co. Ed. Svc. District | N/A   | Audit Preparation     | Professional Services | Casey Terada                 | PO Box 9388                    | Bend            | OR               | 97708-9388     | 07/01/2013-06/30/2014 | 1500.00        |                 | 1500.00     | 
| 2049 | Jefferson Co. Ed. Svc. District | N/A   | Audit Services        | Professional Services | Greer, Mahr & Assoc.         | 499 SW Upper Terrace Dr. Ste A | Bend            | OR               | 97708-0000     | 07/01/2013-06/30/2014 | 8770.00        |                 | 8770.00     | 
```