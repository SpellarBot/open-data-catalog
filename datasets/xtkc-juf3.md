# National Hospice Item Set (HIS) data

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/national-hospice-item-set-his-data) |
| Metadata | [Link](https://data.medicare.gov/api/views/xtkc-juf3) |
| Data: JSON | [100 Rows](https://data.medicare.gov/api/views/xtkc-juf3/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.medicare.gov/api/views/xtkc-juf3/rows.csv?max_rows=100) |
| Host | data.medicare.gov |
| Id | xtkc-juf3 |
| Name | National Hospice Item Set (HIS) data |
| Category | Hospice Data Directory |
| Tags | hospice care, care, hospice, list |
| Created | 2016-11-16T23:04:38Z |
| Publication Date | 2016-12-16T14:05:23Z |

## Description

This data set includes the national averages (mean) for quality measure scores of Medicare-certified hospice agencies calculated from the Hospice Item Set (HIS) for July 1, 2015 to June 30, 2016.

## Columns

```ls
| Included | Schema Type    | Field Name            | Name                    | Data Type | Render Type |
| ======== | ============== | ===================== | ======================= | ========= | =========== |
| No       | time           | :updated_at           | updated_at              | meta_data | meta_data   |
| Yes      | series tag     | measure_name          | Measure Name            | text      | text        |
| Yes      | numeric metric | national_average_mean | National Average (Mean) | percent   | percent     |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:xtkc-juf3 d:2016-11-16T23:04:40.000Z t:measure_name="The percentage of hospice patients who were offered a treatment option when at risk for Opioid-Induced Constipation" m:national_average_mean=94.1

series e:xtkc-juf3 d:2016-11-16T23:04:40.000Z t:measure_name="The percentage of hospice patients who were checked for pain when admitted to hospice" m:national_average_mean=94

series e:xtkc-juf3 d:2016-11-16T23:04:40.000Z t:measure_name="The percentage of hospice patients who received a timely, thorough pain assessment (cause, type, and impact) when the patient reported pain" m:national_average_mean=76.3
```

## Meta Commands

```ls
metric m:national_average_mean p:float l:"National Average (Mean)" t:dataTypeName=percent

entity e:xtkc-juf3 l:"National Hospice Item Set (HIS) data" t:url=https://data.medicare.gov/api/views/xtkc-juf3

property e:xtkc-juf3 t:meta.view v:id=xtkc-juf3 v:category="Hospice Data Directory" v:averageRating=0 v:name="National Hospice Item Set (HIS) data"

property e:xtkc-juf3 t:meta.view.owner v:id=drs7-75yr v:profileImageUrlMedium=/api/users/drs7-75yr/profile_images/THUMB v:profileImageUrlLarge=/api/users/drs7-75yr/profile_images/LARGE v:screenName=cms v:profileImageUrlSmall=/api/users/drs7-75yr/profile_images/TINY v:displayName=cms

property e:xtkc-juf3 t:meta.view.tableauthor v:id=drs7-75yr v:profileImageUrlMedium=/api/users/drs7-75yr/profile_images/THUMB v:profileImageUrlLarge=/api/users/drs7-75yr/profile_images/LARGE v:screenName=cms v:profileImageUrlSmall=/api/users/drs7-75yr/profile_images/TINY v:roleName=administrator v:displayName=cms

property e:xtkc-juf3 t:meta.view.metadata.custom_fields.common_core v:Publisher="Centers for Medicare & Medicaid Services (CMS)" v:Contact_Name=CMS v:Bureau_Code=009:38 v:Program_Code=009:078
```

## Top Records

```ls
| :updated_at | measure_name                                                                                                                                             | national_average_mean | 
| =========== | ======================================================================================================================================================== | ===================== | 
| 1479337480  | The percentage of hospice patients who were offered a treatment option when at risk for Opioid-Induced Constipation                                      | 94.10                 | 
| 1479337480  | The percentage of hospice patients who were checked for pain when admitted to hospice                                                                    | 94.00                 | 
| 1479337480  | The percentage of hospice patients who received a timely, thorough pain assessment (cause, type, and impact) when the patient reported pain              | 76.30                 | 
| 1479337480  | The percentage of hospice patients who were checked to see whether shortness of breath was a problem when admitted to hospice                            | 97.70                 | 
| 1479337480  | The percentage of hospice patients who received timely treatment when experiencing shortness of breath                                                   | 94.80                 | 
| 1479337480  | The percentage of hospice patients who were asked about their preference for life-sustaining treatments (CPR, ventilator support, hospitalization, etc.) | 98.40                 | 
| 1479337480  | The percentage of hospice patients who were invited to discuss spiritual or religious concerns, beliefs, values                                          | 93.30                 | 
```