# Contracts: ESD: Clackamas: Fiscal Year 2014

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/contracts-esd-clackamas-fiscal-year-2014-6fd93) |
| Metadata | [Link](https://data.oregon.gov/api/views/2qg5-vxnh) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/2qg5-vxnh/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/2qg5-vxnh/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | 2qg5-vxnh |
| Name | Contracts: ESD: Clackamas: Fiscal Year 2014 |
| Category | Revenue & Expense |
| Tags | esd, clackamas esd, contracts, esd contracts, clackamas esd contracts 2014 |
| Created | 2014-12-16T18:36:49Z |
| Publication Date | 2014-12-28T22:23:36Z |

## Description

Summary of contracts for Clackamas ESD for Fiscal Year 2014

## Columns

```ls
| Included | Schema Type    | Field Name                                    | Name                                          | Data Type     | Render Type   |
| ======== | ============== | ============================================= | ============================================= | ============= | ============= |
| Yes      | numeric metric | esd                                           | ESD #                                         | number        | number        |
| Yes      | series tag     | esd_name                                      | ESD NAME                                      | text          | text          |
| Yes      | series tag     | po_no                                         | PO No.                                        | text          | number        |
| Yes      | series tag     | award_title                                   | Award Title                                   | text          | text          |
| Yes      | series tag     | award_type                                    | Award Type                                    | text          | text          |
| Yes      | series tag     | type_of_contract                              | Type of Contract                              | text          | text          |
| Yes      | series tag     | vendor_name                                   | Vendor Name                                   | text          | text          |
| Yes      | series tag     | street_address                                | Street Address                                | text          | text          |
| Yes      | time           | original_start_amendment_date_expiration_date | Original Start/Amendment Date/Expiration Date | calendar_date | calendar_date |
| Yes      | numeric metric | original_award_value                          | Original Award Value                          | money         | money         |
| Yes      | series tag     | amendment_value                               | Amendment Value                               | text          | text          |
| Yes      | numeric metric | total_award_value_w_amendments                | Total Award Value w/Amendments                | money         | money         |
```

## Time Field

```ls
Value = original_start_amendment_date_expiration_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:2qg5-vxnh d:2013-09-09T00:00:00.000Z t:esd_name="Clackamas Educational Service District" t:po_no=140316 t:award_title=OHSPP t:street_address="PO Box 547" t:vendor_name="Oregon Trail SD 46" m:total_award_value_w_amendments=116865 m:esd=1902 m:original_award_value=120204

series e:2qg5-vxnh d:2013-07-01T00:00:00.000Z t:type_of_contract="Contracts 2013-14" t:esd_name="Clackamas Educational Service District" t:po_no=140014 t:award_title="Network Info Services" t:street_address="22701 W 68th Ter" t:vendor_name="Perceptive Software" m:total_award_value_w_amendments=23784 m:esd=1902 m:original_award_value=23784

series e:2qg5-vxnh d:2013-07-19T00:00:00.000Z t:type_of_contract="Contracts 2013-14" t:esd_name="Clackamas Educational Service District" t:po_no=140474 t:award_title=WIA t:street_address="1130 S Ivy St" t:vendor_name="Canby SD 86" m:total_award_value_w_amendments=12245.76 m:esd=1902 m:original_award_value=15000
```

## Meta Commands

```ls
metric m:esd p:integer l:"ESD #" t:dataTypeName=number

metric m:original_award_value p:double l:"Original Award Value" t:dataTypeName=money

metric m:total_award_value_w_amendments p:double l:"Total Award Value w/Amendments" t:dataTypeName=money

entity e:2qg5-vxnh l:"Contracts: ESD: Clackamas: Fiscal Year 2014" t:url=https://data.oregon.gov/api/views/2qg5-vxnh

property e:2qg5-vxnh t:meta.view v:id=2qg5-vxnh v:category="Revenue & Expense" v:averageRating=0 v:name="Contracts: ESD: Clackamas: Fiscal Year 2014"

property e:2qg5-vxnh t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:2qg5-vxnh t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| esd  | esd_name                               | po_no  | award_title                    | award_type | type_of_contract  | vendor_name                  | street_address       | original_start_amendment_date_expiration_date | original_award_value | amendment_value | total_award_value_w_amendments | 
| ==== | ====================================== | ====== | ============================== | ========== | ================= | ============================ | ==================== | ============================================= | ==================== | =============== | ============================== | 
| 1902 | Clackamas Educational Service District | 140316 | OHSPP                          |            |                   | Oregon Trail SD 46           | PO Box 547           | 2013-09-09T00:00:00                           | 120204.00            |                 | 116865.00                      | 
| 1902 | Clackamas Educational Service District | 140014 | Network Info Services          |            | Contracts 2013-14 | Perceptive Software          | 22701 W 68th Ter     | 2013-07-01T00:00:00                           | 23784.00             |                 | 23784.00                       | 
| 1902 | Clackamas Educational Service District | 140474 | WIA                            |            | Contracts 2013-14 | Canby SD 86                  | 1130 S Ivy St        | 2013-07-19T00:00:00                           | 15000.00             |                 | 12245.76                       | 
| 1902 | Clackamas Educational Service District | 140098 | 060 Center - Special Education |            | IGA               | Canby SD 86                  | 1130 S Ivy St        | 2013-07-03T00:00:00                           | 6500.00              |                 | 6500.00                        | 
| 1902 | Clackamas Educational Service District | 140858 | WIA                            |            | Contracts         | Clackamas Community College  | 19600 S Molalla Ave  | 2014-01-10T00:00:00                           | 24528.62             |                 | 18434.51                       | 
| 1902 | Clackamas Educational Service District | 140245 | Fiscal Services                |            | Contracts 2012-13 | Showplace Landscape Services | PO Box 746           | 2013-08-08T00:00:00                           | 12707.00             |                 | 12707.00                       | 
| 1902 | Clackamas Educational Service District | 140077 | Child Care Resource/Referral   |            | Contracts 2013-14 | Yelena M Hennegan            | 1446 SW 23rd Court   | 2013-07-08T00:00:00                           | 2700.00              |                 | 1785.00                        | 
| 1902 | Clackamas Educational Service District | 140206 | 060 Center - Special Education |            | Contracts 2013-14 | The Hello Foundation, LLC    | PO BOX 623           | 2013-07-03T00:00:00                           | 46080.00             |                 | 44080.00                       | 
| 1902 | Clackamas Educational Service District | 140255 | Human Resources                |            | Contracts 2013-14 | The Danielson Group          | PO Box 7553          | 2013-08-16T00:00:00                           | 18000.00             |                 | 18000.00                       | 
| 1902 | Clackamas Educational Service District | 140062 | 060 Center - Special Education |            | Contracts 2013-14 | Lake Oswego SD 7Jt           | 2455 Country Club Rd | 2013-07-03T00:00:00                           | 1500.00              |                 | 1500.00                        | 
```