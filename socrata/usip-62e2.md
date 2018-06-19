# Internal Affairs Allegations

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/internal-affairs-allegations) |
| Metadata | [Link](https://data.montgomerycountymd.gov/api/views/usip-62e2) |
| Data: JSON | [100 Rows](https://data.montgomerycountymd.gov/api/views/usip-62e2/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.montgomerycountymd.gov/api/views/usip-62e2/rows.csv?max_rows=100) |
| Host | data.montgomerycountymd.gov |
| Id | usip-62e2 |
| Name | Internal Affairs Allegations |
| Attribution | Montgomery County, MD |
| Category | Public Safety |
| Tags | internal affair, allegations, finding |
| Created | 2016-06-07T20:43:59Z |
| Publication Date | 2016-06-13T14:02:09Z |

## Description

This dataset contains allegations brought to the attention of the Internal Affairs Division either through external complaints or internal complaint or recognition.  Any information that can be used to uniquely identify the complainant or the involved employee will not be published. Update Frequency : Weekly.

## Columns

```ls
| Included | Schema Type | Field Name      | Name        | Data Type     | Render Type   |
| ======== | =========== | =============== | =========== | ============= | ============= |
| Yes      | series tag  | filenum         | File Number | text          | text          |
| Yes      | time        | created_dt      | Date        | calendar_date | calendar_date |
| Yes      | series tag  | source          | Source      | text          | text          |
| Yes      | series tag  | allegation      | Allegation  | text          | text          |
| Yes      | series tag  | incident_status | Status      | text          | text          |
| Yes      | series tag  | finding         | Finding     | text          | text          |
```

## Time Field

```ls
Value = created_dt
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:usip-62e2 d:2014-06-02T00:00:00.000Z t:source=External t:finding=Sustained t:filenum=14-0115 t:incident_status=Completed t:allegation="Neglect of Duty/Unsatisfactory Performance" m:row_number.usip-62e2=1

series e:usip-62e2 d:2014-07-01T00:00:00.000Z t:source=Internal t:finding=Exonerated t:filenum=14-0141 t:incident_status=Completed t:allegation="Use of Force" m:row_number.usip-62e2=2

series e:usip-62e2 d:2015-08-04T00:00:00.000Z t:source=External t:finding="No Corrective Action Tak" t:filenum=15-0140 t:incident_status=Completed t:allegation="Conduct Unbecoming" m:row_number.usip-62e2=3
```

## Meta Commands

```ls
metric m:row_number.usip-62e2 p:long l:"Row Number"

entity e:usip-62e2 l:"Internal Affairs Allegations" t:attribution="Montgomery County, MD" t:url=https://data.montgomerycountymd.gov/api/views/usip-62e2

property e:usip-62e2 t:meta.view v:id=usip-62e2 v:category="Public Safety" v:averageRating=0 v:name="Internal Affairs Allegations" v:attribution="Montgomery County, MD"

property e:usip-62e2 t:meta.view.license v:name="Public Domain"

property e:usip-62e2 t:meta.view.owner v:id=ajn4-zy65 v:screenName="MCG ESB Service" v:lastNotificationSeenAt=1491401045 v:displayName="MCG ESB Service"

property e:usip-62e2 t:meta.view.tableauthor v:id=ajn4-zy65 v:screenName="MCG ESB Service" v:roleName=administrator v:lastNotificationSeenAt=1491401045 v:displayName="MCG ESB Service"
```

## Top Records

```ls
| filenum | created_dt          | source   | allegation                                 | incident_status | finding                  | 
| ======= | =================== | ======== | ========================================== | =============== | ======================== | 
| 14-0115 | 2014-06-02T00:00:00 | External | Neglect of Duty/Unsatisfactory Performance | Completed       | Sustained                | 
| 14-0141 | 2014-07-01T00:00:00 | Internal | Use of Force                               | Completed       | Exonerated               | 
| 15-0140 | 2015-08-04T00:00:00 | External | Conduct Unbecoming                         | Completed       | No Corrective Action Tak | 
| 15-0191 | 2015-10-22T00:00:00 | External | Abuse of Authority                         | Completed       | Administrative Closure   | 
| 14-0220 | 2014-11-05T00:00:00 | External | Courtesy                                   | Completed       | No Corrective Action Tak | 
| 14-0159 | 2014-07-28T00:00:00 | External | Neglect of Duty/Unsatisfactory Performance | Completed       | No Corrective Action Tak | 
| 14-0172 | 2014-08-13T00:00:00 | Internal | Conformance to Law                         | Completed       | Sustained                | 
| 13-0291 | 2013-10-24T00:00:00 | External | Neglect of Duty/Unsatisfactory Performance | Completed       | Declined                 | 
| 14-0060 | 2014-03-27T00:00:00 | External | Conduct Unbecoming                         | Completed       | Corrective Action Taken  | 
| 15-0227 | 2015-12-21T00:00:00 | External | Neglect of Duty/Unsatisfactory Performance | Completed       | No Corrective Action Tak | 
```