# IDOL Licensed Nurse Agencies

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/idol-licensed-nurse-agencies-e3fee) |
| Metadata | [Link](https://data.illinois.gov/api/views/5mzi-s8qv) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/5mzi-s8qv/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/5mzi-s8qv/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | 5mzi-s8qv |
| Name | IDOL Licensed Nurse Agencies |
| Attribution | Illinois Department of Labor |
| Category | Labor |
| Tags | labor, nurse, 225 ilcs 510, health |
| Created | 2014-02-10T21:51:25Z |
| Publication Date | 2015-11-30T16:07:53Z |

## Description

Protects the public's right to high quality health care by licensing and mandating standards of operation for nurse agencies which refer, employ, or assign registered nurses, licensed practical nurses or certified nurse aides to Illinois health care facilities.

## Columns

```ls
| Included | Schema Type | Field Name  | Name       | Data Type | Render Type |
| ======== | =========== | =========== | ========== | ========= | =========== |
| No       | time        | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag  | agency      | Agency     | text      | text        |
| No       |             | address_1   | Address 1  | text      | text        |
| No       |             | address_2   | Address 2  | text      | text        |
| Yes      | series tag  | city        | City       | text      | text        |
| Yes      | series tag  | state       | State      | text      | text        |
| Yes      | series tag  | zip_code    | ZIP Code   | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = address_1,address_2
```

## Data Commands

```ls
series e:5mzi-s8qv d:2015-11-30T08:04:50.000Z t:zip_code=60563- t:state=IL t:agency="HEALTH AT HOME" t:city=NAPERVILLE m:row_number.5mzi-s8qv=1

series e:5mzi-s8qv d:2015-11-30T08:04:50.000Z t:zip_code=60187- t:state=IL t:agency="HEALTH AT HOME" t:city=WHEATON m:row_number.5mzi-s8qv=2

series e:5mzi-s8qv d:2015-11-30T08:04:50.000Z t:zip_code=60035- t:state=IL t:agency="3 CROSS HOME CARE CORP." t:city=CHICAGO m:row_number.5mzi-s8qv=3
```

## Meta Commands

```ls
metric m:row_number.5mzi-s8qv p:long l:"Row Number"

entity e:5mzi-s8qv l:"IDOL Licensed Nurse Agencies" t:attribution="Illinois Department of Labor" t:url=https://data.illinois.gov/api/views/5mzi-s8qv

property e:5mzi-s8qv t:meta.view v:id=5mzi-s8qv v:category=Labor v:attributionLink=http://labor.illinois.gov/ v:averageRating=0 v:name="IDOL Licensed Nurse Agencies" v:attribution="Illinois Department of Labor"

property e:5mzi-s8qv t:meta.view.license v:name="Public Domain"

property e:5mzi-s8qv t:meta.view.owner v:id=qz2n-kjc9 v:screenName="IL Department of Labor" v:displayName="IL Department of Labor"

property e:5mzi-s8qv t:meta.view.tableauthor v:id=qz2n-kjc9 v:screenName="IL Department of Labor" v:roleName=publisher v:displayName="IL Department of Labor"
```

## Top Records

```ls
| :updated_at | agency                                        | address_1                            | address_2             | city        | state | zip_code | 
| =========== | ============================================= | ==================================== | ===================== | =========== | ===== | ======== | 
| 1448870690  | HEALTH AT HOME                                | 2255 ERICKSON DRIVE                  |                       | NAPERVILLE  | IL    | 60563-   | 
| 1448870690  | HEALTH AT HOME                                | 500 WYNDEMERE CIRCLE, GARDEN LEVEL   |                       | WHEATON     | IL    | 60187-   | 
| 1448870690  | 3 CROSS HOME CARE CORP.                       | 3 CROSS HOME CARE CORP.              |                       | CHICAGO     | IL    | 60035-   | 
| 1448870690  | BETTER DAY'S NURSING AGENCY, LLC              | 1935 ALSCHULER DRIVER                |                       | AURORA      | IL    | 60506-   | 
| 1448870690  | SPECIAL NEEDS SPECIALISTS, INC.               | 1250 N. CONVENT, SUITE B             |                       | BOURBONNAIS | IL    | 60914-   | 
| 1448870690  | THE A TEAM STAFF, LLC                         | 2S.951 RED OAK DRIVE                 |                       | ELBURN      | IL    | 60119-   | 
| 1448870690  | HEALTHSOURCE GLOBAL STAFFING, INC.            | 39270 PASEO PADRE PKWAY., #138       |                       | FREMONT     | CA    | 94538-   | 
| 1448870690  | AMERICARE STAFFING SERVICES OF ILLINOIS, INC. | 14551//2 W. DEVON AVENUE             |                       | CHICAGO     | IL    | 60660-   | 
| 1448870690  | AMN ALLIED SERVICES, LLC                      | 8840 CYPRESS WATERS BLVD., SUITE 300 |                       | DALLAS      | TX    | 75063-   | 
| 1448870690  | INGALLS PRIVATE DUTY                          | ONE INGALLS DRIVE                    | WYMAN-GORDON PAVILION | HARVEY      | IL    | 60426-   | 
```