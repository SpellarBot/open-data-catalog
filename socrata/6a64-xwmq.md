# King County 2012 events

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/king-county-2012-events-ba1b5) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/6a64-xwmq) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/6a64-xwmq/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/6a64-xwmq/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | 6a64-xwmq |
| Name | King County 2012 events |
| Attribution | King County Executive |
| Category | Operations |
| Tags | news, executive |
| Created | 2012-12-19T19:12:31Z |
| Publication Date | 2013-02-15T00:09:57Z |

## Description

Newsworthy King County events over the last year

## Columns

```ls
| Included | Schema Type | Field Name | Name       | Data Type     | Render Type   |
| ======== | =========== | ========== | ========== | ============= | ============= |
| Yes      | series tag  | label      | Label      | text          | text          |
| Yes      | time        | start_time | Start Date | calendar_date | calendar_date |
| Yes      | series tag  | link       | link       | url           | url           |
| Yes      | series tag  | notes      | Notes      | text          | text          |
| Yes      | series tag  | image_2    | Image      | photo         | photo         |
| Yes      | series tag  | movie      | Movie      | url           | url           |
| Yes      | series tag  | tags       | Tags       | text          | text          |
| Yes      | series tag  | image      | Image-temp | url           | url           |
```

## Time Field

```ls
Value = start_time
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:6a64-xwmq d:2012-04-05T00:00:00.000Z t:link=http://www.kingcounty.gov/exec/news/release/2012/April/05MuniLeague.aspx t:label="Executive thanks Municipal League of King County for regional leadership award" t:notes="King County Executive Dow Constantine tonight accepted the 2012 James R. Ellis Regional Leadership Award, at the 53rd Annual Civic Awards Celebration Dinner at Herban Feast in the SODO area of Seattle." m:row_number.6a64-xwmq=1

series e:6a64-xwmq d:2012-04-11T00:00:00.000Z t:link=http://www.kingcounty.gov/exec/news/release/2012/April/11SchoolSitingTaskForce.aspx t:label="Regional task force resolves long-standing dispute over school siting" t:notes="A 30-member task force representing a broad coalition of stakeholders from throughout the region has unanimously agreed on key recommendations for school siting in King County that call for future schools to be sited in urban areas and rural towns, rather than in areas designated as rural." m:row_number.6a64-xwmq=2

series e:6a64-xwmq d:2012-07-24T00:00:00.000Z t:link=http://www.kingcounty.gov/exec/news/release/2012/July/23_partnerships.aspx t:label="Executive and Mayor announce innovative partnership for rural protections and urban densities" t:notes="King County Executive Dow Constantine and Seattle Mayor Mike McGinn today proposed a new development incentive program that will invest millions of dollars in community infrastructure projects in the South Lake Union neighborhood, while preserving the working forests and farms that supply Seattle and its residents with fresh locally grown food." m:row_number.6a64-xwmq=3
```

## Meta Commands

```ls
metric m:row_number.6a64-xwmq p:long l:"Row Number"

entity e:6a64-xwmq l:"King County 2012 events" t:attribution="King County Executive" t:url=https://data.kingcounty.gov/api/views/6a64-xwmq

property e:6a64-xwmq t:meta.view v:id=6a64-xwmq v:category=Operations v:attributionLink=http://www.kingcounty.gov/exec/ v:averageRating=0 v:name="King County 2012 events" v:attribution="King County Executive"

property e:6a64-xwmq t:meta.view.license v:name="Public Domain"

property e:6a64-xwmq t:meta.view.owner v:id=7ja6-sv4x v:profileImageUrlMedium=/api/users/7ja6-sv4x/profile_images/THUMB v:profileImageUrlLarge=/api/users/7ja6-sv4x/profile_images/LARGE v:screenName="King County Open Data admin" v:profileImageUrlSmall=/api/users/7ja6-sv4x/profile_images/TINY v:lastNotificationSeenAt=1492197205 v:displayName="King County Open Data admin"

property e:6a64-xwmq t:meta.view.tableauthor v:id=7ja6-sv4x v:profileImageUrlMedium=/api/users/7ja6-sv4x/profile_images/THUMB v:profileImageUrlLarge=/api/users/7ja6-sv4x/profile_images/LARGE v:screenName="King County Open Data admin" v:profileImageUrlSmall=/api/users/7ja6-sv4x/profile_images/TINY v:roleName=administrator v:lastNotificationSeenAt=1492197205 v:displayName="King County Open Data admin"
```

## Top Records

