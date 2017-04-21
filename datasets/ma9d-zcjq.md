# Projects Completed

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/projects-completed-fb271) |
| Metadata | [Link](https://data.hawaii.gov/api/views/ma9d-zcjq) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/ma9d-zcjq/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/ma9d-zcjq/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | ma9d-zcjq |
| Name | Projects Completed |
| Created | 2014-12-24T03:07:12Z |
| Publication Date | 2016-12-03T02:10:27Z |

## Columns

```ls
| Included | Schema Type    | Field Name  | Name        | Data Type     | Render Type   |
| ======== | ============== | =========== | =========== | ============= | ============= |
| Yes      | series tag     | job_no      | Job No      | text          | text          |
| Yes      | series tag     | description | DESCRIPTION | text          | text          |
| Yes      | time           | ntp         | NTP         | calendar_date | calendar_date |
| Yes      | numeric metric | amount      | Amount      | money         | money         |
| No       |                | completed   | Completed   | calendar_date | calendar_date |
```

## Time Field

```ls
Value = ntp
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = completed
```

## Data Commands

```ls
series e:ma9d-zcjq d:2004-03-29T00:00:00.000Z t:description="919 ALA MOANA BUILDING - RENOVATION OF ROOMS 110 AND 117 FOR PSD" t:job_no=12-10-0319 m:amount=58470

series e:ma9d-zcjq d:2004-11-01T00:00:00.000Z t:description="AGRICULTURE AND CONSERVATION FACILITY - REROOF BUILDINGS C AND D" t:job_no=12-11-7156 m:amount=299392

series e:ma9d-zcjq d:2009-03-16T00:00:00.000Z t:description="AIEA & KAPOLEI LIBRARIES - RETROFIT TO ENERGY EFFICIENT LIGHT FIXTURES (CON)" t:job_no=52-36-6456 m:amount=25800
```

## Meta Commands

```ls
metric m:amount p:integer l:Amount t:dataTypeName=money

entity e:ma9d-zcjq l:"Projects Completed" t:url=https://data.hawaii.gov/api/views/ma9d-zcjq

property e:ma9d-zcjq t:meta.view v:id=ma9d-zcjq v:averageRating=0 v:name="Projects Completed"

property e:ma9d-zcjq t:meta.view.owner v:id=ck4w-i5dk v:profileImageUrlMedium=/api/users/ck4w-i5dk/profile_images/THUMB v:profileImageUrlLarge=/api/users/ck4w-i5dk/profile_images/LARGE v:screenName=sojiri v:profileImageUrlSmall=/api/users/ck4w-i5dk/profile_images/TINY v:displayName=sojiri

property e:ma9d-zcjq t:meta.view.tableauthor v:id=ck4w-i5dk v:profileImageUrlMedium=/api/users/ck4w-i5dk/profile_images/THUMB v:profileImageUrlLarge=/api/users/ck4w-i5dk/profile_images/LARGE v:screenName=sojiri v:profileImageUrlSmall=/api/users/ck4w-i5dk/profile_images/TINY v:roleName=publisher v:displayName=sojiri
```

## Top Records

```ls
| job_no     | description                                                                      | ntp                 | amount   | completed           | 
| ========== | ================================================================================ | =================== | ======== | =================== | 
| 12-10-0319 | 919 ALA MOANA BUILDING - RENOVATION OF ROOMS 110 AND 117 FOR PSD                 | 2004-03-29T00:00:00 | 58470    | 2005-09-28T00:00:00 | 
| 12-11-7156 | AGRICULTURE AND CONSERVATION FACILITY - REROOF BUILDINGS C AND D                 | 2004-11-01T00:00:00 | 299392   | 2006-07-10T00:00:00 | 
| 52-36-6456 | AIEA & KAPOLEI LIBRARIES - RETROFIT TO ENERGY EFFICIENT LIGHT FIXTURES (CON)     | 2009-03-16T00:00:00 | 25800    | 2009-08-24T00:00:00 | 
| 12-36-6512 | AIEA PUBLIC LIBRARY - REPLACEMENT FACILITY                                       | 2012-11-26T00:00:00 | 8722544  | 2014-09-24T00:00:00 | 
| 52-36-6503 | AINA HAINA PUBLIC LIBRARY - INSTALL PHOTOVOLTAIC SYSTEM                          | 2010-12-20T00:00:00 | 588888   | 2012-06-05T00:00:00 | 
| 12-36-6497 | AINA HAINA PUBLIC LIBRARY - PARKING LOT AND SIDEWALK IMPROVEMENTS                | 2011-04-05T00:00:00 | 51756    | 2012-02-27T00:00:00 | 
| 62-36-6551 | AINA HAINA PUBLIC LIBRARY - RENOVATION OF PHOTOVOLTAIC SYSTEM                    | 2015-01-02T00:00:00 | 280000   | 2016-02-25T00:00:00 | 
| 52-36-6475 | AINA HAINA, HAWAII KAI, KAIMUKI & WAIKIKI-KAPAHULU P/L - INSTLL PROTEC WDW TINT  | 2011-02-07T00:00:00 | 41711.05 | 2011-11-25T00:00:00 | 
| 82-36-6409 | AINA HAINA, HAWAII KAI, KAIMUKI LIBRARIES - RETROFIT TO ENERGY EFFICIENT LIGHT F | 2008-09-15T00:00:00 | 59870    | 2011-04-01T00:00:00 | 
| 12-20-2576 | ALA MOANA & DIAMOND HEAD HEALTH CENTERS - AIR CONDITIONING SYSTEM IMPROVEMENTS   | 2004-08-30T00:00:00 | 706680   | 2006-05-04T00:00:00 | 
```