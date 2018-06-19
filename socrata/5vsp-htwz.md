# FDNY Certificate Of Fitness Rules Codes

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/fdny-certificate-of-fitness-rules-codes-a64d7) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/5vsp-htwz) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/5vsp-htwz/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/5vsp-htwz/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 5vsp-htwz |
| Name | FDNY Certificate Of Fitness Rules Codes |
| Attribution | Fire Department of New York City (FDNY) |
| Category | Public Safety |
| Tags | fdny, fire department, safety, fire safety, fire code, fire rule, certificate of fitness, cof |
| Created | 2013-01-31T16:19:05Z |
| Publication Date | 2013-01-31T16:22:34Z |

## Description

Rules and Codes required for Certificate of Fitness - FDNY

## Columns

```ls
| Included | Schema Type | Field Name                             | Name                                    | Data Type | Render Type |
| ======== | =========== | ====================================== | ======================================= | ========= | =========== |
| No       | time        | :updated_at                            | updated_at                              | meta_data | meta_data   |
| Yes      | series tag  | type_of_material_operation_or_facility | Type of Material, Operation or Facility | text      | text        |
| Yes      | series tag  | supervision_type                       | Supervision Type                        | text      | text        |
| Yes      | series tag  | fire_code_rule_section                 | Fire Code /Rule Section                 | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:5vsp-htwz d:2013-01-31T08:19:07.000Z t:fire_code_rule_section=R301-01(b)(1) t:supervision_type=Personal t:type_of_material_operation_or_facility="Boatyards, marinas and similar facilities" m:row_number.5vsp-htwz=1

series e:5vsp-htwz d:2013-01-31T08:19:07.000Z t:fire_code_rule_section=FC303.4 t:supervision_type=Personal t:type_of_material_operation_or_facility="Tar kettle operations using combustible liquid" m:row_number.5vsp-htwz=2

series e:5vsp-htwz d:2013-01-31T08:19:07.000Z t:fire_code_rule_section=R303-01(b)(2) t:supervision_type=Personal t:type_of_material_operation_or_facility="Asphalt melter operations using combustible liquid" m:row_number.5vsp-htwz=3
```

## Meta Commands

```ls
metric m:row_number.5vsp-htwz p:long l:"Row Number"

entity e:5vsp-htwz l:"FDNY Certificate Of Fitness Rules Codes" t:attribution="Fire Department of New York City (FDNY)" t:url=https://data.cityofnewyork.us/api/views/5vsp-htwz

property e:5vsp-htwz t:meta.view v:id=5vsp-htwz v:category="Public Safety" v:attributionLink=http://www.nyc.gov/html/fdny/pdf/firecode/certificate_of_fitness.pdf v:averageRating=0 v:name="FDNY Certificate Of Fitness Rules Codes" v:attribution="Fire Department of New York City (FDNY)"

property e:5vsp-htwz t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:5vsp-htwz t:meta.view.tableauthor v:id=syvn-4vgv v:screenName="Sudhir Vasudeva" v:displayName="Sudhir Vasudeva"
```

## Top Records

```ls
| :updated_at | type_of_material_operation_or_facility             | supervision_type | fire_code_rule_section | 
| =========== | ================================================== | ================ | ====================== | 
| 1359620347  | Boatyards, marinas and similar facilities          | Personal         | R301-01(b)(1)          | 
| 1359620347  | Tar kettle operations using combustible liquid     | Personal         | FC303.4                | 
| 1359620347  | Asphalt melter operations using combustible liquid | Personal         | R303-01(b)(2)          | 
| 1359620347  | Portable space heaters storage, handling and use   | Personal/General | FC313.5.2.6            | 
| 1359620347  | De-fueling motor vehicle fuel tanks                | Personal         | FC316.3                | 
| 1359620347  | Cellulose nitrate storage, handling and use        | Personal/General | FC306.2.1              | 
| 1359620347  | Group A occupancies (fire safety training)         | Personal         | FC401.6.1              | 
| 1359620347  | Group B office building fire safety director       | Personal         | FC401.6.2.2            | 
| 1359620347  | Group B office building EAP/fire safety director   | Personal         | FC401.7.2              | 
| 1359620347  | Group I-2 occupancies (fire safety training)       | Personal         | FC401.6.4              | 
```