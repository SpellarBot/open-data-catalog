# Contracts OR Judicial Dept (OJD): FY 2015-2016 Composite

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/contracts-or-judicial-dept-ojd-fy-2015-2016-composite-9fed4) |
| Metadata | [Link](https://data.oregon.gov/api/views/3wxk-gaen) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/3wxk-gaen/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/3wxk-gaen/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | 3wxk-gaen |
| Name | Contracts OR Judicial Dept (OJD): FY 2015-2016 Composite |
| Category | Revenue & Expense |
| Tags | contracts, oregon judicial contracts, oregon judicial; ojd; composite; 2016-2015; 2016; 2015; |
| Created | 2016-12-31T02:16:54Z |
| Publication Date | 2016-12-31T02:26:37Z |

## Description

This report provides contracting information on contracts & amendments issued for fiscal year 2015 - fiscal year 2016 for the Oregon Judicial Department. The contract values reflected in this report are estimates. For more information go to: http://www.oregon.gov/transparency/Pages/contracts.aspx#Oregon_Judicial_Department_-_Contracts%C2%A0

## Columns

```ls
| Included | Schema Type    | Field Name               | Name                     | Data Type     | Render Type   |
| ======== | ============== | ======================== | ======================== | ============= | ============= |
| No       |                | fiscal_year              | Fiscal Year              | number        | number        |
| Yes      | series tag     | award_number             | Award Number             | text          | text          |
| Yes      | series tag     | award_title              | Award Title              | text          | text          |
| Yes      | series tag     | award_type               | Award Type               | text          | text          |
| Yes      | series tag     | company_name             | Company Name             | text          | text          |
| No       |                | company_address          | Company Address          | text          | text          |
| Yes      | series tag     | city                     | City                     | text          | text          |
| Yes      | series tag     | state                    | State                    | text          | text          |
| Yes      | series tag     | zip_code                 | Zip Code                 | text          | number        |
| Yes      | series tag     | company_phone            | Company Phone            | text          | text          |
| Yes      | time           | contract_effective_date  | Contract Effective Date  | calendar_date | calendar_date |
| No       |                | contract_expiration_date | Contract Expiration Date | calendar_date | calendar_date |
| Yes      | numeric metric | original_contract_value  | Original Contract Value  | money         | money         |
| Yes      | numeric metric | total_amendments         | Total Amendments         | money         | money         |
| Yes      | numeric metric | total_contract_value     | Total Contract Value     | money         | money         |
```

## Time Field

```ls
Value = contract_effective_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = company_address,contract_expiration_date,fiscal_year
```

## Data Commands

```ls
series e:3wxk-gaen d:2014-07-16T00:00:00.000Z t:award_number=150480 t:zip_code=30313 t:company_name="Covendis Technologies" t:company_phone=770-903-9990 t:state=GA t:award_type=PSK t:award_title="WOC -Database Analyst II" t:city=Atlanta m:original_contract_value=73840

series e:3wxk-gaen d:2014-08-15T00:00:00.000Z t:award_number=150484 t:zip_code=48033 t:company_name=ImageSoft t:company_phone=248-948-8100 t:state=MI t:award_type=PSK t:award_title="Maintenance and Support Kofax and ImageSoft Software Only - Replaces ImageSoft ECM Solution M&S: OJD Contract No. 090098" t:city=Southfield m:original_contract_value=47806

series e:3wxk-gaen d:2014-08-05T00:00:00.000Z t:award_number=150487 t:zip_code=97205 t:company_name="Fortis Construction, Inc." t:company_phone=503-373-7196 t:state=OR t:award_type=PSK t:award_title="Supreme Court Building Exterior Rehabilitation" t:city=Portland m:original_contract_value=26172
```

## Meta Commands

```ls
metric m:original_contract_value p:double l:"Original Contract Value" t:dataTypeName=money

metric m:total_amendments p:double l:"Total Amendments" t:dataTypeName=money

metric m:total_contract_value p:double l:"Total Contract Value" t:dataTypeName=money

entity e:3wxk-gaen l:"Contracts OR Judicial Dept (OJD): FY 2015-2016 Composite" t:url=https://data.oregon.gov/api/views/3wxk-gaen

property e:3wxk-gaen t:meta.view v:id=3wxk-gaen v:category="Revenue & Expense" v:averageRating=0 v:name="Contracts OR Judicial Dept (OJD): FY 2015-2016 Composite"

property e:3wxk-gaen t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:3wxk-gaen t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| fiscal_year | award_number | award_title                                                                                                              | award_type | company_name                       | company_address                    | city        | state | zip_code | company_phone | contract_effective_date | contract_expiration_date | original_contract_value | total_amendments | total_contract_value | 
| =========== | ============ | ======================================================================================================================== | ========== | ================================== | ================================== | =========== | ===== | ======== | ============= | ======================= | ======================== | ======================= | ================ | ==================== | 
| 2015        | 150480       | WOC -Database Analyst II                                                                                                 | PSK        | Covendis Technologies              | 200 Walker St., Suite B            | Atlanta     | GA    | 30313    | 770-903-9990  | 2014-07-16T00:00:00     | 2015-01-23T00:00:00      | 73840.00                |                  |                      | 
| 2015        | 150484       | Maintenance and Support Kofax and ImageSoft Software Only - Replaces ImageSoft ECM Solution M&S: OJD Contract No. 090098 | PSK        | ImageSoft                          | 40 Oak Hollow, Suite 120           | Southfield  | MI    | 48033    | 248-948-8100  | 2014-08-15T00:00:00     | 2015-07-30T00:00:00      | 47806.00                |                  |                      | 
| 2015        | 150487       | Supreme Court Building Exterior Rehabilitation                                                                           | PSK        | Fortis Construction, Inc.          | 1705 SW Taylor Street              | Portland    | OR    | 97205    | 503-373-7196  | 2014-08-05T00:00:00     | 2015-11-19T00:00:00      | 26172.00                |                  |                      | 
| 2015        | 150488       | Reimbursement - flooring installation                                                                                    | IGA        | Umatilla County                    | 216 SE 4th Street                  | Pendleton   | OR    | 97801    | 541-276-7111  | 2015-03-18T00:00:00     | 2015-06-30T00:00:00      | 21252.98                |                  |                      | 
| 2015        | 150491       | SafeNet SAS-CLOUD SERVICE - Autentication Services                                                                       | SUB        | FishNet Security, Inc.             | 4800 SW Meadows Road, Suite 233422 | Lake Oswego | OR    | 97035    | 503-580-8023  | 2014-11-24T00:00:00     | 2017-11-24T00:00:00      | 9909.00                 |                  |                      | 
| 2015        | 150492       | Development and Maintenance of a Verification Stamp Custom Unity Script.                                                 | PSK        | ImageSoft                          | 40 Oak Hollow, Suite 120           | Southfield  | MI    | 48033    | 248-948-8100  | 2014-09-23T00:00:00     | 2015-11-01T00:00:00      | 6960.00                 |                  |                      | 
| 2015        | 150495       | Telecommunications Systems Management and Services                                                                       | IGA        | Lane Council of Governments (LCOG) | 151 W. 7th Ave,                    | Eugene      | OR    | 97401    | 541-682-4035  | 2014-11-18T00:00:00     | 2015-06-30T00:00:00      | 16205.00                |                  |                      | 
| 2015        | 150497       | air unit for the court                                                                                                   | IGA        | Polk County                        | 850 Main Street                    | Dallas      | OR    | 97338    | 503-623-1888  | 2014-12-10T00:00:00     | 2015-06-30T00:00:00      | 12000.00                |                  |                      | 
| 2015        | 150500       | Environmental Survey: Surpeme Court Building Exterior Rehabililitation Project                                           | PSK        | Apex Enviornmental                 | PO Box 1455                        | Wilsonville | OR    | 97470    | 503-373-7196  | 2014-10-02T00:00:00     | 2015-12-31T00:00:00      | 25000.00                |                  |                      | 
| 2015        | 150502       | Evaluation Testing                                                                                                       | PSK        | David M. Corey, Ph.D.              | 5285 SW Meadows Road, Suite 311    | Lake Oswego | OR    | 97035    | 503-620-8050  | 2014-12-03T00:00:00     | 2016-06-30T00:00:00      | 5000.00                 |                  |                      | 
```