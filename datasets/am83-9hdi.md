# Oregon Opioid Treatment Programs

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/oregon-opioid-treatment-programs-d6e1e) |
| Metadata | [Link](https://data.oregon.gov/api/views/am83-9hdi) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/am83-9hdi/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/am83-9hdi/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | am83-9hdi |
| Name | Oregon Opioid Treatment Programs |
| Created | 2014-08-06T15:27:52Z |
| Publication Date | 2014-08-06T15:32:10Z |

## Description

Medication-Assisted Treatment and Recovery Programs in Oregon

## Columns

```ls
| Included | Schema Type | Field Name   | Name         | Data Type | Render Type |
| ======== | =========== | ============ | ============ | ========= | =========== |
| No       | time        | :updated_at  | updated_at   | meta_data | meta_data   |
| Yes      | series tag  | clinic_name  | Clinic Name  | text      | text        |
| Yes      | series tag  | zip_code     | Zip Code     | text      | number      |
| Yes      | series tag  | phone_number | Phone Number | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:am83-9hdi d:2014-08-08T11:03:11.000Z t:phone_number="(503) 252-3949" t:zip_code=97218 t:clinic_name="CRC Health Oregon, Inc." m:row_number.am83-9hdi=1

series e:am83-9hdi d:2014-08-08T11:03:11.000Z t:phone_number="(503) 408-9585" t:zip_code=97220 t:clinic_name="RAM Clinic, Inc." m:row_number.am83-9hdi=2

series e:am83-9hdi d:2014-08-08T11:03:11.000Z t:phone_number="(503) 239-8400" t:zip_code=97214 t:clinic_name="CODA, Inc." m:row_number.am83-9hdi=3
```

## Meta Commands

```ls
metric m:row_number.am83-9hdi p:long l:"Row Number"

entity e:am83-9hdi l:"Oregon Opioid Treatment Programs" t:url=https://data.oregon.gov/api/views/am83-9hdi

property e:am83-9hdi t:meta.view v:id=am83-9hdi v:averageRating=0 v:name="Oregon Opioid Treatment Programs"

property e:am83-9hdi t:meta.view.owner v:id=brxd-x5ss v:profileImageUrlMedium=/api/users/brxd-x5ss/profile_images/THUMB v:profileImageUrlLarge=/api/users/brxd-x5ss/profile_images/LARGE v:screenName=Mike v:profileImageUrlSmall=/api/users/brxd-x5ss/profile_images/TINY v:displayName=Mike

property e:am83-9hdi t:meta.view.tableauthor v:id=brxd-x5ss v:profileImageUrlMedium=/api/users/brxd-x5ss/profile_images/THUMB v:profileImageUrlLarge=/api/users/brxd-x5ss/profile_images/LARGE v:screenName=Mike v:profileImageUrlSmall=/api/users/brxd-x5ss/profile_images/TINY v:roleName=editor v:displayName=Mike
```

## Top Records

```ls
| :updated_at | clinic_name                                  | zip_code | phone_number   | 
| =========== | ============================================ | ======== | ============== | 
| 1407495791  | CRC Health Oregon, Inc.                      | 97218    | (503) 252-3949 | 
| 1407495791  | RAM Clinic, Inc.                             | 97220    | (503) 408-9585 | 
| 1407495791  | CODA, Inc.                                   | 97214    | (503) 239-8400 | 
| 1407495791  | Integrated Health Clinics - Clackamas County | 97267    | (503) 353-9415 | 
| 1407495791  | CRC Health Oregon, Inc.                      | 97005    | (503) 684-8159 | 
| 1407495791  | CRC Health Oregon, Inc.                      | 97302    | (503) 391-9762 | 
| 1407495791  | Marion County Drug Treatment Program         | 97302    | (503) 588-5358 | 
| 1407495791  | Lane County Methadone Treatment Program      | 97401    | (541) 682-4560 | 
| 1407495791  | CRC Health Oregon, Inc.                      | 97205    | (503) 226-2203 | 
| 1407495791  | CRC Health Oregon, Inc.                      | 97504    | (541) 774-8240 | 
```