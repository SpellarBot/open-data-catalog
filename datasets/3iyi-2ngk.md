# Archived 2013 Oregon Public Meetings

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/archived-2013-oregon-public-meetings-4659d) |
| Metadata | [Link](https://data.oregon.gov/api/views/3iyi-2ngk) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/3iyi-2ngk/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/3iyi-2ngk/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | 3iyi-2ngk |
| Name | Archived 2013 Oregon Public Meetings |
| Category | Administrative |
| Tags | 2013 public meetings, archived public meetings, 2013 meetings, public meetings |
| Created | 2014-02-12T22:02:01Z |
| Publication Date | 2014-03-05T15:28:20Z |
| Rows Updated | 2014-02-12T22:18:11Z |

## Description

This dataset includes all public meetings that were posted to the Transparency website by State of Oregon agencies, boards, commissions and ESD's from January 1. 2013 through December 31, 2013.  The meetings are sorted by name of agency, board, commission or ESD.

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
series e:3iyi-2ngk d:2013-12-11T17:00:00.000Z t:short_description="Regular Board meeting" t:contact_email=marla.royal@imesd.k12.or.us t:contact_name="Marla J. Royal" t:agency_board_commission_branch="InterMountain ESD" t:meeting_title="IMESD Board Meeting" t:meeting_location="InterMountain ESD" m:row_number=1

series e:3iyi-2ngk d:2013-10-16T10:00:00.000Z t:short_description="Regular Scheduled Commission Meeting" t:contact_email=jenny@ostlund.com t:owner=jenny@ostlund.com t:contact_name=Commissions t:agency_board_commission_branch="Mint Commission, Oregon" t:meeting_title="Mint Commission Meeting" t:meeting_location="Hood River Hotel" m:row_number=2

series e:3iyi-2ngk d:2013-09-09T15:00:00.000Z t:short_description="To review financial information" t:contact_email=lnelson@mesd.k12.or.us t:owner=mskolnic@mesd.k12.or.us t:contact_name="Leslie Nelson" t:agency_board_commission_branch="Multnomah ESD" t:meeting_title="Board Finance Committee" t:meeting_location="11611 NE Ainsworth Circle" m:row_number=3
```

## Meta Commands

```ls
metric m:row_number p:long l:"Row Number"

entity e:3iyi-2ngk l:"Archived 2013 Oregon Public Meetings" t:url=https://data.oregon.gov/api/views/3iyi-2ngk

property e:3iyi-2ngk t:meta.view v:id=3iyi-2ngk v:category=Administrative v:averageRating=0 v:name="Archived 2013 Oregon Public Meetings"

property e:3iyi-2ngk t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:displayName="Paula N."

property e:3iyi-2ngk t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:displayName="Paula N."
```