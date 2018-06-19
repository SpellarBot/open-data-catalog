# Timely and Effective Care - State

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/timely-and-effective-care-state-c68cc) |
| Metadata | [Link](https://data.medicare.gov/api/views/apyc-v239) |
| Data: JSON | [100 Rows](https://data.medicare.gov/api/views/apyc-v239/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.medicare.gov/api/views/apyc-v239/rows.csv?max_rows=100) |
| Host | data.medicare.gov |
| Id | apyc-v239 |
| Name | Timely and Effective Care - State |
| Category | Hospital Compare |
| Tags | hospital compare, timely and effective care |
| Created | 2014-05-14T14:51:29Z |
| Publication Date | 2016-12-19T02:16:17Z |

## Description

Timely and Effective Care measures - state data. This data set includes state-level data for measures of heart attack care, heart failure care, pneumonia care, surgical care, emergency department care, preventive care, children?s asthma care, stroke care, blood clot prevention and treatment, and pregnancy and delivery care.

## Columns

```ls
| Included | Schema Type    | Field Name         | Name               | Data Type     | Render Type   |
| ======== | ============== | ================== | ================== | ============= | ============= |
| Yes      | series tag     | state              | State              | text          | text          |
| Yes      | series tag     | condition          | Condition          | text          | text          |
| Yes      | series tag     | measure_name       | Measure Name       | text          | text          |
| Yes      | series tag     | measure_id         | Measure ID         | text          | text          |
| Yes      | numeric metric | score              | Score              | number        | text          |
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
series e:apyc-v239 d:2015-04-01T00:00:00.000Z t:measure_id=OP_1 t:condition="Heart Attack or Chest Pain" t:state=AK t:measure_name="Median Time to Fibrinolysis" m:score=28

series e:apyc-v239 d:2015-04-01T00:00:00.000Z t:measure_id=OP_1 t:condition="Heart Attack or Chest Pain" t:state=AL t:measure_name="Median Time to Fibrinolysis" m:score=22

series e:apyc-v239 d:2015-04-01T00:00:00.000Z t:measure_id=OP_1 t:condition="Heart Attack or Chest Pain" t:state=AR t:measure_name="Median Time to Fibrinolysis" m:score=35
```

## Meta Commands

```ls
entity e:apyc-v239 l:"Timely and Effective Care - State" t:url=https://data.medicare.gov/api/views/apyc-v239

property e:apyc-v239 t:meta.view v:id=apyc-v239 v:category="Hospital Compare" v:averageRating=0 v:name="Timely and Effective Care - State"

property e:apyc-v239 t:meta.view.owner v:id=drs7-75yr v:profileImageUrlMedium=/api/users/drs7-75yr/profile_images/THUMB v:profileImageUrlLarge=/api/users/drs7-75yr/profile_images/LARGE v:screenName=cms v:profileImageUrlSmall=/api/users/drs7-75yr/profile_images/TINY v:displayName=cms

property e:apyc-v239 t:meta.view.tableauthor v:id=drs7-75yr v:profileImageUrlMedium=/api/users/drs7-75yr/profile_images/THUMB v:profileImageUrlLarge=/api/users/drs7-75yr/profile_images/LARGE v:screenName=cms v:profileImageUrlSmall=/api/users/drs7-75yr/profile_images/TINY v:roleName=administrator v:displayName=cms

property e:apyc-v239 t:meta.view.metadata.custom_fields.common_core v:Publisher="Centers for Medicare & Medicaid Services (CMS)" v:Contact_Email=HospitalCompare@hsag.com v:Contact_Name=CMS v:Bureau_Code=009:38 v:Program_Code=009:078
```

## Top Records

```ls
| state | condition                  | measure_name                | measure_id | score         | footnote                                                 | measure_start_date  | measure_end_date    | 
| ===== | ========================== | =========================== | ========== | ============= | ======================================================== | =================== | =================== | 
| AK    | Heart Attack or Chest Pain | Median Time to Fibrinolysis | OP_1       | 28            |                                                          | 2015-04-01T00:00:00 | 2016-03-31T00:00:00 | 
| AL    | Heart Attack or Chest Pain | Median Time to Fibrinolysis | OP_1       | 22            |                                                          | 2015-04-01T00:00:00 | 2016-03-31T00:00:00 | 
| AR    | Heart Attack or Chest Pain | Median Time to Fibrinolysis | OP_1       | 35            |                                                          | 2015-04-01T00:00:00 | 2016-03-31T00:00:00 | 
| AS    | Heart Attack or Chest Pain | Median Time to Fibrinolysis | OP_1       | Not Available | 5 - Results are not available for this reporting period. | 2015-04-01T00:00:00 | 2016-03-31T00:00:00 | 
| AZ    | Heart Attack or Chest Pain | Median Time to Fibrinolysis | OP_1       | 30            |                                                          | 2015-04-01T00:00:00 | 2016-03-31T00:00:00 | 
| CA    | Heart Attack or Chest Pain | Median Time to Fibrinolysis | OP_1       | 28            |                                                          | 2015-04-01T00:00:00 | 2016-03-31T00:00:00 | 
| CO    | Heart Attack or Chest Pain | Median Time to Fibrinolysis | OP_1       | 29            |                                                          | 2015-04-01T00:00:00 | 2016-03-31T00:00:00 | 
| CT    | Heart Attack or Chest Pain | Median Time to Fibrinolysis | OP_1       | 32            |                                                          | 2015-04-01T00:00:00 | 2016-03-31T00:00:00 | 
| DC    | Heart Attack or Chest Pain | Median Time to Fibrinolysis | OP_1       | Not Available | 5 - Results are not available for this reporting period. | 2015-04-01T00:00:00 | 2016-03-31T00:00:00 | 
| DE    | Heart Attack or Chest Pain | Median Time to Fibrinolysis | OP_1       | Not Available | 5 - Results are not available for this reporting period. | 2015-04-01T00:00:00 | 2016-03-31T00:00:00 | 
```