# Archived 2012 Oregon Public Meetings

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/archived-2012-oregon-public-meetings-ab16d) |
| Metadata | [Link](https://data.oregon.gov/api/views/tyr6-t2jq) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/tyr6-t2jq/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/tyr6-t2jq/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | tyr6-t2jq |
| Name | Archived 2012 Oregon Public Meetings |
| Category | Administrative |
| Tags | 2012 public meetings, archived pubic meetings, 2012 archived public meetings, pubic meetings, 2012 meetings |
| Created | 2014-02-12T21:31:45Z |
| Publication Date | 2014-02-20T21:10:22Z |

## Description

This dataset includes all public meetings that were posted to the Transparency website by State of Oregon agencies, boards, commissions and ESD's from January 1, 2012 through December 31. 2012. The meetings are sorted by name of Agency, Board, Commission or ESD.

## Columns

```ls
| Included | Schema Type | Field Name                           | Name                                 | Data Type     | Render Type   |
| ======== | =========== | ==================================== | ==================================== | ============= | ============= |
| Yes      | series tag  | agency_board_commission_branch       | Agency, Board, Commission, Branch    | text          | text          |
| Yes      | series tag  | meeting_title                        | Meeting Title                        | text          | text          |
| Yes      | series tag  | short_description                    | Short Description                    | text          | text          |
| Yes      | time        | start_date_time                      | Start Date & Time                    | calendar_date | calendar_date |
| No       |             | end_date_time                        | End Date & Time                      | calendar_date | calendar_date |
| Yes      | series tag  | meeting_location                     | Meeting Location                     | text          | text          |
| Yes      | series tag  | details                              | Details                              | text          | text          |
| Yes      | series tag  | public_comment_accepted              | Public Comment Accepted              | text          | text          |
| Yes      | series tag  | contact_name                         | Contact Name                         | text          | text          |
| Yes      | series tag  | phone_number                         | Phone Number                         | text          | text          |
| Yes      | series tag  | contact_email                        | Contact Email                        | email         | email         |
| Yes      | series tag  | web_link_optional                    | Web Link (optional)                  | url           | url           |
| Yes      | series tag  | map_link                             | Map Link                             | url           | url           |
| Yes      | series tag  | calendar_link                        | Calendar Link                        | url           | url           |
| Yes      | series tag  | ada_contact                          | ADA Contact                          | text          | text          |
| Yes      | series tag  | ada_contact_phone                    | ADA Contact Phone                    | text          | text          |
| Yes      | series tag  | ada_contact_email                    | ADA Contact Email                    | email         | email         |
| Yes      | series tag  | webinar_webcast                      | Webinar/Webcast?                     | text          | text          |
| Yes      | series tag  | webinar_webcast_link                 | Webinar/Webcast Link                 | url           | url           |
| Yes      | series tag  | public_call_in_number                | Public Call-In Number                | text          | text          |
| Yes      | series tag  | call_in_access_code                  | Call-in Access Code                  | text          | number        |
| Yes      | series tag  | agenda_url                           | Agenda URL                           | url           | url           |
| Yes      | series tag  | owner                                | Owner                                | email         | email         |
| Yes      | series tag  | agenda_upload                        | Agenda Upload                        | url           | url           |
| Yes      | series tag  | map_location                         | Map Location                         | url           | url           |
| Yes      | series tag  | weblink_to_meeting_minutes_summaries | Weblink to Meeting Minutes/Summaries | url           | url           |
```

## Time Field

```ls
Value = start_date_time
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = end_date_time
```

## Data Commands

```ls
series e:tyr6-t2jq d:2012-11-27T17:15:00.000Z t:short_description="regular bd mtg" t:contact_email=waltenburgr@grantesd.k12.or.us t:owner=waltenburgr@grantesd.k12.or.us t:contact_name="Robert Waltenburg" t:agency_board_commission_branch="Grant ESD" t:meeting_title="board mtg" t:meeting_location=basement m:row_number.tyr6-t2jq=1

series e:tyr6-t2jq d:2012-08-28T17:15:00.000Z t:short_description="regular board meeting" t:contact_email=waltenburgr@grantesd.k12.or.us t:owner=waltenburgr@grantesd.k12.or.us t:contact_name="robert waltenburg" t:agency_board_commission_branch="Grant ESD" t:meeting_title="regular board meeting" t:meeting_location=basement m:row_number.tyr6-t2jq=2

series e:tyr6-t2jq d:2012-12-10T07:00:00.000Z t:short_description="Regular Scheduled Commission Meeting" t:contact_email=jenny@ostlund.com t:owner=jenny@ostlund.com t:contact_name="Jenny Woellmer" t:agency_board_commission_branch="Fine Fescue Commission, Oregon" t:meeting_title="Fine Fescue Commission Meeting" t:meeting_location="Salem Convention Center" m:row_number.tyr6-t2jq=3
```

## Meta Commands

```ls
metric m:row_number.tyr6-t2jq p:long l:"Row Number"

entity e:tyr6-t2jq l:"Archived 2012 Oregon Public Meetings" t:url=https://data.oregon.gov/api/views/tyr6-t2jq

property e:tyr6-t2jq t:meta.view v:id=tyr6-t2jq v:category=Administrative v:averageRating=0 v:name="Archived 2012 Oregon Public Meetings"

property e:tyr6-t2jq t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:tyr6-t2jq t:meta.view.tableauthor v:id=pduc-k7d9 v:screenName="Gene Newton" v:displayName="Gene Newton"
```

## Top Records

```ls
| agency_board_commission_branch                           | meeting_title                        | short_description                       | start_date_time     | end_date_time       | meeting_location        | details | public_comment_accepted | contact_name      | phone_number | contact_email                  | web_link_optional                  | map_link     | calendar_link | ada_contact | ada_contact_phone | ada_contact_email | webinar_webcast | webinar_webcast_link | public_call_in_number | call_in_access_code | agenda_url   | owner                          | agenda_upload | map_location | weblink_to_meeting_minutes_summaries | 
| ======================================================== | ==================================== | ======================================= | =================== | =================== | ======================= | ======= | ======================= | ================= | ============ | ============================== | ================================== | ============ | ============= | =========== | ================= | ================= | =============== | ==================== | ===================== | =================== | ============ | ============================== | ============= | ============ | ==================================== | 
| Grant ESD                                                | board mtg                            | regular bd mtg                          | 2012-11-27T17:15:00 |                     | basement                |         |                         | Robert Waltenburg |              | waltenburgr@grantesd.k12.or.us | [null, null]                       | [null, null] | [null, null]  |             |                   |                   |                 | [null, null]         |                       |                     | [null, null] | waltenburgr@grantesd.k12.or.us | [null, null]  | [null, null] | [null, null]                         | 
| Grant ESD                                                | regular board meeting                | regular board meeting                   | 2012-08-28T17:15:00 |                     | basement                |         |                         | robert waltenburg |              | waltenburgr@grantesd.k12.or.us | [null, null]                       | [null, null] | [null, null]  |             |                   |                   |                 | [null, null]         |                       |                     | [null, null] | waltenburgr@grantesd.k12.or.us | [null, null]  | [null, null] | [null, null]                         | 
| Fine Fescue Commission, Oregon                           | Fine Fescue Commission Meeting       | Regular Scheduled Commission Meeting    | 2012-12-10T07:00:00 |                     | Salem Convention Center |         |                         | Jenny Woellmer    |              | jenny@ostlund.com              | [null, null]                       | [null, null] | [null, null]  |             |                   |                   |                 | [null, null]         |                       |                     | [null, null] | jenny@ostlund.com              | [null, null]  | [null, null] | [null, null]                         | 
| Medical Board, Oregon                                    | Investigative Committee              | Monthly Meeting                         | 2012-06-07T07:30:00 |                     | OMB Offices             |         |                         | Brandy Trotter    | 971-673-2704 | brandy.trotter@state.or.us     | [null, null]                       | [null, null] | [null, null]  |             |                   |                   |                 | [null, null]         |                       |                     | [null, null] | brandy.trotter@state.or.us     | [null, null]  | [null, null] | [null, null]                         | 
| Ryegrass Growers Seed Commission, Oregon                 | Ryegrass Commission Meeting          | Regular Scheduled Commission Meeting    | 2012-11-19T18:00:00 |                     | Cascade Grill           |         |                         | Jenny Woellemr    |              | jenny@ostlund.com              | [null, null]                       | [null, null] | [null, null]  |             |                   |                   |                 | [null, null]         |                       |                     | [null, null] | jenny@ostlund.com              | [null, null]  | [null, null] | [null, null]                         | 
| Prescription Drug Monitoring Program Advisory Commission | 2012 Third Quarter Meeting           | Meeting of the PDMP Advisory Commission | 2012-07-13T13:00:00 |                     | PSOB Room 710           |         |                         | Samantha Greene   |              | samantha.r.greene@state.or.us  | [null, null]                       | [null, null] | [null, null]  |             |                   |                   |                 | [null, null]         |                       |                     | [null, null] | todd.beran@state.or.us         | [null, null]  | [null, null] | [null, null]                         | 
| Health Authority, Oregon                                 | HIV/VH/STI Integrated Planning Group | IPG Meeting                             | 2012-07-18T09:00:00 | 2012-07-18T16:30:00 | Doubletree Hotel        |         |                         | Warren Scott      |              | warren.r.scott@state.or.us     | [null, null]                       | [null, null] | [null, null]  |             |                   |                   |                 | [null, null]         |                       |                     | [null, null] | barbara.j.danel@state.or.us    | [null, null]  | [null, null] | [null, null]                         | 
| Tall Fescue Commission, Oregon                           | Tall Fescue Commission Meeting       | Regular Scheduled Commission Meeting    | 2012-09-27T18:00:00 |                     | Cascade Grill           |         |                         | Jenny Woellmer    |              | jenny@ostlund.com              | [null, null]                       | [null, null] | [null, null]  |             |                   |                   |                 | [null, null]         |                       |                     | [null, null] | jenny@ostlund.com              | [null, null]  | [null, null] | [null, null]                         | 
| Mint Commission, Oregon                                  | Mint Commission Meeting              | Regular Scheduled Commission Meeting    | 2012-10-11T10:00:00 |                     | Hood River Hotel        |         |                         | Jenny Woellmer    |              | jenny@ostlund.com              | [null, null]                       | [null, null] | [null, null]  |             |                   |                   |                 | [null, null]         |                       |                     | [null, null] | jenny@ostlund.com              | [null, null]  | [null, null] | [null, null]                         | 
| Lane ESD                                                 | Board of Directors                   | Regular board meeting                   | 2012-05-22T18:00:00 | 2012-05-22T20:00:00 | 1200 Hwy 99N            |         | yes                     | Barbara McBurnett | 541-461-8213 | bmcburnett@lesd.k12.or.us      | [http://www.lesd.k12.or.us/, null] | [null, null] | [null, null]  |             |                   |                   |                 | [null, null]         |                       |                     | [null, null] | bmcburnett@lesd.k12.or.us      | [null, null]  | [null, null] | [null, null]                         | 
```