# Open Meetings

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/open-meetings-f87aa) |
| Metadata | [Link](https://data.mo.gov/api/views/au6r-w9n3) |
| Data: JSON | [100 Rows](https://data.mo.gov/api/views/au6r-w9n3/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.mo.gov/api/views/au6r-w9n3/rows.csv?max_rows=100) |
| Host | data.mo.gov |
| Id | au6r-w9n3 |
| Name | Open Meetings |
| Category | Government Administration |
| Tags | open meetings |
| Created | 2012-04-25T13:08:52Z |
| Publication Date | 2017-04-20T23:00:55Z |

## Description

Schedule of Missouri Open Meetings

## Columns

```ls
| Included | Schema Type    | Field Name         | Name               | Data Type     | Render Type   |
| ======== | ============== | ================== | ================== | ============= | ============= |
| Yes      | series tag     | meeting_body_name  | Meeting Body Name  | text          | text          |
| Yes      | series tag     | committee          | Committee          | text          | text          |
| Yes      | time           | begin_date_time    | Begin Date Time    | calendar_date | calendar_date |
| Yes      | numeric metric | is_all_day         | Is All Day         | number        | number        |
| Yes      | numeric metric | has_end            | Has End            | number        | number        |
| No       |                | end_date_time      | End Date Time      | calendar_date | calendar_date |
| Yes      | series tag     | building_name      | Building Name      | text          | text          |
| Yes      | series tag     | room               | Room               | text          | text          |
| No       |                | address            | Address            | text          | text          |
| No       |                | address2           | Address2           | text          | text          |
| Yes      | series tag     | city               | City               | text          | text          |
| Yes      | series tag     | state              | State              | text          | text          |
| Yes      | series tag     | zip                | Zip                | text          | text          |
| Yes      | series tag     | webcast_url        | Webcast URL        | text          | text          |
| Yes      | series tag     | webcast_plugin     | Webcast Plugin     | text          | text          |
| Yes      | numeric metric | is_video_conf      | Is Video Conf      | number        | number        |
| Yes      | numeric metric | is_conf_call       | Is Conf Call       | number        | number        |
| Yes      | series tag     | conf_call_number   | Conf Call Number   | text          | text          |
| Yes      | series tag     | conf_call_id       | Conf Call ID       | text          | text          |
| Yes      | series tag     | conf_call_password | Conf Call Password | text          | text          |
| Yes      | series tag     | contact_first_name | Contact First Name | text          | text          |
| Yes      | series tag     | contact_last_name  | Contact Last Name  | text          | text          |
| Yes      | series tag     | phone              | Phone              | text          | text          |
| Yes      | series tag     | email              | Email              | text          | text          |
| Yes      | series tag     | notes              | Notes              | text          | text          |
| Yes      | series tag     | materials_url      | Materials URL      | text          | text          |
| Yes      | series tag     | archived_url       | Archived URL       | text          | text          |
| No       |                | publication_date   | Publication Date   | text          | text          |
| Yes      | series tag     | amendments         | Amendments         | text          | text          |
| No       |                | amendment_date     | Amendment Date     | text          | text          |
```

## Time Field

```ls
Value = begin_date_time
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = end_date_time,address,address2,publication_date,amendment_date
```

## Data Commands

```ls
series e:au6r-w9n3 d:2017-03-20T08:00:00.000Z t:building_name="Division of Professional Registration" t:zip=65109 t:phone="(573) 751-1052" t:meeting_body_name="Missouri State Board of Cosmetology and Barber Examiners" t:notes="Portions of this meeting may go into closed pursuant to Sections 610.021 (1)(3)(5)(7)(13)(14) RSMo and Section 324.001.8 and 324.001.9 RSMo." t:city="Jefferson City" m:is_conf_call=0 m:has_end=0 m:is_video_conf=0 m:is_all_day=0

series e:au6r-w9n3 d:2017-03-20T09:00:00.000Z t:building_name="Lathrop and Gage Law Office" t:phone="(573) 522-6277" t:meeting_body_name="Missouri Board of Therapeutic Massage" t:notes="Portions of this meeting may be closed pursuant to Section 610.021 (1)(14) and Chapter 324.001.8 and 324.001.9 RSMo." t:city="Jefferson City" m:is_conf_call=0 m:has_end=0 m:is_video_conf=0 m:is_all_day=0

series e:au6r-w9n3 d:2017-03-20T10:00:00.000Z t:phone="(573) 751-6793" t:committee="The Early Childhood Mental Health Workgroup meeting" t:contact_first_name=Linda t:meeting_body_name="Coordinating Board for Early Childhood" t:notes="Call-in numbers: 573-526-6012 (Local) or 866-630-9353 (Toll-Free)" t:contact_last_name=Sommers m:is_conf_call=1 m:has_end=0 m:is_video_conf=0 m:is_all_day=0
```

## Meta Commands

```ls
metric m:is_all_day p:long l:"Is All Day" t:dataTypeName=number

metric m:has_end p:long l:"Has End" t:dataTypeName=number

metric m:is_video_conf p:long l:"Is Video Conf" t:dataTypeName=number

metric m:is_conf_call p:long l:"Is Conf Call" t:dataTypeName=number

entity e:au6r-w9n3 l:"Open Meetings" t:url=https://data.mo.gov/api/views/au6r-w9n3

property e:au6r-w9n3 t:meta.view v:id=au6r-w9n3 v:category="Government Administration" v:averageRating=0 v:name="Open Meetings"

property e:au6r-w9n3 t:meta.view.owner v:id=348k-4yz7 v:screenName="State of Missouri" v:displayName="State of Missouri"

property e:au6r-w9n3 t:meta.view.tableauthor v:id=348k-4yz7 v:screenName="State of Missouri" v:displayName="State of Missouri"
```

## Top Records

```ls
| meeting_body_name                                         | committee                                           | begin_date_time     | is_all_day | has_end | end_date_time | building_name                              | room                            | address                       | address2 | city           | state | zip   | webcast_url | webcast_plugin | is_video_conf | is_conf_call | conf_call_number | conf_call_id | conf_call_password | contact_first_name | contact_last_name | phone          | email                    | notes                                                                                                                                                         | materials_url                                | archived_url | publication_date      | amendments | amendment_date        | 
| ========================================================= | =================================================== | =================== | ========== | ======= | ============= | ========================================== | =============================== | ============================= | ======== | ============== | ===== | ===== | =========== | ============== | ============= | ============ | ================ | ============ | ================== | ================== | ================= | ============== | ======================== | ============================================================================================================================================================= | ============================================ | ============ | ===================== | ========== | ===================== | 
| Missouri State Board of Cosmetology and Barber Examiners  |                                                     | 2017-03-20T08:00:00 | 0          | 0       |               | Division of Professional Registration      |                                 | 3605 Missouri Boulevard       |          | Jefferson City |       | 65109 |             |                | 0             | 0            |                  |              |                    |                    |                   | (573) 751-1052 |                          | Portions of this meeting may go into closed pursuant to Sections 610.021 (1)(3)(5)(7)(13)(14) RSMo and Section 324.001.8 and 324.001.9 RSMo.                  |                                              |              | 2017-03-03 12:14:50.0 |            |                       | 
| Missouri Board of Therapeutic Massage                     |                                                     | 2017-03-20T09:00:00 | 0          | 0       |               | Lathrop and Gage Law Office                |                                 | 314 E. High Street            |          | Jefferson City |       |       |             |                | 0             | 0            |                  |              |                    |                    |                   | (573) 522-6277 |                          | Portions of this meeting may be closed pursuant to Section 610.021 (1)(14) and Chapter 324.001.8 and 324.001.9 RSMo.                                          |                                              |              | 2017-03-15 10:53:15.0 |            |                       | 
| Coordinating Board for Early Childhood                    | The Early Childhood Mental Health Workgroup meeting | 2017-03-20T10:00:00 | 0          | 0       |               |                                            |                                 |                               |          |                |       |       |             |                | 0             | 1            |                  |              |                    | Linda              | Sommers           | (573) 751-6793 |                          | Call-in numbers: 573-526-6012 (Local) or 866-630-9353 (Toll-Free)                                                                                             |                                              |              | 2016-12-21 10:32:22.0 |            | 2016-12-21 10:37:27.0 | 
| Committee for Simple, Fair and Low Taxes                  |                                                     | 2017-03-20T12:00:00 | 0          | 0       |               | Harry S Truman Building                    | Room 400                        | 301 West High Street          |          | Jefferson City |       | 65101 |             |                | 0             | 0            |                  |              |                    | Angela             | Burke             | (573) 526-4975 | angela.burke@ded.mo.gov  | Portions of this meeting may be closed pursuant to Section 610.021, RSMo.                                                                                     |                                              |              | 2017-03-17 10:50:45.0 |            |                       | 
| St. Louis Family and Community Partnership                | Self-Evaluation Work Group                          | 2017-03-21T09:00:00 | 0          | 0       |               | Vision for Children at Risk                |                                 | 2433 N. Grand Blvd.           |          | St. Louis      |       | 63106 |             |                | 0             | 0            |                  |              |                    | Barb               | Eshenroder        | (314) 264-7653 |                          |                                                                                                                                                               |                                              |              | 2017-03-20 09:41:12.0 |            |                       | 
| Petroleum Storage Tank Insurance Fund (PSTIF)             | PSTIF Advisory Committee Meeting                    | 2017-03-21T10:30:00 | 0          | 0       |               | Courtyard by Marriott                      | Salon C                         | 3301 Lemone Industrial Avenue |          | Columbia       |       | 65201 |             |                | 0             | 0            |                  |              |                    | Carol              | Eighmey           | (573) 522-2352 | pstif@sprintmail.com     |                                                                                                                                                               | http://www.pstif.org/advisory_committee.html |              | 2017-03-16 08:45:16.0 |            |                       | 
| Missouri Conservation Commission                          | Strategic Planning Workshop                         | 2017-03-21T13:00:00 | 0          | 0       |               | Montauk State Park                         |                                 |                               |          | Salem          |       |       |             |                | 0             | 0            |                  |              |                    | Rhonda             | Maples            | (573) 751-4115 | rhonda.maples@mdc.mo.gov |                                                                                                                                                               |                                              |              | 2017-03-20 10:35:21.0 |            | 2017-03-20 10:37:15.0 | 
| Central Missouri Autism Project Parent Advisory Committee |                                                     | 2017-03-21T17:30:00 | 0          | 0       |               | Easter Seals Midwest Office                |                                 | 918 Bernadette Drive          |          | Columbia       |       | 65203 |             |                | 0             | 0            |                  |              |                    | Jennifer           | Cook              | (573) 441-6268 | jennifer.cook@dmh.mo.gov | For participants who want to call in, please call Easter Seals Midwest Office at 573-874-3777 the day of the meeting to obtain the conference call-in number. |                                              |              | 2016-09-22 08:30:13.0 |            | 2016-09-22 08:35:53.0 | 
| Missouri Conservation Commission                          | Strategic Planning Workshop                         | 2017-03-22T07:45:00 | 0          | 0       |               | Montauk State Park                         |                                 |                               |          | Salem          |       |       |             |                | 0             | 0            |                  |              |                    | Rhonda             | Maples            | (573) 751-4115 | rhonda.maples@mdc.mo.gov |                                                                                                                                                               |                                              |              | 2017-03-20 10:35:58.0 |            |                       | 
| Missouri State Board of Nursing                           |                                                     | 2017-03-22T08:30:00 | 0          | 0       |               | Missouri Council of School Administrators' | Education and Conference Center | 3550 Amazonas Drive           |          | Jefferson City |       | 65109 |             |                | 0             | 0            |                  |              |                    |                    |                   | (573) 751-0681 |                          | Portions of this meeting may be closed pursuant to Section 610.021 (1)(12)(14) RSMo. and Section 324.001.8 and 324.001.9 RSMo. and Section 335.068 RSMo.      |                                              |              | 2017-03-10 09:17:51.0 |            |                       | 
```