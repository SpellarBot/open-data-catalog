# EMS - Quarterly Clinical Measures - Trauma Alert

## Dataset

* [Dataset URL](https://data.austintexas.gov/api/views/43eg-euh2/rows.json?accessType=DOWNLOAD)
* [Catalog URL](https://catalog.data.gov/dataset/ems-quarterly-clinical-measures-trauma-alert)
* Id = 43eg-euh2
* Name = EMS - Quarterly Clinical Measures - Trauma Alert
* Attribution = Austin-Travis County EMS
* Category = Public Safety
* Tags = [ems, atcems, clinical data, clinical performance, clinical measures, patient care, trauma, alert]
* Created = 2017-01-17T22:03:22Z
* Publication Date = 2017-01-18T16:13:49Z
* Rows Updated = 2017-01-20T15:52:17Z

## Description

This table contains data describing ATCEMS management of Trauma Alert patients.  In this setting, ?Trauma Alert? refers to injured patients who meet Physiological or Anatomical criteria for transport to a Trauma Center per City of Austin/Travis County EMS System Clinical Operating Guidelines.

## Columns

```ls
| Name                                             | Field Name                           | Data Type     | Render Type   | Schema Type    | Included | 
| ================================================ | ==================================== | ============= | ============= | ============== | ======== | 
| Fiscal Quarter Key                               | fiscal_quarter_key                   | number        | number        | numeric metric | Yes      | 
| Fiscal Quarter                                   | fiscal_quarter                       | text          | text          | series tag     | Yes      | 
| Fiscal Quarter Start Date                        | fiscal_quarter_start_date            | calendar_date | calendar_date | time           | Yes      | 
| Fiscal Quarter End Date                          | fiscal_quarter_end_date              | calendar_date | calendar_date |                | No       | 
| Count - Trauma Alerts                            | count_trauma_alert                   | number        | number        | numeric metric | Yes      | 
| Count - Trauma Alert Scene Interval Compliance   | count_scene_time_compliance          | number        | number        | numeric metric | Yes      | 
| Percent ? Trauma Alert Scene Interval Compliance | percent_scene_time_compliance        | percent       | percent       | numeric metric | Yes      | 
| Trauma Alert Scene Interval Compliance Target    | percent_scene_time_compliance_target | percent       | percent       | numeric metric | Yes      | 
| Count - Trauma Center Transports                 | count_specialty_center               | number        | number        | numeric metric | Yes      | 
| Percent - Trauma Center Transports               | percent_specialty_center             | percent       | percent       | numeric metric | Yes      | 
| Trauma Center Transport Compliance Target        | percent_specialty_center_target      | percent       | percent       | numeric metric | Yes      | 
| Average Call to Door Interval (Minutes)          | average_interval_call_to_door        | number        | number        | numeric metric | Yes      | 
| Call to Door Interval Target                     | average_interval_call_to_door_target | number        | number        | numeric metric | Yes      | 
```

## Time Field

```ls
Value = fiscal_quarter_start_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Metric Prefix = 
Included Fields = *
Excluded Fields = fiscal_quarter_end_date
Annotation Fields = 
```

## Data Commands

```ls
series e:43eg-euh2 d:2013-10-01T00:00:00.000Z t:fiscal_quarter=2014-Q1 m:percent_specialty_center=100 m:average_interval_call_to_door_target=45 m:percent_scene_time_compliance=86.23 m:fiscal_quarter_key=201401 m:count_scene_time_compliance=144 m:percent_scene_time_compliance_target=90 m:count_trauma_alert=167 m:percent_specialty_center_target=95 m:count_specialty_center=167 m:average_interval_call_to_door=34.39

series e:43eg-euh2 d:2014-01-01T00:00:00.000Z t:fiscal_quarter=2014-Q2 m:percent_specialty_center=99.3 m:average_interval_call_to_door_target=45 m:percent_scene_time_compliance=88.81 m:fiscal_quarter_key=201402 m:count_scene_time_compliance=127 m:percent_scene_time_compliance_target=90 m:count_trauma_alert=143 m:percent_specialty_center_target=95 m:count_specialty_center=142 m:average_interval_call_to_door=32.99

series e:43eg-euh2 d:2014-04-01T00:00:00.000Z t:fiscal_quarter=2014-Q3 m:percent_specialty_center=100 m:average_interval_call_to_door_target=45 m:percent_scene_time_compliance=90.96 m:fiscal_quarter_key=201403 m:count_scene_time_compliance=151 m:percent_scene_time_compliance_target=90 m:count_trauma_alert=166 m:percent_specialty_center_target=95 m:count_specialty_center=166 m:average_interval_call_to_door=35.92
```

## Meta Commands

```ls
metric m:fiscal_quarter_key p:integer l:"Fiscal Quarter Key" d:"Row identifier ? numeric representation of fiscal quarter in  format." t:dataTypeName=number

metric m:count_trauma_alert p:integer l:"Count - Trauma Alerts" d:"Count of Trauma Alert patients." t:dataTypeName=number

metric m:count_scene_time_compliance p:integer l:"Count - Trauma Alert Scene Interval Compliance" d:"Count of Trauma Alert patients with a scene interval less than 15 minutes. Scene interval starts when the first ATCEMS personnel arrive on scene, and ends when ATCEMS personnel depart the scene." t:dataTypeName=number

metric m:count_specialty_center p:integer l:"Count - Trauma Center Transports" d:"Count of Trauma Alert patients who are transported to a system approved Trauma Center." t:dataTypeName=number

metric m:average_interval_call_to_door l:"Average Call to Door Interval (Minutes)" d:"Average interval between first 911 call and arrival at the receiving facility for Trauma Alert patients, measured in decimal minutes (e.g. 37.7 minutes)." t:dataTypeName=number

metric m:average_interval_call_to_door_target l:"Call to Door Interval Target" d:"Target for Average Call to Door Interval." t:dataTypeName=number

entity e:43eg-euh2 l:"EMS - Quarterly Clinical Measures - Trauma Alert" t:attribution="Austin-Travis County EMS" t:url=https://data.austintexas.gov/api/views/43eg-euh2

property e:43eg-euh2 t:meta.view d:2017-03-03T13:47:42.239Z v:id=43eg-euh2 v:category="Public Safety" v:averageRating=0 v:name="EMS - Quarterly Clinical Measures - Trauma Alert" v:attribution="Austin-Travis County EMS"

property e:43eg-euh2 t:meta.view.owner d:2017-03-03T13:47:42.239Z v:id=4zcf-8die v:profileImageUrlMedium=/api/users/4zcf-8die/profile_images/THUMB v:profileImageUrlLarge=/api/users/4zcf-8die/profile_images/LARGE v:screenName="Austin-Travis County EMS" v:profileImageUrlSmall=/api/users/4zcf-8die/profile_images/TINY v:displayName="Austin-Travis County EMS"

property e:43eg-euh2 t:meta.view.tableauthor d:2017-03-03T13:47:42.239Z v:id=4zcf-8die v:profileImageUrlMedium=/api/users/4zcf-8die/profile_images/THUMB v:profileImageUrlLarge=/api/users/4zcf-8die/profile_images/LARGE v:screenName="Austin-Travis County EMS" v:profileImageUrlSmall=/api/users/4zcf-8die/profile_images/TINY v:roleName=publisher_stories v:displayName="Austin-Travis County EMS"
```