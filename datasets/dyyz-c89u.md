# Myrtle Edwards Park Temporary Bike Counter 5/10/2013 - 12/31/2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/myrtle-edwards-park-temporary-bike-counter-5-10-2013-12-31-2013-13501) |
| Metadata | [Link](https://data.seattle.gov/api/views/dyyz-c89u) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/dyyz-c89u/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/dyyz-c89u/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | dyyz-c89u |
| Name | Myrtle Edwards Park Temporary Bike Counter 5/10/2013 - 12/31/2013 |
| Category | Transportation |
| Tags | sdot, bicycle, elliott bay, myrtle edwards, seattle, bike counts |
| Created | 2013-07-16T22:12:04Z |
| Publication Date | 2014-01-03T16:26:54Z |

## Description

Monthly data set of our temporary bike counter on the Myrtle Edwards Park trail.

## Columns

```ls
| Included | Schema Type    | Field Name            | Name                  | Data Type     | Render Type   |
| ======== | ============== | ===================== | ===================== | ============= | ============= |
| Yes      | time           | date                  | Date                  | calendar_date | calendar_date |
| Yes      | numeric metric | myrtle_edwards_logger | Myrtle Edwards Logger | number        | number        |
| No       |                | nw                    | NW                    | number        | number        |
| No       |                | se                    | SE                    | number        | number        |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = nw,se
```

## Data Commands

```ls
series e:dyyz-c89u d:2013-05-10T11:00:00.000Z m:myrtle_edwards_logger=27

series e:dyyz-c89u d:2013-05-10T12:00:00.000Z m:myrtle_edwards_logger=86

series e:dyyz-c89u d:2013-05-10T13:00:00.000Z m:myrtle_edwards_logger=71
```

## Meta Commands

```ls
metric m:myrtle_edwards_logger p:integer l:"Myrtle Edwards Logger" t:dataTypeName=number

entity e:dyyz-c89u l:"Myrtle Edwards Park Temporary Bike Counter 5/10/2013 - 12/31/2013" t:url=https://data.seattle.gov/api/views/dyyz-c89u

property e:dyyz-c89u t:meta.view v:id=dyyz-c89u v:category=Transportation v:averageRating=0 v:name="Myrtle Edwards Park Temporary Bike Counter 5/10/2013 - 12/31/2013"

property e:dyyz-c89u t:meta.view.owner v:id=psms-jbhq v:profileImageUrlMedium=/api/users/psms-jbhq/profile_images/THUMB v:profileImageUrlLarge=/api/users/psms-jbhq/profile_images/LARGE v:screenName="Zuniga, Rafael" v:profileImageUrlSmall=/api/users/psms-jbhq/profile_images/TINY v:displayName="Zuniga, Rafael"

property e:dyyz-c89u t:meta.view.tableauthor v:id=psms-jbhq v:profileImageUrlMedium=/api/users/psms-jbhq/profile_images/THUMB v:profileImageUrlLarge=/api/users/psms-jbhq/profile_images/LARGE v:screenName="Zuniga, Rafael" v:profileImageUrlSmall=/api/users/psms-jbhq/profile_images/TINY v:roleName=publisher v:displayName="Zuniga, Rafael"
```

## Top Records

```ls
| date                | myrtle_edwards_logger | nw | se | 
| =================== | ===================== | == | == | 
| 2013-05-10T00:00:00 |                       |    |    | 
| 2013-05-10T01:00:00 |                       |    |    | 
| 2013-05-10T02:00:00 |                       |    |    | 
| 2013-05-10T03:00:00 |                       |    |    | 
| 2013-05-10T04:00:00 |                       |    |    | 
| 2013-05-10T05:00:00 |                       |    |    | 
| 2013-05-10T06:00:00 |                       |    |    | 
| 2013-05-10T07:00:00 |                       |    |    | 
| 2013-05-10T08:00:00 |                       |    |    | 
| 2013-05-10T09:00:00 |                       |    |    | 
```