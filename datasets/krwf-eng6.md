# SCA Disqualified Firms

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/sca-disqualified-firms-ab124) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/krwf-eng6) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/krwf-eng6/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/krwf-eng6/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | krwf-eng6 |
| Name | SCA Disqualified Firms |
| Attribution | School Construction Authority (SCA) |
| Category | Housing & Development |
| Tags | school, construction, authority, sca, firm, company, companies, work, trade, disqualification, disqualify, disqualified, education |
| Created | 2013-04-18T15:19:03Z |
| Publication Date | 2017-04-14T19:17:35Z |

## Description

List of firms that are disqualified to work for the SCA. The file includes the term of the firms' disqualification. If the 'disqualified to date' is empty, the firm is disqualified indefinitely.

## Columns

```ls
| Included | Schema Type | Field Name             | Name                   | Data Type     | Render Type   |
| ======== | =========== | ====================== | ====================== | ============= | ============= |
| Yes      | series tag  | vendor_status          | Vendor Status          | text          | text          |
| Yes      | series tag  | vendor_name            | Vendor Name            | text          | text          |
| Yes      | time        | disqualified_from_date | Disqualified From Date | calendar_date | calendar_date |
| No       |             | disqualified_to_date   | Disqualified To Date   | calendar_date | calendar_date |
```

## Time Field

```ls
Value = disqualified_from_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = disqualified_to_date
```

## Data Commands

```ls
series e:krwf-eng6 d:2004-08-12T00:00:00.000Z t:vendor_status=Suspended t:vendor_name="2000 PAINTING, INC." m:row_number.krwf-eng6=1

series e:krwf-eng6 d:2013-03-11T00:00:00.000Z t:vendor_status=Disqualified t:vendor_name="4 J'S PLUMBING & HEATING CORP." m:row_number.krwf-eng6=2

series e:krwf-eng6 d:2004-11-04T00:00:00.000Z t:vendor_status=Suspended t:vendor_name="A & A CONSTRUCTION AND RENOVATION" m:row_number.krwf-eng6=3
```

## Meta Commands

```ls
metric m:row_number.krwf-eng6 p:long l:"Row Number"

entity e:krwf-eng6 l:"SCA Disqualified Firms" t:attribution="School Construction Authority (SCA)" t:url=https://data.cityofnewyork.us/api/views/krwf-eng6

property e:krwf-eng6 t:meta.view v:id=krwf-eng6 v:category="Housing & Development" v:attributionLink=http://www.nycsca.org/Business/GettingStarted/Pages/DisqualifiedFirms.aspx v:averageRating=0 v:name="SCA Disqualified Firms" v:attribution="School Construction Authority (SCA)"

property e:krwf-eng6 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:krwf-eng6 t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| vendor_status | vendor_name                       | disqualified_from_date | disqualified_to_date | 
| ============= | ================================= | ====================== | ==================== | 
| Suspended     | 2000 PAINTING, INC.               | 2004-08-12T00:00:00    |                      | 
| Disqualified  | 4 J'S PLUMBING & HEATING CORP.    | 2013-03-11T00:00:00    | 2017-06-27T00:00:00  | 
| Suspended     | A & A CONSTRUCTION AND RENOVATION | 2004-11-04T00:00:00    |                      | 
| Suspended     | A & L CONSTRUCTION CORP.          | 2004-05-17T00:00:00    |                      | 
| Suspended     | A & S ENTERPRISES                 | 2009-08-06T00:00:00    |                      | 
| Suspended     | A. TAHER CONTRACTING, CO., INC.   | 2000-10-12T00:00:00    |                      | 
| Disqualified  | A.J.S. PROJECT MANAGEMENT, INC.   | 2017-02-28T00:00:00    | 2021-12-29T00:00:00  | 
| Suspended     | A.K.M. GENERAL CONSTRUCTION CO.   | 2005-06-28T00:00:00    |                      | 
| Suspended     | A.S.L. ASSOCIATES, INC.           | 1996-07-01T00:00:00    |                      | 
| Suspended     | ACCESS CONSTRUCTION CORP.         | 1998-11-23T00:00:00    |                      | 
```