# Grant Information Collection Act List - FY14 From 1-1 To 3-31-14

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/grant-information-collection-act-list-fy14-from-1-1-to-3-31-14-25133) |
| Metadata | [Link](https://data.illinois.gov/api/views/nf5p-9mp6) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/nf5p-9mp6/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/nf5p-9mp6/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | nf5p-9mp6 |
| Name | Grant Information Collection Act List - FY14 From 1-1 To 3-31-14 |
| Attribution | Illinois Arts Council Agency |
| Category | Recreation |
| Tags | iac, illinois arts council, illinois arts council agency, iaca, fy14 |
| Created | 2014-04-09T20:13:51Z |
| Publication Date | 2014-04-09T20:22:12Z |

## Description

Illinois Arts Council Agency Grants in Fiscal Year 14, from January 1 to March 31.

## Columns

```ls
| Included | Schema Type    | Field Name | Name   | Data Type     | Render Type   |
| ======== | ============== | ========== | ====== | ============= | ============= |
| No       |                | fy         | FY     | number        | number        |
| Yes      | series tag     | flname     | FLName | text          | text          |
| Yes      | series tag     | zip        | ZIP    | text          | text          |
| Yes      | series tag     | title      | Title  | text          | text          |
| Yes      | numeric metric | grant      | Grant  | money         | money         |
| Yes      | time           | dvo        | Dvo    | calendar_date | calendar_date |
| No       |                | beg        | Beg    | calendar_date | calendar_date |
| No       |                | end        | End    | calendar_date | calendar_date |
```

## Time Field

```ls
Value = dvo
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = fy,beg,end
```

## Data Commands

```ls
series e:nf5p-9mp6 d:2014-02-05T00:00:00.000Z t:zip=60134-1351 t:title="for general operating support" t:flname="Illinois Brass Band Assn Inc" m:grant=1300

series e:nf5p-9mp6 d:2014-01-09T00:00:00.000Z t:zip=60625 t:title="for general operating support" t:flname="WTTW Communications Inc" m:grant=22500

series e:nf5p-9mp6 d:2014-01-09T00:00:00.000Z t:zip=60618 t:title="for general operating support" t:flname="Chicago Moving Company" m:grant=3550
```

## Meta Commands

```ls
metric m:grant p:integer l:Grant t:dataTypeName=money

entity e:nf5p-9mp6 l:"Grant Information Collection Act List - FY14 From 1-1 To 3-31-14" t:attribution="Illinois Arts Council Agency" t:url=https://data.illinois.gov/api/views/nf5p-9mp6

property e:nf5p-9mp6 t:meta.view v:id=nf5p-9mp6 v:category=Recreation v:averageRating=0 v:name="Grant Information Collection Act List - FY14 From 1-1 To 3-31-14" v:attribution="Illinois Arts Council Agency"

property e:nf5p-9mp6 t:meta.view.owner v:id=5ugp-negb v:screenName="George Tarasuk" v:displayName="George Tarasuk"

property e:nf5p-9mp6 t:meta.view.tableauthor v:id=5ugp-negb v:screenName="George Tarasuk" v:displayName="George Tarasuk"
```

## Top Records

```ls
| fy | flname                               | zip        | title                         | grant | dvo                 | beg                 | end                 | 
| == | ==================================== | ========== | ============================= | ===== | =================== | =================== | =================== | 
| 14 | Illinois Brass Band Assn Inc         | 60134-1351 | for general operating support | 1300  | 2014-02-05T00:00:00 | 2013-09-15T00:00:00 | 2014-08-31T00:00:00 | 
| 14 | WTTW Communications Inc              | 60625      | for general operating support | 22500 | 2014-01-09T00:00:00 | 2013-09-15T00:00:00 | 2014-08-31T00:00:00 | 
| 14 | Chicago Moving Company               | 60618      | for general operating support | 3550  | 2014-01-09T00:00:00 | 2013-09-15T00:00:00 | 2014-08-31T00:00:00 | 
| 14 | Looking Glass Playhouse              | 62254      | for general operating support | 2025  | 2014-01-29T00:00:00 | 2013-09-15T00:00:00 | 2014-08-31T00:00:00 | 
| 14 | Prairie Players Civic Theatre        | 61402      | for general operating support | 2025  | 2014-01-09T00:00:00 | 2013-09-15T00:00:00 | 2014-08-31T00:00:00 | 
| 14 | Red Rose Children's Choir of Lake Co | 60030      | for general operating support | 3515  | 2014-01-09T00:00:00 | 2013-09-15T00:00:00 | 2014-08-31T00:00:00 | 
| 14 | Literature for All of Us             | 60201-3098 | for general operating support | 11050 | 2014-02-04T00:00:00 | 2013-09-15T00:00:00 | 2014-08-31T00:00:00 | 
| 14 | HumanThread Foundation               | 60609-1305 | for general operating support | 875   | 2014-01-29T00:00:00 | 2013-09-15T00:00:00 | 2014-08-31T00:00:00 | 
| 14 | The Classical Symphony Orchestra     | 60604-2316 | for general operating support | 5050  | 2014-01-09T00:00:00 | 2013-09-15T00:00:00 | 2014-08-31T00:00:00 | 
| 14 | Ballet Chicago Company               | 60602      | for general operating support | 11050 | 2014-01-09T00:00:00 | 2013-09-15T00:00:00 | 2014-08-31T00:00:00 | 
```