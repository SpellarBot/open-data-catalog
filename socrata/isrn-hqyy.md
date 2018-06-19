# Timely and Effective Care - National

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/timely-and-effective-care-national-51848) |
| Metadata | [Link](https://data.medicare.gov/api/views/isrn-hqyy) |
| Data: JSON | [100 Rows](https://data.medicare.gov/api/views/isrn-hqyy/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.medicare.gov/api/views/isrn-hqyy/rows.csv?max_rows=100) |
| Host | data.medicare.gov |
| Id | isrn-hqyy |
| Name | Timely and Effective Care - National |
| Category | Hospital Compare |
| Tags | hospital compare, timely and effective care |
| Created | 2014-05-14T14:51:21Z |
| Publication Date | 2016-12-19T02:16:14Z |

## Description

Timely and Effective Care measures - national data. This data set includes national-level data for measures of heart attack care, heart failure care, pneumonia care, surgical care, emergency department care, preventive care, children?s asthma care, stroke care, blood clot prevention and treatment, and pregnancy and delivery care.

## Columns

```ls
| Included | Schema Type    | Field Name         | Name               | Data Type     | Render Type   |
| ======== | ============== | ================== | ================== | ============= | ============= |
| Yes      | series tag     | measure_name       | Measure Name       | text          | text          |
| Yes      | series tag     | measure_id         | Measure ID         | text          | text          |
| Yes      | series tag     | condition          | Condition          | text          | text          |
| Yes      | series tag     | category           | Category           | text          | text          |
| Yes      | numeric metric | score              | Score              | number        | number        |
| No       |                | footnote           | Footnote           | text          | text          |
| Yes      | time           | measure_start_date | Measure Start Date | calendar_date | calendar_date |
| No       |                | measure_end_date   | Measure End Date   | calendar_date | calendar_date |
```

## Time Field

```ls
Value = measure_start_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = footnote,measure_end_date
```

## Data Commands

```ls
series e:isrn-hqyy d:2015-04-01T00:00:00.000Z t:category=ED1 t:measure_id=ED_1b t:condition="Emergency Department" t:measure_name="Average (median) time patients spent in the emergency department, before they were admitted to the hospital as an inpatient A lower number of minutes is better" m:score=279

series e:isrn-hqyy d:2015-04-01T00:00:00.000Z t:category="ED1 - Median time from emergency department arrival to emergency department departure for admitted emergency department patients" t:measure_id=ED_1b_HIGH_MIN t:condition="Emergency Department" t:measure_name="Average time patients spent in the emergency department, before they were admitted to the hospital as an inpatient A lower number of minutes is better (high)" m:score=295

series e:isrn-hqyy d:2015-04-01T00:00:00.000Z t:category="ED1 - Median time from emergency department arrival to emergency department departure for admitted emergency department patients" t:measure_id=ED_1b_LOW_MIN t:condition="Emergency Department" t:measure_name="Average time patients spent in the emergency department, before they were admitted to the hospital as an inpatient A lower number of minutes is better (low)" m:score=210
```

## Meta Commands

```ls
metric m:score p:integer l:Score t:dataTypeName=number

entity e:isrn-hqyy l:"Timely and Effective Care - National" t:url=https://data.medicare.gov/api/views/isrn-hqyy

property e:isrn-hqyy t:meta.view v:id=isrn-hqyy v:category="Hospital Compare" v:averageRating=0 v:name="Timely and Effective Care - National"

property e:isrn-hqyy t:meta.view.owner v:id=drs7-75yr v:profileImageUrlMedium=/api/users/drs7-75yr/profile_images/THUMB v:profileImageUrlLarge=/api/users/drs7-75yr/profile_images/LARGE v:screenName=cms v:profileImageUrlSmall=/api/users/drs7-75yr/profile_images/TINY v:displayName=cms

property e:isrn-hqyy t:meta.view.tableauthor v:id=drs7-75yr v:profileImageUrlMedium=/api/users/drs7-75yr/profile_images/THUMB v:profileImageUrlLarge=/api/users/drs7-75yr/profile_images/LARGE v:screenName=cms v:profileImageUrlSmall=/api/users/drs7-75yr/profile_images/TINY v:roleName=administrator v:displayName=cms

property e:isrn-hqyy t:meta.view.metadata.custom_fields.common_core v:Publisher="Centers for Medicare & Medicaid Services (CMS)" v:Contact_Email=HospitalCompare@hsag.com v:Contact_Name=CMS v:Bureau_Code=009:38 v:Program_Code=009:078
```

## Top Records

```ls
| measure_name                                                                                                                                                                                                                    | measure_id          | condition            | category                                                                                                                         | score | footnote | measure_start_date  | measure_end_date    | 
| =============================================================================================================================================================================================================================== | =================== | ==================== | ================================================================================================================================ | ===== | ======== | =================== | =================== | 
| Average (median) time patients spent in the emergency department, before they were admitted to the hospital as an inpatient A lower number of minutes is better                                                                 | ED_1b               | Emergency Department | ED1                                                                                                                              | 279   |          | 2015-04-01T00:00:00 | 2016-03-31T00:00:00 | 
| Average time patients spent in the emergency department, before they were admitted to the hospital as an inpatient A lower number of minutes is better (high)                                                                   | ED_1b_HIGH_MIN      | Emergency Department | ED1 - Median time from emergency department arrival to emergency department departure for admitted emergency department patients | 295   |          | 2015-04-01T00:00:00 | 2016-03-31T00:00:00 | 
| Average time patients spent in the emergency department, before they were admitted to the hospital as an inpatient A lower number of minutes is better (low)                                                                    | ED_1b_LOW_MIN       | Emergency Department | ED1 - Median time from emergency department arrival to emergency department departure for admitted emergency department patients | 210   |          | 2015-04-01T00:00:00 | 2016-03-31T00:00:00 | 
| Average time patients spent in the emergency department, before they were admitted to the hospital as an inpatient A lower number of minutes is better (moderate)                                                               | ED_1b_MEDIUM_MIN    | Emergency Department | ED1 - Median time from emergency department arrival to emergency department departure for admitted emergency department patients | 258   |          | 2015-04-01T00:00:00 | 2016-03-31T00:00:00 | 
| Average time patients spent in the emergency department, before they were admitted to the hospital as an inpatient A lower number of minutes is better (overall)                                                                | ED_1b_OVERALL_MIN   | Emergency Department | ED1 - Median time from emergency department arrival to emergency department departure for admitted emergency department patients | 275   |          | 2015-04-01T00:00:00 | 2016-03-31T00:00:00 | 
| Average time patients spent in the emergency department, before they were admitted to the hospital as an inpatient A lower number of minutes is better (high)                                                                   | ED_1b_VERY_HIGH_MIN | Emergency Department | ED1 - Median time from emergency department arrival to emergency department departure for admitted emergency department patients | 338   |          | 2015-04-01T00:00:00 | 2016-03-31T00:00:00 | 
| Average (median) time patients spent in the emergency department, after the doctor decided to admit them as an inpatient before leaving the emergency department for their inpatient room A lower number of minutes is better   | ED_2b               | Emergency Department | ED2                                                                                                                              | 99    |          | 2015-04-01T00:00:00 | 2016-03-31T00:00:00 | 
| Average time patients spent in the emergency department, after the doctor decided to admit them as an inpatient before leaving the emergency department for their inpatient room A lower number of minutes is better (high)     | ED_2b_HIGH_MIN      | Emergency Department | ED2 - Admit decision time to emergency department departure time for admitted patient                                            | 115   |          | 2015-04-01T00:00:00 | 2016-03-31T00:00:00 | 
| Average time patients spent in the emergency department, after the doctor decided to admit them as an inpatient before leaving the emergency department for their inpatient room A lower number of minutes is better (low)      | ED_2b_LOW_MIN       | Emergency Department | ED2 - Admit decision time to emergency department departure time for admitted patient                                            | 58    |          | 2015-04-01T00:00:00 | 2016-03-31T00:00:00 | 
| Average time patients spent in the emergency department, after the doctor decided to admit them as an inpatient before leaving the emergency department for their inpatient room A lower number of minutes is better (moderate) | ED_2b_MEDIUM_MIN    | Emergency Department | ED2 - Admit decision time to emergency department departure time for admitted patient                                            | 88    |          | 2015-04-01T00:00:00 | 2016-03-31T00:00:00 | 
```