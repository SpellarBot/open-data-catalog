# MASTER_DATA

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/master-data-d04b2) |
| Metadata | [Link](https://data.wa.gov/api/views/5piy-sp8f) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/5piy-sp8f/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/5piy-sp8f/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | 5piy-sp8f |
| Name | MASTER_DATA |
| Attribution | DES - Enterprise Reporting Services |
| Tags | issuetrak |
| Created | 2013-07-11T18:49:57Z |
| Publication Date | 2013-07-19T17:15:38Z |

## Description

Proof of Concept

## Columns

```ls
| Included | Schema Type    | Field Name        | Name              | Data Type     | Render Type   |
| ======== | ============== | ================= | ================= | ============= | ============= |
| Yes      | series tag     | issue_number      | Issue Number      | text          | number        |
| Yes      | series tag     | subject           | Subject           | text          | text          |
| Yes      | series tag     | subtype_1         | Requestor         | text          | text          |
| Yes      | series tag     | subtype_2         | Cohort            | text          | text          |
| Yes      | series tag     | follow_up_sectors | Follow-up Sectors | text          | text          |
| Yes      | time           | entered_on        | Entered On        | calendar_date | calendar_date |
| Yes      | series tag     | enter_month       | Enter Month       | text          | text          |
| No       |                | closed_on         | Closed On         | calendar_date | calendar_date |
| Yes      | series tag     | close_month       | Close Month       | text          | text          |
| Yes      | series tag     | status            | Status            | text          | text          |
| Yes      | numeric metric | k_12              | K-12              | number        | number        |
| Yes      | numeric metric | early_learning    | Early Learning    | number        | number        |
| Yes      | numeric metric | ctc               | CTC               | number        | number        |
| Yes      | numeric metric | workforce         | Workforce         | number        | number        |
| Yes      | numeric metric | baccalaureate     | Baccalaureate     | number        | number        |
| Yes      | numeric metric | other             | Other             | number        | number        |
```

## Time Field

```ls
Value = entered_on
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = closed_on
```

## Data Commands

```ls
series e:5piy-sp8f d:2013-04-05T11:51:00.000Z t:follow_up_sectors=K-12 t:status=OPEN t:subject="Students in Foster Care" t:subtype_2=K-12 t:subtype_1="Legislator/Leg staff" t:issue_number=290 t:enter_month=04/13 m:k_12=1

series e:5piy-sp8f d:2013-04-05T12:03:00.000Z t:follow_up_sectors="Early learning, K-12, CTC. Baccalaureate, workforce and other" t:status=CLOSED t:subject="Innovative Schools" t:subtype_2=K-12 t:subtype_1="Other government entity" t:issue_number=291 t:enter_month=04/13 t:close_month=06/13 m:other=1 m:early_learning=1 m:baccalaureate=1 m:k_12=1 m:workforce=1 m:ctc=1

series e:5piy-sp8f d:2013-04-15T07:28:00.000Z t:follow_up_sectors="Early learning, K-12" t:status=OPEN t:subject="SouthShore School eval by EcoNW" t:subtype_2=K-12 t:subtype_1="School district/college/university" t:issue_number=296 t:enter_month=04/13 m:early_learning=1 m:k_12=1
```

## Meta Commands

```ls
metric m:k_12 p:integer l:K-12 t:dataTypeName=number

metric m:early_learning p:integer l:"Early Learning" t:dataTypeName=number

metric m:ctc p:integer l:CTC t:dataTypeName=number

metric m:workforce p:integer l:Workforce t:dataTypeName=number

metric m:baccalaureate p:integer l:Baccalaureate t:dataTypeName=number

metric m:other p:integer l:Other t:dataTypeName=number

entity e:5piy-sp8f l:MASTER_DATA t:attribution="DES - Enterprise Reporting Services" t:url=https://data.wa.gov/api/views/5piy-sp8f

property e:5piy-sp8f t:meta.view v:id=5piy-sp8f v:averageRating=0 v:name=MASTER_DATA v:attribution="DES - Enterprise Reporting Services"

property e:5piy-sp8f t:meta.view.owner v:id=gamp-j27n v:screenName="DFW - Gallivan, Timothy" v:displayName="DFW - Gallivan, Timothy"

property e:5piy-sp8f t:meta.view.tableauthor v:id=gamp-j27n v:screenName="DFW - Gallivan, Timothy" v:roleName=viewer v:displayName="DFW - Gallivan, Timothy"
```

## Top Records

```ls
| issue_number | subject                                       | subtype_1                          | subtype_2 | follow_up_sectors                                             | entered_on          | enter_month | closed_on           | close_month | status | k_12 | early_learning | ctc | workforce | baccalaureate | other | 
| ============ | ============================================= | ================================== | ========= | ============================================================= | =================== | =========== | =================== | =========== | ====== | ==== | ============== | === | ========= | ============= | ===== | 
| 287          | Post secondary enrollment and degrees by race | Other government entity            | CTC       | none                                                          | 2013-04-03T14:35:00 | 04/13       | 2013-06-18T15:06:00 | 06/13       | CLOSED |      |                |     |           |               |       | 
| 290          | Students in Foster Care                       | Legislator/Leg staff               | K-12      | K-12                                                          | 2013-04-05T11:51:00 | 04/13       |                     |             | OPEN   | 1    |                |     |           |               |       | 
| 291          | Innovative Schools                            | Other government entity            | K-12      | Early learning, K-12, CTC. Baccalaureate, workforce and other | 2013-04-05T12:03:00 | 04/13       | 2013-06-14T13:49:00 | 06/13       | CLOSED | 1    | 1              | 1   | 1         | 1             | 1     | 
| 296          | SouthShore School eval by EcoNW               | School district/college/university | K-12      | Early learning, K-12                                          | 2013-04-15T07:28:00 | 04/13       |                     |             | OPEN   | 1    | 1              |     |           |               |       | 
| 305          | Nav 101 outcome study                         | Private organization/citizen       | K-12      | CTC, Baccalaureate                                            | 2013-04-22T07:54:00 | 04/13       |                     |             | OPEN   |      |                | 1   |           | 1             |       | 
| 312          | Pipeline/Student demand model                 | Partner agency                     | K-12      | CTC, Baccalaureate                                            | 2013-04-30T07:26:00 | 04/13       |                     |             | OPEN   |      |                | 1   |           | 1             |       | 
| 318          | Running Start report                          | Partner agency                     | K-12      | CTC                                                           | 2013-05-01T15:47:00 | 05/13       | 2013-05-06T15:36:00 | 05/13       | CLOSED |      |                | 1   |           |               |       | 
| 319          | Secondary CTE performance report              | Partner agency                     | K-12      | CTC, Baccalaureate, Workforce                                 | 2013-05-01T16:06:00 | 05/13       | 2013-05-06T15:39:00 | 05/13       | CLOSED |      |                | 1   | 1         | 1             |       | 
| 320          | TechPrep report                               | Partner agency                     | K-12      | CTC, Baccalaureate, Workforce                                 | 2013-05-01T16:10:00 | 05/13       | 2013-05-06T15:58:00 | 05/13       | CLOSED |      |                | 1   | 1         | 1             |       | 
| 321          | CTE 5S1 measure                               | Partner agency                     | K-12      | CTC, Baccalaureate, Workforce                                 | 2013-05-01T16:11:00 | 05/13       | 2013-05-06T15:59:00 | 05/13       | CLOSED |      |                | 1   | 1         | 1             |       | 
```