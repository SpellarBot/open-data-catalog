# Roadway Construction Moratoriums

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/roadway-construction-moratoriums-500c5) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/ndbz-vy4e) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/ndbz-vy4e/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/ndbz-vy4e/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | ndbz-vy4e |
| Name | Roadway Construction Moratoriums |
| Attribution | City of Chicago |
| Category | Transportation |
| Tags | streets, permits, moratoriums |
| Created | 2014-08-25T22:08:47Z |
| Publication Date | 2015-11-13T22:00:05Z |

## Description

Moratoriums are established by the Department of Transportation as a method of protecting reconstructed or repaved roadways within the boundaries of the city.

By having access to this Moratorium list in advance, contractors or utilities with projects that require excavation of roadways can more effectively plan and review conflicts that will be encountered. Currently, roadway sections with active moratoriums have special consideration as to method and size of restoration, and additionally, increased permit fees. Three moratorium types are displayed on this web site: (1) Street Construction is used when the street has been reconstructed. By City ordinance, the moratorium is ten (10) years and during this period permit fees are doubled. (2) Street Resurfacing is used when the road has been repaved. By City ordinance, the moratorium is seven (7) years and during this period permit fees are doubled. (3) Median or Median Landscaping is used where landscaped medians or planters exist on the street median. For these moratoriums types, there is no fee adjustment; however, if a construction permit is being requested, the applicant will be directed to review the planned project with the Department of Transportation/Division of Engineering staff for special instructions on how to properly protect or reconstruct street medians.

## Columns

```ls
| Included | Schema Type | Field Name            | Name                  | Data Type     | Render Type   |
| ======== | =========== | ===================== | ===================== | ============= | ============= |
| Yes      | series tag  | moratorium_type       | MORATORIUM TYPE       | text          | text          |
| Yes      | series tag  | street_address_begin  | STREET ADDRESS BEGIN  | text          | number        |
| Yes      | series tag  | street_address_end    | STREET ADDRESS END    | text          | number        |
| Yes      | series tag  | street_address_prefix | STREET ADDRESS PREFIX | text          | text          |
| Yes      | series tag  | street_name           | STREET NAME           | text          | text          |
| Yes      | series tag  | street_name_suffix    | STREET NAME SUFFIX    | text          | text          |
| Yes      | time        | start_date            | START DATE            | calendar_date | calendar_date |
| No       |             | expiration_date       | EXPIRATION DATE       | calendar_date | calendar_date |
```

## Time Field

```ls
Value = start_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = expiration_date
```

## Data Commands

```ls
series e:ndbz-vy4e d:2014-09-03T00:00:00.000Z t:street_address_end=2359 t:street_address_begin=2000 t:street_name=ARMITAGE t:street_name_suffix=AVE t:street_address_prefix=W t:moratorium_type="Street Resurfacing" m:row_number.ndbz-vy4e=1

series e:ndbz-vy4e d:2015-08-12T00:00:00.000Z t:street_address_end=6459 t:street_address_begin=6400 t:street_name=LAFLIN t:street_name_suffix=ST t:street_address_prefix=S t:moratorium_type="Street Resurfacing" m:row_number.ndbz-vy4e=2

series e:ndbz-vy4e d:2014-05-20T00:00:00.000Z t:street_address_end=3159 t:street_address_begin=3032 t:street_name=WAVELAND t:street_name_suffix=AVE t:street_address_prefix=W t:moratorium_type="Street Resurfacing" m:row_number.ndbz-vy4e=3
```

## Meta Commands

```ls
metric m:row_number.ndbz-vy4e p:long l:"Row Number"

entity e:ndbz-vy4e l:"Roadway Construction Moratoriums" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/ndbz-vy4e

property e:ndbz-vy4e t:meta.view v:id=ndbz-vy4e v:category=Transportation v:attributionLink=http://www.cityofchicago.org v:averageRating=0 v:name="Roadway Construction Moratoriums" v:attribution="City of Chicago"

property e:ndbz-vy4e t:meta.view.owner v:id=3qqc-w7ag v:profileImageUrlMedium=/api/users/3qqc-w7ag/profile_images/THUMB v:profileImageUrlLarge=/api/users/3qqc-w7ag/profile_images/LARGE v:screenName="Tom Schenk Jr" v:profileImageUrlSmall=/api/users/3qqc-w7ag/profile_images/TINY v:lastNotificationSeenAt=1491330280 v:displayName="Tom Schenk Jr"

property e:ndbz-vy4e t:meta.view.tableauthor v:id=3qqc-w7ag v:profileImageUrlMedium=/api/users/3qqc-w7ag/profile_images/THUMB v:profileImageUrlLarge=/api/users/3qqc-w7ag/profile_images/LARGE v:screenName="Tom Schenk Jr" v:profileImageUrlSmall=/api/users/3qqc-w7ag/profile_images/TINY v:roleName=administrator v:lastNotificationSeenAt=1491330280 v:displayName="Tom Schenk Jr"
```

## Top Records

```ls
| moratorium_type     | street_address_begin | street_address_end | street_address_prefix | street_name | street_name_suffix | start_date          | expiration_date     | 
| =================== | ==================== | ================== | ===================== | =========== | ================== | =================== | =================== | 
| Street Resurfacing  | 2000                 | 2359               | W                     | ARMITAGE    | AVE                | 2014-09-03T00:00:00 | 2019-09-02T00:00:00 | 
| Street Resurfacing  | 6400                 | 6459               | S                     | LAFLIN      | ST                 | 2015-08-12T00:00:00 | 2020-08-12T00:00:00 | 
| Street Resurfacing  | 3032                 | 3159               | W                     | WAVELAND    | AVE                | 2014-05-20T00:00:00 | 2019-05-20T00:00:00 | 
| Street Resurfacing  | 432                  | 627                | E                     | 65TH        | ST                 | 2013-09-13T00:00:00 | 2018-09-13T00:00:00 | 
| Street Resurfacing  | 3000                 | 3125               | N                     | HAUSSEN     | CT                 | 2011-08-18T00:00:00 | 2017-12-02T00:00:00 | 
| Street Construction | 3426                 | 3525               | E                     | 107TH       | ST                 | 2015-01-27T00:00:00 | 2024-08-12T00:00:00 | 
| Street Resurfacing  | 801                  | 1157               | N                     | KEDVALE     | AVE                | 2015-10-07T00:00:00 | 2020-10-07T00:00:00 | 
| Street Resurfacing  | 4300                 | 5500               | S                     | MICHIGAN    | AVE                | 2012-10-05T00:00:00 | 2017-10-05T00:00:00 | 
| Street Resurfacing  | 1134                 | 1258               | W                     | 81ST        | ST                 | 2014-12-22T00:00:00 | 2019-12-22T00:00:00 | 
| Street Resurfacing  | 6301                 | 6459               | S                     | VERNON      | AVE                | 2013-06-28T00:00:00 | 2018-05-10T00:00:00 | 
```