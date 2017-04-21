# Contracts: ESD: South Coast: Fiscal Year 2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/contracts-esd-south-coast-fiscal-year-2013-3cb8d) |
| Metadata | [Link](https://data.oregon.gov/api/views/qhct-wumz) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/qhct-wumz/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/qhct-wumz/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | qhct-wumz |
| Name | Contracts: ESD: South Coast: Fiscal Year 2013 |
| Category | Revenue & Expense |
| Tags | contracts, esd, south coast, fiscal year 2013 |
| Created | 2013-10-31T19:29:54Z |
| Publication Date | 2013-10-31T19:31:39Z |

## Description

Contacts for South Coast ESD for Fiscal Year 2013

## Columns

```ls
| Included | Schema Type    | Field Name                 | Name                       | Data Type | Render Type |
| ======== | ============== | ========================== | ========================== | ========= | =========== |
| Yes      | numeric metric | esd                        | ESD #                      | number    | number      |
| Yes      | series tag     | esd_name                   | ESD Name                   | text      | text        |
| Yes      | series tag     | award_number               | Award Number               | text      | text        |
| Yes      | series tag     | award_title                | Award Title                | text      | text        |
| Yes      | series tag     | award_type                 | Award Type                 | text      | text        |
| Yes      | series tag     | contractor_information     | Contractor information     | text      | text        |
| No       |                | start_date_expiration_date | Start Date/Expiration Date | text      | text        |
| Yes      | numeric metric | award_amount               | Award Amount               | number    | number      |
```

## Time Field

```ls
Value = 2013
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = start_date_expiration_date
```

## Data Commands

```ls
series e:qhct-wumz d:2013-01-01T00:00:00.000Z t:esd_name="South Coast ESD" t:award_number=N/A t:award_type=Lease t:award_title=Server t:contractor_information=Dell m:award_amount=5181.87 m:esd=1949

series e:qhct-wumz d:2013-01-01T00:00:00.000Z t:esd_name="South Coast ESD" t:award_number=N/A t:award_type=Lease t:award_title=Server t:contractor_information=Dell m:award_amount=9540.72 m:esd=1949

series e:qhct-wumz d:2013-01-01T00:00:00.000Z t:esd_name="South Coast ESD" t:award_number=N/A t:award_type=Lease t:award_title=Communication t:contractor_information="Key Government" m:award_amount=53323.9 m:esd=1949
```

## Meta Commands

```ls
metric m:esd p:integer l:"ESD #" t:dataTypeName=number

metric m:award_amount p:double l:"Award Amount" t:dataTypeName=number

entity e:qhct-wumz l:"Contracts: ESD: South Coast: Fiscal Year 2013" t:url=https://data.oregon.gov/api/views/qhct-wumz

property e:qhct-wumz t:meta.view v:id=qhct-wumz v:category="Revenue & Expense" v:averageRating=0 v:name="Contracts: ESD: South Coast: Fiscal Year 2013"

property e:qhct-wumz t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:qhct-wumz t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| esd  | esd_name        | award_number | award_title   | award_type | contractor_information | start_date_expiration_date | award_amount       | 
| ==== | =============== | ============ | ============= | ========== | ====================== | ========================== | ================== | 
| 1949 | South Coast ESD | N/A          | Server        | Lease      | Dell                   | 7/1/10-6/30/14             | 5181.87            | 
| 1949 | South Coast ESD | N/A          | Server        | Lease      | Dell                   | 4/29/11-4/29/14            | 9540.7199999999993 | 
| 1949 | South Coast ESD | N/A          | Communication | Lease      | Key Government         | 9/1/10-9/1/2015            | 53323.9            | 
| 1949 | South Coast ESD | N/A          | Office        | Lease      | Pitney Bowes           | 9/08-9/12                  | 2880               | 
| 1949 | South Coast ESD | N/A          | Office        | Lease      | Pitney Bowes           | 9/08-9/12                  | 10740              | 
| 1949 | South Coast ESD | N/A          | Office        | Lease      | Bay Area Copier        | 07/01/12-06/30/117         | 64380              | 
```