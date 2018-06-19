# Missouri Keg Tag

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/missouri-keg-tag) |
| Metadata | [Link](https://data.mo.gov/api/views/7fmu-y7e8) |
| Data: JSON | [100 Rows](https://data.mo.gov/api/views/7fmu-y7e8/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.mo.gov/api/views/7fmu-y7e8/rows.csv?max_rows=100) |
| Host | data.mo.gov |
| Id | 7fmu-y7e8 |
| Name | Missouri Keg Tag |
| Category | Public Safety |
| Tags | alcohol, beer, liquor |
| Created | 2015-04-06T15:58:34Z |
| Publication Date | 2017-04-20T11:02:06Z |

## Description

List of keg tags assigned to distributors

## Columns

```ls
| Included | Schema Type | Field Name      | Name            | Data Type | Render Type |
| ======== | =========== | =============== | =============== | ========= | =========== |
| No       | time        | :updated_at     | updated_at      | meta_data | meta_data   |
| Yes      | series tag  | kegnum          | KegNum          | text      | text        |
| Yes      | series tag  | licensee_name   | Licensee Name   | text      | text        |
| Yes      | series tag  | dba_name        | DBA Name        | text      | text        |
| Yes      | series tag  | first_name      | First Name      | text      | text        |
| Yes      | series tag  | last_name       | Last Name       | text      | text        |
| Yes      | series tag  | phone           | Phone           | phone     | phone       |
| Yes      | series tag  | building_number | Building Number | text      | text        |
| Yes      | series tag  | street          | Street          | text      | text        |
| Yes      | series tag  | city            | City            | text      | text        |
| Yes      | series tag  | state           | State           | text      | text        |
| Yes      | series tag  | zipcode         | Zipcode         | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:7fmu-y7e8 d:2017-04-20T11:00:53.000Z t:first_name=DAN t:kegnum=41001 t:licensee_name="SONNY BOYS PACKAGE LIQUOR LLC" t:phone_number=5734684144 t:zipcode=63080 t:street="FISHER DRIVE" t:last_name=STEELE t:state=MO t:building_number=689 t:dba_name="SONNY BOYS PACKAGE LIQUOR" t:city=SULLIVAN m:row_number.7fmu-y7e8=1

series e:7fmu-y7e8 d:2017-04-20T11:00:53.000Z t:first_name=DAN t:kegnum=41002 t:licensee_name="SONNY BOYS PACKAGE LIQUOR LLC" t:phone_number=5734684144 t:zipcode=63080 t:street="FISHER DRIVE" t:last_name=STEELE t:state=MO t:building_number=689 t:dba_name="SONNY BOYS PACKAGE LIQUOR" t:city=SULLIVAN m:row_number.7fmu-y7e8=2

series e:7fmu-y7e8 d:2017-04-20T11:00:53.000Z t:first_name=DAN t:kegnum=41003 t:licensee_name="SONNY BOYS PACKAGE LIQUOR LLC" t:phone_number=5734684144 t:zipcode=63080 t:street="FISHER DRIVE" t:last_name=STEELE t:state=MO t:building_number=689 t:dba_name="SONNY BOYS PACKAGE LIQUOR" t:city=SULLIVAN m:row_number.7fmu-y7e8=3
```

## Meta Commands

```ls
metric m:row_number.7fmu-y7e8 p:long l:"Row Number"

entity e:7fmu-y7e8 l:"Missouri Keg Tag" t:url=https://data.mo.gov/api/views/7fmu-y7e8

property e:7fmu-y7e8 t:meta.view v:id=7fmu-y7e8 v:category="Public Safety" v:averageRating=0 v:name="Missouri Keg Tag"

property e:7fmu-y7e8 t:meta.view.owner v:id=gytm-8bsj v:screenName="Rob Gourley" v:displayName="Rob Gourley"

property e:7fmu-y7e8 t:meta.view.tableauthor v:id=gytm-8bsj v:screenName="Rob Gourley" v:roleName=editor v:displayName="Rob Gourley"
```

## Top Records

```ls
| :updated_at | kegnum | licensee_name                 | dba_name                  | first_name | last_name | phone              | building_number | street       | city     | state | zipcode | 
| =========== | ====== | ============================= | ========================= | ========== | ========= | ================== | =============== | ============ | ======== | ===== | ======= | 
| 1492686053  | 41001  | SONNY BOYS PACKAGE LIQUOR LLC | SONNY BOYS PACKAGE LIQUOR | DAN        | STEELE    | [5734684144, null] | 689             | FISHER DRIVE | SULLIVAN | MO    | 63080   | 
| 1492686053  | 41002  | SONNY BOYS PACKAGE LIQUOR LLC | SONNY BOYS PACKAGE LIQUOR | DAN        | STEELE    | [5734684144, null] | 689             | FISHER DRIVE | SULLIVAN | MO    | 63080   | 
| 1492686053  | 41003  | SONNY BOYS PACKAGE LIQUOR LLC | SONNY BOYS PACKAGE LIQUOR | DAN        | STEELE    | [5734684144, null] | 689             | FISHER DRIVE | SULLIVAN | MO    | 63080   | 
| 1492686053  | 41004  | SONNY BOYS PACKAGE LIQUOR LLC | SONNY BOYS PACKAGE LIQUOR | DAN        | STEELE    | [5734684144, null] | 689             | FISHER DRIVE | SULLIVAN | MO    | 63080   | 
| 1492686053  | 41005  | SONNY BOYS PACKAGE LIQUOR LLC | SONNY BOYS PACKAGE LIQUOR | DAN        | STEELE    | [5734684144, null] | 689             | FISHER DRIVE | SULLIVAN | MO    | 63080   | 
| 1492686053  | 41006  | SONNY BOYS PACKAGE LIQUOR LLC | SONNY BOYS PACKAGE LIQUOR | DAN        | STEELE    | [5734684144, null] | 689             | FISHER DRIVE | SULLIVAN | MO    | 63080   | 
| 1492686053  | 41007  | SONNY BOYS PACKAGE LIQUOR LLC | SONNY BOYS PACKAGE LIQUOR | DAN        | STEELE    | [5734684144, null] | 689             | FISHER DRIVE | SULLIVAN | MO    | 63080   | 
| 1492686053  | 41008  | SONNY BOYS PACKAGE LIQUOR LLC | SONNY BOYS PACKAGE LIQUOR | DAN        | STEELE    | [5734684144, null] | 689             | FISHER DRIVE | SULLIVAN | MO    | 63080   | 
| 1492686053  | 41009  | SONNY BOYS PACKAGE LIQUOR LLC | SONNY BOYS PACKAGE LIQUOR | DAN        | STEELE    | [5734684144, null] | 689             | FISHER DRIVE | SULLIVAN | MO    | 63080   | 
| 1492686053  | 41010  | SONNY BOYS PACKAGE LIQUOR LLC | SONNY BOYS PACKAGE LIQUOR | DAN        | STEELE    | [5734684144, null] | 689             | FISHER DRIVE | SULLIVAN | MO    | 63080   | 
```