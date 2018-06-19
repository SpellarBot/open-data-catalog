# State of Iowa Expenditures

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/state-of-iowa-expenditures) |
| Metadata | [Link](https://data.iowa.gov/api/views/mn9y-cwp6) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/mn9y-cwp6/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/mn9y-cwp6/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | mn9y-cwp6 |
| Name | State of Iowa Expenditures |
| Attribution | Iowa Department of Administrative Services, State Accounting Enterprise, I3 Data Warehouse |
| Category | Government |
| Tags | financial, expenditures, actuals |
| Created | 2014-11-06T17:22:01Z |
| Publication Date | 2014-12-01T20:26:11Z |

## Description

This dataset provides summarized data for all expenditures from July 2003 through the current fiscal year, year to date, from the State's central accounting system. The state fiscal year runs from July 1 to the following June 30 and is numbered for the calendar year in which it ends. The State of Iowa operates on a modified accrual basis which provides that encumbrances on June 30 must be paid within 60 days after year end. The expenditures are summarized by Fiscal Year, Month, Fund, Appropriation, Department, Unit, and Object Class.

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
| Yes      | series tag     | unit               | Unit               | text      | text        |
| Yes      | series tag     | unit_name          | Unit Name          | text      | text        |
| Yes      | series tag     | fund               | Fund               | text      | text        |
| Yes      | series tag     | fund_name          | Fund Name          | text      | text        |
| Yes      | series tag     | appropriation      | Appropriation      | text      | text        |
| Yes      | series tag     | appropriation_name | Appropriation Name | text      | text        |
| Yes      | numeric metric | object_class       | Object Class       | number    | text        |
| Yes      | series tag     | object_class_name  | Object Class Name  | text      | text        |
| Yes      | numeric metric | amount             | Amount             | money     | money       |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:mn9y-cwp6 d:2014-11-06T09:22:10.000Z t:fund_name="General Fund" t:spec_dept="Human Services, Department of" t:unit=1110 t:fiscal_period_name=July t:appropriation=M30 t:dept_2="Human Services - Cherokee" t:dept_1=407 t:appropriation_name="Cherokee Mhi" t:fund=0001 t:object_class_name="Office Supplies" t:unit_name=Registrar t:function="Human Services" m:amount=190 m:budget_fy=2004 m:fiscal_period=1 m:object_class=301

series e:mn9y-cwp6 d:2014-11-06T09:22:13.000Z t:fund_name="General Fund" t:spec_dept="Iowa Veterans Home" t:unit=5127 t:fiscal_period_name=July t:appropriation=V03 t:dept_2="Iowa Veterans Home" t:dept_1=671 t:appropriation_name="Iowa Veterans Home" t:fund=0001 t:object_class_name=Claims t:unit_name=Laundry t:function="Human Services" m:amount=8.99 m:budget_fy=2004 m:fiscal_period=1 m:object_class=601

series e:mn9y-cwp6 d:2014-11-06T09:22:13.000Z t:fund_name="CPB/CSG 91 93" t:spec_dept="Education, Department of" t:unit=2098 t:fiscal_period_name=July t:appropriation=0000 t:dept_2="Iowa Public Television" t:dept_1=285 t:appropriation_name="Blank Appropriation" t:fund=0033 t:object_class_name="Personal Services" t:unit_name="CSG Ffy97" t:function=Education m:amount=0 m:budget_fy=2004 m:fiscal_period=1 m:object_class=101
```

## Meta Commands

```ls
metric m:budget_fy p:integer l:"Budget FY" d:"Budget Fiscal Year (July 1 - June 30 + 60 days) expenditure was made" t:dataTypeName=number

metric m:fiscal_period p:integer l:"Fiscal Period" d:"Fiscal Period (1-15) the expenditure was made" t:dataTypeName=number

metric m:object_class p:integer l:"Object Class" d:"The code used to designate the type of expenditure" t:dataTypeName=number

metric m:amount p:double l:Amount d:"The total of all expenditures for the specified combination of Budget FY, Fund, Department, etc" t:dataTypeName=money

entity e:mn9y-cwp6 l:"State of Iowa Expenditures" t:attribution="Iowa Department of Administrative Services, State Accounting Enterprise, I3 Data Warehouse" t:url=https://data.iowa.gov/api/views/mn9y-cwp6

property e:mn9y-cwp6 t:meta.view v:id=mn9y-cwp6 v:category=Government v:averageRating=0 v:name="State of Iowa Expenditures" v:attribution="Iowa Department of Administrative Services, State Accounting Enterprise, I3 Data Warehouse"

property e:mn9y-cwp6 t:meta.view.license v:name="Public Domain"

property e:mn9y-cwp6 t:meta.view.owner v:id=vxmx-2ngw v:profileImageUrlMedium=/api/users/vxmx-2ngw/profile_images/THUMB v:profileImageUrlLarge=/api/users/vxmx-2ngw/profile_images/LARGE v:screenName="DAS, State Accounting Enterprise" v:profileImageUrlSmall=/api/users/vxmx-2ngw/profile_images/TINY v:displayName="DAS, State Accounting Enterprise"

property e:mn9y-cwp6 t:meta.view.tableauthor v:id=vxmx-2ngw v:profileImageUrlMedium=/api/users/vxmx-2ngw/profile_images/THUMB v:profileImageUrlLarge=/api/users/vxmx-2ngw/profile_images/LARGE v:screenName="DAS, State Accounting Enterprise" v:profileImageUrlSmall=/api/users/vxmx-2ngw/profile_images/TINY v:roleName=editor v:displayName="DAS, State Accounting Enterprise"
```

## Top Records

```ls
| :updated_at | budget_fy | fiscal_period | fiscal_period_name | function           | spec_dept                     | dept_1 | dept_2                    | unit | unit_name         | fund | fund_name     | appropriation | appropriation_name     | object_class | object_class_name | amount  | 
| =========== | ========= | ============= | ================== | ================== | ============================= | ====== | ========================= | ==== | ================= | ==== | ============= | ============= | ====================== | ============ | ================= | ======= | 
| 1415265730  | 2004      | 1             | July               | Human Services     | Human Services, Department of | 407    | Human Services - Cherokee | 1110 | Registrar         | 0001 | General Fund  | M30           | Cherokee Mhi           | 301          | Office Supplies   | 190     | 
| 1415265733  | 2004      | 1             | July               | Human Services     | Iowa Veterans Home            | 671    | Iowa Veterans Home        | 5127 | Laundry           | 0001 | General Fund  | V03           | Iowa Veterans Home     | 601          | Claims            | 8.99    | 
| 1415265733  | 2004      | 1             | July               | Education          | Education, Department of      | 285    | Iowa Public Television    | 2098 | CSG Ffy97         | 0033 | CPB/CSG 91 93 | 0000          | Blank Appropriation    | 101          | Personal Services | 0       | 
| 1415265737  | 2004      | 2             | August             | Justice System     | Attorney General              | 112    | Justice, Department of    | 1000 | Administration    | 0001 | General Fund  | B01           | General Office A.G.    | 402          | Rentals           | 77.05   | 
| 1415265748  | 2004      | 3             | September          | Education          | Education, Department of      | 282    | Education, Department of  | 3313 | CDCC              | 0001 | General Fund  | 811           | Child Development      | 801          | State Aid         | 1943047 | 
| 1415265749  | 2004      | 3             | September          | Justice System     | Corrections, Department of    | 243    | Corrections - Anamosa     | 1207 | Communication     | 0001 | General Fund  | A45           | Anamosa Inst.          | 301          | Office Supplies   | 99      | 
| 1415265749  | 2004      | 3             | September          | Justice System     | Attorney General              | 114    | Consumer Advocate         | 5000 | Consumer Advocate | 0001 | General Fund  | B06           | Consumer Advocate      | 401          | Communications    | 1577.81 | 
| 1415265760  | 2004      | 4             | October            | Legislative Branch | Legislative Branch            | 500    | House of Representatives  | 1303 | ORG Code 1303     | 0001 | General Fund  | 884           | House                  | 401          | Communications    | 6853.1  | 
| 1415265765  | 2004      | 4             | October            | Education          | Education, Department of      | 285    | Iowa Public Television    | 1000 | Engineering       | 0001 | General Fund  | I78           | Iowa Public Television | 402          | Rentals           | 8239.9  | 
| 1415265765  | 2004      | 4             | October            | Human Services     | Aging, Iowa Department of     | 297    | Iowa Department on Aging  | 5195 | Anti-Fraud Ort    | 0001 | General Fund  | J42           | Aging Programs         | 313          | Postage           | 14.19   | 
```