# MC311 Service Requests

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/mc311-service-requests-c9504) |
| Metadata | [Link](https://data.montgomerycountymd.gov/api/views/xtyh-brr2) |
| Data: JSON | [100 Rows](https://data.montgomerycountymd.gov/api/views/xtyh-brr2/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.montgomerycountymd.gov/api/views/xtyh-brr2/rows.csv?max_rows=100) |
| Host | data.montgomerycountymd.gov |
| Id | xtyh-brr2 |
| Name | MC311 Service Requests |
| Attribution | Montgomery County, MD Government |
| Category | Government |
| Tags | mc311, services, 311, service, requests |
| Created | 2012-08-20T12:14:39Z |
| Publication Date | 2015-09-09T17:15:17Z |

## Description

Information on all MC311 Service Requests received (via email or phone) since July 1, 2012.  This data is updated daily.
The PIO?s business requirement includes adding the following data elements to the new and enhanced open data site being proposed by DTS.  This data is derived from requests for service which originate in the CSC, from the County?s web portal, and via ?walk-ins? from county departments including but not limited to DHCA.
?	SLA ? to indicate the number of days in county business days the department has to fulfill the request.  County business days must exclude weekends, county holidays and days when the county is closed due to inclement weather (snow days, etc) per CountyStat?s business requirement.  This field has been published in the existing MC311 Service Requests dataset with the field name ?Attached Solution SLA Days?.
?	+/- SLA ?to indicate the number of days a service request is over or under SLA as is currently measured by CountyStat. The following 4 fields will be added to fulfill this line item
?	# of days open ? Number of County Business days the Service Request has been opened.
?	Within SLA Window? - To indicate the number of days a service request is over or under SLA as is currently measured by CountyStat.
?	SLA Yes ? Number of days to fulfill the service request  is under the SLA window.
?	SLA No -? Number of days to fulfill the service request  is over the SLA window.

## Columns

```ls
| Included | Schema Type    | Field Name          | Name                       | Data Type     | Render Type   |
| ======== | ============== | =================== | ========================== | ============= | ============= |
| Yes      | numeric metric | sr_num              | SR ID                      | number        | text          |
| Yes      | time           | created             | Opened                     | calendar_date | calendar_date |
| No       |                | closed              | Closed                     | calendar_date | calendar_date |
| Yes      | series tag     | sr_stat_id          | Status                     | text          | text          |
| Yes      | series tag     | department          | Department                 | text          | text          |
| Yes      | series tag     | sr_area             | Area                       | text          | text          |
| Yes      | series tag     | sr_sub_area         | Sub-Area                   | text          | text          |
| Yes      | series tag     | faq_ques_text       | Attached Solution (Topic)  | text          | text          |
| Yes      | numeric metric | x_sla               | Attached Solution SLA Days | number        | number        |
| Yes      | series tag     | x_city              | City                       | text          | text          |
| Yes      | series tag     | x_state             | State                      | text          | text          |
| Yes      | series tag     | x_zipcode           | Zip Code                   | text          | text          |
| Yes      | series tag     | sr_subtype_cd       | Source                     | text          | text          |
| Yes      | series tag     | x_electiondist      | Election District          | text          | text          |
| Yes      | series tag     | x_mdstatedist       | Maryland State District    | text          | text          |
| Yes      | numeric metric | x_congdist          | Congressional District     | number        | text          |
| Yes      | series tag     | x_cong_memb         | Congressional Member       | text          | text          |
| Yes      | series tag     | x_councildist       | Council District           | text          | text          |
| Yes      | series tag     | x_councilmbr        | Council Member Name        | text          | text          |
| No       |                | last_upd            | Changed Date               | calendar_date | calendar_date |
| Yes      | numeric metric | number_of_days_open | # of Days Open             | number        | number        |
| Yes      | series tag     | within_sla_window   | Within SLA Windows         | text          | text          |
| Yes      | numeric metric | sla_yes             | SLA Yes                    | number        | text          |
| Yes      | series tag     | sla_no              | SLA No                     | text          | text          |
```

## Time Field

```ls
Value = created
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = closed,last_upd
```

## Data Commands

```ls
series e:xtyh-brr2 d:2013-02-15T13:41:23.000Z t:faq_ques_text="Journeyman Electrician applicants approved for Licensure" t:within_sla_window=No t:department=DPS t:sr_area=Licensing t:sr_subtype_cd=Phone t:x_state=MD t:sla_no=1 t:sr_stat_id=Closed m:sla_yes=0 m:x_sla=3 m:sr_num=1133981149 m:number_of_days_open=4

series e:xtyh-brr2 d:2016-10-11T12:33:37.000Z t:department=DEP t:sr_subtype_cd=Web t:x_city="SILVER SPRING" t:x_state=MD t:x_zipcode=20904 t:faq_ques_text="Scrap Metal Pick-Up Request" t:x_councildist=5 t:within_sla_window=Yes t:sr_area="Solid Waste" t:x_mdstatedist=20 t:x_cong_memb="CHRISTOPHER VAN HOLLEN,JR -Dem" t:sr_sub_area="Scrap Metal Request" t:x_councilmbr="Tom Hucker" t:sla_no=0 t:x_electiondist=5 t:sr_stat_id=Closed m:sla_yes=1 m:x_sla=5 m:x_congdist=8 m:sr_num=1303668945 m:number_of_days_open=2

series e:xtyh-brr2 d:2016-11-15T14:25:38.000Z t:department=DEP t:sr_subtype_cd=Phone t:x_city=ROCKVILLE t:x_state=MD t:x_zipcode=20853 t:faq_ques_text="Scrap Metal Pick-Up Request" t:x_councildist=4 t:within_sla_window=Yes t:sr_area="Solid Waste" t:x_mdstatedist=19 t:x_cong_memb="CHRISTOPHER VAN HOLLEN,JR -Dem" t:sr_sub_area="Scrap Metal Request" t:x_councilmbr="Nancy Navarro" t:sla_no=0 t:x_electiondist=13 t:sr_stat_id=Closed m:sla_yes=1 m:x_sla=5 m:x_congdist=8 m:sr_num=1305658856 m:number_of_days_open=3
```

## Meta Commands

```ls
metric m:sr_num p:integer l:"SR ID" d:"Service Request ID Number (unique identifier) assigned by the MC311 Call Center" t:dataTypeName=number

metric m:x_sla p:integer l:"Attached Solution SLA Days" d:"Service Level Agreement (SLA) for the number of days expected for the attached solution to resolve the Service Request" t:dataTypeName=number

metric m:x_congdist p:integer l:"Congressional District" d:"U. S. Congressional District, where location is available" t:dataTypeName=number

metric m:number_of_days_open p:integer l:"# of Days Open" d:"Number of County Business days the Service Request has been opened." t:dataTypeName=number

metric m:sla_yes p:integer l:"SLA Yes" d:"Number of days to fulfill the service request is under the SLA window." t:dataTypeName=number

entity e:xtyh-brr2 l:"MC311 Service Requests" t:attribution="Montgomery County, MD Government" t:url=https://data.montgomerycountymd.gov/api/views/xtyh-brr2

property e:xtyh-brr2 t:meta.view v:id=xtyh-brr2 v:category=Government v:averageRating=0 v:name="MC311 Service Requests" v:attribution="Montgomery County, MD Government"

property e:xtyh-brr2 t:meta.view.owner v:id=ajn4-zy65 v:screenName="MCG ESB Service" v:lastNotificationSeenAt=1491401045 v:displayName="MCG ESB Service"

property e:xtyh-brr2 t:meta.view.tableauthor v:id=ajn4-zy65 v:screenName="MCG ESB Service" v:roleName=administrator v:lastNotificationSeenAt=1491401045 v:displayName="MCG ESB Service"
```

## Top Records

```ls
| sr_num     | created             | closed              | sr_stat_id | department | sr_area                   | sr_sub_area             | faq_ques_text                                                                                                                | x_sla | x_city        | x_state | x_zipcode | sr_subtype_cd | x_electiondist | x_mdstatedist | x_congdist | x_cong_memb                    | x_councildist | x_councilmbr   | last_upd            | number_of_days_open | within_sla_window | sla_yes | sla_no | 
| ========== | =================== | =================== | ========== | ========== | ========================= | ======================= | ============================================================================================================================ | ===== | ============= | ======= | ========= | ============= | ============== | ============= | ========== | ============================== | ============= | ============== | =================== | =================== | ================= | ======= | ====== | 
| 1133981149 | 2013-02-15T13:41:23 | 2013-02-22T07:28:58 | Closed     | DPS        | Licensing                 |                         | Journeyman Electrician applicants approved for Licensure                                                                     | 3     |               | MD      |           | Phone         |                |               |            |                                |               |                | 2016-09-07T13:03:04 | 4                   | No                | 0       | 1      | 
| 1303668945 | 2016-10-11T12:33:37 | 2016-10-13T14:24:33 | Closed     | DEP        | Solid Waste               | Scrap Metal Request     | Scrap Metal Pick-Up Request                                                                                                  | 5     | SILVER SPRING | MD      | 20904     | Web           | 5              | 20            | 8          | CHRISTOPHER VAN HOLLEN,JR -Dem | 5             | Tom Hucker     | 2016-10-13T18:24:34 | 2                   | Yes               | 1       | 0      | 
| 1305658856 | 2016-11-15T14:25:38 | 2016-11-18T07:57:00 | Closed     | DEP        | Solid Waste               | Scrap Metal Request     | Scrap Metal Pick-Up Request                                                                                                  | 5     | ROCKVILLE     | MD      | 20853     | Phone         | 13             | 19            | 8          | CHRISTOPHER VAN HOLLEN,JR -Dem | 4             | Nancy Navarro  | 2016-11-18T12:57:00 | 3                   | Yes               | 1       | 0      | 
| 1310137174 | 2017-02-06T08:33:04 | 2017-02-06T08:35:08 | Closed     | DPS        | Residential Construction  | Residential Inspections | Name and Telephone Number of DPS Residential Building Inspector                                                              | 1     |               | MD      |           | Phone         |                |               |            |                                |               |                | 2017-02-06T13:35:10 | 0                   | Yes               | 1       | 0      | 
| 1310137190 | 2017-02-06T08:40:43 | 2017-02-06T08:41:17 | Closed     | FIN        | Payroll                   |                         | Employee - Questions on the W-2 Form                                                                                         | 1     |               | MD      |           | Phone         |                |               |            |                                |               |                | 2017-02-06T13:41:18 | 0                   | Yes               | 1       | 0      | 
| 1303669355 | 2016-10-11T15:07:58 | 2016-10-13T09:42:02 | Closed     | POL        | Animal Services           | Dead Animal             | Reporting a Dead Animal Along the Roadway or on Adjacent Property                                                            | 1     |               |         | 20878     | Web           | 9              | 17            | 6          | JOHN K. DELANEY -Dem           | 3             | Sidney Katz    | 2016-10-13T13:42:03 | 2                   | No                | 0       | 1      | 
| 1310137228 | 2017-02-06T08:41:07 | 2017-02-06T08:42:11 | Closed     | Non-MCG    |                           |                         | Non-MCG Directory Assistance                                                                                                 | 1     |               | MD      |           | Phone         |                |               |            |                                |               |                | 2017-02-06T13:42:11 | 0                   | Yes               | 1       | 0      | 
| 1310137235 | 2017-02-06T08:43:06 | 2017-02-06T08:43:37 | Closed     | Non-MCG    | PG County                 |                         | Prince George's County 311                                                                                                   | 1     |               | MD      |           | Phone         |                |               |            |                                |               |                | 2017-02-06T13:48:01 | 0                   | Yes               | 1       | 0      | 
| 1305660871 | 2016-11-15T14:52:02 | 2016-11-18T14:50:25 | Closed     | DEP        | Solid Waste               | Bulk Trash Request      | Bulk Trash Pick-Up Request                                                                                                   | 5     | BETHESDA      | MD      | 20816     | Phone         | 7              | 16            | 8          | CHRISTOPHER VAN HOLLEN,JR -Dem | 1             | Roger Berliner | 2016-11-18T19:50:25 | 3                   | Yes               | 1       | 0      | 
| 1310137250 | 2017-02-06T08:45:34 | 2017-02-06T08:46:49 | Closed     | POL        | Abandoned Vehicle Section | Removal                 | Report an Untagged, Abandoned, Dysfunctional, or Inoperable Vehicle on the Public Street, Commercial, or Private Parking Lot | 1     |               | MD      |           | Phone         |                |               |            |                                |               |                | 2017-02-06T13:46:49 | 0                   | Yes               | 1       | 0      | 
```