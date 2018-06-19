# Regional AFIS Program Community Events

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/regional-afis-program-community-events-62f29) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/vcj4-3vp9) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/vcj4-3vp9/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/vcj4-3vp9/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | vcj4-3vp9 |
| Name | Regional AFIS Program Community Events |
| Attribution | King County Regional AFIS |
| Category | Public Safety |
| Tags | afis, automated fingerprint identification system, fingerprint, palm print, calendar |
| Created | 2012-09-11T21:23:51Z |
| Publication Date | 2016-08-30T21:04:52Z |

## Description

Automated Fingerprint Identification System community events calendar

## Columns

```ls
| Included | Schema Type | Field Name       | Name              | Data Type | Render Type |
| ======== | =========== | ================ | ================= | ========= | =========== |
| Yes      | series tag  | event_title      | Event name        | text      | text        |
| Yes      | time        | start_time       | Start time        | date      | date        |
| No       |             | end_time         | End time          | date      | date        |
| Yes      | series tag  | meeting_facility | Location name     | text      | text        |
| No       |             | address          | Address           | text      | text        |
| Yes      | series tag  | city             | City              | text      | text        |
| Yes      | series tag  | state            | State             | text      | text        |
| Yes      | series tag  | zip              | Zip               | text      | text        |
| Yes      | series tag  | contact_name     | Contact Name      | text      | text        |
| Yes      | series tag  | phone_number     | Phone Number      | text      | text        |
| Yes      | series tag  | email            | Email             | email     | email       |
| Yes      | series tag  | details          | Event description | text      | text        |
| Yes      | series tag  | url              | URL               | url       | url         |
```

## Time Field

```ls
Value = start_time
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = end_time,address
```

## Data Commands

```ls
series e:vcj4-3vp9 d:2016-08-13T11:00:00.000Z t:meeting_facility="Delridge Community Center" t:zip=98106 t:phone_number=206-263-2723 t:email=judy.cordova@kingcounty.gov t:contact_name="Judy Cordova" t:state=WA t:event_title="Southwest Precinct Community Picnic" t:url=http://kingcounty.gov/depts/sheriff/about-us/enforcement/afis.aspx t:city=Seattle m:row_number.vcj4-3vp9=1

series e:vcj4-3vp9 d:2016-02-13T10:00:00.000Z t:meeting_facility="Washington State Criminal Justice Training Center" t:zip=98148 t:phone_number=206-263-2723 t:email=judy.cordova@kingcounty.gov t:contact_name="Judy Cordova" t:state=WA t:event_title="Women in Law Enforcement Fields Career Fair" t:url=http://kingcounty.gov/depts/sheriff/about-us/enforcement/afis.aspx t:city=Burien m:row_number.vcj4-3vp9=2

series e:vcj4-3vp9 d:2016-02-18T18:00:00.000Z t:meeting_facility="King County Courthouse, Room 1A-42" t:zip=98104 t:phone_number=206-263-2723 t:email=judy.cordova@kingcounty.gov t:contact_name="Judy Cordova" t:state=WA t:event_title="AFIS Presentation for SeaTac Explorers" t:url=http://kingcounty.gov/depts/sheriff/about-us/enforcement/afis.aspx t:city=Seattle m:row_number.vcj4-3vp9=3
```

## Meta Commands

```ls
metric m:row_number.vcj4-3vp9 p:long l:"Row Number"

entity e:vcj4-3vp9 l:"Regional AFIS Program Community Events" t:attribution="King County Regional AFIS" t:url=https://data.kingcounty.gov/api/views/vcj4-3vp9

property e:vcj4-3vp9 t:meta.view v:id=vcj4-3vp9 v:category="Public Safety" v:attributionLink=http://www.kingcounty.gov/afis v:averageRating=0 v:name="Regional AFIS Program Community Events" v:attribution="King County Regional AFIS"

property e:vcj4-3vp9 t:meta.view.license v:name="Public Domain"

property e:vcj4-3vp9 t:meta.view.owner v:id=frb9-ave3 v:screenName=Wilsonlk v:displayName=Wilsonlk

property e:vcj4-3vp9 t:meta.view.tableauthor v:id=frb9-ave3 v:screenName=Wilsonlk v:roleName=editor v:displayName=Wilsonlk
```

