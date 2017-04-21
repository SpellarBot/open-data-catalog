# ADR Calendar

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/adr-calendar-df03b) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/u5eb-c9aj) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/u5eb-c9aj/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/u5eb-c9aj/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | u5eb-c9aj |
| Name | ADR Calendar |
| Attribution | King County ADR |
| Category | Operations |
| Tags | training, calendar, alternative, dispute, resolution, adr, ilcrg |
| Created | 2013-03-05T16:35:06Z |
| Publication Date | 2015-09-11T17:33:25Z |

## Description

Calendar of trainings and other events for the King County Alternative Dispute Resolution (ADR) program.

## Columns

```ls
| Included | Schema Type | Field Name | Name      | Data Type     | Render Type   |
| ======== | =========== | ========== | ========= | ============= | ============= |
| Yes      | time        | startdate  | StartDate | calendar_date | calendar_date |
| No       |             | enddate    | EndDate   | calendar_date | calendar_date |
| Yes      | series tag  | title      | Title     | text          | text          |
| Yes      | series tag  | location   | Location  | text          | text          |
| No       |             | address    | Address   | text          | text          |
| Yes      | series tag  | city       | City      | text          | text          |
| Yes      | series tag  | state      | State     | text          | text          |
| Yes      | series tag  | cost       | Cost      | text          | text          |
| Yes      | series tag  | details    | Details   | text          | text          |
```

## Time Field

```ls
Value = startdate
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = enddate,address
```

## Data Commands

```ls
series e:u5eb-c9aj d:2013-01-28T00:00:00.000Z t:title="Basic Mediation Training" t:details="This six-day (48 hour) classroom training will use various techniques and trainers to convey the mediation process and structure used by the ILCRG. The instructors teach an ""interest-based"" mediation model with an emphasis on face-to-face communication and the self-determination of the parties." t:location="NOAA Facility" t:state=WA t:cost=$500 t:city=Seattle m:row_number.u5eb-c9aj=1

series e:u5eb-c9aj d:2013-03-13T08:30:00.000Z t:title="Labor Basics" t:location="King County Chinook Building" t:state=WA t:city=Seattle m:row_number.u5eb-c9aj=2

series e:u5eb-c9aj d:2013-03-13T13:00:00.000Z t:title="Land Use Mediation" t:location="King County Chinook Building" t:state=WA t:city=Seattle m:row_number.u5eb-c9aj=3
```

## Meta Commands

```ls
metric m:row_number.u5eb-c9aj p:long l:"Row Number"

entity e:u5eb-c9aj l:"ADR Calendar" t:attribution="King County ADR" t:url=https://data.kingcounty.gov/api/views/u5eb-c9aj

property e:u5eb-c9aj t:meta.view v:id=u5eb-c9aj v:category=Operations v:attributionLink=http://www.kingcounty.gov/employees/adr.aspx v:averageRating=0 v:name="ADR Calendar" v:attribution="King County ADR"

property e:u5eb-c9aj t:meta.view.license v:name="Public Domain"

property e:u5eb-c9aj t:meta.view.owner v:id=ph9f-eu4i v:screenName=Cameron v:displayName=Cameron

property e:u5eb-c9aj t:meta.view.tableauthor v:id=ph9f-eu4i v:screenName=Cameron v:roleName=publisher v:displayName=Cameron
```

## Top Records

```ls
| startdate           | enddate             | title                    | location                     | address                   | city    | state | cost | details                                                                                                                                                                                                                                                                                                 | 
| =================== | =================== | ======================== | ============================ | ========================= | ======= | ===== | ==== | ======================================================================================================================================================================================================================================================================================================= | 
| 2013-01-28T00:00:00 | 2013-02-05T00:00:00 | Basic Mediation Training | NOAA Facility                | 7600 Sandpoint Way NE     | Seattle | WA    | $500 | This six-day (48 hour) classroom training will use various techniques and trainers to convey the mediation process and structure used by the ILCRG. The instructors teach an "interest-based" mediation model with an emphasis on face-to-face communication and the self-determination of the parties. | 
| 2013-03-13T08:30:00 | 2013-03-13T12:00:00 | Labor Basics             | King County Chinook Building | 401 Fifth Ave., Suite 123 | Seattle | WA    |      |                                                                                                                                                                                                                                                                                                         | 
| 2013-03-13T13:00:00 | 2013-03-13T15:00:00 | Land Use Mediation       | King County Chinook Building | 401 Fifth Ave., Suite 123 | Seattle | WA    |      |                                                                                                                                                                                                                                                                                                         | 
| 2013-04-10T09:00:00 | 2013-04-10T12:00:00 | Negotiation Phase        | King County Chinook Building | 401 Fifth Ave., Suite 123 | Seattle | WA    |      |                                                                                                                                                                                                                                                                                                         | 
| 2013-04-10T13:00:00 | 2013-04-10T15:00:00 | Pre-Mediation Caucus     | King County Chinook Building | 401 Fifth Ave., Suite 123 | Seattle | WA    |      |                                                                                                                                                                                                                                                                                                         | 
| 2013-06-14T09:00:00 | 2013-06-14T12:00:00 | Active Listening         | King County Chinook Building | 401 Fifth Ave., Suite 123 | Seattle | WA    |      |                                                                                                                                                                                                                                                                                                         | 
| 2013-06-14T13:00:00 | 2013-06-14T15:00:00 | TBA                      | King County Chinook Building | 401 Fifth Ave., Suite 123 | Seattle | WA    |      |                                                                                                                                                                                                                                                                                                         | 
| 2013-07-24T08:30:00 | 2013-07-24T16:30:00 | ESJ/Cross-Cultural       | King County Chinook Building | 401 Fifth Ave., Suite 123 | Seattle | WA    |      |                                                                                                                                                                                                                                                                                                         | 
| 2013-09-11T09:00:00 | 2013-09-11T12:00:00 | Co-Mediation             | King County Chinook Building | 401 Fifth Ave., Suite 123 | Seattle | WA    |      |                                                                                                                                                                                                                                                                                                         | 
| 2013-09-11T13:00:00 | 2013-09-11T15:00:00 | TBA                      | King County Chinook Building | 401 Fifth Ave., Suite 123 | Seattle | WA    |      |                                                                                                                                                                                                                                                                                                         | 
```