# Plan Review

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/plan-review) |
| Metadata | [Link](https://data.montgomerycountymd.gov/api/views/s8xg-6upf) |
| Data: JSON | [100 Rows](https://data.montgomerycountymd.gov/api/views/s8xg-6upf/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.montgomerycountymd.gov/api/views/s8xg-6upf/rows.csv?max_rows=100) |
| Host | data.montgomerycountymd.gov |
| Id | s8xg-6upf |
| Name | Plan Review |
| Category | Licenses/Permits |
| Tags | plan, reivew, permits |
| Created | 2015-02-25T14:09:57Z |
| Publication Date | 2015-03-13T17:02:37Z |

## Description

Plan reviews completed by Permitting Services. Update Frequency: Daily

## Columns

```ls
| Included | Schema Type    | Field Name  | Name           | Data Type     | Render Type   |
| ======== | ============== | =========== | ============== | ============= | ============= |
| Yes      | series tag     | permitno    | Permit Number  | text          | text          |
| Yes      | series tag     | permit_type | Permit Type    | text          | text          |
| Yes      | numeric metric | reviewkey   | Review Key     | number        | text          |
| Yes      | series tag     | reviewtype  | Review Type    | text          | text          |
| Yes      | series tag     | startby     | Started By     | text          | text          |
| No       |                | startdttm   | Started Date   | calendar_date | calendar_date |
| Yes      | series tag     | compby      | Completed By   | text          | text          |
| Yes      | time           | compdttm    | Completed Date | calendar_date | calendar_date |
| Yes      | series tag     | result      | Result         | text          | text          |
```

## Time Field

```ls
Value = compdttm
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = startdttm
```

## Data Commands

```ls
series e:s8xg-6upf d:2009-05-27T00:00:00.000Z t:result=APPROVED t:permit_type="SOILS TESTING PROCESS" t:permitno=109020081 t:compby=CLARI t:startby=CLARI t:reviewtype="W&S SITE REVIEW" m:reviewkey=8154711

series e:s8xg-6upf d:2009-05-27T00:00:00.000Z t:result=APPROVED t:permit_type="SOILS TESTING PROCESS" t:permitno=109020082 t:compby=CLARI t:startby=CLARI t:reviewtype="W&S SITE REVIEW" m:reviewkey=8154727

series e:s8xg-6upf d:2014-05-07T00:00:00.000Z t:result=APPROVED t:permit_type=SUBDIVISION t:permitno=120041050 t:compby=ROTHG t:startby=ROTHG t:reviewtype="DRC RIGHT-OF-WAY" m:reviewkey=8502380
```

## Meta Commands

```ls
metric m:reviewkey p:integer l:"Review Key" d:"Review Key." t:dataTypeName=number

entity e:s8xg-6upf l:"Plan Review" t:url=https://data.montgomerycountymd.gov/api/views/s8xg-6upf

property e:s8xg-6upf t:meta.view v:id=s8xg-6upf v:category=Licenses/Permits v:averageRating=0 v:name="Plan Review"

property e:s8xg-6upf t:meta.view.owner v:id=ajn4-zy65 v:screenName="MCG ESB Service" v:lastNotificationSeenAt=1491401045 v:displayName="MCG ESB Service"

property e:s8xg-6upf t:meta.view.tableauthor v:id=ajn4-zy65 v:screenName="MCG ESB Service" v:roleName=administrator v:lastNotificationSeenAt=1491401045 v:displayName="MCG ESB Service"
```

## Top Records

```ls
| permitno  | permit_type                 | reviewkey | reviewtype          | startby | startdttm           | compby | compdttm            | result   | 
| ========= | =========================== | ========= | =================== | ======= | =================== | ====== | =================== | ======== | 
| 109020081 | SOILS TESTING PROCESS       | 8154711   | W&S SITE REVIEW     | CLARI   | 2009-05-27T00:00:00 | CLARI  | 2009-05-27T00:00:00 | APPROVED | 
| 109020082 | SOILS TESTING PROCESS       | 8154727   | W&S SITE REVIEW     | CLARI   | 2009-05-27T00:00:00 | CLARI  | 2009-05-27T00:00:00 | APPROVED | 
| 120041050 | SUBDIVISION                 | 8502380   | DRC RIGHT-OF-WAY    | ROTHG   | 2014-05-07T00:00:00 | ROTHG  | 2014-05-07T00:00:00 | APPROVED | 
| 13500RIVE | AGENCY SERVICE REQUEST      | 7414445   | DPS                 | ROBEJ   | 2010-02-19T00:00:00 | ROBEJ  | 2010-02-19T00:00:00 | APPROVED | 
| 157       | FLOODPLAIN STUDY            | 7416296   | FLOODPLAIN REVIEW   | BRUSH   | 1998-09-01T00:00:00 | BRUSH  | 1999-10-05T00:00:00 | APPROVED | 
| 17209EMER | SEWAGE DISPOSAL             | 7427781   | DPS                 | SANDB   | 2000-10-16T00:00:00 | SANDB  | 2000-10-16T00:00:00 | APPROVED | 
| 17209EMER | SEWAGE DISPOSAL             | 7473975   | DPS                 | SANDB   | 2000-10-16T00:00:00 | SANDB  | 2000-10-16T00:00:00 | APPROVED | 
| 200       | BUILDING RESIDENTIAL PERMIT | 8077290   | MHIC LICENSE REVIEW | WOODS   | 2008-05-12T00:00:00 | WOODS  | 2008-05-12T00:00:00 | APPROVED | 
| 200       | FLOODPLAIN STUDY            | 7416367   | FLOODPLAIN REVIEW   | BRUSH   | 1999-11-01T00:00:00 | BRUSH  | 1999-12-01T00:00:00 | APPROVED | 
| 200001    | COUNTY WELL PERMIT          | 6949651   | DPS                 | PALUC   | 1999-09-04T00:00:00 | PALUC  | 1999-09-04T00:00:00 | APPROVED | 
```