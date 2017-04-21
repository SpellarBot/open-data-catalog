# DCAS Managed Public Buildings

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dcas-managed-public-buildings-fd000) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/xx2p-4jnq) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/xx2p-4jnq/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/xx2p-4jnq/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | xx2p-4jnq |
| Name | DCAS Managed Public Buildings |
| Attribution | Department of Citywide Administrative Services (DCAS) |
| Category | City Government |
| Tags | building, buildings, permit, permits, building permits, department of citywide administrative services (dcas) |
| Created | 2013-03-06T17:43:44Z |
| Publication Date | 2013-06-21T20:03:33Z |

## Description

This is the list (directory) of Department of Citywide Administrative Services (DCAS) managed public buildings along with the information that the building is DCAS secured or not.

## Columns

```ls
| Included | Schema Type | Field Name                         | Name                               | Data Type | Render Type |
| ======== | =========== | ================================== | ================================== | ========= | =========== |
| No       | time        | :updated_at                        | updated_at                         | meta_data | meta_data   |
| Yes      | series tag  | borough                            | Borough                            | text      | text        |
| Yes      | series tag  | building                           | Building                           | text      | text        |
| Yes      | series tag  | custodial_borough_supervisor_name  | Custodial Borough Supervisor Name  | text      | text        |
| Yes      | series tag  | custodial_borough_supervisor_phone | Custodial Borough Supervisor Phone | text      | text        |
| Yes      | series tag  | custodial                          | Custodial                          | text      | text        |
| Yes      | series tag  | engineering                        | Engineering                        | text      | text        |
| Yes      | series tag  | dcas_security                      | DCAS Security ?                    | text      | text        |
| Yes      | series tag  | security                           | Security                           | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:xx2p-4jnq d:2013-03-06T09:43:46.000Z t:dcas_security=N t:custodial=718-590-7466 t:custodial_borough_supervisor_phone=347-386-2979 t:building="Bronx Housing Court" t:custodial_borough_supervisor_name="Ann Wilson" t:borough=Bronx t:security=718-466-3102 t:engineering=718-590-1061 m:row_number.xx2p-4jnq=1

series e:xx2p-4jnq d:2013-03-06T09:43:46.000Z t:dcas_security=Y t:custodial=718-579-6730 t:custodial_borough_supervisor_phone=347-386-2980 t:building="Bergen Building" t:custodial_borough_supervisor_name="Ann Wilson" t:borough=Bronx t:security=718-579-6733 t:engineering=718-590-3234 m:row_number.xx2p-4jnq=2

series e:xx2p-4jnq d:2013-03-06T09:43:46.000Z t:dcas_security=N t:custodial=718-590-7232 t:custodial_borough_supervisor_phone=347-386-2981 t:building="Concourse Plaza" t:custodial_borough_supervisor_name="Ann Wilson" t:borough=Bronx t:security=718-590-2030 t:engineering=718-590-1814 m:row_number.xx2p-4jnq=3
```

## Meta Commands

```ls
metric m:row_number.xx2p-4jnq p:long l:"Row Number"

entity e:xx2p-4jnq l:"DCAS Managed Public Buildings" t:attribution="Department of Citywide Administrative Services (DCAS)" t:url=https://data.cityofnewyork.us/api/views/xx2p-4jnq

property e:xx2p-4jnq t:meta.view v:id=xx2p-4jnq v:category="City Government" v:attributionLink=http://www.nyc.gov/html/dcas/downloads/pdf/misc/building_contact_list.pdf v:averageRating=0 v:name="DCAS Managed Public Buildings" v:attribution="Department of Citywide Administrative Services (DCAS)"

property e:xx2p-4jnq t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:xx2p-4jnq t:meta.view.tableauthor v:id=iacr-duv5 v:screenName=Tejas.Patel v:displayName=Tejas.Patel
```

## Top Records

```ls
| :updated_at | borough  | building                      | custodial_borough_supervisor_name | custodial_borough_supervisor_phone | custodial    | engineering  | dcas_security | security                | 
| =========== | ======== | ============================= | ================================= | ================================== | ============ | ============ | ============= | ======================= | 
| 1362563026  | Bronx    | Bronx Housing Court           | Ann Wilson                        | 347-386-2979                       | 718-590-7466 | 718-590-1061 | N             | 718-466-3102            | 
| 1362563026  | Bronx    | Bergen Building               | Ann Wilson                        | 347-386-2980                       | 718-579-6730 | 718-590-3234 | Y             | 718-579-6733            | 
| 1362563026  | Bronx    | Concourse Plaza               | Ann Wilson                        | 347-386-2981                       | 718-590-7232 | 718-590-1814 | N             | 718-590-2030            | 
| 1362563026  | Bronx    | Bronx Family & Criminal Court | Ann Wilson                        | 347-386-2982                       | 718-590-3232 | 718-590-3234 | N             | 718-618-2410            | 
| 1362563026  | Bronx    | Bronx Neighborhood Building   | Ann Wilson                        | 347-386-2983                       | 718-655-4893 | 718-590-3835 | N             | 718-881-4455 (9-5, M-F) | 
| 1362563026  | Bronx    | Bronx County Courthouse       | Ann Wilson                        | 347-386-2984                       | 718-590-3486 | 718-590-3835 | N             | 718-618-1701            | 
| 1362563026  | Bronx    | Bronx Hall of Justice         | Ann Wilson                        | 347-386-2985                       | 718-537-1273 | 718-537-5870 | N             | 718-618-1850            | 
| 1362563026  | Brooklyn | Brooklyn Criminal Court       | Robert Pittman                    | 347-386-2986                       | 718-643-2006 | 718-643-2008 | N             | 347-404-9485            | 
| 1362563026  | Brooklyn | Brooklyn Civil Court          | Robert Pittman                    | 347-386-2987                       | 347-404-9142 | N/A          | N             | 347-404-9333            | 
| 1362563026  | Brooklyn | Brooklyn Borough Hall         | Robert Pittman                    | 347-386-2988                       | 718-802-3887 | 718-643-7856 | N             | 718-802-3887            | 
```