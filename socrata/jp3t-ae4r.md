# Contracts: ESD: South Coast: Fiscal Year 2014

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/contracts-esd-south-coast-fiscal-year-2014-c46c4) |
| Metadata | [Link](https://data.oregon.gov/api/views/jp3t-ae4r) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/jp3t-ae4r/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/jp3t-ae4r/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | jp3t-ae4r |
| Name | Contracts: ESD: South Coast: Fiscal Year 2014 |
| Category | Revenue & Expense |
| Tags | contracts, esd, south coast, fiscal year 2014 |
| Created | 2014-12-11T22:31:10Z |
| Publication Date | 2014-12-29T05:50:04Z |

## Description

Contacts for South Coast ESD for Fiscal Year 2014

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
| Yes      | numeric metric | award_amount               | Award Amount               | money     | money       |
```

## Time Field

```ls
Value = 2014
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = start_date_expiration_date
```

## Data Commands

```ls
series e:jp3t-ae4r d:2014-01-01T00:00:00.000Z t:esd_name="South Coast ESD" t:award_number=N/A t:award_type=Lease t:award_title=Communication t:contractor_information="Key Government" m:award_amount=53323.9 m:esd=1949

series e:jp3t-ae4r d:2014-01-01T00:00:00.000Z t:esd_name="South Coast ESD" t:award_number=N/A t:award_type=Lease t:award_title=Office t:contractor_information="Pitney Bowes" m:award_amount=2150.4 m:esd=1949

series e:jp3t-ae4r d:2014-01-01T00:00:00.000Z t:esd_name="South Coast ESD" t:award_number=N/A t:award_type=Lease t:award_title=Office t:contractor_information="Pitney Bowes" m:award_amount=7805.4 m:esd=1949
```

## Meta Commands

```ls
metric m:esd p:integer l:"ESD #" t:dataTypeName=number

metric m:award_amount p:double l:"Award Amount" t:dataTypeName=money

entity e:jp3t-ae4r l:"Contracts: ESD: South Coast: Fiscal Year 2014" t:url=https://data.oregon.gov/api/views/jp3t-ae4r

property e:jp3t-ae4r t:meta.view v:id=jp3t-ae4r v:category="Revenue & Expense" v:averageRating=0 v:name="Contracts: ESD: South Coast: Fiscal Year 2014"

property e:jp3t-ae4r t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:jp3t-ae4r t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| esd  | esd_name        | award_number | award_title   | award_type | contractor_information | start_date_expiration_date | award_amount | 
| ==== | =============== | ============ | ============= | ========== | ====================== | ========================== | ============ | 
| 1949 | South Coast ESD | N/A          | Communication | Lease      | Key Government         | 9/1/10-9/1/2015            | 53323.90     | 
| 1949 | South Coast ESD | N/A          | Office        | Lease      | Pitney Bowes           | 7/12-7/17                  | 2150.40      | 
| 1949 | South Coast ESD | N/A          | Office        | Lease      | Pitney Bowes           | 7/12-7/17                  | 7805.40      | 
| 1949 | South Coast ESD | N/A          | Office        | Lease      | Bay Area Copier        | 07/01/12-06/30/117         | 64380.00     | 
```