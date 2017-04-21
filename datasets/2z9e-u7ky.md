# Santa Rosa Police Department Incidents

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/santa-rosa-police-department-incidents) |
| Metadata | [Link](https://data.srcity.org/api/views/2z9e-u7ky) |
| Data: JSON | [100 Rows](https://data.srcity.org/api/views/2z9e-u7ky/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.srcity.org/api/views/2z9e-u7ky/rows.csv?max_rows=100) |
| Host | data.srcity.org |
| Id | 2z9e-u7ky |
| Name | Santa Rosa Police Department Incidents |
| Category | Police |
| Created | 2015-11-17T00:18:17Z |
| Publication Date | 2017-03-09T23:41:56Z |

## Description

Incidents refers to a specific criminal act involving one or more victims and offenders. For example, if two people are robbed at the same time and place, this is classified as two robbery victimizations but only one robbery incident.

## Columns

```ls
| Included | Schema Type | Field Name      | Name            | Data Type     | Render Type   |
| ======== | =========== | =============== | =============== | ============= | ============= |
| Yes      | series tag  | incident_number | incident_number | text          | number        |
| Yes      | time        | date_time       | date_time       | calendar_date | calendar_date |
| Yes      | series tag  | incident_type   | incident_type   | text          | text          |
| Yes      | series tag  | intersection    | intersection    | text          | text          |
| Yes      | series tag  | location_type   | location_type   | text          | text          |
| No       |             | id              | id              | text          | number        |
| Yes      | series tag  | agency_code     | agency_code     | text          | text          |
| Yes      | series tag  | agency          | agency          | text          | text          |
| Yes      | series tag  | location        | location        | text          | text          |
```

## Time Field

```ls
Value = date_time
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = id
```

## Data Commands

```ls
series e:2z9e-u7ky d:2017-02-25T04:50:00.000Z t:incident_type="ALL OTHER OFFENSE" t:intersection="HENDLEY ST / S E ST" t:location=(38.4316382700001,-122.705352147) t:agency="Santa Rosa Police Department" t:incident_number=170002620 t:agency_code=SRP m:row_number.2z9e-u7ky=1

series e:2z9e-u7ky d:2015-10-01T00:00:00.000Z t:incident_type="ALL OTHER OFFENSE" t:intersection="2ND ST / PIERCE ST" t:location_type=RESIDENCE/HOME t:location=(38.4435100600001,-122.703735225) t:agency="Santa Rosa Police Department" t:incident_number=160010951 t:agency_code=SRP m:row_number.2z9e-u7ky=2

series e:2z9e-u7ky d:2016-12-26T10:50:00.000Z t:incident_type="MOTOR VEHICLE THEFT" t:intersection="AIRWAY DR / HOPPER AV" t:location_type="MOTOR VEHICLE" t:location=(38.4797068240001,-122.738117524) t:agency="Santa Rosa Police Department" t:incident_number=160017284 t:agency_code=SRP m:row_number.2z9e-u7ky=3
```

## Meta Commands

```ls
metric m:row_number.2z9e-u7ky p:long l:"Row Number"

entity e:2z9e-u7ky l:"Santa Rosa Police Department Incidents" t:url=https://data.srcity.org/api/views/2z9e-u7ky

property e:2z9e-u7ky t:meta.view v:id=2z9e-u7ky v:category=Police v:averageRating=0 v:name="Santa Rosa Police Department Incidents"

property e:2z9e-u7ky t:meta.view.owner v:id=u2re-x7kp v:screenName="Petri, Jerry" v:displayName="Petri, Jerry"

property e:2z9e-u7ky t:meta.view.tableauthor v:id=u2re-x7kp v:screenName="Petri, Jerry" v:roleName=administrator v:displayName="Petri, Jerry"
```

## Top Records

```ls
| incident_number | date_time           | incident_type                                | intersection                                  | location_type              | id      | agency_code | agency                       | location                          | 
| =============== | =================== | ============================================ | ============================================= | ========================== | ======= | =========== | ============================ | ================================= | 
| 170002620       | 2017-02-25T04:50:00 | ALL OTHER OFFENSE                            | HENDLEY ST / S E ST                           |                            | 1238562 | SRP         | Santa Rosa Police Department | (38.4316382700001,-122.705352147) | 
| 160010951       | 2015-10-01T00:00:00 | ALL OTHER OFFENSE                            | 2ND ST / PIERCE ST                            | RESIDENCE/HOME             | 1193757 | SRP         | Santa Rosa Police Department | (38.4435100600001,-122.703735225) | 
| 160017284       | 2016-12-26T10:50:00 | MOTOR VEHICLE THEFT                          | AIRWAY DR / HOPPER AV                         | MOTOR VEHICLE              | 1224309 | SRP         | Santa Rosa Police Department | (38.4797068240001,-122.738117524) | 
| 160017314       | 1980-01-01T00:00:00 | ALL OTHER OFFENSE                            | BROOKWOOD AV / SONOMA AV                      | COMMERCIAL/OFFICE BUILDING | 1224398 | SRP         | Santa Rosa Police Department | (38.440358487,-122.70281762)      | 
| 170001269       | 2017-01-28T13:00:00 | BURGLARY - RESIDENTIAL                       | EDGEWATER DR / SWEET GRASS LN                 | RESIDENCE/HOME             | 1231937 | SRP         | Santa Rosa Police Department | (38.413776182,-122.749538745)     | 
| 170001460       | 2017-01-27T12:19:00 | LARCENY / THEFT OFFENSES - ALL OTHER LARCENY | CRAWFORD CT / MENDOCINO AV                    | SCHOOL/COLLEGE             | 1233049 | SRP         | Santa Rosa Police Department | (38.4515443990001,-122.717477064) | 
| 170001715       | 2017-02-07T14:27:00 | SEX OFFENSES / NON-FORCIBLE - STATUTORY RAPE | MOJAVE AV / WHITE SANDS ST                    | AIR/BUS/TRAIN TERMINAL     | 1234369 | SRP         | Santa Rosa Police Department | (38.40369115,-122.728645673)      | 
| 170001721       | 2017-02-07T14:49:00 | DESTRUCTION OF PROPERTY / VANDALISM          | CLEMENT AV / SALEM AV                         | HIGHWAY/ROAD/ALLEY         | 1234380 | SRP         | Santa Rosa Police Department | (38.458780948,-122.718659549)     | 
| 170001736       | 2017-02-07T16:47:00 | COUNTERFEITING / FORGERY                     | ADMINISTRATION DR / CHANATE RD / MENDOCINO AV | BANK/SAVINGS & LOAN        | 1234475 | SRP         | Santa Rosa Police Department | (38.4650527790001,-122.719368629) | 
| 170001741       | 2017-01-25T17:53:00 | DESTRUCTION OF PROPERTY / VANDALISM          | BARNETT ST / S DAVIS ST                       | RESIDENCE/HOME             | 1234487 | SRP         | Santa Rosa Police Department | (38.4305089110001,-122.716019911) | 
```