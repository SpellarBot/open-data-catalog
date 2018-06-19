# PDRs After using "City of Seattle Public Records Request Center"

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/pdrs-after-to-using-city-of-seattle-public-records-request-center) |
| Metadata | [Link](https://data.seattle.gov/api/views/wj44-r6br) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/wj44-r6br/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/wj44-r6br/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | wj44-r6br |
| Name | PDRs After using "City of Seattle Public Records Request Center" |
| Category | Public Safety |
| Created | 2015-11-21T00:06:35Z |
| Publication Date | 2016-03-15T18:53:41Z |

## Description

PDRs After using "City of Seattle Public Records Request Center"

## Columns

```ls
| Included | Schema Type | Field Name                           | Name                                           | Data Type     | Render Type   |
| ======== | =========== | ==================================== | ============================================== | ============= | ============= |
| Yes      | series tag  | assigned_dept                        | Department                                     | text          | text          |
| Yes      | series tag  | reference_no                         | Request Reference Number                       | text          | text          |
| Yes      | series tag  | request_type                         | Request Type                                   | text          | text          |
| Yes      | series tag  | city_requestertype_internal          | Requester Type                                 | text          | text          |
| Yes      | series tag  | request_status                       | Request Status                                 | text          | text          |
| No       |             | close_date                           | Request Closed Date                            | calendar_date | calendar_date |
| Yes      | time        | create_date                          | Request Create Date                            | calendar_date | calendar_date |
| Yes      | series tag  | source                               | Request Source                                 | text          | text          |
| Yes      | series tag  | spd_receiptofrecordspreference       | Records Receipt Preference                     | text          | text          |
| Yes      | series tag  | spd_recreqincidentreportyesno        | Police Initial Incident Report Requests        | text          | text          |
| Yes      | series tag  | spd_recreqfollowupinvestigationyesno | Police Follow-up Investigation Report Requests | text          | text          |
| Yes      | series tag  | spd_recreqvideoyesno                 | Police Video Requests                          | text          | text          |
| Yes      | series tag  | spd_recreqspd911yesno                | Police 911 Requests                            | text          | text          |
| Yes      | series tag  | spd_recreqphotoyesno                 | Police Photo Requests                          | text          | text          |
| Yes      | series tag  | spd_recreqotheryesno                 | Police Other Requests                          | text          | text          |
```

## Time Field

```ls
Value = create_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = close_date
```

## Data Commands

```ls
series e:wj44-r6br d:2016-10-28T10:04:00.000Z t:source="Counter/In Person" t:spd_recreqspd911yesno=No t:request_status=Received t:request_type=Police t:spd_recreqincidentreportyesno=No t:spd_recreqvideoyesno=No t:spd_recreqphotoyesno=No t:spd_recreqotheryesno=No t:reference_no=P006210-102816 t:spd_recreqfollowupinvestigationyesno=No t:spd_receiptofrecordspreference="Web (Public Records Center)" t:assigned_dept=SPD t:city_requestertype_internal="City Employee" m:row_number.wj44-r6br=1

series e:wj44-r6br d:2017-02-22T16:43:00.000Z t:source=Telephone t:spd_recreqspd911yesno=No t:request_status="Requested Clarification" t:request_type=Police t:spd_recreqincidentreportyesno=No t:spd_recreqvideoyesno=No t:spd_recreqphotoyesno=No t:spd_recreqotheryesno=No t:reference_no=P009868-022217 t:spd_recreqfollowupinvestigationyesno=No t:spd_receiptofrecordspreference="Web (Public Records Center)" t:assigned_dept=SPD t:city_requestertype_internal="City Employee" m:row_number.wj44-r6br=2

series e:wj44-r6br d:2017-03-01T13:06:00.000Z t:source=Telephone t:spd_recreqspd911yesno=No t:request_status="Closed/Failed to Pay/Pick Up" t:request_type=Police t:spd_recreqincidentreportyesno=No t:spd_recreqvideoyesno=No t:spd_recreqphotoyesno=No t:spd_recreqotheryesno=Yes t:reference_no=P009874-030117 t:spd_recreqfollowupinvestigationyesno=Yes t:spd_receiptofrecordspreference="Web (Public Records Center)" t:assigned_dept=SPD t:city_requestertype_internal="City Employee" m:row_number.wj44-r6br=3
```

## Meta Commands

```ls
metric m:row_number.wj44-r6br p:long l:"Row Number"

entity e:wj44-r6br l:"PDRs After using ""City of Seattle Public Records Request Center""" t:url=https://data.seattle.gov/api/views/wj44-r6br

property e:wj44-r6br t:meta.view v:id=wj44-r6br v:category="Public Safety" v:averageRating=0 v:name="PDRs After using ""City of Seattle Public Records Request Center"""

property e:wj44-r6br t:meta.view.owner v:id=avyg-ej9j v:screenName=spd2internetData v:displayName=spd2internetData

property e:wj44-r6br t:meta.view.tableauthor v:id=avyg-ej9j v:screenName=spd2internetData v:roleName=publisher v:displayName=spd2internetData
```

## Top Records

```ls
| assigned_dept | reference_no   | request_type                                              | city_requestertype_internal | request_status                     | close_date          | create_date         | source            | spd_receiptofrecordspreference | spd_recreqincidentreportyesno | spd_recreqfollowupinvestigationyesno | spd_recreqvideoyesno | spd_recreqspd911yesno | spd_recreqphotoyesno | spd_recreqotheryesno | 
| ============= | ============== | ========================================================= | =========================== | ================================== | =================== | =================== | ================= | ============================== | ============================= | ==================================== | ==================== | ===================== | ==================== | ==================== | 
| SPD           | P006210-102816 | Police                                                    | City Employee               | Received                           |                     | 2016-10-28T10:04:00 | Counter/In Person | Web (Public Records Center)    | No                            | No                                   | No                   | No                    | No                   | No                   | 
| SPD           | P009868-022217 | Police                                                    | City Employee               | Requested Clarification            |                     | 2017-02-22T16:43:00 | Telephone         | Web (Public Records Center)    | No                            | No                                   | No                   | No                    | No                   | No                   | 
| SPD           | P009874-030117 | Police                                                    | City Employee               | Closed/Failed to Pay/Pick Up       |                     | 2017-03-01T13:06:00 | Telephone         | Web (Public Records Center)    | No                            | Yes                                  | No                   | No                    | No                   | Yes                  | 
| SPD           | P009875-030117 | Police                                                    | Student                     | Payment Successful-Pending Release |                     | 2017-02-25T00:00:00 | Counter/In Person | Web (Public Records Center)    | No                            | Yes                                  | No                   | No                    | No                   | Yes                  | 
| SPD           | C007125-112316 | Transportation - General                                  | Individual                  | Received                           |                     | 2016-11-23T22:59:00 | Web               |                                |                               |                                      |                      |                       |                      |                      | 
| SPD           | C005483-100516 | Transportation - Traffic, Accident, Maintenance, Potholes | Individual                  | Closed/No Exemptions               | 2016-10-07T10:42:00 | 2016-10-05T09:12:00 | Web               |                                |                               |                                      |                      |                       |                      |                      | 
| SPD           | C006616-110716 | Law                                                       | Individual                  | Closed/Duplicate                   | 2016-11-08T11:29:00 | 2016-11-07T15:36:00 | Web               |                                |                               |                                      |                      |                       |                      |                      | 
| SPD           | C006617-110716 | Law                                                       | Individual                  | Closed/Duplicate                   | 2016-11-08T11:25:00 | 2016-11-07T15:39:00 | Web               |                                |                               |                                      |                      |                       |                      |                      | 
| SPD           | C006618-110716 | Law                                                       | Individual                  | Closed/Duplicate                   | 2016-11-08T11:24:00 | 2016-11-07T16:03:00 | Web               |                                |                               |                                      |                      |                       |                      |                      | 
| SPD           | C009871-021417 | Sustainability & Environment                              | Individual                  | Received                           | 2017-02-21T11:23:00 | 2017-02-14T10:43:00 | Web               |                                |                               |                                      |                      |                       |                      |                      | 
```