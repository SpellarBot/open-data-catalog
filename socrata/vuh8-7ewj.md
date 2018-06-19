# OSAC Calendar

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/osac-calendar-17966) |
| Metadata | [Link](https://data.oregon.gov/api/views/vuh8-7ewj) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/vuh8-7ewj/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/vuh8-7ewj/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | vuh8-7ewj |
| Name | OSAC Calendar |
| Category | Public Safety |
| Tags | osac, oregon state athletic commission, mixed martial arts, mma, kick boxing, boxing, entertainment wrestling, wrestling, ring side sports |
| Created | 2013-09-23T14:23:29Z |
| Publication Date | 2017-04-19T23:14:37Z |

## Description

Oregon State Athletic Commission calendar of events

## Columns

```ls
| Included | Schema Type | Field Name              | Name                    | Data Type     | Render Type   |
| ======== | =========== | ======================= | ======================= | ============= | ============= |
| Yes      | series tag  | event_title             | Event Title             | text          | text          |
| Yes      | series tag  | short_description       | Short Description       | text          | text          |
| Yes      | time        | start_date_amp_time     | Start Date & Time       | calendar_date | calendar_date |
| No       |             | end_date_amp_time       | End Date & Time         | calendar_date | calendar_date |
| Yes      | series tag  | street_address          | Street Address          | text          | text          |
| Yes      | series tag  | city                    | City                    | text          | text          |
| Yes      | series tag  | state                   | State                   | text          | text          |
| Yes      | series tag  | zip                     | Zip                     | text          | number        |
| Yes      | series tag  | details                 | Details                 | text          | text          |
| Yes      | series tag  | public_comment_accepted | Public Comment Accepted | text          | text          |
| Yes      | series tag  | contact_name            | Contact Name            | text          | text          |
| Yes      | series tag  | phone_number            | Phone Number            | text          | text          |
| Yes      | series tag  | contact_email           | Contact Email           | text          | text          |
| Yes      | series tag  | web_link_optional       | Web Link (optional)     | text          | text          |
| Yes      | series tag  | map_link                | Map Link                | text          | text          |
| Yes      | series tag  | public_call_in_number   | Public Call-In Number   | text          | text          |
| Yes      | series tag  | call_in_access_code     | Call-in Access Code     | text          | text          |
| Yes      | series tag  | agenda_url              | Agenda URL              | text          | text          |
| Yes      | series tag  | agenda_upload           | Agenda Upload           | text          | text          |
| Yes      | series tag  | map_location            | Map Location            | text          | text          |
| Yes      | series tag  | owner                   | Owner                   | text          | text          |
```

## Time Field

```ls
Value = start_date_amp_time
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = end_date_amp_time
```

## Data Commands

```ls
series e:vuh8-7ewj d:2013-09-21T00:00:00.000Z t:short_description="MMA Event" t:event_title=Knucklehead m:row_number.vuh8-7ewj=1

series e:vuh8-7ewj d:2013-09-22T00:00:00.000Z t:short_description="Entertainment Wrestling" t:event_title="Blue Collar Wrestling" m:row_number.vuh8-7ewj=2

series e:vuh8-7ewj d:2013-09-27T00:00:00.000Z t:short_description="MMA Event at the Moda Center (former Rose Garden)" t:event_title=Bellator m:row_number.vuh8-7ewj=3
```

## Meta Commands

```ls
metric m:row_number.vuh8-7ewj p:long l:"Row Number"

entity e:vuh8-7ewj l:"OSAC Calendar" t:url=https://data.oregon.gov/api/views/vuh8-7ewj

property e:vuh8-7ewj t:meta.view v:id=vuh8-7ewj v:category="Public Safety" v:averageRating=0 v:name="OSAC Calendar"

property e:vuh8-7ewj t:meta.view.owner v:id=fm47-72pe v:screenName=jw_yost v:displayName=jw_yost

property e:vuh8-7ewj t:meta.view.tableauthor v:id=fm47-72pe v:screenName=jw_yost v:roleName=editor v:displayName=jw_yost
```

## Top Records

```ls
| event_title             | short_description                                 | start_date_amp_time | end_date_amp_time   | street_address         | city     | state | zip   | details             | public_comment_accepted | contact_name     | phone_number | contact_email    | web_link_optional | map_link | public_call_in_number | call_in_access_code | agenda_url                                              | agenda_upload | map_location | owner            | 
| ======================= | ================================================= | =================== | =================== | ====================== | ======== | ===== | ===== | =================== | ======================= | ================ | ============ | ================ | ================= | ======== | ===================== | =================== | ======================================================= | ============= | ============ | ================ | 
| Knucklehead             | MMA Event                                         | 2013-09-21T00:00:00 | 2013-09-21T00:00:00 |                        |          |       |       |                     |                         |                  |              |                  |                   |          |                       |                     |                                                         |               |              |                  | 
| Blue Collar Wrestling   | Entertainment Wrestling                           | 2013-09-22T00:00:00 | 2013-09-22T00:00:00 |                        |          |       |       |                     |                         |                  |              |                  |                   |          |                       |                     |                                                         |               |              |                  | 
| Bellator                | MMA Event at the Moda Center (former Rose Garden) | 2013-09-27T00:00:00 | 2013-09-27T00:00:00 |                        |          |       |       |                     |                         |                  |              |                  |                   |          |                       |                     |                                                         |               |              |                  | 
| Blue Collar Wrestling   | Entertainment Wrestling                           | 2013-09-29T00:00:00 | 2013-09-29T00:00:00 |                        |          |       |       |                     |                         |                  |              |                  |                   |          |                       |                     |                                                         |               |              |                  | 
| WCWC                    | Entertainment Wrestling                           | 2013-09-20T00:00:00 | 2013-09-20T00:00:00 |                        |          |       |       |                     |                         | Trista Robischon | 503-378-8739 | osac@state.or.us |                   |          |                       |                     |                                                         |               |              |                  | 
| Power Pit Pro Wrestling | Entertainment Wrestling                           | 2013-11-24T16:30:00 |                     | 111 General Ave        | Roseburg | OR    | 97470 | Army National Guard |                         | Trista Robischon | 503-378-8739 | osac@state.or.us |                   |          |                       |                     |                                                         |               |              |                  | 
| Proposed Rule Change    | telecom conference hearing                        | 2013-10-16T10:00:00 | 2013-10-16T00:00:00 | 4190 Aumsville Hwy. SE | Salem    | OR    | 97317 |                     | Yes                     | Trista Robischon | 503-378-8739 | osac@state.or.us |                   |          | (877) 873?8017        | code #: 9496107     | http://www.oregon.gov/osp/GAMING/pages/b_w_welcome.aspx |               |              | Trista Robischon | 
| Power Pit Pro Wrestling | Entertainment Wrestling                           | 2013-12-15T16:30:00 |                     | 111 General Ave        | Roseburg | OR    | 97470 | Army National Guard |                         | Trista Robischon | 503-378-8739 | osac@state.or.us |                   |          |                       |                     |                                                         |               |              |                  | 
| Power Pit Pro Wrestling | Entertainment Wrestling                           | 2013-10-27T16:30:00 |                     | 111 General Ave        | Roseburg | OR    | 97470 | Army National Guard |                         | Trista Robischon | 503-378-8739 | osac@state.or.us |                   |          |                       |                     |                                                         |               |              |                  | 
| Caged Promotions        | MMA (Roseland Theater)                            | 2013-10-12T19:00:00 | 2013-10-12T23:59:00 |                        | Portland | OR    |       | Roseland Theater    |                         |                  |              |                  |                   |          |                       |                     |                                                         |               |              |                  | 
```