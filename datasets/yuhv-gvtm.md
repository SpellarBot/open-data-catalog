# COS-Statistics-Top5000-Pages

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/city-of-seattle-webstats-most-popular-pages-62e24) |
| Metadata | [Link](https://data.seattle.gov/api/views/yuhv-gvtm) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/yuhv-gvtm/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/yuhv-gvtm/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | yuhv-gvtm |
| Name | COS-Statistics-Top5000-Pages |
| Attribution | City of Seattle |
| Category | City Business |
| Tags | google, webstats, nre, census-okfn, 5000 |
| Created | 2015-07-20T21:11:18Z |
| Publication Date | 2015-07-20T21:13:32Z |

## Description

Top 5000 seattle.gov web pages accessed by month via Google Analytics. yuhv-gvtm

## Columns

```ls
| Included | Schema Type    | Field Name      | Name            | Data Type     | Render Type   |
| ======== | ============== | =============== | =============== | ============= | ============= |
| Yes      | series tag     | page            | Page            | text          | text          |
| Yes      | numeric metric | pageviews       | Pageviews       | number        | number        |
| Yes      | numeric metric | uniquepageviews | UniquePageviews | number        | number        |
| Yes      | series tag     | avgtimeonpage   | AvgTimeonPage   | text          | text          |
| Yes      | numeric metric | entrances       | Entrances       | number        | number        |
| Yes      | numeric metric | bouncerate      | BounceRate      | percent       | percent       |
| Yes      | numeric metric | percentexit     | PercentExit     | percent       | percent       |
| Yes      | time           | month           | Month           | calendar_date | calendar_date |
```

## Time Field

```ls
Value = month
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:yuhv-gvtm d:2015-02-01T00:00:00.000Z t:page=www.seattle.gov/fleets t:avgtimeonpage=0:01:39 m:entrances=18 m:percentexit=27.47 m:bouncerate=44.44 m:pageviews=91 m:uniquepageviews=73

series e:yuhv-gvtm d:2015-04-01T00:00:00.000Z t:page=www.seattle.gov/lgbt t:avgtimeonpage=0:01:35 m:entrances=240 m:percentexit=54.26 m:bouncerate=63.33 m:pageviews=352 m:uniquepageviews=302

series e:yuhv-gvtm d:2015-09-01T00:00:00.000Z t:page=www.seattle.gov/utilities t:avgtimeonpage=0:00:23 m:entrances=70 m:percentexit=18 m:bouncerate=14.29 m:pageviews=100 m:uniquepageviews=90
```

## Meta Commands

```ls
metric m:pageviews p:integer l:Pageviews t:dataTypeName=number

metric m:uniquepageviews p:integer l:UniquePageviews t:dataTypeName=number

metric m:entrances p:integer l:Entrances t:dataTypeName=number

metric m:bouncerate p:double l:BounceRate t:dataTypeName=percent

metric m:percentexit p:double l:PercentExit t:dataTypeName=percent

entity e:yuhv-gvtm l:COS-Statistics-Top5000-Pages t:attribution="City of Seattle" t:url=https://data.seattle.gov/api/views/yuhv-gvtm

property e:yuhv-gvtm t:meta.view v:id=yuhv-gvtm v:category="City Business" v:attributionLink=http://www.seattle.gov/ v:averageRating=0 v:name=COS-Statistics-Top5000-Pages v:attribution="City of Seattle"

property e:yuhv-gvtm t:meta.view.license v:name="Public Domain"

property e:yuhv-gvtm t:meta.view.owner v:id=seg8-ihrf v:profileImageUrlMedium=/api/users/seg8-ihrf/profile_images/THUMB v:profileImageUrlLarge=/api/users/seg8-ihrf/profile_images/LARGE v:screenName="Eckstine, Nate" v:profileImageUrlSmall=/api/users/seg8-ihrf/profile_images/TINY v:displayName="Eckstine, Nate"

property e:yuhv-gvtm t:meta.view.tableauthor v:id=seg8-ihrf v:profileImageUrlMedium=/api/users/seg8-ihrf/profile_images/THUMB v:profileImageUrlLarge=/api/users/seg8-ihrf/profile_images/LARGE v:screenName="Eckstine, Nate" v:profileImageUrlSmall=/api/users/seg8-ihrf/profile_images/TINY v:roleName=administrator v:displayName="Eckstine, Nate"
```

## Top Records

```ls
| page                                                                                                                        | pageviews | uniquepageviews | avgtimeonpage | entrances | bouncerate | percentexit | month               | 
| =========================================================================================================================== | ========= | =============== | ============= | ========= | ========== | =========== | =================== | 
| www.seattle.gov/fleets                                                                                                      | 91        | 73              | 0:01:39       | 18        | 44.44      | 27.47       | 2015-02-01T00:00:00 | 
| www.seattle.gov/lgbt                                                                                                        | 352       | 302             | 0:01:35       | 240       | 63.33      | 54.26       | 2015-04-01T00:00:00 | 
| www.seattle.gov/utilities                                                                                                   | 100       | 90              | 0:00:23       | 70        | 14.29      | 18          | 2015-09-01T00:00:00 | 
| www2.seattle.gov/fire/realtime911/getrecsfordatepub.asp?action=today&incdate=03/31/2015&rad1=des                            | 100       | 52              | 0:04:01       | 52        | 50         | 52          | 2015-09-01T00:00:00 | 
| alert.seattle.gov/2015/08/03/city-of-seattle-debuts-public-emergency-alert-and-notification-system-alertseattle/default.htm | 99        | 96              | 0:02:25       | 51        | 86.27      | 72.73       | 2015-09-01T00:00:00 | 
| parkways.seattle.gov/2015/09/08/im-a-park-and-rec-kid/default.htm                                                           | 99        | 87              | 0:02:41       | 58        | 79.31      | 67.68       | 2015-09-01T00:00:00 | 
| spdblotter.seattle.gov/2015/09/30/teens-arrested-for-attempted-burglary-on-beacon-hill/default.htm                          | 99        | 97              | 0:01:02       | 9         | 77.78      | 33.33       | 2015-09-01T00:00:00 | 
| web6.seattle.gov/dpd/luib/notice.aspx?bid=1064&nid=20417                                                                    | 99        | 81              | 0:01:17       | 34        | 76.47      | 41.41       | 2015-09-01T00:00:00 | 
| www.seattle.gov/business-regulations/taxis-for-hires-and-tncs/taxis/taxi-vehicle-owners                                     | 99        | 78              | 0:01:49       | 43        | 55.81      | 41.41       | 2015-09-01T00:00:00 | 
| www.seattle.gov/cityclerk/services-and-programs/accessibility-and-requests-for-accommodations                               | 99        | 83              | 0:03:46       | 56        | 78.57      | 63.64       | 2015-09-01T00:00:00 | 
```