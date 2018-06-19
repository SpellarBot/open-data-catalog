# Property Data (Buildings Information System)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/property-data-buildings-information-system-275cd) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/e98g-f8hy) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/e98g-f8hy/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/e98g-f8hy/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | e98g-f8hy |
| Name | Property Data (Buildings Information System) |
| Attribution | Department of Buildings (DOB) |
| Category | Housing & Development |
| Tags | property, building, jurisdiction, clean web |
| Created | 2011-10-20T18:03:22Z |
| Publication Date | 2015-02-02T20:50:17Z |

## Description

List of NYC Properties under DOB jurisdiction

## Columns

```ls
| Included | Schema Type    | Field Name                         | Name                               | Data Type     | Render Type   |
| ======== | ============== | ================================== | ================================== | ============= | ============= |
| Yes      | numeric metric | permit_bin                         | Permit BIN                         | number        | number        |
| Yes      | series tag     | permit_application_job_number      | Permit Application Job Number      | text          | number        |
| Yes      | series tag     | permit_application_document_number | Permit Application Document Number | text          | number        |
| Yes      | series tag     | permit_application_job_type        | Permit Application Job Type        | text          | text          |
| Yes      | series tag     | permit_type                        | Permit Type                        | text          | text          |
| Yes      | series tag     | permit_subtype                     | Permit SubType                     | text          | text          |
| Yes      | series tag     | permit_status_description          | Permit Status Description          | text          | text          |
| Yes      | series tag     | permit_sequence_number             | Permit Sequence Number             | text          | number        |
| Yes      | time           | permit_status_date                 | Permit Status Date                 | calendar_date | calendar_date |
| No       |                | permit_issuance_date               | Permit Issuance Date               | calendar_date | calendar_date |
| No       |                | permit_experation_date             | Permit Experation Date             | calendar_date | calendar_date |
```

## Time Field

```ls
Value = permit_status_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = permit_issuance_date,permit_experation_date
```

## Data Commands

```ls
series e:e98g-f8hy d:2011-04-12T00:00:00.000Z t:permit_application_job_number=102790106 t:permit_type=PL t:permit_sequence_number=8 t:permit_application_job_type=A2 t:permit_status_description="PERMIT ISSUED" t:permit_application_document_number=2 m:permit_bin=1083687

series e:e98g-f8hy d:2011-04-12T00:00:00.000Z t:permit_application_job_number=103338201 t:permit_type=PL t:permit_sequence_number=7 t:permit_application_job_type=A2 t:permit_status_description="PERMIT ISSUED" t:permit_application_document_number=1 m:permit_bin=1083690

series e:e98g-f8hy d:2011-04-12T00:00:00.000Z t:permit_application_job_number=102785960 t:permit_type=PL t:permit_sequence_number=7 t:permit_application_job_type=A2 t:permit_status_description="PERMIT ISSUED" t:permit_application_document_number=2 m:permit_bin=1082870
```

## Meta Commands

```ls
metric m:permit_bin p:integer l:"Permit BIN" t:dataTypeName=number

entity e:e98g-f8hy l:"Property Data (Buildings Information System)" t:attribution="Department of Buildings (DOB)" t:url=https://data.cityofnewyork.us/api/views/e98g-f8hy

property e:e98g-f8hy t:meta.view v:id=e98g-f8hy v:category="Housing & Development" v:averageRating=40 v:name="Property Data (Buildings Information System)" v:attribution="Department of Buildings (DOB)"

property e:e98g-f8hy t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:e98g-f8hy t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| permit_bin | permit_application_job_number | permit_application_document_number | permit_application_job_type | permit_type | permit_subtype | permit_status_description | permit_sequence_number | permit_status_date  | permit_issuance_date | permit_experation_date | 
| ========== | ============================= | ================================== | =========================== | =========== | ============== | ========================= | ====================== | =================== | ==================== | ====================== | 
| 1083687    | 102790106                     | 2                                  | A2                          | PL          |                | PERMIT ISSUED             | 8                      | 2011-04-12T00:00:00 | 2011-04-12T00:00:00  | 2012-04-11T00:00:00    | 
| 1083690    | 103338201                     | 1                                  | A2                          | PL          |                | PERMIT ISSUED             | 7                      | 2011-04-12T00:00:00 | 2011-04-12T00:00:00  | 2012-04-11T00:00:00    | 
| 1082870    | 102785960                     | 2                                  | A2                          | PL          |                | PERMIT ISSUED             | 7                      | 2011-04-12T00:00:00 | 2011-04-12T00:00:00  | 2012-04-11T00:00:00    | 
| 1083682    | 102901852                     | 2                                  | A2                          | PL          |                | PERMIT ISSUED             | 9                      | 2011-04-12T00:00:00 | 2011-04-12T00:00:00  | 2012-04-11T00:00:00    | 
| 1082862    | 103345337                     | 1                                  | A2                          | PL          |                | PERMIT ISSUED             | 7                      | 2011-04-12T00:00:00 | 2011-04-12T00:00:00  | 2012-04-11T00:00:00    | 
| 1005283    | 103878895                     | 2                                  | A2                          | PL          |                | PERMIT ISSUED             | 3                      | 2011-04-12T00:00:00 | 2011-04-12T00:00:00  | 2012-04-11T00:00:00    | 
| 1082869    | 102813822                     | 2                                  | A2                          | PL          |                | PERMIT ISSUED             | 7                      | 2011-04-12T00:00:00 | 2011-04-12T00:00:00  | 2012-04-11T00:00:00    | 
| 1082850    | 102780689                     | 2                                  | A2                          | PL          |                | PERMIT ISSUED             | 9                      | 2011-04-12T00:00:00 | 2011-04-12T00:00:00  | 2012-04-11T00:00:00    | 
| 1082860    | 102795183                     | 2                                  | A2                          | PL          |                | PERMIT ISSUED             | 8                      | 2011-04-12T00:00:00 | 2011-04-12T00:00:00  | 2012-04-11T00:00:00    | 
| 1083692    | 102901870                     | 2                                  | A2                          | PL          |                | PERMIT ISSUED             | 8                      | 2011-04-12T00:00:00 | 2011-04-12T00:00:00  | 2012-04-11T00:00:00    | 
```