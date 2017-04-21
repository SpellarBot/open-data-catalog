# Security Level and Facility by Crime Group, Under Custody

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/security-level-and-facility-by-crime-group-under-custody) |
| Metadata | [Link](https://data.ny.gov/api/views/7whc-b5e4) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/7whc-b5e4/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/7whc-b5e4/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | 7whc-b5e4 |
| Name | Security Level and Facility by Crime Group, Under Custody |
| Attribution | DOCCS Program Planning Research and Evaluation |
| Category | Public Safety |
| Tags | facility, crime, under-custody |
| Created | 2013-03-01T22:13:54Z |
| Publication Date | 2016-10-26T16:54:45Z |

## Description

Number of under-custody offenders by facility by crime grouping

## Columns

```ls
| Included | Schema Type    | Field Name         | Name               | Data Type     | Render Type   |
| ======== | ============== | ================== | ================== | ============= | ============= |
| Yes      | series tag     | security_level     | Security Level     | text          | text          |
| Yes      | series tag     | facility           | Facility           | text          | text          |
| Yes      | numeric metric | violentfelony      | Violent Felony     | number        | number        |
| Yes      | numeric metric | other_coercive     | Other Coercive     | number        | number        |
| Yes      | numeric metric | drug_felony        | Drug Felony        | number        | number        |
| Yes      | numeric metric | property_other     | Property/Other     | number        | number        |
| Yes      | numeric metric | youth_juv_offender | Youth/Juv Offender | number        | number        |
| Yes      | numeric metric | not_coded          | Not Coded          | number        | number        |
| Yes      | numeric metric | total              | Total              | number        | number        |
| Yes      | time           | snapshot_date      | Snapshot Date      | calendar_date | calendar_date |
```

## Time Field

```ls
Value = snapshot_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:7whc-b5e4 d:2016-07-01T00:00:00.000Z t:facility=ATTICA t:security_level="MAXIMUM SECURITY" m:total=1998 m:other_coercive=81 m:drug_felony=96 m:violentfelony=1725 m:not_coded=0 m:youth_juv_offender=3 m:property_other=93

series e:7whc-b5e4 d:2016-07-01T00:00:00.000Z t:facility="ATTICA RMHU" t:security_level="MAXIMUM SECURITY" m:total=5 m:other_coercive=1 m:drug_felony=0 m:violentfelony=3 m:not_coded=0 m:youth_juv_offender=0 m:property_other=1

series e:7whc-b5e4 d:2016-07-01T00:00:00.000Z t:facility=AUBURN t:security_level="MAXIMUM SECURITY" m:total=1548 m:other_coercive=56 m:drug_felony=82 m:violentfelony=1288 m:not_coded=0 m:youth_juv_offender=10 m:property_other=112
```

## Meta Commands

```ls
metric m:violentfelony p:integer l:"Violent Felony" t:dataTypeName=number

metric m:other_coercive p:integer l:"Other Coercive" t:dataTypeName=number

metric m:drug_felony p:integer l:"Drug Felony" t:dataTypeName=number

metric m:property_other p:integer l:Property/Other t:dataTypeName=number

metric m:youth_juv_offender p:integer l:"Youth/Juv Offender" t:dataTypeName=number

metric m:not_coded p:integer l:"Not Coded" t:dataTypeName=number

metric m:total p:integer l:Total t:dataTypeName=number

entity e:7whc-b5e4 l:"Security Level and Facility by Crime Group, Under Custody" t:attribution="DOCCS Program Planning Research and Evaluation" t:url=https://data.ny.gov/api/views/7whc-b5e4

property e:7whc-b5e4 t:meta.view v:id=7whc-b5e4 v:category="Public Safety" v:attributionLink=http://www.doccs.ny.gov v:averageRating=0 v:name="Security Level and Facility by Crime Group, Under Custody" v:attribution="DOCCS Program Planning Research and Evaluation"

property e:7whc-b5e4 t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:7whc-b5e4 t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:7whc-b5e4 t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| security_level   | facility           | violentfelony | other_coercive | drug_felony | property_other | youth_juv_offender | not_coded | total | snapshot_date       | 
| ================ | ================== | ============= | ============== | =========== | ============== | ================== | ========= | ===== | =================== | 
| MAXIMUM SECURITY | ATTICA             | 1725          | 81             | 96          | 93             | 3                  | 0         | 1998  | 2016-07-01T00:00:00 | 
| MAXIMUM SECURITY | ATTICA RMHU        | 3             | 1              | 0           | 1              | 0                  | 0         | 5     | 2016-07-01T00:00:00 | 
| MAXIMUM SECURITY | AUBURN             | 1288          | 56             | 82          | 112            | 10                 | 0         | 1548  | 2016-07-01T00:00:00 | 
| MAXIMUM SECURITY | CLINTON            | 2145          | 127            | 199         | 137            | 13                 | 1         | 2622  | 2016-07-01T00:00:00 | 
| MAXIMUM SECURITY | COXSACKIE          | 730           | 38             | 83          | 45             | 17                 | 0         | 913   | 2016-07-01T00:00:00 | 
| MAXIMUM SECURITY | COXSACKIE JUVENILE | 12            | 2              | 0           | 1              | 11                 | 0         | 26    | 2016-07-01T00:00:00 | 
| MAXIMUM SECURITY | DOWNSTATE          | 630           | 118            | 179         | 196            | 33                 | 4         | 1160  | 2016-07-01T00:00:00 | 
| MAXIMUM SECURITY | EASTERN            | 855           | 15             | 28          | 10             | 1                  | 0         | 909   | 2016-07-01T00:00:00 | 
| MAXIMUM SECURITY | ELMIRA             | 1203          | 74             | 96          | 174            | 16                 | 13        | 1576  | 2016-07-01T00:00:00 | 
| MAXIMUM SECURITY | FIVE POINTS        | 1032          | 63             | 101         | 75             | 19                 | 0         | 1290  | 2016-07-01T00:00:00 | 
```