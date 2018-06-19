# Total Number of High School Seniors in Missouri

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/test-data-2-678bc) |
| Metadata | [Link](https://data.mo.gov/api/views/8yaf-xv66) |
| Data: JSON | [100 Rows](https://data.mo.gov/api/views/8yaf-xv66/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.mo.gov/api/views/8yaf-xv66/rows.csv?max_rows=100) |
| Host | data.mo.gov |
| Id | 8yaf-xv66 |
| Name | Total Number of High School Seniors in Missouri |
| Category | Education |
| Tags | school |
| Created | 2014-12-05T19:26:05Z |
| Publication Date | 2017-02-17T14:48:01Z |

## Description

This dataset shows the number of seniors by school year and school.

## Columns

```ls
| Included | Schema Type    | Field Name        | Name              | Data Type     | Render Type   |
| ======== | ============== | ================= | ================= | ============= | ============= |
| Yes      | numeric metric | ncessch           | NCESSCH           | number        | text          |
| Yes      | series tag     | school_name       | School Name       | text          | text          |
| Yes      | series tag     | district          | District          | text          | text          |
| Yes      | numeric metric | school_year       | School Year       | number        | text          |
| Yes      | numeric metric | number_of_seniors | Number of Seniors | number        | text          |
| Yes      | time           | lastupdated       | lastUpdated       | calendar_date | calendar_date |
| Yes      | series tag     | recordid          | recordId          | text          | text          |
```

## Time Field

```ls
Value = lastupdated
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:8yaf-xv66 d:2015-02-05T14:42:00.000Z t:number_of_seniors=* t:school_name="FRANKLIN CO. SPECL. ED. COOP." t:district="ST. CLAIR R-XIII" t:recordid=2929100025682015 m:ncessch=292910002568 m:school_year=2015

series e:8yaf-xv66 d:2015-04-14T09:19:00.000Z t:number_of_seniors=* t:school_name="SIERRA-OSAGE TREATMENT CTR." t:district="DIVISION OF YOUTH SERVICES" t:recordid=2900009011852015 m:ncessch=290000901185 m:school_year=2015

series e:8yaf-xv66 d:2015-04-14T09:19:00.000Z t:number_of_seniors=* t:school_name="HOGAN ST REGIONAL YOUTH CTR." t:district="DIVISION OF YOUTH SERVICES" t:recordid=2900009011952015 m:ncessch=290000901195 m:school_year=2015
```

## Meta Commands

```ls
metric m:ncessch p:long l:NCESSCH d:"School identifier" t:dataTypeName=number

metric m:school_year p:integer l:"School Year" t:dataTypeName=number

entity e:8yaf-xv66 l:"Total Number of High School Seniors in Missouri" t:url=https://data.mo.gov/api/views/8yaf-xv66

property e:8yaf-xv66 t:meta.view v:id=8yaf-xv66 v:category=Education v:averageRating=0 v:name="Total Number of High School Seniors in Missouri"

property e:8yaf-xv66 t:meta.view.owner v:id=wt79-n3v6 v:screenName="Diane Prenger" v:displayName="Diane Prenger"

property e:8yaf-xv66 t:meta.view.tableauthor v:id=wt79-n3v6 v:screenName="Diane Prenger" v:roleName=editor v:displayName="Diane Prenger"
```

## Top Records

```ls
| ncessch      | school_name                    | district                   | school_year | number_of_seniors | lastupdated         | recordid         | 
| ============ | ============================== | ========================== | =========== | ================= | =================== | ================ | 
| 292910002568 | FRANKLIN CO. SPECL. ED. COOP.  | ST. CLAIR R-XIII           | 2015        | *                 | 2015-02-05T14:42:00 | 2929100025682015 | 
| 290000901185 | SIERRA-OSAGE TREATMENT CTR.    | DIVISION OF YOUTH SERVICES | 2015        | *                 | 2015-04-14T09:19:00 | 2900009011852015 | 
| 290000901195 | HOGAN ST REGIONAL YOUTH CTR.   | DIVISION OF YOUTH SERVICES | 2015        | *                 | 2015-04-14T09:19:00 | 2900009011952015 | 
| 290000901270 | NORTHWEST REG. YOUTH CTR.      | DIVISION OF YOUTH SERVICES | 2015        | *                 | 2015-04-14T09:19:00 | 2900009012702015 | 
| 290000100049 | BELLE HIGH                     | MARIES CO. R-II            | 2015        | 60                | 2015-04-14T09:19:00 | 2900001000492015 | 
| 290000201642 | SOUTH HARRISON HIGH            | SOUTH HARRISON CO. R-II    | 2015        | 55                | 2015-04-14T09:19:00 | 2900002016422015 | 
| 290000302458 | PORTAGEVILLE HIGH              | PORTAGEVILLE               | 2015        | 56                | 2015-04-14T09:19:00 | 2900003024582015 | 
| 290000401488 | CENTRAL HIGH                   | NEW MADRID CO. R-I         | 2015        | 104               | 2015-04-14T09:19:00 | 2900004014882015 | 
| 290000901145 | MONTGOMERY CITY TREATMENT CTR. | DIVISION OF YOUTH SERVICES | 2015        | *                 | 2015-04-14T09:19:00 | 2900009011452015 | 
| 290001402743 | HOGAN PREPARATORY ACADEMY      | HOGAN PREPARATORY ACADEMY  | 2015        | 68                | 2015-04-14T09:19:00 | 2900014027432015 | 
```