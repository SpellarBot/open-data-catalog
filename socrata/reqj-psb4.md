# SSMMA Sauk Village FOIA Log

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ssmma-sauk-village-foia-log-a2433) |
| Metadata | [Link](https://data.illinois.gov/api/views/reqj-psb4) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/reqj-psb4/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/reqj-psb4/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | reqj-psb4 |
| Name | SSMMA Sauk Village FOIA Log |
| Attribution | South Suburban Mayors and Managers Association |
| Category | Municipality |
| Tags | freedom of information, foia, general government, administration |
| Created | 2012-11-27T18:04:30Z |
| Publication Date | 2012-11-27T19:06:54Z |

## Description

This dataset is a freedom of information request log for the Village of Sauk Village for the 2012 calendar year.

## Columns

```ls
| Included | Schema Type | Field Name       | Name             | Data Type     | Render Type   |
| ======== | =========== | ================ | ================ | ============= | ============= |
| Yes      | series tag  | number           | NUMBER           | text          | text          |
| Yes      | time        | date_received    | DATE RECEIVED    | calendar_date | calendar_date |
| Yes      | series tag  | requested_by     | REQUESTED BY     | text          | text          |
| Yes      | series tag  | assigned_to      | ASSIGNED TO      | text          | text          |
| No       |             | date_completed   | DATE COMPLETED   | calendar_date | calendar_date |
| Yes      | series tag  | method           | METHOD           | text          | text          |
| Yes      | series tag  | foia_description | FOIA DESCRIPTION | text          | text          |
```

## Time Field

```ls
Value = date_received
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = date_completed
```

## Data Commands

```ls
series e:reqj-psb4 d:2012-01-03T00:00:00.000Z t:assigned_to="Sandy Dietrich" t:requested_by="Bernice Brewer" t:method=emailed t:number=2012-1-3 t:foia_description="Vendor History Aurora water products" m:row_number.reqj-psb4=1

series e:reqj-psb4 d:2012-01-09T00:00:00.000Z t:assigned_to="Mohan Rao" t:requested_by="Bernice Brewer" t:method=emailed t:number=2012-1-9 t:foia_description="Debt Service for maint of wells infrastructure 2006-2011" m:row_number.reqj-psb4=2

series e:reqj-psb4 d:2012-01-09T00:00:00.000Z t:assigned_to="Tom Kelly HUB" t:requested_by="Bernice Brewer" t:method=emailed t:number="2012-1-9 #2" t:foia_description="Lawsuits against Village 1-2011-Present amount paid and nature" m:row_number.reqj-psb4=3
```

## Meta Commands

```ls
metric m:row_number.reqj-psb4 p:long l:"Row Number"

entity e:reqj-psb4 l:"SSMMA Sauk Village FOIA Log" t:attribution="South Suburban Mayors and Managers Association" t:url=https://data.illinois.gov/api/views/reqj-psb4

property e:reqj-psb4 t:meta.view v:id=reqj-psb4 v:category=Municipality v:attributionLink=http://www.ssmma.org v:averageRating=0 v:name="SSMMA Sauk Village FOIA Log" v:attribution="South Suburban Mayors and Managers Association"

property e:reqj-psb4 t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:reqj-psb4 t:meta.view.owner v:id=p88s-rkzf v:profileImageUrlMedium=/api/users/p88s-rkzf/profile_images/THUMB v:profileImageUrlLarge=/api/users/p88s-rkzf/profile_images/LARGE v:screenName=mrizzitiello v:profileImageUrlSmall=/api/users/p88s-rkzf/profile_images/TINY v:displayName=mrizzitiello

property e:reqj-psb4 t:meta.view.tableauthor v:id=74c3-ka9x v:profileImageUrlMedium=/api/users/74c3-ka9x/profile_images/THUMB v:profileImageUrlLarge=/api/users/74c3-ka9x/profile_images/LARGE v:screenName="Rey de Castro" v:profileImageUrlSmall=/api/users/74c3-ka9x/profile_images/TINY v:roleName=publisher v:displayName="Rey de Castro"
```

## Top Records

```ls
| number       | date_received       | requested_by      | assigned_to     | date_completed      | method                          | foia_description                                                    | 
| ============ | =================== | ================= | =============== | =================== | =============================== | =================================================================== | 
| 2012-1-3     | 2012-01-03T00:00:00 | Bernice Brewer    | Sandy Dietrich  | 2012-01-03T00:00:00 | emailed                         | Vendor History Aurora water products                                | 
| 2012-1-9     | 2012-01-09T00:00:00 | Bernice Brewer    | Mohan Rao       | 2012-01-25T00:00:00 | emailed                         | Debt Service for maint of wells infrastructure 2006-2011            | 
| 2012-1-9 #2  | 2012-01-09T00:00:00 | Bernice Brewer    | Tom Kelly HUB   | 2012-03-13T00:00:00 | emailed                         | Lawsuits against Village 1-2011-Present amount paid and nature      | 
| 2012-1-10    | 2012-01-10T00:00:00 | Bernice Brewer    | Sandy Dietrich  | 2012-01-10T00:00:00 | emailed                         | Vedor update for Round the Clock Jan 2011-Dec 2011                  | 
| 2012-1-12 #1 | 2012-01-12T00:00:00 | Joe Wiszowaty     | Clerk           | 2012-01-17T00:00:00 | emailed                         | Employment agreement for Village Manager                            | 
| 2012-1-12 #2 | 2012-01-12T00:00:00 | Joe Wiszowaty     | Sherry Jasinski | 2012-01-12T00:00:00 | emailed                         | Policy take home vehicles, outside employment,Job Desp Police Chief | 
| 2012-1-13    | 2012-01-13T00:00:00 | Katie Hufnagl     | Sandy Dietrich  | 2012-01-13T00:00:00 | faxed/left copy at front window | Requesting certain start date for employee/dispatch                 | 
| 2012-1-17    | 2012-01-17T00:00:00 | Joseph Ryan       | Mohan Rao       | 2012-01-17T00:00:00 | emailed                         | Last two financial audits and last budget                           | 
| 2012-1-20    | 2012-01-20T00:00:00 | Rimkus Consulting | Fire Department | 2012-01-23T00:00:00 | emailed                         | Report/photos for fire at 22160 Clyde                               | 
| 2012-1-20 #2 | 2012-01-20T00:00:00 | Kevin Zarlengo    | Sandy Dietrich  | 2012-01-23T00:00:00 | emailed                         | Lease agreements for copying and printing equipment                 | 
```