# Title V Calendar set

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/title-v-calendar-set) |
| Metadata | [Link](https://data.oregon.gov/api/views/6raa-5kpf) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/6raa-5kpf/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/6raa-5kpf/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | 6raa-5kpf |
| Name | Title V Calendar set |
| Category | Health & Human Services |
| Created | 2016-09-19T23:29:15Z |
| Publication Date | 2017-02-13T22:49:14Z |

## Columns

```ls
| Included | Schema Type | Field Name           | Name                 | Data Type     | Render Type   |
| ======== | =========== | ==================== | ==================== | ============= | ============= |
| Yes      | series tag  | event_title          | Event Title          | text          | text          |
| Yes      | series tag  | event_location       | Event Location       | text          | text          |
| Yes      | time        | event_start_time     | Event Start Time     | calendar_date | calendar_date |
| No       |             | event_end_time       | Event End Time       | calendar_date | calendar_date |
| Yes      | series tag  | webinar_information  | Webinar Information  | url           | url           |
| Yes      | series tag  | description_of_event | Description of Event | text          | text          |
```

## Time Field

```ls
Value = event_start_time
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = event_end_time
```

## Data Commands

```ls
series e:6raa-5kpf d:2016-10-04T09:00:00.000Z t:webinar_information=https://attendee.gotowebinar.com/register/4542634866231398145 t:event_location=GotoWebinar t:event_title="One Key Question: Implementation in Public Health" m:row_number.6raa-5kpf=1

series e:6raa-5kpf d:2016-10-06T14:00:00.000Z t:event_location="PSOB -810 or Call in" t:event_title="State Title V Coordination Team Meeting" m:row_number.6raa-5kpf=2

series e:6raa-5kpf d:2016-10-17T14:00:00.000Z t:webinar_information=https://attendee.gotowebinar.com/register/9204670820629571073 t:event_location=GotoWebinar t:event_title="One Key Question: Implementation in Public Health" m:row_number.6raa-5kpf=3
```

## Meta Commands

```ls
metric m:row_number.6raa-5kpf p:long l:"Row Number"

entity e:6raa-5kpf l:"Title V Calendar set" t:url=https://data.oregon.gov/api/views/6raa-5kpf

property e:6raa-5kpf t:meta.view v:id=6raa-5kpf v:category="Health & Human Services" v:averageRating=0 v:name="Title V Calendar set"

property e:6raa-5kpf t:meta.view.owner v:id=ashy-reik v:profileImageUrlMedium=/api/users/ashy-reik/profile_images/THUMB v:profileImageUrlLarge=/api/users/ashy-reik/profile_images/LARGE v:screenName=Kaliipnettleton v:profileImageUrlSmall=/api/users/ashy-reik/profile_images/TINY v:displayName=Kaliipnettleton

property e:6raa-5kpf t:meta.view.tableauthor v:id=ashy-reik v:profileImageUrlMedium=/api/users/ashy-reik/profile_images/THUMB v:profileImageUrlLarge=/api/users/ashy-reik/profile_images/LARGE v:screenName=Kaliipnettleton v:profileImageUrlSmall=/api/users/ashy-reik/profile_images/TINY v:roleName=editor v:displayName=Kaliipnettleton
```

## Top Records

```ls
| event_title                                            | event_location        | event_start_time    | event_end_time      | webinar_information                                                   | description_of_event                                          | 
| ====================================================== | ===================== | =================== | =================== | ===================================================================== | ============================================================= | 
| One Key Question: Implementation in Public Health      | GotoWebinar           | 2016-10-04T09:00:00 | 2016-10-04T11:00:00 | [https://attendee.gotowebinar.com/register/4542634866231398145, null] |                                                               | 
| State Title V Coordination Team Meeting                | PSOB -810 or Call in  | 2016-10-06T14:00:00 | 2016-10-06T15:30:00 | [null, null]                                                          |                                                               | 
| One Key Question: Implementation in Public Health      | GotoWebinar           | 2016-10-17T14:00:00 | 2016-10-17T16:00:00 | [https://attendee.gotowebinar.com/register/9204670820629571073, null] |                                                               | 
| State Title V Coordination Team Meeting                | PSOB - 612 or Call in | 2016-11-09T13:30:00 | 2016-11-09T15:30:00 | [null, null]                                                          |                                                               | 
| Title V Trauma and ACEs Work Group GotoMeeting         | PSOB 815 or Call in   | 2016-11-10T10:00:00 | 2016-11-10T12:00:00 | [null, null]                                                          | Call in: 1-877-411-9748 Participant code: 929689              | 
| Title V Trauma and ACEs Work Group GotoMeeting         | PSOB 918 or Call in   | 2016-10-17T13:00:00 | 2016-10-17T15:00:00 | [null, null]                                                          | Call in: 1-877-411-9748 Participant code: 929689              | 
| Title V Annual Plan Webinar                            | Webinar               | 2017-01-12T09:00:00 | 2017-01-12T10:30:00 | [https://attendee.gotowebinar.com/register/3155033601424575235, null] | https://attendee.gotowebinar.com/register/3155033601424575235 | 
| Title V Annual Plan Update Webinar                     | Webinar               | 2017-01-10T13:00:00 | 2017-01-10T14:30:00 | [https://attendee.gotowebinar.com/register/8726099590179522307, null] | https://attendee.gotowebinar.com/register/8726099590179522307 | 
| Title V Annual Plan Reporting TA                       | Webinar               | 2017-02-21T14:00:00 | 2017-02-21T15:00:00 | [https://attendee.gotowebinar.com/register/3319270953329562626, null] |                                                               | 
| Title V Well Woman Care Learning Collaborative Meeting | GoTo Meeting          | 2017-04-03T15:00:00 | 2017-04-03T16:30:00 | [null, null]                                                          |                                                               | 
```