# Parolees Under Community Supervision: Beginning 2008

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/parolees-under-community-supervision-beginning-2008) |
| Metadata | [Link](https://data.ny.gov/api/views/pmxm-gftz) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/pmxm-gftz/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/pmxm-gftz/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | pmxm-gftz |
| Name | Parolees Under Community Supervision: Beginning 2008 |
| Attribution | NYS Department of Corrections and Community Supervision |
| Category | Public Safety |
| Tags | parolees, community supervision |
| Created | 2014-01-10T21:41:49Z |
| Publication Date | 2015-11-30T16:20:05Z |

## Description

Provides data about parolees under community supervision on March 31 of the snapshot year. Information includes region of supervision, county of residence, snapshot year, supervision level, gender, age as of the file date, and crime type for most serious instant offense.

## Columns

```ls
| Included | Schema Type    | Field Name        | Name                  | Data Type | Render Type |
| ======== | ============== | ================= | ===================== | ========= | =========== |
| Yes      | time           | snapshot_year     | Snapshot Year         | number    | number      |
| Yes      | series tag     | region            | Region of Supervision | text      | text        |
| Yes      | series tag     | county            | County of Residence   | text      | text        |
| Yes      | series tag     | supervision_level | Supervision Level     | text      | text        |
| Yes      | series tag     | gender            | Gender                | text      | text        |
| Yes      | numeric metric | age               | Age                   | number    | number      |
| Yes      | series tag     | crime             | Crime                 | text      | text        |
```

## Time Field

```ls
Value = snapshot_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:pmxm-gftz d:2008-01-01T00:00:00.000Z t:region=WILLARD t:county=SENECA t:crime="DRUG OFFENSES" t:gender=MALE m:age=29

series e:pmxm-gftz d:2008-01-01T00:00:00.000Z t:region=WILLARD t:county=SENECA t:crime="DRUG OFFENSES" t:gender=MALE m:age=24

series e:pmxm-gftz d:2008-01-01T00:00:00.000Z t:region=WILLARD t:county=SENECA t:crime="OTHER COERCIVE" t:gender=MALE m:age=51
```

## Meta Commands

```ls
metric m:age p:integer l:Age d:"Age of parolee at the time of the file/most recent snapshot year" t:dataTypeName=number

entity e:pmxm-gftz l:"Parolees Under Community Supervision: Beginning 2008" t:attribution="NYS Department of Corrections and Community Supervision" t:url=https://data.ny.gov/api/views/pmxm-gftz

property e:pmxm-gftz t:meta.view v:id=pmxm-gftz v:category="Public Safety" v:attributionLink=http://www.doccs.ny.gov/ v:averageRating=0 v:name="Parolees Under Community Supervision: Beginning 2008" v:attribution="NYS Department of Corrections and Community Supervision"

property e:pmxm-gftz t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:pmxm-gftz t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:pmxm-gftz t:meta.view.metadata.custom_fields.common_core v:Contact_Email=opendata@its.ny.gov v:Publisher="State of New York" v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| snapshot_year | region    | county       | supervision_level | gender | age | crime          | 
| ============= | ========= | ============ | ================= | ====== | === | ============== | 
| 2008          | WILLARD   | SENECA       |                   | MALE   | 29  | DRUG OFFENSES  | 
| 2008          | WILLARD   | SENECA       |                   | MALE   | 24  | DRUG OFFENSES  | 
| 2008          | WILLARD   | SENECA       |                   | MALE   | 51  | OTHER COERCIVE | 
| 2008          | WILLARD   | SENECA       |                   | MALE   | 39  | DRUG OFFENSES  | 
| 2008          | WILLARD   | SENECA       |                   | MALE   | 59  | DRUG OFFENSES  | 
| 2008          | WESTERN   | OUT OF STATE |                   | MALE   | 27  | DRUG OFFENSES  | 
| 2008          | WILLARD   | SENECA       |                   | FEMALE | 46  | MAJOR PROPERTY | 
| 2008          | WILLARD   | SENECA       |                   | FEMALE | 44  | OTHER FELONY   | 
| 2008          | MANHATTAN | NEW YORK     |                   | FEMALE | 37  | OTHER FELONY   | 
| 2008          | MANHATTAN | NEW YORK     |                   | FEMALE | 45  | MAJOR PROPERTY | 
```