# IDPH Illinois STD Clinics

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/idph-illinois-std-clinics) |
| Metadata | [Link](https://data.illinois.gov/api/views/baev-3ncn) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/baev-3ncn/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/baev-3ncn/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | baev-3ncn |
| Name | IDPH Illinois STD Clinics |
| Attribution | Illinois Department of Public Health STD Program |
| Tags | std, std clinic, clinic |
| Created | 2013-11-05T17:03:36Z |
| Publication Date | 2016-05-10T14:17:53Z |

## Description

STD (sexually transmitted disease) clinics in Illinois that utilize the Illinois Department of Public Health (IDPH) laboratories for testing.

## Columns

```ls
| Included | Schema Type | Field Name  | Name                  | Data Type | Render Type |
| ======== | =========== | =========== | ===================== | ========= | =========== |
| No       | time        | :updated_at | updated_at            | meta_data | meta_data   |
| Yes      | series tag  | county      | County                | text      | text        |
| Yes      | series tag  | clinicname  | ClinicName & Location | text      | text        |
| Yes      | series tag  | phone       | City                  | text      | text        |
| Yes      | series tag  | hours       | Days/Hours            | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:baev-3ncn d:2016-05-10T07:10:45.000Z t:clinicname="636 Hampshire St., Suite 201" m:row_number.baev-3ncn=1

series e:baev-3ncn d:2016-05-10T07:10:45.000Z t:clinicname="QUINCY 62301" m:row_number.baev-3ncn=2

series e:baev-3ncn d:2016-05-10T07:10:45.000Z t:clinicname=217-224-6877 m:row_number.baev-3ncn=3
```

## Meta Commands

```ls
metric m:row_number.baev-3ncn p:long l:"Row Number"

entity e:baev-3ncn l:"IDPH Illinois STD Clinics" t:attribution="Illinois Department of Public Health STD Program" t:url=https://data.illinois.gov/api/views/baev-3ncn

property e:baev-3ncn t:meta.view v:id=baev-3ncn v:averageRating=0 v:name="IDPH Illinois STD Clinics" v:attribution="Illinois Department of Public Health STD Program"

property e:baev-3ncn t:meta.view.owner v:id=rth8-ngz8 v:screenName="Danny Brikshavana" v:displayName="Danny Brikshavana"

property e:baev-3ncn t:meta.view.tableauthor v:id=rth8-ngz8 v:screenName="Danny Brikshavana" v:displayName="Danny Brikshavana"
```

## Top Records

```ls
| :updated_at | county | clinicname                   | phone | hours | 
| =========== | ====== | ============================ | ===== | ===== | 
| 1462864245  |        | 636 Hampshire St., Suite 201 |       |       | 
| 1462864245  |        | QUINCY 62301                 |       |       | 
| 1462864245  |        | 217-224-6877                 |       |       | 
| 1462864245  |        | 3014 Elm St.                 |       |       | 
| 1462864245  |        | CAIRO 62914                  |       |       | 
| 1462864245  |        | 618-734-4167                 |       |       | 
| 1462864245  |        | 1204 Logan Ave               |       |       | 
| 1462864245  |        | BELVIDERE 61008              |       |       | 
| 1462864245  |        | 815-544-9730                 |       |       | 
| 1462864245  |        | 201 W. Kenyon St.            |       |       | 
```