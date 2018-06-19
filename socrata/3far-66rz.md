# Freedom Of Information Act (FOIA) Log - Office of the President - Archive

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/freedom-of-information-act-foia-log-office-of-the-president-ffc2a) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/3far-66rz) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/3far-66rz/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/3far-66rz/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | 3far-66rz |
| Name | Freedom Of Information Act (FOIA) Log - Office of the President - Archive |
| Attribution | Toni Preckwinkle, Cook County Board President |
| Category | Finance & Administration |
| Created | 2011-09-21T16:45:17Z |
| Publication Date | 2014-10-09T20:56:12Z |

## Description

This dataset is an archive for historical reference only. For current data please see https://datacatalog.cookcountyil.gov/d/7aqq-ahcq. Updated 3/19/12.  A list of recent FOIA requests sent to the Office of the President.

## Columns

```ls
| Included | Schema Type | Field Name        | Name              | Data Type     | Render Type   |
| ======== | =========== | ================= | ================= | ============= | ============= |
| Yes      | series tag  | name_of_requestor | NAME OF REQUESTOR | text          | text          |
| Yes      | series tag  | organization      | ORGANIZATION      | text          | text          |
| Yes      | series tag  | description       | DESCRIPTION       | text          | text          |
| Yes      | time        | date_received     | DATE RECEIVED     | calendar_date | calendar_date |
| Yes      | series tag  | status_of_request | STATUS OF REQUEST | text          | text          |
```

## Time Field

```ls
Value = date_received
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:3far-66rz d:2012-08-22T07:31:38.000Z t:organization=N/A t:name_of_requestor="Barbara Syzponik" t:status_of_request=Completed t:description="Inquest record" m:row_number.3far-66rz=1

series e:3far-66rz d:2012-08-22T07:31:38.000Z t:organization="Asset Management Consultants" t:name_of_requestor="Chris Hayes" t:status_of_request=Completed t:description="Stale-dated check list" m:row_number.3far-66rz=2

series e:3far-66rz d:2012-08-22T07:31:38.000Z t:organization=N/A t:name_of_requestor="Jackie Wisniewski" t:status_of_request=Completed t:description="Inquest record" m:row_number.3far-66rz=3
```

## Meta Commands

```ls
metric m:row_number.3far-66rz p:long l:"Row Number"

entity e:3far-66rz l:"Freedom Of Information Act (FOIA) Log - Office of the President - Archive" t:attribution="Toni Preckwinkle, Cook County Board President" t:url=https://datacatalog.cookcountyil.gov/api/views/3far-66rz

property e:3far-66rz t:meta.view v:id=3far-66rz v:category="Finance & Administration" v:averageRating=0 v:name="Freedom Of Information Act (FOIA) Log - Office of the President - Archive" v:attribution="Toni Preckwinkle, Cook County Board President"

property e:3far-66rz t:meta.view.license v:name="Public Domain"

property e:3far-66rz t:meta.view.owner v:id=u38g-hbsa v:screenName="Cook County Open Data" v:lastNotificationSeenAt=1492536815 v:displayName="Cook County Open Data"

property e:3far-66rz t:meta.view.tableauthor v:id=u38g-hbsa v:screenName="Cook County Open Data" v:roleName=administrator v:lastNotificationSeenAt=1492536815 v:displayName="Cook County Open Data"
```

## Top Records

```ls
| name_of_requestor   | organization                 | description                                                                  | date_received | status_of_request | 
| =================== | ============================ | ============================================================================ | ============= | ================= | 
| Barbara Syzponik    | N/A                          | Inquest record                                                               |               | Completed         | 
| Chris Hayes         | Asset Management Consultants | Stale-dated check list                                                       |               | Completed         | 
| Jackie Wisniewski   | N/A                          | Inquest record                                                               |               | Completed         | 
| Ruth Susmarski      | N/A                          | Inquest record                                                               |               | Completed         | 
| Theresa Leeser      | N/A                          | Inquest record                                                               |               | Completed         | 
| Carol Wise          | N/A                          | Investigation report prepared by the Sheriff's Office of Professional Review |               | Completed         | 
| Dorothy Holmes      | N/A                          | Inquest record                                                               |               | Completed         | 
| Tim Novak           | Chicago Sun-Times            | Information regarding County amusement tax receipts and waivers              |               | Completed         | 
| Nora Ellin O'Connor | NCM Solutions LLC            | Stale-dated check list                                                       |               | Completed         | 
| Bennie K. Ellison   | N/A                          | Special Escort Officer information                                           |               | Completed         | 
```