# Aggregate Employee Statistics

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/aggregate-employee-statistics-81c07) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/eddp-3v5g) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/eddp-3v5g/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/eddp-3v5g/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | eddp-3v5g |
| Name | Aggregate Employee Statistics |
| Attribution | Department of Correction (DOC) |
| Category | Public Safety |
| Created | 2016-03-23T18:29:36Z |
| Publication Date | 2016-03-23T18:44:04Z |

## Description

Staff records with attributes (status, rank/title, gender).

## Columns

```ls
| Included | Schema Type | Field Name        | Name              | Data Type | Render Type |
| ======== | =========== | ================= | ================= | ========= | =========== |
| No       | time        | :updated_at       | updated_at        | meta_data | meta_data   |
| Yes      | series tag  | doc_employee_id   | DOC_EMPLOYEE_ID   | text      | text        |
| Yes      | series tag  | leave_status_desc | LEAVE_STATUS_DESC | text      | text        |
| Yes      | series tag  | rank_title        | RANK_TITLE        | text      | text        |
| Yes      | series tag  | gender            | GENDER            | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:eddp-3v5g d:2016-03-23T11:29:40.000Z t:gender=FEMALE t:rank_title="ASSISTANT COMMISSIONER (COMM. SVCES)" t:doc_employee_id=22375 t:leave_status_desc=CEASED m:row_number.eddp-3v5g=1

series e:eddp-3v5g d:2016-03-23T11:29:40.000Z t:gender=MALE t:rank_title="LEGAL COORDINATOR" t:doc_employee_id=22377 t:leave_status_desc=CEASED m:row_number.eddp-3v5g=2

series e:eddp-3v5g d:2016-03-23T11:29:40.000Z t:gender=MALE t:rank_title="CORRECTION OFFICER" t:doc_employee_id=22378 t:leave_status_desc=CEASED m:row_number.eddp-3v5g=3
```

## Meta Commands

```ls
metric m:row_number.eddp-3v5g p:long l:"Row Number"

entity e:eddp-3v5g l:"Aggregate Employee Statistics" t:attribution="Department of Correction (DOC)" t:url=https://data.cityofnewyork.us/api/views/eddp-3v5g

property e:eddp-3v5g t:meta.view v:id=eddp-3v5g v:category="Public Safety" v:averageRating=0 v:name="Aggregate Employee Statistics" v:attribution="Department of Correction (DOC)"

property e:eddp-3v5g t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:eddp-3v5g t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | doc_employee_id | leave_status_desc | rank_title                           | gender | 
| =========== | =============== | ================= | ==================================== | ====== | 
| 1458732580  | 22375           | CEASED            | ASSISTANT COMMISSIONER (COMM. SVCES) | FEMALE | 
| 1458732580  | 22377           | CEASED            | LEGAL COORDINATOR                    | MALE   | 
| 1458732580  | 22378           | CEASED            | CORRECTION OFFICER                   | MALE   | 
| 1458732580  | 22379           | CEASED            | WARDEN                               | MALE   | 
| 1458732580  | 22380           | CEASED            | CAPTAIN                              | MALE   | 
| 1458732580  | 22381           | CEASED            | DEPUTY WARDEN                        | MALE   | 
| 1458732580  | 22382           | CEASED            | CAPTAIN                              | MALE   | 
| 1458732580  | 22383           | CEASED            | CAPTAIN                              | MALE   | 
| 1458732580  | 22384           | CEASED            | CORRECTION OFFICER                   | MALE   | 
| 1458732580  | 22385           | CEASED            | CAPTAIN                              | MALE   | 
```