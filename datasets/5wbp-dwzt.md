# Utility Excavation Moratorium Streets

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/utility-excavation-moratorium-streets-ea35c) |
| Metadata | [Link](https://data.sfgov.org/api/views/5wbp-dwzt) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/5wbp-dwzt/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/5wbp-dwzt/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | 5wbp-dwzt |
| Name | Utility Excavation Moratorium Streets |
| Attribution | Department of Public Works |
| Category | City Infrastructure |
| Tags | excavation, paving, moratorium, permits, utilities, 5, five, year, plan |
| Created | 2012-08-03T22:54:14Z |
| Publication Date | 2015-07-17T15:31:24Z |

## Description

Street segments and intersections that have been paved within the last 5 years

## Columns

```ls
| Included | Schema Type    | Field Name     | Name           | Data Type     | Render Type   |
| ======== | ============== | ============== | ============== | ============= | ============= |
| Yes      | numeric metric | cnn            | CNN            | number        | number        |
| Yes      | series tag     | streetname     | Streetname     | text          | text          |
| Yes      | series tag     | limits         | Limits         | text          | text          |
| Yes      | series tag     | jobordernum    | JobOrderNum    | text          | text          |
| Yes      | time           | effectivedate  | EffectiveDate  | calendar_date | calendar_date |
| No       |                | expirationdate | ExpirationDate | calendar_date | calendar_date |
| No       |                | modifieddate   | ModifiedDate   | calendar_date | calendar_date |
| No       |                | id             | ID             | text          | number        |
| No       |                | x              | X              | number        | number        |
| No       |                | y              | Y              | number        | number        |
| No       |                | latitude       | Latitude       | number        | number        |
| No       |                | longitude      | Longitude      | number        | number        |
```

## Time Field

```ls
Value = effectivedate
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = expirationdate,modifieddate,id,x,y,latitude,longitude
```

## Data Commands

```ls
series e:5wbp-dwzt d:2016-07-27T00:00:00.000Z t:limits="BALBOA ST to CABRILLO ST (600 - 699)" t:jobordernum=2833J t:streetname="03RD AVE" m:cnn=157000

series e:5wbp-dwzt d:2016-06-23T00:00:00.000Z t:limits="END to LAKE ST (1 - 99)" t:streetname="05TH AVE" m:cnn=275000

series e:5wbp-dwzt d:2012-07-07T00:00:00.000Z t:limits="PARNASSUS AVE intersection" t:jobordernum=1747J t:streetname="03RD AVE" m:cnn=27065000
```

## Meta Commands

```ls
metric m:cnn p:integer l:CNN t:dataTypeName=number

entity e:5wbp-dwzt l:"Utility Excavation Moratorium Streets" t:attribution="Department of Public Works" t:url=https://data.sfgov.org/api/views/5wbp-dwzt

property e:5wbp-dwzt t:meta.view v:id=5wbp-dwzt v:category="City Infrastructure" v:attributionLink=http://www.sfdpw.org v:averageRating=0 v:name="Utility Excavation Moratorium Streets" v:attribution="Department of Public Works"

property e:5wbp-dwzt t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:5wbp-dwzt t:meta.view.owner v:id=rcpp-nrjq v:profileImageUrlMedium=/api/users/rcpp-nrjq/profile_images/THUMB v:profileImageUrlLarge=/api/users/rcpp-nrjq/profile_images/LARGE v:screenName="Public Works" v:profileImageUrlSmall=/api/users/rcpp-nrjq/profile_images/TINY v:displayName="Public Works"

property e:5wbp-dwzt t:meta.view.tableauthor v:id=rcpp-nrjq v:profileImageUrlMedium=/api/users/rcpp-nrjq/profile_images/THUMB v:profileImageUrlLarge=/api/users/rcpp-nrjq/profile_images/LARGE v:screenName="Public Works" v:profileImageUrlSmall=/api/users/rcpp-nrjq/profile_images/TINY v:roleName=editor v:displayName="Public Works"
```

## Top Records

```ls
| cnn      | streetname | limits                                   | jobordernum | effectivedate       | expirationdate      | modifieddate        | id   | x             | y             | latitude         | longitude         | 
| ======== | ========== | ======================================== | =========== | =================== | =================== | =================== | ==== | ============= | ============= | ================ | ================= | 
| 157000   | 03RD AVE   | BALBOA ST to CABRILLO ST (600 - 699)     | 2833J       | 2016-07-27T00:00:00 | 2021-07-27T00:00:00 | 2016-12-05T14:03:13 | 112  | 5995026.62547 | 2111120.55312 | 37.7764486209873 | -122.460728551404 | 
| 275000   | 05TH AVE   | END to LAKE ST (1 - 99)                  |             | 2016-06-23T00:00:00 | 2021-06-23T00:00:00 | 1979-08-01T00:00:00 | 476  | 5994257.22822 | 2115235.44592 | 37.787702708882  | -122.463688818947 | 
| 27065000 | 03RD AVE   | PARNASSUS AVE intersection               | 1747J       | 2012-07-07T00:00:00 | 2017-07-07T00:00:00 | 2012-07-16T10:53:41 | 124  | 5995194.60884 | 2106192.05727 | 37.7629259242275 | -122.459790374397 | 
| 457000   | 09TH ST    | HARRISON ST to MCLEA CT (400 - 465)      | 1784J       | 2015-03-02T00:00:00 | 2020-03-02T00:00:00 | 2015-05-25T15:49:50 | 877  | 6009774.11546 | 2109242.45468 | 37.7721292628554 | -122.409579994605 | 
| 30739000 | 05TH ST    | CYRIL MAGNIN ST \ MARKET ST intersection | 1975J       | 2013-07-13T00:00:00 | 2018-07-13T00:00:00 | 2015-05-30T12:25:28 | 505  | 6010299.51804 | 2113551.92032 | 37.7839914732389 | -122.408066547307 | 
| 412000   | 08TH ST    | FOLSOM ST to RINGOLD ST (300 - 341)      | 1678J       | 2012-05-04T00:00:00 | 2017-05-04T00:00:00 | 2012-05-21T10:04:26 | 767  | 6009732.73441 | 2110205.76361 | 37.7747719659134 | -122.409791144914 | 
| 614000   | 15TH AVE   | IRVING ST to JUDAH ST (1300 - 1399)      | 2506J       | 2014-07-17T00:00:00 | 2019-07-17T00:00:00 | 2014-07-22T14:47:27 | 1309 | 5991455.75685 | 2106232.57596 | 37.7628214556191 | -122.472724598425 | 
| 27272000 | 07TH AVE   | FULTON ST intersection                   | 1932J       | 2013-12-04T00:00:00 | 2018-12-04T00:00:00 | 2013-12-17T08:36:37 | 646  | 5993824.1734  | 2110067.77998 | 37.7734887305936 | -122.464811670267 | 
| 27449000 | 15TH AVE   | FULTON ST intersection                   | 1932J       | 2013-09-26T00:00:00 | 2018-09-26T00:00:00 | 2013-09-27T08:36:06 | 1305 | 5991331.14574 | 2109965.04589 | 37.7730625999265 | -122.473427836341 | 
| 675000   | 16TH AVE   | BALBOA ST to CABRILLO ST (600 - 699)     | 2090J       | 2014-07-03T00:00:00 | 2019-07-03T00:00:00 | 2014-07-11T07:34:14 | 1446 | 5990969.11769 | 2110972.9503  | 37.7758090594075 | -122.474753702902 | 
```