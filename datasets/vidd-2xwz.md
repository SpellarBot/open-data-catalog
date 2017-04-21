# Audit Reports

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/audit-reports-1c05b) |
| Metadata | [Link](https://data.iowa.gov/api/views/vidd-2xwz) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/vidd-2xwz/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/vidd-2xwz/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | vidd-2xwz |
| Name | Audit Reports |
| Attribution | State of Iowa, Auditor of State |
| Category | Government |
| Tags | audit reports, cpa firms |
| Created | 2015-01-21T20:36:26Z |
| Publication Date | 2015-03-11T12:52:06Z |

## Description

This dataset contains a listing of audit reports issued by the Auditor of State (AOS) or received from CPA firms under the provisions of Chapter 11 of the Code of Iowa for the period ended June 30, 2004 and after.

## Columns

```ls
| Included | Schema Type | Field Name         | Name                 | Data Type     | Render Type   |
| ======== | =========== | ================== | ==================== | ============= | ============= |
| Yes      | series tag  | typeofentity       | Type of Entity       | text          | text          |
| Yes      | series tag  | auditcategory      | Type of Audit        | text          | text          |
| Yes      | series tag  | entity             | Entity Name          | text          | text          |
| Yes      | time        | reportperiodending | Report Period Ending | calendar_date | calendar_date |
| Yes      | series tag  | firm               | Firm                 | text          | text          |
| Yes      | series tag  | url                | Report URL           | url           | url           |
```

## Time Field

```ls
Value = reportperiodending
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:vidd-2xwz d:2011-06-30T00:00:00.000Z t:typeofentity="State Agency" t:firm="Office of Auditor of State" t:entity="Natural Resources, Department of" t:auditcategory=Performance/Extension t:url=http://www.auditor.iowa.gov/reports/0960-5420-B0P2.pdf m:row_number.vidd-2xwz=1

series e:vidd-2xwz d:2014-06-30T00:00:00.000Z t:typeofentity=City t:firm="Winther, Stave & Co." t:entity=Spencer t:auditcategory="Financial Statement" t:url=http://www.auditor.iowa.gov/reports/1420-0180-C00F.pdf m:row_number.vidd-2xwz=2

series e:vidd-2xwz d:2005-06-30T00:00:00.000Z t:typeofentity="28E Organizations" t:firm="Dietz, Donald & Co." t:entity="Mar Mac Unified Law Enforcement District" t:auditcategory="Financial Statement" t:url=http://www.auditor.iowa.gov/reports/0514-2154-C00F.pdf m:row_number.vidd-2xwz=3
```

## Meta Commands

```ls
metric m:row_number.vidd-2xwz p:long l:"Row Number"

entity e:vidd-2xwz l:"Audit Reports" t:attribution="State of Iowa, Auditor of State" t:url=https://data.iowa.gov/api/views/vidd-2xwz

property e:vidd-2xwz t:meta.view v:id=vidd-2xwz v:category=Government v:averageRating=0 v:name="Audit Reports" v:attribution="State of Iowa, Auditor of State"

property e:vidd-2xwz t:meta.view.license v:name="Public Domain"

property e:vidd-2xwz t:meta.view.owner v:id=v63m-mv9p v:profileImageUrlMedium=/api/users/v63m-mv9p/profile_images/THUMB v:profileImageUrlLarge=/api/users/v63m-mv9p/profile_images/LARGE v:screenName="Iowa Auditor of State" v:profileImageUrlSmall=/api/users/v63m-mv9p/profile_images/TINY v:displayName="Iowa Auditor of State"

property e:vidd-2xwz t:meta.view.tableauthor v:id=v63m-mv9p v:profileImageUrlMedium=/api/users/v63m-mv9p/profile_images/THUMB v:profileImageUrlLarge=/api/users/v63m-mv9p/profile_images/LARGE v:screenName="Iowa Auditor of State" v:profileImageUrlSmall=/api/users/v63m-mv9p/profile_images/TINY v:roleName=editor v:displayName="Iowa Auditor of State"
```

## Top Records

```ls
| typeofentity      | auditcategory             | entity                                   | reportperiodending  | firm                           | url                                                            | 
| ================= | ========================= | ======================================== | =================== | ============================== | ============================================================== | 
| State Agency      | Performance/Extension     | Natural Resources, Department of         | 2011-06-30T00:00:00 | Office of Auditor of State     | [http://www.auditor.iowa.gov/reports/0960-5420-B0P2.pdf, null] | 
| City              | Financial Statement       | Spencer                                  | 2014-06-30T00:00:00 | Winther, Stave & Co.           | [http://www.auditor.iowa.gov/reports/1420-0180-C00F.pdf, null] | 
| 28E Organizations | Financial Statement       | Mar Mac Unified Law Enforcement District | 2005-06-30T00:00:00 | Dietz, Donald & Co.            | [http://www.auditor.iowa.gov/reports/0514-2154-C00F.pdf, null] | 
| School            | Financial Statement       | Newton CSD                               | 2005-06-30T00:00:00 | Nolte, Cornman & Johnson, P.C. | [http://www.auditor.iowa.gov/reports/0530-4725-C00F.pdf, null] | 
| State Agency      | Report of Recommendations | Public Defense, Department of            | 2004-06-30T00:00:00 | Office of Auditor of State     | [http://www.auditor.iowa.gov/reports/0560-5820-0R00.pdf, null] | 
| County            | Financial Statement       | Hancock County                           | 2010-06-30T00:00:00 | Renner & Birchem P.C.          | [http://www.auditor.iowa.gov/reports/1010-0041-C00F.pdf, null] | 
| County            | Financial Statement       | Hardin County                            | 2005-06-30T00:00:00 | Bowman & Company, P.C.         | [http://www.auditor.iowa.gov/reports/0510-0042-C00F.pdf, null] | 
| School            | Financial Statement       | IKM-Manning CSD                          | 2011-06-30T00:00:00 | Burton E. Tracy & Co., P.C.    | [http://www.auditor.iowa.gov/reports/1130-3168-C00F.pdf, null] | 
| City              | Financial Statement       | Aurelia                                  | 2005-06-30T00:00:00 | Hunzelman, Putzier & Co.       | [http://www.auditor.iowa.gov/reports/0521-0153-C00F.pdf, null] | 
| 28E Organizations | Financial Statement       | Tama County Solid Waste Disposal         | 2011-06-30T00:00:00 | Bowman & Miller, P.C.          | [http://www.auditor.iowa.gov/reports/1114-2305-C00F.pdf, null] | 
```