# SFMTA-Enforced Temporary Tow Zones

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/sfmta-enforced-temporary-tow-zones-2e176) |
| Metadata | [Link](https://data.sfgov.org/api/views/cqn5-muyy) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/cqn5-muyy/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/cqn5-muyy/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | cqn5-muyy |
| Name | SFMTA-Enforced Temporary Tow Zones |
| Attribution | San Francisco Metropolitan Transportation Agency |
| Category | Transportation |
| Tags | parking, tow zones |
| Created | 2014-04-28T21:49:10Z |
| Publication Date | 2017-01-13T20:45:25Z |

## Description

Temporary tow away zones in San Francisco granted by permit from the SFMTA or Department of Public Works. These zones have signs posted minimum of 72 hours prior to enforcement.

## Columns

```ls
| Included | Schema Type    | Field Name             | Name                   | Data Type     | Render Type   |
| ======== | ============== | ====================== | ====================== | ============= | ============= |
| Yes      | series tag     | mta_service_request    | MTA_Service_Request    | text          | text          |
| No       |                | fromaddress            | FromAddress            | number        | text          |
| No       |                | toaddress              | ToAddress              | text          | text          |
| Yes      | series tag     | streetname             | StreetName             | text          | text          |
| Yes      | series tag     | frontage               | Frontage               | text          | text          |
| Yes      | series tag     | starting_meter_number  | starting_meter_number  | text          | number        |
| Yes      | series tag     | ending_meter_number    | ending_meter_number    | text          | number        |
| Yes      | time           | starting_date          | starting_date          | calendar_date | calendar_date |
| No       |                | ending_date            | ending_date            | calendar_date | calendar_date |
| Yes      | series tag     | days                   | Days                   | text          | text          |
| Yes      | series tag     | recurrence_pattern     | recurrence_pattern     | text          | text          |
| Yes      | series tag     | starttime              | starttime              | text          | text          |
| Yes      | series tag     | endtime                | endtime                | text          | text          |
| Yes      | series tag     | hoursfromdpw           | HoursFromDPW           | text          | text          |
| Yes      | series tag     | frequencycode          | FrequencyCode          | text          | text          |
| Yes      | series tag     | allday                 | AllDay                 | text          | text          |
| Yes      | series tag     | mta_status_code        | MTA_Status_Code        | text          | text          |
| Yes      | series tag     | agency                 | Agency                 | text          | text          |
| Yes      | series tag     | vehicle_code_section   | Vehicle_Code_Section   | text          | text          |
| Yes      | series tag     | renewal                | Renewal                | text          | text          |
| Yes      | series tag     | related_dpw_permit     | Related_DPW_Permit     | text          | text          |
| Yes      | series tag     | dpw_receipt_number     | DPW_Receipt_Number     | text          | text          |
| Yes      | series tag     | dbi_receipt_number     | DBI_Receipt_Number     | text          | text          |
| Yes      | series tag     | dbi_application_number | DBI_Application_Number | text          | text          |
| Yes      | series tag     | bsm_permit_number      | BSM_Permit_Number      | text          | text          |
| Yes      | numeric metric | signcount              | SignCount              | number        | number        |
| Yes      | series tag     | category_code          | Category_Code          | text          | text          |
| Yes      | series tag     | notes                  | Notes                  | text          | text          |
| Yes      | series tag     | specialcondition       | SpecialCondition       | text          | text          |
| No       |                | createdat              | CreatedAt              | calendar_date | calendar_date |
| No       |                | updatedat              | UpdatedAt              | calendar_date | calendar_date |
```

## Time Field

```ls
Value = starting_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = fromaddress,toaddress,ending_date,createdat,updatedat
```

## Data Commands

```ls
```

## Meta Commands

```ls
metric m:signcount p:long l:SignCount t:dataTypeName=number

entity e:cqn5-muyy l:"SFMTA-Enforced Temporary Tow Zones" t:attribution="San Francisco Metropolitan Transportation Agency" t:url=https://data.sfgov.org/api/views/cqn5-muyy

property e:cqn5-muyy t:meta.view v:id=cqn5-muyy v:category=Transportation v:attributionLink=http://www.sfmta.com v:averageRating=0 v:name="SFMTA-Enforced Temporary Tow Zones" v:attribution="San Francisco Metropolitan Transportation Agency"

property e:cqn5-muyy t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:cqn5-muyy t:meta.view.owner v:id=jb2b-5ckh v:profileImageUrlMedium=/api/users/jb2b-5ckh/profile_images/THUMB v:profileImageUrlLarge=/api/users/jb2b-5ckh/profile_images/LARGE v:screenName=sfmtaData v:profileImageUrlSmall=/api/users/jb2b-5ckh/profile_images/TINY v:displayName=sfmtaData

property e:cqn5-muyy t:meta.view.tableauthor v:id=jb2b-5ckh v:profileImageUrlMedium=/api/users/jb2b-5ckh/profile_images/THUMB v:profileImageUrlLarge=/api/users/jb2b-5ckh/profile_images/LARGE v:screenName=sfmtaData v:profileImageUrlSmall=/api/users/jb2b-5ckh/profile_images/TINY v:roleName=editor v:displayName=sfmtaData
```

## Top Records

```ls
| mta_service_request | fromaddress | toaddress       | streetname                     | frontage | starting_meter_number | ending_meter_number | starting_date       | ending_date | days    | recurrence_pattern | starttime | endtime                | hoursfromdpw | frequencycode | allday   | mta_status_code | agency | vehicle_code_section | renewal | related_dpw_permit | dpw_receipt_number | dbi_receipt_number | dbi_application_number | bsm_permit_number | signcount | category_code | notes | specialcondition                                                                                                                                                                                                                                                                                                                                                                                                              | createdat           | updatedat           | 
| =================== | =========== | =============== | ============================== | ======== | ===================== | =================== | =================== | =========== | ======= | ================== | ========= | ====================== | ============ | ============= | ======== | =============== | ====== | ==================== | ======= | ================== | ================== | ================== | ====================== | ================= | ========= | ============= | ===== | ============================================================================================================================================================================================================================================================================================================================================================================================================================= | =================== | =================== | 
| SR00099037          | 1040        | Baker Street    | NULL                           | NULL     |                       |                     | 2019-02-12T00:00:00 |             | 1111100 | 7:00               | 19:00     | 7am-7pm mon-fri        | Daily        | 0             | Approved | DPW             | 33.1   | NULL                 | NULL    | 1174320            | 1174320            | 200812118317       |                        | NULL              |           | NULL          |       | Re-roofing                                                                                                                                                                                                                                                                                                                                                                                                                    | 2013-09-18T04:20:19 | 2013-09-18T04:20:19 | 
| SR00099052          | 3456        | Jackson Street  | NULL                           | NULL     |                       |                     | 3011-12-30T00:00:00 |             | 1111100 | 7:00               | 17:00     | 7am-5pm m-f            | Daily        | 0             | Approved | DPW             | 33.1   | NULL                 | NULL    | 1250039            | 1250039            | M284787            |                        | NULL              |           | NULL          |       | Street space permit.                                                                                                                                                                                                                                                                                                                                                                                                          | 2013-09-18T04:20:20 | 2013-09-18T04:20:20 | 
| SR00120235          | 3264        | 20th Street     | 20th Street 375 feet Even Side |          |                       |                     | 2017-05-31T00:00:00 |             | 0000010 | 6:00               | 14:00     |                        | Daily        | 0             | Approved | MTA             | 33.1   | 0                    |         |                    |                    |                    |                        | 0                 |           |               |       | Transferred 311 Data
311 id
3638231
contractor
san francisco department of public works
contact name
jerad weiner
phone
4155956933
email
jerad.weiner@sfdpw.org
email2
jerad.weiner@sfdpw.org
location
3264
street
20th street
side of street
even
linear feet
375
dates
05/31/2014 - 05/31/2017
times
06:00 am - 02:00 pm
weekdays
sat
contact street num
2323
contact city
san francisco
contact state
ca
contact zip
94124 | 2014-05-13T19:30:09 | 2014-05-13T20:52:12 | 
| SR00148992          | 3303        | Folsom Street   | NULL                           |          |                       |                     | 2025-10-24T00:00:00 |             | 1111110 | 7:00               | 18:00     | 7AM - 6PM Mon - Sat    | Daily        | 0             | Approved | DPW             | 33.1   | 0                    |         | 1331351            | 1331351            | 201403211414       | NULL                   | 0                 |           |               |       | Convert 2 extg floors to habitable. Lower floor at story 2. Repair extg decks.                                                                                                                                                                                                                                                                                                                                                | 2015-04-22T15:00:19 | 2015-04-22T15:00:19 | 
| SR00171249          | 1601        | Castro Street   | Clipper Street 40 feet Side    |          |                       |                     | 2018-02-16T00:00:00 |             | 1111110 | 7:00               | 18:00     | 7AM 6PM Mon - Sat      | Daily        | 0             | Approved | DPW             | 33.1   | 0                    |         | M637607            | NULL               | NULL               | M637607                | 0                 |           |               |       |                                                                                                                                                                                                                                                                                                                                                                                                                               | 2015-11-18T16:00:21 | 2015-11-18T16:00:21 | 
| SR00188309          | 881         | Lombard Street  | Lombard Street 27 feet Side    |          |                       |                     | 3016-07-03T00:00:00 |             | 1111110 | 7:00               | 18:00     | 7AM - 6PM Mon - Sat    | Daily        | 0             | Approved | DPW             | 33.1   | 0                    |         | m692667            | NULL               | NULL               | m692667                | 0                 |           |               |       |                                                                                                                                                                                                                                                                                                                                                                                                                               | 2016-05-22T15:00:23 | 2016-05-22T15:00:23 | 
| SR00200894          | 368         | Prentiss Street | Prentiss Street 24 feet Side   |          |                       |                     | 2017-04-03T00:00:00 |             | 1111110 | 7:00               | 17:30     | 7AM - 5:30PM Mon - Sat | Daily        | 0             | Approved | DPW             | 33.1   | 0                    |         | 201004281288       | NULL               | NULL               | 201004281288           | 0                 |           |               |       |                                                                                                                                                                                                                                                                                                                                                                                                                               | 2016-09-17T15:00:15 | 2016-09-17T15:00:15 | 
| SR00200895          | 2104        | Bryant Street   | Bryant Street 25 feet Side     |          |                       |                     | 2017-01-26T00:00:00 |             | 1111110 | 7:00               | 18:00     | 7AM - 6PM Mon - Sat    | Daily        | 0             | Approved | DPW             | 33.1   | 0                    |         | 201501206158       | NULL               | NULL               | 201501206158           | 0                 |           |               |       |                                                                                                                                                                                                                                                                                                                                                                                                                               | 2016-09-17T15:00:15 | 2016-09-17T15:00:15 | 
| SR00200905          | 1035        | Folsom Street   | Folsom Street 110 feet Side    |          |                       |                     | 2017-03-19T00:00:00 |             | 1111111 | 2:00               | 16:00     | 24 hours Mon - Sun     | Daily        | 0             | Approved | DPW             | 33.1   | 0                    |         | m715707            | NULL               | NULL               | m715707                | 0                 |           |               |       |                                                                                                                                                                                                                                                                                                                                                                                                                               | 2016-09-17T15:00:16 | 2016-09-17T15:00:16 | 
| SR00200906          | 1035        | Folsom Street   | Harriet Street 70 feet Side    |          |                       |                     | 2017-03-19T00:00:00 |             | 1111111 | 2:00               | 16:00     | 24 hours Mon - Sun     | Daily        | 0             | Approved | DPW             | 33.1   | 0                    |         | m715707            | NULL               | NULL               | m715707                | 0                 |           |               |       |                                                                                                                                                                                                                                                                                                                                                                                                                               | 2016-09-17T15:00:16 | 2016-09-17T15:00:16 | 
```