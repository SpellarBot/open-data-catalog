# ACRIS - UCC Collateral Codes

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/acris-ucc-collateral-codes-ee59f) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/q9kp-jvxv) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/q9kp-jvxv/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/q9kp-jvxv/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | q9kp-jvxv |
| Name | ACRIS - UCC Collateral Codes |
| Attribution | Department of Finance (DOF) |
| Category | City Government |
| Tags | dof, acris land records |
| Created | 2013-09-16T18:24:03Z |
| Publication Date | 2017-04-08T20:02:47Z |

## Description

ACRIS Collateral Type mapping for Codes in the ACRIS Personal Property Master Dataset

## Columns

```ls
| Included | Schema Type | Field Name          | Name                | Data Type | Render Type |
| ======== | =========== | =================== | =================== | ========= | =========== |
| No       | time        | :updated_at         | updated_at          | meta_data | meta_data   |
| Yes      | series tag  | record_type         | RECORD TYPE         | text      | text        |
| Yes      | series tag  | ucc_collateral_code | UCC COLLATERAL CODE | text      | text        |
| Yes      | series tag  | description         | DESCRIPTION         | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:q9kp-jvxv d:2017-04-08T20:02:42.000Z t:record_type=U t:description="TRANSMITTING UTILITIES DBTR" t:ucc_collateral_code=D m:row_number.q9kp-jvxv=1

series e:q9kp-jvxv d:2017-04-08T20:02:42.000Z t:record_type=U t:description="CROPS/EXTRACTED/COLLATERAL/TIMBER TO BE CUT" t:ucc_collateral_code=R m:row_number.q9kp-jvxv=2

series e:q9kp-jvxv d:2017-04-08T20:02:42.000Z t:record_type=U t:description=COOPERATIVE t:ucc_collateral_code=C m:row_number.q9kp-jvxv=3
```

## Meta Commands

```ls
metric m:row_number.q9kp-jvxv p:long l:"Row Number"

entity e:q9kp-jvxv l:"ACRIS - UCC Collateral Codes" t:attribution="Department of Finance (DOF)" t:url=https://data.cityofnewyork.us/api/views/q9kp-jvxv

property e:q9kp-jvxv t:meta.view v:id=q9kp-jvxv v:category="City Government" v:averageRating=0 v:name="ACRIS - UCC Collateral Codes" v:attribution="Department of Finance (DOF)"

property e:q9kp-jvxv t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:q9kp-jvxv t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | record_type | ucc_collateral_code | description                                 | 
| =========== | =========== | =================== | =========================================== | 
| 1491681762  | U           | D                   | TRANSMITTING UTILITIES DBTR                 | 
| 1491681762  | U           | R                   | CROPS/EXTRACTED/COLLATERAL/TIMBER TO BE CUT | 
| 1491681762  | U           | C                   | COOPERATIVE                                 | 
| 1491681762  | U           | F                   | FIXTURE FILING                              | 
| 1491681762  | U           | M                   | MANUFACTURED HOUSING                        | 
| 1491681762  | U           | O                   | OTHER                                       | 
| 1491681762  | U           | A                   | COOPERATIVE WITH ADDENDUM                   | 
| 1491681762  | U           | P                   | PUBLIC FINANCE                              | 
```