```ls
| label                                                                                                     | start_time          | link                                                                                            | notes                                                                                                                                                                                                                                                                                                                                                      | image_2                                     | movie        | tags | image        | 
| ========================================================================================================= | =================== | =============================================================================================== | ========================================================================================================================================================================================================================================================================================================================================================== | =========================================== | ============ | ==== | ============ | 
| Executive thanks Municipal League of King County for regional leadership award                            | 2012-04-05T00:00:00 | [http://www.kingcounty.gov/exec/news/release/2012/April/05MuniLeague.aspx, null]                | King County Executive Dow Constantine tonight accepted the 2012 James R. Ellis Regional Leadership Award, at the 53rd Annual Civic Awards Celebration Dinner at Herban Feast in the SODO area of Seattle.                                                                                                                                                  |                                             | [null, null] |      | [null, null] | 
| Regional task force resolves long-standing dispute over school siting                                     | 2012-04-11T00:00:00 | [http://www.kingcounty.gov/exec/news/release/2012/April/11SchoolSitingTaskForce.aspx, null]     | A 30-member task force representing a broad coalition of stakeholders from throughout the region has unanimously agreed on key recommendations for school siting in King County that call for future schools to be sited in urban areas and rural towns, rather than in areas designated as rural.                                                         |                                             | [null, null] |      | [null, null] | 
| Executive and Mayor announce innovative partnership for rural protections and urban densities             | 2012-07-24T00:00:00 | [http://www.kingcounty.gov/exec/news/release/2012/July/23_partnerships.aspx, null]              | King County Executive Dow Constantine and Seattle Mayor Mike McGinn today proposed a new development incentive program that will invest millions of dollars in community infrastructure projects in the South Lake Union neighborhood, while preserving the working forests and farms that supply Seattle and its residents with fresh locally grown food. |                                             | [null, null] |      | [null, null] | 
| Executive congratulates King County Council for approving arena agreement                                 | 2012-07-30T00:00:00 | [http://www.kingcounty.gov/exec/news/release/2012/July/30stadium.aspx, null]                    | King County Executive Dow Constantine this afternoon thanked the Metropolitan King County Council for authorizing a memorandum of understanding with the city of Seattle and investor Chris Hansen for the proposed Sonics arena.                                                                                                                          |                                             | [null, null] |      | [null, null] | 
| King County Executive proposes partnership with Vashon Island Fire and Rescue on new rural service center | 2012-08-02T00:00:00 | [http://www.kingcounty.gov/exec/news/release/2012/August/02VashonRuralServiceCenter.aspx, null] | Facility with co-located services would open in downtown Vashon in spring 2013 if County Council agrees.                                                                                                                                                                                                                                                   |                                             | [null, null] |      | [null, null] | 
| King County launches regional Smart911 service                                                            | 2012-09-11T00:00:00 | [http://www.kingcounty.gov/exec/news/release/2012/September/11Smart911Launch.aspx, null]        | Voluntary, user-entered safety profiles can provide critical information to 9-1-1 centers and emergency responders when help is needed.                                                                                                                                                                                                                    |                                             | [null, null] |      | [null, null] | 
| High credit ratings lead to lower borrowing costs for King County                                         | 2012-09-18T00:00:00 | [http://www.kingcounty.gov/exec/news/release/2012/September/18TransitBondRefi.aspx, null]       | Bond refinancing for transit improvements will help save more than $15 million.                                                                                                                                                                                                                                                                            |                                             | [null, null] |      | [null, null] | 
| Testimony of King County Executive Dow Constantine on the proposed Cherry Point coal export terminal EIS  | 2012-12-13T00:00:00 | [http://www.kingcounty.gov/exec/news/release/2012/December/13CoalTrains.aspx, null]             | Testimony of King County Executive Dow Constantine on the proposed Cherry Point coal export terminal EIS.                                                                                                                                                                                                                                                  |                                             | [null, null] |      | [null, null] | 
| Report shows King County GIS delivered $775 million return on investment over past two decades            | 2012-04-05T00:00:00 | [http://www.kingcounty.gov/exec/news/release/2012/April/05GISroi.aspx, null]                    | King County's long-term use of its in-house Geographic Information System (GIS) has resulted in three quarters of a billion dollars in net benefits to the County, according to a first-of-its-kind report.                                                                                                                                                | AnVYrWsC4KhhbDSV9OlUxSUPIkf_NboNM4AsmENdvOI | [null, null] |      | [null, null] | 
| Executive proposes boundaries for seven new Community Service Areas for better engagement with residents  | 2012-07-19T00:00:00 | [http://www.kingcounty.gov/exec/news/release/2012/July/19-community-service-areas.aspx, null]   | King County Executive Dow Constantine today proposed the boundaries for seven new Community Service Areas that together cover all of unincorporated King County, as part of his reform measures to strengthen the access of residents to their County government.                                                                                          | WyaYqQi12OOrB5lBT59M2citjTt1MbPABUuagj9ol_4 | [null, null] |      | [null, null] | 
```