## Top Records

```ls
| event_title                                       | start_time | end_time   | meeting_facility                                  | address                               | city         | state | zip   | contact_name | phone_number | email                       | details | url                                                                        | 
| ================================================= | ========== | ========== | ================================================= | ===================================== | ============ | ===== | ===== | ============ | ============ | =========================== | ======= | ========================================================================== | 
| Southwest Precinct Community Picnic               | 1471086000 | 1471100400 | Delridge Community Center                         | 4501 Delridge Way SW                  | Seattle      | WA    | 98106 | Judy Cordova | 206-263-2723 | judy.cordova@kingcounty.gov |         | [http://kingcounty.gov/depts/sheriff/about-us/enforcement/afis.aspx, null] | 
| Women in Law Enforcement Fields Career Fair       | 1455357600 | 1455372000 | Washington State Criminal Justice Training Center | 19010 1st Avenue South                | Burien       | WA    | 98148 | Judy Cordova | 206-263-2723 | judy.cordova@kingcounty.gov |         | [http://kingcounty.gov/depts/sheriff/about-us/enforcement/afis.aspx, null] | 
| AFIS Presentation for SeaTac Explorers            | 1455818400 | 1455825600 | King County Courthouse, Room 1A-42                | 516 Third Avenue                      | Seattle      | WA    | 98104 | Judy Cordova | 206-263-2723 | judy.cordova@kingcounty.gov |         | [http://kingcounty.gov/depts/sheriff/about-us/enforcement/afis.aspx, null] | 
| Science on Patrol                                 | 1455116400 | 1455120900 | Cedar Heights Middle School                       | 19640 SE 272nd Street                 | Sammamish    | WA    | 98042 | Judy Cordova | 206-263-2723 | judy.cordova@kingcounty.gov |         | [http://kingcounty.gov/depts/sheriff/about-us/enforcement/afis.aspx, null] | 
| North Precinct Community Picnic                   | 1468062000 | 1468080000 | Ballard Commons Park                              | 5701 22nd Avenue NW                   | Ballard      | WA    | 98107 | Judy Cordova | 206-263-2723 | judy.cordova@kingcounty.gov |         | [http://kingcounty.gov/depts/sheriff/about-us/enforcement/afis.aspx, null] | 
| AFIS Presentation for North King County Explorers | 1459881000 | 1459888200 | King County Courthouse, Room 1A-42                | 516 Third Avenue                      | Seattle      | WA    | 98104 | Judy Cordova | 206-263-2723 | judy.cordova@kingcounty.gov |         | [http://kingcounty.gov/depts/sheriff/about-us/enforcement/afis.aspx, null] | 
| Maple Valley Citizens Academy                     | 1464285600 | 1464291000 | Lake Wilderness Lodge                             | 22500 SE 248th Street                 | Maple Valley | WA    | 98038 | Judy Cordova | 206-263-2723 | judy.cordova@kingcounty.gov |         | [http://kingcounty.gov/depts/sheriff/about-us/enforcement/afis.aspx, null] | 
| West Precinct Community Picnic/National Night Out | 1470157200 | 1470168000 | Occidental Square                                 | S Main Street and Occidental Avenue S | Seattle      | WA    | 98104 | Judy Cordova | 206-263-2723 | judy.cordova@kingcounty.gov |         | [http://kingcounty.gov/depts/sheriff/about-us/enforcement/afis.aspx, null] | 
| Fairwood 50th Anniversary                         | 1472302800 | 1472317200 | Ridgewood Elementary                              | 18030 162nd Pl SE                     | Renton       | WA    | 98058 | Judy Cordova | 206-263-2723 | judy.cordova@kingcounty.gov |         | [http://kingcounty.gov/depts/sheriff/about-us/enforcement/afis.aspx, null] | 
| East Precinct Community Picnic                    | 1468674000 | 1468684800 | 12th Avenue between Pike and Pine                 | 12th Avenue between Pike and Pine     | Seattle      | WA    | 98122 | Judy Cordova | 206-263-2723 | judy.cordova@kingcounty.gov |         | [http://kingcounty.gov/depts/sheriff/about-us/enforcement/afis.aspx, null] | 
```