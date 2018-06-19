# Projects Accepted

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/projects-accepted-b16cb) |
| Metadata | [Link](https://data.hawaii.gov/api/views/4apz-zc66) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/4apz-zc66/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/4apz-zc66/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | 4apz-zc66 |
| Name | Projects Accepted |
| Created | 2014-12-05T01:18:19Z |
| Publication Date | 2016-12-03T03:10:54Z |

## Columns

```ls
| Included | Schema Type    | Field Name         | Name             | Data Type     | Render Type   |
| ======== | ============== | ================== | ================ | ============= | ============= |
| Yes      | series tag     | job_no             | Job No           | text          | text          |
| Yes      | series tag     | description        | DESCRIPTION      | text          | text          |
| Yes      | time           | ntp                | NTP              | calendar_date | calendar_date |
| No       |                | project_acceptance | Acceptance       | calendar_date | calendar_date |
| No       |                | final_inspection   | Final Inspection | calendar_date | calendar_date |
| Yes      | numeric metric | amount             | Amount           | money         | money         |
```

## Time Field

```ls
Value = ntp
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = project_acceptance,final_inspection
```

## Data Commands

```ls
series e:4apz-zc66 d:2016-04-28T00:00:00.000Z t:description="ALOHA STADIUM - ATHLETIC FIELD SURFACE REPLACEMENT" t:job_no=22-10-0801 m:amount=1100706

series e:4apz-zc66 d:2014-12-15T00:00:00.000Z t:description="ALOHA STADIUM - HEALTH AND SAFETY IMPROVEMENTS, PHASE 3" t:job_no=12-10-0736 m:amount=12064418

series e:4apz-zc66 d:2012-05-07T00:00:00.000Z t:description="HAWAII CONVENTION CENTER - LOBBY WATER FEATURE REPAIRS AND IMPROVEMENTS" t:job_no=42-26-7452 m:amount=926490
```

## Meta Commands

```ls
metric m:amount p:integer l:Amount t:dataTypeName=money

entity e:4apz-zc66 l:"Projects Accepted" t:url=https://data.hawaii.gov/api/views/4apz-zc66

property e:4apz-zc66 t:meta.view v:id=4apz-zc66 v:averageRating=0 v:name="Projects Accepted"

property e:4apz-zc66 t:meta.view.owner v:id=ck4w-i5dk v:profileImageUrlMedium=/api/users/ck4w-i5dk/profile_images/THUMB v:profileImageUrlLarge=/api/users/ck4w-i5dk/profile_images/LARGE v:screenName=sojiri v:profileImageUrlSmall=/api/users/ck4w-i5dk/profile_images/TINY v:displayName=sojiri

property e:4apz-zc66 t:meta.view.tableauthor v:id=ck4w-i5dk v:profileImageUrlMedium=/api/users/ck4w-i5dk/profile_images/THUMB v:profileImageUrlLarge=/api/users/ck4w-i5dk/profile_images/LARGE v:screenName=sojiri v:profileImageUrlSmall=/api/users/ck4w-i5dk/profile_images/TINY v:roleName=publisher v:displayName=sojiri
```

## Top Records

```ls
| job_no     | description                                                                      | ntp                 | project_acceptance  | final_inspection    | amount   | 
| ========== | ================================================================================ | =================== | =================== | =================== | ======== | 
| 22-10-0801 | ALOHA STADIUM - ATHLETIC FIELD SURFACE REPLACEMENT                               | 2016-04-28T00:00:00 | 2016-08-05T00:00:00 | 2016-08-05T00:00:00 | 1100706  | 
| 12-10-0736 | ALOHA STADIUM - HEALTH AND SAFETY IMPROVEMENTS, PHASE 3                          | 2014-12-15T00:00:00 | 2016-08-05T00:00:00 | 2016-08-26T00:00:00 | 12064418 | 
| 42-26-7452 | HAWAII CONVENTION CENTER - LOBBY WATER FEATURE REPAIRS AND IMPROVEMENTS          | 2012-05-07T00:00:00 | 2013-07-25T00:00:00 | 2013-07-25T00:00:00 | 926490   | 
| 12-20-2664 | HAWAII STATE HOSPITAL - REPLACE HIGH VOLTAGE POLE & ELECTRICAL DISTRIBUTION PAN. | 2015-01-12T00:00:00 | 2016-07-15T00:00:00 | 2016-07-15T00:00:00 | 351900   | 
| 62-36-6533 | HAWAII STATE LIBRARY - FOUNDATION STABILIZATION AND FLOOR REPAIRS                | 2016-09-23T00:00:00 | 2016-11-23T00:00:00 | 2016-11-23T00:00:00 | 90000    | 
| 62-36-6517 | HAWAII STATE LIBRARY - REPLACE A/C CHILLERS                                      | 2012-09-19T00:00:00 | 2014-01-29T00:00:00 | 2014-01-22T00:00:00 | 598295   | 
| 12-20-2686 | KAMAULEULE BUILDING (DOH LABORATORY) - MISCELLANEOUS ROOF IMPROVEMENTS           | 2014-11-24T00:00:00 | 2016-01-05T00:00:00 | 2015-12-24T00:00:00 | 1712600  | 
| 22-21-7326 | KAUIKEAOULI HALE - UPGRADE AND MODERNIZE ELEVATORS                               | 2010-08-30T00:00:00 | 2015-10-24T00:00:00 | 2014-02-21T00:00:00 | 2187000  | 
| 12-33-7265 | LEEWARD HOMELESS SHELTERS - VOICE OF AMERICA SITE (VILLAGES OF MAILI)            | 2007-12-10T00:00:00 | 2009-04-17T00:00:00 | 2009-04-17T00:00:00 | 13074697 | 
| 12-10-0758 | STATE CAPITOL BUILDING - 5TH FLOOR EXTERIOR WALL REPLACEMENT & EXTERIOR REPAIRS  | 2015-05-18T00:00:00 | 2016-03-01T00:00:00 | 2016-03-01T00:00:00 | 4050980  | 
```