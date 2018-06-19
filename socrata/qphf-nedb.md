# IDPH Ambulatory Surgical Treatment Center Directory

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/idph-ambulatory-surgical-treatment-center-directory-88095) |
| Metadata | [Link](https://data.illinois.gov/api/views/qphf-nedb) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/qphf-nedb/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/qphf-nedb/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | qphf-nedb |
| Name | IDPH Ambulatory Surgical Treatment Center Directory |
| Attribution | Division of Health Care Facilities and Programs |
| Category | Public Health |
| Tags | ambulatory, surgical, treatment, center |
| Created | 2012-01-27T21:18:08Z |
| Publication Date | 2017-04-05T16:14:06Z |

## Description

Current as of April 2017

## Columns

```ls
| Included | Schema Type    | Field Name                           | Name                                 | Data Type | Render Type |
| ======== | ============== | ==================================== | ==================================== | ========= | =========== |
| No       | time           | :updated_at                          | updated_at                           | meta_data | meta_data   |
| Yes      | series tag     | ambulatory_surgical_treatment_center | Ambulatory Surgical Treatment Center | text      | text        |
| No       |                | address                              | Address                              | text      | text        |
| Yes      | series tag     | city                                 | City                                 | text      | text        |
| Yes      | series tag     | zip                                  | Zip                                  | text      | number      |
| Yes      | series tag     | county                               | County                               | text      | text        |
| Yes      | series tag     | phone                                | Phone                                | text      | text        |
| Yes      | numeric metric | license_                             | License #                            | number    | number      |
| Yes      | series tag     | license_expiration_date              | License Expiration Date              | html      | html        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = address
```

## Data Commands

```ls
series e:qphf-nedb d:2017-04-05T16:13:46.000Z t:zip=60192 t:license_expiration_date=09/29/16 t:phone="(847) 742-7272" t:ambulatory_surgical_treatment_center="1800 McDonough Road Surgery Center, LLC - DBA Ashton Center for Day Surgery" t:county=Cook t:city="Hoffman Estates" m:license_=7003138

series e:qphf-nedb d:2017-04-05T16:13:46.000Z t:zip=60602 t:license_expiration_date=01/18/18 t:phone="(312) 726-3329" t:ambulatory_surgical_treatment_center="25 East Same Day Surgery" t:county=Cook t:city=Chicago m:license_=7001969

series e:qphf-nedb d:2017-04-05T16:13:46.000Z t:zip=60707 t:license_expiration_date=05/03/17 t:phone="(773) 637-1700" t:ambulatory_surgical_treatment_center="Advanced Ambulatory Surgical Center" t:county=Cook t:city=Chicago m:license_=7002256
```

## Meta Commands

```ls
metric m:license_ p:integer l:"License #" t:dataTypeName=number

entity e:qphf-nedb l:"IDPH Ambulatory Surgical Treatment Center Directory" t:attribution="Division of Health Care Facilities and Programs" t:url=https://data.illinois.gov/api/views/qphf-nedb

property e:qphf-nedb t:meta.view v:id=qphf-nedb v:category="Public Health" v:attributionLink=http://www.idph.state.il.us/about/ohcr.htm v:averageRating=0 v:name="IDPH Ambulatory Surgical Treatment Center Directory" v:attribution="Division of Health Care Facilities and Programs"

property e:qphf-nedb t:meta.view.owner v:id=e75b-y6hv v:screenName=Jenny v:displayName=Jenny

property e:qphf-nedb t:meta.view.tableauthor v:id=e75b-y6hv v:screenName=Jenny v:roleName=publisher v:displayName=Jenny
```

## Top Records

```ls
| :updated_at | ambulatory_surgical_treatment_center                                          | address                       | city              | zip   | county   | phone          | license_ | license_expiration_date | 
| =========== | ============================================================================= | ============================= | ================= | ===== | ======== | ============== | ======== | ======================= | 
| 1491408826  | 1800 McDonough Road Surgery Center, LLC - DBA Ashton Center for Day Surgery   | 1800 McDonough Road Suite 100 | Hoffman Estates   | 60192 | Cook     | (847) 742-7272 | 7003138  | 09/29/16                | 
| 1491408826  | 25 East Same Day Surgery                                                      | 25 East Washington            | Chicago           | 60602 | Cook     | (312) 726-3329 | 7001969  | 01/18/18                | 
| 1491408826  | Advanced Ambulatory Surgical Center                                           | 2333 North Harlem Avenue      | Chicago           | 60707 | Cook     | (773) 637-1700 | 7002256  | 05/03/17                | 
| 1491408826  | Advantage Health Care, Ltd.                                                   | 203 E. Irving Park Road       | Wood Dale         | 60191 | Du Page  | (630) 595-1515 | 7002140  | 08/20/17                | 
| 1491408826  | Aiden Center for Day Surgery, LLC                                             | 1580 W. Lake Street           | Addison           | 60101 | Du Page  | (630) 285-7000 | 7003140  | 02/28/18                | 
| 1491408826  | Algonquin Road Surgery Center, LLC                                            | 2550 Algonquin Road           | Lake in the Hills | 60516 | Mc Henry | (847) 458-1246 | 7002579  | 12/13/17                | 
| 1491408826  | Ambulatory Surgery Center of Centralia, LLC - DBA Surgery Center of Centralia | 1045 Martin Luther King Drive | Centralia         | 62801 | Marion   | (618) 532-3110 | 7002298  | 01/31/18                | 
| 1491408826  | Ambulatory Surgicenter of Downers Grove, Ltd.                                 | 4333 Main Street              | Downers Grove     | 60515 | Cook     | (630) 322-9451 | 7002082  | 10/08/17                | 
| 1491408826  | AmSurg Surgery Center                                                         | 998 129th Infantry Drive      | Joliet            | 60435 | Will     | (815) 744-3000 | 7003160  | 05/03/17                | 
| 1491408826  | Associated Surgical Center, LLC                                               | 129 W. Rand Road              | Arlington Heights | 60004 | Cook     | (847) 215-0530 | 7003214  | 06/02/17                | 
```