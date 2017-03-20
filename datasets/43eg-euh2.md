# EMS - Quarterly Clinical Measures - Trauma Alert

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ems-quarterly-clinical-measures-trauma-alert) |
| Metadata | [Link](https://data.austintexas.gov/api/views/43eg-euh2) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/43eg-euh2/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/43eg-euh2/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | 43eg-euh2 |
| Name | EMS - Quarterly Clinical Measures - Trauma Alert |
| Attribution | Austin-Travis County EMS |
| Category | Public Safety |
| Tags | ems, atcems, clinical data, clinical performance, clinical measures, patient care, trauma, alert |
| Created | 2017-01-17T22:03:22Z |
| Publication Date | 2017-01-18T16:13:49Z |
| Rows Updated | 2017-01-20T15:52:17Z |

## Description

This table contains data describing ATCEMS management of Trauma Alert patients.  In this setting, “Trauma Alert” refers to injured patients who meet Physiological or Anatomical criteria for transport to a Trauma Center per City of Austin/Travis County EMS System Clinical Operating Guidelines.

## Columns

```ls
| Included | Schema Type    | Field Name                           | Name                                             | Data Type     | Render Type   |
| ======== | ============== | ==================================== | ================================================ | ============= | ============= |
| Yes      | numeric metric | fiscal_quarter_key                   | Fiscal Quarter Key                               | number        | number        |
| No       |                | fiscal_quarter                       | Fiscal Quarter                                   | text          | text          |
| Yes      | time           | fiscal_quarter_start_date            | Fiscal Quarter Start Date                        | calendar_date | calendar_date |
| No       |                | fiscal_quarter_end_date              | Fiscal Quarter End Date                          | calendar_date | calendar_date |
| Yes      | numeric metric | count_trauma_alert                   | Count - Trauma Alerts                            | number        | number        |
| Yes      | numeric metric | count_scene_time_compliance          | Count - Trauma Alert Scene Interval Compliance   | number        | number        |
| Yes      | numeric metric | percent_scene_time_compliance        | Percent – Trauma Alert Scene Interval Compliance | percent       | percent       |
| Yes      | numeric metric | percent_scene_time_compliance_target | Trauma Alert Scene Interval Compliance Target    | percent       | percent       |
| Yes      | numeric metric | count_specialty_center               | Count - Trauma Center Transports                 | number        | number        |
| Yes      | numeric metric | percent_specialty_center             | Percent - Trauma Center Transports               | percent       | percent       |
| Yes      | numeric metric | percent_specialty_center_target      | Trauma Center Transport Compliance Target        | percent       | percent       |
| Yes      | numeric metric | average_interval_call_to_door        | Average Call to Door Interval (Minutes)          | number        | number        |
| Yes      | numeric metric | average_interval_call_to_door_target | Call to Door Interval Target                     | number        | number        |
```

## Time Field

```ls
Value = fiscal_quarter_start_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = fiscal_quarter_end_date,fiscal_quarter
```

## Data Commands

```ls
series e:43eg-euh2 d:2013-10-01T00:00:00.000Z m:percent_specialty_center=100 m:average_interval_call_to_door_target=45 m:percent_scene_time_compliance=86.23 m:fiscal_quarter_key=201401 m:count_scene_time_compliance=144 m:percent_scene_time_compliance_target=90 m:count_trauma_alert=167 m:percent_specialty_center_target=95 m:count_specialty_center=167 m:average_interval_call_to_door=34.39

series e:43eg-euh2 d:2014-01-01T00:00:00.000Z m:percent_specialty_center=99.3 m:average_interval_call_to_door_target=45 m:percent_scene_time_compliance=88.81 m:fiscal_quarter_key=201402 m:count_scene_time_compliance=127 m:percent_scene_time_compliance_target=90 m:count_trauma_alert=143 m:percent_specialty_center_target=95 m:count_specialty_center=142 m:average_interval_call_to_door=32.99

series e:43eg-euh2 d:2014-04-01T00:00:00.000Z m:percent_specialty_center=100 m:average_interval_call_to_door_target=45 m:percent_scene_time_compliance=90.96 m:fiscal_quarter_key=201403 m:count_scene_time_compliance=151 m:percent_scene_time_compliance_target=90 m:count_trauma_alert=166 m:percent_specialty_center_target=95 m:count_specialty_center=166 m:average_interval_call_to_door=35.92
```

## Meta Commands

```ls
metric m:fiscal_quarter_key p:integer l:"Fiscal Quarter Key" d:"Row identifier – numeric representation of fiscal quarter in <yyyyqq> format." t:dataTypeName=number

metric m:count_trauma_alert p:integer l:"Count - Trauma Alerts" d:"Count of Trauma Alert patients." t:dataTypeName=number

metric m:count_scene_time_compliance p:integer l:"Count - Trauma Alert Scene Interval Compliance" d:"Count of Trauma Alert patients with a scene interval less than 15 minutes. Scene interval starts when the first ATCEMS personnel arrive on scene, and ends when ATCEMS personnel depart the scene." t:dataTypeName=number

metric m:percent_scene_time_compliance p:float l:"Percent – Trauma Alert Scene Interval Compliance" d:"Percent of Trauma Alert patients with a scene interval less than 15 minutes." t:dataTypeName=percent

metric m:percent_scene_time_compliance_target p:float l:"Trauma Alert Scene Interval Compliance Target" d:"Target performance level for compliance with scene time goal for Trauma Alert patients." t:dataTypeName=percent

metric m:count_specialty_center p:integer l:"Count - Trauma Center Transports" d:"Count of Trauma Alert patients who are transported to a system approved Trauma Center." t:dataTypeName=number

metric m:percent_specialty_center p:float l:"Percent - Trauma Center Transports" d:"Percent of Trauma Alert patients who are transported to a system approved Trauma Center." t:dataTypeName=percent

metric m:percent_specialty_center_target p:float l:"Trauma Center Transport Compliance Target" d:"Target specialty center transport rate for Trauma Alert patients." t:dataTypeName=percent

metric m:average_interval_call_to_door p:float l:"Average Call to Door Interval (Minutes)" d:"Average interval between first 911 call and arrival at the receiving facility for Trauma Alert patients, measured in decimal minutes (e.g. 37.7 minutes)." t:dataTypeName=number

metric m:average_interval_call_to_door_target p:float l:"Call to Door Interval Target" d:"Target for Average Call to Door Interval." t:dataTypeName=number

entity e:43eg-euh2 l:"EMS - Quarterly Clinical Measures - Trauma Alert" t:attribution="Austin-Travis County EMS" t:url=https://data.austintexas.gov/api/views/43eg-euh2

property e:43eg-euh2 t:meta.view v:id=43eg-euh2 v:category="Public Safety" v:averageRating=0 v:name="EMS - Quarterly Clinical Measures - Trauma Alert" v:attribution="Austin-Travis County EMS"

property e:43eg-euh2 t:meta.view.owner v:id=4zcf-8die v:profileImageUrlMedium=/api/users/4zcf-8die/profile_images/THUMB v:profileImageUrlLarge=/api/users/4zcf-8die/profile_images/LARGE v:screenName="Austin-Travis County EMS" v:profileImageUrlSmall=/api/users/4zcf-8die/profile_images/TINY v:roleName=publisher_stories v:displayName="Austin-Travis County EMS"

property e:43eg-euh2 t:meta.view.tableauthor v:id=4zcf-8die v:profileImageUrlMedium=/api/users/4zcf-8die/profile_images/THUMB v:profileImageUrlLarge=/api/users/4zcf-8die/profile_images/LARGE v:screenName="Austin-Travis County EMS" v:profileImageUrlSmall=/api/users/4zcf-8die/profile_images/TINY v:roleName=publisher_stories v:displayName="Austin-Travis County EMS"
```