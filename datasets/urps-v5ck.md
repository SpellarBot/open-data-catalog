# State of Iowa Revenue

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/state-of-iowa-revenue) |
| Metadata | [Link](https://data.iowa.gov/api/views/urps-v5ck) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/urps-v5ck/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/urps-v5ck/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | urps-v5ck |
| Name | State of Iowa Revenue |
| Attribution | Iowa Department of Administrative Services, State Accounting Enterprise, I3 Data Warehouse |
| Category | Government |
| Tags | financial, resources, revenue |
| Created | 2014-11-06T21:01:01Z |
| Publication Date | 2014-12-01T20:32:54Z |

## Description

This dataset provides information on state revenue for fiscal years starting July 1, 2011 through the current fiscal year, year to date, from the state's centralized accounting system.  The revenue are summarized by Fiscal Year, Month, Fund, Appropriation, Department, Unit, and Revenue Class. The state fiscal year runs from July 1 to the following June 30 and is numbered for the calendar year in which it ends. The State of Iowa operates on a modified accrual basis which provides that encumbrances on June 30 must be paid within 60 days after year end.

## Columns

```ls
| Included | Schema Type    | Field Name         | Name               | Data Type | Render Type |
| ======== | ============== | ================== | ================== | ========= | =========== |
| No       | time           | :updated_at        | updated_at         | meta_data | meta_data   |
| Yes      | numeric metric | budget_fy          | Budget FY          | number    | number      |
| Yes      | numeric metric | fiscal_period      | Fiscal Period      | number    | number      |
| Yes      | series tag     | fiscal_period_name | Fiscal Period Name | text      | text        |
| Yes      | series tag     | function           | Function           | text      | text        |
| Yes      | series tag     | spec_dept          | Spec Dept          | text      | text        |
| Yes      | series tag     | dept_1             | Dept #             | text      | text        |
| Yes      | series tag     | dept_2             | Dept               | text      | text        |
| Yes      | series tag     | fund               | Fund               | text      | text        |
| Yes      | series tag     | fund_name          | Fund Name          | text      | text        |
| Yes      | series tag     | unit               | Unit               | text      | text        |
| Yes      | series tag     | unit_name          | Unit Name          | text      | text        |
| Yes      | series tag     | appropriation      | Appropriation      | text      | text        |
| Yes      | series tag     | appropriation_name | Appropriation Name | text      | text        |
| Yes      | numeric metric | revenue_class      | Revenue Class      | number    | text        |
| Yes      | series tag     | revenue_class_name | Revenue Class Name | text      | text        |
| Yes      | numeric metric | amount             | Amount             | money     | money       |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:urps-v5ck d:2014-11-06T13:01:20.000Z t:fund_name="General Fund" t:spec_dept="General Fund Use" t:unit=2175 t:fiscal_period_name=March t:revenue_class_name=Other t:appropriation=0000 t:dept_2=Fees t:dept_1=996 t:appropriation_name="Blank Appropriation" t:fund=0001 t:unit_name="Real Estate" t:function="General Fund Use Only" m:amount=9000 m:budget_fy=2012 m:fiscal_period=9 m:revenue_class=704

series e:urps-v5ck d:2014-11-06T13:01:15.000Z t:fund_name="General Fund" t:spec_dept="Human Services, Department of" t:unit=1227 t:fiscal_period_name=January t:revenue_class_name=Other t:appropriation=M30 t:dept_2="Human Services - Cherokee" t:dept_1=407 t:appropriation_name="Cherokee MHI" t:fund=0001 t:unit_name=Laundry t:function="Human Services" m:amount=341.25 m:budget_fy=2012 m:fiscal_period=7 m:revenue_class=704

series e:urps-v5ck d:2014-11-06T13:01:25.000Z t:fund_name="IPTV- Misc" t:spec_dept="Education, Department of" t:unit=2030 t:fiscal_period_name=May t:revenue_class_name=Interest t:appropriation=0000 t:dept_2="Iowa Public Television" t:dept_1=285 t:appropriation_name="Blank Appropriation" t:fund=0085 t:unit_name="Iptv Miscellaneous" t:function=Education m:amount=19.54 m:budget_fy=2012 m:fiscal_period=11 m:revenue_class=301
```

## Meta Commands

```ls
metric m:budget_fy p:integer l:"Budget FY" d:"Budget Fiscal Year revenue was received" t:dataTypeName=number

metric m:fiscal_period p:integer l:"Fiscal Period" d:"Fiscal Period (1 -15) the revenue was received" t:dataTypeName=number

metric m:revenue_class p:integer l:"Revenue Class" d:"The code used to designate the type of revenue" t:dataTypeName=number

metric m:amount p:double l:Amount d:"Total of all revenues for the specified combination of Budget FY, Fund, Department, etc" t:dataTypeName=money

entity e:urps-v5ck l:"State of Iowa Revenue" t:attribution="Iowa Department of Administrative Services, State Accounting Enterprise, I3 Data Warehouse" t:url=https://data.iowa.gov/api/views/urps-v5ck

property e:urps-v5ck t:meta.view v:id=urps-v5ck v:category=Government v:averageRating=0 v:name="State of Iowa Revenue" v:attribution="Iowa Department of Administrative Services, State Accounting Enterprise, I3 Data Warehouse"

property e:urps-v5ck t:meta.view.license v:name="Public Domain"

property e:urps-v5ck t:meta.view.owner v:id=vxmx-2ngw v:profileImageUrlMedium=/api/users/vxmx-2ngw/profile_images/THUMB v:profileImageUrlLarge=/api/users/vxmx-2ngw/profile_images/LARGE v:screenName="DAS, State Accounting Enterprise" v:profileImageUrlSmall=/api/users/vxmx-2ngw/profile_images/TINY v:displayName="DAS, State Accounting Enterprise"

property e:urps-v5ck t:meta.view.tableauthor v:id=vxmx-2ngw v:profileImageUrlMedium=/api/users/vxmx-2ngw/profile_images/THUMB v:profileImageUrlLarge=/api/users/vxmx-2ngw/profile_images/LARGE v:screenName="DAS, State Accounting Enterprise" v:profileImageUrlSmall=/api/users/vxmx-2ngw/profile_images/TINY v:roleName=editor v:displayName="DAS, State Accounting Enterprise"
```

## Top Records

```ls
| :updated_at | budget_fy | fiscal_period | fiscal_period_name | function              | spec_dept                     | dept_1 | dept_2                    | fund | fund_name    | unit | unit_name          | appropriation | appropriation_name  | revenue_class | revenue_class_name    | amount     | 
| =========== | ========= | ============= | ================== | ===================== | ============================= | ====== | ========================= | ==== | ============ | ==== | ================== | ============= | =================== | ============= | ===================== | ========== | 
| 1415278880  | 2012      | 9             | March              | General Fund Use Only | General Fund Use              | 996    | Fees                      | 0001 | General Fund | 2175 | Real Estate        | 0000          | Blank Appropriation | 704           | Other                 | 9000       | 
| 1415278875  | 2012      | 7             | January            | Human Services        | Human Services, Department of | 407    | Human Services - Cherokee | 0001 | General Fund | 1227 | Laundry            | M30           | Cherokee MHI        | 704           | Other                 | 341.25     | 
| 1415278885  | 2012      | 11            | May                | Education             | Education, Department of      | 285    | Iowa Public Television    | 0085 | IPTV- Misc   | 2030 | Iptv Miscellaneous | 0000          | Blank Appropriation | 301           | Interest              | 19.54      | 
| 1415278887  | 2012      | 12            | June               | Human Services        | Iowa Veterans Home            | 671    | Iowa Veterans Home        | 0001 | General Fund | 5126 | Housekeeping       | V03           | Iowa Veterans Home  | 603           | Rents & Leases        | 2235.5     | 
| 1415278888  | 2012      | 13            | July (H/O)         | Judicial Branch       | Judicial Branch               | 444    | Judicial Branch           | 0001 | General Fund | 0110 | Family Drug Court  | B20           | Judicial Branch     | 201           | Federal Support       | 91618.37   | 
| 1415278890  | 2012      | 14            | August (H/O)       | General Fund Use Only | General Fund Use              | 990    | Special Taxes             | 0001 | General Fund | 2120 | Beer Tax           | 0000          | Blank Appropriation | 101           | Beer Tax              | 910607.61  | 
| 1415278865  | 2012      | 1             | July               | General Fund Use Only | General Fund Use              | 990    | Special Taxes             | 0001 | General Fund | 6250 | Revenue & Finance  | 0000          | Blank Appropriation | 102           | Cigarette Tax         | 34556.57   | 
| 1415278865  | 2012      | 1             | July               | General Fund Use Only | General Fund Use              | 990    | Special Taxes             | 0001 | General Fund | 6250 | Revenue & Finance  | 0000          | Blank Appropriation | 103           | Tobacco Products Tax  | 2472419.81 | 
| 1415278865  | 2012      | 1             | July               | General Fund Use Only | General Fund Use              | 990    | Special Taxes             | 0001 | General Fund | 6250 | Revenue & Finance  | 0000          | Blank Appropriation | 108           | Inheritance Tax       | 5093157.04 | 
| 1415278865  | 2012      | 1             | July               | General Fund Use Only | General Fund Use              | 990    | Special Taxes             | 0001 | General Fund | 6250 | Revenue & Finance  | 0000          | Blank Appropriation | 110           | Insurance Premium Tax | 1019616.36 | 
```