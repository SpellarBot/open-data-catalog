# NADAC Comparison

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/nadac-comparison) |
| Metadata | [Link](https://data.medicaid.gov/api/views/6gk3-9bxc) |
| Data: JSON | [100 Rows](https://data.medicaid.gov/api/views/6gk3-9bxc/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.medicaid.gov/api/views/6gk3-9bxc/rows.csv?max_rows=100) |
| Host | data.medicaid.gov |
| Id | 6gk3-9bxc |
| Name | NADAC Comparison |
| Attribution | Centers for Medicare and Medicaid Services |
| Category | Drug Pricing and Payment |
| Tags | nadac, nadac comparison |
| Created | 2015-08-19T22:29:45Z |
| Publication Date | 2016-05-03T15:34:24Z |

## Description

The NADAC Weekly Comparison identifies the drug products with current NADAC rates that are replaced with new NADAC rates.  Other changes (e.g. NDC additions and terminations) to the NADAC file are not reflected in this comparison.

## Columns

```ls
| Included | Schema Type    | Field Name                      | Name                            | Data Type     | Render Type   |
| ======== | ============== | =============================== | =============================== | ============= | ============= |
| Yes      | series tag     | ndc_description                 | NDC Description                 | text          | text          |
| Yes      | series tag     | ndc                             | NDC                             | text          | text          |
| Yes      | numeric metric | old_nadac_per_unit              | Old NADAC Per Unit              | number        | number        |
| Yes      | numeric metric | new_nadac_per_unit              | New NADAC Per Unit              | number        | number        |
| Yes      | series tag     | classification_for_rate_setting | Classification for Rate Setting | text          | text          |
| Yes      | numeric metric | percent_change                  | Percent Change                  | percent       | percent       |
| Yes      | series tag     | primary_reason                  | Primary Reason                  | text          | text          |
| Yes      | time           | start_date                      | Start Date                      | calendar_date | calendar_date |
| No       |                | end_date                        | End Date                        | calendar_date | calendar_date |
```

## Time Field

```ls
Value = start_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = end_date
```

## Data Commands

```ls
series e:6gk3-9bxc d:2013-11-28T00:00:00.000Z t:primary_reason="WAC Adjustment" t:ndc=11980001105 t:ndc_description="BLEPH-10 10% EYE DROPS" t:classification_for_rate_setting=B m:percent_change=245.23 m:old_nadac_per_unit=4.96476 m:new_nadac_per_unit=17.13978

series e:6gk3-9bxc d:2013-11-28T00:00:00.000Z t:primary_reason="WAC Adjustment" t:ndc=11980002205 t:ndc_description="BLEPHAMIDE EYE DROPS" t:classification_for_rate_setting=B m:percent_change=4.15 m:old_nadac_per_unit=16.68362 m:new_nadac_per_unit=17.37665

series e:6gk3-9bxc d:2013-11-28T00:00:00.000Z t:primary_reason="WAC Adjustment" t:ndc=11980002210 t:ndc_description="BLEPHAMIDE EYE DROPS" t:classification_for_rate_setting=B m:percent_change=40.49 m:old_nadac_per_unit=12.36584 m:new_nadac_per_unit=17.37265
```

## Meta Commands

```ls
metric m:old_nadac_per_unit p:double l:"Old NADAC Per Unit" t:dataTypeName=number

metric m:new_nadac_per_unit p:double l:"New NADAC Per Unit" t:dataTypeName=number

metric m:percent_change p:float l:"Percent Change" t:dataTypeName=percent

entity e:6gk3-9bxc l:"NADAC Comparison" t:attribution="Centers for Medicare and Medicaid Services" t:url=https://data.medicaid.gov/api/views/6gk3-9bxc

property e:6gk3-9bxc t:meta.view v:id=6gk3-9bxc v:category="Drug Pricing and Payment" v:attributionLink=http://www.medicaid.gov v:averageRating=0 v:name="NADAC Comparison" v:attribution="Centers for Medicare and Medicaid Services"

property e:6gk3-9bxc t:meta.view.license v:name="Public Domain"

property e:6gk3-9bxc t:meta.view.owner v:id=nmzs-t286 v:profileImageUrlMedium=/api/users/nmzs-t286/profile_images/THUMB v:profileImageUrlLarge=/api/users/nmzs-t286/profile_images/LARGE v:screenName="Jeff Chamblee" v:profileImageUrlSmall=/api/users/nmzs-t286/profile_images/TINY v:lastNotificationSeenAt=1491332351 v:displayName="Jeff Chamblee"

property e:6gk3-9bxc t:meta.view.tableauthor v:id=nmzs-t286 v:profileImageUrlMedium=/api/users/nmzs-t286/profile_images/THUMB v:profileImageUrlLarge=/api/users/nmzs-t286/profile_images/LARGE v:screenName="Jeff Chamblee" v:profileImageUrlSmall=/api/users/nmzs-t286/profile_images/TINY v:roleName=administrator v:lastNotificationSeenAt=1491332351 v:displayName="Jeff Chamblee"

property e:6gk3-9bxc t:meta.view.metadata.custom_fields.common_core v:Bureau_Code=009:00 v:Program_Code=009:076
```

## Top Records

```ls
| ndc_description             | ndc         | old_nadac_per_unit | new_nadac_per_unit | classification_for_rate_setting | percent_change | primary_reason | start_date          | end_date            | 
| =========================== | =========== | ================== | ================== | =============================== | ============== | ============== | =================== | =================== | 
| BLEPH-10 10% EYE DROPS      | 11980001105 | 4.96476            | 17.13978           | B                               | 245.23         | WAC Adjustment | 2013-11-28T00:00:00 | 2013-12-05T00:00:00 | 
| BLEPHAMIDE EYE DROPS        | 11980002205 | 16.68362           | 17.37665           | B                               | 4.15           | WAC Adjustment | 2013-11-28T00:00:00 | 2013-12-05T00:00:00 | 
| BLEPHAMIDE EYE DROPS        | 11980002210 | 12.36584           | 17.37265           | B                               | 40.49          | WAC Adjustment | 2013-11-28T00:00:00 | 2013-12-05T00:00:00 | 
| BLEPHAMIDE EYE OINTMENT     | 00023031304 | 23.06996           | 24.56304           | B                               | 6.47           | WAC Adjustment | 2013-11-28T00:00:00 | 2013-12-05T00:00:00 | 
| FML FORTE 0.25% EYE DROPS   | 11980022805 | 6.61291            | 17.43335           | B                               | 163.63         | WAC Adjustment | 2013-11-28T00:00:00 | 2013-12-05T00:00:00 | 
| FML FORTE 0.25% EYE DROPS   | 11980022810 | 5.84597            | 17.54777           | B                               | 200.17         | WAC Adjustment | 2013-11-28T00:00:00 | 2013-12-05T00:00:00 | 
| FML LIQUIFILM 0.1% EYE DROP | 11980021105 | 8.28341            | 17.72599           | B                               | 113.99         | WAC Adjustment | 2013-11-28T00:00:00 | 2013-12-05T00:00:00 | 
| FML S.O.P. 0.1% OINTMENT    | 00023031604 | 15.02903           | 24.93166           | B                               | 65.89          | WAC Adjustment | 2013-11-28T00:00:00 | 2013-12-05T00:00:00 | 
| PRED FORTE 1% EYE DROPS     | 11980018005 | 9.542              | 17.2715            | B                               | 81.01          | WAC Adjustment | 2013-11-28T00:00:00 | 2013-12-05T00:00:00 | 
| PRED FORTE 1% EYE DROPS     | 11980018010 | 9.63577            | 17.45539           | B                               | 81.15          | WAC Adjustment | 2013-11-28T00:00:00 | 2013-12-05T00:00:00 | 
```