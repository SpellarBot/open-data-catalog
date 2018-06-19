# EMS - FY2016 Top 10 Primary Impressions

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ems-fy2016-top-10-primary-impressions) |
| Metadata | [Link](https://data.austintexas.gov/api/views/qnvv-hkw2) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/qnvv-hkw2/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/qnvv-hkw2/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | qnvv-hkw2 |
| Name | EMS - FY2016 Top 10 Primary Impressions |
| Category | Public Safety |
| Tags | ems, atcems, patient contacts, primary impressions, fy2016 |
| Created | 2016-10-31T16:05:33Z |
| Publication Date | 2016-10-31T16:06:23Z |

## Description

** Static Data Set ** This table shows the 10 primary impressions most frequently recorded by ATCEMS field personnel during fiscal year 2016. THE DATA IN THIS TABLE WILL NOT BE UPDATED.

## Columns

```ls
| Included | Schema Type    | Field Name         | Name               | Data Type | Render Type |
| ======== | ============== | ================== | ================== | ========= | =========== |
| Yes      | series tag     | primary_impression | Primary Impression | text      | text        |
| Yes      | numeric metric | contact_count      | Patient Count      | number    | number      |
```

## Time Field

```ls
Value = 2016
Format & Zone = yyyy
```

## Data Commands

```ls
series e:qnvv-hkw2 d:2016-01-01T00:00:00.000Z t:primary_impression="Injury - Extremity Upper" m:contact_count=3793

series e:qnvv-hkw2 d:2016-01-01T00:00:00.000Z t:primary_impression="OD/Poisoning Unspecified" m:contact_count=4403

series e:qnvv-hkw2 d:2016-01-01T00:00:00.000Z t:primary_impression="Injury - Extremity Lower" m:contact_count=4429
```

## Meta Commands

```ls
metric m:contact_count p:integer l:"Patient Count" d:"The count of patient contacts associated with the listed primary impression for Fiscal Year 2016." t:dataTypeName=number

entity e:qnvv-hkw2 l:"EMS - FY2016 Top 10 Primary Impressions" t:url=https://data.austintexas.gov/api/views/qnvv-hkw2

property e:qnvv-hkw2 t:meta.view v:id=qnvv-hkw2 v:category="Public Safety" v:averageRating=0 v:name="EMS - FY2016 Top 10 Primary Impressions"

property e:qnvv-hkw2 t:meta.view.owner v:id=4zcf-8die v:profileImageUrlMedium=/api/users/4zcf-8die/profile_images/THUMB v:profileImageUrlLarge=/api/users/4zcf-8die/profile_images/LARGE v:screenName="Austin-Travis County EMS" v:profileImageUrlSmall=/api/users/4zcf-8die/profile_images/TINY v:displayName="Austin-Travis County EMS"

property e:qnvv-hkw2 t:meta.view.tableauthor v:id=4zcf-8die v:profileImageUrlMedium=/api/users/4zcf-8die/profile_images/THUMB v:profileImageUrlLarge=/api/users/4zcf-8die/profile_images/LARGE v:screenName="Austin-Travis County EMS" v:profileImageUrlSmall=/api/users/4zcf-8die/profile_images/TINY v:roleName=publisher_stories v:displayName="Austin-Travis County EMS"
```

## Top Records

```ls
| primary_impression       | contact_count | 
| ======================== | ============= | 
| Injury - Extremity Upper | 3793          | 
| OD/Poisoning Unspecified | 4403          | 
| Injury - Extremity Lower | 4429          | 
| Injury - Multiple Sites  | 4533          | 
| Psychiatric / Behavioral | 4968          | 
| Respiratory Distress     | 5511          | 
| Altered Mental Status    | 5971          | 
| Injury - Head            | 6082          | 
| Pain - No Trauma         | 9407          | 
| Unspecified Condition    | 21345         | 
```