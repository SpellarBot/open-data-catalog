# Contracts: ESD: Clackamas: FY 2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/contracts-esd-clackamas-fy-2013-f9300) |
| Metadata | [Link](https://data.oregon.gov/api/views/yvx8-nqru) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/yvx8-nqru/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/yvx8-nqru/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | yvx8-nqru |
| Name | Contracts: ESD: Clackamas: FY 2013 |
| Category | Revenue & Expense |
| Tags | esd, clackamas esd, contracts, esd contracts, clackamas esd contracts |
| Created | 2013-11-26T21:32:28Z |
| Publication Date | 2013-11-26T21:36:04Z |

## Description

Summary of contracts for Clackamas ESD for Fiscal Year 2013

## Columns

```ls
| Included | Schema Type    | Field Name             | Name                   | Data Type     | Render Type   |
| ======== | ============== | ====================== | ====================== | ============= | ============= |
| Yes      | numeric metric | esd_1                  | ESD #                  | number        | number        |
| Yes      | series tag     | esd_2                  | ESD                    | text          | text          |
| Yes      | series tag     | unique_identifier      | Unique Identifier      | text          | text          |
| Yes      | series tag     | award_title            | Award Title            | text          | text          |
| Yes      | series tag     | award_type             | Award Type             | text          | text          |
| Yes      | series tag     | type_of_contract       | Type of Contract       | text          | text          |
| Yes      | series tag     | contractor_information | Contractor Information | text          | text          |
| No       |                | contractor_address     | Contractor Address     | text          | text          |
| Yes      | series tag     | contractor_city        | Contractor City        | text          | text          |
| Yes      | series tag     | contractor_state       | Contractor State       | text          | text          |
| Yes      | series tag     | contractor_zip         | Contractor Zip         | text          | text          |
| Yes      | time           | start_date             | Start Date             | calendar_date | calendar_date |
| No       |                | expiration_date        | Expiration Date        | calendar_date | calendar_date |
| Yes      | numeric metric | award_value            | Award Value            | number        | number        |
| Yes      | numeric metric | amendments             | Amendments             | number        | number        |
| Yes      | numeric metric | total_award_value      | Total Award Value      | money         | money         |
```

## Time Field

```ls
Value = start_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = contractor_address,expiration_date
```

## Data Commands

```ls
series e:yvx8-nqru d:2013-11-26T13:32:32.000Z t:type_of_contract=Material t:contractor_state=TX t:esd_2="Clackamas Educational Service District" t:contractor_city=Austin t:award_type="State Contract" t:contractor_information="Apple Computer" t:contractor_zip=78754 m:award_value=43000 m:total_award_value=43000 m:esd_1=1902

series e:yvx8-nqru d:2012-07-01T00:00:00.000Z t:type_of_contract=Personal t:unique_identifier="2012-13 Contract" t:contractor_state=OR t:esd_2="Clackamas Educational Service District" t:contractor_city=Sherwood t:award_type="Personal Services" t:award_title="Fiscal Services" t:contractor_information="Bizon Landscape Maintenance Company" t:contractor_zip=97140-9002 m:award_value=11706 m:total_award_value=11706 m:esd_1=1902

series e:yvx8-nqru d:2012-07-01T00:00:00.000Z t:type_of_contract=Personal t:unique_identifier="2012-13 Contract" t:contractor_state=OR t:esd_2="Clackamas Educational Service District" t:contractor_city="King City" t:award_type="Personal Services" t:award_title="Child Care Resource/Referral" t:contractor_information="Boyle EMS HazMat Education" t:contractor_zip=97224-2424 m:award_value=13220 m:total_award_value=13220 m:esd_1=1902
```

## Meta Commands

```ls
metric m:esd_1 p:integer l:"ESD #" t:dataTypeName=number

metric m:award_value p:double l:"Award Value" t:dataTypeName=number

metric m:amendments p:long l:Amendments t:dataTypeName=number

metric m:total_award_value p:double l:"Total Award Value" t:dataTypeName=money

entity e:yvx8-nqru l:"Contracts: ESD: Clackamas: FY 2013" t:url=https://data.oregon.gov/api/views/yvx8-nqru

property e:yvx8-nqru t:meta.view v:id=yvx8-nqru v:category="Revenue & Expense" v:averageRating=0 v:name="Contracts: ESD: Clackamas: FY 2013"

property e:yvx8-nqru t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:yvx8-nqru t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| esd_1 | esd_2                                  | unique_identifier | award_title                  | award_type                  | type_of_contract | contractor_information              | contractor_address                         | contractor_city | contractor_state | contractor_zip | start_date          | expiration_date     | award_value | amendments | total_award_value | 
| ===== | ====================================== | ================= | ============================ | =========================== | ================ | =================================== | ========================================== | =============== | ================ | ============== | =================== | =================== | =========== | ========== | ================= | 
| 1902  | Clackamas Educational Service District |                   |                              | State Contract              | Material         | Apple Computer                      | 2420 Ridgepoint Dr. Ms: 198Ew              | Austin          | TX               | 78754          |                     |                     | 43000.00    |            | 43000.00          | 
| 1902  | Clackamas Educational Service District | 2012-13 Contract  | Fiscal Services              | Personal Services           | Personal         | Bizon Landscape Maintenance Company | 25935 SW Grahams Ferry Rd.                 | Sherwood        | OR               | 97140-9002     | 2012-07-01T00:00:00 | 2012-12-31T00:00:00 | 11706.00    |            | 11706.00          | 
| 1902  | Clackamas Educational Service District | 2012-13 Contract  | Child Care Resource/Referral | Personal Services           | Personal         | Boyle EMS HazMat Education          | 12365 SW King George Dr.                   | King City       | OR               | 97224-2424     | 2012-07-01T00:00:00 | 2013-06-30T00:00:00 | 13220.00    |            | 13220.00          | 
| 1902  | Clackamas Educational Service District | 2012-13 WIA       |                              | Intergovernmental Agreement | IGA              | Canby SD 86                         | 1130 S Ivy St                              | Canby           | OR               | 97013-4230     | 2012-07-01T00:00:00 | 2013-06-30T00:00:00 | 15000.00    |            | 15000.00          | 
| 1902  | Clackamas Educational Service District | 530-Equipment     | Tagged Items                 | Price Agreement             | Material         | Captureworx, Inc.                   | 234 Curtis Drive                           | Longview        | WA               | 98632          | 2012-07-01T00:00:00 | 2013-06-30T00:00:00 | 39995.00    |            | 39995.00          | 
| 1902  | Clackamas Educational Service District | 2012-13 Contract  |                              | Price Agreement             | Material         | CDW Government, Inc.                | 230 N Milwaukee Ave                        | Vernon Hills    | IL               | 60061-4304     | 2012-07-01T00:00:00 | 2013-06-30T00:00:00 | 25063.36    |            | 25063.36          | 
| 1902  | Clackamas Educational Service District |                   | Network Info Services        | Utility Services            | Professional     | Century Link                        | PO Box 29080                               | Phoenix         | AZ               | 85038          |                     |                     | 28000.00    |            | 28000.00          | 
| 1902  | Clackamas Educational Service District | 2012-13 Contract  | Child Eval Center            | Personal Services           | Personal         | Christopher Ryder, Psy. D.          | Harbor Square, Sw #260 5520 SW Macadam Ave | Portland        | OR               | 97239-3768     | 2012-07-01T00:00:00 | 2013-06-30T00:00:00 | 48405.00    |            | 48405.00          | 
| 1902  | Clackamas Educational Service District | 2012-13 Contract  |                              | Intergovernmental Agreement | IGA              | Clackamas Community College         | 19600 S Molalla Ave                        | Oregon City     | OR               | 97045-8980     | 2012-07-01T00:00:00 | 2013-06-30T00:00:00 | 38736.00    |            | 38736.00          | 
| 1902  | Clackamas Educational Service District | 530-Equipment     | Assets                       | Intergovernmental Agreement | IGA              | Clackamas County Finance            | Dept. of Finance 2051 Kaen Rd              | Oregon City     | OR               | 97045-4035     | 2012-07-01T00:00:00 | 2013-06-30T00:00:00 | 14668.00    |            | 14668.00          | 
```